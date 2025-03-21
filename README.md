# Delta Apps - Core Applications for DeltaDE


  [![License: GPL-3.0](https://img.shields.io/badge/License-GPL%203.0-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
  [![Python](https://img.shields.io/badge/Python-70.2%25-3776AB?logo=python)](https://www.python.org/)
  [![C++](https://img.shields.io/badge/C++-11%25-00599C?logo=cplusplus)](https://isocpp.org/)

## Overview

Delta Apps is a collection of modern desktop applications specifically designed for the DeltaDE (Delta Desktop Environment). These applications are built with performance, usability, and aesthetic consistency in mind, following the NurOS design philosophy.

## Applications

### System
- **Delta Command** - Modern terminal emulator with multi-tab support
- **Wifi Manager** - Wireless network management utility
- **Astrum** - System utility

### Media
- **Delta Media Player** - Feature-rich media player
- **Photo Viewer** - Image viewing application
- **Notepad** - Simple text editor

### Education
- **Delta Math** - Mathematical calculations and utilities

### Games
- **Four Balls in a Row** - Classic connection game
- **Juldyz Game** - Space shooter game
- **Ping Pong** - Classic table tennis game
- **Tic Tac Toe** - Available in multiple implementations:
  - C++
  - Python
  - PHP
  - Lua
  - Web (HTML/JS/CSS)

## Technical Stack

- **Languages**:
  - Python (70.2%)
  - C++ (11%)
  - Makefile (9.6%)
  - C (3.4%)
  - PHP (1.6%)
  - JavaScript (1.6%)
  - Other (2.6%)

- **Core Technologies**:
  - Qt6 Framework
  - QTermWidget
  - Python Libraries
  - Custom Delta Components

## Installation

### Dependencies
```bash
# For NurOS / Arch Linux
sudo pacman -S qt6-base qt6-tools qtermwidget cmake ninja pkg-config noto-fonts-mono
```

### Building from Source
```bash
# Clone the repository
git clone https://github.com/NurOS-Linux/ddeapps.git
cd ddeapps

# Build Delta Command
cd command
chmod +x build.sh
./build.sh
```

## Project Structure
```
delta-apps/
├── command/          # Delta Command Terminal
├── astrum/          # System Utility
├── math/            # Delta Math Application
├── mediaplayer/     # Delta Media Player
├── manger_wifi/     # Wifi Manager
├── PhotoViewer/     # Photo Viewer
├── Notepad/         # Text Editor
├── games/           # Game Collection
│   ├── four-balls-in-a-row/
│   ├── juldyzgame/
│   ├── pingpong/
│   └── tictactoe/
└── app_concept/     # Application Prototypes
```

## Development

### Requirements
- C++17 compiler (Clang recommended)
- Qt6 development packages
- CMake 3.16+
- Ninja build system
- Make build system
- Python 3.8+

## Contributing

1. Fork the repository
2. Create feature branch (`git checkout -b feature/amazing-feature`)
3. Commit changes (`git commit -m 'Add some amazing feature'`)
4. Push to branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the GNU General Public License v3.0 - see the [LICENSE](LICENSE) file for details.

## Contact

- Repository: [https://github.com/NurOS-Linux/ddeapps](https://github.com/NurOS-Linux/ddeapps)
- NurOS Website: [https://nuros.org](https://nuros.org)



## Описание на русском

Delta Apps - это набор основных приложений для окружения рабочего стола DeltaDE. Проект включает:

### Системные приложения
- **Delta Command** - Современный терминал с поддержкой вкладок
- **Wifi Manager** - Утилита управления Wi-Fi
- **Astrum** - Системная утилита

### Мультимедиа
- **Delta Media Player** - Медиаплеер
- **Photo Viewer** - Просмотрщик изображений
- **Notepad** - Текстовый редактор

### Образование
- **Delta Math** - Математические утилиты

### Игры
- **Four Balls in a Row** - Классическая игра "4 в ряд"
- **Juldyz Game** - Космический шутер
- **Ping Pong** - Настольный теннис
- **Tic Tac Toe** - Крестики-нолики (в нескольких реализациях)
