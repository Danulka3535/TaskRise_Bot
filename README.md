# KoopAttendanceBot 🤖

### **Username бота: @GameDigest_Bot**                                 *(тестовое название)*

**Бот для учета посещаемости учащихся**  
[![Python](https://img.shields.io/badge/Python-3.9%2B-blue)](https://www.python.org/)
[![Aiogram](https://img.shields.io/badge/Aiogram-2.x-green)](https://docs.aiogram.dev/)
[![MongoDB](https://img.shields.io/badge/MongoDB-5.0%2B-brightgreen)](https://www.mongodb.com/)

Бот помогает преподавателям и администраторам удобно вести учет посещаемости учащихся, отправлять данные коллегам и получать подтверждение операций.

---

## 🌟 Основные функции
- **Добавление учащихся**: Ввод ФИО учеников с возможностью продолжить или завершить ввод.
- **Отправка данных**: Выбор получателя и отправка данных после его подтверждения.
- **Интерактивное меню**: Удобные кнопки для быстрого взаимодействия.
- **Безопасность**: Данные хранятся в MongoDB с защитой от дублирования.

---

## 🚀 Быстрый старт
### Требования
- **Python 3.9+**
- **MongoDB (локально или облачная версия)**
- **Токен Telegram-бота ([@BotFather](https://t.me/BotFather))**

### Установка
1. **Клонируйте репозиторий:**
   ```bash
   git clone https://github.com/ваш-username/AttendanceTrackerBot.git
   cd AttendanceTrackerBot
## **Установите зависимости:**
 
Copy
pip install -r requirements.txt

## **Настройте подключение к MongoDB в database.py:**
 
python
Copy
mongo_client = MongoClient("mongodb://localhost:27017/")  # Ваш URI

## **Укажите токен бота в config.py:**
python
Copy
BOT_TOKEN = "ваш_токен"

### 🖥 Использование
**Начало работы:**
**Отправьте команду** */start боту.*
**Стартовое меню**

**Добавление учащихся:**

**1. Введите ФИО ученика** *(например, "Иванов Иван Иванович").*

**2. Выберите** *"Добавить"* **или** *"Завершить"*.
**Добавление ученика**

**Отправка данных:**

**3. Укажите username получателя** *(например, @colleague).*

**Получатель подтвердит или отклонит запрос.**

**После подтверждения данные автоматически отправятся.
Отправка данных**

# 🛠 Технологии
- **Python: Основной язык разработки.**

- **Aiogram: Асинхронный фреймворк для Telegram-ботов.**

- **MongoDB: Хранение данных о пользователях и операциях.**

- **Docker: Опционально для развертывания (см. docker-compose.yml).**

# 📜 Лицензия
- **Проект распространяется под лицензией MIT.**
- **Подробнее см. LICENSE.**

# 📞 Контакты
- **Авторы: Лесников Евгений, Даниил Касаткин.**
- **Email: ----**
- **Telegram: @Rengoku_crd**

# ✨ Присоединяйтесь к разработке!
**PR и идеи приветствуются. Давайте сделаем образование удобнее вместе!**
