# 🚀 Starship Custom Themes: WhiteSur Dark & ThinkPad

A collection of clean, high-contrast, Powerline-styled configurations for the [Starship](https://starship.rs/) cross-shell prompt[cite: 1]. 

Both presets are **based directly on the Catppuccin Powerline preset and recolored** into custom palettes for modern dark terminal setups:
- 🍎 **WhiteSur Dark**: Recolored into macOS Monterey/Big Sur-inspired dark glass aesthetics with cool slate grays and system accents[cite: 1].
- 🔴 **ThinkPad Edition**: Recolored into the iconic ThinkPad matte Raven Black chassis styling with vibrant TrackPoint Red highlights[cite: 1].

---

## 🎨 Themes Overview

Both themes retain the structured, full-featured layout and symbol mapping of the **Catppuccin Powerline** preset, dynamically styled using dedicated custom palette definitions:

### 1. WhiteSur Dark
- **Base:** Catppuccin Powerline (Recolored)
- **Style:** Powerline pill / gradient segments[cite: 1]
- **Palette:** macOS Slate Grays (`#1c1f26` → `#3e4453`), Crisp White (`#ffffff`), System Blue (`#007aff`), Sky Blue (`#5ac8fa`), and Alert Red (`#ff453a`)[cite: 1].

### 2. ThinkPad Edition
- **Base:** Catppuccin Powerline (Recolored)
- **Style:** Sleek matte carbon Powerline segments[cite: 1]
- **Palette:** ThinkPad TrackPoint Red (`#e2231a`), Matte Carbon (`#1f2124`), Deep Chassis Gray (`#2b2e34`), and Raven Black (`#141618`)[cite: 1].

---

## 📦 Prerequisites

1. **Starship Prompt** installed [cite: 1]:
   ```sh
   curl -sS https://starship.rs/install.sh | sh
   ```
2. A **Nerd Font** installed and enabled in your terminal (e.g., *JetBrainsMono Nerd Font*, *FiraCode Nerd Font*, or *MesloLGS NF*) for OS glyphs and powerline separators (``, ``, ``) [cite: 1].

---

## 🚀 Installation & Switching Themes

### Clone the Repository
```sh
git clone https://github.com/itsmedeimo/Starship.git ~/starship-presets
cd ~/starship-presets
```

### Apply a Theme

#### Option A: Apply WhiteSur Dark
```sh
cp configs/bigsur-dark/starship.toml ~/.config/starship.toml
source ~/.bashrc   # Or ~/.zshrc / source ~/.config/fish/config.fish
```

#### Option B: Apply ThinkPad Edition
```sh
cp configs/thinkpad/starship.toml ~/.config/starship.toml
source ~/.bashrc   # Or ~/.zshrc / source ~/.config/fish/config.fish
```

---

## ⚙️ Quick Shell Setup

Make sure Starship is initialized in your shell config [cite: 1]:

- **Bash (`~/.bashrc`):**
  ```sh
  eval "$(starship init bash)"
  ```
- **Zsh (`~/.zshrc`):**
  ```sh
  eval "$(starship init zsh)"
  ```
- **Fish (`~/.config/fish/config.fish`):**
  ```fish
  starship init fish | source
  ```

---

## 📂 Repository Structure

```text
.
├── README.md
├── configs/bigsur-dark/starship.toml   # WhiteSur Dark config
└── configs/thinkpad/starship.toml        # ThinkPad config
```

---

## 📜 License

MIT © itsmedeimo