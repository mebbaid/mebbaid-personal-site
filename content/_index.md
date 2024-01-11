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
      username: mebbaid
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
          date_start: '2022-02-24'
          date_end: ''
          description:
        - title: Research Fellow
          company: Istituto Italiano di Tecnologia
          company_url: 'https://www.iit.it/'
          company_logo: iit
          location: Genoa, Italy
          date_start: '2018-01-03'
          date_end: '2028-11-01'
          description:
        - title: Automation Engineer
          company: Kenana Engineering and Technical Services - KETS
          company_url: 'https://www.kets.sd'
          company_logo: kets
          location: Khartoum, Sudan
          date_start: '2012-01-01'
          date_end: '2015-05-30'
          description:
        - title: Graduate Teaching assistant
          company: University of Khartoum
          company_url: 'https://uofk.edu/'
          company_logo: U of K
          location: Khartoum, Sudan
          date_start: '2011-08-01'
          date_end: '2011-12-31'
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
