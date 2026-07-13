# 🛠️ FreeCPUcore: From Boolean Algebra to Hacker-Fab

A complete open-source hardware guide to designing a custom CPU core using Boolean algebra, prototyping with 74LSxx TTL logic, and preparing schematics for desktop semiconductor fabrication (Sputtering).

---

## 🗺️ Project Roadmap & Documentation Structure

This documentation is currently being synchronized from paper to GitHub. 

- [x] **1. Binary** — *Status: 100% Finalized (Paper & Breadboard)*
  Fundamentals of binary arithmetic and representation. Visualizing signed 5-bit numbers `[-16, 15]` using the spatial dynamics of a Go-board to understand the inverse character without abstract formulas.
  
- [x] **2. Logic** — *Status: 100% Finalized (Paper & Breadboard)*
  Reduction of complex operations into pure Boolean algebra. Driven by a question-catalog (NOT, AND, OR, XOR) and wired on separate, isolated breadboards. Investigating the Ripple-Carry bottleneck and the beauty of padding.
  
- [x] **3. ALU (Arithmetic Logic Unit)** — *Status: 95% Finalized (Paper & Breadboard)*
  Mathematical design of the core execution units using basic TTL logic constraints.

- [ ] **4. Registers 🌟 (Core Focus)** — *Status: Active Hardware Prototyping (74LSxx)*
  The heart of the architecture. Deep dive into custom register design, state retention, and bus isolation without proprietary silicon blocks.

- [ ] **5. Takt (Clock Generation)** — *Status: Logic Defined / Testing*
  Clock conditioning, glitch-free edge detection, and timing constraints for low-frequency prototyping.

- [ ] **6. 3-Device Handshake 🌟 (Core Focus)** — *Status: Active Code & Protocol Development*
  The asynchronous communication protocol. Ensuring safe, race-condition-free data transport between three independent physical silicon/TTL modules.

- [ ] **7. Getting Started: The Full CPU** — *Status: Planned*
  Integration of all modules into a fully functional schematic ready for lithography mask-generation and sputtering.

---

## ⚡ Technical Foundations & Hardware Target

- **Logic Family:** 74LSxx Series (TTL) for the physical bench-prototype.
- **Goal:** Preparation of logical schematics optimized for physical micro-fabrication (Sputtering/Lithography) in a home/hacker lab environment.
- **Philosophy:** No black boxes. Pure discrete logic derived directly from mathematical equations.

---

## 🤝 Sponsoring & Open Source

This project is fully open-source because semiconductor knowledge should belong to the world, not just corporate giants. If you want to support independent hardware research, consider sponsoring this project.

*Note: Sponsoring platforms are currently being set up. In the meantime, star this repository to show your support!*
