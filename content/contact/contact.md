---
# An instance of the Contact widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 10

title: Contact
subtitle:

content:
  # Contact (edit or remove options as required)

  email: lisi.beyersmann@mq.edu.au
  phone: +61 2 9850 2976
  address:
    street: Australian Hearing Hub, 16 University Ave
    city: Macquarie University
    region: NSW
    postcode: '2109'
    country: Australia
    country_code: AU
  coordinates:
    latitude: '-33.77676'
    longitude: '151.111949'
  #contact_links:
  #  - icon: comments
  #    icon_pack: fas
  #    name: Discuss on Forum
  #    link: 'https://discourse.gohugo.io'

  # Automatically link email and phone or display as text?
  autolink: true

  # Email form provider
  form:
    provider: netlify
    formspree:
      id:
    netlify:
      # Enable CAPTCHA challenge to reduce spam?
      captcha: false

design:
  columns: '1'
---
