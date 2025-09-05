---
# Leave the homepage title empty to use the site title
title:
date: 2025-09-05
type: landing

sections:
  # Remove any potential contact or publication blocks from main sections
  - block: hero
    content:
      title: |
        HuBEL: Human Behaviour and Energy Labratory
      text: |
        <br>
        
        **HuBEL** has been a center of excellence for cutting edge research, teaching, and practice since its founding in 2010.
    design:
      columns: '1'
      background:
        image: 
          filename: welcome.jpg
          filters:
            brightness: 0.6
          parallax: true
          position: center
          size: cover
        text_color_light: true
      spacing:
          padding: ['300px', '0', '20px', '0']
      css_class: fullscreen
  
  - block: markdown
    content:
      title: |
        Welcome to HuBEL
      text: |
        <br>
        
        The Human Behaviour and Energy Laboratory (HuBEL) at the Kyung Hee University was founded in 2010. A central aim of the HuBEL is to contribute to creating carbon efficient and healthy buildings and cities by carrying out innovative research in the area of adaptive comfort, occupant behaviour, energy efficient control algorithm, building energy management system, deep neural network models, the energy-efficiency and renewable energy potentials of buildings and urban space, the health performance of buildings, urban climatic maps, and implications of climate change.

        <br>

        Human factors in building performance is a key research area of HuBEL. The HuBEL has developed and adaptive comfort and behavioural models of control systems for thermal and luminous environments through the rigorous statistical analysis of field measurement data. The energy efficient control algorithms, which enable the application of the behavioural models to Building Energy Management System (BEMS), have been created and tested. The recent research of the HuBEL includes the development of real-time simulation with BEMS, the use of machine learning (deep learning, reinforcement learning) for the design and operation of buildings at urban scales.

        <br>

        Another key research area is the visual perception of occupants and the application of advanced lighting systems. The HuBEL has investigated the visual effects of different spectral power distributions of light sources, the use of lighting systems in practice, and their energy implications through a series of experiments, field measurements, and simulations. Recently, the HuBEL has been testing the subjective responses of people to organic lighting emitting device (OLED) lighting and been developing the lighting strategies to apply OLED in buildings in a carbon efficient way, which can maximise the comfort and well-being of building occupants.

  - block: collection
    id: publications
    content:
      title: Recent Publications
      text: |
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./publication/).
        {{% /callout %}}
      filters:
        folders:
          - publication
        featured_only: false
    design:
      view: citation
      columns: '1'
  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./members/" cta_text="Meet the members →" %}}
    design:
      columns: '1'

---
