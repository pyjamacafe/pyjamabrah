---
layout: products

url: /freeRTOS-101

aliases:
- /freertos-porting/
- /freertos/

define:
  course-name: &course-name "FreeRTOS - Teardown and Porting"
  enrolled: &enrolled 2000+
  lastupdated: &lastupdated "23 November 2025"
  cover-art: &cover-art "/images/courses/freeRTOS-101.png"
  oneliner: &oneliner "`Port FreeRTOS on a new target from scratch`"

title: *course-name
date: "2025-10-11T17:48:22+05:30"
tags:
  - bundle
description: *oneliner
thumbnail: *cover-art
categories: courses
product: "4-freeRTOS-101"

param:
  image: *cover-art
  bundle:
    - course: *course-name
      subtitle: *oneliner
      description: "**Note: This course is already included in the [Master Embedded Systems](/master-embedded)!**\n\nLearn FreeRTOS kernel by tearing it down to it's bare minimum and doing a port for a new target from scratch. This includes booting the CPU from scratch and placing the code in memory manually. Along the way, learn the internals of how the OS is structured and how it works."
      previewCover: *cover-art
      bestSeller: "yes"
      beginner: "yes"
      intermediate: "yes"
      rating: 4.9
      ratingCount:
      studentsCount: *enrolled
      message: "freertos"
      courseCount:
      emulator: true
      hardware:
      workshops:
      newcontent: true
      creators: ["piyush", "mahmad"]
      lastUpdated: *lastupdated
      language: "English"
      lessons: 27
      length: "~ 6 hr 40 mins"
      files: "1"
      quizzes:
      certificate: "/freeRTOS-101/certificate.png"
      validity: 365 days
      projects: 1
      learning:
        - "Understand FreeRTOS and its role in embedded systems"
        - "Learn the benefits of using FreeRTOS for real-time applications"
        - "Set up development tools and Codespace for FreeRTOS"
        - "Visualize course objectives through a demo walkthrough"
        - "Master the ARM M CPU programmer’s model and essentials"
        - "Boot an ARM M CPU from scratch"
        - "Transition from assembly to C functions in FreeRTOS source"
        - "Troubleshoot function call issues in C"
        - "Locate and utilize FreeRTOS source code and documentation"
        - "Integrate the FreeRTOS kernel into a project"
        - "Fix errors in portmacro.h for platform compatibility"
        - "Configure FreeRTOSConfig.h for project needs"
        - "Enable heap for dynamic memory allocation"
        - "Set the scheduling rate for task execution"
        - "Compile the FreeRTOS kernel successfully"
        - "Run a compiled FreeRTOS binary on a target platform"
        - "Investigate task creation failures"
        - "Debug memory allocation issues using GDB"
        - "Correct boot-up code and memory initialization"
        - "Install and configure exception handlers"
        - "Diagnose and resolve hard faults"
        - "Enable and verify the FreeRTOS scheduler"
      sections:
      - section: "Introduction and Setup"
        id: "intro"
        description: "Introduces FreeRTOS, covering its purpose and importance in embedded systems development. Through a guided demo walkthrough, you will understand the course’s end goals and the tools required. The section concludes with hands-on guidance on setting up a Codespace environment, ensuring a smooth start to FreeRTOS development."
        open: "open"
        chapters:
          - chapter: "What and Why FreeRTOS"
            type: "video"
          - chapter: "Demo walkthrough - End goal and Tools"
            type: "video"
          - chapter: "Codespace Setup"
            type: "video"
      - section: "Booting the ARM M CPU from Scratch"
        id: "setup"
        open: "open"
        description: "This section dives into the fundamentals of the ARM M CPU, exploring its programmer’s model and essential concepts critical for embedded development. Through a practical demo, you will gain hands-on experience in booting the ARM-M CPU from scratch, laying a solid foundation for integrating FreeRTOS on the platform."
        chapters:
          - chapter: "Programmers model and Essentials of ARM M CPU"
            type: "video"
            preview: ""
          - chapter: "Demo - Booting the CPU"
            type: "video"
            preview: ""
      - section: "Exploring FreeRTOS Source"
        id: "explore"
        open: "open"
        description: "This section guides on navigating the FreeRTOS source code, starting with transitioning from assembly code to C functions. You will troubleshoot and resolve issues related to function calls in C, ensuring smooth code execution. Additionally, the section covers how to locate, download, and effectively use FreeRTOS source code and documentation for project development."
        chapters:
          - chapter: "Jumping from Assembly code to function in C files"
            type: "video"
            preview: ""
          - chapter: "Fixing the problem of function calls in C"
            type: "video"
            preview: ""
          - chapter: "Getting the FreeRTOS source code and documentation"
            type: "video"
            preview: "9FGdiaNzKfk"
      - section: "Integrating FreeRTOS Kernel"
        id: "integration"
        open: "open"
        description: "This section focuses on the practical steps to integrate the FreeRTOS kernel into a project. You will learn to identify and resolve errors in portmacro.h, configure FreeRTOSConfig.h for project-specific needs, and enable heap memory for dynamic allocation. The section also covers setting the scheduling rate to control task execution and guides you through achieving a successful kernel compilation for the target platform."
        chapters:
          - chapter: "Starting to Integrate the FreeRTOS-Kernel"
            type: "video"
            preview: ""
          - chapter: "Finding and fixing the portmacro.h errors"
            type: "video"
            preview: "U_DDLbHN8dI"
          - chapter: "Finding and adding the FreeRTOSConfig.h"
            type: "video"
            preview: ""
          - chapter: "Enabling heap for dynamic memory allocation"
            type: "video"
            preview: ""
          - chapter: "Setting the Scheduling Rate"
            type: "video"
            preview: ""
          - chapter: "Getting the Kernel to compile successfully"
            type: "video"
            preview: ""
      - section: "Investigating Runtime Instabilities"
        id: "instabilities"
        open: "open"
        description: "This section equips you with the skills to run a compiled FreeRTOS binary on a target platform and troubleshoot runtime issues. You will investigate why tasks fail to create, using GDB to diagnose memory allocation failures. The section concludes with correcting boot-up code and memory initialization to ensure system stability."
        chapters:
          - chapter: "Running the compiled binary"
            type: "video"
            preview: ""
          - chapter: "Investigating why task is not getting created"
            type: "video"
            preview: ""
          - chapter: "GDB Investigation - Memory Allocation failure"
            type: "video"
            preview: ""
          - chapter: "Correcting the boot-up code and memory init"
            type: "video"
            preview: ""
      - section: "Debugging and Getting the Scheduler to run"
        id: "debug-scheduler"
        open: "open"
        description: "This section focuses on advanced debugging techniques for FreeRTOS. You will learn to install and configure exception handlers to manage system errors effectively. The section guides you through identifying and resolving the causes of hard faults. Finally, you will master the process of enabling and verifying the FreeRTOS scheduler to ensure seamless task execution."
        chapters:
          - chapter: "Installing the Exception Handlers"
            type: "video"
            preview: ""
          - chapter: "Hunting the cause for the Hard Fault"
            type: "video"
            preview: ""
          - chapter: "Getting the Scheduling to work"
            type: "video"
            preview: ""
          - chapter: "SVC Handler leading to Hard Fault"
            type: "pdf"
            preview: ""
      - section: "Fixing errors and Testing on real hardware"
        id: "hardware"
        open: "open"
        description: "This section focuses on bridging the gap between the emulator and the real hardware. You will upload and debug the compiled binary to the real board, connect gdb and confirm the scheduler to be working."
        chapters:
          - chapter: "Correcting the Linker script and reasoning about SVC"
            type: "video"
            preview: ""
          - chapter: "Working with the Hardware, uploading the code"
            type: "video"
            preview: ""
          - chapter: "Loading the code to board and exploring task scheduling"
            type: "video"
            preview: ""
      - section: "Conclusion and Next steps"
        id: "conclusion"
        open: "open"
        description: "As part of this section you will focus on exploring the operation of the freeRTOS scheduler and the various system level components that get it going and how to reverse engineer the mechanics of it. The course ends with a lecture on what to do next on your journey to mastering embedded software development."
        chapters:
          - chapter: "Exploring the Scheduler implementation"
            type: "video"
            preview: ""
          - chapter: "Summary and What to pursue next"
            type: "video"
            preview: ""

      requirements:
        - GitHub account to do the hands-on coding in Codespaces.
        - Interest in learning the underlying details of how the CPU works.
        - Functional internet connection.
      audience:
        - Students in Academia with operating systems as a subject in the course.
        - Those wanting to learn assembly programming.
        - Those interested in the ARM Cortex-M CPU working.
        - Those looking to understand how a scheduler works.
      reviewSectionTitle: "Reviews from the learners"
      reviewSectionDescription: ""
      reviews:
      compare:
        - feature: "Explain the CPU and the boot process."
          us: true
          others: false
        - feature: "Explain the minimum files to enable the FreeRTOS scheduler."
          us: true
          others: false
        - feature: "Explain the porting process."
          us: true
          others: false
        - feature: "Explain the configuration options."
          us: true
          others: false
        - feature: "Dive into the details of the implementation of the tasks."
          us: true
          others: false
        - feature: "Explain how to start the scheduler."
          us: true
          others: false
        - feature: "Explain the details of how to enable the OS for a new target without copy pasting other examples."
          us: true
          others: false
        - feature: "Develop without IDE and automated tools. Enable the port by hand from scratch."
          us: true
          others: false
      faqs:
        - q: "Do I need to know Assembly Language?"
          a: "No. You will learning the required basics (and advance concepts) as part of the course."
          open: "open"
        - q: "Is this course good for beginners?"
          a: "Familiarity is not assumed. Some idea of OS keywords can help."
          open: "open"
        - q: "Why is the course validity 365 days?"
          a: "We need to maintain the servers that host the courses. At the moment we have enough capital to keep the server afloat for another year. We are striving to make this a lifetime access course. As the funds trickle in, we will revisit the validity and might update it for all the enrolled learners. It is however no a promise!"
          open: "open"
        - q: "Do I need a special machine configuration to take this course?"
          a: "No! All you will need is an internet connection and the Chrome browser. The hands-on examples and lab work is based on GitHub codespaces platform."
          open: "open"
        - q: "Why is a GitHub account needed?"
          a: "The Experiments and Labs are based on the GitHub provided Codespaces virtual machine. Codespaces will enable a common work environment for all the learners and avoid the hassle of special setup."
          open: "open"
        - q: "Can I change my email-id post purchase?"
          a: "As much as we'd like to support that, your account will be linked to your email-id post purchase."
          open: "open"
        - q: "What name will be printed on the Certificate?"
          a: "The name you use on the platform will be printed as is on the Certificate when it is generated."
          open: "open"
        - q: "Can I follow the steps on my own PC?"
          a: "Yes for the most part. Better yet would be if you have a Linux machine. We will not support debugs on your personal support."
          open: "open"
        - q: "Is doubt resolution support provided?"
          a: "The courses is self-paced. We do not support Q/A or doubt resolution. The platform provides a way for you to ask questions that other students can respond to."
          open: "open"
        - q: "Why is the course based on emulator?"
          a: "We wanted the learners to be able to experiment without investing into any hardware. Once the learner is comfortable with the material, they can try the experiment on the real hardware."
          open: "open"
---

# What is so special about this course?

There are several courses online that dive into how to use FreeRTOS. This one take a different approach and dives into the internals of FreeRTOS and how to port it from scratch on a new micro-controller. Learning it this way will ensure that you understand the internals of this RTOS and reason better when using it.
