---
# An instance of the Blank widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: blank

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 10

# Section title
title: Beyersmann Reading Lab

# Section subtitle
subtitle:

# Section design
design:
  # Use a 1-column layout
  columns: "1"
  
banner:
  image: "home.jpg"
  image_position: center
    
---

<html>
<head>
  <style>
    /* Center align the header and body text */
    h2 {
      text-align: center;
      font-weight: bold;
      font-size: 32px; /* Adjusted size */
    }
    p {
      text-align: center;
      font-size: 18px; /* Adjusted font size */
      line-height: 1.6;
    }
    /* Ensuring the image is centered */
    .image-container {
      text-align: center;
      margin-top: 20px;
    }
  </style>
</head>
<body>

  <!-- Heading for the lab -->
  <h2>Beyersmann Reading Lab</h2>

  <!-- Body text with linked researcher and university info -->
  <p>
    <a href="https://beyersmannlab.cogscience.org/author/associate-professor-elisabeth-lisi-beyersmann/" target="_blank">
      Associate Professor Elisabeth (Lisi) Beyersmann
    </a> and her team are based at the 
    <a href="https://www.mq.edu.au/about/about-the-university/our-faculties/medicine-and-health-sciences/departments-and-centres/department-of-psychology" target="_blank">
      School of Psychological Sciences at Macquarie University
    </a> and are interested in the cognitive underpinnings of language processing, particularly in understanding the processes involved in reading and reading development. 
    The lab investigates language processing in both children and adults, using a variety of behavioural, neuropsychological, and neurophysiological techniques including MEG, EEG, and eye-tracking.
  </p>

  <!-- Image below the text -->
  <div class="image-container">
    {{< figure src="home.jpg" caption="Beyersmann Reading Lab" >}}
  </div>

  <!-- Call to action for "Meet the Team" -->
  {{% cta cta_link="./researchers/" cta_text="Meet the Team →" %}}

</body>
</html>



  

