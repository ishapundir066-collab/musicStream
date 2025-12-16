🎧 INFINITY-PLAYER
🎶 Your Favorite Music, Reimagined with a Neon Glow

INFINITY-PLAYER is a sleek, modern, and interactive music player built entirely with HTML, CSS, and Vanilla JavaScript. It features a responsive Neon / 3D-inspired UI and delivers a smooth, immersive playback experience using a local music library.

✨ Features

Neon / 3D Interface
Modern, visually striking design using advanced CSS transforms, shadows, and neon glow effects.

Fully Responsive Design
Optimized for desktop, tablet, and mobile devices.

Complete Player Controls

Play / Pause

Next / Previous

Interactive Seek Bar (Progress Bar)

Dynamic Song List
Songs are loaded dynamically from a JavaScript array, making playlist updates easy.

Auto Play Next
Automatically plays the next track when the current song ends.

Visual Feedback
Displays a playing GIF and continuously updates the current song title.

🚀 Getting Started
1️⃣ File Structure Setup

Ensure your project directory follows this structure:

Infinity-Player-Project
│-- index.html              ← Main application file
│-- logo.png                ← Player logo
│-- playing.gif             ← Playing animation
│
├── songs
│   ├── 1.mp3
│   ├── 2.mp3
│   └── ... (up to 17.mp3)
│
├── covers
│   ├── 1.jpg
│   ├── 2.jpg
│   └── ... (additional cover images)


⚠️ Important:
The player uses relative paths (songs/1.mp3, covers/1.jpg).
If files are missing or incorrectly named, audio and cover images will not load.

2️⃣ Running the Application

Save the code in a file named index.html

Place your audio files in the songs/ folder

Place album covers in the covers/ folder

Open index.html in any modern web browser (Chrome, Firefox, Edge)

⚙️ Customization

The design uses CSS variables defined in the <style> block:

Variable	Description	Default
--primary-color	Main neon accent color	#00e0ff
--secondary-color	Dark background for UI elements	#1a1a2e
--background-color	Main page background	#0d0d18
--glow-shadow	Neon glow effect	0 0 10px rgba(0, 224, 255, 0.6)

🎨 To change the theme color, simply update the value of --primary-color.

🎵 Updating the Playlist

The playlist is managed in JavaScript using the songs array:

let songs = [
  {
    songName: "Manma Emotion Jaage [Slowed & Reverb]",
    filePath: "songs/1.mp3",
    coverPath: "covers/1.jpg",
    duration: "05:34"
  },
  {
    songName: "Love Me Back - R.I.P",
    filePath: "songs/2.mp3",
    coverPath: "covers/2.jpg",
    duration: "04:12"
  }
  // Add more songs here
];

➕ To Add a New Song:

Add the MP3 file to the songs/ folder

Add the cover image to the covers/ folder

Append a new object to the songs array

Ensure filePath, coverPath, and duration are correct

🤝 Contributing

This project is a great front-end UI challenge.
You’re welcome to contribute by adding features such as:

Volume slider

Audio visualizer

Playlist search

Theme switcher

Fork the repository and submit a pull request with your improvements.

📝 License

All Rights Reserved
© INFINITY-PLAYER 2023