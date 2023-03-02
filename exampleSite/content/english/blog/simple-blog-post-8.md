---
title: PHP BASIC
date: 2023-03-02T08:51:12+00:00
image_webp: images/blog/blog-post-2.webp
image: images/blog/blog-post-2.jpg
author: TÍT
description: PHP CƠ BẢN

---
## **PHP CƠ BẢN**

### **ÔN TẬP PHP**

1. **PHP có mấy cách khai báo? Những cách nào được xem là chính thống và không ảnh hưởng khi các phiên bản update sau này?**

       Đáp:
       PHP có 4 cách khai báo, tuy nhiên có cách chính thống: <?php ?>
2. **Hằng trong PHP khác gì so với biến? Nếu 1 hằng được định nghĩa 2 lần, thì liệu có bị lỗi không?**

       Đáp:
       2.1 Hằng thì không thay đổi trong suốt quá trình trương chạy,biến thì có.
       2.2 Không bị lỗi, tuy nhiên hằng chỉ nhận giá trị đầu tiên.
3. **Phân biệt $_POST và $_GET trong php?**

       Đáp: 
       Điểm chung đều được dùng để gửi dữ liệu lên server.
       Điểm khác biệt: POST thì dữ liệu được truyền thông qua HTTP HEADER nên có tính bảo mật hơn.
       Dữ liệu gửi lên thì không bị giới hạn. Chậm hơn GET
       Get dữ liệu gửi lên được truyền trên URL, thông tin được hiển thị trên URL lên tính bảo mật kém hơn.
       Bị giới hạn 1024 ký tự. Nhanh hơn POST do được cache trên web