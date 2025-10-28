# Kew Music Player Controls

Your launcher now includes comprehensive controls for **kew**, a terminal-based music player with cover art support.

## How to Use

1. **Type `kew`** in the launcher to see all available controls
2. **Type `kew [command]`** to filter specific commands (e.g., `kew vol` for volume controls)
3. **Type `k [command]`** as a shortcut (e.g., `k play` for quick playback)

## Available Commands

### 🎵 Basic Playback Controls
- **play** - ▶️ Resume playback
- **pause** - ⏸️ Pause playback
- **toggle** - ⏯️ Toggle play/pause
- **stop** - ⏹️ Stop playback
- **next** - ⏭️ Next track
- **prev** - ⏮️ Previous track

### 🔊 Volume Controls
- **vol-up** - 🔊 Increase volume
- **vol-down** - 🔉 Decrease volume

### ⏩ Seek Controls
- **seek-forward** - ⏩ Seek forward 5 seconds
- **seek-backward** - ⏪ Seek backward 5 seconds

### 🎛️ Playback Modes
- **shuffle** - 🔀 Toggle shuffle mode
- **repeat** - 🔁 Toggle repeat mode

### 📁 Playlist Management
- **add-dir** - ➕ Add directory to playlist
- **add-file** - 🎵 Add file to playlist
- **list** - 📋 Show current playlist
- **clear** - 🗑️ Clear playlist
- **save** - 💾 Save current playlist

### 🔍 Library & Info
- **search** - 🔍 Search in music library
- **show** - ℹ️ Show current track info
- **rebuild** - 🔄 Rebuild music library

## Examples

1. **Quick play/pause**: Type `k toggle`
2. **Next track**: Type `k next` or `kew next`
3. **Volume control**: Type `kew vol` then select from volume options
4. **Browse all commands**: Type `kew` and browse available commands

## Requirements

- `kew` must be installed on your system
  - Arch Linux: `pacman -S kew` or `yay -S kew`
  - From source: https://github.com/ravachol/kew

## About Kew

Kew is a command-line music player with these features:
- Terminal-based UI with cover art support
- Supports various audio formats (MP3, FLAC, OGG, WAV, etc.)
- Playlist management
- Music library with search capabilities
- Gapless playback
- Customizable keybindings

## Technical Details

The commands use `kew` CLI under the hood:
- `kew play` - Resume playback
- `kew next` - Skip to next track
- `kew volup` - Increase volume
- `kew toggle` - Toggle play/pause
- etc.

All kew commands are executed in the background, so you can control your music without switching to the terminal where kew is running.

## Tips

- Kew must be running in a terminal for these controls to work
- Launch kew in a terminal with: `kew`
- You can control kew from the launcher while it runs in the background
- Use `k ` prefix for faster access (e.g., `k n` for next instead of `kew next`)