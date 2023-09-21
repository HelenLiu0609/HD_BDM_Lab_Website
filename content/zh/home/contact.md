---
# An instance of the Contact widget.
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 80

title: 联系我们
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
  email: email
  address:
    street: 地址
    city: 城市
    region: 省份
    postcode: '邮编'
    country: 国家
    country_code: 国家缩写
  coordinates:
    latitude: '32.03'
    longitude: '118.46'
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: DM Me
      link: 'https://twitter.com/hcp4715'

design:
  columns: '2'
---
