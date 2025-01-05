# molekula: keyboard framework

## modular framework

This project aims to provide components for building modular ergo keyboards by separating one main PCB into central and side parts. **Side** is a dumb PCB, with key matrix only (up to 25 keys), and accepts all switch types (MX/ChocV1/ChocV2/GLP). **Central** is a keyboard brain, which contains any MCU (wired/wireless/integrated) and additional hardware - encoders/touchpads/trackballs/displays/etc, while keeping its size under 100x100mm. PCBs are interconnected with 12-pin FFC cables, and can be replaced/updated independently.

Such modular approach allows for quick, cheap and easy experimenting with different hardware, prototyping, and reusing of side PCBs.

### PCB examples

- central with pro-micro/nice!nano footprint, nice!view and rotary encoder

- side with 18 keys and minY spacing (19x16mm)

## Molekula2 keyboard

Reference design using molekula PCBs.

Features:

- minY (19x16mm) spacing
- unibody that can be disassembled into two parts for traveling
- 36 keys
- wireless
- nice!view support
- rotary encoder

[Build guide](./keyboards/Molekula2/README.md)

### Photos

### Sponsors

Molekula keyboard was sponsored by PCBWay. I can highly recommend their PCBA and 3D printing services - their "Imaging Black" resin looks fantastic.

<a href="https://shop.beekeeb.com" target="_blank"><img src="https://beekeeb.com/beekeeb-logo.png" align="left" width="200" ></a>

### Support

If you like my work and want to support my future designs, please consider [sponsorship](https://github.com/sponsors/zzeneg).
