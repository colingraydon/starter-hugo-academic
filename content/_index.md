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
        - name: Full-Stack Developer
          description: TypeScript, React, GraphQL
          icon: code
          icon_pack: fas
        - name: Data Science
          description: Python, R, Machine Learning
          icon: database
          icon_pack: fas
        - name: Dev Ops
          description: Kubernetes, Docker, AWS, Prometheus
          icon: cloud-arrow-up
          icon_pack: fas
  - block: experience
    id: experience
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
        - title: Student
          company: Georgetown University
          company_url: ""
          company_logo: Georgetown
          location: Washington, DC
          date_start: "2023-06-01"
          date_end:
          description: Studying computer science, mathematics, and economics.
        - title: Senior Investment Specialist
          company: Merrill Lynch
          company_url: ""
          company_logo: Merrill
          location: New Jersey
          date_start: "2021-01-01"
          date_end: "2022-06-01"
          description: Licensed broker and advisor. Helped ultra affluent clients solve technical problems.

    design:
      columns: "2"
  - block: accomplishments
    id: accomplishments
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
          description: "Showcases proficiency in the deployment, maintenance, and troubleshooting of Kubernetes clusters, including development, networking, logging, and secret management."
          organization: Kubernetes
          organization_url: https://www.linuxfoundation.org/
          title: Certified Kubernetes Administrator
        - certificate_url: https://www.credly.com/users/colin-graydon/badges?sort=-state_updated_at&page=1
          date_end: ""
          date_start: "2023-01-01"
          description: Indicates an ability to monitor cloud-native applications and infrastructure. Demonstrates aptitude in the design and implementation of data-scraping methods.
          organization: Prometheus
          organization_url: https://www.linuxfoundation.org/
          title: Certified Prometheus Associate

        - certificate_url: https://www.credly.com/users/colin-graydon/badges?sort=-state_updated_at&page=1
          date_start: "2023-04-06"
          description: "Demonstrates an ability to design and build well-architected distributed systems which are resilient, cost-effective, and scalable."
          organization: AWS
          organization_url: https://aws.amazon.com/
          title: "AWS Certified Solutions Architect"

        - date_start: "2022-03-01"
          description: "Held Series 7 and 66 licenses after passing FINRA exams while working for Merrill."
          organization: Finra
          organization_url: https://finra.org/
          title: "Series 7, Series 66 Licenses"

    design:
      columns: "2"

  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        I'd love to hear from you, especially if you're interested in collaborating on a project.
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
