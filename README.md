Automation framework được viết trên ngôn ngữ lập trình Java và selenium version 3.xx.
Về cấu trúc thiết kế framework:
1. Common: Chứa những hàm thao tác với element có tính tái sử dụng và quản lý môi trường test và trình duyệt tương ứng.
2. PageObject: Chữa những câu lệnh thao tác với element của web test.
3. Page UI: Chữa những xpath và css của element.
4. reportConfig: Chưa code quản lý report sau khi chạy test (Hiện tại đang dùng extent report)
5. Test: Chữa những TC chạy automation test và file xml quản lý chạy test case.
6. Data: Chứa file quản lý data của từng dự án chạy auto (Hiện đang dùng file Json).
7. environmentConfig: Chứa Cấu hình từng môi trường test khác nhau.
8. extentV5: Chứa file html report sau mỗi lần chạy automation test.

Trên đây là thông tin về cấu trúc framework automation test mà Leon đã build dựa trên kiến thức và kinh nghiệm của mình. Mọi thắc mắc có thể liên hệ về email: leon.kieu@gmail.com 
or Phone: 0945696835
