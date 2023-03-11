---
title: PHP BASIC
date: 2023-03-02T08:51:12+00:00
image_webp: "/images/php-mascot.jpg"
image: "/images/php-mascot.jpg"
author: TÍT
description: PHP CƠ BẢN

---
## **PHP CƠ BẢN**

### **ÔN TẬP PHP**

1. **PHP có mấy cách khai báo? Những cách nào được xem là chính thống và không ảnh hưởng khi các phiên bản update sau này?**

   Đáp: - PHP có 4 cách khai báo, tuy nhiên chỉ có cách chính thống: <?php ?>
2. **Hằng trong PHP khác gì so với biến? Nếu 1 hằng được định nghĩa 2 lần, thì liệu có bị lỗi không?**

   Đáp:
   2\.1 Hằng thì không thay đổi trong suốt quá trình trương chạy, biến thì có.
   2\.2 Không bị lỗi, tuy nhiên hằng chỉ nhận giá trị đầu tiên.
3. **Phân biệt $_POST và $_GET trong php?**

   Đáp:    
   \- Điểm chung đều được dùng để gửi dữ liệu lên server.   
   \- Điểm khác biệt: POST thì dữ liệu được truyền thông qua HTTP HEADER nên có tính bảo mật hơn. Dữ liệu gửi lên thì không bị giới hạn. Chậm hơn GET   
   \- Get dữ liệu gửi lên được truyền trên URL, thông tin được hiển thị  trên URL lên tính bảo mật kém hơn. Bị giới hạn 1024 ký tự. Nhanh hơn POST do được cache trên web.
4. **Mảng là gì? Có mấy loại mảng trong PHP?**  
   Đáp:  
   Mảng là phần tử trong đó có chứa các thành phần, có thể lọc, xoá, thay đổi phần tử trong mảng một cách dễ dàng.  
   Có 3 loại mảng:  
   \- Mảng tuần tự: Là mảng có key tự động tạo là chữ số tăng dần bắt đầu từ 0  
   \- Mảng không tuần tự: Là mảng có key tự định nghĩa, có thể là số hoặc là các ký tự. Không tuân theo bất ký sắp xếp nào.  
   \- Mảng đa chiều: Là mảng trong đó có chứa ít nhất 1 mảng.
5. **Mảng tuần tự là gì? Khác gì với bất tuần tự? Để duyệt mảng ta dùng vòng lặp nào?**  
   \- Mảng tuần tự là có key được tạo tự động, tăng dần bắt đầu từ số 0.  
   \- Khác nhau: Mảng bất tuần tự không tuân theo bất kỹ sắp sếp nào,  còn mảng không tuần tự thì ngược lại  
   \- Để duyệt mảng trong PHP ta có rất nhiều cách như là (array_map,  foreach). Nhưng chỉ có 1 cách dễ sử dụng và tốc đô xử lý nhanh hơn đố là vòng lắp foreach.
6. **Để chuyển mảng thành chuỗi ta dùng hàm gì? Để tách chuỗi thành mảng ta dùng hàm gì?**  
   \- Để chuyển mảng thành chuỗi ta dùng implode(), ngược lại thì dùng hàm explode().
7. **Trong PHP để gộp mảng ta dùng hàm gì? Để tách mảng ta dùng hàm gì?**  
   \- Để gộp mảng ta dùng hàm array_merge.  
   \- Để tách mảng ta dùng array_slice
8. **Cho biết sự khác nhau giữa serialize và json_encode? Lý giải theo cách bạn hiểu?**  
   \- Đều là chuyển đổi một mảng hoặc object thành string.  
   \- serialize chuyển đổi thành một chuỗi theo chuẩn PHP và unserialize để chuyển ngược lại thành mảng hoặc object.  
   \- json encode thì chuyển thành dữ liệu JSON để sử dụng trong lưu trữ database và để chuyển đổi sử dụng json decode để chuyển ngược lại thành mảng/