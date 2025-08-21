# 📦 Audio Journal I - Releases

This repository contains pre-built binaries and releases for Audio Journal I applications.

## 🚀 Latest Release

**Version**: v1.0.2 - Production Ready  
**Date**: August 21, 2025  
**Status**: ✅ Stable Release

## 📥 Downloads

### CLI Tool
- **File**: `audio-journal-cli`
- **SHA256**: `2ac482c13f2ac0bfb0571aa6caf7aeb6b63bc0c62ba536bb4740fb8785b55721`
- **Download**: [v1.0.2 Release](https://github.com/shyamalschandra/audio-journal-releases/releases/tag/v1.0.2)

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
# Record a new entry
audio-journal-cli record --duration 30 --notes "Meeting notes"

# List all entries
audio-journal-cli list --detailed

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

### 🔧 Technical Details
- **Platform**: macOS 13.0+
- **Architecture**: x86_64, arm64
- **Dependencies**: Swift 5.9+, macOS frameworks
- **Permissions**: Microphone, Location, iCloud

## 📊 Release History

### v1.0.2 (Current)
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
# Should output: 2ac482c13f2ac0bfb0571aa6caf7aeb6b63bc0c62ba536bb4740fb8785b55721
```

### Binary Information
```bash
# Check binary details
file audio-journal-cli
# Should show: Mach-O 64-bit executable

# Check version
audio-journal-cli --version
# Should show: 1.0.0
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
