# Mashku Portfolio

Минималистичный сайт-портфолио UX дизайнера с подробными кейс-стади проектов.

## 🛠 Технологии

- HTML5
- SCSS для стилей
- JavaScript (ES6+)
- Vite для сборки и разработки
- GitHub Pages для хостинга

## 🚀 Начало работы

### Предварительные требования

- Node.js 18+ и npm

### Установка

1. Клонируйте репозиторий:
```bash
git clone https://github.com/username/mashku-portfolio.git
cd mashku-portfolio
```

2. Установите зависимости:
```bash
npm install
```

### Разработка

Запустите сервер разработки:
```bash
npm run dev
```

Сайт будет доступен по адресу `http://localhost:3000`

## 📦 Сборка

Для продакшн сборки выполните:
```bash
npm run build
```

Результат сборки будет в директории `dist/`

## 🚀 Деплой

Для деплоя на GitHub Pages:
```bash
npm run deploy
```

## 📁 Структура проекта

```
mashku-portfolio/
├── src/                  # Исходный код
│   ├── assets/          # Изображения и другие ресурсы
│   ├── styles/          # SCSS стили
│   ├── scripts/         # JavaScript
│   ├── projects/        # HTML страницы проектов
│   └── index.html       # Главная страница
├── package.json         # Зависимости и скрипты
└── vite.config.js       # Конфигурация Vite
```

## 🎨 Добавление контента

### Добавление нового проекта

1. Создайте HTML файл в `src/projects/`
2. Добавьте информацию о проекте в `src/scripts/main.js`
3. Добавьте изображения в `src/assets/images/`

### Редактирование стилей

- Основные переменные: `src/styles/_variables.scss`
- Миксины: `src/styles/_mixins.scss`
- Стили компонентов: соответствующие файлы в `src/styles/`

## 📝 Лицензия

MIT License - подробности в файле LICENSE

## 👤 Автор

Mashku - UX Designer
