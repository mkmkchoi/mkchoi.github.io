# MK Choi IT Column

GitHub Pages에 IT/AI 관련 글을 길게 정리하고, LinkedIn과 리멤버에는 요약과 원문 링크를 공유하기 위한 개인 칼럼 저장소입니다.

## Structure

- `_posts/`: Markdown 원고를 저장합니다.
- `_layouts/`: 공통 페이지와 글 레이아웃입니다.
- `assets/css/main.css`: 사이트 스타일입니다.
- `assets/images/`: 글 대표 이미지와 공유용 이미지를 둡니다.

## Writing a Post

새 글은 `_posts/YYYY-MM-DD-slug.md` 형식으로 추가합니다.

```md
---
title: "글 제목"
description: "공유 링크에 노출될 짧은 설명"
date: 2026-06-21
category: AI Engineering
permalink: /2026-06-transformer-fine-tuning/
image: /assets/images/transformer-fine-tuning-hero.png
linkedin_summary: |
  LinkedIn에 올릴 3-5문장 요약을 여기에 둡니다.
remember_summary: |
  리멤버에 맞춘 더 짧고 실무적인 요약을 여기에 둡니다.
---

본문을 작성합니다.
```

## Publishing Flow

1. GitHub Pages에 자세한 글을 작성합니다.
2. 글의 `linkedin_summary`, `remember_summary`를 다듬습니다.
3. LinkedIn과 리멤버에는 요약과 GitHub Pages 원문 링크를 함께 게시합니다.

First post URL:

<https://mkmkchoi.github.io/posts/2026-06-transformer-fine-tuning/>
