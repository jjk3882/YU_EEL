---
title: 'Energy Engineering Laboratory'
summary: ''
date: 2026-06-01
type: landing

sections:
  # 1. 메인 소개 대문 구역
  - block: markdown
    content:
      title: 'Energy Engineering Laboratory (EEL)'
      subtitle: 'Yeungnam University'
      text: |-
        영남대학교 기계공학부 **에너지공학 연구실(EEL)**에 오신 것을 환영합니다. 
        우리 연구 그룹은 신기열 교수님의 지도 아래 열관리 및 에너지 시스템(Thermal Management and Energy Systems) 분야의 최첨단 시뮬레이션 및 설계 연구를 수행하고 있습니다. 
        관련 분야에 경험이 있거나 관심 있는 대학원생 및 학부 연구생을 모집하고 있으니 언제든 연락 바랍니다.

        Welcome to the Energy Engineering Laboratory (EEL) at Yeungnam University. Our research group, led by Prof. Shin Ki-yeol, focuses on comprehensive studies, engineering simulations, and advanced thermal management and energy system designs.

        ---

        ### 📍 Contact Information
        * **교수연구실 (신기열 교수님):** 053-810-XXXX / 교수님 이메일
        * **학생연구실 (연구원실):** 053-810-XXXX / 랩실 이메일
    design:
      columns: '1'
      background:
        gradient_mesh:
          enable: true

  # 2. Members (연구원 소개) 구역 - 4명 일렬 나열 버전
  - block: collection
    id: people
    content:
      title: 'Members'
      subtitle: 'Our Research Team'
      text: ''
      count: 50
      filters:
        folders:
          - authors
      view: card
    design:
      columns: '1'

  # 3. Research (연구 과제/프로젝트) 구역
  - block: collection
    id: projects
    content:
      title: 'Research'
      subtitle: 'Projects & Laboratory Interests'
      text: ''
      count: 50
      filters:
        folders:
          - project
      view: card
    design:
      columns: '1'

  # 4. Lectures (강의 자료/Teaching) 구역
  - block: collection
    id: experience
    content:
      title: 'Lectures'
      subtitle: 'Academic Courses & Teaching'
      text: ''
      count: 50
      filters:
        folders:
          - experience
      view: card
    design:
      columns: '1'

  # 5. Publications (논문 및 발표자료) 구역
  - block: collection
    id: publications
    content:
      title: 'Publications'
      subtitle: 'Recent Research Papers & Presentations'
      text: ''
      count: 50
      filters:
        folders:
          - publications
      view: citation
    design:
      columns: '1'
---
