---
layout: page
title: About
#background_style: bg-info
background_image: url('assets/img/backgrounds/image-from-rawpixel-id-1199650-jpeg.jpg')
# Add a link to the the top menu
menus:
  header:
    title: About
    weight: 2

sections:
- type: members.html
  section_id: team
  title: Our Crew!
  background_style: bg-info text-white
  members:
    - title: Addy Moran
      text: Founder & Software Engineer
      image: assets/img/members/person1.jpg
      url: 'https://addymmoran.github.io'
  
- type: timeline.html
  section_id: history
  title: History
  background_style: bg-dark text-primary
  last_image: assets/img/timeline-end.png
  actions:
    - image: assets/img/portfolio/thumbnails/1.jpg
      title: >+
        2017-2018
        **Humble Beginnings**
      text: >-
        We begun with small group of people willing to work hard and make our
        teaching skills worth , in front of all others!
    - image: assets/img/portfolio/thumbnails/2.jpg
      title: >+
        November 2019
        An Coaching started
      text: >-
        We started to gather like minded people and started our stategies
        and future plans to them. As a result , interested people joined us!


- type: contact.html
  section_id: contact
  title: Get In Touch!
  text: >-
    Ready to start your next project with us? Give us a call or send us an email
    and we will get back to you as soon as possible!
  actions:
    - title: +1 (202) 555-014
      icon: fa-phone
    - title: E-Mail
      icon: fa-envelope
      url: mailto:contact@yourwebsite.com
    - title: Twitter
      icon: fa-twitter
      icon_type: fab
      url: '#'
    - title: Facebook
      icon: fa-facebook
      icon_type: fab
      url: '#'
  
---