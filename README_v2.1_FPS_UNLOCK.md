# 🚀 AX HyperBoost ULTIMATE v2.1 EXTREME FPS

## ✨ NEW in v2.1: FPS UNLOCK/LOCK FEATURE!

**Auto-detect your display's maximum refresh rate (60/90/120/144/165Hz) and unlock games to match!**

---

## 🎯 What's New in v2.1

### 🔓 **FPS Unlock System**
- ✅ **Auto-detects** your device's maximum refresh rate
- ✅ **Unlocks** display to maximum Hz (120/144/165Hz)
- ✅ **Forces** games to run at max FPS
- ✅ **Disables** FPS limiters and VSync
- ✅ **Locks** FPS to specific values (60/90/120/144/165)
- ✅ **Real-time** FPS monitoring

### 🎨 **Enhanced WebUI**
- ✅ Beautiful anime-themed backgrounds
- ✅ Gradient effects and smooth animations
- ✅ Live FPS monitoring dashboard
- ✅ Real-time performance graphs
- ✅ One-click FPS unlock/lock buttons
- ✅ Detailed system information

### ⚡ **Performance Improvements**
- ✅ Better thermal management
- ✅ Optimized CPU/GPU scaling
- ✅ Improved touch response
- ✅ Enhanced network speed
- ✅ Smarter memory management

---

## 📦 Package Contents

```
AXHyperBoost_v2.1_FPS_UNLOCK.zip (17 MB with backgrounds)
│
├── module.prop              ✅ v2.1 FPS metadata
├── customize.sh             ✅ Installation script
├── post-fs-data.sh         ✅ Boot initialization
├── service.sh              ✅ Main service launcher
├── action.sh               ✅ AxManager action button
├── uninstall.sh            ✅ Complete uninstall script
│
├── system/bin/             ✅ Enhanced binaries
│   ├── axengine           → v2.1 with FPS unlock
│   ├── gpuopt             → GPU optimizer
│   └── touchboost         → Touch response optimizer
│
├── config/                 ✅ Configuration files
│   ├── axeron.conf        → Main config
│   ├── profiles.json      → Performance profiles
│   ├── devices.json       → Device-specific settings
│   ├── gamelist.txt       → Game detection list
│   └── fps_settings.conf  → NEW! FPS configuration
│
├── webroot/               ✅ Enhanced Web UI
│   ├── index.html        → NEW! Anime-themed control panel
│   ├── dashboard.html    → NEW! Real-time FPS monitoring
│   ├── plugin.json       → Plugin metadata
│   ├── css/style.css     → Enhanced styling
│   ├── js/              → JavaScript controllers
│   └── assets/
│       ├── background.png → NEW! Anime background
│       ├── banner.png     → NEW! Anime banner
│       └── icon.svg       → Module icon
│
└── lib/                   ✅ Native libraries (placeholder)
```

---

## 🎮 FPS UNLOCK Features

### Auto-Detection:
The module automatically detects your device's max refresh rate:

| Device Type | Max Hz | Unlock Target |
|-------------|--------|---------------|
| High-end | 165Hz | 165Hz/165fps |
| Gaming | 144Hz | 144Hz/144fps |
| High refresh | 120Hz | 120Hz/120fps |
| Medium refresh | 90Hz | 90Hz/90fps |
| Standard | 60Hz | 60Hz/60fps |

### FPS Control Commands:

```bash
# Unlock to maximum
axengine --fps-unlock

# Lock to 60Hz/fps (battery save)
axengine --fps-lock

# Get FPS information
axengine --fps-info

# Gaming mode (auto-unlocks FPS)
axengine --gaming

# Battery mode (auto-locks to 60fps)
axengine --battery
```

---

## 🖥️ Enhanced WebUI Features

### Main Control Panel (index.html):
- 🎨 Anime-themed background
- 📊 Real-time system status
- 🔓 FPS unlock/lock buttons
- ⚡ Performance profile switching
- 🎮 Quick action buttons

### Dashboard (dashboard.html):
- 📈 Live FPS graph
- 🌡️ Temperature monitoring
- 💻 CPU/GPU stats
- 📡 Network status
- 📝 Live activity logs

---

## 🎯 Installation

### Requirements:
- ✅ Android 8.0+ (API 26+)
- ✅ AxManager v1.04.00+
- ✅ 20MB free space (includes backgrounds)
- ✅ No root required (if using AxManager)

### Steps:

1. **Download** `AXHyperBoost_v2.1_FPS_UNLOCK.zip`
2. Open **AxManager** app
3. Go to **Modules** section
4. Tap **Install from ZIP**
5. Select the downloaded file
6. Wait for installation to complete
7. **Reboot** your device
8. Access enhanced WebUI via AxManager → Plugins

---

## 🚀 Usage

### Via Enhanced WebUI:

1. Open AxManager → Plugins → AX HyperBoost
2. Beautiful anime-themed interface loads
3. See real-time FPS and system stats
4. Click "🔓 Unlock to MAX" to unlock FPS
5. Or click specific Hz lock buttons (60/90/120/144/165)
6. Switch performance profiles
7. View dashboard for detailed monitoring

### Via Terminal:

```bash
# Unlock FPS to device maximum
axengine --fps-unlock

# Lock to 120Hz
sh system/bin/axengine --fps-lock

# Check current FPS settings
axengine --fps-info

# Switch to gaming mode (auto-unlock FPS)
axengine --gaming

# Output example:
# Device Max Refresh Rate: 144Hz
# Display unlocked to 144Hz
# Game FPS unlocked to 144fps
# FPS UNLOCKED: Display=144Hz, Games=144fps
```

---

## 🎮 Performance Profiles

Each profile now has FPS settings:

| Profile | CPU | GPU | Display Hz | Game FPS | Battery |
|---------|-----|-----|------------|----------|---------|
| **Battery** | Powersave | Low | 60Hz | 60fps | ⚡ Best |
| **Balanced** | Performance | Adaptive | Max | Max | ⚡⚡ Good |
| **Gaming** | Max | Max | Max | Max | ⚡⚡⚡ Medium |
| **Extreme** | Locked Max | Locked Max | Max | Max | ⚡⚡⚡⚡ High |

---

## 🔍 FPS Unlock Technical Details

### What it does:

1. **Detects** maximum display refresh rate
2. **Unlocks** SurfaceFlinger frame limiter
3. **Disables** HWUI FPS caps
4. **Removes** VSync limitations
5. **Forces** games to use max FPS
6. **Optimizes** GPU rendering pipeline
7. **Logs** all settings to fps_settings.conf

### System Changes:

```bash
# Display unlock
- Sets min_refresh_rate = max_refresh_rate
- Disables auto-refresh switching
- Forces peak_refresh_rate via settings

# Game FPS unlock
- Disables frame_rate_cap
- Sets debug.hwui.target_fps to max
- Removes SurfaceFlinger back pressure
- Enables unsignaled latch
- Optimizes buffer age

# GPU optimization
- Sets render ahead to 4 frames
- Disables VSync
- Enables hardware acceleration
```

---

## ⚠️ Important Warnings

### **FPS Unlock Warnings:**

1. **Higher battery drain** - Unlocked FPS uses more power
2. **Increased heat** - More frames = more GPU work
3. **Not all games support high FPS** - Some are locked at 60fps
4. **Monitor temperature** - Check temps frequently
5. **May reduce battery life** - Use wisely

### **Recommended Usage:**

- 🎮 **Gaming:** Use FPS unlock
- 📱 **Daily use:** Lock to 60-90Hz
- 🔋 **Battery saving:** Lock to 60Hz
- 🌡️ **High temps:** Reduce to 60-90Hz

---

## 📊 How to Monitor FPS

### Method 1: WebUI Dashboard
1. Open AxManager → AX HyperBoost → Dashboard
2. See real-time FPS graph
3. Monitor temps and loads

### Method 2: Terminal
```bash
axengine --fps-info

# Output shows:
# Device Max Refresh Rate: 144Hz
# MAX_HZ=144
# CURRENT_DISPLAY_HZ=144
# CURRENT_GAME_FPS=144
# MODE=gaming
```

### Method 3: Settings
```bash
# Check current display Hz
settings get system peak_refresh_rate

# Check FPS limit
getprop debug.hwui.target_fps
```

---

## 🎨 WebUI Screenshots Description

### Main Control Panel:
- Stunning anime girl background (red/purple sunset theme)
- Glowing purple/violet UI elements
- Real-time system stats in cards
- FPS unlock/lock buttons
- Performance profile switcher

### Dashboard:
- Dark anime background
- Live FPS counter (huge display)
- Real-time FPS graph
- CPU/GPU/Memory stats
- Temperature monitoring
- Activity logs viewer

---

## 🐛 Troubleshooting

### FPS Not Unlocking:

**Problem:** Still capped at 60fps
**Solution:**
```bash
# Force unlock
axengine --fps-unlock

# Check device max Hz
axengine --fps-info

# Some devices need reboot
reboot
```

### Game Still at 60fps:

**Possible causes:**
1. Game has internal 60fps lock (some games do)
2. Need to enable high FPS in game settings
3. Device doesn't support higher Hz
4. Game not optimized for high FPS

**Solution:**
- Check game graphics settings
- Enable "High frame rate" in game
- Some games need specific app settings

### WebUI Not Showing Backgrounds:

**Problem:** Black screen or no images
**Solution:**
```bash
# Check if images exist
ls -lh /data/user_de/0/com.android.shell/axeron/plugins/ax.hyperboost/webroot/assets/

# Should show:
# background.png (9.5MB)
# banner.png (6.9MB)

# If missing, reinstall module
```

---

## 💡 Pro Tips

### For Maximum FPS:

1. **Use Gaming/Extreme profile**
2. **Close all background apps**
3. **Enable FPS unlock**
4. **Check in-game settings** (enable high FPS mode)
5. **Monitor temperature** every 15-30 mins
6. **Use gaming mode** in game settings

### For Battery Life:

1. **Lock to 60Hz** when not gaming
2. **Use Battery profile** for daily tasks
3. **Unlock only when needed**
4. **Monitor battery drain**

### For Best Experience:

1. **120Hz** - Best balance (gaming + battery)
2. **144Hz** - Competitive gaming
3. **60Hz** - Maximum battery life

---

## 📈 Performance Comparison

### Before v2.1 (No FPS Unlock):
- Display: 60Hz locked
- Games: 60fps cap
- Some stuttering
- Battery: Good

### After v2.1 (FPS Unlocked):
- Display: 144Hz unlocked
- Games: 144fps capable
- Buttery smooth
- Battery: Higher drain (worth it!)

---

## 🔄 Updating from v2.0

1. **Uninstall v2.0** (use uninstall.sh)
2. **Reboot**
3. **Install v2.1**
4. **Reboot again**
5. **Enjoy FPS unlock!**

Your settings will be fresh (recommended).

---

## 🗑️ Uninstall

Same uninstall.sh script works perfectly:

### Via AxManager:
1. Modules → AX HyperBoost → Uninstall
2. Reboot

### Via Terminal:
```bash
sh /data/user_de/0/com.android.shell/axeron/plugins/ax.hyperboost/uninstall.sh
reboot
```

Uninstall script automatically:
- ✅ Stops all services
- ✅ Restores FPS to default
- ✅ Re-locks display to auto
- ✅ Removes all configs
- ✅ Complete system restore

---

## 📚 Files and Logs

### FPS Configuration:
```
/config/fps_settings.conf
```

Contains:
- MAX_HZ (detected max Hz)
- CURRENT_DISPLAY_HZ
- CURRENT_GAME_FPS  
- MODE (current profile)

### Logs:
```
/logs/axengine.log
```

Shows all FPS unlock operations.

---

## 🎊 Credits & Thanks

**Module Created by:** Willy Gailo  
**Version:** 2.1 EXTREME FPS  
**Year:** 2026  
**Anime Artwork:** Beautiful backgrounds included!  

**Compatible With:**
- ✅ AxManager v1.04.00+
- ✅ Android 8.0+
- ✅ All SoCs (Snapdragon, MediaTek, Exynos, Tensor)

---

## 🚀 Final Notes

### v2.1 is the ULTIMATE performance module with:

- ✅ **Smart FPS unlock** - Auto-detects max Hz
- ✅ **Beautiful WebUI** - Anime-themed interface
- ✅ **Real-time monitoring** - Live FPS graphs
- ✅ **Complete control** - Lock/Unlock with one click
- ✅ **Safe operation** - Includes uninstall script
- ✅ **Professional quality** - Production-ready code

**Unlock your device's TRUE potential!** 🎮⚡

**Maximum Performance + Beautiful Interface = AX HyperBoost ULTIMATE v2.1!** 🚀

---

## 📞 Support

Having issues? Check:
1. Logs in `/logs/axengine.log`
2. FPS config in `/config/fps_settings.conf`
3. Run `axengine --fps-info` for diagnostics

**Enjoy your unlocked FPS!** 🔓🎮✨
