## Awesome SDR [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of awesome Software Defined Radio (SDR) software, drivers, frameworks, libraries, tools, and more. Software Defined Radio enables flexible, reconfigurable radio systems using software rather than hardware components. This list highlights tools and resources for enthusiasts, students, and professionals interested in SDR development and experimentation.


## Table of Contents

- [Hardware](#hardware)
- [HackRF](#hackrf)
  - [Modes Supported by HackRF](#modes-supported-by-hackrf)
  - [Tools & Libraries](#tools--libraries)
- [LimeSDR](#limesdr)
  - [Modes Supported by LimeSDR](#modes-supported-by-limesdr)
  - [Development Kit (GUI based)](#development-kit-gui-based)
- [Awesome SDR Resources](#awesome-sdr-projects)
- [🧠 Books & References](#-books--references)
- [🌐 Communities](#-communities)
- [Contributing](#contributing)


---


### Hardwares

Most common and used SDR gears:

- **LimeSDR**
  - [LimeSDR USB](https://limemicro.com/sdr/limesdr-usb/)
  - [LimeSDR Mini](https://limemicro.com/sdr/limesdr-mini-2-0/)
  - [LimeSDR XTRX](https://limemicro.com/sdr/limesdr-xtrx/)
  - [LimeSDR X3](https://limemicro.com/sdr/limesdr-x3/)
- **HackRF**
  - [HackRF One](https://greatscottgadgets.com/hackrf/one/)

### HackRF

#### Modes Supported by HackRF

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

#### Tools & Libraries

- [GNU Radio](https://github.com/gnuradio/gnuradio)
- [SDRangel](https://github.com/f4exb/sdrangel)
- [GQRX](https://github.com/csete/gqrx)
- [HackRF Tools](https://github.com/mossmann/hackrf)
- [Gr-GSM](https://github.com/ptrkrysik/gr-gsm)
- [QSpectrumAnalyzer](https://github.com/xmikos/qspectrumanalyzer)

### LimeSDR

LimeSDR is a product of Lime Microsystems. Its official drivers, libraries and projects are published and maintained by [Myriad-RF](https://myriadrf.org/).

#### Modes Supported by LimeSDR

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

#### Development Kit (GUI based)

- [LimeSuiteNG](https://github.com/myriadrf/LimeSuiteNG)
- [SoapySDR](https://github.com/pothosware/SoapySDR)
- [PothosFlow](https://github.com/pothosware/PothosFlow)
- [GNU Radio](https://github.com/gnuradio/gnuradio)



---



### Awesome SDR Projects

- [Universal Radio Hacker](https://github.com/jopohl/urh) - The Universal Radio Hacker (URH) is a complete suite for wireless protocol investigation with native support for many common Software Defined Radios.
- [rt_433](https://github.com/merbanan/rtl_433) - A generic data receiver, mainly for the 433.92 MHz, 868 MHz (SRD), 315 MHz, 345 MHz, and 915 MHz ISM bands.
- [SDRangel](https://github.com/f4exb/sdrangel) - An open-source Qt5 / OpenGL 3.0+ SDR and signal analyzer frontend to various hardware.
- [rtlamr](https://github.com/bemasher/rtlamr) - An rtl-sdr receiver for Itron ERT compatible smart meters operating in the 900MHz ISM band.


---


### 🌐 Communities

- [r/RTLSDR on Reddit](https://www.reddit.com/r/RTLSDR/) - Active subreddit for all things SDR.
- [Myriad-RF Community Forum](https://discourse.myriadrf.org/) - Community discussion for LimeSDR and Myriad RF projects.
- [SDR Enthusiasts Discord](https://discord.gg/sdr) - Unofficial but active Discord server for SDR hobbyists and developers.



---


### 🧠 Books & References

- *Software Defined Radio using MATLAB & Simulink* - Offers deep insight into building SDR systems using MathWorks tools.
- *Introduction to Communications Engineering* by H. Taub - Solid foundation for understanding radio signals.


---

## Contributing

Contributions welcome! Please read the [contributing guidelines](CONTRIBUTING.md) and adhere to the [code of conduct](CODE_OF_CONDUCT.md).

---

*Maintained by [vkvbit](https://keybase.io/vkvbit)* – Secure communications welcome via Keybase.
