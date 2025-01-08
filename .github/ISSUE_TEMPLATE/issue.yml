name: '이슈 생성'
description: 'Repo에 이슈를 생성하며, 생성된 이슈는 Jira와 연동됩니다.'
labels: [feat]
title: '이슈 이름을 작성해주세요'
body:
  - type: input
    id: parentKey
    attributes:
      label: '🎟️ 상위 작업 (Ticket Number)'
      description: '상위 작업의 Ticket Number를 기입해주세요'
      placeholder: 'PRJ-00'
    validations:
      required: true

  - type: input
    id: branch
    attributes:
      label: '🌳 브랜치명 (Branch)'
      description: '영어로 브랜치명을 작성해주세요'
    validations:
      required: true
      
  - type: input
    id: description
    attributes:
      label: '📝 상세 내용(Description)'
      description: '이슈에 대해서 간략히 설명해주세요'
    validations:
      required: true

  - type: textarea
    id: tasks
    attributes:
      label: '✅ 체크리스트(Tasks)'
      description: '해당 이슈에 대해 필요한 작업목록을 작성해주세요'
      value: |
        - [ ] Task1
        - [ ] Task2
    validations:
      required: true

출처: https://lamerry.tistory.com/entry/프로젝트에서-Jira-사용하기-3-Github-Actions로-GithubJira-이슈-자동화?category=1265013 [시니유의 개발 블로그:티스토리]
