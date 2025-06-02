# ZENDER | Real-Time Chat Application

A fully responsive real-time chat application built with **ReactJS** and **Laravel**, offering seamless messaging, file sharing, group management, and live WebSocket-powered updates.

## 🚀 Features

- 🔄 Real-time sending and receiving of messages via WebSockets
- 😀 Emoji support in messages
- 📝 Markdown formatting support
- ❌ Delete your own messages
- 🔁 Infinite scroll for older messages
- 📎 Send files of any type
- 🖼️ Quick image sharing with preview
- 🎤 Record and send audio messages from the browser
- 🔍 Preview images, videos, audio, and PDFs in small or full screen
- ➕ Add and manage users
- 🔒 Block and unblock users
- 🛠️ Assign and remove admin roles
- 👥 Create, edit, and delete groups
- ⚙️ Background jobs for handling large group deletions with live user notifications
- 👤 Update your profile details including name, email, password, and profile picture
- 📱 Fully responsive design optimized for all screen sizes

## 🛠 Tech Stack

### Frontend
- ReactJS
- TailwindCSS or Material UI
- Axios
- React Router
- Emoji Picker
- React-Markdown

### Backend
- Laravel
- Laravel WebSockets or Pusher
- Laravel Sanctum (for authentication)
- Laravel Queues (for background jobs)
- Laravel File Storage (for media handling)

### Others
- MySQL / PostgreSQL
- Redis (for broadcasting & queues)
- Docker (optional)

## 📦 Installation

### Backend (Laravel)

```bash
git clone https://github.com/mrJudyAbraham/Zender.git
cd Zender
composer install
cp .env.example .env
php artisan key:generate
php artisan migrate
php artisan storage:link
php artisan serve

cd ../frontend
npm install
npm run dev
```