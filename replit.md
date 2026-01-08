# BlazerGames - Gaming Portal

## Overview
BlazerGames is a static HTML/CSS/JavaScript gaming portal website featuring multiple browser-based games including VEX series, Moto X3M, Retro Bowl, Drive Mad, Slope, and Bob the Robber 2.

**Current State:** Fully functional and deployed on Replit
**Last Updated:** November 1, 2025

## Project Architecture

### Technology Stack
- **Frontend:** Pure HTML, CSS, JavaScript (no frameworks)
- **Server:** Python 3.11 with built-in HTTP server
- **Port:** 5000 (frontend webview)
- **Host:** 0.0.0.0 (configured for Replit proxy)

### Project Structure
```
/
├── index.html          # Main homepage
├── main.css           # Global styles
├── script.js          # Search functionality
├── server.py          # Python HTTP server
├── images/            # Game thumbnails and logos
└── games/             # Individual game directories
    ├── vex7/
    ├── vex6/
    ├── vex5/
    ├── vex4/
    ├── vex3/
    ├── moto-x3m/
    ├── motox3m2/
    ├── retro-bowl/
    ├── slope/
    ├── drive-mad/
    ├── bob-the-robber-2/
    └── 1v1lol/
```

## Features
- **Game Library:** Collection of popular browser-based games
- **Search Functionality:** Real-time search filter for games
- **Featured Games:** Highlighted popular games section
- **Responsive Design:** Modern UI with Montserrat font
- **Play Button Hover Effect:** Interactive game thumbnails

## Technical Configuration

### Server Setup
- Static file server using Python's `http.server` module
- Cache-Control headers disabled for development
- Serves all static assets from project root

### Deployment
- **Type:** Autoscale (stateless static site)
- **Command:** `python3 server.py`
- **No build step required** (pure static files)

## Recent Changes
- **November 1, 2025:** Initial import from GitHub
  - Configured Python HTTP server on port 5000
  - Set up workflow for webview output
  - Configured deployment for autoscale
  - Added .gitignore for Python files
  - Verified all games and assets load correctly
