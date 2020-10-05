---
title: 렌파이 게임 메뉴 GUI
author: 션짱구
date: 2020-10-06 01:30:00 +0900
categories: [IT, Renpy]
tags: [renpy, game]     # TAG names should always be lowercase
toc: true
---

## 목표
- 렌파이 게임 메뉴 GUI의 구성 파악하기
- `use`와 `transclude` 문법 이해하기

이번 포스팅은 렌파이 [렌파이 카페 비모에 정리된 글](https://cafe.naver.com/vmo/1472)을 바탕으로 재구성하였다.

## 게임 메뉴 화면 구성
게임 메뉴는 다음 이미지 파일로 구성되어 있다.
1) `game-directory/game/gui/overlay/game_menu.png`
좌측에 하늘색 선이 들어가있는 반투명 이미지다. 렌파이에서 명령어를 통해 선을 그린 것이 아니고, 원래 이미지 파일에 그려져있다.
2) `game-directory/game/gui/game_menu.png`
1) 파일 아래에 비춰지는 이미지이다.

아래는 게임 메뉴의 `Preferences` 화면이다.
해당 메뉴 화면은 아래와 같이 구성되어 있다.
