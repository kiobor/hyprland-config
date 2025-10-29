# Hyprland Configuration

Personal Hyperland configuration for **Lenovo IdeaPad Pro 5 14AHP9**

## Daily Workflow

cd ~/.config/hypr
git status
git diff
git add hyprland.conf
git commit -m "feat: enable blur for better aesthetics"  #example
git push

## Hardware

- CPU: AMD Ryzen 8845HS 
- GPU: AMD Radeon 780M (Integrated)
- Display: 2880x1800 120Hz (60Hz battery optimized)
- RAM: 16GB DDR5
- OS: Arch Linux

## Features

- Battery optimized (60Hz, No Blur, Minimal Animations)
- KDE Plasma integrations
- Touchpad gestures
- Good Power Management for laptop

## Essential Keybindings

- SUPER + RETURN: Terminal (Konsole)
- SUPER + D: App Launcher (wofi)
- SUPER + E: File Manager (Doplphin)
- SUPER + Q: Close Window
- SUPER + M: Log Out

## Installation

'''bash
git clone git@github.com:kiobor/hyprland-config.git ~/.config/hypr
hyprctl reload

