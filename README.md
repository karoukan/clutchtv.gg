# ClutchTV

<div align="center">

<img src="assets/clutchtv-logo.png" alt="ClutchTV Logo" width="300">

**Never miss a play. Record your League of Legends games automatically.**

[![Download](https://img.shields.io/badge/Download-Latest%20Release-blue?style=for-the-badge)](../../releases/latest)
[![Discord](https://img.shields.io/badge/Discord-Join%20Community-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/9JQzXfTVXE)
[![Windows](https://img.shields.io/badge/Windows-10%2F11-0078D6?style=for-the-badge&logo=windows&logoColor=white)](../../releases/latest)

</div>

---

## 🎮 What is ClutchTV?

ClutchTV automatically records your League of Legends games and tracks every kill, death, and objective. Review your gameplay with an interactive timeline that lets you jump to any moment instantly.

### ✨ Features

- **🎥 Auto-Recording** - Starts recording when you enter a League game
- **⚡ Event Timeline** - Every kill, death, assist, and objective tracked automatically
- **✂️ Clip Editor** - Create highlight clips with one click
- **💾 100% Local** - Everything stays on your computer, no cloud uploads
- **🎯 Quick Clips** - Instant event-based clipping (pentakills, baron steals, etc.)
- **🔍 Player Detection** - Automatically identifies your summoner name and champion

---

## 📥 Download

### Option 1: Standalone Package (Recommended for Alpha)

**[⬇️ Download ClutchTV v0.1.2-alpha.zip](../../releases/latest)**

1. Extract the ZIP to any folder
2. Run `ClutchTV.exe`
3. Select your videos folder on first launch
4. Start playing League - recording begins automatically!

**Requirements:**
- Windows 10 or 11 (64-bit)
- League of Legends installed
- ~10GB free disk space for recordings

### Option 2: Microsoft Store (Coming Soon)

📦 **Distribution via Microsoft Store** - No SmartScreen warnings, automatic updates

---

## 🚀 Quick Start

1. **Launch ClutchTV**
2. **Start League of Legends**
3. **Play your game** - Recording starts automatically
4. **Review your replay** - Timeline shows all events
5. **Create clips** - Select moments and export

---

## 🎬 How It Works

### Recording
- Automatically detects when you enter a League game
- Records at your native resolution
- Minimal performance impact (~5-10 FPS)

### Event Tracking
- Connects to League's Live Client API (port 2999)
- Tracks kills, deaths, assists, dragons, barons, towers
- Events sync perfectly with your video timeline

### Clip Creation
- Open any replay and click "Edit"
- Select start/end times on the timeline
- Export clips with optional watermark
- Clips saved to a separate folder

---

## ⚠️ Alpha Release Notes

This is an **alpha version** - bugs are expected!

**Known Issues:**
- Windows SmartScreen warning on first run (normal for new apps)
  - Click "More info" → "Run anyway"
- May require "Run as Administrator" on some systems
- Large video files (~500MB per 30min game)

**Please report bugs on [Discord](https://discord.gg/9JQzXfTVXE) or [GitHub Issues](../../issues)!**

---

## 🛠️ Troubleshooting

### Recording didn't start?
- Make sure League is running in **Windowed** or **Borderless** mode (not fullscreen)
- Check if ClutchTV is running in the background

### No events showing on timeline?
- Game must be longer than 5 minutes
- Practice Tool is not supported (no Live Client API)
- Check your firewall isn't blocking port 2999

### App won't launch?
- Right-click `ClutchTV.exe` → "Run as Administrator"
- Check Windows Event Viewer for error details

### Video playback is laggy?
- Try reducing your in-game resolution
- Ensure videos are saved to a fast drive (SSD recommended)

---

## 🗺️ Roadmap

### v0.2.0 (Coming Soon)
- [ ] **Performance Heatmaps** - Visualize your kills/deaths on the minimap
- [ ] **Advanced Analytics** - Win condition analysis, objective control stats
- [ ] **Auto-Highlights** - AI detects outplays, pentakills, and clutch moments
- [ ] **Cloud Clip Sharing** - Share clips with friends via link

### v1.0.0 (Full Release)
- [ ] Microsoft Store distribution
- [ ] Multi-language support
- [ ] Advanced clip editor with transitions
- [ ] Statistics dashboard

---

## 💬 Community & Support

- **Discord**: [https://discord.gg/9JQzXfTVXE](https://discord.gg/9JQzXfTVXE)
- **Bug Reports**: [GitHub Issues](../../issues)
- **Made by**: Processor

---

## 🔒 Privacy

- **No telemetry** - We don't track you
- **No cloud uploads** - Everything stays local
- **No account required** - Just download and use
- **Open issue tracking** - Transparent development

Your replays and data never leave your PC.

---

## 📂 Where Are My Files?

- **Recordings**: The folder you selected on first launch (default: `%USERPROFILE%\Videos\ClutchTV`)
- **Database**: `%USERPROFILE%\AppData\Local\ClutchTV\clutchtv.db`
- **Logs**: `%USERPROFILE%\AppData\Local\ClutchTV\logs\`
- **Clips**: `YourVideosFolder\clips\`

---

## 🎯 Coming Soon

**ClutchTV is laser-focused on becoming the ultimate League of Legends replay tool.**

- 🗺️ **Performance Heatmaps** - Visualize where you dominate or struggle on the map
- 📊 **Advanced Analytics** - Win rate by champion, objective control, lane phase analysis
- 🤖 **AI Outplay Detection** - Automatically find your best mechanical plays
- 🔗 **Clip Sharing** - Share highlights directly with friends
- 🏆 **Champion Mastery Showcase** - Auto-generated montages of your best plays
- 📈 **Progress Tracking** - See your improvement over time with detailed stats

---

<div align="center">

**[⬇️ Download Latest Release](../../releases/latest)** • **[Join Discord](https://discord.gg/9JQzXfTVXE)** • **[Report Bug](../../issues)**

Made with ❤️ by Processor • 2025

</div>
