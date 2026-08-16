# 🎵 Music Player — CodeAlpha Internship

A responsive music player web app built with **HTML, CSS, and JavaScript**, featuring a vinyl-record inspired interface, full playback controls, and a 50-song playlist.

## 📋 Overview

Nightwave is a browser-based music player that lets users play, pause, skip, and scrub through tracks in a polished, interactive UI. It was built to demonstrate front-end audio handling with the native HTML5 `<audio>` API, DOM manipulation, and responsive interface design.

## ✨ Features

- **Playback controls** — play, pause, next, and previous track
- **Now playing info** — displays song title, artist, current time, and total duration
- **Seekable progress bar** — click anywhere on the bar to jump to that point in the track
- **Volume control** — adjustable slider for real-time volume changes
- **Playlist** — scrollable list of 50 songs; click any track to play it instantly
- **Autoplay** — automatically advances to the next track when the current one ends (toggle on/off)
- **Animated vinyl record** — spins during playback, with a tonearm that lifts and drops in sync with play/pause state
- **Keyboard shortcuts** — `Space` to play/pause, arrow keys to skip tracks
- **Responsive design** — adapts cleanly to mobile and desktop screens

## 🛠️ Built With

- **HTML5** — structure and the native `<audio>` element for playback
- **CSS3** — styling, layout, and animations (vinyl spin, tonearm motion, equalizer icon)
- **JavaScript (Vanilla)** — playback logic, event handling, and playlist management

## 🚀 Getting Started

### Run locally

1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/music-player.git
   ```
2. Navigate into the project folder:
   ```bash
   cd music-player
   ```
3. Open `index.html` in your browser — no build step or dependencies required.

## 📂 Project Structure

```
music-player/
├── index.html      # Markup for the player UI
├── style.css       # Styling and animations
├── script.js       # Playback logic and playlist handling
└── README.md       # Project documentation
```

## ⌨️ Keyboard Shortcuts

| Key           | Action           |
|---------------|------------------|
| `Space`       | Play / Pause     |
| `→`           | Next track       |
| `←`           | Previous track   |

## 🎧 Audio Files

The playlist ships with **placeholder royalty-free audio** so the player works out of the box. To use your own music:

1. Open `script.js` and locate the `songs` (or `songMeta` / `PLACEHOLDER_SRCS`) array.
2. Replace each `src` value with the path or URL to a track you have the rights to use — your own library, a licensed streaming API, or royalty-free sources like Free Music Archive or Pixabay Music.
3. Update the `title` and `artist` fields to match.

> ⚠️ Do not distribute copyrighted audio files in this repository unless you hold the rights to them.

## 🎯 What I Learned

- Working with the HTML5 `<audio>` API (play, pause, `timeupdate`, `loadedmetadata`, `ended` events)
- Managing playback state (current track, playing/paused, progress) in vanilla JavaScript
- Building custom UI controls (progress bar, volume slider) on top of native audio events
- Creating CSS animations tied to application state (spinning vinyl, tonearm movement)
- Structuring a dynamic, data-driven playlist rendered from a JavaScript array

## 📌 Internship

This project was developed as part of the **CodeAlpha Web Development Internship** program.

## 📄 License

This project is open source and available for learning purposes. Audio files are not included/distributed — see [Audio Files](#-audio-files) above.
