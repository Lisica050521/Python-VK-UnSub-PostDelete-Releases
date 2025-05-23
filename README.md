### 🧹 VK UnSub & PostDelete | Удаление постов и отписка подписчиков из групп и сообществ

## Для чего нужен данный проект
Раньше я активно вела несколько торговых сообществ ВК, но после смены деятельности столкнулась с проблемой: группы нельзя просто взять и удалить. Нужно:  
• Очистить все посты (иногда тысячи! У меня были посты с 2012 года)  
• Удалить подписчиков (800, 3000 участников и т.д в каждой группе)  
• Удалить медиафайлы  

Вручную — это месяцы работы. Платными сервисами я не хотела пользоваться, поэтому создала данный проект, успешно очистила и удалила свои группы ВКонтакте. 

## 🌟 Возможности

- 🗑️ Массовое удаление постов со стены сообщества (100 в час)
- 👥 Удаление подписчиков (до 1000 в день)
- ⏱️ Настраиваемые интервалы между запросами
- 🔒 Безопасное хранение токена в конфигурации
- 🖥️ Удобный графический интерфейс

## 🛠️ Установка и запуск

### Требования:
- Активный токен VK
- ID группы
- Не требует установки

## 🚀 Инструкция по использованию

**1. Скачайте файл в любое место и запустите**  

<a href="https://github.com/Lisica050521/Python-VK-UnSub-PostDelete-Releases/raw/master/VK%20UnSub%20%26%20PostDelete.exe" download>
  <button>Скачать VK UnSub & PostDelete.exe</button>
</a>
<br><br>

**2. Введите токен**  
Пример формата:
```
vk1.a.7hR5sD9kL2pX3wE1qC8zY4xU6vB0nM9jH5gT3fK8dS2lP4rA9wQ5eJ7iV1oN6mZ9cX2yU4bR0tD5fG8hS3jK6lL9pO4aQ7wE2iI5uY0
   ```
**2. Введите ID группы**  
   Пример:
   ```
   152273091
   ```
   → Нажмите кнопку **«Сохранить»**  

**3. Управление процессом**  

   🟢 **Старт** - для запуска очистки  
   🔴 **Стоп** - если хотите остановить работу приложения

**4. После запуска приложения создадутся два файла**  
с конфигурациями и лимитами. Не удаляйте их до завершения работы приложения. В данных файлах настройки и лимиты, которые должны быть соблюдены во избежание блокировки Вашего аккаунта.

## 🔐 Как получить токен
1. Перейдите по ссылке:
```
https://oauth.vk.com/authorize?client_id=6121396&scope=groups,wall,manage&response_type=token
```
2. Скопируйте токен из адресной строки (часть после `access_token=` до `&expires_in`)

## 📌 Как найти ID группы
1. Откройте любое фото группы
2. В URL найдите `photo-152273091_...` → ID группы: `-152273091`

## 📌 Как отозвать токен ВКонтакте (2025)
Через завершение всех сеансов:  
Зайдите в Настройки ВК → Управление аккаунтом → Безопасность  → 
Список устройств и история активности → выйти на других устройствах.  
В истории активности → «Завершить все сеансы» 
Все Ваши токены будут аннулированы!

## 🖼️ Интерфейс
![Интерфейс](https://raw.githubusercontent.com/Lisica050521/Python-VK-UnSub-PostDelete/master/images/interface.png)

## 🖼️ Работа с лимитами наглядно
![Интерфейс](https://raw.githubusercontent.com/Lisica050521/Python-VK-UnSub-PostDelete/master/images/limits.png)

## 🖼️ Начало работы приложения (дата и количество подписчиков, наличие постов)

![Интерфейс](images/start_14.04.25.png)  

## 🖼️ Конец работы приложения (дата и количество подписчиков, наличие постов)

![Интерфейс](images/end_17.04.25.png) 

## ⚠️ Ограничения на один аккаунт
- Не более 1000 подписчиков в день
- Не более 100 постов в час
- Задержка: 2 секунды

## Расширю функционал: 
Напишите Ваши вопросы мне в телеграм: @lisica_2023  
Поддержать проект: https://donate.stream/donate_67fa327209b19