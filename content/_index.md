---
# Leave the homepage title empty to use the site title
title: zarema-akhmadiyeva
date: 2023-10-06
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
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
        - title: Research Associate
          company: Leibniz Institute of Agricultural Development in Transition Economies(IAMO). Department of Agricultural Policy
          company_url: 'https://www.iamo.de/'
          company_logo: 
          location: Halle (Saale), Germany
          date_start: '2017-06-15'
          date_end: '2021-10-30'
          description: |2-
              Responsibilities include:

              * Performing research in topics related to agricultural development andland reforms in countries with transition economies;
              * Contribution to measuring tenure security and understanding itsinfluence on producers’ incentives
              * Contribution to scientific publications
        - title: Lecturer
          company: Suleyman Demirel University
          company_url: 'https://sdu.edu.kz/language/en/'
          company_logo: 
          location: Almaty, Kazakhstan
          date_start: '2013-09-01'
          date_end: '2027-06-15'
          description: Full-time lecturer of Statistics, Econometrics, Principles of Economics,and Sustainable Development for students of Faculty of Economics andAdministrative Sciences.
    design:
      columns: '2'
  - block: collection
    content:
      title: Recent Publications
      text: |-
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      # Contact (add or remove contact options as necessary)
      email: zarema.akhmadieva@gmail.com
      contact_links:
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
      columns: '2'
---
