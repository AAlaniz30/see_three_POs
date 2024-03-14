---
title: "TEST TITLE"
sections:
- block: hero
  content:
    title: |-
    
      Bee Movie 
    
      By Jerry Seinfeld
      
  design:
    spacing:
      padding: ["40px","0","20px","0"]
    background:
      gradient_end: '#1b2724'
      gradient_start: '#264038'
      text_color_light: yes
    css_class: 'big_headline'
- block: markdown
  content:
    text: |-
    
      ### {{< icon name="bug" pack="fas" >}} *According to all known laws of aviation*
        
      ### {{< icon name="calculator" pack="fas" >}} **there is no way a bee should be able to fly**
        
      ### {{< icon name="terminal" pack="fas" >}} **Its wings are too small to get its fat little body off the ground**
      
      <br />
    
      ## Engaging people with web-based apps
      
      Stakeholders respond well to interactive, local predictions. For example, foresters wish to know where and when pests like Spongy moth (*Lymantria dispar*) will appear.
      
      #### *Using the app*
      
      Select a year and a site on the **Map** tab to see estimated population densities for that location and year on the **Population Densities** tab. The <span style="color:#6eb39c">dotted teal line</span> tracks today's date in 2023.
      
        <iframe height="1200px" width="100%" src="https://ecodata.pro/phenogamTest/" frameborder="0"></iframe>
      
  design:
    background:
      image:
        color: '#1b2724'
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
