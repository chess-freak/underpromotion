---
layout: default
title: Blog
navigation:
  - name: "홈"
    link: "/"
  - name: "블로그"
    link: "/blog/"
---

<section class="section blog-index">
  <div class="container">
    <h1 class="section-title">블로그</h1>
    <p class="blog-home-description text-center">
      작업 중 떠오른 생각과 배운 것들을 주제에 구애받지 않고 정리합니다.
    </p>
    {% include blog_list.html %}
  </div>
</section>
