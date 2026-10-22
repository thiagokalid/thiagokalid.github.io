---
title: ""
summary: ""
date: "2022-10-24"
type: "landing"
design:
  spacing: 5rem"
sections:
  - block: "resume-biography-3"
    content:
      username: "me"
      text: |2-
          Hi! I’m Thiago, a graduate researcher at the [UTFPR](https://www.utfpr.edu.br/english), currently pursuing an M.Sc. in Computer Engineering in the [Graduate Program in Electrical and Computer Engineering](https://antigo.utfpr.edu.br/cursos/coordenacoes/stricto-sensu/cpgei/english/graduate-program-in-electrical-and-computer-engineering). My work is at the intersection of inverse problems and signal processing, mostly applied to ultrasonic imaging for non-destructive testing.


          For the past few years, I’ve been part of [AUSPEX](https://lassip-utfpr.github.io/AUSPEX/load_presentation2.html), a [Petrobras](https://petrobras.com.br/en)-funded project at the [Laboratory of Statistical Signal Processing and Inverse Problems (LASSIP)](https://utfpr.curitiba.br/lassip/). There, I help developing new ultrasound techniques to inspect subsea pipelines faster and more reliably.

          I’m particularly interested in using signal processing and physics-based models to extract meaningful information from sensor data in real-world environments. I find it fascinating that algorithms and sensing systems allow us to infer quantities that are hard (or impossible) to measure directly, and how this can directly support real-world decision-making.

          You can check out more about my academic journey below. Feel free to reach out at [thiagokalid@alunos.utfpr.edu.br](mailto:thiagokalid@alunos.utfpr.edu.br). I’d love to connect!
        
      button:
        text: "Download my CV"
        url: "uploads/thiagokalid_cv.pdf"
      headings:
        interests: ""
        about: "About me"
        education: "Education"

    design:
      background:
        gradient_mesh:
          enable: true

      #background:
      #color: "#eeeeee"
      name:
        size: "md"
      avatar:
        size: "large"
        shape: "rounded"
      banner: {}
    oe: "section-db2a473a"
    _internalId: "section-at0lCZGQ"
  - block: "cta-button-list"
    oe: "section-5-cta-button-list"
    _internalId: "section-NZfWicbe"
    
  - block: "markdown"
    content:
      title: "Research"
      subtitle: ""
      text: |-        
       I am passionate about applying complex mathematical modeling to solve real-world problems. For this reason (along with a bit of life’s randomness), I naturally gravitated toward the intersection of signal processing and inverse problems, primarily in ultrasound imaging for NDT.

       More recently, I have enjoyed studying ultrasound simulation methods, such as ray tracing and finite-element-based methods, to enhance my understanding of the physics behind sound propagation.

       While these are the areas I have worked on so far, one of the things that I most enjoy is studying new subjects and concepts.  

    design:
      columns: "1"
      
    oe: "section-02377af5"
    id: "research"
    _internalId: "section-mEAD8Lij"
    
  - block: "collection"
    content:
      count: 6
      offset: 0
      sort_by: "Date"
      sort_ascending: false
      title: "Projects"
      text: |-
        Some interesting academic projects I’ve worked on that did not lead (yet) to formal publications.
      order: "desc"
      filters:
        folders:
          - "projects"
    oe: "section-4-collection"
    design:
      background:
        color: "#f5f5f5"
      columns: 3
      fill_image: false
      show_date: true
      show_read_time: false
      show_read_more: true
      view: "article-grid"
    id: "projects"
    _internalId: "section-d0UfL1OD"
    
  - block: "collection"
    content:
      title: "Recent Papers"
      filters:
        folders:
          - "publications"
        featured_only: false
      order: "desc"
      sort_by: "Date"
      offset: 0
      count: 0
    design:
      view: "citation"
      columns: 1
      fill_image: false
      show_date: true
      show_read_more: false
      background:
        color: "#f5f5f5"
    oe: "section-papers"
    id: "papers"
    _internalId: "section-ehG-ifiu"
    
  - block: "contact-info"
    content:
      title: "Contact"
      visit_title: "Visit Us"
      connect_title: " "
      show_form: false
      email: "thiagokalid@alunos.utfpr.edu.br"
      #prospective:
      #  button: {}
    oe: "section-6-contact-info"
#    design:       
#      background:
#        color: "#f5f5f5"
    id: "contact"
    _internalId: "section-66_1H6bb"
---
