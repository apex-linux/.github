# Apex

Apex is a desktop operating system for one laptop, the ASUS Vivobook Pro 14X OLED (M7400QC),
built on Fedora 45 as a bootc image: atomic updates, rollback, and a GNOME desktop
reshaped by patches to the shell and its toolkit.

| Repository | What it holds |
|---|---|
| [apex](https://github.com/apex-linux/apex) | The documentation: architecture, design, roadmap, decisions, install and recovery |
| [apex-system](https://github.com/apex-linux/apex-system) | The update and boot stack in Rust (`apex-updated`, `apexctl`, `apex-boot`), the machine profile, the `apex` RPM |
| [apex-gnome](https://github.com/apex-linux/apex-gnome) | The Apex layer of GNOME Shell and its rebuild recipe, with the shell's tests |
| [apex-desktop](https://github.com/apex-linux/apex-desktop) | Desktop data: settings schema, vendor defaults, wallpapers, the shell crash guard; the `apex-desktop` RPM |
| [apex-kernel](https://github.com/apex-linux/apex-kernel) | The kernel and libfprint rebuilds for this machine |
| [apex-image](https://github.com/apex-linux/apex-image) | The bootc image, the rebuild lane, the builder VM and the gates that decide what ships |
| [apex-ci](https://github.com/apex-linux/apex-ci) | The CI tooling every repository shares: actions, the comment guard and the Renovate preset |
| [.github](https://github.com/apex-linux/.github) | This page and the security policy |

Apex is a personal project in active development and is not ready for general use.
