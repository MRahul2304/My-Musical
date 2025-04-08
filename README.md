# 🎵 Mini Music Player App

A simple, responsive music player built with **React**, **TailwindCSS**, and **React Context API**. Users can play, pause, seek, and navigate through a list of songs with a clean and minimal interface.

---

## 📦 Features

- 🎧 Audio playback with play/pause
- ⏮️ Previous/Next track navigation
- ⏱️ Time tracker with dynamic progress bar
- 🎚️ Seek functionality
- 🧠 Global state management using React Context
- ⚡ TailwindCSS for styling

---

## 🛠️ Tech Stack

- **React 18**
- **Vite**
- **TailwindCSS**
- **React Context API**
- **JavaScript (ES6)**

---

## 📁 Folder Structure

```
├── public/
├── src/
│   ├── assets/           # Static assets like icons, song files, and metadata
│   ├── Components/       # React UI components (Sidebar, Player, Display)
│   ├── Context/          # Player context (state & audio controls)
│   ├── App.jsx           # Main application layout
│   ├── index.css         # TailwindCSS base styles
│   ├── main.jsx          # Entry point
├── index.html
├── package.json
├── vite.config.js
```

---

## 🚀 Getting Started

### 1. Clone the repo

```bash
git clone https://github.com/your-username/mini-music-player.git
cd mini-music-player
```

### 2. Install dependencies

```bash
npm install
```

### 3. Start the development server

```bash
npm run dev
```

---

## 🧠 Usage

- Click the **Play** button to start playback.
- Use **Previous** and **Next** buttons to navigate between songs.
- Click the progress bar to seek through the track.
- Audio updates are synced in real-time with the UI.

---

## 📦 Build for Production

```bash
npm run build
```

---

## 📌 Notes

- Ensure the `songsData` in `assets/assets.js` is correctly set with valid audio file URLs and metadata.
- This is a minimal example meant to be extended with features like playlists, volume control, or user authentication.

---

## 📃 License

MIT © 2025 Rahul

```
