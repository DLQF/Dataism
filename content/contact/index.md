---
title: Contact
date: 2022-10-24

type: landing

sections:
  - block: contact
    content:
      title: Contact
      text: |-
        Please feel free to contact us if you want to collaborate with us or join the team. We would be happy to have you!
      email: habibnia@vt.ed
#      phone: 888 888 88 88
      address:
        street: Pamplin Hall, 880 West Campus Drive
        city: Blacksburg
        region: VA
        postcode: '24060'
        country: United States
        country_code: US
      coordinates:
        latitude: '37.22876'
        longitude: '-80.42462'
      directions: Enter Pamplin Hall and head to room 3016
#      office_hours:
#        - 'Monday 10:00 to 13:00'
#        - 'Wednesday 09:00 to 10:00' 
#      appointment_url: 'https://calendly.com'
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

  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: pamplin_hall.jpeg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen
---
