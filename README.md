--------- các thao tác ban đầu ------------
- Mở CMD gõ lệnh "npm install gulp-cli -g" để cài đặt thư viện gulp
- Từ CMD trỏ về thư mục dự  án /vinharound.com gõ lệnh "npm install" để cài tất cả các thư viện cần thiết cho dự án
- Cách dùng gulp
 + lệnh "gulp serve" khởi chạy 1 host local mỗi khi save update file html, css gulp sẽ tự động update 
 + lệnh "gulp build:dist" dùng để tạo bản deploy tất cả sẽ nằm trong thư mục /dist tất cả các file dc build trong thư mục /dist có thể upload lên host và chạy 
- bấm Ctrl + C để thoát tất cả các lệnh đang chạy

--------- cấu trúc dự án --------
- làm việc với các file ở thư mục /src
- các component html được chia thành nhiều file chứa trong thư mục /src/partials 
- dùng lệnh @@include để include các file html với nhau
- dự án này tập trung vào các partials có tiền tố _vinh-

--------- cách sử dụng component --------
- luôn tham khảo các component, các class name css từ trang https://sandbox.elemisthemes.com/index.html
- không nên thay đổi cấu trúc html
- nên tham khảo cố vấn trước khi thực hiện 