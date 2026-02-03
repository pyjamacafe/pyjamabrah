---
type: pitch
title: "Learning Embedded Systems!"
description: "Serious Skills. Comfy Setting."
thumbnail: "/images/pitch/model.jpeg"

sections:
  - section:
    - details:
        type: "full"
        title: "Embedded Systems"
        subtitle: "insights and resoning from first principles"
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
        - text: "Historically, it has been very difficult and time consuming to learn low level details of how Computers really work. We are on a mission `to lowering the barrier to learning Embedded systems Software and Hardware`."
        - text: "We have organised the basics as organised courses in the **Embedded Systems Library**."
        img: ""
        video: ""
        ctas:
          - cta:
            primary: true
            link: ""
            text: "Join the Library!"
          - cta:
            primary: ""
            link: "mailto:support@pyjamacafe.com"
            text: "Contact Us"
  - section:
    - details:
        type: "full"
        title: "getting started"
        subtitle: "there is a structured path to it..."
    - details:
        type: "half"
        texts:
          - text: "Learning Embedded Systems is a circular process. Often times, you need to know a little bit of everything to make progress.Here is what we recommend -"
        sequence:
          - "Pick a 32/64 Bit CPU of choice (ARM/RISC-V etc)."
          - "Learn the basics of Assembly/C."
          - "Learn how to use build tools (gcc, as, ld) and utilities (make)."
          - "Write baremetal bootcode and boot the CPU from scratch."
          - "Implement a scheduler for the CPU and later replace it with an RTOS."
          - "Write state-machines and develop applications."
          - "Restart from #1."
        posttexts:
          - text: On each iteration, you will learn something new and more involved about the part.
    - details:
        type: "half"
        img: "/images/pitch/plan.jpg"
  - section:
    - details:
        type: "full"
        title: "CPU, Memory, and Peripherals"
        subtitle: "Fetch, Decode, Execute, Write back"
        video: "https://raw.githubusercontent.com/pyjamacafe/cache/master/pitch/cpu-model.webm"
        caption: "RISC-V Emulator running assembly code. Controls the GREEN LED with the Switch."
  - section:
    - details:
        type: "full"
        title: "Why it works?"
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
        img: "/images/pitch/model.jpeg"
        # img: "/images/circle/cpu.png"
        # video: "https://raw.githubusercontent.com/pyjamacafe/cache/master/pitch/cpu-model.mp4"
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
        title: "The Languages"
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

  - section:
    - details:
        type: "full"
        title: "Learning Tracks"
        subtitle: "all included in the **Library**"
        ctas:
          - cta:
            primary: true
            link: "/library"
            text: "Explore the Library"
          - cta:
            primary: ""
            link: "mailto:support@pyjamacafe.com"
            text: "Contact Us"
        cards:
          - card:
            title: "C Language"
            img: "/images/courses/c.png"
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
          - text: "Again, the library is a growing repositor of resources dedicated to learning Embedded systems from scratch."
          - text: "Yes. There is everything on the internet. We just organised it one place."
  - section:
    - details:
        type: "full"
        title: "Meet the Team"
        subtitle: "We spent a lot of time digging for the information you are looking for."
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
  - section:
    - details:
        type: "full"
        title: "what you'll learn"
        subtitle: "at the end of it all, you will..."
    - details:
        type: "half"
        img: "/images/circle/target.png"
    - details:
        type: "half"
        sequence:
          - "C programming, converting to Assembly and machine code."
          - "Grasp ARM-M, ARM-A, and RISC-V memory maps and programmer's models."
          - "Write and debug C programs for practical use."
          - "Command C constructs - functions, pointers, structs, unions, enums."
          - "Analyze data types - integers, floats, doubles, signed/unsigned, const, volatile."
          - "Understand data type memory representation - 2's complement, floating-point encoding."
    - details:
        type: "full"
        ctas:
            - cta:
              primary: true
              link: "/library"
              text: "Join the Library!"
---

