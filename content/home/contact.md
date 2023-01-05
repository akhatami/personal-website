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
#   form:
#     provider: netlify
#     formspree:
#       id:
#     netlify:
#       # Enable CAPTCHA challenge to reduce spam?
#       captcha: false
  # Contact details
  email: "info@akhatami.com"
  phone: ''
  
  # Address
  # For country_code, use the 2-letter ISO code (see https://en.wikipedia.org/  wiki/ISO_3166-1_alpha-2 )
  address:
    street: Van Mourik Broekmanweg 6
    city: Delft
    region: South-Holland
    postcode: 2628 XE
    country: The Netherlands
    country_code: NL
  
  # Geographic coordinates
  # To get your coordinates, right-click on Google Maps and choose "What's   here?". The coords will show up at the bottom.
  coordinates:
    latitude: "37.4275"
    longitude: "-122.1697"
  
  # Directions for visitors to locate you.
  # directions: 
  
  # Office hours
  # A list of your office hours. To remove, set to an empty list `[]`.
  office_hours: []
  
  # Enter an optional link for booking appointments (e.g. calendly.com).
  appointment_url: ""
  
  # Contact links
  # Set to `[]` to disable, or comment out unwanted lines with a hash `#`.
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: DM Me
      link: "https://twitter.com/_akhatami_"
    # - icon: skype
    #   icon_pack: fab
    #   name: Skype Me
    #   link: ""
  design:
    columns: '2'
---