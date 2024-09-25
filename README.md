# BananaPI BPI-R4 OpenWRT Builder

This project automates the process of building OpenWrt firmware images for the BananaPI BPI-R4 with BPI-R4-NIC-BE14 WiFi 7 NIC. The build process incorporates various optimizations, hardening options, and quality-of-life enhancements. 

## Features

[TODO]

## Build Process

The build process is automated using GitHub Actions...
[TODO]

## Configuration

The project utilizes a custom configuration file [`bpi-r4-mda.config`](bpi-r4-mda.config) to specify the desired settings for the firmware build. This file includes various options such as target platform, compiler optimizations, package selections, and more.

## SSH Hardening

To enhance the security of SSH connections, the project includes a hardened SSH configuration. The configuration is derived from recommendations by [SSH-Audit](https://github.com/jtesta/ssh-audit) and the [BSI](https://www.bsi.bund.de/), it specifies strong key exchange algorithms, ciphers, message authentication codes (MACs), host key algorithms, and public key algorithms. This ensures that only secure and up-to-date algorithms are used for SSH communication.


## Contributing

Contributions to this project are welcome. If you encounter any issues or have suggestions for improvements, please open an issue or submit a pull request on the GitHub repository.

## Acknowledgements

- The OpenWrt project for providing the foundation for this firmware build.
- The Qualcomm IPQ807x platform and the Xiaomi AX3600 router for the hardware support.
- The community over at the [OpenWrt forum](https://forum.openwrt.org/t/ipq807x-nss-build/148529) for their valuable contributions and resources. 
- [rodriguezst](https://github.com/rodriguezst) for his [ipq807x-openwrt-builder](https://github.com/rodriguezst/ipq807x-openwrt-builder)
- And a special thanks to [qosmio](https://github.com/qosmio) for the main NSS development
- [Qualcommax NSS Builder](https://github.com/JuliusBairaktaris/Qualcommax_NSS_Builder)
