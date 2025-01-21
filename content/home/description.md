---
# An instance of the Blank widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: blank

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 10

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
    /* Center align the h3 heading and make it bold, with a smaller size */
    h3 {
      text-align: center;
      font-weight: bold;  /* Ensures the heading is bold */
      font-size: 28px; /* Adjusted smaller size */
      margin-bottom: 20px; /* Adds some space below the heading */
    }

    /* Center align the paragraph text with a smaller font size */
    p {
      text-align: center;
      font-size: 16px; /* Adjusted smaller font size */
      line-height: 1.6;
      margin-bottom: 30px; /* Adds some space below the paragraph */
    }

    /* Center the image and add a small gap between text and image */
    .image-container {
      text-align: center;
      margin-top: 20px; /* Adds space above the image */
      margin-bottom: 20px; /* Adds space below the image */
    }
  </style>
</head>
<body>

  <!-- Heading for the lab (now h3) -->
  <h3>Beyersmann Reading Lab</h3>

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

  <!-- Image below the text (without caption) -->
  <div class="image-container">
    {{< figure src="home.jpg" >}} <!-- Image without caption -->
  </div>

  <!-- Call to action for "Meet the Team" -->
  {{% cta cta_link="./researchers/" cta_text="Meet the Team →" %}}

</body>
</html>


  

