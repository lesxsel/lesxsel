# lesxsel

[![React](https://img.shields.io/badge/React-%2320232a.svg?logo=react&logoColor=%2361DAFB)](#) [![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=fff)](#) SQLite [![SQLite](https://img.shields.io/badge/SQLite-%2307405e.svg?logo=sqlite&logoColor=white)](#)

## 🛠️ Технический стек (Tech Stack)

*   **Языки**: JavaScript, Python 3.12
*   **Фронтенд**: React.js, Vite, Axios, HTML5, CSS3 (Flexbox, Grid)
*   **Бэкенд & API**: FastAPI, Uvicorn, Requests
*   **Базы данных**: SQLite3
*   **Инструменты**: Git, GitHub, Telegram Bot API

---

## 🚀 Разработанные проекты (Projects)

### [shohle-website](https://github.com) — Fullstack веб-каталог продукции
Приложение для расчета стоимости солнцезащитных систем и управления контентом.

*   **Реализованный функционал**:
    *   Двухуровневый адаптивный каталог с фильтрацией по папкам-категориям.
    *   Калькулятор стоимости изделий на основе вводимых габаритов (см) и кода ткани.
    *   Автоподстановка (autocomplete) артикулов с валидацией наличия номенклатуры в базе данных.
    *   Прямой перенос выбранного артикула из карточки товара в форму расчета цены.
    *   Адаптивная медиагалерея выполненных работ с полноэкранным просмотром изображений.
    *   Панель администратора (CMS) под паролем для добавления/удаления материалов каталога и фото.
    *   Автоматическое удаление медиафайлов с жесткого диска сервера при очистке позиций в БД.
    *   Сбор лидов (габариты, цена, номер телефона, адрес) и отправка Markdown-сообщений в Telegram.

### 📐 Схема движения данных (Data Flow)
```text
[React Client] ➔ (Axios POST) ➔ [FastAPI Server] ➔ [SQLite3 Database]
                                       │
                                (Requests POST)
                                       ▼
                             [Telegram Bot API] ➔ [Смартфон Мастера]
```


## 📫 Контакты
*   **Email**: shohle_jalyuz@mail.ru
