# Gestion-Magasin

A modern, professional-grade store management system built with C++ and Qt 5.3.2. This desktop application provides an intuitive interface for inventory management, sales operations, and store administration.

## Overview

**Gestion-Magasin** is a comprehensive solution designed to streamline retail operations. Whether you're managing a small boutique or a larger retail operation, this application offers the tools needed to efficiently handle inventory, track sales, and maintain customer relationships through a clean, user-friendly interface.

## Features

- **Inventory Management**: Track stock levels, manage products, and organize warehouse operations
- **Sales Operations**: Process transactions, handle point-of-sale activities, and generate receipts
- **Modern UI**: Clean, intuitive interface built with Qt 5.3.2 for an excellent user experience
- **Desktop Application**: Cross-platform desktop solution with native performance
- **Data Management**: Robust data handling and persistence for reliable business operations

## Tech Stack

| Technology | Version | Purpose |
|-----------|---------|---------|
| **C++** | Modern C++ | Core application logic |
| **Qt** | 5.3.2 | GUI framework and cross-platform support |
| **QMake** | - | Build system |

## Getting Started

### Prerequisites

- **C++ Compiler**: Supporting modern C++ (GCC, Clang, or MSVC)
- **Qt 5.3.2**: Download from [qt.io](https://www.qt.io/download)
- **QMake**: Included with Qt installation
- **CMake** or **QMake**: Build system

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/JessyTsiriniaina/gestion-magasin.git
   cd gestion-magasin
   ```

2. **Build the project**:
   ```bash
   qmake
   make
   ```

   Or if using CMake:
   ```bash
   mkdir build
   cd build
   cmake ..
   make
   ```

3. **Run the application**:
   ```bash
   ./gestion-magasin
   ```

## 🔧 Development

### Building from Source

To build the project with debugging symbols:

```bash
qmake CONFIG+=debug
make
```

For release build with optimizations:

```bash
qmake CONFIG+=release
make
```

## Future Enhancements

Potential areas for expansion:

- Multi-user authentication and role-based access
- Database integration (SQLite, MySQL, PostgreSQL)
- Advanced reporting and analytics
- Mobile app companion
- Network/cloud synchronization
- Multi-language support
