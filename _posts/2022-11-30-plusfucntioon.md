---
title:  "Google Analytics"
excerpt: "Google Analytics 기능 삽입하는 방법을 알아보자."

categories:
  - Blog
tags:
  - [Blog, jekyll, Github, Git]

toc: true
toc_sticky: true
 
date: 2022-11-30
last_modified_at: 2022-11-30
---
# 1. 계정 생성
1. https://analytics.google.com/에 접속해 계정을 생성한다.
2. 데이터 스트림 항목에 접속해 블로그 주소 입력 후 스트림 추가한다.

![ga1](https://user-images.githubusercontent.com/105484114/204743087-0412b52d-4a21-4f7f-8632-77012ccfa76f.png)
3. ID확인 

# 2. 블로그에 적용
1. 추적 ID를 확인해 복사한다.
2. _config.yml 파일에 들어가 내용을 수정한다.
![ga3](https://user-images.githubusercontent.com/105484114/204745052-11f07a62-a03f-4fbd-b223-2f2aac5ac57d.png)
3. 그 후 google analytics에 접속해 확인하면 분석이 되는 것을 확인할 수 있다. 
![ga4](https://user-images.githubusercontent.com/105484114/204747865-1c6f5c47-0c76-4659-abb2-61fe5ab3a9a1.png)
