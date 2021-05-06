# lab1
♥♥♥МІНІСТЕРСТВО ОСВІТИ І НАУКИ УКРАЇНИ

Національний аерокосмічний університет ім. М. Є. Жуковського «Харківський авіаційний інститут»

Факультет «Радіоелектроніки, комп’ютерних систем та інфокомунікацій» Кафедра «Аерокосмічних радіоелектронних систем»

Лабораторна робота №1

з дисципліни «Інформаційно-комунікаційні мережі »

на тему: «Основи роботи з Git»

Виконав: студент 4 курсу групи № 536-ст напряму підготовки (спеціальності) 172 «Телекомунікації та радіотехніка» Шевцов В.В

Прийняв: ас. каф. 501

Перетятько М. С.

Національна шкала:

Кількість балів:

Оцінка: ECTS

Харків 2021

Ціль роботи: Навчитися створювати репозиторії на GitHub, працювати з ssh ключами, оформити профіль.

ХІД РОБОТИ

1)Створили обліковий запис GitHub
![image](https://user-images.githubusercontent.com/79759252/117300469-3e5a0300-ae82-11eb-94e9-0d0f9b3db53f.png)
Рисунок 1 – Обліковий запис

\2) Встановили CHOCOLATEY:

запустили powershell від імені адміністратора
![image](https://user-images.githubusercontent.com/79759252/117300633-6cd7de00-ae82-11eb-9393-b0b9d2b7c976.png)
Рисунок 2 – Запуск powershell

виконали команду:

Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))

3)Встановили git на ваш комп'ютер за допомогою Chocolatey:

choco install git -y
![image](https://user-images.githubusercontent.com/79759252/117300771-90028d80-ae82-11eb-93b5-f995bd5191fa.png)
Рисунок 3 – Встановлення git

4)Налаштували свій git:

git config --global user.name "Shevon4ik"

git config --global user.email Shevon4ik@gmail.com

5)Згенерували новий SSH ключ:

ssh-keygen -t ed25519 -C "Shevon4ik@gmail.com"

6)Додайте ключ до облікового запису Github:
![image](https://user-images.githubusercontent.com/79759252/117301069-ea9be980-ae82-11eb-8346-ab597b88fa43.png)
Рисунок 4 – Додання ключа до Github

\7) Створили новий репозиторій і написали про себе
![image](https://user-images.githubusercontent.com/79759252/117301152-030c0400-ae83-11eb-8208-34ee070d275d.png)
Рисунок 5 – Редагування файлу README.md

\8) Завантажили опис профілю:

git add .

git commit -m "Add your comment"

git push

ВИСНОВКИ

В данній лабораторній роботі було виконано маніпуляції з git, а саме ми навчилися створювати обліковий запис на GitHub. Навчився комітить і пушить командами git commit, git push. Також встановили CHOCOLATEY і встановили git. Навчилися генерувати ключ SSH. Заповнював та редагував опис свого профілю і завантижив його на Git.
