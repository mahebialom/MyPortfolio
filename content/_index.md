---
# Leave the homepage title empty to use the site title
title: ""
date: 2024-11-11
type: landing

design:
  # Default section spacing
  spacing: "4rem"
  padding: ["4rem", "4rem", "4rem", "4rem"]  # Top and bottom padding 0, left and right padding 2rem

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: 
      text: ""
      # Show a call-to-action button under your biography? (optional)
    design:
      columns: "1"
      css_class: gray
      background: 
        color: 
        image: 
          # assets/media/debashis.jpg
          # Add your image background to `assets/media/`.
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false

  - block: markdown
    content:
      title: "🌱 About Me"
      subtitle: ""
      text: |-
        Hello! I'm **Debashis Dhali**, a Computer Science and Engineering student at Jahangirnagar University with a strong passion for becoming a full-stack developer. Currently, I'm in my third year, dedicating myself to mastering both frontend and backend development. My journey began with HTML, CSS, and JavaScript, and now I'm diving deeper into **React.js** and **IoT** development.

        My recent projects include automating systems, building IoT solutions to enhance agriculture and water monitoring, and tackling problem-solving challenges on platforms like Codeforces. I love exploring new technologies and am always looking for innovative ways to apply my skills.
        
        I’d love to connect and collaborate on impactful projects!
    design:
      columns: "1"


  - block: collection
    id: blog
    content:
      title: Blog Posts
      subtitle: ""
      text: "**Title: My Tech Journey: From Development to IoT Solutions**

       Hi, I’m Debashis Dhali, a 23-year-old Computer Science student at Jahangirnagar University. Starting with frontend development—HTML, CSS, JavaScript, and React—my goal is to become a full-stack developer, hopefully at Google. To get there, I’m following a structured roadmap to deepen my skills across all aspects of web development.

       Beyond coding, I’m diving into IoT with projects aimed at solving local issues. Inspired by Bangladesh’s “More Fish” project, I’m working on a device to monitor water quality in ponds, helping fish farmers increase yields. Another project automates the pre-exam process at my university, reducing time and effort for students through online applications and mobile banking.

       As I grow technically, I’m also committed to self-improvement, focusing on discipline and health. I document my journey through YouTube and blogging, sharing insights as I learn. Each project and challenge brings me closer to my vision of using tech to make a difference!"
      page_type: post
      count: 5
      filters:
        author: "Debashis Dhali"
      order: desc
    design:
      view: date-title-summary
      spacing:
        padding: [0, 0, 0, 0]

  - block: cta-card
    demo: false
    content:
      title: "💡 Let’s Build Something Amazing Together"
      text: |-
        I'm always open to collaborations, whether for full-stack projects, IoT innovations, or tackling real-world challenges with tech. Feel free to reach out if you have an idea or project in mind!
      button:
        text: Contact Me
        url: /contact
    design:
      card:
        css_class: "bg-primary-700"
        css_style: ""
---
