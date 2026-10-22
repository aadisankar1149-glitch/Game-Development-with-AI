# NIDAR — The Lone Warrior of Punjab

**Tagline:** Fearless. Alone. Unbroken.

NIDAR is a small browser-based 2D action-game prototype created for the SDC — Next-Gen AI for Emerging Professionals CA-2 website assignment.

## Game concept

The player controls a fictional Sikh warrior defending a fictional Punjab village. Defeat five raiders before the 90-second timer expires or the warrior loses all three health points. Combat is stylized and non-graphic. The setting is inspired by rural Punjab and does not depict a specific historical battle or religious event.

## Play

- Move: **WASD** or **arrow keys**
- Attack: **Space** or the **Strike** button
- Goal: defeat five raiders while protecting your health and beating the timer
- Select **Start / Restart** to begin or replay

## Technologies

- HTML for page structure
- CSS for responsive layout and visual design
- JavaScript Canvas API for the game loop, movement, combat, enemy behaviour, HUD, timer, and effects
- No external libraries, server, API key, or online database required

## Run locally

Open `index.html` in a modern browser. Keep `styles.css` and `game.js` in the same directory as `index.html`.

## Deployment

This repository is intended to be published with GitHub Pages. To enable it, open **Settings → Pages**, choose **Deploy from a branch**, select `main` and `/(root)`, and save. The exact public URL appears in that settings page after publishing.

## Project notes

This is a prototype. Test the complete game in the target browser before reporting gameplay tests as passed. It uses no live AI model and stores the best completion time locally in the browser.