---
# Page configuration
type: pitch
title: "Soan Papdi FPGA"
description: "A beginner friendly FPGA board based on the Lattice-iCE40UP5K Chip with healthy support from the open-source community."
thumbnail: "/images/soanpapdi/soanpapdi.jpg"

url: /fpga

aliases:
- /soanpapdi/
- /sp/

# default CTA
default_cta: &defaults
  - cta:
    link: "https://pages.razorpay.com/pl_S5TIBZBqV4mteF/view"
    text: "🛒 Get Soanpapdi"
    primary: true
  - cta:
    link: "mailto:hardikseth1975@gmail.com"
    text: "Contact Us ↗"

sticky:
  text: "Get your own Soan Papdi"
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
        # img: "/images/soanpapdi/soanpapdi.jpg"
        model: "/models/sp.glb"

  - section:
    - details:
        type: "full"
        title: "4 Steps - Zero to Hero!"
        subtitle: "for kids and adults alike"
    - details:
        type: "half"
        video: "https://raw.githubusercontent.com/pyjamacafe/cache/master/soanpapdi/icestudio.webm"
    - details:
        type: "half"
        texts:
          - No complicated installation flow. No lame driver installation. Download the IDE, double click, get started!
        sequence:
          - Draw the circuit using building blocks.
          - Map the inputs and output to FPGA pins.
          - Verify and Build.
          - Upload to the board!
        posttexts:
          - Program it using the open-source iCEStudio IDE or use RAW HDL!
        ctas: *defaults
  - section:
    - details:
        type: "full"
        title: "Technical Specifications"
        subtitle: "For beginners and experts alike!"
    - details:
        type: "half"
        youtube: "_XBXZJRrtPg"
    - details:
        type: "half"
        list:
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
        ctas: *defaults
  - section:
    - details:
        type: "full"
        title: "Minimal Design"
        subtitle: "less is more"
    - details:
        type: "half"
        defines:
          "iCE40UP5k": "The soul of Soan Papdi board is the FPGA by Lattice Semiconductor - the iCE40UP5k. We picked this FPGA because the open-source community loves it. It is very easy to program using open-source tools and utilities. Besides all of this, it has enough LUTs(logical units) to realize the RISC-V CPU."

          "SRAM": "The circuit configuration are held in SRAM. When the board is powered on, the FPGA pulls the configuration and realizes the circuit."

          "PROG and RESET": "RESET is to reboot the board. When PROG is pressed and RESET is toggled, the board is ready to accept the new configuration."

          "A3-A0, B3-B0": "These are two sets of switches specifically to serve as user inputs for circuits that we develop."

          "D7-D0": "These are Yellow LED to serve as the outputs for our circuits and show the output value."
          "S3-S0": "Status LEDs for our circuits."
          "I0-I9": "General purpose I/O pins to connect to external circuits."
    - details:
        type: "half"
        img: "/images/soanpapdi/soanpapdi-pins.png"

  - section:
    - details:
        type: "full"
        title: "Free Lectures"
        subtitle: "Lectures to guide you on how to use the board"
    - details:
        type: "full"
        youtubePlaylist:
          - title: "Soan Papdi: Unboxing and board Walkthrough"
            link: "U5uXXChxLwI"
          - title: "Soan Papdi: Software Setup from the Source"
            link: "mDM6PSjPgIU"
          - title: "Soanpapdi FPGA Board (optional)"
            link: _XBXZJRrtPg
          - title: "1. Transistor as a Switch"
            link: "vo9w4ybxnvg"
          - title: "2. Logical Gates using Switches"
            link: "4x95liMJepA"
          - title: "3. CPU vs FPGA detailed discussion"
            link: "LOV8ZIaD4OY"
          - title: "4. On the history of where it all started"
            link: "c_OnaoL9F4Q"
        posttexts:
          - "This is a ever growing resource"
  - section:
    - details:
        type: "break"
    - details:
        type: "half"
        img: "/images/soanpapdi/versions.jpg"
        caption: "The journey of Soan Papdi to it's final form."
    - details:
        type: "half"
        title: "the backstory"
        subtitle: "Soan Papdi is deliberate and very intentional"
        texts:
          - "Soan Papdi board is designed to be easy to use, be simple in design and not limit the learner."
        ctas: *defaults
    - details:
        type: "half"
        title: "Ready to Ship"
        texts:
          - "Hand assembled and tested by Hardik (personally). Ready to be shipped."
        ctas: *defaults
    - details:
        type: "half"
        img: "/images/soanpapdi/shipping.jpg"
        caption: "The journey of Soan Papdi to it's final form."

  - section:
    - details:
        type: "full"
        title: "the team"
        subtitle: "a collaboration between Pyjama Cafe and DIY with Hardik"
        people:
          - ind:
            name: "Hardik Seth"
            img: "/images/authors/hs.jpg"
            designation: "Embedded Engineer"
            orgs: "STEMpedia"
            links:
              linkedin: "https://www.linkedin.com/in/hardik-seth-8687b7201/"
              youtube: "https://www.youtube.com/@DIYwithHardik"
              x: "https://x.com/HardikSeth69?s=20"
            texts:
              - "An embedded product engineer who designs PCBs, writes firmware, and enjoys turning ideas into complete, working hardware products from first schematic to final blink."
              - "Engineer by day, Maker by night - playing with electronics since the age of 9. From childhood, I’ve loved tearing things apart, rebuilding them, and learning through hands-on experimentation and how-to videos."
          - ind:
            name: "Piyush Itankar"
            img: "/images/authors/pi.jpg"
            designation: "Senior Embedded SW Engineer"
            orgs: "Google | Ex-Intel"
            links:
              linkedin: "https://www.linkedin.com/in/streetdogg/"
              x: "https://x.com/_streetdogg"
              youtube: "https://www.youtube.com/@pyjamacafe"
            texts:
              - "Electrical Engineer holding a Master’s degree in Embedded Systems, with a proven track record at industry giants. At Intel, contributed expertise to Navigation Firmware, Bluetooth Driver development, and RF validation software."
              - "Currently thriving as an Embedded Software Engineer at Google, drove innovation in Firmware development for the Power Management Sub-system on Tensor SoCs (Pixel Phones) and presently advancing system software for the Pixel Watch."
        posttexts:
          - "Proposal of Soan Papdi was made by Piyush, the idea was brought to life by Hardik."
          - "Made with Love and Care, in India ❤️"
---
