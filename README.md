---

# Todo List App

**A modern, mobile-friendly todo list application with time tracking, reminders, and bulk operations.**

## Features

### 📝 Task Management
- **Add, edit, and delete tasks** with titles and optional time reminders.
- **Mark tasks as complete** with a single tap.
- **Bulk operations**: Select multiple tasks to complete or delete in one go.

### ⏰ Time Tracking & Reminders
- Set **time-based reminders** for tasks.
- Get **automatic notifications** (browser and sound) when a task is due.
- **No blocking alerts**: Reminders play sound and show notifications without requiring user interaction.

### 📊 Stats & Overview
- View **total, completed, and pending tasks** at a glance.
- **Visual feedback** for reminders (highlighted tasks).

### 🔄 Data Management
- **Export/Import tasks** as JSON for backup or transfer.
- **Clear all data** with a single click.

### 🛠️ Technical Features
- **Offline support** via Service Worker and caching.
- **Responsive design** for mobile and desktop.
- **Dark/light mode** (via Tailwind CSS).
- **Custom animations** for a smooth user experience.
- **Web Audio API** for reliable sound notifications.

### 🔒 Privacy & Permissions
- **Notification permissions** are requested only when needed.
- All data is stored locally in the browser (no server required).

---

## How to Use

1. **Add a Task**: Click the "+" button, enter a title, and optionally set a time.
2. **Edit/Delete**: Tap the edit or delete icons next to each task.
3. **Bulk Actions**: Tap the tasks icon to select multiple tasks, then complete or delete them.
4. **Reminders**: Set a time for a task, and you’ll get a notification and sound when it’s due.
5. **Export/Import**: Use the settings menu to back up or restore your tasks.

---

## Installation

### Web App
- Simply open `index.html` in a modern browser (Chrome, Firefox, Edge, etc.).
- For offline use, ensure the Service Worker is registered (check browser console for errors).

### Mobile
- Add the app to your home screen for a native-like experience.

---

## Technologies Used
- **HTML5, CSS3, JavaScript (ES6+)**
- **Tailwind CSS** for styling
- **Font Awesome** for icons
- **Web Audio API** for sound notifications
- **Service Worker** for offline support
- **LocalStorage** for data persistence

---

## Contributing
Pull requests and suggestions are welcome! For major changes, please open an issue first.

---

## License
This project is open-source and free to use.

---
