# Noctalia DriftWM Dotfiles
 Personal custom configuration for **DriftWM** on **Gentoo Linux**.

## Environment
- **OS:** Gentoo Linux
- **WM:** `driftwm`
- **Terminal:** `foot`
- **Font:** Nerd Fonts
- **Wallpaper:** Managed directly via `config.toml`

## Installation
1. Copy the configuration file to your config directory:
   ```bash
   mkdir -p ~/.config/driftwm
   cp config.toml ~/.config/driftwm/config.toml

 2. Needed packages (in gentoo)
wlr-randr,
dev-lang/rust,
noctalia,
grim,
wayland-satellite,
foot,gui-libs/xdg-desktop-portal,gui-libs/xdg-desktop-portal-wlr,sys-auth/seatd, dev-libs/libinput,x11-libs/libxkbcommon
