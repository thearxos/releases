
# <p align="center">🪐 ArxOS v2026.1 ~ Venus</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/thearxos/thearxos.github.io/main/ARXOS.png" alt="ArxOS Logo" width="300" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Version-v2026.1-blue?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Codename-Venus-purple?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Release_Date-January_2026-green?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Type-Rolling_LTS-red?style=for-the-badge" />
</p>

<p align="center">
  <strong>First Official Release - Rolling LTS</strong><br>
  Where Performance Meets Penetration Testing
</p>

---

## 🌟 Release Information

- **Version**: v2026.1
- **Codename**: Venus ♀️
- **Release Date**: January 2026
- **Release Type**: Rolling LTS (Long Term Support)
- **Base**: ArchBang + Arch Linux
- **Kernel**: Latest Arch Linux Kernel
- **Desktop**: KDE Plasma 6 (Minimalistic)

---

## 🎯 What is Venus?

**Venus** is the inaugural release of ArxOS, marking the beginning of a new era in penetration testing distributions. Named after the second planet from the sun, Venus represents brightness, beauty, and power - exactly what ArxOS brings to the security community.

This is our **first rolling LTS release**, meaning you'll receive continuous updates while maintaining system stability. Once you install Venus, you'll always have the latest tools and features through regular updates.

---

## ✨ Highlights

### 🔐 Complete Security Arsenal
- **2800+ BlackArch Tools** pre-installed and configured
- Complete penetration testing suite from reconnaissance to reporting
- All tools tested and working out-of-the-box
- No need to download or configure anything

### ⚡ Performance Optimized
- **Custom CPU Governor** for maximum performance
- Optimized kernel parameters for speed
- Minimal resource usage (~800MB RAM idle)
- Fast boot times (<30 seconds on NVMe SSD)

### 🎨 Beautiful Desktop
- **KDE Plasma 6** with minimalistic configuration
- Custom ArxOS dark theme with grey accents
- ARXOS wallpaper and branding throughout
- Optimized panel layout for pentesting workflow

### 💻 Developer Experience
- **Oh-My-Zsh** with custom configuration
- 50+ productivity aliases (arxos-update, arxos-clean, etc.)
- Syntax highlighting and auto-completion
- Custom prompt: `🧞マシン👀username`

---

## 📦 What's Included

### Base System
- **OS Base**: ArchBang (Lightweight Arch Linux)
- **Security Tools**: Complete BlackArch repository (2800+ tools)
- **Desktop**: KDE Plasma 6 (minimalistic setup)
- **Shell**: Zsh with Oh-My-Zsh framework
- **Kernel**: Latest Arch Linux rolling release kernel

### Pre-installed Applications
```
Desktop Environment: KDE Plasma 6
Terminal: Konsole with Oh-My-Zsh
Browser: Brave (privacy-focused) / Firefox
Code Editors: VSCode, Kate, Vim, Neovim
File Manager: Dolphin (KDE)
System Monitor: btop, htop, nvtop
Package Manager: pacman + yay (AUR support)
Network Tools: NetworkManager, OpenVPN, WireGuard
Performance: CPU Governor (pre-installed)
Display: Fastfetch with random anime logos
All BlackArch Tools: 2800+ pre-installed
```

### Custom Tools & Scripts
- **CPU Governor**: C-based performance controller
- **Custom Aliases**: 50+ productivity shortcuts
- **ArxOS Utilities**: System management scripts
- **Fastfetch Config**: Custom branding with anime logos

---

## 🚀 New Features

### System
- ✅ Complete ArchBang base installation
- ✅ BlackArch repository integration (all 2800+ tools)
- ✅ KDE Plasma 6 desktop environment
- ✅ Custom ArxOS theme and branding
- ✅ Optimized system configuration

### Performance
- ✅ CPU Governor pre-installed and configured
- ✅ Performance mode aliases (arxos-boostmode)
- ✅ Optimized kernel parameters
- ✅ Fast boot configuration
- ✅ Memory management optimization

### Tools & Utilities
- ✅ 2800+ BlackArch tools pre-installed
- ✅ All tools tested and working
- ✅ Custom aliases for common tasks
- ✅ Oh-My-Zsh with plugins
- ✅ Syntax highlighting and auto-completion

### Desktop Experience
- ✅ KDE Plasma 6 minimalistic setup
- ✅ Custom ArxOS dark theme
- ✅ ARXOS wallpapers (SDDM, Desktop, GRUB)
- ✅ Fastfetch with random anime logos
- ✅ Optimized panel and widgets

### Installation
- ✅ Calamares graphical installer
- ✅ Full disk encryption support (LUKS)
- ✅ Automatic partitioning option
- ✅ Manual partitioning support
- ✅ Live environment with persistence

---

## 🛠️ System Requirements

### Minimum Requirements
- **CPU**: 64-bit processor (2 cores, 2GHz+)
- **RAM**: 4GB (8GB recommended)
- **Storage**: 50GB free space
- **Graphics**: Any GPU with 512MB VRAM
- **Network**: Ethernet or WiFi adapter

### Recommended Specifications
- **CPU**: Intel i5/AMD Ryzen 5 or better (4+ cores)
- **RAM**: 16GB+ for running multiple tools
- **Storage**: 150GB+ SSD (NVMe preferred)
- **Graphics**: Dedicated GPU for GPU cracking (hashcat)
- **Network**: Dual network cards for MitM attacks

### Tested Hardware
✅ **HP EliteBook 840 G6** (Primary development machine)
- Intel Core i7-8665U (4C/8T)
- 32GB DDR4 RAM
- 1TB NVMe SSD
- Intel UHD Graphics 620
- **Status**: Fully working, excellent performance

---

## 💿 Download

### ISO Information
- **Size**: ~30GB+ (all tools pre-installed)
- **Type**: Hybrid ISO (USB/DVD bootable)
- **Architecture**: x86_64 only
- **Format**: ISO 9660

### Download Links
**Coming Soon** - Venus ISO will be available for download shortly

### Verification
```bash
# SHA256 checksum (will be provided with download)
sha256sum arxos-v2026.1-venus-x86_64.iso

# Verify signature
gpg --verify arxos-v2026.1-venus-x86_64.iso.sig
```

### Creating Bootable USB
```bash
# Linux (using dd)
sudo dd if=arxos-v2026.1-venus-x86_64.iso of=/dev/sdX bs=4M status=progress

# Or use balenaEtcher, Ventoy, Rufus (Windows)
```

---

## 📋 Installation Guide

### Live Environment Credentials
- **Username**: `live`
- **Password**: `evolution`
- **Root Password**: `evolution`

### Installation Steps
1. Boot from USB/DVD
2. Select "Install ArxOS" from boot menu
3. Follow Calamares installer:
   - Choose language and timezone
   - Configure partitioning (automatic or manual)
   - Optional: Enable disk encryption (LUKS)
   - Create user account
   - Set hostname and network
   - Install GRUB bootloader
4. Reboot and enjoy ArxOS!

### Recommended Partition Scheme
```
/boot     - 512MB  (ext4, unencrypted)
/         - 80GB+  (ext4 or btrfs)
/home     - Rest   (ext4 or btrfs)
swap      - 8-16GB (optional, depends on RAM)
```

---

## 🔧 Post-Installation

### First Boot Checklist

1. **Update System**
   ```bash
   arxos-update
   # Or manually:
   sudo pacman -Syu
   yay -Syu
   ```

2. **Enable Performance Mode**
   ```bash
   sudo cpu-governor performance
   sudo systemctl enable cpu-performance.service
   ```

3. **Configure Mirrors (Optional)**
   ```bash
   arxos-mirrors
   ```

4. **Verify Tools**
   ```bash
   # All 2800+ tools are pre-installed
   nmap --version
   metasploit --version
   burpsuite --version
   ```

5. **Configure Network**
   ```bash
   # WiFi setup
   wifi                    # List networks
   wifi-connect "SSID"     # Connect
   ```

---

## 🎨 Customization

### Included Themes
- **ArxOS Dark** - Default dark theme with grey accents
- **ARXOS Wallpaper** - Custom wallpaper for all screens
- **Breeze Dark Icons** - Modern icon theme
- **Custom Fastfetch** - Random anime logos

### Terminal Experience
- **Shell**: Zsh with Oh-My-Zsh
- **Prompt**: `🧞マシン👀username`
- **Theme**: Powerlevel10k compatible
- **Plugins**: git, zsh-syntax-highlighting, zsh-autosuggestions

### Custom Aliases
Over 50 custom aliases including:
- `arxos-update` - Full system update
- `arxos-clean` - Clean package cache
- `arxos-boostmode` - Maximum CPU performance
- `whatsmyip` - Show external IP
- `portsopen` - Show listening ports
- `sysinfo` - Comprehensive system info

---

## 📊 Performance Benchmarks

### Boot Performance
- **Boot Time**: <30 seconds (NVMe SSD)
- **Login to Desktop**: ~5 seconds
- **Total to Usable**: <35 seconds

### Resource Usage (Idle)
- **RAM Usage**: ~800MB
- **CPU Usage**: <5%
- **Disk Usage**: ~80-100GB (full installation)

### CPU Governor Impact
- **Compilation Speed**: +10-15% faster
- **Gaming FPS**: +15-20% average
- **Frame Time 1% Low**: -30-40% (smoother)
- **Benchmark Scores**: +5-10% improvement

---

## 🐛 Known Issues

### Currently Known
No critical issues in this release.

### Reporting Bugs
Found a bug? Please report it:
- **GitHub Issues**: [github.com/thearxos/bugs-issues](https://github.com/thearxos/bugs-issues)
- **Email**: contact.arxos@proton.me

---

## 🔄 Update Path

Venus is a **Rolling LTS** release. You don't need to reinstall for future versions.

### Updating to Future Releases
```bash
# Regular updates maintain your system
arxos-update

# No reinstallation needed
# You'll automatically receive all updates
```

Future releases (Mars, Jupiter, etc.) will be rolling updates, not new installations.

---

## 📚 Documentation

### Resources
- **Website**: [thearxos.github.io](https://thearxos.github.io)
- **Main README**: [ArxOS Documentation](https://github.com/thearxos/thearxos.github.io)
- **Tools & Scripts**: [Custom Scripts Repository](https://github.com/thearxos/tools-scripts)
- **Bug Tracker**: [Issues Repository](https://github.com/thearxos/bugs-issues)

### Community
- **Email**: contact.arxos@proton.me
- **GitHub**: [github.com/thearxos](https://github.com/thearxos)
- **Developer**: [0xb0rn3.github.io](https://0xb0rn3.github.io)

---

## 🙏 Credits & Acknowledgments

### Built On
- **ArchBang** - Lightweight Arch Linux base
- **Arch Linux** - Rolling release foundation
- **BlackArch** - Security tools repository
- **KDE Plasma** - Desktop environment

### Special Thanks
- **ArchBang Team** - For the excellent Arch base
- **BlackArch Team** - For comprehensive security tools
- **KDE Team** - For beautiful Plasma 6
- **Community** - For testing and feedback

---

## 📜 License

ArxOS is built on open-source software:
- **Arch Linux**: GPL License
- **BlackArch**: GPL License
- **KDE Plasma**: GPL/LGPL
- **Custom Scripts**: MIT License

---

## 🔗 Links

- **Download**: Coming Soon
- **Website**: [thearxos.github.io](https://thearxos.github.io)
- **GitHub**: [github.com/thearxos](https://github.com/thearxos)
- **Bug Reports**: [github.com/thearxos/bugs-issues](https://github.com/thearxos/bugs-issues)
- **Developer**: [0xb0rn3.github.io](https://0xb0rn3.github.io)

---

## 🎉 Thank You

Thank you for choosing ArxOS v2026.1 ~ Venus!

This is just the beginning. We're committed to:
- Regular updates and improvements
- Listening to community feedback
- Adding new features and tools
- Maintaining system stability
- Providing excellent support

**Welcome to the ArxOS family!** 🛡️

---

<p align="center">
  <strong>Made with 🪐 for Security Professionals</strong><br>
  <em>© 2026 ArxOS • Created by oxbv1 | 0xb0rn3</em>
</p>

<p align="center">
  <a href="https://github.com/0xb0rn3">
    <img src="https://img.shields.io/badge/GitHub-0xb0rn3-181717?style=for-the-badge&logo=github" />
  </a>
  <a href="https://0xb0rn3.github.io">
    <img src="https://img.shields.io/badge/Portfolio-0xb0rn3-4285F4?style=for-the-badge&logo=google-chrome" />
  </a>
  <a href="mailto:contact.arxos@proton.me">
    <img src="https://img.shields.io/badge/Email-ArxOS-8B89CC?style=for-the-badge&logo=protonmail" />
  </a>
</p>

---

**ArxOS v2026.1 ~ Venus** — *The beginning of something beautiful* 🪐
