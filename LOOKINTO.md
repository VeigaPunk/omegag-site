# omegaG website look-into

**Live URL:** https://veigapunk.github.io/omegag-site/  
**Product:** omegaG (formerly DS4CC) — controller-native agent control  
**Repos:** https://github.com/vgpnk-holdings-llc/omegaG  
**Legacy:** https://github.com/VeigaPunk/DS4CC (+ releases)

## What the site claims
- PlayStation DualSense / DualShock 4 → shortcut mapper for terminal-first dev
- Windows tray daemon; Linux (Ubuntu 22.04+ / Arch) via evdev/uinput
- Six chat slots behind PS modifier; lightbar projects selected-slot state
- Lightbar: idle / thinking / complete·unread / requires input / error / unassigned
- Pulse 500ms, brightness, 180s sleep, wake on modifier
- PS hold exclusive layer: L1/R1 cycle slots, Share blank thread, Options fork, touchpad select (double-press 350ms)
- Cross/Circle accept/decline; Square priority; Triangle composer; L2 PTT (latch 350ms)
- D-pad reasoning effort; right-stick cardinal actions; L3/R3 command/skill
- Optional Codex app-server runtime (disabled by default)
- Config TOML: `%APPDATA%\ds4cc\config.toml` / `~/.config/ds4cc/config.toml`
- Stack: Rust 2024, tokio, hidapi; MIT

## Local mirrors
- Site snapshot: `~/Projects/omegag-site/` (index.fetched.html, style.css, main.js, assets/)
- Source tree: `~/Projects/omegaG/`

## Session goal
Audit marketing site vs repo truth; note gaps, broken links, brand DS4CC→omegaG consistency, deploy path (kimi.page), and next product-site improvements. Report findings; do not force-push. Prefer local-first commits if implementing site fixes in a new tree.
