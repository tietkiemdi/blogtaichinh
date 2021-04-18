---
layout: defaults/page
permalink: index.html
narrow: true
title: Welcome to Tietkiemdi
---


## Cách bắt đầu con đường độc lập tài chính

Blog này chuyên viết về tài chính cá nhân. Các bạn có thể tìm thấy các công thức tiết kiệm tiền, tạo thu nhập và độc lập tài chính.

[The documentation]({{ site.baseurl }}{% link list/projects.md %}) Các công thức về tài chính rất dễ áp dụng.

[The blog]({{ site.baseurl }}{% link list/posts.html %}) List bài viết hàng ngày update liên tục. Cung cấp cho độc giả nhiều kiến thức hay về tài chính cá nhân

<hr />

### Bài viết mới nhất

{% for post in site.posts limit:3 %}
{% include components/post-card.html %}
{% endfor %}


