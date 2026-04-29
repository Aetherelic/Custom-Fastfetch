# Fastfetch Config

This repository contains my personal Fastfetch config used on my main PC, tailored for a cozy, lofi kind of vibe featuring a clean and aesthetically pleasing layout with custom ascii art, colors, and modules.

**Features include:**
- Aesthetic colour palette
- Detailed system information including GPU driver version and display information
- Music player integration

## Preview

> This may vary depending on the terminal used, chosen font, and terminal background.

<img width="810" height="578" alt="image" src="https://github.com/user-attachments/assets/57776db0-f26e-4f3b-bf5c-7915250dcdbe" />

## Installation

### 1. Install Fastfetch

Make sure you have Fastfetch installed on your system. If not, grab it from the official repo:

👉 https://github.com/fastfetch-cli/fastfetch

### 2. Install Git

Make sure you have Git installed:

```bash
sudo apt install git      # Debian/Ubuntu
sudo pacman -S git        # Arch
sudo dnf install git      # Fedora
```

### 3. Clone this repository

```bash
git clone https://github.com/Aetherelic/Custom-Fastfetch.git
```

### 4. Copy the config files

```bash
mkdir -p ~/.config/fastfetch
cp config.jsonc ~/.config/fastfetch/config.jsonc
cp -r logo ~/.config/fastfetch/
```

### 5. Run Fastfetch

```bash
fastfetch
```

Feel free to tweak the config to suit your style! 🎨
