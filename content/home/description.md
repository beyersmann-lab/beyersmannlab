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
    /* Description Text (Smaller and Centered) */
    .description-text {
      text-align: center;          /* Ensures the text is centered */
      font-size: 14px;             /* Smaller font size to fit within 3 lines */
      max-width: 800px;            /* Keeps text within a manageable width */
      margin-left: auto;
      margin-right: auto;         /* Centers the paragraph */
      line-height: 1.4;           /* Makes the text more compact */
      margin-bottom: 20px;        /* Adds space below the text */
      padding-left: 10px;
      padding-right: 10px;
    }

    /* Heading remains centered */
    h3 {
      text-align: center;
      font-weight: bold;
      font-size: 28px;
      margin-bottom: 20px;
    }

    /* Image container centered */
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

    /* Reduce space below CTA button */
    .cta-container {
      margin-bottom: 10px;
    }
  </style>
</head>
<body>

  <h3>Beyersmann Reading Lab</h3>
  
  <!-- Description Text -->
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
