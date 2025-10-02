# FasterEvenFaster
3day Solo GameJam Project

## Setup Instructions

This repository is ready to receive your Unity project. Follow these steps to add your Unity project:

### Option 1: Add Unity Project to This Repository

If you've already created a Unity project locally and want to add it here:

1. **Copy your Unity project files** to this repository directory:
   ```bash
   # Navigate to this repository
   cd /path/to/FasterEvenFaster
   
   # Copy your Unity project files here (Assets, ProjectSettings, Packages, etc.)
   # Make sure to copy the following essential folders:
   # - Assets/
   # - ProjectSettings/
   # - Packages/
   # - UserSettings/ (optional, but recommended)
   ```

2. **Commit and push your changes**:
   ```bash
   git add .
   git commit -m "Add Unity project files"
   git push origin main
   ```

### Option 2: Clone and Add Unity Project

If you haven't cloned this repository yet:

1. **Clone this repository**:
   ```bash
   git clone https://github.com/OfficialHwempire/FasterEvenFaster.git
   cd FasterEvenFaster
   ```

2. **Open Unity Hub** and add this folder as a Unity project, or copy your existing Unity project files here

3. **Commit and push**:
   ```bash
   git add .
   git commit -m "Add Unity project files"
   git push origin main
   ```

## What's Included

- ✅ Unity-specific `.gitignore` file (keeps repository clean)
- ✅ README with setup instructions

## Important Unity Files to Commit

When adding your Unity project, make sure these directories are present:
- `Assets/` - Your game assets, scripts, scenes, etc.
- `ProjectSettings/` - Unity project configuration
- `Packages/` - Package dependencies manifest

The `.gitignore` file is already configured to exclude:
- `Library/` - Unity's cache (auto-generated)
- `Temp/` - Temporary files
- `Obj/` - Build artifacts
- `.vs/` - Visual Studio files
- And other Unity-generated files

## Getting Started

After adding your Unity project:
1. Open the project in Unity Hub
2. Unity will regenerate the `Library/` folder automatically
3. Start developing your game!
