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
    /* Heading: Center and bold */
    h3 {
      text-align: center;          /* Ensure heading is centered */
      font-weight: bold;
      font-size: 28px;             /* Keep the header size the same as before */
      margin-bottom: 20px;         /* Adds space below the heading */
    }

    /* Description Text: Centered, smaller and with good margins */
    .description-text {
      text-align: center;          /* Ensures the text is centered */
      font-size: 18px;             /* Adjusted for better readability */
      max-width: 800px;            /* Keeps text width manageable */
      margin-left: auto;           /* Centers the text */
      margin-right: auto;          /* Centers the text */
      line-height: 1.6;            /* Adds more space between lines */
      margin-bottom: 30px;         /* Increased margin below the text */
      padding-left: 20px;          /* Adds padding inside the container */
      padding-right: 20px;         /* Adds padding inside the container */
    }

    /* Image container: Keep it centered */
    .image-container {
      text-align: center;
      margin-top: 20px;            /* Adds space above the image */
      margin-bottom: 20px;         /* Adds space below the image */
    }

    .image-container img {
      display: block;
      margin-left: auto;           /* Centers the image horizontally */
      margin-right: auto;
      max-width: 100%;             /* Ensures the image doesn't overflow */
    }

    /* Reducing space after "Meet the Team" button */
    .cta-container {
      margin-bottom: 10px;         /* Adjusts space below the CTA button */
    }
  </style>
</head>
<body>

  <!-- Heading for the lab (h3 centered) -->
  <h3>Beyersmann Reading Lab</h3>

  <!-- Description Text: Apply the "description-text" class here -->
  <p class="description-text">
    Associate Professor Elisabeth (Lisi) Beyersmann and her team are based at the 
    <a href="https://www.mq.edu.au/about/about-the-university/our-faculties/medicine-and-health-sciences/departments-and-centres/department-of-psychology" target="_blank">
      School of Psychological Sciences at Macquarie University
    </a> and are interested in the cognitive underpinnings of language processing, particularly in understanding the processes involved in reading and reading development.
    The lab investigates language processing in both children and adults, using a variety of behavioural, neuropsychological, and neurophysiological techniques including MEG, EEG, and eye-tracking.
  </p>

  <!-- Image Section -->
  <div class="image-container">
    {{< figure src="home.jpg" >}} <!-- Image without caption -->
  </div>

  <!-- Meet the Team Link -->
  <div class="cta-container">
    {{% cta cta_link="./researchers/" cta_text="Meet the Team →" %}}
  </div>

</body>
</html>
