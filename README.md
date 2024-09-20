## Лабораторная работа 1

1. Открываем терминал и создаем новый файл `script.bash`

```bash
touch script.bash
```

2. Открываем новый файл в текстовом редакторе `gedit`, выполняя в терминале

```bash
gedit script.bash
```
<img width="321" alt="image" src="https://github.com/user-attachments/assets/c5b8d7bc-c45f-421a-bad0-381b8450ece7">


3. В открывшемся файле пишем скрипт

```bash
#!/bin/bash

echo "Welcome to ITMO University"
```
<img width="394" alt="image" src="https://github.com/user-attachments/assets/10259d76-a271-4da5-94c1-98c8fc76852b">

4. Сохраняем и закрываем файл
5. Запускаем bash-скрипт, выполняя в терминале

```bash
bash script.bash
```
<img width="326" alt="image" src="https://github.com/user-attachments/assets/3beb4ff7-2c46-4825-998c-62e49979356d">

6. Все получилось!

### Задача
1. Для выполнения задачи ищем дополнительные источники в интернете
<img width="545" alt="image" src="https://github.com/user-attachments/assets/eefd4a21-c515-4ddf-ba33-4ba51d7cf5cc">


2. Открываем файл script.bash и меняем скрипт, добавляя переменную

```bash
#!/bin/bash

echo "Welcome, "$*"
```
 <img width="398" alt="image" src="https://github.com/user-attachments/assets/afc37c1d-0c0b-4692-b3f2-e41db5a8f4b1">


3. Сохраняем и закрываем файл

4. В терминале запускаем файл и проверяем
<img width="325" alt="image" src="https://github.com/user-attachments/assets/7a340933-0cd7-4fdb-9782-01bff8ed7511">
