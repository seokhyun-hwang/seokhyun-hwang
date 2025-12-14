# 👋 Hello, I'm SEOKHYUN HWANG
> **FPGA & Embedded System Developer**
> *Digital Logic Design Engineer | SystemVerilog & RISC-V Architecture*

<br>

## 🚀 About Me
- 🎓 **Education**: 고려대학교 전자및정보공학과 (졸업)
- 📍 **Location**: Incheon, Korea
- 🎂 **Birth**: 1998.10.06.
- 📝 **Intro**:
  하드웨어 아키텍처의 동작 원리를 탐구하는 것을 즐기는 **반도체 설계 검증 엔지니어**입니다.
  **SystemVerilog**를 주력으로 **RISC-V CPU**를 밑바닥부터 설계하고 **AMBA APB** 프로토콜을 구현한 경험이 있습니다. 기능 구현을 넘어 **Hardware Acceleration**과 **Verification(검증)** 역량을 갖추어 신뢰성 높은 시스템을 만드는 것을 목표로 합니다.

<br>

## 🛠️ Tech Stacks
### Languages
![SystemVerilog](https://img.shields.io/badge/SystemVerilog-181717?style=flat&logo=systemverilog&logoColor=white&color=00599C)
![Verilog](https://img.shields.io/badge/Verilog-181717?style=flat&logo=verilog&logoColor=white&color=555555)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat&logo=c&logoColor=white&color=blue)
![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=c%2B%2B&logoColor=white&color=00599C)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white&color=3776AB)
![MATLAB](https://img.shields.io/badge/MATLAB(Basic)-e36414?style=flat&logo=mathworks&logoColor=white&color=orange)

### Tools & IDE
![Vivado](https://img.shields.io/badge/Xilinx%20Vivado-red?style=flat&logo=xilinx&logoColor=white&color=red)
![Vitis](https://img.shields.io/badge/Xilinx%20Vitis-orange?style=flat&logo=xilinx&logoColor=white&color=orange)
![ModelSim](https://img.shields.io/badge/ModelSim-Verification-success?style=flat&color=green)
![EDA Playground](https://img.shields.io/badge/EDA%20Playground-9C27B0?style=flat&logo=edaplayground&logoColor=white&color=9C27B0)

<br>

## 🗂️ Projects

### 🏛️ RISC-V & CPU Architecture
| Project & Description | Tech Stack | Links |
| :--- | :--- | :---: |
| **🚀 SystemVerilog RISC-V RV32I Multi-Cycle CPU**<br>• 32-bit RISC-V Multi-Cycle Core 설계 및 **AMBA APB** 버스 인터페이스 구축<br>• UART, GPIO 등 주변장치 통합 제어<br>• FSM 기반 Control Unit 및 Datapath 최적화 | ![SystemVerilog](https://img.shields.io/badge/-SystemVerilog-00599C)<br>![AMBA APB](https://img.shields.io/badge/-AMBA_APB-critical) | [👉 Repo](https://github.com/hyun1006/RISC-V_RV32I_CPU_Multi-Cycle_-_AMBA_APB_Peripheral) |
| **🏛️ RISC-V RV32I Single-Cycle CPU**<br>• RISC-V 아키텍처의 기초가 되는 Single-Cycle CPU 구현<br>• 명령어 처리 Datapath 및 Control Unit 설계<br>• 기본 명령어 셋 시뮬레이션 검증 | ![SystemVerilog](https://img.shields.io/badge/-SystemVerilog-00599C) | [👉 Repo](https://github.com/hyun1006/RISC-V_RV32I_CPU_Single-Cycle) |

### ⚡ FPGA & Video Processing
| Project & Description | Tech Stack | Links |
| :--- | :--- | :---: |
| **🎲 Real-time VGA Processing & Dice Game SoC**<br>• VGA 인터페이스 기반 실시간 영상 처리 및 다이스 게임 구현<br>• 실시간 Red Color 검출 및 픽셀 면적 계산 알고리즘 하드웨어화<br>• Master-Slave 아키텍처 설계 | ![SystemVerilog](https://img.shields.io/badge/-SystemVerilog-00599C)<br>![FPGA](https://img.shields.io/badge/-FPGA-red) | [👉 Repo](https://github.com/hyun1006/Real-time-VGA-Processing-Filter-Dice-Game) |
| **🖼️ Line Buffer Scaler**<br>• **Line Buffer**를 활용한 효율적인 하드웨어 이미지 스케일러 설계<br>• 스트림 데이터 처리를 통한 메모리 사용 최적화<br>• 영상 크기 변환 로직 구현 | ![SystemVerilog](https://img.shields.io/badge/-SystemVerilog-00599C)<br>![Image Processing](https://img.shields.io/badge/-Processing-success) | [👉 Repo](https://github.com/hyun1006/LineBuffer_Scaler) |

### 🔍 Verification & Embedded Systems
| Project & Description | Tech Stack | Links |
| :--- | :--- | :---: |
| **🔎 UART Verification (VIP)**<br>• UART 통신 신뢰성 검증을 위한 **Verification Environment** 구축<br>• Testbench 및 VIP(Verification IP) 개념 적용<br>• 다양한 전송 시나리오에 대한 프로토콜 검증 | ![SystemVerilog](https://img.shields.io/badge/-SystemVerilog-00599C)<br>![Verification](https://img.shields.io/badge/-Verification-violet) | [👉 Repo](https://github.com/hyun1006/UART_Verification) |
| **⏱️ UART Watch & Stopwatch with Sensors**<br>• UART 통신, 시계/스톱워치, 센서 제어(HC-SR04, DHT-11) 통합 시스템<br>• 하드웨어-소프트웨어 인터페이스 제어 실습<br>• 센서 데이터 처리 및 타이밍 로직 구현 | ![Verilog](https://img.shields.io/badge/-Verilog-555555)<br>![Sensors](https://img.shields.io/badge/-Sensors-orange) | [👉 Repo](https://github.com/hyun1006/UART_Watch_Stopwatch_HC-SR04_DHT-11) |
| **⌚ Digital Watch & Stopwatch**<br>• 디지털 논리 회로 설계의 기초인 시계 및 정밀 스톱워치 구현<br>• FND Dynamic Scanning 및 Debouncing 로직 적용<br>• 계층적 모듈 설계를 통한 시스템 구조화 | ![Verilog](https://img.shields.io/badge/-Verilog-555555) | [👉 Repo](https://github.com/hyun1006/Watch_Stopwatch) |
| **🛠️ Github Auto Uploader**<br>• Python을 활용한 깃허브 업로드 자동화 스크립트<br>• 개발 워크플로우 효율성 증대 도구 | ![Python](https://img.shields.io/badge/-Python-3776AB) | [👉 Repo](https://github.com/hyun1006/Github_AutoUploader) |

<br>

## 🎓 Education & Training
* **[하만 세미콘 아카데미]** | [대한상공회의소 서울기술교육센터] | *2025.07.01 ~ 2026.01.26 (예정)*
    * 주요 학습 내용: Verilog HDL/SystemVerilog & UVM을 활용한 FPGA 설계 및 검증
* **[반도체공정및실습캡스톤디자인]** | [고려대학교] | *2024.03 ~ 2024.06*
    * Project 내용: 공정 압력에 따른 증착률 분석 연구
* **[교내 반도체공정, 장비 실습]** | [고려대학교] | *2021.01 ~ 2021.01*
    * Project 내용: Photo-litho, Etch, Deposition 등 반도체 공정 실습을 통해 공정 과정 설계와 실제 구현

<br>

## 📂 Other Projects & Research
> **📄 압력 변화와 열처리 과정이 박막에 미치는 영향**
> * **설명**: 공정 압력(유량)에 따른 증착률 및 비저항 분석 연구
> * **자료 보기**: 👉 [PDF 다운로드 (경로 확인 필요)](./files/반도체공정및실습캡스톤_보고서.pdf)

<br>

## 📈 GitHub Stats
<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=hyun1006&show_icons=true&theme=radical" height="150" alt="stats graph" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=hyun1006&layout=compact&theme=radical" height="150" alt="languages graph" />
</div>

<br>

## 📫 Contact
* 📞 **Phone**: 010-6506-3552
* 📧 **Email**: [doitndidit@gmail.com](mailto:doitndidit@gmail.com)
* 🐱 **Github**: [https://github.com/hyun1006](https://github.com/hyun1006)
