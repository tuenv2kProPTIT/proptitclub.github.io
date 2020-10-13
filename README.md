---
layout: post
title: TEST post 
description: >
  Tutorial  
---

# Thông tin chung

Bố cục trang gồm 3 phần post - certification - project. Muốn viết bài nào liên quan thì viết tương ứng trong các mục đó.

# Post một bài mới.

## Đặt tên file lưu post.

Một file đặt vào 1 trong 3 folder :

* _project
* _blog-posts
* certification

Được đặt tên theo định dạng : năm-tháng-ngày-tênpost.md

## Config

Một bài post bắt buộc phải có config ở đầu.

Có thể config tùy ý, nhưng phải có : 

* layout: post 
* title: Tiêu đề bài post
* description: Mô tả chung về bài post đó.

## Post 

Post có thể viết bằng [markdow](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet).

## Static file 

Các file static được lưu vào mục assets. Để render một ảnh trong /assets/img/certificates/ACMPTIT2018.jpg. Ta chỉ việc dùng chính link đó, không cần chèn thêm đường dẫn gì nữa. Việc render ảnh khi có đường dẫn thì làm theo cách thông thường markdown.

## Math

Site sử dụng mathjax để render các công thức toán.

$\sqrt(x^2)$

## Sau khi viết xong chỉ cần push lên github. Cli github sẽ tự render ra blog cho mình.

---




