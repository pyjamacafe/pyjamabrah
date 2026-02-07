---
# Page configuration
type: pitch
title: "Soan Papdi FPGA"
description: "A beginner friendly FPGA board based on the Lattice-iCE40UP5K Chip with healthy support from the open-source community."
thumbnail: "/images/pitch/model.jpeg"

# url: /embedded
#
# aliases:
# - /emb/
# - /embdedsystems/

# default CTA
default_cta: &defaults
  - cta:
    link: "https://pages.razorpay.com/pl_S5TIBZBqV4mteF/view"
    text: "🛒 Get Soanpapdi"
  - cta:
    link: "mailto:"
    text: "Contact Us ↗"

sticky:
  ctas: *defaults

sections:
  - section:
    - details:
        type: "half"
        title: "Soan Papdi FPGA!"
        subtitle: "*No MCU. Pure FPGA!"
        texts:
          - "Soan Papdi is a learning-focused FPGA board built around the Lattice iCE40UP5K, making FPGA development simple and approachable for learners."
          - "The design is intentional - Just `the FPGA`, `Flash memory`, a `USB-C` port for power and loading circuits, and Basics Input/Output."
          - "This is THE board if you wanted to dip yours toes and try Digital Design!"
    - details:
        type: "half"
        video: "_XBXZJRrtPg"
  - section:
    - details:
        type: "full"
        title: "Technical Specifications"
        subtitle: "For beginners and experts alike!"
    - details:
        type: "half"
        img: "/images/pitch/model.jpeg"
    - details:
        type: "half"
        sequence:
          - "Lattice iCE40UP5K FPGA with 5,280 LUTs."
          - "128 Mbit onboard Flash memory."
          - "On-chip PLL. Internal 10 kHz and 48 MHz Oscillators."
          - "2 × SPI and 2 × I²C Hard IPs"
          - "8 DSP multiplier blocks."
          - "Capable of hosting RISC-V soft-core CPUs."
          - "USB-C fully controlled by FPGA (no ext. MCU)."
          - "⁠Programmable via preloaded DFU bootloader."
          - "3.0 mm LEDs (through-hole)"
          - "4 × SMD LEDs"
          - "8 x  DIP switches"
          - "2 push buttons (Programming & Reset)"
          - "10 x I/O pins for ext. sensors & peripherals."
---
