# Домашнее задание к занятию 8.03. Что такое DevOps. СI/СD - Качан Олег
---
## Задание 1.

Что нужно сделать:

Установите себе jenkins по инструкции из лекции или любым другим способом из официальной документации. Использовать Docker в этом задании нежелательно.
Установите на машину с jenkins golang.
Используя свой аккаунт на GitHub, сделайте себе форк репозитория. В этом же репозитории находится дополнительный материал для выполнения ДЗ.
Создайте в jenkins Freestyle Project, подключите получившийся репозиторий к нему и произведите запуск тестов и сборку проекта go test . и docker build ..
В качестве ответа пришлите скриншоты с настройками проекта и результатами выполнения сборки.

<img width="1554" alt="Screenshot 2023-07-01 at 22 35 56" src="https://github.com/otuzi/8-03-hw/assets/61628386/71dbc2da-10f7-425c-aa60-5457a15263b5">
<img width="1592" alt="Screenshot 2023-07-01 at 22 36 20" src="https://github.com/otuzi/8-03-hw/assets/61628386/9ca03af0-b53e-45f5-bda0-b414a726fadc">
<img width="1619" alt="Screenshot 2023-07-01 at 22 36 33" src="https://github.com/otuzi/8-03-hw/assets/61628386/64205acd-3db7-4266-b550-66ad75fdf12b">
<img width="1573" alt="Screenshot 2023-07-01 at 22 36 47" src="https://github.com/otuzi/8-03-hw/assets/61628386/d2a559aa-1526-4814-8aba-8c885c6dcd0a">
<img width="1588" alt="Screenshot 2023-07-01 at 22 36 59" src="https://github.com/otuzi/8-03-hw/assets/61628386/0f5aec10-f759-4b6b-bdde-7b3a9175b883">

## результат сборки:
<img width="1321" alt="Screenshot 2023-07-01 at 22 38 13" src="https://github.com/otuzi/8-03-hw/assets/61628386/e5cb2d6d-ebf3-45b4-b5cf-2cc87387d195">




---
## Задание 2.

### Что нужно сделать:

1. Создайте новый проект pipeline.
2. Перепишите сборку из задания 1 на declarative в виде кода.
В качестве ответа пришлите скриншоты с настройками проекта и результатами выполнения сборки.

<img width="1645" alt="Screenshot 2023-07-01 at 22 55 00" src="https://github.com/otuzi/8-03-hw/assets/61628386/b6162306-40aa-4044-9f0f-9d7a6f0ae791">
<img width="1378" alt="Screenshot 2023-07-01 at 22 54 31" src="https://github.com/otuzi/8-03-hw/assets/61628386/294a2ec2-c18e-4d8d-9379-1a34fb24719c">




---
## Задание 3.

### Что нужно сделать:

1. Установите на машину Nexus.
2. Создайте raw-hosted репозиторий.
3. Измените pipeline так, чтобы вместо Docker-образа собирался бинарный go-файл. Команду можно скопировать из Dockerfile.
4. Загрузите файл в репозиторий с помощью jenkins.
В качестве ответа пришлите скриншоты с настройками проекта и результатами выполнения сборки.

<img width="1415" alt="Screenshot 2023-07-01 at 23 03 24" src="https://github.com/otuzi/8-03-hw/assets/61628386/d108da70-9f1f-4cb2-81e8-2eeab6a5e682">
<img width="1045" alt="Screenshot 2023-07-01 at 23 04 06" src="https://github.com/otuzi/8-03-hw/assets/61628386/1b3d359f-b066-4453-9e9f-60f1e48bf5e5">


