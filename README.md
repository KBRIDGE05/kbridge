# KBRIDGE Jekyll Blog Site

이 폴더는 GitHub Pages에서 사용할 수 있는 케이브릿지 Jekyll 기반 블로그 구조입니다.

현재 샘플 글은 모두 제거되어 있습니다.  
실제 글을 `_posts` 폴더에 추가하면 메인 화면의 최신 글 영역과 `/blog/` 목록 페이지에 자동으로 표시됩니다.

## HTML 글 추가 방법

`_posts` 폴더에 아래 형식으로 HTML 파일을 추가하세요.

```text
YYYY-MM-DD-title.html
```

예시:

```text
2026-06-09-lcl-shipping-guide.html
```

파일 내용 예시:

```html
---
layout: post
title: "LCL 해상운송 처음 진행할 때 확인해야 할 5가지"
category: "물류정보"
date: 2026-06-09
description: "소량 수입 화물을 진행하기 전 CBM, 창고료, 통관, 국내운송 기준을 쉽게 정리했습니다."
---

<h2>1. LCL은 어떤 화물에 적합할까?</h2>
<p>LCL은 컨테이너 한 대를 채우기 어려운 소량 화물을 다른 화주의 화물과 함께 운송하는 방식입니다.</p>

<h2>2. 문의 전에 확인해야 할 정보</h2>
<ul>
  <li>품명</li>
  <li>박스 수량</li>
  <li>박스별 규격</li>
  <li>총중량</li>
  <li>출발지와 도착지</li>
</ul>
```

## Markdown 글도 가능

```text
2026-06-09-title.md
```

## GitHub Pages 설정

GitHub 저장소에 업로드 후 Settings → Pages에서 배포 브랜치를 선택하면 됩니다.


## 블로그 카테고리

카테고리는 `물류정보` 또는 `시황·정책`만 사용합니다.
