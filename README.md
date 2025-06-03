<h1 align="center">⋆.˚ ☾⭒.˚ ✮ ⋆ ˚｡𖦹 ⋆｡°✩ MonochromeRice ✮ ⋆ ˚｡𖦹 ⋆｡°✩ ⋆.˚ ☾⭒.˚</h1>
<table align="center">
  <tr>
    <td colspan="2"><img src="https://github.com/user-attachments/assets/d7fb271d-07dd-4830-af19-91ced39ef8b9"></td>
  </tr>
  <tr>
    <td colspan="1"><img src="https://github.com/user-attachments/assets/d0d0d596-f04f-4eb5-b335-e4a0326befdb"></td>
    <td colspan="1"><img src="https://github.com/user-attachments/assets/ad006f3b-065d-46ba-a7a6-e406bbeefaf7"></td>
  </tr>
  <tr>
    <td colspan="1"><img src="https://github.com/user-attachments/assets/892fec36-fa8f-47cc-bb52-5a88d58ea00c"></td>
    <td colspan="1"><img src="https://github.com/user-attachments/assets/e70bebab-9419-4fc7-83b6-3de163aaef0e"></td>
  </tr>
</table>

## Prerequisites for This Hyprland Dotfiles Configuration

To get this Hyprland setup working as intended, you'll need the following software and components installed on your Arch Linux (or similar) system.

---

### 1. Core System & Desktop Environment

* **Hyprland:** The Wayland compositor itself.
* **Arch Linux Base System:** (Assumed as the base OS)
* **Polkit Agent:** `polkit-gnome` (specifically `polkit-gnome-authentication-agent-1`)
* **dbus:** For system services and environment variable propagation.
* **XWayland:** `xorg-xwayland` for compatibility with X11 applications.
* **XDG Desktop Portals:**
    * `xdg-desktop-portal-hyprland` (Hyprland-specific integration)
    * `xdg-desktop-portal` (Core XDG portal)
    * `xdg-desktop-portal-gtk` (For GTK applications, if used)
* **Login Manager (Optional):** Such as `SDDM`, `GDM`, or `LightDM` configured to launch Hyprland sessions.

---

### 2. Shell & Utilities

* **Zsh:** Your preferred shell.
* **Oh My Zsh:** (Required if your `.zshrc` relies on it for plugins/themes)
* **Powerlevel10k:** Zsh theme (`p10k`).

---

### 3. Custom Programs & Scripts

* **Terminal Emulator:** `kitty`
* **File Manager:** `thunar`
* **Application Launcher:** `rofi`
* **Screenshot Tool:** `hyprshot`
* **Screen Locker:** `hyprlock`
* **Status Bar:** `waybar`
* **Wallpaper Setter:** `swww`
* **Audio Control:** `pipewire`, `pipewire-pulse`, `wireplumber` (for `wpctl`)
* **Media Control:** `playerctl`
* **Brightness Control:** `brightnessctl`
* **Terminal Animations/Monitors (specific to your autostart):**
    * `unimatrix`
    * `cava`
    * `bpytop`
* **Media Player:** `mpv` (for GIF playback)
* **Custom Scripts:**
    * `theme-switcher.sh` (at `~/Documents/themes/theme-switcher.sh` or update path)
    * `powermenu.sh` (at `~/.config/rofi/powermenu.sh` or update path)
* **Image Assets:**
    * `wallpaper.jpg` (located in the same directory as your Hyprland config, or specify full path)
    * `lain.gif` (located in the same directory as your Hyprland config, or specify full path)

---

### 4. Fonts & Icons

* **Nerd Fonts:** For Powerlevel10k symbols and Waybar icons (e.g., FiraCode Nerd Font, JetBrains Mono Nerd Font).
* **Icon Fonts:** (e.g., Font Awesome, if used by Waybar or Rofi)
* **System Fonts:** Any general purpose fonts you prefer.

---

### 5. Dotfile Management

* **Git:** For cloning and version control.
* **GNU Stow:** For symlinking dotfiles.

---

### Installation Notes:

* Ensure necessary permissions for `brightnessctl` (e.g., user in `video` group, udev rules).
* Some tools might be available via your distribution's official repositories, while others might require an AUR helper (e.g., `yay`, `paru`) or manual installation (e.g., `pip` for Python scripts).

---
<div align="center">
  <img src="assets/important.gif" alt="Lain_dance">
</div>

<br>

<div align="center">

[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://yion-dev.vercel.app/)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/thu-ta-naing-83b5222b0/)
[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/yion69.com)

</div>

---
