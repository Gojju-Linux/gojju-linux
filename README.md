<p align="center"><img src="assets/logo.svg" width="128" alt="mlinux"></p>

# mlinux

**Linux, native on Apple Silicon.**

An open project to boot Linux on Apple's M4 Macs and build a distro around it. Early stage: research and planning, nothing boots yet.

## Status

| Board | Machine | Boots | Network | GPU |
|---|---|---|---|---|
| J773g | Mac mini (M4) | untested | untested | untested |
| J713 | MacBook Air 13" (M4) | untested | untested | untested |

Status words mean exactly what [BRANDING.md](BRANDING.md) says.

## Goal

1. Boot an M4 Mac into Linux with working network.
2. Package a repeatable image and installer.
3. Grow into a usable daily desktop.

See [ROADMAP.md](ROADMAP.md).

## Standing on others' work

mlinux depends on research by the Asahi Linux, Gravity Linux and Omarchy-M4-Native projects. See [CREDITS.md](CREDITS.md). Not affiliated with any of them or with Apple.

## Safety

Changing a Mac's boot configuration can leave it unbootable. Back up first, and keep a second computer available for recovery.

## Licence

To be decided before the first code is added. Pick one that is compatible with the upstream code we use.
