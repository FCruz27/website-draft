---
# An instance of the Contact widget.
widget: contact

# Activate this widget? true/false
active: true

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 60

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
  email: franciscocorreiadacruz@gmail.com
  address:
    street: Alameda da Universidade
    city: Lisbon
    postcode: '1649-013'
    country: Portugal
    country_code: PT
  directions: Office XXX

design:
  columns: '2'
---
