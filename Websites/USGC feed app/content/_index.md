---
title: "USGC Feed Calculator"
sections:
- block: hero
  content:
    title: |-
    
      Feed Purchase and Feed Production Savings Calculator
      
  design:
    spacing:
      padding: ["40px","0","20px","0"]
    background:
      color: '#003e6a'
      text_color_light: yes
    css_class: 'big_headline'
- block: markdown
  content:
    text: |-
    
      ### {{< icon name="sack-dollar" pack="fas" >}} **Biological system:** Spongy moth, spotted lanternfly
        
      ### {{< icon name="drumstick-bite" pack="fas" >}} **Data analysis:** General additive models, iNaturalist dataset
        
      ### {{< icon name="wheat-awn" pack="fas" >}} **Production stack:** R, Shiny, AWS, Shiny Server, Nginx
      
      <br />
    
      ## Engaging people with web-based apps
      
      Stakeholders respond well to interactive, local predictions. For example, foresters wish to know where and when pests like Spongy moth (*Lymantria dispar*) will appear.
      
      #### *Using the app*
      
      Select a year and a site on the **Map** tab to see estimated population densities for that location and year on the **Population Densities** tab. The <span style="color:#6eb39c">dotted teal line</span> tracks today's date in 2023.
      
        <iframe height="1200px" width="100%" src="https://usgrains.corn-simulator.dev.ecodata.pro/" frameborder="0"></iframe>
      
  design:
    background:
      image:
        color: '#f6cf3f'
        text_color_light: yes
    css_class: 'brief'
    spacing:
      padding: ["20px","0","5px","0"]
- block: portfolio
  content:
    filters:
      folders: project
      tags:
      - Intro
      - Problem
      - Solution
    title: ''
    sort_by: Weight
    sort_ascending: yes
  design:
    spacing:
      padding: ["40px","0","40px","0"]
    columns: '1'
    flip_alt_rows: yes
    view: community/showcase_rounded
    background:
      color: '#1b2724'
      text_color_light: yes
- block: markdown
  design:
    background:
      image:
        filename: bg.jpeg
        size: cover
        position: center
        parallax: yes
        text_color_light: yes
date: "2022-10-24"
type: landing
---
