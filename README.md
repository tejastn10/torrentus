<p align="center">
  <img src="logo.svg" alt="Torrentus Logo">
</p>

# Torrentus ⚡

![Electron](https://img.shields.io/badge/Electron-Latest-47848F?logo=electron&logoColor=white)
![React](https://img.shields.io/badge/React-19%2B-61DAFB?logo=react&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-5%2B-007ACC?logo=typescript&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-6%2B-646CFF?logo=vite&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-yellow?logo=open-source-initiative&logoColor=white)

**Torrentus** is a modern, cross-platform torrent client built with Electron, React, and TypeScript.
Experience fast, reliable torrent downloading with a beautiful and intuitive user interface.

---

## Features 🌟

- **Modern Torrent Client**: Download and manage torrent files with ease
- **Cross-platform**: Works seamlessly on Windows, macOS, and Linux
- **Built with Modern Tech**:
  - **Electron Framework**: Native desktop experience
  - **React + TypeScript**: Responsive UI with type safety
  - **Vite-powered**: Lightning-fast development and optimized builds
- **Developer Experience**:
  - **BiomeJS**: Enforces consistent code quality.
  - **Hot Reloading**: See changes instantly during development
  - **Production Ready**: Optimized build configurations for all platforms

---

## Getting Started 🚀

### Prerequisites

Ensure you have the following installed:

- **Node.js**: v22 or later
- **npm**: v8 or later

---

### Installation ⚙️

1. Clone the repository:

   ```bash
   git clone https://github.com/tejastn10/torrentus.git
   cd torrentus
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Start the application in development mode:

   ```bash
   npm run dev
   ```

4. The Torrentus app will launch automatically.

---

## Development Workflow 💻

### IDE Setup

For the best development experience, we recommend:

- [VSCode](https://code.visualstudio.com/) with the following extensions:
  - [Biome](https://marketplace.visualstudio.com/items?itemName=biomejs.biome)

### Available Scripts

- **Development Mode**:

  ```bash
  npm run dev
  ```

- **Type Checking**:

  ```bash
  npm run typecheck
  ```

- **Linting**:

  ```bash
  npm run lint
  ```

- **Formatting**:

  ```bash
  npm run format
  ```

---

## Building for Production 🏗️

Torrentus comes with pre-configured build scripts for all major platforms:

### Windows

```bash
npm run build:win
```

### macOS

```bash
npm run build:mac
```

### Linux

```bash
npm run build:linux
```

### All Platforms

```bash
npm run build
```

Build outputs will be available in the `dist` directory.

---

## Project Structure 📁

```bash
torrentus/
├── .husky/                     # Git hooks configuration
│   ├── _/                      # Husky internals
│   ├── commit-msg              # Commit message validation hook
│   └── pre-commit              # Pre-commit hook
├── build/                      # Build-related files
│   ├── entitlements.mac.plist  # macOS app entitlements
│   ├── icon.icns               # macOS app icon
│   ├── icon.ico                # Windows app icon
│   └── icon.png                # Generic app icon
├── out/                        # Build output directory
│   ├── main/                   # Main process compiled files
│   └── preload/                # Preload scripts
├── resources/                  # Resource files
│   └── icon.png                # Application icon
├── src/                        # Source code
├── .gitignore                  # Git ignore configuration
├── .commitlintrc.yml           # Commitlint configuration
├── .nvmrc                      # Node version manager config
├── dev-app-update.yml          # Auto-updater dev configuration
├── electron-builder.yml        # Electron builder configuration
├── biome.json                  # Biome configuration
├── LICENSE.md                  # License file
├── package.json                # Project dependencies and scripts
├── package-lock.json           # Locked dependencies
├── README.md                   # Project documentation
├── tsconfig.json               # Main TypeScript configuration
└── vite.config.ts              # Vite configuration
```

---

## Customization 🔧

### Application Information

To customize your application details, modify the following files:

- `package.json`: Update name, description, version, and author
- `electron-builder.yml`: Configure build options for different platforms

### Styling and Theming

The project uses modern React practices for styling. You can integrate your preferred styling solution:

- CSS/SCSS Modules
- Styled Components
- Tailwind CSS
- Material UI or other component libraries

---

## License 📜

This project is licensed under the MIT License. See the [LICENSE](LICENSE.md) file for details.

---

## Acknowledgments 🙌

- Built with **Electron** for cross-platform desktop applications
- Powered by **Vite** for lightning-fast development
- Strengthened with **TypeScript** for type-safe development
- Made with ❤️ for efficient torrent downloading
