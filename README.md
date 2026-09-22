# Blocky Brain

A kid-friendly, retro platformer-themed memory matching game — flip two blocks at a time and find every pair, built with React.

## How to run it

No installs, no build tools needed. Just:

1. Unzip this folder.
2. Double-click `index.html` — it opens straight in your browser.

Or, in VS Code:
1. Open this folder (`File → Open Folder`).
2. Right-click `index.html` → "Open with Live Server" (install the Live Server extension first if you don't have it).

## How it works

This is a single HTML file that loads React, ReactDOM, and Babel directly from a CDN, so the browser can run the React/JSX code with no separate build step. That's why it needs an internet connection the first time it loads (to fetch those scripts) — after that, the game itself runs entirely in your browser.

## Customizing

Open `index.html` in any text editor:
- Change the `ICONS` array near the top of the `<script type="text/babel">` section to swap the emoji icons.
- Tweak the CSS variables at the top of the `<style>` block to change colors.
