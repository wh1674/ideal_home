---
title: Contact
date: 2022-10-24

type: landing

sections:
  - block: contact
    content:
      title: IDEAL
      text: |-
        IDEA 연구실에서는 반도체 칩으로 구현되는 System-on-Chip (SoC) 아키텍처와 설계 기술에 관련된 하드웨어와 소프트웨어에서의 다양한 문제들을 연구하고 있습니다. 최근 우리는 빅 데이터와 인공지능 어플리케이션에서 기인하는 메모리 및 스토리지 데이터 병목현상을 해결하기 위한 지능형 데이터 중심 컴퓨팅 아키텍처, optical link를 포함하는 차세대 온칩 인터커넥트 등의 분야에서 시스템 레벨 연구에 초점을 맞추고 있습니다.
        
      email: test@example.org
      phone: 888 888 88 88
      address:
        street: 450 Serra Mall
        city: Stanford
        region: CA
        postcode: '94305'
        country: United States
        country_code: US
      coordinates:
        latitude: '37.4275'
        longitude: '-122.1697'
      directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
      office_hours:
        - 'Monday 10:00 to 13:00'
        - 'Wednesday 09:00 to 10:00'
      appointment_url: 'https://calendly.com'
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
          filename: contact.jpg
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
