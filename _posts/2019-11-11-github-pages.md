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
### GitHub Pages : [공식 사이트](https://pages.github.com/)
GitHub에서 2008년 말부터 제공하는 정적 웹사이트(static websites) 호스팅 서비스다.
그냥 쉽게 GitHub에서 운영하는 블로그 서비스라고 이해하고 있자... 
왜? 나는 블로그를 만들기 위해 사용할 테니까!!

### 지킬(Jekyll) : [공식 사이트](https://jekyllrb-ko.github.io/)
루비(Ruby)(<https://www.ruby-lang.org/ko>)로 만든 정적 웹사이트 생성기(static websites generator)로 HEXO(<https://hexo.io/ko>)와 함께 가장 많이 사용하고 있다.
GitHub는 markdown 파일포맷을 지원하는데, 이 파일포맷으로 글을 작성하면 지킬이 자동으로 html 포맷으로 변환해 준다.
블로그를 만들기 위해  맨 땅에 헤딩해서 쌩~고생을 하는것을 막아주는 고마운 존재이다.
지킬을 성공적으로 설치한 후,   
좀 더 쉽게 관리하기 위해서 Jekyll plugin중 [Jekyll  Admin](https://github.com/jekyll/jekyll-admin)도 설치해 둔다.  
현재까지는 약간씩의 버그들이 있는거 같기는 한데,  없는것 보단 나으니 감안하고 사용한다.

Usage
Start Jekyll as you would normally :  
bundle exec jekyll serve   
Navigate to http://localhost:4000/admin   to access the administrative interface  

### 젬(Gem): 
분산 패키지 시스템으로 라이브러리의 작성이나 공개, 설치를 도와주는 시스템이다.  
루비(Ruby)는 젬(gem)을 사용하여 라이브러리 설치를 편하게 설치, 관리할 수 있다.  

### Gemfile & Bundler:
`Gemfile`은 다양한 젬(gem)들을 등록하는 파일로서 종속성을 구성하는 표준 방법이다. 그래서 설치가 필요한 젬(gem)파일들을 여기에 등록해놓고 사용하면 된다.  
`Gemfile.lock` 은 실제로 인스톨된 Gem과 의존관계가 있는 Gem이 기술된 파일이다.

Gemfile 업데이트 -> bundle install 실행 -> Gemfile.lock 자동갱신  
`일단, 특별히 건드릴 일은 없는 파일이다.`

`Bundler`는 Gemfile에 정의된 젬(gem)들의 의존성을 파악해서 올바른 젬(gem)을 사용할 수 있게끔 해주는 관리툴이라 할 수 있다. 즉, 필요한 정확한 gem과 버전을 추적하고 설치하여 루비 프로젝트를 위한 일관된 환경을 제공해 준다. 특정 gem의 의존성을 관리하거나, 환경에따라 버전을 바꿔볼때 버전을 관리 하거나 한다. Bundler또한 RubyGems(gem)의 하나이다.

~~~
gem install bundler
bundle install
~~~

결론적으로,  
**Gemfile 에 필요한 젬(gem)들을 추가하고 -> Bundler로 인스톨(bundle install)해서 사용하면 된다.**


### 헥소?(Hexo): [공식사이트](https://hexo.io/ko/)
Node.js(<https://nodejs.org>)로 만든 정적 웹사이트 생성기(static websites generator)로 Jekyll 과 함께 많이 사용되고 있는듯 하다.  
Jekyll에 gem 이 있다면 Hexo에는 npm 이 있다. 따라서 처음 설치나 세팅을 제외하면  
그외 GitHub Blog(username.github.io)를 만들기 위한 과정은 비슷하다.  
그러므로 각자 이리저리 검색해 보고 입맛에 맞는걸 선택하면 된다.