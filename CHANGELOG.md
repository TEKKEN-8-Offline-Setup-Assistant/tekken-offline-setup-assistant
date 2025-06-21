# 📅 Changelog

All notable changes to the TEKKEN 8 Offline Setup Assistant will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### 🔄 Planned Features
- Steam Deck compatibility improvements
- Additional controller support (Brook converters)
- Custom tournament bracket generator
- Replay analysis tools
- Multi-language interface support

## [2.1.0] - 2024-12-26

### ✨ Added
- **Universal Controller Support**: Added support for arcade sticks and custom HID controllers
- **Graphics Presets**: Pre-configured performance and quality profiles
- **Frame Data Overlay**: Real-time frame advantage display in training mode
- **Tournament Mode**: Local bracket management for community events
- **Audio Enhancement**: Spatial audio configuration and custom soundtrack support

### 🔧 Improved
- **Startup Performance**: 40% faster assistant launch time
- **Game Detection**: Automatic detection of Steam, Epic, and Microsoft Store installations
- **Settings Persistence**: Better configuration saving and loading
- **Error Handling**: More descriptive error messages and recovery options
- **UI Responsiveness**: Smoother animations and reduced input lag

### 🐛 Fixed
- Fixed issue with 4K resolution not saving properly
- Resolved controller input conflicts in multi-controller setups
- Fixed crash when TEKKEN installation path contains special characters
- Corrected HDR detection on Windows 11 systems
- Fixed memory leak in real-time frame data display

### 🔒 Security
- Enhanced digital signature verification
- Improved sandboxing for game file modifications
- Added integrity checks for configuration files

## [2.0.0] - 2024-11-15 🎉

### 🎮 Major Release - Complete Rewrite

#### ✨ Added
- **Modern UI**: Complete interface redesign with dark/light themes
- **Offline Training Lab**: Advanced practice tools with combo trainer
- **Local Versus Enhancement**: Improved split-screen and hot-seat modes
- **Character Unlock System**: Instant access to all fighters and customizations
- **Advanced Display Options**: Support for ultrawide, multi-monitor, and VRR displays
- **Input Display**: Real-time controller input visualization
- **Replay System**: Record and analyze offline matches

#### 🔧 Changed
- **Architecture**: Migrated from WinForms to WPF for better performance
- **Configuration**: JSON-based settings with backup and restore
- **Dependencies**: Updated to .NET 6.0 for better compatibility
- **Installation**: MSI installer for cleaner system integration

#### 🗑️ Removed
- Legacy Windows 7 support (now requires Windows 10+)
- Deprecated Xbox 360 controller workarounds
- Old configuration file format (automatic migration included)

## [1.9.2] - 2024-10-20

### 🐛 Fixed
- Critical fix for Steam version compatibility
- Resolved audio device switching issues
- Fixed controller rumble not working on some devices
- Corrected stage selection persistence

### 🔧 Improved
- Better error logging and diagnostic information
- Faster game launch sequences
- Improved compatibility with Windows 11 22H2

## [1.9.1] - 2024-09-28

### 🐛 Fixed
- Fixed installation detection for Epic Games Store version
- Resolved frame rate limiting not applying correctly
- Fixed crash on systems with multiple audio devices
- Corrected Japanese text display issues

### 📝 Documentation
- Added troubleshooting guide for common issues
- Updated controller configuration examples
- Improved installation instructions

## [1.9.0] - 2024-09-01

### ✨ Added
- **HDR Support**: Automatic HDR configuration for compatible displays
- **Accessibility Features**: Screen reader support and high contrast mode
- **Quick Launch**: Desktop shortcuts for different game modes
- **Backup System**: Automatic configuration and save file backups

### 🔧 Improved
- **Loading Times**: 25% faster assistant startup
- **Memory Usage**: Reduced RAM footprint by 30%
- **Network Detection**: Better offline mode verification
- **Controller Latency**: Optimized input processing

### 🐛 Fixed
- Fixed issues with Windows scaling above 125%
- Resolved audio crackling on certain sound cards
- Fixed controller profiles not loading correctly
- Corrected character unlock verification

## [1.8.0] - 2024-07-15

### ✨ Added
- **Multi-Language Support**: Japanese, Korean, Spanish localization
- **Tournament Organizer**: Basic bracket management tools
- **Performance Metrics**: FPS counter and frame time display
- **Custom Key Bindings**: Keyboard remapping for accessibility

### 🔧 Improved
- Enhanced controller auto-detection
- Better compatibility with Windows mixed reality
- Improved error messages and user guidance
- Faster configuration file processing

### 🐛 Fixed
- Fixed display mode switching on multi-monitor setups
- Resolved issues with DualSense controller haptics
- Fixed character customization not saving
- Corrected audio output device selection

## [1.7.0] - 2024-05-20 🚀

### ✨ Initial Public Release

#### Core Features
- **Offline Mode Activation**: Bypass online requirements for solo play
- **Controller Configuration**: Support for Xbox, PlayStation, and arcade sticks
- **Display Optimization**: Resolution, refresh rate, and windowed mode settings
- **Training Mode**: Enhanced practice environment with frame data
- **Local Versus**: Couch multiplayer without network requirements

#### Supported Platforms
- Windows 10/11 (64-bit)
- Steam, Epic Games Store, Microsoft Store versions
- Xbox One/Series and DualShock 4/DualSense controllers

#### Technical
- .NET Framework 4.8 runtime
- DirectX 12 compatible graphics
- Administrator rights for game file modifications

---

## 🔤 Version Naming Convention

- **Major** (X.0.0): Breaking changes, major feature additions
- **Minor** (X.Y.0): New features, significant improvements
- **Patch** (X.Y.Z): Bug fixes, small improvements, security updates

## 🏷️ Release Types

- 🎉 **Major Release**: Complete rewrites, architectural changes
- ✨ **Feature Release**: New capabilities and enhancements
- 🐛 **Bugfix Release**: Critical fixes and stability improvements
- 🔒 **Security Release**: Security patches and vulnerability fixes
- 📝 **Documentation Update**: Guide and help improvements

## 📦 Download Links

### Current Stable Release
- **Version**: 2.1.0
- **Release Date**: December 26, 2024
- **Download**: [GitHub Releases](https://github.com/TEKKEN-8-Offline-Setup-Assistant/tekken-offline-setup-assistant/releases/latest)
- **Checksums**: Available in release notes

### Beta Channel
- **Preview Builds**: Available for active community members
- **Discord Access**: Join #beta-testing channel
- **Feedback**: Submit via GitHub issues with `[BETA]` tag

## 🔄 Upgrade Guides

### From 1.x to 2.x
Major version upgrade with significant changes:
1. **Backup**: Export your current configuration
2. **Uninstall**: Remove old version completely
3. **Install**: Download and install v2.x
4. **Migrate**: Use built-in configuration migration tool
5. **Verify**: Test all your game modes and settings

### Minor Version Updates
- Automatic update notification in-app
- One-click update process
- Settings preserved automatically
- Rollback available if needed

---

**For detailed technical changes and API modifications, see our [Developer Changelog](docs/developer-changelog.md).** 