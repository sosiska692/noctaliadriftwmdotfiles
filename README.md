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
   ```

3. Install the required packages (for Gentoo Linux):
   ```bash
   sudo emerge --ask sys-apps/xdg-desktop-portal gui-libs/xdg-desktop-portal-wlr gui-apps/wlr-randr gui-apps/foot gui-apps/grim dev-lang/rust sys-auth/seatd dev-libs/libinput x11-libs/libxkbcommon
   ```
   > **Note:** Packages like `noctalia` and `wayland-satellite` are not in the official Portage tree and must be installed manually or via custom overlays.
   
   
**Keybinds**
super+e open dolphin
super+t open telegram
super+z open noctalia settings
super+b open browser





**Preview**
[![watch preview on my yt channel](https://youtube.com)](https://youtu.be/0MS3WMkaikk?si=ks1QpbyDKYPsp5ay)
