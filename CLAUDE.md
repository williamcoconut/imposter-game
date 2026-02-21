# Imposter Party Game - PWA

## What This Is
A mobile-first party game (pass-the-phone style). Everyone sees the secret word except one imposter. Players discuss with one-word clues, then vote to find the imposter.

## Tech
- Single `index.html` file — all HTML/CSS/JS inline
- PWA with inline manifest + service worker for offline/home-screen use
- No dependencies, no build step

## Game Flow
1. **Setup** — pick player count (3-12), category, hint toggles
2. **Pass-the-Phone** — each player taps to reveal role (imposter or word)
3. **Discussion & Voting** — timer, clue-giving, then reveal imposter

## Testing
Open `index.html` in browser. For PWA testing, serve via `python3 -m http.server` and use Safari on iPhone.
