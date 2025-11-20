# Modos de Estudio - Game Selector

## Overview
This is a Spanish-language game collection web application featuring interactive browser games. The project includes a main selector page that allows users to choose between different games.

## Project Structure
- **index.html** - Main game selector page
- **numalea.html** - Number guessing game page
- **ppt.html** - Rock-paper-scissors game page (placeholder)
- **styles.css** - Styling for the main selector
- **stylenumalea.css** - Styling for the number guessing game
- **scriptnumalea.js** - Game logic for the number guessing game
- **server.py** - Python HTTP server serving static files on port 5000

## Available Games
1. **Adivina Numero Aleatorio** (Guess Random Number) - A game where players try to guess a randomly generated number between 1 and 100
2. **Piedra Papel Tijeras** (Rock Paper Scissors) - Coming soon

## Technical Setup
- **Frontend**: Pure HTML, CSS, and JavaScript (no build process needed)
- **Server**: Python 3.11 HTTP server
- **Port**: 5000 (configured for Replit webview)
- **Host**: 0.0.0.0 (allows access through Replit's proxy)

## Recent Changes
- **2025-11-20**: Initial import and setup in Replit environment
  - Installed Python 3.11
  - Created HTTP server with cache-control headers
  - Configured workflow for port 5000 with webview
  - Added .gitignore for Python files

## Running the Project
The project automatically runs via the "Web Server" workflow. The Python server serves all static files and is configured to prevent caching issues.
