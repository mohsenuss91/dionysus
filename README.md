# Dionysus 🌓

**Dionysus** is PewDiePie’s first GitHub project — a personal Linux ricing and dotfiles repository.  
It reflects the journey from bloated, restrictive systems to a lightweight, free, and fully customizable Linux environment.  

The name comes from **Dionysus**, the Greek god of freedom, creativity, and breaking boundaries — symbolizing what Linux represents: **control, beauty, and independence**.

---

## 🌌 Philosophy

> “I installed Linux (so should you).” — PewDiePie  

This project is more than just configuration files:  
- It’s about **escaping Windows/MacOS bloat**.  
- It’s about **taking control of your environment**.  
- It’s about **creativity and aesthetics** (*ricing*).  
- It’s about **sharing knowledge** so anyone can join the open-source journey.  

---

## 📂 What’s Inside

- **`dotfiles/`** → shell configs, aliases, and scripts to make Linux efficient.  
- **`assets/`** → wallpapers, icons, themes, shaders, and styling resources.  
- **scripts/** (if present) → automation helpers, e.g., for Waybar or system tweaks.  

Together, these files replicate the minimal, beautiful, and functional setup seen in PewDiePie’s Linux journey.

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/pewdiepie-archdaemon/dionysus.git
cd dionysus
```

### 2. Explore Configs

```bash
cd dotfiles
ls
```

### 3. Apply Dotfiles

Example for Bash/Zsh:

```bash
ln -sv "$(pwd)/.bashrc" ~/.bashrc
ln -sv "$(pwd)/.zshrc" ~/.zshrc
source ~/.bashrc
```

For wallpapers/themes:

```bash
ln -sv ~/dionysus/assets/wallpaper.png ~/Pictures/wallpaper.png
```

---

## ✨ Features

- Minimalist Linux setup  
- Fast shell environment (aliases, scripts, configs)  
- Riced desktop (bar, wm, themes)  
- Public configs you can fork, adapt, and remix  

---

## 🤝 Contributing

Contributions are welcome!  
If you have new scripts, themes, or tweaks:

1. Fork this repo  
2. Create a branch: `git checkout -b feature/my-theme`  
3. Commit: `git commit -m "Added cool new theme"`  
4. Submit a pull request  

---

## 📺 Inspiration

This repo is connected to PewDiePie’s video:  
**[I installed Linux (so should you)](https://www.youtube.com/watch?v=pVI_smLgTY0)**  

The video explains the philosophy of Linux and why this project exists.  

---

## ⚖️ License

_No license specified yet. Consider MIT, GPL, or similar._  

---

*Dionysus is freedom. Dionysus is Linux. Dionysus is you taking control of your computer.* 🖤
