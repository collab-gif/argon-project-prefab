# Roblox Studio Project

A modern Roblox game development template using Argon for local development workflo.

## 🥀 Overview

This is a Roblox game development project template that leverages Argon to create a powerful local development environment.
template is designed for both beginners and experienced Roblox developers who want a professional, scalable development environment.

## 📦 Installation

### 1. Clone the Repository

```bash
git clone https://github.com/collab-gif/argon-project-prefab.git
ren argon-project-prefab PROJECT_NAME
cd PROJECT_NAME
```

**Note**: Replace `PROJECT_NAME` with your desired project name.

### 2. Initialize Project Structure

#### macOS/Linux (Terminal)

```bash
mkdir -p src/{ReplicatedFirst,ReplicatedStorage,ServerScriptService,ServerStorage,StarterGui,StarterPlayer/{StarterCharacterScripts,StarterPlayerScripts},workspace}
```

#### Windows (Command Prompt)

```bat
mkdir src
cd src
mkdir ReplicatedFirst ReplicatedStorage ServerScriptService ServerStorage StarterGui StarterPlayer workspace
cd StarterPlayer
mkdir StarterCharacterScripts StarterPlayerScripts
```

### 3. Start Argon

```bat
argon serve -s
```

### 4. connect to argon on roblox plugin

## 🏗️ Project Structure

The project follows Roblox's standard service hierarchy:

```sh
📁PROJECT_NAME
├── 📄aftman.toml                       # Toolchain configuration
├── 📄default.project.json              # project configuration
└── 📁src                               # Source code directory
    ├── 📁ReplicatedFirst
    ├── 📁ReplicatedStorage
    ├── 📁ServerScriptService
    ├── 📁ServerStorage
    ├── 📁StarterGui
    ├── 📁StarterPlayer
    │   ├── 📁StarterCharacterScripts
    │   └── 📁StarterPlayerScripts
    └── 📁workspace
```

## 📚 Additional Resources

- extension
  - [Error Lens](https://marketplace.visualstudio.com/items?itemName=usernamehw.errorlens) - highlights errors and warnings inline for better code visibility
  - [Luau Language Server](https://github.com/JohnnyMorganz/luau-lsp) - provides advanced Luau language support with IntelliSense, autocomplete, and error detection
  - [StyLua](https://github.com/JohnnyMorganz/StyLua) - automatic code formatter for consistent Luau styling
- file sync tool
  - [Rojo](https://rojo.space/)
  - [Argon](https://argon.wiki/)
- toolchain / package manager
  - [Aftman](https://github.com/LPGhatguy/aftman) - cross-platform toolchain manager for Roblox development tools
  - [Wally](https://wally.run/) - package manager for Roblox with dependency management and registry
- resource
  - [Roblox API Reference 1](https://developer.roblox.com/en-us/api-reference) - official Roblox API documentation with comprehensive class references
  - [Roblox API Reference 2](https://robloxapi.github.io/ref/) - community-maintained API reference with enhanced search and filtering
  - [Roblox Developer Hub](https://developer.roblox.com/) - official learning resources, tutorials, and best practices
