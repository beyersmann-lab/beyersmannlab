---

widget: blank
weight: 1
active: true
headless: true
title: Walking Lab
subtitle: The Walking Lab meets every fortnight and is based on the idea that walking encourages thinking. Many philosophers, such as Socrates and Aristotle, walked with their students. In fact, Aristotle was known to walk in his lectures, as he believed that walking facilitates thinking. Instead of meeting in a conventional conference room, the Walking Lab meeting is entirely media-free and takes place in a new campus location every time, including both indoor and outdoor venues. The lab walks together from our department building to a specific location on campus, where the meeting is held either standing or sitting. Not only does the meeting allow lab members to discover the unexpected variety of campus features such as lawns, amphitheatres, botanical gardens, and roof top terrasses, but it also provides an opportunity to brainstorm, network, and have a desk-free hour in the day.

---

widget: slider  # Use the Slider widget as this page section
weight: 2  # Position of this section on the page
active: true  # Publish this section?
headless: true  # This file represents a page section.

design:
  # Slide height is automatic unless you force a specific height (e.g. '400px')
  slide_height: ''
  is_fullscreen: true
  # Automatically transition through slides?
  loop: false
  # Duration of transition between slides (in ms)
  interval: 2000

content:
  slides:
    - title: Walking Lab Gallery
      content: Take a look at various locations on campus the Walking Lab have visited...
      align: center
      background:
        position: right
        color: '#666'
        brightness: 0.7
        media: coders.jpg
        fit: cover
    - title: Lunch & Learn ☕️
      content: 'Share your knowledge with the group and explore exciting new topics together!'
      align: left
      background:
        position: center
        color: '#555'
        brightness: 0.7
        media: contact.jpg
        fit: cover
    - title: World-Class Semiconductor Lab
      content: 'Just opened last month!'
      align: right
      background:
        position: center
        color: '#333'
        brightness: 0.5
        media: welcome.jpg
        fit: cover
      link:
        icon: graduation-cap
        icon_pack: fas
        text: Join Us
        url: ../contact/
