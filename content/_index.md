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

  # 1.5. Professor (교수 소개) 구역 - 버그 및 태그 노출 완벽 우회 버전
  - block: markdown
    id: about
    content:
      title: 'Professor'
      subtitle: ''
      text: |
        <div style="display: flex; gap: 50px; margin-top: 30px; align-items: flex-start; text-align: left; flex-wrap: wrap;">
          <!-- 왼쪽: 프로필 사진 및 성함 -->
          <div style="flex: 1; min-width: 250px; text-align: center;">
            <img src="uploads/professor.jpg" style="width: 200px; height: 200px; border-radius: 50%; object-fit: cover; border: 3px solid #fff; box-shadow: 0 4px 10px rgba(0,0,0,0.1);" alt="Shin Ki-yeol">
            <h2 style="font-size: 1.8rem; margin-top: 15px; margin-bottom: 5px; color: #222; font-weight: 700;">Shin Ki-yeol (신기열)</h2>
            <p style="color: #666; margin-bottom: 15px;">Professor of Mechanical Engineering</p>
            <p style="color: #888; font-size: 0.9rem; margin-bottom: 20px;">Yeungnam University</p>
            <div style="display: flex; gap: 10px; justify-content: center;">
              <a href="mailto:교수님메일@yu.ac.kr" style="width: 40px; height: 40px; border-radius: 50%; background: #fff; display: flex; align-items: center; justify-content: center; box-shadow: 0 2px 5px rgba(0,0,0,0.1); color: #444; text-decoration: none;">✉️</a>
              <a href="https://scholar.google.com" target="_blank" style="width: 40px; height: 40px; border-radius: 50%; background: #fff; display: flex; align-items: center; justify-content: center; box-shadow: 0 2px 5px rgba(0,0,0,0.1); color: #444; text-decoration: none; font-weight: bold;">G</a>
            </div>
          </div>
          <!-- 오른쪽: 요약, 학력, 연구분야 -->
          <div style="flex: 2; min-width: 300px;">
            <h3 style="font-size: 1.4rem; color: #222; border-bottom: 2px solid #eee; padding-bottom: 8px; margin-bottom: 15px; font-weight: 600;">📝 Professional Summary</h3>
            <p style="line-height: 1.8; color: #444; margin-bottom: 30px;">
              신기열 교수님은 영남대학교 기계공학부 에너지공학 연구실(EEL)의 지도교수로서, 고도화된 열관리 및 에너지 시스템 설계, 엔지니어링 시뮬레이션 해석 분야의 최첨단 국책 과제 및 산학 연구를 총괄하고 계십니다.
            </p>
            <h3 style="font-size: 1.4rem; color: #222; border-bottom: 2px solid #eee; padding-bottom: 8px; margin-bottom: 15px; font-weight: 600;">🎓 Education</h3>
            <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 15px; margin-bottom: 30px;">
              <div style="background: #fff; padding: 15px; border-radius: 8px; box-shadow: 0 2px 8px rgba(0,0,0,0.05); border: 1px solid #f0f0f0;">
                <strong style="color: #222; display: block; margin-bottom: 5px;">Ph.D. in Mechanical Engineering</strong>
                <span style="font-size: 0.9rem; color: #666;">영남대학교 (2012)</span>
              </div>
              <div style="background: #fff; padding: 15px; border-radius: 8px; box-shadow: 0 2px 8px rgba(0,0,0,0.05); border: 1px solid #f0f0f0;">
                <strong style="color: #222; display: block; margin-bottom: 5px;">M.S. in Mechanical Engineering</strong>
                <span style="font-size: 0.9rem; color: #666;">영남대학교 (2008)</span>
              </div>
              <div style="background: #fff; padding: 15px; border-radius: 8px; box-shadow: 0 2px 8px rgba(0,0,0,0.05); border: 1px solid #f0f0f0;">
                <strong style="color: #222; display: block; margin-bottom: 5px;">B.S. in Mechanical Engineering</strong>
                <span style="font-size: 0.9rem; color: #666;">영남대학교 (2006)</span>
              </div>
            </div>
            <h3 style="font-size: 1.4rem; color: #222; border-bottom: 2px solid #eee; padding-bottom: 8px; margin-bottom: 15px; font-weight: 600;">✨ Interests</h3>
            <div style="display: flex; gap: 10px; flex-wrap: wrap;">
              <span style="background: #fff; padding: 6px 15px; border-radius: 20px; font-size: 0.9rem; color: #444; box-shadow: 0 2px 5px rgba(0,0,0,0.05); border: 1px solid #e8e8e8;">Thermal Management</span>
              <span style="background: #fff; padding: 6px 15px; border-radius: 20px; font-size: 0.9rem; color: #444; box-shadow: 0 2px 5px rgba(0,0,0,0.05); border: 1px solid #e8e8e8;">Energy Systems Simulation</span>
              <span style="background: #fff; padding: 6px 15px; border-radius: 20px; font-size: 0.9rem; color: #444; box-shadow: 0 2px 5px rgba(0,0,0,0.05); border: 1px solid #e8e8e8;">Advanced Thermal Stress Analysis</span>
              <span style="background: #fff; padding: 6px 15px; border-radius: 20px; font-size: 0.9rem; color: #444; box-shadow: 0 2px 5px rgba(0,0,0,0.05); border: 1px solid #e8e8e8;">Fluid & Thermal Engineering</span>
            </div>
          </div>
        </div>
    design:
      columns: '1'
      background:
        gradient_mesh:
          enable: false

  # 2. Members (연구원 소개) 구역
  - block: markdown
    id: people
    content:
      title: 'Members'
      subtitle: ''
      text: |-
        ## Research Prof. & Post Doc.

        <div style="display: flex; gap: 30px; margin-top: 30px; margin-bottom: 45px; align-items: flex-start; text-align: left;">
          <img src="uploads/liu-jie.jpg" style="width: 160px; border: 1px solid #ddd; border-radius: 4px;" alt="Liu Jie">
          <div style="line-height: 1.9;">
            <strong style="font-size: 1.25rem; color: #222;">Liu Jie (박사), Ph.D.</strong>
            <ul style="list-style-type: '☉ '; padding-left: 20px; margin-top: 10px; color: #444;">
              <li><b>Research Topic :</b> 연구 분야 및 주제</li>
              <li><b>Email :</b> liujie@example.com</li>
              <li><b>TEL :</b> 053-810-XXXX</li>
              <li><b>Location :</b> 기계관 XXX호</li>
            </ul>
          </div>
        </div>

        <hr style="border: 0; height: 1px; background: #eee; margin-bottom: 40px;">

        ## Undergraduate Researchers

        <div style="display: flex; gap: 30px; margin-bottom: 45px; align-items: flex-start; text-align: left;">
          <img src="uploads/student1.jpg" style="width: 160px; border: 1px solid #ddd; border-radius: 4px;" alt="Student 1">
          <div style="line-height: 1.9;">
            <strong style="font-size: 1.25rem; color: #222;">학부연구생 1</strong>
            <ul style="list-style-type: '☉ '; padding-left: 20px; margin-top: 10px; color: #444;">
              <li><b>Research Topic :</b> 참여 연구 과제</li>
              <li><b>Email :</b> student1@gmail.com</li>
              <li><b>TEL :</b> 010-XXXX-XXXX</li>
              <li><b>Location :</b> 기계관 XXX호</li>
            </ul>
          </div>
        </div>

        <div style="display: flex; gap: 30px; margin-bottom: 45px; align-items: flex-start; text-align: left;">
          <img src="uploads/student2.jpg" style="width: 160px; border: 1px solid #ddd; border-radius: 4px;" alt="Student 2">
          <div style="line-height: 1.9;">
            <strong style="font-size: 1.25rem; color: #222;">학부연구생 2</strong>
            <ul style="list-style-type: '☉ '; padding-left: 20px; margin-top: 10px; color: #444;">
              <li><b>Research Topic :</b> 참여 연구 과제</li>
              <li><b>Email :</b> student2@gmail.com</li>
              <li><b>TEL :</b> 010-XXXX-XXXX</li>
              <li><b>Location :</b> 기계관 XXX호</li>
            </ul>
          </div>
        </div>

        <div style="display: flex; gap: 30px; margin-bottom: 45px; align-items: flex-start; text-align: left;">
          <img src="uploads/student3.jpg" style="width: 160px; border: 1px solid #ddd; border-radius: 4px;" alt="Student 3">
          <div style="line-height: 1.9;">
            <strong style="font-size: 1.25rem; color: #222;">학부연구생 3</strong>
            <ul style="list-style-type: '☉ '; padding-left: 20px; margin-top: 10px; color: #444;">
              <li><b>Research Topic :</b> 참여 연구 과제</li>
              <li><b>Email :</b> student3@gmail.com</li>
              <li><b>TEL :</b> 010-XXXX-XXXX</li>
              <li><b>Location :</b> 기계관 XXX호</li>
            </ul>
          </div>
        </div>

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
