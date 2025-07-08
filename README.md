## Josh Musics – A React-Based Music Player

**Josh Musics** is a responsive and fully functional web music player application built using React, Redux, and Tailwind CSS. Designed to replicate a simplified streaming experience, it allows users to browse tracks, play music, search by artist or title, and manage personal playlists and liked songs.


![image](https://github.com/user-attachments/assets/12afa413-4909-4fa2-8ae9-0a78d6e2942c)

### Features

* Interactive "Now Playing" section with dynamic UI feedback
* Playlist support with add/remove functionality
* Liked songs section with persistent state
* Real-time search filtering by song title or artist name
* Custom audio player with play, pause, skip, and seek controls
* Responsive design for both desktop and mobile layouts
* Clean component-based architecture with state management using Redux and Context API

### Tech Stack

* **Framework:** React (Vite)
* **Styling:** Tailwind CSS
* **Routing:** React Router
* **State Management:** Redux Toolkit and React Context API
* **Audio Handling:** HTML5 Audio API
* **Other Tools:** React Icons, useRef/useState/useEffect for playback logic

### Project Structure

```
src/
│
├── components/        # Reusable UI components (Player, Card, Nav)
├── pages/             # Page-level views (Home, Search, Playlist, Liked)
├── context/           # Audio playback state (UserContext)
├── redux/             # Redux store configuration
├── assets/            # Static assets (images, animations)
├── App.jsx            # Main routing logic
└── main.jsx           # Entry point
```

### Installation

To run the project locally:

```bash
git clone https://github.com/yourusername/josh-musics.git
cd josh-musics
npm install
npm run dev
```

### Pages Overview

| Route       | Description                                     |
| ----------- | ----------------------------------------------- |
| `/`         | Home page with "Now Playing" and full song list |
| `/search`   | Search songs by name or singer                  |
| `/playlist` | View and play from your playlist                |
| `/liked`    | Access your liked songs                         |

### Live Demo

> https://josh-musics.netlify.app/

---
