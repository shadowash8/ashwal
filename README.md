## Introduction

<p align="center">
  <img src="https://github.com/user-attachments/assets/c35fe6fa-d919-4831-98c5-640a6bbc4637"
alt="cwal16 showcase" width="700"/>
</p>

`cwal` is a fast and lightweight command-line tool for generating dynamic color schemes from images. It extracts dominant colors from your chosen image and applies them to your terminal, applications, and other system components, providing a cohesive and visually appealing desktop experience.
For more details see the [Wiki](https://github.com/shadowash8/cwal16/wiki/Home) page.


## ✨ Features

- **Dynamic Color Generation**: Extracts a vibrant 16-color palette from any image
- **Advanced Backend Support**: Utilizes `imagemagick` or `libimagequant` for efficient color quantization
- **Lua Scripting Support**: Create custom backends using Lua scripts for advanced color quantization
- **Extensive Customization**: Fine-tune saturation, contrast, alpha transparency, and theme mode (dark/light)
- **Template-Based Output**: Generates color schemes for various applications using customizable templates
- **Automatic Application Reloading**: Seamlessly integrates with your system to apply changes instantly
- **Palette Preview**: View the generated color palette directly in your terminal
- **Random Image Selection**: Automatically pick a random image from any specified directory
- **Theme Management**: Load predefined themes or select random themes based on mode (dark/light/all)


## 🖼️ Showcase


- Dark mode

<p align="center">
  <img src="https://github.com/user-attachments/assets/ddc1b78b-a4fd-4607-8919-071f1ef4785f" width="260"/>
  <img src="https://github.com/user-attachments/assets/3f0a2d95-10a2-4713-bf29-d7e270e7f15c" width="260"/>
  <img src="https://github.com/user-attachments/assets/f41fd575-fde2-4fca-8445-9640d4f45476" width="260"/>
</p>
<p align="center">
  <img src="https://github.com/user-attachments/assets/45cebfd0-ba5c-4b91-a8fd-61fb44c1cbcd" width="260"/>
  <img src="https://github.com/user-attachments/assets/dc831594-36b5-4856-89d4-d248139d2949" width="260"/>
  <img src="https://github.com/user-attachments/assets/0098d56e-7620-4719-b6d0-90816ec1a40a" width="260"/>
</p>

- Light mode
<p align="center">
  <img src="https://github.com/user-attachments/assets/3a14f92f-64fe-411a-abb8-3b247907b594" width="260"/>
  <img src="https://github.com/user-attachments/assets/2c1406e2-737b-43d5-9855-4648948f1ef0" width="260"/>
  <img src="https://github.com/user-attachments/assets/2884d220-5c6c-4e57-b14b-a9be54d8fa9c" width="260"/>
</p>
<p align="center">
  <img src="https://github.com/user-attachments/assets/229f2491-25f7-4e3e-86fa-278c6207e59e" width="260"/>
  <img src="https://github.com/user-attachments/assets/2b585d8c-9fd3-4382-81e9-f25ebe5d39ab" width="260"/>
  <img src="https://github.com/user-attachments/assets/2ff60780-328d-4dbd-ba8e-4b4f776b510a" width="260"/>
</p>


## 🚀 Installation



`cwal16` requires `imagemagick`, `libimagequant`, and `lua` as dependencies.

### Prerequisites

Ensure the following libraries are installed on your system:

- `imagemagick`
- `libimagequant`
- `lua` (or `liblua-dev`)

**Ubuntu/Debian:**

```bash
sudo apt install imagemagick libimagequant-dev liblua5.4-dev
```

**Arch Linux:**

```bash
sudo pacman -S imagemagick libimagequant lua
```

**Fedora/RHEL:**

```bash
sudo dnf install ImageMagick-devel libimagequant-devel lua-devel
```

**macOS**
```bash
brew install imagemagick libimagequant lua
```

### Arch Linux (AUR)

Install directly from the AUR:

```bash
yay -S cwal16
# or
paru -S cwal16
```

### Building from Source

1. **Clone the repository:**

```bash
git clone https://github.com/shadowash8/cwal16.git
cd cwal16
```

2. **Build and install:**

*User-specific:*

```bash
mkdir build && cd build
cmake -DCMAKE_INSTALL_PREFIX=$HOME/.local ..
make
make install
```

*System-wide:*

```bash
mkdir build && cd build
cmake ..
make
sudo make install
```

## 📖 Documentation
- [Getting Started](https://github.com/shadowash8/cwal16/wiki/Getting-Started)
- [Templates](https://github.com/shadowash8/cwal16/wiki/Templates)
- [Advanced Usage](https://github.com/shadowash8/cwal16/wiki/Advanced)
- [Plugins](https://github.com/shadowash8/cwal16/wiki/Plugins)

## 🤝 Contributing

Report issues, request features, or contribute via PRs. See the GitHub repository for more info.

## 📄 License

Licensed under GNU GPL v3.0 — always free and open-source.

**Star the project on GitHub if you find it useful!**


## Special Thanks

- [cwal](https://github.com/nitinbhat972/cwal) by [nitinbhat972](https://github.com/nitinbhat972)

- [pywal](https://github.com/dylanaraps/pywal) by [dylanaraps](https://github.com/dylanaraps)

- [pywal16](https://github.com/eylles/pywal16) by [eylles](https://github.com/eylles)
