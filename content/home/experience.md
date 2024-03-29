---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 30

title: Work Experience
subtitle:

# Date format for experience
#   Refer to https://wowchemy.com/docs/customization/#date-format
date_format: Jan 2006

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience:
  - title: Software Engineer Intern 
    company: Sony Pictures Entertainment 
    company_url: ''
    company_logo: spe
    location: Los Angeles, California
    date_start: '2022-06-01'
    date_end: ''
    description: |2-
        * Worked on a video upscale project to improve video quality and resolution.

        * Improved the performance and user experience of the Web Application through asynchronous programming and UI logic optimization, etc. Reduced waiting time by 70%.

        * Integrated HDR conversion steps into the current AWS architecture.

        * Utilized Terraform to orchestrate AWS services such as EC2, S3, DynamoDB, Lambda, Batch, SQS, etc. as the practice of infrastructure as code.

  - title: Software Engineer Intern
    company: Nokia
    company_url: ''
    company_logo: nokia
    location: Hangzhou, China
    date_start: '2021-05-23'
    date_end: '2021-08-07'
    description: |2-
        * Developed a 5G document verification system, used to regulate the document format.

        * Acted as Scrum Master, collaborating with a group of 7 engineers. Implemented the idea of Agile development, familiar with CI/CD and DevOps process.

        * Architected and built out a pipeline infrastructure with GitLab Webhook + Jenkins + Docker to leverage automation to prevent potential troubles.

        * Revamped the back-end/front-end structure with React / SpringBoot + MongoDB to increase search speed by 30%.

  - title: Software Engineer Intern
    company: Hikvision
    company_url: ''
    company_logo: hikvision
    location: Hangzhou, China
    date_start: '2020-03-08'
    date_end: '2020-05-20'
    description: |2-
        * Developed an Auxiliary Platform (AP), used to audit submitted source code, documentation, etc., and authorize the permission-related configuration. 

        * Revised the back-end/front-end with Django + REST API / Vue + Element UI, visualized data report with ECharts.

        * Deployed micro-services and CI/CD pipeline with Jenkins and GitLab.


design:
  columns: '2'
---
