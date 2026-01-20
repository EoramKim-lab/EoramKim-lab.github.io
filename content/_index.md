---
# 메인 페이지 설정
title: 
date: 2026-01-20
type: landing

sections:
  # 1. 히어로 섹션 (첫인상)
  - block: hero
    content:
      title: |
        Python Developer
        Portfolio
      image:
        filename: welcome.jpg  # 나중에 본인 대표 이미지로 교체 가능
      text: |
        <br>
        효율적인 코드와 문제 해결을 즐기는 개발자 **본인이름**입니다.
        주로 파이썬을 활용한 자동화 및 데이터 처리에 집중하고 있습니다.
    design:
      background:
        gradient_start: '#4bb4e3'
        gradient_end: '#2b94c3'
        text_color_light: true

  # 2. 최근 포스트 (블로그 글)
  - block: collection
    content:
      title: Latest Posts
      subtitle: '학습한 내용과 기술적인 고민들을 기록합니다.'
      text:
      count: 3
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: card
      columns: '1'

  # 3. 중간 구분선 (배경 이미지)
  - block: markdown
    content:
      title:
      subtitle: ''
      text: "꾸준히 성장하고 기록하는 개발자가 되겠습니다."
    design:
      columns: '1'
      background:
        image: 
          filename: coders.jpg
          filters:
            brightness: 0.5
          parallax: true
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['100px', '0', '100px', '0']

  # 4. 프로젝트 섹션 (포트폴리오 핵심)
  - block: collection
    content:
      title: Featured Projects
      subtitle: '직접 설계하고 구현한 프로젝트들을 소개합니다.'
      text: ""
      count: 5
      filters:
        folders:
          - project
    design:
      view: starter # 프로젝트 이미지와 설명이 잘 보이는 뷰
      columns: '2'

  # 5. 연락처로 연결되는 버튼 (CTA)
  - block: markdown
    content:
      title: Get In Touch
      subtitle:
      text: |
        저와 함께 협업하거나 궁금한 점이 있다면 언제든 연락 주세요.
        {{% cta cta_link="mailto:본인이메일@example.com" cta_text="이메일 보내기 →" %}}
    design:
      columns: '1'
---