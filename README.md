## 👋 Hi, I'm Minseong (민성)

**"하드웨어를 실제로 움직이는 즐거움을 아는 엔지니어"**

임베디드 & BSP 엔지니어를 목표로 공부하고 있는 개발자입니다.  
STM32, Raspberry Pi 5, Yocto, CAN, GStreamer, Hailo-8 등을 이용해서  
**실제 하드웨어가 동작하는 시스템**을 설계하고 구현하는 것을 좋아합니다.

---

### 🛠 Tech Stack

**Languages**
<img src="https://img.shields.io/badge/C-00599C?style=flat&logo=c&logoColor=white"/>
<img src="https://img.shields.io/badge/C++-00599C?style=flat&logo=c%2B%2B&logoColor=white"/>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white"/>

**Embedded / MCU**
<img src="https://img.shields.io/badge/STM32-03234B?style=flat&logo=stmicroelectronics&logoColor=white"/>
<img src="https://img.shields.io/badge/FreeRTOS-009688?style=flat"/>
<img src="https://img.shields.io/badge/ESP32-000000?style=flat"/>

**Linux & BSP**
<img src="https://img.shields.io/badge/Embedded_Linux-000000?style=flat&logo=linux&logoColor=white"/>
<img src="https://img.shields.io/badge/Raspberry_Pi-A22846?style=flat&logo=raspberrypi&logoColor=white"/>
<img src="https://img.shields.io/badge/Yocto_Project-35495E?style=flat"/>
<img src="https://img.shields.io/badge/Automotive_Grade_Linux-009639?style=flat"/>
<img src="https://img.shields.io/badge/CAN-Bus-003366?style=flat"/>
<img src="https://img.shields.io/badge/Linux_Device_Driver-000000?style=flat&logo=linux&logoColor=white"/>

**Multimedia / AI**
<img src="https://img.shields.io/badge/GStreamer-FF6F00?style=flat"/>
<img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat&logo=opencv&logoColor=white"/>
<img src="https://img.shields.io/badge/Hailo--8-FF1493?style=flat"/>
<img src="https://img.shields.io/badge/CARLA_Simulator-000000?style=flat"/>
<img src="https://img.shields.io/badge/PETR-6A5ACD?style=flat"/>

**Tools**
<img src="https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white"/>
<img src="https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white"/>
<img src="https://img.shields.io/badge/VS_Code-007ACC?style=flat&logo=visualstudiocode&logoColor=white"/>
<img src="https://img.shields.io/badge/CMake-064F8C?style=flat&logo=cmake&logoColor=white"/>
<img src="https://img.shields.io/badge/Bash-4EAA25?style=flat&logo=gnu-bash&logoColor=white"/>
<img src="https://img.shields.io/badge/systemd-000000?style=flat&logo=systemd&logoColor=white"/>

---
### 💡 What I Can Do

| 분야 | 내가 할 수 있는 일 | 관련 프로젝트 |
| :--- | :--- | :--- |
| **임베디드 MCU** <br>(STM32) | • GPIO / 타이머 / ADC / UART / I2C / SPI 설정 <br>• 센서 값 읽고 모터·부저·LED 제어 <br>• FreeRTOS 태스크 구성 및 스케줄링 | [Flood_barrier](https://github.com/nasi546/Flood_barrier)<br>[Aiot_SmartHome](https://github.com/nasi546/Aiot_SmartHome)<br>[E.S.S.E.N.T.I.A.L (ess-guardian)](https://github.com/nasi546/ess-guardian) |
| **센서·액추에이터 통합** | • 수위·가스·화재·진동·PIR·온습도 센서 제어 <br>• 서보모터, 릴레이, RFID, LCD 등 이종 하드웨어 통합 시스템 구축 | Aiot_SmartHome<br>Flood_barrier<br>[E.S.S.E.N.T.I.A.L (ess-guardian)](https://github.com/nasi546/ess-guardian) |
| **Embedded Linux** <br>**& BSP** | • **Yocto** : RPi5용 이미지 빌드, meta-layer 작성 <br>• **Device Tree** : 오버레이 적용 및 커널 설정 <br>• **System** : systemd 서비스 등록, MCP2515(CAN) 설정 | [AI-Black-Box](https://github.com/nasi546/AI-Black-Box)<br>[E.S.S.E.N.T.I.A.L (ess-guardian)](https://github.com/nasi546/ess-guardian) |
| **영상·스트리밍** | • V4L2 카메라 캡쳐 → GStreamer 파이프라인 설계 <br>• AI 인퍼런스 연동 및 오버레이 출력 최적화 | AI-Black-Box<br>[E.S.S.E.N.T.I.A.L (ess-guardian)](https://github.com/nasi546/ess-guardian) |
| **Linux Device Driver** | • Character device(/dev), poll/read, IRQ 구현 <br>• I2C/GPIO 드라이버 직접 구현 및 RTC 연동 <br>• udev + systemd를 활용한 자동화 | [Device_Driver_Mini_Project](https://github.com/nasi546/Device_Driver_Mini_Project) |
| **운영/배포 자동화** | • udev 트리거를 이용한 USB 삽입 감지 자동화 <br>• state.json 기반 버전 관리 및 롤백 시스템 구현 | [Raspberry Pi 5 USB Auto Update](https://github.com/nasi546/Raspbery-pi5-USB-update)<br>[E.S.S.E.N.T.I.A.L (ess-guardian)](https://github.com/nasi546/ess-guardian) |
| **알고리즘 & 기본기** | • C++ STL 활용, 자료구조/알고리즘 문제 풀이 <br>• 코드 리팩토링 및 최적화 | [baekjoon](https://github.com/nasi546/baekjoon) |

---

### 🚀 Featured Projects

#### 1. [AI-Black-Box](https://github.com/nasi546/AI-Black-Box)
> **Raspberry Pi 5 + Hailo-8 + CAN 기반 차량용 AI 블랙박스**

* **핵심 기술:** Yocto 커스텀 이미지, GStreamer, CAN → KUKSA → AGL 클러스터 연동
* **내용:** 실제 차량 데이터를 모사하여 CAN 통신으로 전송하고, AI 가속기(Hailo-8)를 통해 객체를 실시간 탐지 및 녹화하는 블랙박스 시스템입니다.

#### 2. [E.S.S.E.N.T.I.A.L (ESS Guardian)](https://github.com/nasi546/ess-guardian)
> **ESS 시설 안전 통합 시스템: 환경/열화상 이상 감지 + Hybrid Patrol Robot(ROS2) + MQTT Control Tower**

🏆 **Award**: E.S.S.E.N.T.I.A.L (ESS Guardian) — **대한상공회의소 우수상**

* **핵심 기술:** ROS2(Nav2), ArUco Auto-Docking, MQTT, MLX90640(열화상), RFID, STM32(I2C 센서: SGP30/DHT 계열), MariaDB, Qt UI, systemd/udev 자동기동
* **내용:** Zone별 환경 데이터를 `ess/env`로 수집하고, 위험 이벤트(가스/열화상)를 `ess/alert`로 즉시 전송해 **DB 이력화 + UI 관제**까지 연결했습니다. 로봇은 순찰 후 ArUco 마커로 **홈 복귀 정렬/보정**을 수행하며, udev로 `/dev/cam_rgb` 심볼릭 링크를 만들어 **부팅 즉시 서비스가 올라오는 배포 구조**(systemd)까지 포함했습니다.

#### 3. [Raspberry Pi 5 – USB Auto Update System](https://github.com/nasi546/Raspbery-pi5-USB-update)
> **인터넷 연결 없이 USB만 꽂으면 끝나는 펌웨어 자동 업데이트 시스템**

* **핵심 기술:** udev, systemd Service/Timer, Shell Script, JSON Parsing
* **내용:** 현장 유지보수를 위해 USB/외장 SSD 연결 시 자동으로 앱을 업데이트합니다. 버전 관리, 헬스 체크, 자동 롤백, 로그 관리까지 포함된 안정적인 배포 파이프라인을 구현했습니다.

#### 4. [Device Driver Mini Project](https://github.com/nasi546/Device_Driver_Mini_Project)
> **리눅스 커널 레벨부터 유저 공간까지: 디바이스 드라이버 풀스택 구현**

* **핵심 기술:** Linux Kernel Module, Character Device, I2C Protocol, RTC
* **내용:** Raspberry Pi 4B에서 OLED, RTC, LED Bar 등을 제어하는 디바이스 드라이버 4종을 직접 작성하고, 데몬 앱과 연동하여 시스템을 제어하는 학습 프로젝트입니다.

#### 5. [Aiot_SmartHome](https://github.com/nasi546/Aiot_SmartHome)
> **STM32 & ESP32 & RPi5를 통합한 멀티 MCU 스마트홈**

* **핵심 기술:** STM32 HAL, FreeRTOS, Socket 통신, Sensor Integration
* **내용:** 가스/화재/방범 등 다양한 센서를 통합 관리하며, 외부 위협 감지 시 자동으로 차단 및 경고 시스템이 작동하는 종합 IoT 프로젝트입니다.

---

### 📫 Contact

새로운 기술을 배우고 적용하여 **실제 하드웨어를 움직일 때** 가장 큰 즐거움을 느낍니다.  
기술적인 토론이나 협업 제안은 언제든 환영합니다!

* **Email**: [minsoung1027@gmail.com](mailto:minsoung1027@gmail.com)
* **GitHub**: [@nasi546](https://github.com/nasi546)
