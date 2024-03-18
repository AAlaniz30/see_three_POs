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
        
      ### {{< icon name="spider" pack="fas" >}} **there is no way a bee should be able to fly**
        
      ### {{< icon name="forumbee" pack="fab" >}} ***Its wings are too small to get its fat little body off the ground***
      
      <br />
    
      ## The bee, of course, flies anyway
      
      because bees don't care what humans think is impossible. Yellow, black. Yellow, black. Yellow, black. Yellow, black.
      
      Ooh, black and yellow! Let's shake it up a little.
      
      #### *Barry! Breakfast is ready!*
      
      Coming! Hang on a second. Hello? Barry? Adam? Can you believe this is happening? I can't. I'll pick you up. Looking *sharp*. Use the stairs. Your father paid good money for those. Sorry. I'm excited.  Here's the graduate. *We're very proud of you, son*. A perfect report card, ***all B's***.
      
        <iframe height="500px" width="100%" src="https://usgrains.corn-simulator.ecodata.pro/" frameborder="0"></iframe>
      
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
  content:
    text: |-
    
        <iframe height="500px" width="100%" src="https://ecodata.pro/phenogamTest/" frameborder="0"></iframe>
      
  design:
    background:
      image:
        color: '#1b2724'
        text_color_light: yes
    css_class: 'brief'
    spacing:
      padding: ["20px","0","5px","0"]



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
