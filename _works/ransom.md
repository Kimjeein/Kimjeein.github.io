---
# preview details
layout: works-single
title: 랜섬웨어 프로젝트 구조 분석과 대응 방안
category: malware
category_slug: malware
image: assets/img/works/ransom.png
short_description: 암호화 기반 랜섬웨어를 직접 구현하고 분석함으로써 공격과 방어 양측 시점에서 사이버보안 대응 전략을 도출한 프로젝트

# full details
# live_preview: https://bslthemes.com
full_image: assets/img/works/ransom1.png
info:
  - label: Year
    value: 2025

  - label: Category
    value: Cybersecurity

description1:
  show: yes
  title: Project Goal
  text: |
    <p>본 프로젝트는 랜섬웨어의 작동 원리와 구조를 이해하고, 모의 환경에서 간단한 형태의 암호화 기반 랜섬웨어를 직접 구현 및 분석한 사례를 담고 있습니다.</p>
    <p>공격자와 방어자의 시점을 동시에 경험함으로써, 실무 중심의 보안 사고를 키우는 데에 중점을 두었습니다. 암호화 대상 탐색, 파일 암호화 및 삭제, 랜섬노트 생성 등의 흐름을 실제로 구현하고, 가상 환경 내에서 그 영향을 분석했습니다.</p>
    <p>특히 백업 정책, 파일 무결성, 실시간 감시 등 방어 전략의 중요성을 체감하며, 향후 보안 대응 전략 수립 시 고려해야 할 점들을 구체적으로 도출했습니다.</p>

gallery:
  - assets/img/works/ransom1.png
  - assets/img/works/ransom3.png
  - assets/img/works/ransom4.png
  - assets/img/works/ransom5.png

description2:
  title: Features & Flow
  text: |
    <ul>
      <li><strong>Python 기반 간단한 파일 암호화/복호화 로직 구현</strong></li>
      <li>대상 디렉토리 탐색 및 AES 기반 암호화 처리</li>
      <li>원본 파일 삭제 및 `.locked` 확장자 생성</li>
      <li>랜섬노트 자동 생성 및 바탕화면 배치</li>
      <li>실시간 로그 생성 및 감염 시간 기록</li>
    </ul>
    <p>테스트는 텍스트, 이미지, 문서 파일이 포함된 모의 디렉토리를 구성하여 진행하였으며, 복호화 실패 시 데이터 손실 가능성까지 포함하여 시뮬레이션했습니다.</p>
    <p>감염 행위 분석을 위해 Wireshark, Process Explorer, Sysinternals 등의 도구를 활용하였고, 실행 흐름 및 이상 행위 탐지를 중심으로 패턴을 정리했습니다.</p>

video:
  poster: assets/img/works/ransom.png
  id: Gu6z6kIukgg
---
