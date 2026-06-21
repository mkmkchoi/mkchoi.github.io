---
layout: default
title: MK Choi IT Column
description: IT와 AI 개발 주제를 자세히 정리하고, LinkedIn과 리멤버에는 핵심 요약과 원문 링크를 공유합니다.
---

<section class="home-hero">
  <p class="eyebrow">IT Column Archive</p>
  <h1>기술을 실무 언어로 다시 정리합니다.</h1>
  <p>AI 개발, 소프트웨어 엔지니어링, 생산성 도구, 개발 워크플로를 긴 글로 정리하는 공간입니다. 외부 채널에는 짧게 공유하고, 자세한 맥락과 체크리스트는 이곳에 남깁니다.</p>
</section>

<section class="post-list" aria-labelledby="latest-posts">
  <h2 class="section-title" id="latest-posts">Latest Posts</h2>
  <div class="post-grid">
    {% for post in site.posts %}
      <a class="post-card" href="{{ post.url | relative_url }}">
        {% if post.image %}
          <img src="{{ post.image | relative_url }}" alt="{{ post.title }} 대표 이미지">
        {% endif %}
        <div class="post-card-body">
          <time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%Y.%m.%d" }}</time>
          <h2>{{ post.title }}</h2>
          <p>{{ post.description }}</p>
        </div>
      </a>
    {% endfor %}
  </div>
</section>
