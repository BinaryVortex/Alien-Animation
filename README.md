# Alien Animation

Responsive alien / UFO animation built with pure HTML and CSS (with a tiny amount of semantic structure in the HTML). A lightweight, easy-to-read example showing how shapes, gradients and keyframe animation combine to make a playful illustration.

![Alien Animation Screenshot](./Screenshot%202024-08-30%20104203.png)

## Demo
Open `index.html` in any modern browser. No build steps, no dependencies — just the files in this repository.

Quick ways to view the project:
- Double-click `index.html` to open it in your default browser.
- Use VS Code + Live Server extension to view live while editing.

## What you'll find in this repo
- `index.html` — minimal semantic markup that structures the UFO and alien.
- `style.css` — all styling and animation (pure CSS). The repository is composed mostly of CSS.
- `Screenshot 2024-08-30 104203.png` — a preview image used in this README.

## Features
- Pure CSS shapes and gradients to form the UFO and alien.
- A simple floating animation implemented with CSS keyframes.
- Responsive sizing using ems and a media query for larger screens.

## How it works (short)
The animation uses a single keyframe named `float` that adjusts the `top` of the `.ufo` element to create a subtle up-and-down movement. The alien and UFO shapes are created using border-radius, pseudo-elements (`::before` / `::after`), and box-shadow — no images required.

## Customize
- Tweak sizes by changing the `.container` dimensions or the `font-size` in the media query.
- Change colors in `style.css` (background, alien skin, highlights) to create different themes.
- Add more keyframes or transform rules to create more complex motion.

## License
This project is provided as-is. Feel free to copy, adapt, and reuse the code in your own projects.

---

Made with care by BinaryVortex — have fun animating!