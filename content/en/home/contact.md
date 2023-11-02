---
# An instance of the Contact widget.
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 60

title: Contact Us
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
  email: xtwang@cuhk.edu.cn
  address: 
    street: 2001 Longxiang Boulevard
    city: Shenzhen
    region:
    postcode: '518172'
    country: China
    country_code: country_code
  coordinates:
    latitude: '32.03'
    longitude: '118.46'

design:
  columns: '2'
---
