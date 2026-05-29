# Embedded Firmware Engineer Fundamentals

A single-page reference guide covering the core knowledge areas for embedded firmware and software engineers. Includes deep dives, code examples, and study guides for key textbooks.

**Live site:** https://jtraut.github.io/Embedded-Fundamentals/

## Full Guide

[`Embedded_Firmware_Engineer_Fundamentals.html`](Embedded_Firmware_Engineer_Fundamentals.html) — 7 tabs:

1. **Embedded & Systems** — MCU/SoC/Linux spectrum, bare-metal vs RTOS vs Linux, memory maps & MMIO, registers & bit fields, MMU vs MPU, boot chain, interrupts & ISRs, DMA, concurrency & reentrancy, device drivers, on-board buses (I2C, SPI, UART, CAN), toolchain & linker, debug/power/watchdog. Includes study guides for *Making Embedded Systems* and *Programming Embedded Systems*.

2. **C / C++** — endianness, fixed-width types, alignment & struct packing, bit-fields, serialization, `memcpy` use & misuse, `volatile`, `const`/`static`/`extern`, bit manipulation toolkit, stack/heap/static memory, C vs C++ tradeoffs, C++ features that pay off in embedded, undefined behavior traps. Study guides for K&R, *Data Structures & Algorithm Analysis in C++*, *Accelerated C++*, and *C++ Concurrency in Action*.

3. **Design Patterns & OOP** — four pillars of OOP, SOLID principles, GoF creational/structural/behavioral patterns, worked examples (Strategy, Observer, State machine as FSM, Factory Method). Study guide for *Design Patterns* (GoF).

4. **Networking & OSI** — OSI 7-layer model, TCP/IP stack & encapsulation, TCP vs UDP, unicast/multicast/broadcast, MAC/IP/ARP, Ethernet, Wi-Fi, Cellular, Bluetooth & BLE, Automotive Ethernet, switches & PHYs, VLANs & TSN. Study guide for *TCP/IP Illustrated Vol. 1*.

5. **Time Sync / PTP** — NTP vs PTP, IEEE 1588, clock roles & grandmaster hierarchy, BMCA, sync message exchange, offset & delay math, one-step vs two-step, hardware timestamping, 802.1AS gPTP, 802.1AS-2020 deep dive, peer-delay & rateRatio math, deployment & troubleshooting.

6. **Glossary** — quick-reference definitions across all topic areas.

7. **Interview Q&A** — common interview questions with answers across embedded, C/C++, and networking.

## Basic Guide

[`Embedded_Firmware_Engineer_Fundamentals_Basic.html`](Embedded_Firmware_Engineer_Fundamentals_Basic.html) — a more concise 6-tab version covering the same topic areas (minus the Design Patterns tab) with shorter explanations and fewer code examples. Good as a quick refresher or starting point.

## Viewing Locally

Open either HTML file directly in a browser — no build step or server required.
