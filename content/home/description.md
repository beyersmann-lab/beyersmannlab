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
      text-align: center;---
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
    /* Ensure the whole page is styled correctly, targeting only specific elements */
    body {
      font-family: Arial, sans-serif; /* Optional, for better readability */
    }

    /* Center the heading (h3) and make it bold, with a smaller font */
    h3 {
      text-align: center;
      font-weight: bold;
      font-size: 24px; /* Adjust to a smaller size */
      margin-bottom: 20px; /* Adds some space below the heading */
    }

    /* Ensure description text is centered and smaller */
    .description-text {
      font-size: 14px !important; /* Make sure it's smaller */
      text-align: center; /* Ensure the text is centered */
      max-width: 800px; /* Prevent the text from stretching too wide */
      margin: 0 auto 20px auto; /* Center the paragraph and space below */
      padding-left: 10px;
      padding-right: 10px;
      line-height: 1.6; /* Improve readability */
    }

    /* Image styling: Ensure it is centered */
    .image-container {
      text-align: center;
      margin-top: 20px; /* Space above image */
      margin-bottom: 20px; /* Space below image */
    }

    .image-container img {
      display: block;
      margin-left: auto;
      margin-right: auto;
      max-width: 100%;
    }

    /* "Meet the Team" Button Styling: Reduce space below */
    .cta-container {
      margin-bottom: 10px; /* Reduce space after the button */
    }
  </style>
</head>
<body>

  <!-- Heading for the lab (now h3) -->
  <h3>Beyersmann Reading Lab</h3>

  <!-- Body text with linked researcher and university info -->
  <p class="description-text">
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
  <div class="cta-container">
    {{% cta cta_link="./researchers/" cta_text="Meet the Team →" %}}
  </div>

</body>
</html>

