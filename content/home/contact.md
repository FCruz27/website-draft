---
# An instance of the Contact widget.
widget: contact

# Activate this widget? true/false
active: true

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
  email: franciscocorreiadacruz@gmail.com
  address:
    street: Alameda da Universidade
    city: Lisbon
    postcode: '1649-013'
    country: Portugal
    country_code: PT
  directions: Office XXX
  contact_links:
  - icon: researchgate
    icon_pack: ai
    link: https://www.researchgate.net/profile/Francisco-Cruz-16 
  - icon: twitter
    icon_pack: fab
    link: https://twitter.com/cruz_fcorreia
  - icon: linkedin
    icon_pack: fab
    link: https://www.linkedin.com/in/francisco-cruz-23a58115b/

design:
  columns: '2'
---
