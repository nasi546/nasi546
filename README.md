## 👋 Hi, I'm Minseong (민성)

임베디드 & BSP 엔지니어를 목표로 공부하고 있는 개발자입니다.  
**“실제 하드웨어가 움직이고, 부팅하면 자동으로 돌아가는 시스템”**을 만드는 걸 좋아합니다.

- 🧩 **Linux BSP/Yocto**: 커스텀 이미지, meta-layer, overlay/DT, systemd 기반 운영
- 🧠 **Linux Device Driver**: char device(/dev), poll/read, IRQ, I2C/GPIO, RTC 연동
- 🎥 **Multimedia/AI Pipeline**: V4L2 + GStreamer + OpenCV + (Hailo) 인퍼런스/오버레이
- 🔌 **통신/연동**: SocketCAN, UDP/TCP, MCU↔Linux 시스템 통합

**Contact**: minsoung1027@gmail.com · **GitHub**: [@nasi546](https://github.com/nasi546)

---

### 💡 What I Can Do (Quick View)

| 분야 | 내가 할 수 있는 일 (요약) | 관련 프로젝트 |
| --- | --- | --- |
| **Embedded Linux & BSP** | Yocto 이미지 빌드/커스텀, meta-layer 작성, DT/overlay, systemd 서비스 구성 | **[AI-Black-Box](https://github.com/nasi546/AI-Black-Box)** |
| **Linux Device Driver** | char device(/dev), poll/read, IRQ, I2C/GPIO, RTC 연동, udev + systemd 자동화 | **[Device_Driver_Mini_Project](https://github.com/nasi546/Device_Driver_Mini_Project)** |
| **운영/배포 자동화 (Linux)** | udev 트리거 + systemd로 자동 실행, 버전/헬스체크 기반 안전 업데이트, 롤백/로그 | **[USB Auto Update](https://github.com/nasi546/Raspbery-pi5-USB-update)** |
| **영상/스트리밍 파이프라인** | V4L2 캡쳐 → GStreamer → 처리/오버레이 → 출력/디버깅 | **[AI-Black-Box](https://github.com/nasi546/AI-Black-Box)** |
| **MCU / 센서·액추에이터** | STM32 주변장치(UART/I2C/SPI/ADC/Timer), 센서/모터/부저/LED 제어, 간단 FreeRTOS | [Flood_barrier](https://github.com/nasi546/Flood_barrier), [Aiot_SmartHome](https://github.com/nasi546/Aiot_SmartHome) |
| **네트워크/통신** | SocketCAN, UDP/TCP, Wi-Fi(ESP8266/ESP32) 기반 노드 통신 설계/연동 | AI-Black-Box, Aiot_SmartHome |
| **기본기/알고리즘** | C++ STL, 자료구조/알고리즘 풀이 및 리팩토링 습관 | **[baekjoon](https://github.com/nasi546/baekjoon)** |

---

### 🚀 Featured Projects

#### Major
- **[AI-Black-Box](https://github.com/nasi546/AI-Black-Box)**  
  Raspberry Pi 5 + (Hailo-8) + MCP2515 CAN + 카메라 기반 시스템.  
  **Yocto 커스텀 이미지**, GStreamer 파이프라인, CAN → KUKSA → AGL 클러스터 연동.

- **[Raspberry Pi 5 – USB Auto Update System](https://github.com/nasi546/Raspbery-pi5-USB-update)**  
  USB/외장 SSD 삽입만으로 자동 업데이트.  
  udev + systemd, state.json 기반 버전관리, **헬스체크 승인(pending) + 자동/수동 롤백 + 로그**.

#### Mini (Device Driver)
- **[Device Driver Mini Project](https://github.com/nasi546/Device_Driver_Mini_Project)**  
  Raspberry Pi 4B 기반 **Linux 디바이스 드라이버(4) + 데몬 + systemd/udev 자동 실행**.  
  OLED(SSD1306) 시간/온습도 표시, Rotary/Key로 **RTC 시간 설정**, LED bar로 **습도 레벨 게이지** 출력.

#### Others
- **[Aiot_SmartHome](https://github.com/nasi546/Aiot_SmartHome)**  
  STM32 + ESP + RPi 기반 AIoT 스마트홈 프로토타입(센서/액추에이터 통합).

- **[Flood_barrier](https://github.com/nasi546/Flood_barrier)**  
  수위 기반 자동 차수막(서보 + LCD + 리모컨) 제어.

- **[baekjoon](https://github.com/nasi546/baekjoon)**  
  C++ 알고리즘 풀이 저장소.

---

<details>
<summary><b>🛠 Tech Stack (click to expand)</b></summary>

<br/>

**Languages**  
![C](https://img.shields.io/badge/C-00599C?style=flat&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=c%2B%2B&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)

**Embedded / MCU**  
![STM32](https://img.shields.io/badge/STM32-03234B?style=flat&logo=stmicroelectronics&logoColor=white)
![FreeRTOS](https://img.shields.io/badge/FreeRTOS-009688?style=flat)
![ESP8266](https://img.shields.io/badge/ESP8266-000000?style=flat)
![ESP32](https://img.shields.io/badge/ESP32-000000?style=flat)

**Linux & BSP**  
![Embedded Linux](https://img.shields.io/badge/Embedded_Linux-000000?style=flat&logo=linux&logoColor=white)
![Yocto](https://img.shields.io/badge/Yocto_Project-35495E?style=flat)
![AGL](https://img.shields.io/badge/Automotive_Grade_Linux-009639?style=flat)
![CAN Bus](https://img.shields.io/badge/CAN-Bus-003366?style=flat)

**Multimedia / AI**  
![GStreamer](https://img.shields.io/badge/GStreamer-FF6F00?style=flat)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat&logo=opencv&logoColor=white)
![Hailo-8](https://img.shields.io/badge/Hailo--8-FF1493?style=flat)
![CARLA](https://img.shields.io/badge/CARLA_Simulator-000000?style=flat)

**Tools**  
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=flat&logo=visualstudiocode&logoColor=white)
![STM32CubeIDE](https://img.shields.io/badge/STM32CubeIDE-03234B?style=flat)
![CMake](https://img.shields.io/badge/CMake-064F8C?style=flat&logo=cmake&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat&logo=gnu-bash&logoColor=white)
![systemd](https://img.shields.io/badge/systemd-000000?style=flat&logo=systemd&logoColor=white)

</details>
