## [1.0.0] - 2026-03-23

### 🚀 Features

- Remove asserts folder and add to .gitignore
- Add alpha value to cache and config
- Implemented theme loading and minor changes
- Add support for custom backends using lua scripting
- Add gif support for random image path
- Add Neovim, Quickshell, and Dunst templates
- Add Cava template
- Add version flag and rename project to cwal16
- Add gtk and libadwaita templates
- Add qt templates

### 🐛 Bug Fixes

- Properly remove asserts folder from Git tracking
- Initialize list_theme flag in CliArgs
- Improve template directory handling and memory management
- Improved GIF reading to load only first frame
- Ensure config directory and subdirectories are created
- Update the CMakeList.txt for new structure
- Replace strtok with strtok_r for thread safety
- Replace strcpy with snprintf for buffer safety
- Replace unsafe functions with safer alternatives and define constants for magic numbers
- Preserve random image filename casing
- Naming issues

### 💼 Other

- New project name

### 🚜 Refactor

- Replace system() with fork/exec for hook execution

### 📚 Documentation

- Add Lua scripting support section and example to README.md
- Add lua dependency info
- Add aur install option in readme
- Update readme to link to wiki page for more info
- Update reademe formatting

### ⚡ Performance

- Reduce palette generation overhead

### 🎨 Styling

- Format code according to cpplint
- Removed unnecessary header and blank line
- Fix rofi templates formatting according to rasi format
- Differentiate between dwl colors with bar and without bar
- Fix foot term deprecation
- Fix dwl colors formatting

### 🧪 Testing

- Release workflow

### ⚙️ Miscellaneous Tasks

- Nix flake
- Restructure the project
- Add automated changelog and release workflow
- Update changelog
- Remove 'Release' prefix from release title
