---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/resume.pdf
    design:
      css_class: dark
      background:
        color: slategray
        image:
          # Add your image background to `assets/media/`.
         
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: markdown
    content:
      title: '📚 My Research'
      subtitle: ''
      text: |-
        Use this area to speak to your mission. I'm a research scientist in the Moonshot team at DeepMind. I blog about machine learning, deep learning, and moonshots.

        I apply a range of qualitative and quantitative methods to comprehensively investigate the role of science and technology in the economy.
        
        Please reach out to collaborate 😃
    design:
      columns: '1'
  
   
    content:
      title: ''
      text: |-
      
       <h1>What I Do</h1>

       <h3>Web Development</h3>
        I design and develop responsive, user-friendly websites using technologies like HTML, CSS, JavaScript, and frameworks like React. My goal is to create seamless digital experiences that resonate with users.<br>



        <h3>IoT and Robotics</h3>
        With hands-on experience in Arduino, ESP boards, and various sensors, I specialize in crafting smart systems and automation solutions. From concept to implementation, I enjoy tackling challenges that connect the physical and digital worlds.<br>

        <h3>My Mission</h3>
        I’m committed to leveraging technology to solve real-world problems and improve everyday life. My dream is to contribute to a smarter, connected future by blending software, hardware, and innovation.





      button:
        text: Get Started
        url: https://hugoblox.com/templates/
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-700"
        css_style: ""
---
