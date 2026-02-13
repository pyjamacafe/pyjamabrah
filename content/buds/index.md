---
type: pitch
title: "Budding Minds"
description: "Nurturing the young buds."
thumbnail: "/images/buds/hero.jpg"

url: /buds

# default CTA
default_cta: &defaults
  - cta:
    link: "https://courses.pyjamabrah.com/web/checkout/6982b85e4496ead2c9979031?purchaseNow=true&couponcode=EARLYBUDS"
    text: "Join the Course"
    primary: true

# Add a Sticky Footer
sticky:
  discount:
    code: "EARLYBUDS"
    percent: "40%"
  ctas: *defaults

sections:
  - section:
    - details:
        type: "full"
        title: "The Story of Money"
        subtitle: "Through the financial adventures of Narayanswamy and his Son..."
    - details:
        type: "break"
    - details:
        type: "half"
        img2: "/images/buds/hero.jpg"
    - details:
        type: "half"
        ctas: *defaults
        title: "Backstory"
        sequence:
          - "Narayanswamy is a hard worker."
          - "He doesn't understand money and it's nature. As a result, life is difficult."
          - "Over time, he gathers the courage to venture into the wild and understand everything about money and how to manage it."
          - "At the end of it all, he has a Burger Shop and life is great."
        posttexts:
          - you can be an onlooker and even an active participant in guiding Narayanswamy ...
  - section:
    - details:
        type: "full"
        title: "Teaser"
        subtitle: "You may have a dream, but unless you plan and act..."
        videoPaused: "https://raw.githubusercontent.com/pyjamacafe/cache/master/buds/story.webm"
        ctas: *defaults
  - section:
    - details:
        type: "half"
        title: "The learnings?"
        subtitle: ""
        sequence:
          - "Get introduced to the world on money through an engaging, relatable and humorous story ('whiteboard sketch' style)."
          - "Simplifies complex ideas, transform dry financial topics like banking, credit, budgeting and currency into engaging visual stories."
          - "See how money works in the real world, making financial literacy feel like a fun discovery rather than a classroom chore."
          - "The assignments at end of the each module will make you think analytically and challenge the understanding."
        ctas: *defaults
    - details:
        type: "half"
        img2: "/images/buds/hero-2.jpg"
  - section:
    - details:
        type: "full"
        title: "How to access the Course?"
        texts:
          - "Browser, iOS or Android - we got you covered!"
        ctas:
          - cta:
            link: "https://apps.apple.com/in/app/pyjama-brah/id6746846358"
            text: "Download iOS App"
          - cta:
            link: "https://play.google.com/store/apps/details?id=com.tagmango.tmpyjamabrah&pcampaignid=web_share"
            text: "Download Android App"
          - cta:
            link: "https://courses.pyjamacafe.com"
            text: "Access on the Web"
  - section:
    - details:
        type: "full"
        title: "The Creators"
        subtitle: "Created by Balaji. Cheer-leading by Piyush."
        people:
          - ind:
            name: "Balaji Natakala"
            img: "/images/authors/bn.png"
            designation: "Ex-Firmware Architect/SMTS"
            orgs: "Ex-Intel, Ex-ST-Ericsson, Ex-NXP"
            links:
              linkedin: "https://www.linkedin.com/in/balajinatakala/"
            texts:
              - "Firmware Architect and Technical Leader dedicated to bridging the gap between complex hardware design and seamless software execution. Over 12-year tenure at Intel, pivoted from mastering GNSS stacks for global mobile OEMs to architecting next-generation FPGA configuration and secured boot subsystems."
              - "Expertise lies in HW-SW co-design, led the development of RISC-V based submodules and high-speed DMA engines. Beyond technical architecture, Balaji is passionate about organizational growth—having scaled teams from the ground up and mentored the next generation of technical leads."
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
  - section:
    - details:
        type: "half"
        img2: "/images/buds/vision.jpg"
    - details:
        type: "half"
        title: "Our Vision"
        subtitle: "why a course on money?"
        list:
          - "Our Vision Our journey begins with financial literacy for children, but our ultimate goal is far broader: `we aim to cultivate critical thinking in the next generation`."
          - "By addressing essential topics that are rarely covered in traditional school curriculum we are building curiosity."
          - "This vision is based in our existing ecosystem, which already offers deep-dive embedded systems courses tailored for graduates and young professionals."
        posttexts:
          - "Watch out this space for more of learning tracks around computation and electronics crafted for kids of all ages."
        ctas:
        - cta:
          link: "/embedded"
          text: "Explore Embedded"
        - cta:
          link: "/soanpapdi"
          text: "Explore Digital Logic"
---
