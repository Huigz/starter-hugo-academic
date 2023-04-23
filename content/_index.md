---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: '**Academic.<br>jmsu.me**'
      image:
        filename: network.png
      cta:
        label: '**Get Started**'
        url: /post
      cta_alt:
        label: About Methodology  
        url: /methodology
      cta_note:
        label:
          使用Hugo Academic主题生成 托管于Netlify<br>
          Made by Hugo Academic theme on Netlify
          
      text: |-
        
        <br>
        <br>
        这里包含了有关 社会学 数据科学相关的知识内容
        
        여기 사회학 데이터사이언스용합 지식을 포함되었다
        <br>
        <br>
        <!--Custom spacing-->
        <div class="mb-5"></div>
        <!--GitHub Button JS-->
        <script async defer src="https://buttons.github.io/buttons.js"></script>
    design:
      background:
        gradient_end: '#30cfd0'
        gradient_start: '#330867'
        text_color_light: true
        
  - block: about.avatar
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your bio text from `authors/admin/_index.md`?
      text:
  - block: features
    content:
      title: Skills
      items:
        - name: Python
          description: Pandas, Plotly, Networkx 
          icon: python
          icon_pack: fab
        - name: Sociology theory
          description: Exchange theory, Social Netowrk Analysis
          icon: chart-line
          icon_pack: fas
        - name: Programming 
          description: Flutter, Flask, HTML, tailwindCSS, Echarts
          icon: chrome
          icon_pack: fab
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
        - title: 학부생
          company: 성균관대
          company_url: 'https://www.skku.edu'
          company_logo: skku
          location: 서울
          date_start: '2018-09-01'
          date_end: '2023-02-01'
          description: |2-
              Responsibilities include:

              * 사회학
              * 소프트웨어용합
            
        - title: 대학원생
          company: 성균관대
          company_url: 'https://www.skku.edu'
          company_logo: skku
          location: 서울
          date_start: '2023-03-01'
          date_end: ''
          description: 사회학전공으로 열심히 공부하는 중
    design:
      columns: '2'

  - block: collection
    id: posts
    content:
      title: Recent Posts
      subtitle: ''
      text: ''
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        folders:
          - post
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: compact
      columns: '2'
  
  - block: markdown
    content:
      title: My Life
      subtitle: 'with JINQU & Pudding'
      text: |-
        {{< gallery album="mylife" >}}
    design:
      columns: '1'

  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis ut magna et, vehicula efficitur enim.
      # Contact (add or remove contact options as necessary)
      email: test@example.org
      phone: 888 888 88 88
      appointment_url: 'https://calendly.com'
      address:
        street: 450 Serra Mall
        city: Stanford
        region: CA
        postcode: '94305'
        country: United States
        country_code: US
      directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
      office_hours:
        - 'Monday 10:00 to 13:00'
        - 'Wednesday 09:00 to 10:00'
      contact_links:
        - icon: twitter
          icon_pack: fab
          name: DM Me
          link: 'https://twitter.com/Twitter'
        - icon: skype
          icon_pack: fab
          name: Skype Me
          link: 'skype:echo123?call'
        - icon: video
          icon_pack: fas
          name: Zoom Me
          link: 'https://zoom.com'
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
