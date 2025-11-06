# Changelog

All notable changes to ClutchTV will be documented in this file.

## [0.1.2-alpha] - 2025-11-05

### ✨ Added

- **Game Insights System**: Automatic post-game analysis with actionable improvement suggestions
  - **Death Pattern Analysis**: Detects repeated deaths in same map zones with ward placement suggestions (17 zones tracked)
  - **Early Death Analysis**: Identifies first blood and early game deaths that cause snowballing
  - **Vision Pre-Objective Analysis**: Tracks vision score gain before Drake/Baron/Herald spawns
- **Coordinate Tracking**: All events now capture X/Y map coordinates for spatial analysis
- **Map Zone System**: 17 identified zones (lanes, jungle quadrants, objectives, strategic bushes)
- **Auto-Clip System**: Automatic clips generated for all major events (pentakills, baron steals, first bloods, deaths)
- **Game Session Management**: Delete entire game sessions with one click (removes recordings, clips, and database entries)
- **Advanced Clip Editor**: New UI with event type filtering and improved timeline navigation
- **Async SaveWorker**: Eliminated FPS drops during clip encoding with background worker thread

### 🔧 Changed

- Insights work for **all roles** (Top, Jungle, Mid, Bot, Support) with universal analyzers
- Improved database schema with cascading deletes for data integrity
- Enhanced event detection with position data extraction from LCU API

### 🐛 Fixed

- Fixed foreign key constraint errors when deleting game sessions
- Resolved type mismatches in vision analyzer compilation
- Improved error handling in event polling with coordinate extraction

### 🗑️ Removed

- CS Performance Analyzer temporarily disabled (not suitable for jungle/support roles)

---

## [0.1.1-alpha] - 2025-02-15

### ✨ Added

- Circular buffer recording system (records 24/7 without filling disk)
- Improved game session organization
- Better performance monitoring

### 🔧 Changed

- Optimized recording performance to maintain ~100 FPS capture
- Improved event synchronization with video timeline

---

## [0.1.0-alpha] - 2025-01-29

### 🎉 Initial Alpha Release

First public release of ClutchTV!

### ✨ Features

- **Auto-Recording**: Automatically detects League of Legends games and starts recording
- **Event Timeline**: Tracks kills, deaths, assists, dragons, barons, and towers
- **Player Detection**: Automatically identifies summoner name and champion via LCU API
- **Quick Clips**: Instant event-based clipping for pentakills, baron steals, etc.
- **Clip Editor**: Create custom clips with start/end time selection
- **Local Storage**: All recordings and data stored locally on your PC
- **Video Analysis**: Automatic thumbnail generation and metadata extraction
- **Interactive Timeline**: Click event markers to jump to any moment
- **Filter Events**: View only your kills/deaths on timeline by default


### ⚠️ Known Issues

- Windows SmartScreen warning on first run (normal for unsigned apps)
- Only supports League of Legends (more games coming soon)
- May require "Run as Administrator" on some systems
- Large video files (~500MB per 30min game)
- Practice Tool not supported (no Live Client API)

### 📦 Installation

Download `ClutchTV-v0.1.0-alpha.zip` from [Releases](../../releases/latest), extract, and run `ClutchTV.exe`.

### 🔜 Coming Soon

- Performance heatmaps for League of Legends
- Advanced analytics (win conditions, objective control)
- AI-powered outplay detection
- Cloud clip sharing
- Microsoft Store distribution

---

## Template for Future Releases

## [X.Y.Z] - YYYY-MM-DD

### ✨ Added
- New feature description

### 🔧 Changed
- Changed feature description

### 🐛 Fixed
- Bug fix description

### 🗑️ Removed
- Removed feature description

### ⚠️ Deprecated
- Deprecated feature description

### 🔒 Security
- Security improvement description
