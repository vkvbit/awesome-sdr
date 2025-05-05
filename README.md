# Awesome SDR  [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of awesome Software Defined Radio (SDR) software, drivers, frameworks, libraries, tools, and more. Software Defined Radio enables flexible, reconfigurable radio systems using software rather than hardware components. This list highlights tools and resources for enthusiasts, students, and professionals interested in SDR development and experimentation.

## Contents

- [Hardware](#hardware)
- [HackRF](#hackrf)
  - [Modes Supported by HackRF](#modes-supported-by-hackrf)
  - [Tools & Libraries](#tools--libraries)
- [LimeSDR](#limesdr)
  - [Modes Supported by LimeSDR](#modes-supported-by-limesdr)
  - [Development Kit (GUI based)](#development-kit-gui-based)
- [Awesome SDR Projects](#awesome-sdr-projects)
- [Communities](#-communities)
- [Books & References](#-books--references)
- [Contributing](#contributing)

## Hardware

Most common and used SDR gears:

- [LimeSDR](https://limemicro.com/sdr/)
  - [LimeSDR USB](https://limemicro.com/sdr/limesdr-usb/)
  - [LimeSDR Mini](https://limemicro.com/sdr/limesdr-mini-2-0/)
  - [LimeSDR XTRX](https://limemicro.com/sdr/limesdr-xtrx/)
  - [LimeSDR X3](https://limemicro.com/sdr/limesdr-x3/)
- [HackRF](https://greatscottgadgets.com/hackrf/)
  - [HackRF One](https://greatscottgadgets.com/hackrf/one/)

## HackRF

### Modes Supported by HackRF

HackRF is a half-duplex SDR that supports a wide frequency range and can be used for:

- ADS-B (aircraft tracking)
- POCSAG (pager decoding)
- GSM sniffing and injection
- FM/AM Radio
- NOAA Weather Satellite (APT)
- APRS (Amateur Packet Radio System)
- TETRA and DMR decoding
- Bluetooth and Wi-Fi analysis
- GPS signal replay
- Key fob signal capture (433 MHz / 315 MHz)

### Tools & Libraries

- [GNU Radio](https://github.com/gnuradio/gnuradio) - A free & open-source software development toolkit that provides signal processing blocks to implement software radios.
- [SDRangel](https://github.com/f4exb/sdrangel) - An open-source Qt5 / OpenGL 3.0+ SDR and signal analyzer frontend to various hardware.
- [GQRX](https://github.com/csete/gqrx) - A software defined radio receiver powered by GNU Radio and Qt.
- [HackRF Tools](https://github.com/mossmann/hackrf) - Official HackRF tools and utilities.
- [Gr-GSM](https://github.com/ptrkrysik/gr-gsm) - GNU Radio blocks and tools for receiving GSM transmissions.
- [QSpectrumAnalyzer](https://github.com/xmikos/qspectrumanalyzer) - A spectrum analyzer for various SDR hardware.

## LimeSDR

LimeSDR is a product of Lime Microsystems. Its official drivers, libraries and projects are published and maintained by [Myriad-RF](https://myriadrf.org/).

### Modes Supported by LimeSDR

LimeSDR is a full-duplex, highly flexible SDR ideal for advanced applications such as:

- GSM/3G/4G/5G base stations
- LoRa communication
- ADS-B decoding
- Satellite communications
- Wideband spectrum analysis
- FM/DAB/AM Radio reception
- Digital TV (DVB-T)
- Wi-Fi/Bluetooth/ZigBee prototyping
- Amateur Radio (SSB, CW, RTTY)
- TETRA/DMR/PMR decoding

### Development Kit (GUI based)

- [LimeSuiteNG](https://github.com/myriadrf/LimeSuiteNG) - Next generation LimeSuite GUI application.
- [SoapySDR](https://github.com/pothosware/SoapySDR) - Vendor and platform neutral SDR support library.
- [PothosFlow](https://github.com/pothosware/PothosFlow) - A dataflow programming environment for SDR.

## Awesome SDR Projects

- [Universal Radio Hacker](https://github.com/jopohl/urh) - The Universal Radio Hacker (URH) is a complete suite for wireless protocol investigation with native support for many common Software Defined Radios.
- [rtl_433](https://github.com/merbanan/rtl_433) - A generic data receiver, mainly for the 433.92 MHz, 868 MHz (SRD), 315 MHz, 345 MHz, and 915 MHz ISM bands.
- [rtlamr](https://github.com/bemasher/rtlamr) - An rtl-sdr receiver for Itron ERT compatible smart meters operating in the 900MHz ISM band.

## Communities

- [r/RTLSDR on Reddit](https://www.reddit.com/r/RTLSDR/) - Active subreddit for all things SDR.
- [Myriad-RF Community Forum](https://discourse.myriadrf.org/) - Community discussion for LimeSDR and Myriad RF projects.
- [SDR Enthusiasts Discord](https://discord.gg/sdr) - Unofficial but active Discord server for SDR hobbyists and developers.

## Books & References

- [Software Defined Radio using MATLAB & Simulink](https://www.mathworks.com/solutions/software-defined-radio.html) - Offers deep insight into building SDR systems using MathWorks tools.
- [Introduction to Communications Engineering](https://www.amazon.com/Introduction-Communications-Engineering-H-Taub/dp/0070130600) by H. Taub - Solid foundation for understanding radio signals.

## Contributing

Contributions welcome! Please read the [contributing guidelines](CONTRIBUTING.md) and adhere to the [code of conduct](CODE_OF_CONDUCT.md).

---

*Maintained by [vkvbit](https://keybase.io/vkvbit)* – Secure communications welcome via Keybase.
