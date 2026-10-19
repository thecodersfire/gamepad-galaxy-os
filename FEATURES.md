# Built-in features for gamepad-galaxy-os

Purpose: controller gaming

1. **prepare racing and game notes** — run gamepad-galaxy-os-workspace. It creates ~/Documents/gamepad-galaxy-os-workspace/ with Game Notes, Screenshots, Capture Plans folders.
2. **plan a play or streaming session** — run gamepad-galaxy-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/gamepad-galaxy-os-session-plans/.
3. **check game and controller readiness** — run gamepad-galaxy-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/gamepad-galaxy-os-workspace features/gamepad-galaxy-os-plan features/gamepad-galaxy-os-check "$HOME/.local/bin/"
