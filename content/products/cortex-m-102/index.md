---
layout: products

url: /cortex-m-102

aliases:
- /m-102/
- /arm-m-102/

define:
  course-name: &course-name "Scheduler Design on ARM Cortex-M"
  enrolled: &enrolled 2000+
  lastupdated: &lastupdated "3 October 2025"
  cover-art: &cover-art "/images/courses/cortex-m-102.jpg"

title: *course-name
date: "2025-01-08T17:48:22+05:30"
tags:
  - bundle
description: "Learn arm cortex-m controller assembly programming"
thumbnail: *cover-art
categories: courses
product: "3-cortex-m-102"

param:
  image: *cover-art
  bundle:
    - course: *course-name
      subtitle: "`Learn arm cortex-m controller assembly programming`"
      description: "**Note: This course is already included in the [Library Access](/library)!**\n\nLearn the assembly programming for ARM Cortex-M CPUs by writing a scheduler from scratch, without using any IDE, SDK or boiler plate code. A scheduler is at the heart of every operating system.\n\n By writing one from scratch, not only will you learn how to write assembly code, but also how the CPU works and, how a single CPU can run more than one process. As part of this course, the goal is to make a single CPU run three infinite `while(1){}` loops!"
      previewCover: *cover-art
      bestSeller: "yes"
      beginner: "yes"
      intermediate: "yes"
      rating: 5
      ratingCount:
      studentsCount: *enrolled
      message: "cortex-m-102"
      courseCount:
      emulator: true
      hardware:
      workshops:
      newcontent: true
      creators: ["piyush"]
      lastUpdated: *lastupdated
      language: "English"
      lessons: 24
      length: "~ 5 hr"
      files: 3
      quizzes:
      certificate: "/cortex-m-102/certificate.png"
      validity: 365 days
      projects: 1
      learning:
        - Understand ARM Cortex-M CPU Architecture
        - Mental Model of CPU and Systems
        - Programmer’s Model and NVIC
        - Privilege Levels and Operating Modes
        - CPU Boot-Up Process
        - Exception Handling
        - Writing Assembly Code
        - Startup Assembly Program
        - Instruction Sets and Encoding
        - Anatomy of Assembly Files
        - Stack Manipulation
        - Scheduler Theory
        - Task Anatomy
        - Context Switching and Scheduling
        - Exception Entry/Exit and SysTick Timer
        - Hands-On Scheduler Implementation
        - Programming the SysTick timer and verifying exception handling.
        - Saving and restoring CPU context during task switches.
        - Setting up tasks and their stacks for round-robin scheduling.
        - Achieving round-robin scheduling to switch between processes.
        - Running Multiple Processes
        - Key Considerations for Scheduling
        - Comparison with FreeRTOS
        - Debugging using GDB
      sections:
      - section: "Environment Setup"
        id: "setup"
        description: "The courses uses the QEMU emulator for a real hardware board (the experiments should also run on real hardware). To ensure that everyone has the same setup and doesn't get tangled in the setup issues - we use the GitHub Codespaces instance running a virtual machine configuration we defined. This section guides through the steps of accessing it."
        open: open
        chapters:
        - chapter: "End Goal"
          type: "video"
        - chapter: "Environment Setup"
          type: "video"
      - section: "How the ARM M-class CPUs Work"
        id: "cpu-working"
        description: "This section provides a comprehensive introduction to the core concepts of ARM Cortex-M CPUs, laying the foundation for understanding their architecture and operation. Explore the mental model of the CPU, systems, and the Cortex-M controller, gaining insight into how these components interact."
        open: open
        chapters:
        - chapter: "Mental Model of the CPU, Systems and the Cortex M Controller"
          type: "video"
        - chapter: "From bit to the Programmers model and NVIC"
          type: "video"
        - chapter: "Various ARM Architecture and CPUs - M0, M3, M23 etc."
          type: "video"
        - chapter: "Programmers model for the M Class CPUs"
          type: "video"
        - chapter: "Privilege and Modes of operation"
          type: "video"
        - chapter: "Boot up process"
          type: "video"
        - chapter: "Exception Handling and Register Save/Restore"
          type: "video"
      - section: "Assembly Programming"
        id: "assembly"
        description: "Introduces the essentials of assembly programming for ARM Cortex-M CPUs, focusing on practical implementation. Start by exploring the processor boot-up process and writing their first assembly program, gaining hands-on experience with the Cortex-M environment. The section delves into the structure of instructions, their encoding, and how to analyze binary dumps to understand the low-level representation of code. Examine the anatomy of an assembly file, learning its components and organization. Master stack manipulation instructions, understanding their critical role in managing data and CPU context. "
        open: open
        chapters:
        - chapter: "Booting the Processor and First Assembly Program"
          preview: "aEE4bK-HnHg"
          type: "video"
        - chapter: "Instructions, Encoding and binary dump"
          type: "video"
        - chapter: "Anatomy of assembly file"
          type: "video"
        - chapter: "Cortex m3 instructions and experiments"
          type: "video"
        - chapter: "Stack manipulation instructions"
          type: "video"
      - section: "Implementing the Scheduler - Theory"
        id: "theory"
        description: "Covers the theoretical foundations of implementing a scheduler on ARM Cortex-M CPUs, enabling multitasking on a single processor. Explore how a single CPU can run multiple processes, uncovering the principles behind concurrent task execution. Covers the anatomy of a task, detailing its structure and role within a scheduler. Discover the critical techniques for context switching and scheduling, including the `trick` that facilitates seamless task transitions."
        open: open
        chapters:
        - chapter: "How can Single CPU run multiple processes?"
          type: "video"
        - chapter: "Anatomy of a Task"
          type: "video"
        - chapter: "Trick to Context Switching and Scheduling"
          type: "video"
        - chapter: "Exception Entry, Exit and SysTick timer"
          type: "video"
      - section: "Implementing the Scheduler - Hands on"
        id: "implementation"
        description: "Practical implementation of a scheduler. Program the SysTick timer and verify its associated exception handling to ensure accurate timing for task scheduling. Covers techniques for saving and restoring CPU context, a critical step for seamless task switching. Set up tasks and their respective stacks, configuring the system to enable round-robin scheduling. Through hands-on exercises, implement round-robin scheduling and achieve process switching."
        open: open
        chapters:
        - chapter: "Programming SysTick and confirming the exception"
          type: "video"
        - chapter: "saving and restoring CPU context"
          type: "video"
        - chapter: "Setting up the tasks and the stack and trying to round robin"
          type: "video"
        - chapter: "Round robin and switching between processes"
          type: "video"
      - section: "Conclusion"
        id: "conclusion"
        description: "Final thoughts and next steps."
        open: open
        chapters:
        - chapter: "Things to be mindful of"
          type: "video"
        - chapter: "FreeRTOS - the struggle to get to context switching"
          type: "video"

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
        - reviewer: "Ashish Kumar Verma"
          date: 18/08/2025
          rating: 5
          review: "Perfectly what i need to start with freertos , very good structured course."
        - reviewer: "Prajwal"
          date: 14/09/2025
          rating: 5
          review: "Nicely explained, Thank you for your support."
        - reviewer: "Davidkumar P"
          rating: 5
          review: "Very Useful.Keep doing this we always supports. Here I learned M-Class CPU registers working and scheduler Working Nature and how involved is interrupt and Very great course i recently studied in ARM.Thank you for Your Information!"
          date: 05/07/2025
        - reviewer: "RAM AXAYKUMAR"
          review: "amazing content to i able to understand to how to cpu is actually wotk"
          rating: 5
          date: 11/07/2025
      compare:
        - feature: "Use abstractions and be top level."
          us: false
          others: true
        - feature: "Superficial and hand wavy explanation."
          us: false
          others: true
        - feature: "Explain how the CPU works."
          us: true
          others: false
        - feature: "Details of how the CPU boots."
          us: true
          others: false
        - feature: "Explain how assembly code is written and converted to binary."
          us: true
          others: false
        - feature: "Hand code a scheduler."
          us: true
          others: false
      faqs:
        - q: "Do I need to know Assembly Language?"
          a: "No. You will learning the required basics (and advance concepts) as part of the course."
          open: "open"
        - q: "Is this course good for beginners?"
          a: "Yes! The course is taught as if the learner has no idea about ARM Cortex-M CPUs, Assembly and OS."
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
---

# What is so special about this course?

Every complex embedded systems solution uses an OS/RTOS for implementing the state machine. An OS at its core implements a task scheduler (among other things). Not everyone understands how it works.

The design of this course is deliberate in the sense that - in an attempt to implementing the "Scheduler" you will learn the CPU operations, how assembly programs are written and how scheduling works.

Completing this course should set you up to understand & work efficiently with an operating system (like the FreeRTOS).
