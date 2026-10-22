# NIDAR — The Lone Warrior of Punjab

**Tagline:** Fearless. Alone. Unbroken.

NIDAR is a small browser-based 2D action game developed as a student project for SDC — Next-Gen AI for Emerging Professionals.

## Game concept

The player controls a fictional Sikh warrior defending a fictional Punjab village. Defeat five raiders before the 90-second timer expires or the warrior loses all three health points. The game uses stylized, non-graphic combat and a custom-drawn Punjab-inspired setting. It does not depict a specific historical battle or religious event.

## 🎮 Play NIDAR

**[Click here to play the live game](https://aadisankar1149-glitch.github.io/Game-Development-with-AI/)**

If the site has just been published, give GitHub Pages a little time to finish deploying.

## Play the game

**Controls**
- Move: **WASD** or **arrow keys**
- Attack: **Space** or the **Strike** button
- Objective: defeat five raiders before the time or health runs out
- Press **Start / Restart** to begin again

## Technology

- HTML, CSS and vanilla JavaScript
- Canvas API for the playable game, movement, enemy behaviour, scoring, timer, combat feedback and effects
- No external libraries, server, API key or online database is required

## Run locally

Download or clone this repository, then open `index.html` in a modern browser. The page is self-contained.

## Publish using GitHub Pages

1. Open this repository's **Settings → Pages**.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select branch `main` and folder `/(root)`, then save.
4. Open the public URL shown on the Pages settings page. For this repository it should be:
   `https://aadisankar1149-glitch.github.io/Game-Development-with-AI/`
5. Test the link in an Incognito/Private window and on a narrow/mobile viewport.

Official guide: https://docs.github.com/en/pages/quickstart

## Project notes and limitations

This is a one-level prototype. The characters and environment are drawn with CSS and Canvas shapes; the game does not use a live AI model or online database. The best completion time is stored locally in the browser. Test all controls and game states in the target browser before reporting them as verified in the assignment.