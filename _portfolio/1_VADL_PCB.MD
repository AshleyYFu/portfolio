---
title: "Rocket Payload Electronics PCB"
excerpt: "PCBs for rocket payload including a Teensy breakout board and an in-situ soil sensing board."
header:
  teaser: assets/img/pcb_alone.png
---

## About
![Figure 1. Connections to PCBs](/portfolio/assets/img/vadl_pcb.png)
*Figure 1. PCBs from Electronics Design*

As the Lead Electrical Engineer of Vanderbilt’s **7× national-champion** rocket team competing in NASA’s USLI challenge, I lead the design and integration of payload electronics responsible for flight-state detection, sensing, and post-landing activation. 

Recently, I designed two custom PCBs in Altium: a modular Teensy breakout board providing robust, connectorized interfaces to all peripherals (power, IMU, motor controller, RGB LED, etc.), and an in-situ soil sensing board for post-landing analysis. The soil board interfaces scientific-grade EC, pH, and nitrate probes via a high-impedance instrumentation amplifier designed to preserve signal fidelity when digitized by the Teensy ADC. Both boards were designed with an emphasis on compactness, modularity, and signal integrity in a launch-constrained, noise-sensitive environment. Moreover, both boards have been manufactured by JLCPCB and assembled - ready to be launched!

The project is highly cross-disciplinary, requiring close collaboration with mechanical engineers to ensure survivability under launch loads and reliable integration with deployment mechanisms, and with environmental engineers to align sensing logic with the scientific objectives of the payload. 