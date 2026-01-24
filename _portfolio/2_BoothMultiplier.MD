---
title: "8-Bit Booth Multiplier"
excerpt: "An 8-bit booth multiplier with custom CMOS layouts in Cadence Virtuoso using 90nm process technology."
header:
  teaser: assets/img/booth.png
---

## About
![Figure 1. Cadence Layout](/portfolio/assets/img/booth_multiplier.png)
*Figure 1. Cadence Layout of Completed Booth Multiplier*

I designed and implemented an 8-bit Booth multiplier using full-custom CMOS design in **Cadence Virtuoso** (90 nm). I also developed hierarchical, transistor-level schematics and layouts, achieving DRC/LVS clean verification. The design was built from scratch all the way from fundamental building pieces like an inverter, an NAND gate, an NOR gate, etc...

Design techniques such as the **manchester carry chain** were used to reduce delays in the circuit.  

![Figure 2. Inverter Layout](/portfolio/assets/img/inverter.png)
*Figure 2. Inverter Designed by PMOS + NMOS*

To test the functionality of my layout design, I performed parasitic extraction and post-layout simulations to evaluate timing and layout-induced delays. The design was optimized for speed and area through fanout balancing, modular cell architecture, and careful floorplanning.

![Figure 3. Schematic](/portfolio/assets/img/booth_schematic.png)
*Figure 3. Overall schematic of the Booth Multiplier*

This project was a significant learning experience that bridged fundamental digital logic with real transistor-level design. I revisited core concepts such as K-maps and Boolean optimization, then extended them into practical considerations including fanout, propagation delay, and transistor sizing. Designing the entire Booth multiplier from scratch required careful modular decomposition and incremental verification, which reinforced the importance of structured testing and hierarchy in complex designs. The iterative debug cycle—from schematic to layout to post-layout simulation—also built resilience, as each stage introduced new constraints and tradeoffs that had to be systematically addressed.

## Credits
**ECE 4385 VLSI Design** Final Design Project

{% include gallery %}
