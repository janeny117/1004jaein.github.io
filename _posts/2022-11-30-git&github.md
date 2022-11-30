---
title:  "Git & Github"
excerpt: "Git과 Github에 대해 알아보자. "

categories:
  - Blog
tags:
  - [Blog, jekyll, Github, Git]

toc: true
toc_sticky: true
 
date: 2022-11-30
last_modified_at: 2022-11-30
---
# 1. Git
## 1.Git이란?
    GIT이란 분산 버전관리 시스템이다. 컴퓨터 파일의 변경사항을 추적하고 여러명의 사용자들 간에 파일에 대한 작업을 조율하는 데 이용한다. 주로 여러명의 개발자가 하나의 프로젝트에 참여할 때 소스 코드를 관리하는 데 사용한다. 
## 2. Git 기본 명령어 
    - Repository: 저장소, 히스토리, 태그, 소스의 가지치기, branch에 따라 버전 저장. 작업자가 변경한 모든 히스토리 확인 가능  
    - Working Tree : 저장소를 바라보는 작업자의 현재 시점  
    - Staging Area: 커밋을 준비하는 위치
    - Commit: 현재 변경된 작업 상태를 점검을 마치면 확정하고 저장소에 저장하는 작업   
    - Head: 현재 작업하고 있는 Branch  
    - Branch: 가지 또는 분기점.   
    - Merge: 다른 Branch의 내용을 현재 Branch로 가져와 합치는 작업  


## 3. Git 기본 명령어
    - git help: 도움말 기능  
    - git init: 저장소 초기화  
    - git status: 저장소 상태 확인  
    - git branch: 새로운 브랜치 생성  
    - git add: staging 영역에 변경내용 추가   
    - git commit: staging area에 있는 변경 내용 묶음 정의  
    - git log: 커밋 내역 확인  
    - git push: 로컬 컴퓨터에서 서버로 변경사항 push  
    - git pull: 서버 저장소로부터 최신 내용을 로컬 컴퓨터로 복사  
    - git checkout: 작업하길 원하는 브랜치로 이동   
    - git merge: 개별 branch에서 마친 작업을 master branch로 병합


참고 : https://git-scm.com/book/ko/v2


# 2. Github
## 1. Github이란
    github은 git을 이용하는 웹호스팅 서비스이다. 버전 관리와 협업을 위한 코드 웹 호스팅 플랫폼으로, 언제, 어디서나 협업 프로젝트를 진행할 수 있도록 돕는다. 

## 2. 사용법
1. repository 생성
<img src="사진 업로드/create_repository.png" width="400">

2. git clone 저장소 주소
<img src="사진 업로드/clone.png" width="400">

3. git add로 변경 추가
<img src="사진 업로드/add.png" width="400">

4. git commit으로 메세지 남기기
 <img src="사진 업로드/commit.png" width="400">

5. git push로 원격저장소로 push
<img src="사진 업로드/push.png" width="400">
