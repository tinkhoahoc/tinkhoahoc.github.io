---
date: 2023-04-24
layout: post
title: Các công cụ nhận dạng văn bản viết bằng ChatGPT có sai số cao
subtitle: Nghiên cứu của đại học Stanford cho thấy các công cụ kiểm tra xem một bài viết có phải do GPT viết hay không đang dựa vào độ đa dạng của từ vựng, và cho kế quả đánh giá sai khi người viết không sử dụng tiếng Anh như tiếng mẹ đẻ. 
description: >-
  Minh họa giao diện ChatGPT của OpenAI. Nguồn: Emiliano Vittoriosi (Unplash)
image: >-
  https://images.unsplash.com/photo-1677691824654-080253698493?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1548&q=80
category: Công nghệ
tags:
  - công nghệ
  - AI
author: mranderson
paginate: true
---

Hiện nay, khi một bài viết được viết bằng GPT, nhiều công cụ được sử dụng để kiểm tra xem liệu nó có phải là do GPT viết hay không. Tuy nhiên, các công cụ này thường đưa ra đánh giá sai với tỉ lệ khác nhau.

Nhóm tác giả từ đại học Stanford đã tiến hành nghiên cứu và phát hiện ra rằng các bài viết thật sư do con người viết nhưng bị đánh giá sai thường là do người viết không sử dụng tiếng Anh như tiếng mẹ đẻ, và sử dụng các từ đơn giản và không đa dạng, dẫn đến việc bị đánh giá nhầm là do AI viết.

Để kiểm tra giả thuyết này, nhóm tác giả đã sử dụng 91 bài luận TOEFL của người Trung Quốc và 88 bài luận của học sinh lớp 8 ở Mỹ. Họ cũng thử thay đổi bài viết bằng cách tăng độ đa dạng của từ vựng cho các bài luận của người Trung Quốc và sử dụng các từ vựng đơn giản cho các bài luận của học sinh Mỹ. Kết quả cho thấy rằng, các công cụ kiểm tra dựa vào tính đa dạng của từ vựng để đưa ra kết luận.

<figure>
  <img src="/assets/img/ai-detectors-bias.png" alt="Data">
  <figcaption>Tăng tính đa dạng của từng vựng làm thay đổi kết quả của các bộ công cụ kiểm tra GPT. Nguồn: arXiv.</figcaption>
</figure>

Một trong những nguyên nhân gây ra hiện tượng này có thể là do các công cụ này được huấn luyện trên cơ sở dữ liệu của người nói tiếng Anh là tiếng mẹ đẻ. Điều này là không công bằng với những người không nói tiếng Anh và cần được cải thiện.


<em>Ghi chú:</em> Bài viết được đăng tải trên arXiv chưa phải là bản cuối cùng và có thể đang chờ được bình duyệt ở một tạp chí khoa học.

> Liang, W., Yuksekgonul, M., Mao, Y., Wu, E. and Zou, J., 2023. [GPT detectors are biased against non-native English writers](https://doi.org/10.48550/arXiv.2304.02819). arXiv preprint arXiv:2304.02819.




