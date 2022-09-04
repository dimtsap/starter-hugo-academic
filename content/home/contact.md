---
# An instance of the Contact widget.
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 130

title: Contact
subtitle:

content:
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

  # Contact details (edit or remove options as required)
  email: dimtsap@hotmail.com
  address:
    street: 3400 North Charles Street
    city: Baltimore
    region: MD
    postcode: '21218'
    country: United States
    country_code: US
  coordinates:
    latitude: '39.3278'
    longitude: '-76.6207'
  directions: Enter Latrobe Hall and take the stairs to Office 310 on Floor 3
  appointment_url: 'https://calendly.com'
  contact_links:
    - icon: linkedin-in
      icon_pack: fas
      name: DM Me
      link: 'https://www.linkedin.com/in/dimitris-tsapetis/'
    - icon: video
      icon_pack: fas
      name: Zoom Me
      link: 'https://JHUBlueJays.zoom.us/my/dtsapetis'

design:
  columns: '2'
---
