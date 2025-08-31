# 🚀 Daily Launcher

A full-stack web application for students, freelancers, and professionals who open multiple URLs daily.  
Instead of typing the same 5–10 URLs every day, save them as **collections** and launch all with **one click**.  
Supports **window layouts, delays and customization** for a productivity boost.  

---

## ✨ Features

### ✅ Core Features
- **Add Multiple URLs** – Quick input with auto-formatting (`google.com → https://google.com`)
- **Save Collections** – Organize URLs into named collections
- **One-Click Launch** – Open all URLs in a collection instantly
- **Delete Collections** – Remove collections when no longer needed
- **Duplicate Prevention** – Avoids saving the same URL twice

### 🌟 Extra Features
- 🎨 **Dark/Light Theme** – Toggle themes with persistence
- 📊 **Usage Analytics** – Track launches & usage stats
- 🏷️ **Tags & Categories** – Organize collections with custom tags
- 🔍 **Search & Filter** – Quickly find collections
- 💾 **Import/Export** – Backup and restore collections
- ⌨️ **Keyboard Shortcuts** – Quick actions (Ctrl+N, Ctrl+S, Ctrl+/)
- 🎨 **Custom Themes** – Each collection can have its own theme
- 📈 **Launch Statistics** – See which collections you use most
- 📝 **Rich Descriptions** – Add detailed notes
- 🖥️ **Window Resizer Options** – Open URLs in layouts (left, right, top, bottom, grid)
- ⏱️ **Delay Loader** – Open URLs with delay to reduce overload
- 🔗 **Share Sessions** – Share collections with friends or teammates

---

## 🛠️ Tech Stack
- **Frontend:** React (Vite) + Tailwind CSS + Lucide Icons
- **Backend:** Flask + SQLAlchemy + SQLite
- **Other Features:** REST API, PWA, Responsive UI/UX

---

## 📂 Project Structure
daily-launcher/
├── backend/
│ ├── app.py # Flask API server
│ ├── requirements.txt # Python dependencies
│ └── daily_launcher.db # SQLite database (auto-created)
├── frontend/
│ ├── public/
│ │ ├── index.html # Main HTML file
│ │ └── manifest.json # PWA manifest
│ ├── src/
│ │ ├── App.js # Main React component
│ │ ├── index.js # React entry point
│ │ └── index.css # Tailwind CSS
│ ├── package.json # Node dependencies
│ └── tailwind.config.js # Tailwind configuration


---

## ⚡ Setup Instructions (Windows + VS Code)

### 1️⃣ Prerequisites
- Python 3.8+
- Node.js 16+
- VS Code with extensions:
  - Python
  - ES7+ React/Redux snippets
  - Tailwind CSS IntelliSense

### 2️⃣ Clone Repository

git clone https://github.com/your-username/daily-launcher.git
cd daily-launcher

### 3️⃣ Setup Backend
cd backend
python -m venv venv
venv\Scripts\activate   # Windows
pip install -r requirements.txt
python app.py


Backend runs on http://127.0.0.1:5000

### 4️⃣ Setup Frontend

Open new terminal:

cd frontend
npm install
npm run dev


Frontend runs on http://localhost:5173

## 🎮 Usage

Open the app in browser.

Add URLs and save as collections.

Use Launch All to open multiple sites instantly.

Choose window layouts (top, left, right, grid).

Toggle dark/light theme.

Use tags, search, and favorites to stay organized.

Backup or share collections.
