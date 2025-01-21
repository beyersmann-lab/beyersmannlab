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
      font-weight: bold;
      font-size: 28px; /* Adjusted smaller size */
      margin-bottom: 20px; /* Adds some space below the heading */
    }

    /* Specific styling for description paragraph */
    .description-text {
      text-align: center;  /* Ensure text is centered */
      font-size: 14px !important; /* Ensures text is smaller, using !important to override */
      line-height: 1.6;
      margin-bottom: 20px;
      max-width: 800px; /* Restricts width for readability */
      margin-left: auto;
      margin-right: auto; /* Centers the paragraph container */
      padding-left: 10px;
      padding-right: 10px;
    }

    /* Center the image container and image */
    .image-container {
      text-align: center;
      margin-top: 20px;
      margin-bottom: 20px;
    }

    .image-container img {
      display: block;
      margin-left: auto;
      margin-right: auto;
      max-width: 100%;
    }

    /* Reduce space between "Meet the Team" button and next section */
    .cta-container {
      margin-bottom: 10px;
    }
  </style>
</head>
<body>

  <!-- Heading for the lab (now h3) -->
  <h3>Beyersmann Reading Lab</h3>

  <!-- Description paragraph -->
  <p class="description-text">
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
    {{< figure src="home.jpg" >}} <!-- Image without caption -->
  </div>

  <!-- Call to action for "Meet the Team" -->
  <div class="cta-container">
    {{% cta cta_link="./researchers/" cta_text="Meet the Team →" %}}
  </div>

</body>
</html>
