---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.avatar
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: lrapetti
      # Override your bio text from `authors/lrapetti/_index.md`?
      text:
  - block: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Postdoctoral Researcher
          company: Istituto Italiano di Tecnologia
          company_url: 'https://www.iit.it/'
          company_logo: iit
          location: Genoa, Italy
          date_start: '2023-01-01'
          date_end: ''
          description:
        - title: PhD Fellow
          company: Istituto Italiano di Tecnologia
          company_url: 'https://www.iit.it/'
          company_logo: iit
          location: Genoa, Italy
          date_start: '2019-01-01'
          date_end: '2022-12-31'
          description:
        - title: Research Fellow
          company: Istituto Italiano di Tecnologia
          company_url: 'https://www.iit.it/'
          company_logo: iit
          location: Genoa, Italy
          date_start: '2018-05-01'
          date_end: '2018-12-31'
          description:
        - title: Graduate Research Fellow
          company: University of Illinois College of Medicine
          company_url: 'https://medicine.uic.edu/'
          company_logo: uic
          location: Chicago, US
          date_start: '2016-09-01'
          date_end: '2017-05-31'
          description: 
    design:
      columns: '2'
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
      #   Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis ut magna et, vehicula efficitur enim.
      # Contact (add or remove contact options as necessary)
      email: lorenzo.rapetti@iit.com
      # phone: 888 888 88 88
      # appointment_url: 'https://calendly.com'
      # address:
      #   street: 450 Serra Mall
      #   city: Stanford
      #   region: CA
      #   postcode: '94305'
      #   country: United States
      #   country_code: US
      #  directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
      #  office_hours:
      #    - 'Monday 10:00 to 13:00'
      #    - 'Wednesday 09:00 to 10:00'
      # contact_links:
      #   - icon: twitter
      #     icon_pack: fab
      #     name: DM Me
      #     link: 'https://twitter.com/Twitter'
      #   - icon: skype
      #     icon_pack: fab
      #     name: Skype Me
      #     link: 'skype:echo123?call'
      #   - icon: video
      #     icon_pack: fas
      #     name: Zoom Me
      #     link: 'https://zoom.com'
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      # form:
      #   provider: netlify
      #   formspree:
      #     id:
      #   netlify:
      #     # Enable CAPTCHA challenge to reduce spam?
      #     captcha: false
    design:
      columns: '2'
---
