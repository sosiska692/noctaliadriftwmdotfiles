# Noctalia DriftWM Dotfiles
 Personal custom configuration for **DriftWM** on **Gentoo Linux**.

## Environment
- **OS:** Gentoo Linux
- **WM:** `driftwm`
- **Terminal:** `foot`
- **Font:** Nerd Fonts
- **Wallpaper:** Managed directly via `config.toml`

## Installation

1. Clone repository:
   ```bash
   git clone https://github.com/sosiska692/noctaliadriftwmdotfiles.git
   cd noctaliadriftwmdotfiles
   ```

2. Copy the configuration file to your config directory:
   ```bash
   mkdir -p ~/.config
   cp -r driftwm ~/.config/
   cp -r noctalia ~/.config/
   cp -r foot ~/.config/
   cp -r qt6ct ~/.config/
   cp -r qt5ct ~/.config/
   ```

3. Install the required packages (for Gentoo Linux):
   ```bash
   sudo emerge --ask sys-apps/xdg-desktop-portal gui-libs/xdg-desktop-portal-wlr gui-apps/wlr-randr gui-apps/foot gui-apps/grim dev-lang/rust sys-auth/seatd dev-libs/libinput x11-libs/libxkbcommon gui-apps/qt6ct
   ```
   > **Note:** Packages like `noctalia` and `wayland-satellite` are not in the official Portage tree and must be installed manually or via custom overlays.
   
   
**Keybinds**
super+e open dolphin
super+t open telegram
super+z open noctalia settings
super+b open browser





https://github.com/user-attachments/assets/2dc92ead-ec09-4ff4-9a79-77b79eec4051


