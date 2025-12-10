
<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,100:203a43&height=280&section=header&text=Verification%20Engineer&fontSize=60&fontColor=ffffff&fontAlignY=38&desc=Hyun's%20Portfolio&descAlignY=60&descAlign=50&animation=fadeIn" width="100%" />
</div>

<div align="center">
  <br>
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=26&duration=3000&pause=1000&color=203A43&center=true&vCenter=true&width=600&lines=System-Level+Verification;UVM+Architecture+Design;SoC+Design+%26+Validation;Turning+Specs+into+Reality" alt="Typing SVG" />
  </a>
</div>

<br>

<div align="center">
  <b>" Design with Logic, Verify with <span style="color: #203A43">Precision</span> "</b>
  <br><br>
  안녕하세요! <b>SystemVerilog</b>와 <b>UVM</b>을 기반으로 신뢰성 높은 칩을 설계하는 검증 엔지니어입니다.<br>
  논리적인 시나리오 설계와 자동화된 검증 환경 구축에 강점이 있습니다.
</div>

<br>

### 🏗️ Verification Environment Architecture
> **My UVM Structure Strategy:**

```mermaid
classDiagram
    direction TB
    class uvm_test
    class uvm_env
    class uvm_scoreboard
    class uvm_agent
    class uvm_sequencer
    class uvm_driver
    class uvm_monitor
    
    uvm_test --* uvm_env : Contains
    uvm_env --* uvm_agent : Contains
    uvm_env --* uvm_scoreboard : Analysis
    uvm_agent --* uvm_sequencer : Control
    uvm_agent --* uvm_driver : Drive
    uvm_agent --* uvm_monitor : Monitor
    
    uvm_driver ..> DUT : Virtual Interface
    uvm_monitor ..> DUT : Virtual Interface
````

<br>

### 🛠️ Technical Skills

\<div align="center"\>

| **Category** | **Stack** |
| :--- | :--- |
| **Languages** | \<img src="https://www.google.com/search?q=https://img.shields.io/badge/SystemVerilog-181717%3Fstyle%3Dflat-square%26logoColor%3Dwhite"/\> \<img src="https://www.google.com/search?q=https://img.shields.io/badge/Verilog-B71C1C%3Fstyle%3Dflat-square%26logoColor%3Dwhite"/\> \<img src="https://www.google.com/search?q=https://img.shields.io/badge/C%2B%2B-00599C%3Fstyle%3Dflat-square%26logo%3Dc%252B%252B%26logoColor%3Dwhite"/\> \<img src="https://www.google.com/search?q=https://img.shields.io/badge/Python-3776AB%3Fstyle%3Dflat-square%26logo%3Dpython%26logoColor%3Dwhite"/\> |
| **Methodologies** | \<img src="https://www.google.com/search?q=https://img.shields.io/badge/UVM-IEEE%25201800.2-4CAF50%3Fstyle%3Dflat-square%26logoColor%3Dwhite"/\> \<img src="https://www.google.com/search?q=https://img.shields.io/badge/AMBA\_AXI-000000%3Fstyle%3Dflat-square%26logoColor%3Dwhite"/\> \<img src="https://www.google.com/search?q=https://img.shields.io/badge/APB%252FAHB-0091BD%3Fstyle%3Dflat-square%26logoColor%3Dwhite"/\> |
| **EDA Tools** | \<img src="https://www.google.com/search?q=https://img.shields.io/badge/Xilinx\_Vivado-FF0000%3Fstyle%3Dflat-square%26logo%3Dxilinx%26logoColor%3Dwhite"/\> \<img src="https://www.google.com/search?q=https://img.shields.io/badge/ModelSim-2C2255%3Fstyle%3Dflat-square%26logoColor%3Dwhite"/\> \<img src="https://www.google.com/search?q=https://img.shields.io/badge/Quartus-0071C5%3Fstyle%3Dflat-square%26logo%3Dintel%26logoColor%3Dwhite"/\> |
| **Tools** | \<img src="https://www.google.com/search?q=https://img.shields.io/badge/Git-F05032%3Fstyle%3Dflat-square%26logo%3Dgit%26logoColor%3Dwhite"/\> \<img src="https://www.google.com/search?q=https://img.shields.io/badge/Linux-FCC624%3Fstyle%3Dflat-square%26logo%3Dlinux%26logoColor%3Dblack"/\> \<img src="https://www.google.com/search?q=https://img.shields.io/badge/Jira-0052CC%3Fstyle%3Dflat-square%26logo%3Djira%26logoColor%3Dwhite"/\> |

\</div\>

<br>

### 🚀 Key Projects

| **Project** | **Role & Description** | **Tech Stack** |
| :--- | :--- | :--- |
| **[UVM Virtual Sequencer](https://www.google.com/search?q=https://github.com/hyun1006)** | • **Multi-Agent Control:** APB/SPI Agent 간의 동기화 및 시퀀스 제어<br>• **Architecture:** Virtual Sequence를 활용한 계층적 검증 환경 구축<br>• **Result:** 복잡한 시나리오 검증 자동화 성공 | `SystemVerilog`<br>`UVM` |
| **[AXI4 Bus VIP](https://www.google.com/search?q=https://github.com/hyun1006)** | • **VIP Development:** AXI4 Master/Slave VIP 설계 및 구현<br>• **Verification:** Constrained Random Test를 통한 프로토콜 무결성 검증<br>• **Result:** Bus Latency 최적화 및 Deadlock 이슈 해결 | `Verilog`<br>`AMBA AXI` |
| **[FPGA Image Accelerator](https://www.google.com/search?q=https://github.com/hyun1006)** | • **HW/SW Co-design:** Zynq SoC를 활용한 엣지 검출 가속기<br>• **Optimization:** HLS를 활용하여 SW 대비 처리 속도 50배 향상<br>• **Result:** 실시간(Real-time) 영상 처리 구현 | `Vivado`<br>`Zynq` |

<br>

### 📊 GitHub Analytics

\<div align="center"\>
\<a href="https://github.com/ryo-ma/github-profile-trophy"\>
\<img src="https://www.google.com/search?q=https://github-profile-trophy.vercel.app/%3Fusername%3Dhyun1006%26theme%3Dflat%26column%3D7%26margin-w%3D15%26margin-h%3D15%26no-bg%3Dtrue" /\>
\</a\>
\</div\>

\<div align="center"\>
\<img src="https://www.google.com/search?q=https://github-readme-stats.vercel.app/api%3Fusername%3Dhyun1006%26show\_icons%3Dtrue%26theme%3Dradical%26bg\_color%3D0f2027%26title\_color%3D203a43%26text\_color%3Dffffff%26hide\_border%3Dtrue" height="150" alt="stats graph" /\>
\<img src="https://www.google.com/search?q=https://github-readme-stats.vercel.app/api/top-langs/%3Fusername%3Dhyun1006%26layout%3Dcompact%26theme%3Dradical%26bg\_color%3D0f2027%26title\_color%3D203a43%26text\_color%3Dffffff%26hide\_border%3Dtrue" height="150" alt="languages graph" /\>
\</div\>

<br>

\<div align="center"\>
\<img src="https://www.google.com/search?q=https://capsule-render.vercel.app/api%3Ftype%3Dwaving%26color%3D0:0f2027,100:203a43%26height%3D80%26section%3Dfooter" width="100%" /\>

\<a href="mailto:your\_email@gmail.com"\>\<img src="https://www.google.com/search?q=https://img.shields.io/badge/Contact-Gmail-D14836%3Fstyle%3Dfor-the-badge%26logo%3Dgmail%26logoColor%3Dwhite"/\>\</a\>
\<a href="https://www.google.com/search?q=https://www.linkedin.com/in/"\>\<img src="https://www.google.com/search?q=https://img.shields.io/badge/Connect-LinkedIn-0077B5%3Fstyle%3Dfor-the-badge%26logo%3Dlinkedin%26logoColor%3Dwhite"/\>\</a\>

\</div\>

```
```
