---
layout: products

url: /c-old

aliases:
- /c-old/
- /c-language-old/
- /products/c-language/

title: "The C Language"
date: "2025-01-08T17:48:22+05:30"
tags:
  - bundle
description: "The language, the tools and the programming techniques."
thumbnail: "/c-old/cover.png"
categories: courses
product: "1-c"

define:
  enrolled: &enrolled 2000+
  lastupdated: &lastupdated "10 Jan 2026"

param:
  image: "/c/c-course.png"
  bundle:
    - course: "The C Language"
      subtitle: "`the language, the tools and the programming techniques`"
      description: "This course dives into the practical applications of the C language, emphasizing hands-on learning to solidify key concepts. Delivered in an engaging and unconventional style, the lessons go beyond theory, equipping you with the skills to apply C programming in real-world scenarios.\n\n By the end of the course, you’ll feel confident in your mastery of the C language, adept at using it alongside the tools and utilities professional C programmers rely on daily."
      previewCover: "/c/c-course.png"
      # previewVideo: "https://github.com/pyjamabrah/preview-videos/raw/refs/heads/main/C%20to%20Assembly.mp4"
      bestSeller: "yes"
      beginner: "yes"
      intermediate: "yes"
      rating: 4.9
      ratingCount: 44
      studentsCount: *enrolled
      message: "c"
      courseCount:
      emulator: true
      hardware:
      workshops:
      newcontent: true
      creators: ["piyush"]
      lastUpdated: *lastupdated
      language: "English"
      lessons: 91
      length: "~ >26 hr"
      files: 12
      quizzes:
      certificate: "/c/certificate.png"
      validity: 365 days
      projects: 3
      learning:
        - Mental models to use when coding in C.
        - What is machine code.
        - Instruction Set Architecture and Assembly coding.
        - GNU toolchain utilities/programs (gcc, as, ld wtc).
        - GNU Debugger (GDB).
        - Automation using Makefiles.
        - How text is converted to 0s and 1s.
        - Syntax and Structure of C Programs.
        - Data types, variables, declaration/definition.
        - Arrays, Strings and Pointers.
        - Structs and Union.
        - arithmetic, logical, relational operators in C.
        - Functions and Modules/Libraries in C.
        - Pointers and how to use them in Design.
        - Types of pointers.
        - Bit fields and Bit manipulation.
        - Const and volatile type qualifiers
        - Controlling placement of code and data in memory.
        - Loops - for, while, do while.
        - Branching - if, if-else, switch, goto.
        - Mixing Assembly and C and the need for it.
        - Booting RISC-V CPU from scratch.
        - Cross compiling and what it means.
        - memory management - Stack vs. Heap.
        - Dynamic memory allocation (malloc, calloc, realloc, free).
        - Compiler optimizations (-O1, -O2, -O3, -Os, -Ofast).
      sections:
        - section: "C Language Tour"
          id: "c-tour"
          description: ""
          open: "open"
          chapters:
          - chapter: "Roadmap and Mindset"
            type: "video"
          - chapter: "Sandbox Environment and Basic C Program"
            type: "video"
          - chapter: "Keep an Eye on Functions, Pointers and Structs"
            type: "video"
          - chapter: "Example of the RAW power - Functions, Struct and Pointers"
            preview: "1-GXQFRaHZc"
            type: "video"
        - section: "Mental Models to brain tattoo"
          id: "mental-model"
          description: ""
          open: "open"
          chapters:
          - chapter: "Mental Model of the System"
            type: "video"
          - chapter: "The mental model of the CPU"
            type: "video"
          - chapter: "The mental model of the Memory"
            type: "video"
        - section: "From Text to Binary"
          id: "text-2-binary"
          description: ""
          open: "open"
          chapters:
          - chapter: "Instruction Encoding and the rv32i ISA"
            type: "video"
          - chapter: "A tour of Toolchain, QEMU, GDB"
            type: "video"
          - chapter: "Demo - assembly to binary, QEMU and GDB"
            type: "video"
          - chapter: "Instruction Encoder Decoder, Makefile and GDB Dashboard"
            type: "video"
        - section: "Dwelling in the World of Assembly"
          id: "assembly-101"
          description: ""
          open: "open"
          chapters:
          - chapter: "Anatomy of Assembly Program, writing code, debugging in GDB"
            type: "video"
          - chapter: "Decomposing C to Assembly and the relation"
            preview: "2eAv_b4OrAE"
            type: "video"
        - section: "C Keywords - Data Types"
          id: "c-datatypes"
          description: ""
          open: "open"
          chapters:
          - chapter: "Getting CPU from assembly to jump to C program"
            type: "video"
          - chapter: "Introducing the C Keywords"
            type: "video"
          - chapter: "Data types, Variables and Integers"
            type: "video"
          - chapter: "Datatypes - float and double"
            type: "video"
          - chapter: "Exploring sizes of data types and location in memory"
            type: "video"
          - chapter: "How integers are stored - 2s complement"
            type: "video"
          - chapter: "floating point number encoding and few examples"
            type: "video"
          - chapter: "more floating point - float and double"
            type: "video"
          - chapter: "signed and unsigned"
            type: "video"
          - chapter: "const and volatile"
            type: "video"
          - chapter: "demo - const and volatile"
            type: "video"
          - chapter: "void, c standard and gnu C manual"
            type: "video"
          - chapter: "typedef and sizeof"
            type: "video"
          - chapter: "structs and unions"
            type: "video"
          - chapter: "enums as named numbers"
            type: "video"
        - section: "C Keywords - Branching and Looping"
          id: "c-keywords"
          description: ""
          open: "open"
          chapters:
          - chapter: "if, else, switch, case, default, do, while, for, continue and break"
            type: "video"
          - chapter: "goto and return"
            type: "video"
          - chapter: "Demo - if, else if and else effects at assembly level"
            type: "video"
          - chapter: "Demo - switch case and effects at assembly level"
            type: "video"
          - chapter: "Demo - loops - for, do, while, continue and effects at assembly level"
            type: "video"
          - chapter: "Demo - goto and jumps across functions"
            type: "video"
          - chapter: "auto, register, extern and static"
            type: "video"
          - chapter: "Demo - auto keyword7"
            type: "video"
          - chapter: "Demo - register keyword"
            type: "video"
          - chapter: "Demo - extern keyword"
            type: "video"
          - chapter: "Demo - static keyword"
            type: "video"
        - section: "Variables and Functions"
          id: "variables-and-functions"
          description: ""
          open: "open"
          chapters:
          - chapter: "Introduction to Variables and Functions"
            type: "video"
          - chapter: "definition vs declaration"
            type: "video"
          - chapter: "Demo - variable and function names"
            type: "video"
          - chapter: "Arithmetic operations and pitfalls"
            type: "video"
        - section: "Project-1: Calculator in C"
          id: "project-1"
          description: ""
          open: "open"
          chapters:
          - chapter: "Problem statement"
            type: "pdf"
          - chapter: "Problem statement walkthrough"
            type: "video"
          - chapter: "Setup, variables and I/O"
            type: "video"
          - chapter: "Using conditions, switch and loops"
            type: "video"
          - chapter: "debugging scanf issue and cleaning up the code"
            type: "video"
          - chapter: "guarding against bad inputs and concluding the project"
            type: "video"
        - section: "Strings, Array and Pointers"
          id: "strings"
          description: ""
          open: "open"
          chapters:
          - chapter: "Strings and concept of array and pointers"
            type: "video"
          - chapter: "Defining and Assigning Arrays"
            type: "video"
          - chapter: "Arrays and out of bound access"
            type: "video"
          - chapter: "Strings and Character arrays"
            type: "video"
          - chapter: "Introduction to the concept of pointers"
            type: "video"
          - chapter: "Syntax related to Pointers"
            type: "video"
          - chapter: "Demo - introduction to working with data pointers"
            type: "video"
          - chapter: "Detour - Endianness"
            type: "video"
          - chapter: "Demo - Difference between array and pointers"
            type: "video"
        - section: "Project-2: Generating Digital Audio"
          id: "project-2"
          description: ""
          open: "open"
          chapters:
          - chapter: "Generating Digital Audio - walkthrough"
            type: "video"
          - chapter: "Math concepts and sampling"
            type: "video"
          - chapter: "Generating samples and file operations"
            type: "video"
          - chapter: "Demo - Playing the Digital Audio"
            type: "video"
        - section: "User Defined Data types"
          id: "user-data-type"
          description: ""
          open: "open"
          chapters:
          - chapter: "Revisiting types of data types"
            type: "video"
          - chapter: "Structures - Sneak peak"
            type: "video"
          - chapter: "Anatomy of Struct and examples"
            type: "video"
          - chapter: "Demo - structs"
            type: "video"
          - chapter: "unions and how they defer from struct"
            type: "video"
          - chapter: "Demo - union"
            type: "video"
          - chapter: "Enums and fun experiments"
            type: "video"
          - chapter: "Enum and Scope"
            type: "video"
        - section: "Project-3: Embedded Sensor Management"
          id: "project-3"
          description: ""
          open: "open"
          chapters:
          - chapter: "Problem Statement"
            type: "pdf"
          - chapter: "Introduction and Walkthrough"
            type: "video"
          - chapter: "Converting specification to data structure"
            type: "video"
          - chapter: "The case for union and saving memory"
            type: "video"
          - chapter: "Accessing elements with nested union and structs"
            type: "video"
        - section: "Operators"
          id: "operators"
          description: ""
          open: "open"
          chapters:
          - chapter: "Types of operators"
            type: "video"
          - chapter: "Arithmetic Operators"
            type: "video"
          - chapter: "Arithmetic Operators at Assembly Level"
            type: "video"
          - chapter: "Relational Operators"
            type: "video"
          - chapter: "Relational Operators - Assembly Level decomposition"
            type: "video"
          - chapter: "Use of Relational Operators"
            type: "video"
          - chapter: "Logical Operators"
            type: "video"
          - chapter: "Logical Operator - Assembly decomposition"
            type: "video"
        - section: "Bitwise Operators"
          id: "bitwise"
          description: ""
          open: "open"
          chapters:
          - chapter: "What are bitwise operations and the types"
            type: "video"
          - chapter: "Shift Operations - Left, Logical and Arithmetic Right"
            type: "video"
          - chapter: "The Bitwise NOT operation"
            type: "video"
          - chapter: "Understanding using printf"
            type: "video"
          - chapter: "Understanding the Assembly View"
            type: "video"
          - chapter: "Exploring the Shift operations"
            type: "video"
          - chapter: "Assembly view of Shift operation"
            type: "video"
        - section: "more lectures being recorded"
          id: ""
          description: ""
          open: "open"
          chapters:
          - chapter: "more being uploaded..."
            type: ""

      requirements:
        - GitHub account to do the hands-on coding in Codespaces.
        - Interest in the lower level working of the system.
        - Some exposure to Digital systems is good (but not strictly required).
        - Basic understanding of number systems, logic gates, bits and bytes is good to have (but not strictly required).
      audience:
        - Students in Academia with C as a subject in the course.
        - Those using the C language for development (Embedded Systems Engineers, System Software Engineers etc).
        - Electrical/Electronics Engineers working on hardware programming.
        - Anyone seeking gain system level insights.
        - Anyone curious to learn the underlying details of Systems and how to program it using C.
      reviewSectionTitle: "Reviews from the learners"
      reviewSectionDescription: "Because the course is brand new, we released some lectures on YouTube to get early feedback, and it has been a banger! You will not regret taking this course..."
      reviews:
        - reviewer: "Jim Nnamdi Samuel"
          date: "15/05/2025"
          rating: 5
          review: "very insightful"
        - reviewer: "Pulkit Singla"
          rating: 5
          review: "Fantastic explanation of the basic concepts. This course has helped me a lot in understanding the basics that I struggled with before."
          date: "21/05/2025"
        - reviewer: "Aditya Shidlyali"
          review: "Even though I know C language, after going through this series of lectures I was like wow, just amazing. Thank you so much Piyush and team making me learning embedded systems in joyful way and working on these kind of world was one of my dream and thanks for making me learning these things."
          date: "16/06/2025"
          rating: 5
      compare:
        - feature: "Basic C Syntax."
          us: true
          others: true
        - feature: "Data types, strings, pointers, operators and other basics."
          us: true
          others: true
        - feature: "Code development without IDE, like how the professionals do it."
          us: true
          others: false
        - feature: "Decomposition of C code into Assembly and conversion to machine code."
          us: true
          others: false
        - feature: "Mental models to aid thinking and reasoning."
          us: true
          others: false
        - feature: "A Bottom-Up Approach with the tinge of answering the `Whys`."
          us: true
          others: false
        - feature: "Mixing C with Assembly"
          us: true
          others: false
        - feature: "Real and applicable Case study and programming projects"
          us: true
          others: false
        - feature: "Project-Based Learning - Develop and learn with a simple yet effective project like C shell, memory allocator, etc."
          us: true
          others: false
        - feature: "Teach with insights at the CPU level."
          us: true
          others: false
        - feature: "Cover Assembly Language and Machine code."
          us: true
          others: false
        - feature: "Cover the toolchain utilities like compiler, assembler, linker and debug tools like GDB?"
          us: true
          others: false
      faqs:
        - q: "What is the difference between this course (paid) and the videos on YouTube?"
          a: "Only few initial videos are put on YouTube. The Full course has many more videos and is a paid offering. Learners will also have access to the notes, source code files and other resources."
          open: "open"
        - q: "Is this course good for beginners?"
          a: "Yes! The course is taught as if the learner has no idea about the C programming language."
          open: "open"
        - q: "Why is the course validity 365 days?"
          a: "We need to maintain the servers that host the courses. At the moment we have enough capital to keep the server afloat for another until. We are striving to make this a lifetime access course. As the funds trickle in, we will revisit the validity and might update it for all the enrolled learners."
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
          a: "Yes for the most part. Better yet would be if you have a linux machine."
          open: "open"
        - q: "How will the open-source contribution work?"
          a: "We will host few github repos under pyjamabrah with the skeleton code and details asks (in comments) about the subsequent tasks. You can add the code (with your details in the comment if you'd want), create PR (pull-request) and submit. We will review and merge your PR into main."
          open: "open"
        - q: "Will this course be added to `Firmware Engineer's Arsenal`?"
          a: "No! This is a separate offering and unrelated to my previous work at inpyjama.com. pyjamabrah is exclusively run by me and independent of continuous collaboration with my team."
          open: "open"
---

# The Design and Deliberation

The internet is flooded with coding courses—yet none rival this. For over a decade, C has been my daily driver at work. Unlike kernel developers leaning on abstractions, I’ve wielded C in its purest, most raw form—programming CPUs from scratch, without the crutch of standard libraries. This course hands you that same unfiltered power. By the end, you won’t just know C—you’ll command it like a seasoned pro, bending it to your will in ways most developers never dream of.

Here’s the truth: **C’s mastery runs deeper than most realize**. The general public and students rarely glimpse its full scope from the sidelines. I’ve lived it, and now I’m pulling back the curtain for you.

