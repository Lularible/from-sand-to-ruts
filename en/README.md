# From Sand to Ruts: An Engineer's Understanding

A technical book that starts from philosophy, passes through physics and chips, and ends at automotive electronics.

<p align="center">
  <a href="../README.md"><img src="../assets/lang-zh.svg" alt="中文" height="30"></a>&nbsp;&nbsp;&nbsp;<a href="README.md"><img src="../assets/lang-en-active.svg" alt="English" height="30"></a>
</p>

> 🌐 Chinese version: [from-sand-to-ruts (中文)](../README.md). Chinese chapters live in [`chapters/`](../chapters/).

## Read Online

[Browse this book online (Chinese)](https://web-l.github.io/lularible-books/from-sand-to-ruts/index.html)

The English edition is currently Markdown-only.

## What This Book Covers

The book has 33 sections in seven parts:

- **Part 1 (5 sections): The Nature of Computation: From Philosophy to Mathematics.** Leibniz, Hilbert, Gödel, Turing, the von Neumann architecture, and your first line of embedded code.
- **Part 2 (6 sections): The Material Basis of Computing: From Sand to Chip.** A thought experiment about building a chip in a forest, then semiconductor physics, MOSFETs, CMOS, manufacturing, and the journey from wafer to ECU.
- **Part 3 (5 sections): From Logic Gates to Processors: How Instructions Are Executed.** Combinational logic, sequential logic, the datapath, pipelining, and the memory hierarchy.
- **Part 4 (6 sections): From On-Chip Bus to Vehicle Network: How Chips Talk to Each Other.** On-chip buses, SPI/I2C, CAN/CAN-FD, automotive Ethernet, PTP time synchronization, and sensor interfaces.
- **Part 5 (3 sections): From Bare Metal to AUTOSAR: Layers of Abstraction.** Bare-metal programming, RTOS, and AUTOSAR CP/AP: three paths with different complexity and different trade-offs.
- **Part 6 (3 sections): Diagnostics, Security, and OTA: The Operations Loop of Automotive Software.** UDS diagnostics, HSM security, and OTA updates with storage.
- **Part 7 (5 sections): The Engineer's Inner Core: Creating Possibilities Within Constraints.** A thought experiment, the spirit of "Two Bombs, One Satellite", resource scarcity, the Lanting Collection, and closing words.

No prior knowledge of automotive electronics is required. If you have ever wondered how a chip is made from sand, why a computer can compute, or how dozens of ECUs in a car talk to each other, this book is for you.

## Quick Start

Read the Markdown files under `en/chapters/`, in section order (Preface, then 1.1 through 7.5).

Recommended: VS Code with the Markdown Preview Enhanced extension, or Typora / Obsidian.

## License

Book content: [CC BY-NC-ND 4.0](../LICENSE)

## Companion Books

This book is the overview volume of the "Automotive Electronics Septet" series. The other six volumes are already published:

- **[PTP — From Thought Experiments to a Working Implementation](https://github.com/Lularible/ptp-book)** — Time synchronization, from thought experiments to a working PTP implementation.
- **[HSM — From Thought Experiments to a Security Cornerstone](https://github.com/Lularible/hsm-book)** — From cave-painting cryptography to hardware security modules, covering the full technical chain of the automotive HSM.
- **[Storage — Building a Reliable Data Home on Unreliable Hardware](https://github.com/Lularible/storage-book)** — The evolution of storage technology and the implementation of filesystems.
- **[UDS — From Diagnosis to a UDS Protocol Implementation](https://github.com/Lularible/uds-book)** — From the meta-questions of diagnostics through ISO 14229 and the AUTOSAR DCM source code to building a UDS stack by hand.
- **[Functional Safety — ISO 26262 Analysis and Code Implementation](https://github.com/Lularible/safety-book-iso26262)** — A functional-safety book narrated through the immune-system metaphor, combining ISO 26262 analysis, source-code dissection, and hands-on implementation.
- **[Automotive Embedded Software Engineering — Engineering Through an Architectural Metaphor](https://github.com/Lularible/swe-book)** — The engineering-methodology volume: architecture principles and quality infrastructure, with a runnable CI-pipeline teaching project, eng-lite.

## Acknowledgements

- Thanks to [@web-l](https://github.com/web-l) for building and maintaining the [mdBook site](https://web-l.github.io/lularible-books/) for this series, which makes it easier for everyone to read.

---

If you find it useful, a ⭐ is the best support. And if you can pass it on to someone who needs it, even better. 🚗💨
