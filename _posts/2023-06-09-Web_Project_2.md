---
layout: single
title:  "웹 미니 프로젝트 16조 회고"
categories: [Project]
tag: [InnovationCamp, 웹미니프로젝트, 협업] 
toc: true
toc_sticky: true
toc_label: 목차
toc_icon: "fas fa-mug-hot"
author_profile: false
search: true
use_math: true
published: false
sidebar:
    nav: "counts"
---

# [웹 미니 프로젝트 후 회고록] 
팀장으로서 미니프로젝트를 진행하면서 알게되거나 느낀점을 정리하였다.

## ◆ 주제 및 진행기간
- 주제: 소통이 가능한 프로필 페이지
- 2023/06/07 ~ 2023/06/09

## ◆ 구현한 기능들
- Create, Read, Update, Delete 기능을 프로필 화면에 대하여 구현
- 수정 기능 발현 시 새로운 화면으로 이동하여 수정할 수 있도록 함.
  - 수정 시에는 이전의 작성 값을 value로 띄워서 확인 후 수정할 수 있도록 하였다.
  - 수정 완료 버튼을 누르면 수정 값이 반영되고 홈페이지로 이동
  - 수정 취소를 누르면 수정 값 반영 없이 홈페이지로 이동할 수 있도록 하였다.
- 프로필 별로 '좋아요' 공감 기능을 추가하여 프로필에 반응을 표시하였다.   

## ◆ 잘된 점
- 한 테마(프로필)에 대하여 Create, Read, Update, Delete를 모두 구현
- '좋아요'같이 상호 소통가능한 기능을 구현
- 'gitflow' 협업에서 'github' + 집중 개발 형태로 전략을 수정하여 부족한 시간을 보충하고 프로젝트를 완성함.

## ◆ 부족했던 점
- github branch에 대해서 완전히 분산하여 개발하지 않고 실시간 소통을 통해 하나씩 기능을 구현하였음.
- API설계에 대하여 지속적으로 수정, 보완이 필요했으나 완전히 진행하지 못하였음.
- 한가지 기능에 여러명이 참여했기에 변수와 함수 명명에 대해 설정하지 않고 개발을 진행했음. 

## ◆ 생각해볼 것들
- 추가 가능한 기능들
  - 이미지 업로드, 조회, 수정, 삭제 기능
  - 각 프로필에 대한 댓글기능
  - 프로필 별로 화면을 이동하는 기능
- 보완할 점
  - 기획서 작성시 API 설계
  - DB 관계설정 지식
  - API, URL, 웹페이지에 대한 이해도


## ◇ 총평
처음이고 짧은 기간으로 인해 많은 기능을 개발하지는 못했지만, Github를 통한 협업을 경험하고 프로젝트를 완성하는 과정을 알 수 있었다.

## ◇ 참조
- 깃허브링크: https://github.com/YiHwanRyu/Web_MiniProject
- 프로젝트 기획서: https://yihwanryu.github.io/project/Web_Project_1/