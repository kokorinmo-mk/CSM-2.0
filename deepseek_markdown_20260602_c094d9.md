# CSM 2.0 - Система оценки компетенций

Веб-приложение для оценки компетенций CSM 2.0 (Customer Success Manager).

## 🚀 Функциональность

- ✅ **Авторизация** через Firebase (регистрация/вход)
- ✅ **Тестирование знаний** по 8 областям компетенций
- ✅ **Самооценка** навыков по шкале 1-10
- ✅ **ИИ-рекомендации** через GigaChat (сервер на Render)
- ✅ **История** всех результатов
- ✅ **Адаптивный дизайн** для всех устройств

## 🛠 Технологии

- **Frontend**: React 18, TypeScript, Tailwind CSS
- **Routing**: React Router v6
- **Auth & DB**: Firebase (Authentication, Firestore)
- **HTTP Client**: Axios
- **Markdown**: react-markdown
- **Icons**: Lucide React

## 📦 Установка и запуск

### Требования
- Node.js 18+
- npm или yarn

### Локальный запуск

```bash
# Клонируем репозиторий
git clone https://github.com/YOUR_USERNAME/csm-web.git
cd csm-web

# Устанавливаем зависимости
npm install

# Создаём файл .env и добавляем Firebase конфиг
cp .env.example .env

# Запускаем dev сервер
npm run dev