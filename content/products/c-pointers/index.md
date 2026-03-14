---
layout: products

url: /pointers-old

aliases:
- /c-pointers-old/
- /products/c-pointers-old/

title: "Pointers (in C)"
date: "2025-11-08T00:00:00+05:30"
tags:
  - bundle
description: "significance, mechanics and use in design."
thumbnail: "/images/courses/pointers.png"
categories: courses
product: "5-pointers"

define:
  enrolled: &enrolled 760+
  lastupdated: &lastupdated "8 November 2025"

param:
  image: "/images/courses/pointers.png"
  bundle:
    - course: "Pointers (in C)"
      subtitle: "`significance, mechanics and use in design.`"
      description: "**NOTE: This course is already included in the Library Access!**\n\nIn one intense, code-first course you’ll build rock-solid mental models, wield multi-level pointers, function callbacks, void*, and heap safely, then read real kernel source like a pro.\n\nFrom “&” vs “*” to dodging leaks and dangling pointers, leave with the exact pointer super-powers that separate junior coders from firmware ninjas.\n\n`Zero fluff, 100 % hands-on`."
      previewCover: "/images/courses/pointers.png"
      bestSeller: "yes"
      beginner: "yes"
      intermediate: "yes"
      rating: 4.9
      ratingCount: 48
      studentsCount: *enrolled
      message: ""
      courseCount:
      emulator:
      hardware:
      workshops:
      newcontent:
      creators: ["piyush"]
      lastUpdated: *lastupdated
      language: "English"
      lessons: 33
      length: "~ 5 hr 30 mins"
      files: 15
      quizzes:
      certificate: "/pointers/certificate.png"
      validity: 365 days
      projects:
      learning:
        - Develop mental models for visualizing and reasoning about pointers.
        - Learn what a pointer fundamentally is and how to imagine its behavior.
        - Explore the motivations and reasons for using pointers in C programming.
        - Set up an environment for working with pointers in code.
        - Master the syntax for declaring and defining pointers.
        - Grasp the relationship between pointer variables and memory addresses.
        - Understand the roles of the * (dereference) and & (address-of) operators in relation to pointers.
        - Work with multi-level pointers and their applications.
        - Apply multiple * and & operators effectively in code.
        - Differentiate between pointers to pointers and arrays of pointers.
        - Identify similarities and differences between arrays and pointers.
        - Learn about pointers to data and how they reference data with specific types.
        - Use pointers with structures, including the * (dereference), . (dot), and -> (arrow) operators.
        - Perform pointer arithmetic and understand its implications.
        - Comprehend the memory model in relation to pointers and data.
        - Understand function pointers (callbacks) and their purpose.
        - Master the syntax for declaring and using function pointers.
        - Utilize typedef with function pointers for cleaner code.
        - Implement examples like arrays of function pointers.
        - Learn about void pointers and their flexibility.
        - Differentiate between NULL and NULL pointers, including their uses.
        - Examine real-world examples of void pointers in Linux source code.
        - Handle dynamic memory allocation using heap, malloc(), and free().
        - Manage allocation failures and best practices for error handling.
        - Identify and prevent memory leaks in pointer-based code.
        - Recognize and avoid dangling pointers.
        - Understand the risks of double free() and how to prevent them.
        - Avoid pointer manipulation issues and accessing unowned memory.
        - Analyze pointers in open-source baremetal code.
        - Explore pointer usage in FreeRTOS.
        - Study pointer implementations in Linux source code.
      sections:
        - section: "Mental Models, Motivation and Reasoning about pointers"
          id: ""
          description: "You’ll trade confusion for clarity in under an hour. Instead of dry definitions, you’ll lock in a single, vivid mental image that turns every pointer into something you can literally see on a whiteboard or sketch on a napkin. You’ll discover what a pointer truly is (spoiler: it’s not just “a variable holding an address”), why the Linux kernel, FreeRTOS, Zephyr, and every serious RTOS lean on them like oxygen, and the three everyday firmware disasters that disappear once pointers click. By the end, you’ll explain pointers to a five-year-old!"
          open: "open"
          chapters:
            - chapter: "What to Imagine?"
              type: "video"
            - chapter: "What is a pointer?"
              type: "video"
              preview: "_xdDXEuSHHg"
            - chapter: "Why pointers?"
              type: "video"
        - section: "Pointers - Syntax and Code"
          id: ""
          description: "You’ll fire up a real dev environment in five minutes and start writing pointer code that compiles and runs on your laptop. You’ll declare your first pointer, watch the & operator spit out raw memory addresses, and use * to reach inside that address like a surgeon. By the time you finish, the difference between a pointer variable and the memory it guards will feel as natural as breathing, and you’ll never again mix up “value” versus “address” in your sleep. No slides, no theory—just you, a terminal, and the exact four lines of code that make every kernel tick."
          open: "open"
          chapters:
          - chapter: "Environment Setup"
            type: "video"
          - chapter: "Declaring|Defining a Pointer"
            type: "video"
          - chapter: "Pointer Variable and Address"
            type: "video"
          - chapter: "* and & in relation to pointer variable"
            type: "video"
        - section: "Multi-level Pointers"
          id: ""
          description: "You’ll level-up from baby steps to ninja territory in one adrenaline-fueled sprint. You’ll chain ** together until you’re juggling triple-star pointers like a circus pro, then watch & peel them back layer by layer. You’ll see why an array name is secretly a pointer, where the two diverge, and how to build an array of pointers that makes qsort() and Linux device tables look trivial. By the final keystroke, you’ll wield “many *s and many &s” without blinking, turn pointer-to-pointer into your secret weapon, and laugh at code that once looked like hieroglyphics, ready to debug any kernel structure on sight."
          open: "open"
          chapters:
          - chapter: "Use of * and &"
            type: "video"
          - chapter: "Array and Pointers - Similarity and differences"
            type: "video"
          - chapter: "Many *s and Many &s"
            type: "video"
          - chapter: "Pointer to pointer"
            type: "video"
          - chapter: "Array of pointers"
            type: "video"
          - chapter: "Different types of Pointers"
            type: "video"
        - section: "Pointer to Data"
          id: ""
          description: "You’ll step inside actual RAM and treat memory like clay in your hands. You’ll point to ints, floats, and custom structs with surgical precision, then swap the clumsy (*p).field for the sleek p->field arrow that every Linux driver lives by. You’ll stride through arrays with p+1, discover why char* walks one byte at a time while int* leaps four, and sketch the exact memory map that turns a flat address into a living struct. By the end, you’ll read any kernel data structure blindfolded, fix off-by-one bugs before breakfast, and never again wonder “where exactly does this pointer land?”"
          open: "open"
          chapters:
          - chapter: "Pointing to data with a Data type"
            type: "video"
          - chapter: "Pointer to a struct, *, . and ->"
            type: "video"
          - chapter: "Pointer Arithmetic"
            type: "video"
          - chapter: "Memory model and pointer to data"
            type: "video"
        - section: "Pointer to Code - Function Pointers or Callbacks"
          id: ""
          description: "You’ll discover exactly what a function pointer is, master its complete syntax, and clean it up with a single typedef. You’ll then build and run a real function-pointer array that stores multiple functions and calls any one by index."
          open: "open"
          chapters:
          - chapter: "What is a function pointer?"
            type: "video"
            preview: "ZYDY2B50pws"
          - chapter: "Function pointers syntax"
            type: "video"
          - chapter: "typedef and function pointers"
            type: "video"
          - chapter: "Example - function pointer array"
            type: "video"
        - section: "Void Pointers"
          id: ""
          description: "You’ll master the shapeshifting void*: what it is, why it exists, and how to wield it safely. You’ll see NULL in action, learn the exact difference between a null pointer and NULL itself, and then dive straight into real Linux kernel code where void* carries structs, buffers, and callbacks across subsystems."
          open: "open"
          chapters:
          - chapter: "What is a void pointer?"
            type: "video"
          - chapter: "What is NULL and NULL pointer?"
            type: "video"
          - chapter: "void pointers in - Linux source code"
            type: "video"
        - section: "Pointers, Dynamic Allocation and Problems"
          id: ""
          description: "You’ll master the heap with malloc() and free(), catch allocation failures the moment they happen, hunt down every byte lost to memory leaks, rescue code from dangling pointers, stop double-free crashes cold, and lock out pointer manipulation that wanders into unowned memory."
          open: "open"
          chapters:
          - chapter: "heap/ malloc() and free()"
            type: "video"
          - chapter: "Allocation failure"
            type: "video"
          - chapter: "Memory Leak"
            type: "video"
          - chapter: "Dangling Pointer"
            type: "video"
          - chapter: "Double free()"
            type: "video"
          - chapter: "pointer manipulation and unowned memory"
            type: "video"
        - section: "Open Source Code and Pointers"
          id: ""
          description: "You will examine pointers in Baremetal Code, trace their use in FreeRTOS, and study how they work in Linux."
          open: "open"
          chapters:
          - chapter: "Baremetal Code"
            type: "video"
          - chapter: "FreeRTOS"
            type: "video"
          - chapter: "Linux"
            type: "video"
      requirements:
        - GitHub account to do the hands-on coding in Codespaces.
        - Some familiarity with the C programming language.
        - Interest in mastering the concept of Pointers.
      audience:
        - Students in Academia with C as a subject in the course.
        - Those using the C language for development (Embedded Systems Engineers, System Software Engineers etc).
        - Embedded systems or Firmware Engineers.
        - Anyone seeking gain system level insights.
        - Anyone curious to learn the underlying details of Systems and how to program it using pointers.
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
        - feature: "Explain what pointer in C is."
          us: true
          others: true
        - feature: "Code development without IDE, like how the professionals do it."
          us: true
          others: false
        - feature: "Decomposition of code into Assembly to understand the CPU-Memory interactions."
          us: true
          others: false
        - feature: "Mental models to aid thinking and reasoning."
          us: true
          others: false
        - feature: "A Bottom-Up Approach with the tinge of answering the `Whys`."
          us: true
          others: false
        - feature: "Real and applicable Case study and programming projects"
          us: true
          others: false
        - feature: "Teach with insights at the CPU level."
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

---

# The Design and Deliberation

I am a big believer of mental models and visualisations when it comes to learning technical concepts. This course is deliberately heavy on insight and frameworks of thinking about pointers.

**Pointers** in C is a straight forward concept but it has earned a reputation for being hard to understand. In my opinion, the problem is - most of those who try and learn pointers don't understand how and what to imagine and reason based off of.

From the very first lecture, you'll notice that I explain key concepts with visualisation and mental models along with a hands on experiment to prove the point. The course is loaded with insights that will empower you to your pointers like a pro!
