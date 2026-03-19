---
# Leave the homepage title empty to use the site title
title:
#type: landing
type: home_index
#subTitle: Animal Physiological Ecology and Conservation







heroBlock:
  block: hero
  content:
    title: Welcome to the Lab!
    subtitle: About Wang Wei
#    image:
#      filename: research_topic.jpg
    text: |
      He received his B.S. in Chemistry from Nanjing Normal University in 1988, followed by an M.S. in Organic Chemistry from the Shanghai Institute of Materia Medica, Chinese Academy of Sciences in 1993. He earned his Ph.D. in Organic Chemistry from North Carolina State University, USA, in 2000. He then completed postdoctoral training at the University of Arizona (2000-2001). Subsequently, he worked as a Senior Investigator at the Novartis Institute for Genomic Research, USA (2001-2003). He began his academic career as an Assistant Professor (2003-2008) and later became an Associate Professor (2008-2012) and then Full Professor (2012-2018) at the University of New Mexico, USA. In 2018, he joined the University of Arizona College of Pharmacy as the Coit Professor and Co-Director of the Center for Drug Discovery, a position he held until 2025.
  
      Throughout his career, he has authored over 350 research papers in prestigious journals such as Nature Catalysis, Nature Communications, Nature Cell Biology, Chem, Journal of the American Chemical Society (JACS), and Angewandte Chemie. He has also published one book and 17 book chapters, maintaining an H-index of 85. He holds 18 granted patents, including 12 in the United States and 6 in China. He has founded three biotechnology and new drug discovery startup companies.
      
      In recognition of his contributions, he was elected as a Fellow of the American Institute for Medical and Biological Engineering (AIMBE). His awards include the Outstanding Basic Research Award from the University of Arizona Cancer Center (2023), the James Halpert Outstanding Research Award from the University of Arizona College of Pharmacy (2021), and the Distinguished Junior Faculty Research Award from the Chinese-American Chemistry and Chemical Biology Professors Association (2008).
        

  
heroSlideBlock:
  block: slider
  content:
    slides:
    - title: 
      content: 
      align: center
      background:
        image:
          filename: group_slides/team-view.webp
          filters:
            brightness: 1.1
        position: right
        color: '#666'  
    # - title: 
    #   content: 
    #   align: left
    #   background:
    #     image:
    #       filename: group_slides/group_photo2.jpg
    #       filters:
    #         brightness: 1
    #     position: right
    #     color: '#666'  
  design:
    # Slide height is automatic unless you force a specific height (e.g. '400px')
    slide_height: '400px'
    is_fullscreen: false
    # Automatically transition through slides?
    loop: false
    # Duration of transition between slides (in ms)
    interval: 2000


newsBlock:
  block: collection
  content:
    title: Latest News
    count: 5
    filters:
      author: ''
      category: ''
      exclude_featured: false
      publication_type: ''
      tag: ''
    offset: 0
    order: desc
    page_type: post
  design:
    view: card
    columns: '1'      


publicationsBlock:
  block: collection
  content:
    title: Publications
    count: 5
    filters:
      folders:
        - publication
#      publication_type: 'article-journal'
      publication_type: 
  design:
    view: card
    columns: '1'      

teamsBlock:
  block: markdown
  content:
    title:
    subtitle:  
    text: |
      {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
  design:
    columns: '1'



 
---
