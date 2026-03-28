# CronVsSystemd

## Что такое Cron?

Cron — это программа, которая работает в фоне и проверяет каждую минуту: "Не пора ли запустить какую-нибудь задачу?"

Представьте, что вы хотите:

1. Каждое утро в 9:00 отправлять отчёт

2. Каждый час проверять, работает ли сайт

3. Каждую пятницу делать резервную копию

Cron умеет всё это автоматически.

## Что такое Systemd?

Systemd — это более современная система, которая управляет всем в Linux. Она умеет:

1. Запускать программы при старте компьютера

2. Следить, чтобы программы не падали

3. Планировать задачи (как Cron, но мощнее)

## Cron

### Создаем папку для работы с Cron

<img width="415" height="66" alt="image" src="https://github.com/user-attachments/assets/a2b1a9a8-9b06-4b85-bf56-4afb0ce1d5d7" />

### Создаём скрипт, который будет отправлять запрос

<img width="464" height="20" alt="image" src="https://github.com/user-attachments/assets/3c4aaf0f-5cea-45be-a932-19d9659af3de" />

---
<img width="706" height="360" alt="image" src="https://github.com/user-attachments/assets/91bd6228-f0ea-403b-9d84-a4143a9b3149" />

###  Делаем скрипт исполняемым

<img width="495" height="16" alt="image" src="https://github.com/user-attachments/assets/585bc6c9-92b6-4e5e-84af-c50e83d467cc" />

### Тестируем скрипт

<img width="710" height="66" alt="image" src="https://github.com/user-attachments/assets/7c38b083-2a67-4d4f-8a94-703cb6798d45" />

### Добавляем задачу в Cron
<img width="467" height="142" alt="image" src="https://github.com/user-attachments/assets/a2120a06-f4c4-4fad-9a68-bd2705cdbd69" />

---
<img width="581" height="391" alt="image" src="https://github.com/user-attachments/assets/7b0938b1-cd27-4bba-b910-16e363ec93e0" />


### Проверяем, что задача добавилась

<img width="517" height="387" alt="image" src="https://github.com/user-attachments/assets/f0597931-ed17-4f9d-8f23-d63cd07895b3" />


### проверяем результат

<img width="711" height="97" alt="image" src="https://github.com/user-attachments/assets/45e6b052-3978-45ac-a389-36e3f66c65b5" />

## Systemd

### Создаём скрипт
---

<img width="526" height="82" alt="image" src="https://github.com/user-attachments/assets/4ebc56f8-99e2-41a3-ac40-f205176dbb2d" />
---


<img width="671" height="405" alt="image" src="https://github.com/user-attachments/assets/d3c1db88-a617-475f-be22-e0a5a67efb57" />




