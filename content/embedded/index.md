---
type: pitch
title: "How to Embedded systems?"
description: "A structured path to learning and becoming Embedded Systems Engineer."
thumbnail: "/images/pitch/model.jpeg"

url: /embedded

aliases:
- /emb/
- /embdedsystems/

# default CTA
default_cta: &defaults
  - cta:
    link: "https://courses.pyjamabrah.com/web/checkout/68200b15f391a0bf84933bc7?purchaseNow=true&couponcode=FUNDCAFE"
    text: "🛒 Get Library (Yearly Access)"
  - cta:
    link: "/library"
    text: "learn more ↗"

# Add a Sticky Footer
sticky:
  discount:
    code: "FUND"
    percent: "70%"
  ctas: *defaults

sections:
  - section:
    - details:
        type: "full"
        title: "what is Embedded Systems?"
        subtitle: "Electronics with a CPU in them. Almost everything around us!"
    - details:
        type: "break"
    - details:
        type: "half"
        img: "/images/pitch/es.png"
    - details:
        type: "half"
        texts:
          - text: "Embedded Systems refers to electronics which are driven by an onboard CPU. Embedded Systems at the heart of it sense, process and actuate."
        sequence:
          - "**Sensors:** Measure the environment."
          - "**ADC:** Convert analog signals to digital numbers."
          - "**CPU:** Processes the numbers and figures what needs to be done. The software it runs implements the algorithms."
          - "**DAC:** Converts processed number to a analog signal."
          - "**Acturators:** Convery electrical signals to physical phenomena."
        posttexts:
          - text: "Embedded Software is all about program the CPU, reading inputs and generating outputs."
  - section:
    - details:
        type: "full"
        title: "in action ..."
        subtitle: "emulator based example"
        texts:
          - text: "This is the CPU (an internal view) reading the program, sensing the Switch state, processing the information and setting the output LED (actuating)"
        video: "https://raw.githubusercontent.com/pyjamacafe/cache/master/pitch/cpu-model.webm"
        caption: "RISC-V Emulator running assembly code. Controls the GREEN LED with the Switch."
  - section:
    - details:
        type: "full"
        title: "how to Embedded Systems?"
        subtitle: "master the CPU. learn how to command it."
    - details:
        type: "break"
    - details:
        type: "half"
        title: ""
        subtitle: ""
        img: "/images/pitch/model.jpeg"
    - details:
        type: "half"
        title: ""
        subtitle: ""
        texts:
        - text: "You only need to master the CPU. The mental model - often referred to as the `Programmer's model!`"
        - text: "Historically, it has been very difficult and time consuming to learn low level details of how Computers really work. We are on a mission `to lowering the barrier to learning Embedded systems Software and Hardware`."
        - text: "We have organised the basics as organised learning tracks in the **Embedded Systems Library**."
        img: ""
        video: ""
  - section:
    - details:
        type: "full"
        title: "where and how to start?"
        subtitle: "there is a structured path to it..."
    - details:
        type: "half"
        texts:
          - text: "Learning Embedded Systems is a circular process. Often times, you need to know a little bit of everything to make progress. Here is what we recommend -"
        sequence:
          - "Pick a 32/64 Bit CPU of choice (ARM/RISC-V etc)."
          - "Learn the basics of Assembly/C."
          - "Learn how to use build tools (gcc, as, ld) and utilities (make)."
          - "Write baremetal bootcode and boot the CPU from scratch."
          - "Implement a scheduler for the CPU and later replace it with an RTOS."
          - "Write state-machines and develop applications."
          - "Restart from #1."
    - details:
        type: "half"
        img: "/images/pitch/plan.png"
    - details:
        type: "full"
        texts:
          - text: On each iteration, you will learn something new and more involved about the part.
  - section:
    - details:
        type: "full"
        title: "why the 5?"
        subtitle: "Every Embedded Systems solution will have 3 of the 5 components."
    - details:
        type: "break"

    # the CPU
    - details:
        type: "half"
        title: "The CPU"
        subtitle: "The one that drives the System..."
        texts:
          - text: "Digital systems have a CPU (ARM/RISC-V etc) that drives the system states. The most popular CPUs for Embedded systems on the planet at the moment are - ARM-M, RISC-V and ARM-A."
    - details:
        type: "half"
        title: ""
        subtitle: ""
        img: "/images/circle/cpu.png"
  # The Languages
  - section:
    - details:
        type: "half"
        title: ""
        subtitle: ""
        img: "/images/circle/languages.png"
        video: ""
    - details:
        type: "half"
        title: "C and Assembly"
        subtitle: "Got to program the CPU somehow..."
        texts:
          - text: "Majority of Firmware/Systems software solutions are still authored in C with a little bit of Assembly."
  # Tools
  - section:
    - details:
        type: "half"
        title: "The Tools"
        subtitle: "Binary, debugging and automation"
        texts:
          - text: "CPUs don't understand Assembly or C, they only understand 0s and 1s in the memory interpreted as an instruction. There are tools compiler, debuggers and others that help go from text to binary, debug the system and automate a lot of flows."
    - details:
        type: "half"
        title: ""
        subtitle: ""
        img: "/images/circle/tools.png"
        video: ""
  # OS
  - section:
    - details:
        type: "half"
        title: ""
        subtitle: ""
        img: "/images/circle/os.png"
        video: ""
    - details:
        type: "half"
        title: "The Operating System"
        subtitle: "Managing state-machines and resources..."
        texts:
          - text: "When you have too many state-machines to be managed an Operating System helps. Majority of embedded system solutions use an RTOS."
  # FPGA
  - section:
    - details:
        type: "half"
        title: "Digital Hardware Design"
        subtitle: "Understanding how machines are designed"
        texts:
          - text: "Knowing how to implement simple digital machines and deploying them on FPGA will give you deep insights on how the CPUs and other digital circuits work."
    - details:
        type: "half"
        title: ""
        subtitle: ""
        img: "/images/circle/fpga.png"
        video: ""

  - section:
    - details:
        type: "full"
        title: "the Library Access"
        subtitle: "a collection of structured learning tracks with focus on delivering insights with hands on experiments."
        cards:
          - card:
            title: "C Language"
            img: "/images/courses/c.png"
            badge: "beginner"
            text: "Learning to write code by investigating the RISC-V assembly instructions."
            more: ""
          - card:
            title: "C Pointer"
            img: "/images/courses/pointers.png"
            text: "Learn to visualise, reason about and use pointers like a Ninja!"
            more: ""
          - card:
            title: "Data Structures (using C)"
            img: "/images/courses/dsa.png"
            text: "Learn how to orgranise and manipulate data using the C Language."
            more: ""
          - card:
            title: "Bit Manipulation (using C)"
            img: "/images/courses/bit-manipulation.png"
            text: "Master the art of manipulating bits with surgical precsion."
            more: ""
          - card:
            title: "GDB (GNU Debugger)"
            img: "/images/courses/gdb.png"
            text: "Learn the basics of debugging firmware code using GDB."
            more: ""
          - card:
            title: "ARM Cortex-M 101"
            img: "/images/courses/arm-m101.png"
            text: "Get an idea of how the Cortex-M (32 Bit) CPU can be studied and programmed."
            more: ""
          - card:
            title: "ARM Cortex-M 102 (Scheduler)"
            img: "/images/courses/cortex-m-102.jpg"
            text: "Program the M Class CPU from scratch in Assembly and implement a Scheduler."
            more: ""
          - card:
            title: "GNU make (Automation)"
            img: "/images/courses/gnu-make.png"
            text: "Learn how the make utility is used to automate build processes."
            more: ""
          - card:
            title: "GNU Linker Script"
            img: "/images/courses/gnu-ld.png"
            text: "Master the wizardry of controling the placement of code and data in memory."
            more: ""
          - card:
            title: "FreeRTOS (teardown/port)"
            img: "/images/courses/freeRTOS-101.png"
            text: "Learn the rare skill of porting FreeRTOS kernel on a new target."
            more: ""
          - card:
            title: "Zephyr RTOS (101)"
            img: "/images/courses/zephyr-101.png"
            text: "Explore the source code of Zephyr and boot it on a new target."
            more: ""
          - card:
            title: "Git and Gerrit"
            img: "/images/courses/git-gerrit.png"
            text: "Learn how to use GIT and Gerrit to effectively collaborate on a project."
            more: "/c"
          - card:
            title: "Technical Discussions"
            img: "/images/courses/discussions.png"
            text: "An overview of the vocabulary you'll need to talk to more experienced engineers."
            more: ""
          - card:
            title: "Aarch64: ARM-A 101"
            img: "/images/courses/arm-a101.png"
            text: "An introduction to the aarch64 (64 bit ARM A) architecture."
            more: ""
          - card:
            title: "ARM-A: Baremetal Programming"
            img: "/images/courses/arm-a102.png"
            text: "Explore how the 64 Bit CPU boots with hands on experiments."
            more: ""
          - card:
            title: "System Components (MMU/SMMU)"
            img: "/images/courses/smmu.png"
            text: "Dive into the concepts of Virtual memory and the hardware that enables it."
            more: ""
          - card:
            title: "Linux Kernel (build/run)"
            img: "/images/courses/linux-101.png"
            text: "Build and Run the Linux kernel from scratch by downloading the source code."
            more: ""
          - card:
            title: "Linux Device Driver 101"
            img: "/images/courses/ldd-101.png"
            text: "Get a hands on introduction by writing your own character device driver."
            more: ""
          - card:
            title: "Controlling Hardware"
            img: "/images/courses/ldd-102.png"
            text: "Extend your skills and write a driver to control a hardware peripheral."
            more: ""
          - card:
            title: "Kernel Facilities/Functions"
            img: "/images/courses/kernel-facilities.png"
            text: "Sharper the driver authoring skills by exploring kernel libraries."
            more: ""
          - card:
            title: "Digital Design 101"
            img: "/images/courses/digital-design.png"
            text: "Peel the abstraction layer, learn to design basic cuits and deploying on FPGA."
            more: ""
          - card:
            title: "How to Embedded Systems"
            img: "/images/courses/howtoembedded.png"
            text: "A short presentation on what is Embedded Systems and how to get started."
            more: ""
          - card:
            title: "Low Level @ Pyjama Cafe"
            img: "/images/courses/book.png"
            text: "Read the draft of our book focused on learning C Language."
            more: ""
          - card:
            title: "Python 101"
            img: "/images/courses/python.png"
            text: "Learn Python and the use in Embedded System."
            more: ""
          - card:
            title: "Walkthroughs"
            img: "/images/courses/walkthrough.png"
            text: "Learn how to navigate and deal with new source codes."
            more: ""
          - card:
            title: "Tech-Syncs"
            img: "/images/courses/tech-syncs.png"
            text: "Collection of talks by industry experts on ad-hoc topics."
            more: ""
          - card:
            title: "Podcasts"
            img: "/images/courses/podcast.png"
            text: "Collection of casual discussions with industry experts."
            more: ""
        posttexts:
          - text: ""
          - text: "Again, the library is a growing repository of resources dedicated to learning Embedded systems from scratch."
          - text: "Yes. There is everything on the internet. We just organised it one place."
  - section:
    - details:
        type: "full"
        title: "emulator first"
        subtitle: "you can learn without hardware"
        texts:
          - text: "here is a clip from lecture on implementing a scheduler on ARM Cortex-M CPU"
        video: "https://raw.githubusercontent.com/pyjamacafe/cache/master/pitch/demo-hands-on.webm"
        caption: "using emulator helps us run code without the need for the hardware."
  - section:
    - details:
        type: "full"
        title: "what about hardware?"
        subtitle: "learn on emulator, deploy on hardware (whenever)"
        cards:
          - card:
            title: "STM32 (VLDISCOVERY)"
            text: "This is cheap board based on the ARM-M3 controller. This also has a Qemu target."
            img: "/images/pitch/hardware/stm.jpg"
          - card:
            title: "Raspberry-Pi (4B)"
            text: "Raspberry-Pi 4B is a perfect target for learning ARM-A 64Bit (aarch64) CPUs"
            img: "/images/pitch/hardware/rpi-4b.png"
          - card:
            title: "Soan Papdi (FPGA)"
            text: "We designed our own low-cost high density FPGA to enable learning digital hardware design."
            img: "/images/pitch/hardware/fpga.jpg"
        posttexts:
          - text: "While the course uses a mix of emulator and actual hardware."
          - text: "We recommend you start with the emulators and later get the hardware when you feel confident"
  - section:
    - details:
        type: "full"
        title: "earn the badge"
        subtitle: "get a certificate for each technical track"
        posttexts:
          - text: "Certificates are available for the technical courses. The color and design may vary."
        img: "https://pyjamacafe.com/library/certificate.png"
  - section:
    - details:
        type: "full"
        title: "at the End of it all"
        subtitle: "at the end of it all, you will..."
    - details:
        type: "half"
        img: "/images/circle/target.png"
    - details:
        type: "half"
        sequence:
          - "Feel confident about all things Embedded Software."
          - "Have a strong grasp of the C and Assembly Language."
          - "Be able to program ARM-A (aarch64), ARM-M and RISC-V CPUs from scratch."
          - "Understand and use RTOS/Operating Systems confidently."
          - "Write and Debug software state-machines using tools and utilities."
          - "Be able to design and control a build system."
          - "And more..."
  - section:
    - details:
        type: "full"
        title: "the baristas"
    - details:
        type: "break"
    - details:
        type: "full"
        people:
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
              - text: "Electrical Engineer holding a Master’s degree in Embedded Systems, with a proven track record at industry giants. At Intel, contributed expertise to Navigation Firmware, Bluetooth Driver development, and RF validation software."
              - text: "Currently thriving as an Embedded Software Engineer at Google, drove innovation in Firmware development for the Power Management Sub-system on Tensor SoCs (Pixel Phones) and presently advancing system software for the Pixel Watch."
          - ind:
            name: "Mahmad Bharmal"
            img: "/images/authors/mb.jpg"
            designation: "Embedded SW Engineer"
            orgs: "Google | Ex-Intel"
            links:
              linkedin: "https://www.linkedin.com/in/streetdogg/"
              x: "https://x.com/_streetdogg"
              youtube: "https://www.youtube.com/@pyjamacafe"
            texts:
              - text: "Computer Engineer holding a Master’s degree in Embedded Systems. Worked on improving the debug architecture of the Bluetooth Firmware at Intel."
              - text: "Worked on ARM64 architecture, programming and exercising latest ARMv8/v9 extensions - programming in low-level FWs (ARM TF-A, trusty) and kernels (LK and Linux) at Google."
              - text: "Currently exploring the Pixel Watch Kernel and BSP (boot-loaders, Linux Kernel, Android HALs and frameworks)."
---

