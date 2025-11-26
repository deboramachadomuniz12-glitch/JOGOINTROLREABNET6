# STELAS - Plataforma de Reabilitacao Digital

## Overview
This is a digital rehabilitation platform featuring the "Articule Livre" application, designed to help people with repetitive strain injuries perform guided hand exercises.

## Project Architecture
- **Frontend**: Static HTML/CSS/JS served by Express
- **Backend**: Node.js with Express server
- **Integration**: GitHub API via Octokit

## GitHub Integration
The project includes GitHub integration that provides:
- `/api/github/user` - Get authenticated user profile
- `/api/github/repos` - List user's repositories (10 most recent)

## Running the Project
The server runs on port 5000 and serves:
- Static files from the root directory
- GitHub API endpoints under `/api/github/`

## Files
- `index.html` - Main presentation page for Articule Livre
- `server.js` - Express server with GitHub integration
- `style.css` - Additional styles
- `script.js` - Client-side JavaScript
- Images: CAPA.png, ALBINA.png, jogo.png, etc.

## Recent Changes
- Nov 2025: Added GitHub integration with Octokit
- Nov 2025: Created Express backend server
