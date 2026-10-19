# Built-in features for gamepad-galaxy-os

Purpose: controller gaming

1. **prepare racing and game notes** — run gamepad-galaxy-os-workspace. It creates ~/Documents/gamepad-galaxy-os-workspace/ with Game Notes, Screenshots, Capture Plans folders.
2. **plan a play or streaming session** — run gamepad-galaxy-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/gamepad-galaxy-os-session-plans/.
3. **check game and controller readiness** — run gamepad-galaxy-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/gamepad-galaxy-os-workspace features/gamepad-galaxy-os-plan features/gamepad-galaxy-os-check "$HOME/.local/bin/"

## Preinstalled purpose software

The installer adds these three Flathub applications for controller gaming:

1. **Lutris** — net.lutris.Lutris
2. **Bottles** — com.usebottles.bottles
3. **ProtonUp-Qt** — net.davidotek.pupgui2

They are installed from Flathub during setup. The repository contains application IDs and documentation, not third-party binaries; each publisher’s terms and licenses apply.

## Ten more purpose-specific preinstalled applications

The setup installs these ten Flathub apps selected for controller gaming:

1. **OBS Studio** — record or stream sessions (com.obsproject.Studio)
2. **VLC** — review media files (org.videolan.VLC)
3. **Godot Engine** — build and test 2D and 3D games (org.godotengine.Godot)
4. **Blender** — create 3D assets and animations (org.blender.Blender)
5. **VSCodium** — edit code and project files (com.vscodium.codium)
6. **GNOME Boxes** — test workflows in virtual machines (org.gnome.Boxes)
7. **GNOME Logs** — inspect logs during troubleshooting (org.gnome.Logs)
8. **GNOME Calculator** — perform scientific and financial calculations (org.gnome.Calculator)
9. **Disk Usage Analyzer** — find large files and manage storage (org.gnome.baobab)
10. **Flatseal** — review Flatpak app permissions (com.github.tchx84.Flatseal)

Flathub distributes the app packages. Check each publisher license and terms. This repository contains app IDs and documentation, not third-party binaries.
