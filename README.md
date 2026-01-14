😂 Meme Generator

A browser-based meme creation tool built with vanilla JavaScript.

This app lets users pick an image, add multiple text layers, move them around, and export a finished meme — all directly in the browser without any external libraries.

🖼️ What it does

The Meme Generator allows you to:

Choose an image from a gallery or upload your own

Add multiple text captions

Drag text freely on the canvas

Change font size, color and alignment

Download the final meme as an image

Everything happens client-side, so no files are uploaded to a server.

🛠 Built with

JavaScript (Vanilla)

HTML

CSS

Canvas API

No frameworks, no dependencies.

🧠 How it works

The core of the app is an HTML <canvas> element.
Each text caption is stored as an object with position, font size, color and content.

When something changes (text, position, style), the canvas is cleared and re-rendered:

The image is drawn

All text layers are drawn on top

The result is shown instantly

Dragging text is handled with mouse events that update each text layer’s coordinates in real time.

Open index.html in your browser
or run a local server:

npx serve

🚀 Why this project exists

This project was built to practice:

Working with the Canvas API

Creating interactive drag & drop interfaces

Managing layered visual data

Turning user input into exported media

It’s designed as a foundation for future features like:

Templates

Stickers

Mobile support

Sharing
