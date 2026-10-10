<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:F6D6E1,50:D8C7E9,100:C1E1EC&height=200&section=header&text=Hey,%20I'm%20Sanisa&fontSize=42&fontColor=4B3B4E&animation=fadeIn&fontAlignY=38&desc=%20%F0%9F%8C%B7Embedded%20%2B%20Low-level%20systems%20%C2%B7%20Hardware%20security%20%F0%9F%8C%B7&descAlignY=58&descSize=18" width="100%"/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&color=B08CB0&center=true&vCenter=true&width=620&lines=Embedded+%2B+Low-level+systems+engineer+%F0%9F%94%A9;From+copper+pads+to+root+shells+%F0%9F%8C%BF;UART+%C2%B7+SWD+%C2%B7+SPI+flash+%F0%9F%8C%B1;Breaking+firmware+by+day%2C+writing+by+night+%F0%9F%AA%B6;Finding+poetry+in+silicon+%F0%9F%AA%B7" alt="Typing SVG" />
<br>

### 🌺 *Tender of the garden: Embedded & Low-level systems engineer, with thorns on the Security side* 🛡️

</div>

<br>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:F6D6E1,50:D8C7E9,100:C1E1EC&height=6&width=100%25" width="100%"/>

## 🪴 About the garden

I'm a final-year **EXTC** engineer in Mumbai who works where **silicon, firmware and the operating system meet**. I build firmware, and I take other people's firmware apart. Most of my work happens at the lowest layers: finding debug interfaces on a bare PCB, pulling firmware out over UART, SWD or straight off the flash chip, reversing it in Ghidra, and working out what the code *actually* does on the metal.

Building teaches me how systems are meant to behave. Breaking them shows me how they really behave. After that, I write it all down so someone else can follow the same path. Half engineer, half storyteller.

```
🍀 Current saplings

🔧 building      CyberEdge-001 · ESP32-S3 firmware on FreeRTOS: drivers, state machine, safety guardrail layer
🐞 disclosing    2 vulnerabilities in coordinated disclosure (see below 🌱)
🌿 contributing  upstream open source · both as a hacker and as a dev
🪶 writing       research work on iotsec.in
🌸 cultivating   curiosity at the hardware–software boundary
```

<br>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:F6D6E1,50:D8A7CA,100:E4C1F9&height=6&width=100%25" width="100%"/>

## 🐞 Bugs in my garden

*Vulnerabilities I've found and reported through coordinated disclosure. The details stay underground until the vendors say they can bloom.*

| | Where | Status |
|---|---|---|
| 🌱 | **An RTOS** | Reported to the Project's security team · coordinated disclosure in progress · **goes public 25 Oct 2026** |
| 🌱 | **A global consumer electronics brand** | Consumer IoT device vulnerability, reported through the vendor's bug bounty program · in vendor triage |

> 🔒 Until then, no hints and no teasers. That's how disclosure works. Some of my other hardware security work (internship research and contributions) is also under confidentiality. If you'd like to talk about it in general terms, please reach out 🌸

<br>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:C1E1EC,50:E4C1F9,100:F6D6E1&height=6&width=100%25" width="100%"/>

## 🧷 Projects on the shelf

> 🌿 **[UART Recon](https://github.com/sanisapatrikar/UART-Recon)**
> I start from bare copper pads on a router PCB, find the pinout with a JTAGulator, and end up with a live root shell over UART. The repo covers the whole path: interface discovery, the console session and firmware exploration.

> 🪴 **[SWD Recon](https://github.com/sanisapatrikar/SWD-Recon)**
> SWD reconnaissance on two targets. The first was a GNSS module that refused to talk (DAP failures and all). The second was a Cube Orange+ flight controller (STM32H7), where I extracted the firmware over SWD and ran into a dual-bank flash surprise along the way.

> 🌾 **[CyberEdge-001](https://github.com/sanisapatrikar/CyberEdge-001)** · *growing, prototype due Nov 2026*
> An ESP32-S3 security training toolkit with modular Wi-Fi, BLE (nRF) and RFID add-ons. Its guardrails are built in so it can't easily be turned into a real attack device. I own the firmware and the security layer: FreeRTOS, a non-blocking state machine, MAC/UID ownership allowlists checked before any module runs, per-module timeouts and an on-device audit log.

> 🌵 **[Drone Mirage](https://github.com/1Horizon002/DRONE_MIRAGE-)** · *🏆 won Tech-a-thon 4.0*
> A two-node drone threat detection system. An airborne Raspberry Pi runs a custom YOLOv8 model to spot drones, and a ground-station Pi scores each one from benign to malicious through a threat engine.

> 🌼 **Upstream: [Zed](https://github.com/zed-industries/zed)**
> A documentation preprocessor fix in the Rust-based code editor. The story is in the library below.

*(and a few more growing quietly in the private greenhouse 🌱)*

<br>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:F6D6E1,50:D8C7E9,100:C1E1EC&height=6&width=100%25" width="100%"/>

## 📚 The garden library

*A library filled entirely with my works. Straight from the bench, for people coming in after me to follow thru, published on [iotsec.in](https://iotsec.in). They're technically precise, a little poetic, and honest about what didn't work.*

| | Pressing | What grew there |
|---|---|---|
| 🌷 | **[Whispers on the Wire: From Copper Pads to a Live UART Root Shell](https://iotsec.in/t/whispers-on-the-wire-from-copper-pads-to-a-live-uart-root-shell/87)** | Pinout hunting with a JTAGulator → a live root shell over UART |
| 🪻 | **[SWD Wasn't Talking, So I Changed the Target](https://iotsec.in/t/swd-wasnt-talking-so-i-changed-the-target-swd-reconnaissance-dap-failures-and-a-dual-bank-plot-twist/88)** | SWD reconnaissance, DAP failures, and a dual-bank plot twist |
| 🌹 | **[I Found a MITM Vulnerability in a Camera's TLS Handshake. I Was Wrong.](https://iotsec.in/t/i-found-a-mitm-vulnerability-in-a-cameras-tls-handshake-i-was-wrong-a-static-reversal-of-an-mbedtls-config-struct/106)** | A static reversal of an mbedTLS config struct, and what a disproved hypothesis teaches you |
| 🌻 | **[Swapping My Hacker Hat for a Dev One, for a Day](https://iotsec.in/t/swapping-my-hacker-hat-for-a-dev-one-for-a-day/107)** | Security research vs. shipping code: inspired by my work across both fields |

> 🪶 Outside the terminal, I write and do voice acting. To me, being able to explain why a side-channel attack matters to someone who has never held a chip is a security skill too.

<br>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:F6D6E1,50:D8C7E9,100:C1E1EC&height=6&width=100%25" width="100%"/>

## 🧵 The technical thread

<div align="center">
<img src="assets/skill-garden.svg" width="100%" alt="skill specimens"/>
</div>

<br>

**Silicon & firmware**
<br>
<img src="https://img.shields.io/badge/ESP32--S3-D8A7CA?style=for-the-badge&logo=espressif&logoColor=4B3B4E"/> <img src="https://img.shields.io/badge/FreeRTOS-D0F4DE?style=for-the-badge"/> <img src="https://img.shields.io/badge/Zephyr_RTOS-D8C7E9?style=for-the-badge"/> <img src="https://img.shields.io/badge/Raspberry_Pi-C9E4DE?style=for-the-badge&logo=raspberry-pi&logoColor=4B3B4E"/> <img src="https://img.shields.io/badge/PlatformIO-E4C1F9?style=for-the-badge&logo=platformio&logoColor=4B3B4E"/>

**Interfaces I speak**
<br>
<img src="https://img.shields.io/badge/UART-F6D6E1?style=for-the-badge"/> <img src="https://img.shields.io/badge/SWD-D8C7E9?style=for-the-badge"/> <img src="https://img.shields.io/badge/SPI-F9E2AE?style=for-the-badge"/> <img src="https://img.shields.io/badge/I2C-C1E1EC?style=for-the-badge"/>

**Languages**
<br>
<img src="https://img.shields.io/badge/C-D8C7E9?style=for-the-badge&logo=c&logoColor=4B3B4E"/> <img src="https://img.shields.io/badge/C++-C1E1EC?style=for-the-badge&logo=cplusplus&logoColor=4B3B4E"/> <img src="https://img.shields.io/badge/Python-F6D6E1?style=for-the-badge&logo=python&logoColor=4B3B4E"/> <img src="https://img.shields.io/badge/Bash-C9E4DE?style=for-the-badge&logo=gnu-bash&logoColor=4B3B4E"/> <img src="https://img.shields.io/badge/Rust-D0F4DE?style=for-the-badge&logo=rust&logoColor=4B3B4E"/>

**Analysis**
<br>
<img src="https://img.shields.io/badge/Ghidra-FFCAD4?style=for-the-badge"/> <img src="https://img.shields.io/badge/binwalk-D0F4DE?style=for-the-badge"/> <img src="https://img.shields.io/badge/Wireshark-D8A7CA?style=for-the-badge&logo=wireshark&logoColor=4B3B4E"/> <img src="https://img.shields.io/badge/Linux-C1E1EC?style=for-the-badge&logo=linux&logoColor=4B3B4E"/> <img src="https://img.shields.io/badge/Git-F9E2AE?style=for-the-badge&logo=git&logoColor=4B3B4E"/>

**The workbench** *(hardware rig)*
<br>
<img src="https://img.shields.io/badge/J--Link_PRO-D8A7CA?style=for-the-badge"/> <img src="https://img.shields.io/badge/JTAGulator-C9E4DE?style=for-the-badge"/> <img src="https://img.shields.io/badge/ChipWhisperer-D0F4DE?style=for-the-badge"/> <img src="https://img.shields.io/badge/Bus_Pirate-F9E2AE?style=for-the-badge"/> <img src="https://img.shields.io/badge/CH341A_Programmer-FFCAD4?style=for-the-badge"/> <img src="https://img.shields.io/badge/Universal_Programmer-C1E1EC?style=for-the-badge"/> <img src="https://img.shields.io/badge/Logic_Analyser-E4C1F9?style=for-the-badge"/> <img src="https://img.shields.io/badge/AmScope-D8C7E9?style=for-the-badge"/>

<br>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:C1E1EC,50:E4C1F9,100:F6D6E1&height=6&width=100%25" width="100%"/>

## 🎀 Pressed flowers (milestones)

| | |
|---|---|
| 🔬 | **Embedded Security Research Intern**, CoE CNDS (VJTI): firmware extraction over UART & SWD, black-box IoT testing, side-channel experiments |
| 🏆 | **2× National Hackathon Winner**: Tech-a-thon 4.0 (Drone Mirage) · Hackquinox 2.0 (SafeLabs) |
| 🚩 | **CTFs**: placed at RedFox CTF (international) and RAIT-CTF (national) · won IEEE-CTF VESIT |
| 📜 | **CompTIA Security+** certified (2026) |
| 🎓 | **EXTC, VESIT Mumbai**: CGPA 9.48 · Class of 2027 |
| 🦔 | **Founding member & Senior Technical Head**, Cyber Tinkerers' Club, building a hardware/security community from zero |

<br>

<div align="center">

Let's talk 🌷

<a href="https://linkedin.com/in/sanisa-patrikar"><img src="https://img.shields.io/badge/LinkedIn-D8C7E9?style=for-the-badge&logo=linkedin&logoColor=4B3B4E"/></a> <a href="https://iotsec.in"><img src="https://img.shields.io/badge/iotsec.in-C1E1EC?style=for-the-badge&logo=discourse&logoColor=4B3B4E"/></a> <a href="https://beyondthespeakingmind.wordpress.com"><img src="https://img.shields.io/badge/WordPress-F6D6E1?style=for-the-badge&logo=wordpress&logoColor=4B3B4E"/></a> <a href="mailto:sanisa.patrikar@gmail.com"><img src="https://img.shields.io/badge/Email-C9E4DE?style=for-the-badge&logo=gmail&logoColor=4B3B4E"/></a>

<br><br>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:C1E1EC,50:D8C7E9,100:F6D6E1&height=100&section=footer" width="100%"/>

</div>
