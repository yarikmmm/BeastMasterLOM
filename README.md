# BeastMasterLOM 🍄
> Мастер зверей для Legend of Mushrooms - современный веб-сайт с трендовым дизайном

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live-brightgreen)](https://yarikmmm.github.io/BeastMasterLOM)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Node.js](https://img.shields.io/badge/Node.js-18+-green.svg)](https://nodejs.org/)

## 🚀 Особенности

- ✨ **Современный дизайн** - Трендовые градиенты, анимации и эффекты
- 📱 **Адаптивная верстка** - Отлично работает на всех устройствах
- ⚡ **Быстрая загрузка** - Оптимизированный код и ресурсы
- 🎨 **Интерактивность** - Плавные анимации и эффекты при наведении
- 🌟 **Готов к деплою** - Настроен для GitHub Pages

## 🛠 Технологии

- **HTML5** - Семантическая разметка
- **CSS3** - Современные стили с CSS Grid и Flexbox
- **JavaScript (ES6+)** - Интерактивность и анимации
- **Font Awesome** - Иконки
- **Google Fonts** - Шрифт Inter

## 📦 Установка и запуск

### Локальная разработка

1. **Клонируйте репозиторий:**
   ```bash
   git clone https://github.com/yarikmmm/BeastMasterLOM.git
   cd BeastMasterLOM
   ```

2. **Установите зависимости:**
   ```bash
   npm install
   ```

3. **Запустите локальный сервер:**
   ```bash
   npm start
   ```
   Сайт будет доступен по адресу: http://localhost:3000

### Альтернативные способы запуска

**С помощью Python:**
```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```

**С помощью Node.js:**
```bash
npx http-server . -p 8080
```

## 🚀 Деплой на GitHub Pages

### Автоматический деплой (рекомендуется)

1. **Настройте репозиторий:**
   - Перейдите в Settings → Pages
   - Выберите Source: "GitHub Actions"

2. **Деплой:**
   ```bash
   git add .
   git commit -m "Initial commit"
   git push origin main
   ```

3. **Сайт будет доступен по адресу:**
   `https://yarikmmm.github.io/BeastMasterLOM`

### Ручной деплой

```bash
npm run deploy
```

## 📁 Структура проекта

```
BeastMasterLOM/
├── index.html          # Главная страница
├── styles.css          # Стили
├── script.js           # JavaScript
├── package.json        # Зависимости
├── _config.yml         # Jekyll конфигурация
├── .github/
│   └── workflows/
│       └── deploy.yml  # GitHub Actions
├── .gitignore          # Игнорируемые файлы
└── README.md           # Документация
```

## 🎨 Кастомизация

### Изменение цветов

Отредактируйте CSS переменные в `styles.css`:

```css
:root {
    --primary-color: #6366f1;    /* Основной цвет */
    --secondary-color: #8b5cf6;  /* Вторичный цвет */
    --accent-color: #06b6d4;     /* Акцентный цвет */
}
```

### Добавление контента

1. **Новые секции** - Добавьте в `index.html`
2. **Стили** - Обновите `styles.css`
3. **Интерактивность** - Расширьте `script.js`

### Настройка GitHub Pages

Обновите следующие файлы:

1. **`package.json`** - Измените URL репозитория
2. **`_config.yml`** - Обновите настройки сайта
3. **`.github/workflows/deploy.yml`** - Настройте деплой

## 🔧 Разработка

### Добавление новых функций

1. Создайте новую ветку:
   ```bash
   git checkout -b feature/new-feature
   ```

2. Внесите изменения и закоммитьте:
   ```bash
   git add .
   git commit -m "Add new feature"
   ```

3. Отправьте изменения:
   ```bash
   git push origin feature/new-feature
   ```

4. Создайте Pull Request

### Тестирование

```bash
# Локальный сервер
npm start

# Проверка на мобильных устройствах
# Откройте http://localhost:3000 в браузере
# Используйте инструменты разработчика для тестирования
```

## 📱 Поддерживаемые браузеры

- ✅ Chrome 90+
- ✅ Firefox 88+
- ✅ Safari 14+
- ✅ Edge 90+

## 🤝 Вклад в проект

1. Форкните репозиторий
2. Создайте ветку для функции (`git checkout -b feature/AmazingFeature`)
3. Закоммитьте изменения (`git commit -m 'Add some AmazingFeature'`)
4. Отправьте в ветку (`git push origin feature/AmazingFeature`)
5. Откройте Pull Request

## 📄 Лицензия

Этот проект лицензирован под MIT License - см. файл [LICENSE](LICENSE) для деталей.

## 📞 Контакты

- **GitHub**: [@yarikmmm](https://github.com/yarikmmm)
- **Email**: contact@beastmasterlom.com
- **Discord**: [Сервер сообщества](https://discord.gg/yourinvite)

## 🙏 Благодарности

- [Font Awesome](https://fontawesome.com/) за иконки
- [Google Fonts](https://fonts.google.com/) за шрифты
- [GitHub Pages](https://pages.github.com/) за хостинг

---

⭐ Если проект вам понравился, поставьте звезду!
