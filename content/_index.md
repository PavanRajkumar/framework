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
      username: admin
      # Override your bio text from `authors/admin/_index.md`?
      text:

  ############################################################################################################

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
        - title: Hardware Engineering Intern
          company: LinkedIn
          company_url: 'https://www.linkedin.com/company/linkedin/'
          company_logo: linkedin_logo
          location: Sunnyvale
          date_start: '2023-05-01'
          date_end: ''
          description: |2-
            [In]coming Hardware Engineering Intern.

        - title: Systems Administrator
          company: University of Southern California
          company_url: 'https://www.linkedin.com/school/university-of-southern-california/'
          company_logo: usc_logo
          location: Los Angeles
          date_start: '2022-01-01'
          date_end: ''
          description: I support research applications and servers with over 25,000 users globally.

        - title: Systems Administrator
          company: Information Sciences Institute
          company_url: 'https://www.linkedin.com/company/information-sciences-institute/'
          company_logo: isi_logo
          location: Marina Del Ray
          date_start: '2022-06-01'
          date_end: '2022-08-01'
          description: SysAdmin for cutting-edge cyber security and network research testbeds.

        - title: Associate Product Developer
          company: Epicor Software
          company_url: 'https://www.linkedin.com/company/epicor/'
          company_logo: epicor_logo
          location: Bangalore
          date_start: '2021-01-01'
          date_end: '2021-12-01'
          description: Full Stack developer and Automation Engineer.

        - title: Software Engineer Intern
          company: Eurofins Scientific
          company_url: 'https://www.linkedin.com/company/eitsi/'
          company_logo: eurofins_logo
          location: Bangalore
          date_start: '2020-02-01'
          date_end: '2020-12-01'
          description: Developed a tool to predict bug-inducing risk of git commits using Machine Learning and Explainable AI.
    design:
      columns: '2'

  ############################################################################################################
    
  - block: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Certifications'
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url: https://www.credly.com/badges/585f5b7f-5bd1-403f-ab44-eb837e94d2d9
          date_end: ''
          date_start: '2021-12-16'
          description: 'Earners of this certification have a comprehensive understanding of AWS services and technologies. They demonstrated the ability to build secure and robust solutions using architectural design principles based on customer requirements. Badge owners are able to strategically design well-architected distributed systems that are scalable, resilient, efficient, and fault-tolerant.'
          organization: Amazon Web Services
          organization_url: https://www.linkedin.com/company/amazon-web-services/
          title: AWS Certified Solutions Architect – Associate
          url: ''
    design:
      columns: '2'
    
  ############################################################################################################

  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-

      # Contact (add or remove contact options as necessary)
      email: pavanraj.m14@gmail.com
      address:
        street: 3740 McClintock Avenue
        city: Los Angeles
        region: CA
        postcode: '90089'
        country: United States
        country_code: US
      directions: Room EEB 422, 4th Floor
      # Automatically link email and phone or display as text?
      autolink: true

    design:
      columns: '2'
---
