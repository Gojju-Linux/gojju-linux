# Roadmap

Each milestone ends with something you can see, so progress is visible.

## M0: Foundations
- [x] Name, logo and brand guide
- [ ] Organisation and repo set up
- [ ] Back up the target Mac, and decide on a second computer for recovery
- [ ] Read the upstream boot chain docs (iBoot, m1n1, U-Boot, kernel)

## M1: Know the hardware
- [ ] Run the read-only macOS survey on the target Mac and save the output
- [ ] Compare it against the upstream device tree for the board
- [ ] Write up the differences in `docs/`

## M2: Image that boots in a VM
- [ ] Minimal arm64 root filesystem built by a script
- [ ] Boots in QEMU on macOS
- [ ] CI builds the image

## M3: First real boot
- [ ] Recovery plan tested before touching boot settings
- [ ] m1n1 stage loads on the target
- [ ] Kernel reaches a shell (serial or framebuffer)

## M4: Network
- [ ] Ethernet link and DHCP
- [ ] Wi-Fi and Bluetooth (stretch)

## M5: Daily-driver basics
- [ ] Desktop, storage, input, audio, power
- [ ] Installer
