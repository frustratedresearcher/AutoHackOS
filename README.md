# AutoHackOS

**AutoHackOS** is an open-source operating system purpose-built for automotive cybersecurity and vehicle penetration testing. It provides a one-stop platform with all the tools and frameworks needed to assess the security of modern vehicles, eliminating the hassle of setting up multiple VMs or toolchains for different automotive systems. AutoHackOS supports a wide range of interfaces (CAN bus, Bluetooth, RF, Wi-Fi, Telecom, Cloud, etc.), making it a versatile toolkit for comprehensive vehicle security assessments.

---

## Overview

AutoHackOS is an open-source Linux-based operating system tailored for vehicle penetration testing and automotive security research. It consolidates all necessary car-hacking tools in one environment, enabling researchers, enthusiasts, and professionals to analyze and exploit vulnerabilities across ECUs, networks, and external interfaces.

---

## Features

- **Pre-Installed Automotive Security Tools** – Ready-to-use, organized toolset for vehicle security testing.  
- **Multi-Domain Interface Support** – CAN, BLE, RF, Wi-Fi, Telecom, Cloud, and Web application testing.  
- **Prebuilt VM & ISO Images** – Available as a Virtual Machine (OVA/VMware) or bootable ISO.  
- **Automation & Training Aids** – Includes automation scripts, simulators (ICSim, UDSim, etc.), and vulnerable apps for hands-on practice.  
- **Regular Updates & Changelogs** – Community-driven bug tracking and tool updates to keep pace with emerging threats.  

---

## Tool Categories

### CAN Penetration Testing
- **Simulators**: ICSim, UDSim, CANToolz, Virtual Car  
- **Attack Tools**: canutils, Caring Caribou, CanTot  

### Telecom Testing (Telematics & Cellular)
- **Stacks**: Osmocom, srsRAN  
- **Tools**: Modmobjam, Modmobmap  
- **Automation**: LTE Deploy, Osmo-NITB Scripts  

### BLE (Bluetooth Low Energy) Testing
- Tools: hcitool, gatttool, BlueBorne, Crackle, BrakTooth, btlejack, btlejuice  

### Firmware Analysis
- Tools: binwalk, EMBA, Firmware Slap, Firmwalker, Firmadyne, FWAnalyzer, FACT, expliot  

### Web & Cloud Pentesting
- Tools: OWASP ZAP, Burp Suite CE, Postman, Nuclei, Interactsh, ScoutSuite, awscli, azurecli  

### Network Pentesting
- Tools: Wireshark, Ettercap, Nmap, Aircrack-ng, Airgeddon, GPS-SDR-Sim, Metasploit  

### Mobile Testing
- Tools: adb, apktool, jadx, Frida, MobSF  

### Fuzzing
- Tools: AFL, Domato, FreeDOM  

### Reverse Engineering
- Tools: radare2, Ghidra, IDA Free, Cutter  

---

## Hardware Compatibility

- **CAN Bus Adapters**: USB2CAN/USBCAN, MCP2515, CANtact, CANPico, USBtin, Macchina M2  
- **SDRs**: HackRF, BladeRF, USRP, LimeSDR  
- **BLE Dongles**: CYW920819EVB-02, Nordic nRF52840, Ubertooth One, Adafruit Bluefruit LE Sniffer  
- **Debugging Tools**: Bus Pirate, JTAGulator, ST-Link V2  

---

## Installation Instructions

- **Virtual Machine (VM)**: Import the provided OVA/VMware image into VirtualBox/VMware and boot directly.  
- **Live ISO / Bare Metal**: Flash the ISO to a USB (via Rufus or `dd`) and boot. Can be run as Live OS or installed permanently.  

*Refer to [documentation](https://autohackos.readthedocs.io/en/latest/) for full setup details.*

---

## Documentation

📖 [AutoHackOS Documentation (Latest)](https://autohackos.readthedocs.io/en/latest/)

---

## Community & Contribution

- **Forum**: [forum.autohackos.com](http://forum.autohackos.com) *(in progress)*  
- **Bug Tracker**: [bugs.autohackos.com](http://bugs.autohackos.com)  
- **Contribute**: Submit code, tools, scripts, or documentation improvements. Community-written tutorials are highly encouraged!  

---

## Links

- 🌐 [Website](https://autohackos.com)  
- 💻 [GitHub](https://github.com/AutoHackOS)  
- 📖 [Documentation](https://autohackos.readthedocs.io/en/latest/)  

---

## License

AutoHackOS is an open-source project. License details are provided in this repository.  
All included tools maintain their respective licenses.

---

*Developed by a passionate community of automotive security researchers. Making car hacking more accessible and effective.* 🚗🔒

