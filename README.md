<div align="center">

![](./header.svg)

</div>

<br/>

## [ PROFILE ]

17-year-old backend engineer focused on low-level systems and computer architecture. Transitioning to Go while maintaining a deep interest in bare-metal simulation.

Currently an applicant for the **ITMO STARS 2026** program.

---

## [ CORE STACK ]

<div align="center">

![Python](https://img.shields.io/badge/Python-849283?style=flat-square&logo=python&logoColor=EAEAEA)
![Go](https://img.shields.io/badge/Go-849283?style=flat-square&logo=go&logoColor=EAEAEA)
![Flask](https://img.shields.io/badge/Flask-849283?style=flat-square&logo=flask&logoColor=EAEAEA)
![React](https://img.shields.io/badge/React-849283?style=flat-square&logo=react&logoColor=EAEAEA)
![Docker](https://img.shields.io/badge/Docker-849283?style=flat-square&logo=docker&logoColor=EAEAEA)
![Linux](https://img.shields.io/badge/Linux-849283?style=flat-square&logo=linux&logoColor=EAEAEA)
![Git](https://img.shields.io/badge/Git-849283?style=flat-square&logo=git&logoColor=EAEAEA)

</div>

---

## [ PROJECT: SIMCOM v2.0 ]

SimCom represents a high-fidelity 16-bit CPU emulator built as a complete software-defined machine. The goal: reproduce classical Von Neumann architecture at the instruction level with full observability.

**Architecture:**
- **Segmented Memory Model:** CS, DS, and SS registers provide explicit isolation of code, data, and stack segments across a 64K address space (0x0000 to 0xFFFF).
- **Hardware Fidelity:** Two's Complement arithmetic throughout the ALU. Signed overflow, zero, and negative flags are tracked per instruction via a dedicated FLAGS register. Custom ISA covers 24 operations including data transfer, arithmetic, bitwise logic, branching, subroutine calls, stack operations, and I/O.
- **Integrated Environment:** Flask REST API exposes per-step execution endpoints. Each session runs an isolated emulator instance. React frontend provides a live register file viewer, memory inspector, and inline assembler input.
- **Deployment:** Fully containerized via Docker Compose. Single command boot, no host dependencies required.

[View Repository](https://github.com/irumka/simcom)

---

## [ METRICS ]

<div align="center">

<img height="158" src="https://github-readme-stats.vercel.app/api?username=irumka&show_icons=true&count_private=true&include_all_commits=true&title_color=849283&text_color=EAEAEA&bg_color=1A1C1C&icon_color=849283&border_color=4E594A" alt="GitHub Stats"/>

<img height="158" src="https://github-readme-stats.vercel.app/api/top-langs/?username=irumka&layout=compact&langs_count=6&title_color=849283&text_color=EAEAEA&bg_color=1A1C1C&border_color=4E594A" alt="Top Languages"/>

</div>

<div align="center">

<img src="https://streak-stats.demolab.com/?user=irumka&background=1A1C1C&ring=849283&fire=849283&currStreakNum=EAEAEA&sideNums=849283&currStreakLabel=849283&sideLabels=849283&dates=4E594A&border=4E594A" alt="Streak"/>

</div>

---

## [ CONTACT ]

[Telegram](https://t.me/irumik) &nbsp;·&nbsp; [Email](mailto:kirill_vasyutchenkov@mail.ru)
