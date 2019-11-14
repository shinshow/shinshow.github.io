---
title: GitHub Pages 란?
layout: single
author_profile: true
read_time: true
comments: true
share: true
related: true
excerpt: GitHub Pages 용어정리
categories:
- GitHub Pages
tags:
- GitHub
- 깃허브
- 블로그
last_modified_at: 2019-11-11T17:58
---

# 용어 정리
### GitHub Pages : [깃허브 페이지 공식 사이트](https://pages.github.com/)
GitHub에서 2008년 말부터 제공하는 정적 웹사이트(static websites) 호스팅 서비스다.
그냥 쉽게 GitHub에서 운영하는 블로그 서비스라고 이해하고 있자... 
왜? 나는 블로그를 만들기 위해 사용할 테니까!!

### 지킬(Jekyll) : [지킬 공식 사이트](https://jekyllrb-ko.github.io/)
루비(Ruby)로 만든 정적 웹사이트 생성기(static websites generator)로 HEXO와 함께 가장 많이 사용하고 있다.
GitHub는 markdown 파일포맷을 지원하는데, 이 파일포맷으로 글을 작성하면 지킬이 자동으로 html 포맷으로 변환해 준다.
블로그를 만들기 위해  맨 땅에 헤딩해서 쌩~고생을 하는것을 막아주는 고마운 존재이다.
지킬을 성공적으로 설치한 후,   
좀 더 쉽게 관리하기 위해서 Jekyll plugin중   
[Jekyll  Admin](https://github.com/jekyll/jekyll-admin)도 설치해 둔다.  
현재까지는 약간씩의 버그들이 있는거 같기는 한데,  없는것 보단 나으니 감안하고 사용한다.

Usage
Start Jekyll as you would normally :  
bundle exec jekyll serve   
Navigate to http://localhost:4000/admin   to access the administrative interface  

### 젬(gem): 
분산 패키지 시스템으로 라이브러리의 작성이나 공개, 설치를 도와주는 시스템이다.  
루비(Ruby)는 젬(gem)을 사용하여 라이브러리 설치를 편하게 설치, 관리할 수 있다.