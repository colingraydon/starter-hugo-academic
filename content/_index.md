---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: features
    id: skills
    content:
      title: Skills

      items:
        - name: R
          description: 90%
          icon: r-project
          icon_pack: fab
        - name: Statistics
          description: 100%
          icon: chart-line
          icon_pack: fas
        - name: Photography
          description: 10%
          icon: camera-retro
          icon_pack: fas
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
        - title: CEO
          company: GenCoin
          company_url: ""
          company_logo: org-gc
          location: California
          date_start: "2021-01-01"
          date_end: ""
          description: |2-
              Responsibilities include:

              * Analysing
              * Modelling
              * Deploying
        - title: Professor of Semiconductor Physics
          company: University X
          company_url: ""
          company_logo: org-x
          location: California
          date_start: "2016-01-01"
          date_end: "2020-12-31"
          description: Taught electronic engineering and researched semiconductor physics.
    design:
      columns: "2"
  - block: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: "Accomplish&shy;ments"
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url: https://www.credly.com/users/colin-graydon/badges?sort=-state_updated_at&page=1
          date_end: ""
          date_start: "2023-05-23"
          description: "Showcases proficiency in the deployment, maintenance, and troubleshooting of Kubernetes clusters, including development, networking, logging, and secret management"
          organization: Linux Foundation
          organization_url: https://www.linuxfoundation.org/
          title: Certified Kubernetes Administrator
          url: ""
        - certificate_url: https://www.credly.com/users/colin-graydon/badges?sort=-state_updated_at&page=1
          date_end: ""
          date_start: "2023-01-01"
          description: Indicates an understanding of monitoring cloud-native applications and infrastructure. Demonstrates the ability to design and implement data-scraping methods.
          organization: Linux Foundation
          organization_url: https://www.linuxfoundation.org/
          title: Certified Prometheus Associate

        - certificate_url: https://www.credly.com/users/colin-graydon/badges?sort=-state_updated_at&page=1
          date_start: "2023-04-06"
          description: "Demonstrates an ability to design and build well-architected distributed systems which are resilient, cost-effective, and scalable"
          organization: AWS
          organization_url: https://aws.amazon.com/
          title: "AWS Certified Solutions Architect"
          url: ""
    design:
      columns: "2"

  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis ut magna et, vehicula efficitur enim.
      # Contact (add or remove contact options as necessary)
      email: colingraydon@gmail.com
      phone: 609 947 8025

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
      columns: "2"
---
