=========================================
NGÀY 3 - TIMER POLLING VÀ TIMER INTERRUPT
=========================================

Ngày học thứ ba tập trung tìm hiểu bộ Timer trên STM32 và cách sử dụng
Timer để tạo các khoảng thời gian chính xác thay cho phương pháp sử dụng
HAL_Delay(). Đồng thời làm quen với hai phương pháp xử lý thời gian là
Timer Polling và Timer Interrupt.

Trong buổi học, thực hiện cấu hình Timer bằng STM32CubeMX, tìm hiểu vai
trò của các thanh ghi PSC (Prescaler), ARR (Auto Reload Register) và CNT
(Counter), cũng như cách tính toán các giá trị này để tạo chu kỳ mong
muốn. Quá trình Debug được sử dụng để quan sát trực tiếp giá trị của bộ
đếm Timer nhằm hiểu rõ nguyên lý hoạt động của phần cứng. 

Bên cạnh đó, tiến hành so sánh giữa HAL_Delay(), Timer Polling và Timer
Interrupt để hiểu ưu điểm và hạn chế của từng phương pháp. Kiến thức về
Timer sau đó được áp dụng để điều khiển hiệu ứng LED Knight Rider theo
kiểu không chặn (Non-blocking), giúp chương trình có thể thực hiện nhiều
tác vụ đồng thời mà không bị dừng trong các khoảng Delay. 

Ngày học này giúp xây dựng nền tảng quan trọng về quản lý thời gian trong
hệ thống nhúng, đồng thời tạo tiền đề cho việc sử dụng Interrupt, xây
dựng Driver và phát triển các ứng dụng Embedded theo hướng chuyên
nghiệp ở những bài học tiếp theo. 
