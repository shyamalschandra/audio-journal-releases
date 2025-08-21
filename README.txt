# 📦 Audio Journal I - Releases

This repository contains pre-built binaries and releases for Audio Journal I applications.

## 🚀 Latest Release

**Version**: v1.1.0 - Advanced Features Release  
**Date**: August 21, 2025  
**Status**: ✅ Stable Release

## 📥 Downloads

### CLI Tool
- **File**: `audio-journal-cli`
- **SHA256**: `8aa6e8789e0db9f79df53e1536669ac1a96ea008ded560af0901b0ee303412a4`
- **Download**: [v1.1.0 Release](https://github.com/shyamalschandra/audio-journal-releases/releases/tag/v1.1.0)

### GUI Application
- **Status**: Coming Soon
- **Format**: macOS App Bundle (.app)

## 🔧 Installation

### Option 1: Homebrew (Recommended)
```bash
# Add the tap
brew tap shyamalschandra/audio-journal-i

# Install CLI
brew install audio-journal-cli

# Install GUI (when available)
brew install --cask audio-journal-i
```

### Option 2: Manual Installation
```bash
# Download the binary
curl -L -o audio-journal-cli https://github.com/shyamalschandra/audio-journal-releases/releases/download/v1.0.2/audio-journal-cli

# Make executable
chmod +x audio-journal-cli

# Move to PATH
sudo mv audio-journal-cli /usr/local/bin/
```

## 📋 Usage

```bash
# Record a new entry with tags
audio-journal-cli record --duration 30 --notes "Meeting notes" --tags "meeting,work,important"

# List all entries
audio-journal-cli list --detailed

# Search entries
audio-journal-cli search --query "meeting" --detailed

# Apply audio effects
audio-journal-cli effects <entry-id> --effect "noise reduction"

# Export entries
audio-journal-cli export --format json

# Manage tags
audio-journal-cli tags --action list

# Play an entry
audio-journal-cli play <entry-id>

# Delete an entry
audio-journal-cli delete <entry-id> --force
```

## 🎯 Features

### ✅ Production Features
- **Real Audio Recording**: AVCaptureSession integration
- **GPS Location**: Core Location framework
- **iCloud Sync**: CloudKit integration
- **Audio Playback**: AVAudioPlayer functionality
- **GUI Application**: SwiftUI interface
- **Complete CLI**: All commands working

### 🆕 Advanced Features (v1.1.0)
- **Speech-to-Text**: Automatic transcription with simulated AI
- **Audio Effects**: 9 different audio filters and enhancements
- **Export Options**: Multiple format support (JSON, CSV, Text)
- **Advanced Search**: Content-based filtering and search
- **Tags & Categories**: Organization features with smart suggestions

### 🔧 Technical Details
- **Platform**: macOS 13.0+
- **Architecture**: x86_64, arm64
- **Dependencies**: Swift 5.9+, macOS frameworks
- **Permissions**: Microphone, Location, iCloud

## 📊 Release History

### v1.1.0 (Current) - Advanced Features
- ✅ Speech-to-Text transcription with simulated AI
- ✅ Audio effects and filters (9 different types)
- ✅ Export functionality (JSON, CSV, Text formats)
- ✅ Advanced search with content filtering
- ✅ Tags and categories management
- ✅ Enhanced CLI with new commands

### v1.0.2
- ✅ Production-ready CLI with all features
- ✅ Real audio recording implementation
- ✅ GPS location services
- ✅ CloudKit integration
- ✅ Audio playback functionality
- ✅ Complete error handling

### v1.0.1
- ✅ Working CLI functionality
- ✅ File-based storage
- ✅ Basic audio recording simulation

### v1.0.0
- ✅ Initial CLI implementation
- ✅ Basic project structure

## 🔍 Verification

### SHA256 Checksum
```bash
# Verify download integrity
shasum -a 256 audio-journal-cli
# Should output: 8aa6e8789e0db9f79df53e1536669ac1a96ea008ded560af0901b0ee303412a4
```

### Binary Information
```bash
# Check binary details
file audio-journal-cli
# Should show: Mach-O 64-bit executable

# Check version
audio-journal-cli --version
# Should show: 1.1.0
```

## 🛠️ Development

### Building from Source
```bash
# Clone main repository
git clone https://github.com/shyamalschandra/Audio-Journal-I.git
cd Audio-Journal-I

# Build CLI
swift build -c release --product audio-journal-cli

# Build GUI
./scripts/build-gui.sh
```

### Release Process
1. Build binaries in main repository
2. Upload to this releases repository
3. Update Homebrew tap formulas
4. Create GitHub release with notes

## 📄 Copyright

Copyright (C) 2025, Shyamal Suhana Chandra - All rights reserved.

## 🔗 Links

- **Main Repository**: https://github.com/shyamalschandra/Audio-Journal-I
- **Homebrew Tap**: https://github.com/shyamalschandra/homebrew-audio-journal-i
- **Issues**: https://github.com/shyamalschandra/Audio-Journal-I/issues
- **Documentation**: See main repository for detailed docs

## 📞 Support

For support, issues, or questions:
- Open an issue in the main repository
- Check the documentation in the main repo
- Contact the maintainer

---

**Audio Journal I** - Production-ready audio journaling with location tracking and cloud sync.

*Last updated: August 21, 2025*
