# Running Ariana IDE in Development Mode

Use these simple one-command operations for development:

## Development Commands

```bash
# 🚀 Run backend server (installs deps + runs)
just dev-backend

# 🎨 Run frontend Tauri app only (no CLI login needed)
just dev-frontend

# 🔐 Run frontend via CLI login (requires backend running)
just dev-cli
```

## Build Commands

```bash
# 📦 Build with custom config
just build example-configs/ariana-beta.json

# 🏗️ Platform builds
just build-windows
just build-macos  
just build-linux
```

## Other Commands

```bash
# 🧹 Format all code
just format
```

That's it! All dependencies are automatically installed and configured by the `just` commands.