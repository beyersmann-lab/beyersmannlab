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
      text-align: center !important;    /* Ensure heading is centered */
      font-weight: bold;
      font-size: 28px !important;       /* Keep the header size the same as before */
      margin-bottom: 20px !important;   /* Adds space below the heading */
    }

    /* Description Text: Smaller, centered with good margins */
    .description-text {
      text-align: center !important;          /* Ensures the text is centered */
      font-size: 16px !important;             /* Smaller font size for the description */
      max-width: 700px !important;            /* Keeps text width manageable */
      margin-left: auto !important;           /* Centers the text */
      margin-right: auto !important;          /* Centers the text */
      line-height: 1.4 !important;            /* Adjust line-height for better spacing */
      margin-bottom: 30px !important;         /* Space below the text */
      padding-left: 10px !important;          /* Adds some space on the left */
      padding-right: 10px !important;         /* Adds some space on the right */
    }

    /* Image container: Centered with space around it */
    .image-container {
      text-align: center !important;
      margin-top: 20px !important;            /* Adds space above the image */
      margin-bottom: 20px !important;         /* Adds space below the image */
    }

    .image-container img {
      display: block !important;
      margin-left: auto !important;           /* Centers the image horizontally */
      margin-right: auto !important;
      max-width: 100% !important;             /* Ensures the image doesn't overflow */
    }

    /* Adjust space after "Meet the Team" button */
    .cta-container {
      margin-bottom: 10px !important;         /* Adjusts space below the CTA button */
    }
  </style>
</head>
<body>

  <!-- Heading for the lab (h3 centered) -->
  <h3>Beyersmann Reading Lab</h3>

  <!-- Description Text: Apply the "description-text" class here -->
  <p class="description-text">
    Associate Professor Elisabeth (Lisi) Beyersmann and her team at the 
    <a href="https://www.mq.edu.au/about/about-the-university/our-faculties/medicine-and-health-sciences/departments-and-centres/department-of-psychology" target="_blank">
      School of Psychological Sciences, Macquarie University,
    </a> investigate the cognitive processes involved in reading and reading development. 
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
