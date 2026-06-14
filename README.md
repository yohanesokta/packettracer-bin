# packettracer-bin

[![AUR](https://img.shields.io/badge/AUR-packettracer--bin-1793D1?style=for-the-badge&logo=archlinux&logoColor=white)](https://aur.archlinux.org/packages/packettracer-bin)
[![License](https://img.shields.io/badge/License-Proprietary-red?style=for-the-badge)](https://www.netacad.com/courses/packet-tracer)

An Arch Linux AUR package for **Cisco Packet Tracer 9.0** — a network simulation tool that lets you experiment with network setups and configurations.

## Installation

### Prerequisites
- Arch Linux (or Arch-based distribution)
- `base-devel` package group

### From AUR
```bash
yay -S packettracer-bin
# or
paru -S packettracer-bin
```

### From Source
```bash
git clone https://github.com/spaciousejar/packettracer-bin.git
cd packettracer-bin
makepkg -si
```

## Usage

Once installed, you can start Packet Tracer in a few ways:

- **Command line:** `packettracer`
- **Application menu:** Look for "Cisco Packet Tracer"

> Note: The first launch might take a bit longer as it sets up everything.

## Package Details

| Detail | Value |
|--------|-------|
| **Version** | 9.0 |
| **Architecture** | x86_64 |
| **Installation path** | `/opt/pt/` |
| **Maintainer** | [@spaciousejar](https://github.com/spaciousejar) |

This package uses the official Cisco Packet Tracer Debian package and sets up everything needed to run it on Arch Linux. It creates desktop entries and command-line shortcuts automatically.

## License

Cisco Packet Tracer is proprietary software. Make sure to check the EULA during installation for the terms of use.

## Contributing

If you run into any issues or have ideas for improvements, feel free to [open an issue](https://github.com/spaciousejar/packettracer-bin/issues) on GitHub or on the [AUR package page](https://aur.archlinux.org/packages/packettracer-bin).
