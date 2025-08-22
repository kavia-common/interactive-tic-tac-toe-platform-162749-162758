# Tic Tac Toe Frontend (Astro)

A modern, minimalistic, responsive Tic Tac Toe game UI built with Astro.

Features:
- Start new game
- Two player (PvP) mode
- Play against basic AI
- Score tracking (session/localStorage)
- Responsive design
- Game reset and score reset

## Quick start

From this folder:

1) Install deps
   npm install

2) Start dev server
   npm run dev
   # served at http://localhost:3000

3) Build
   npm run build

4) Preview production build
   npm run preview

## Project structure

- src/layouts/Layout.astro — global layout and theme variables
- src/components/TicTacToe.astro — main game component with logic
- src/components/ThemeToggle.astro — optional light/dark theme switch
- src/pages/index.astro — page entry wiring the component

No backend required.
