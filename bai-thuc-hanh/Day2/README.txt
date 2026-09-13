=========================================
NGÀY 2 - GPIO, BUTTON VÀ STATE MACHINE
=========================================

Sau khi làm quen với lập trình GPIO cơ bản ở ngày đầu tiên, ngày học thứ
hai tập trung mở rộng khả năng điều khiển nhiều LED, đọc trạng thái nút
nhấn và xây dựng thuật toán điều khiển theo mô hình State Machine.

Trong buổi học, thực hiện điều khiển nhiều LED bằng GPIO Output, sau đó
tối ưu chương trình bằng cách sử dụng mảng (Array) kết hợp với vòng lặp
for để quản lý nhiều chân GPIO, giúp mã nguồn ngắn gọn, dễ mở rộng và
dễ bảo trì hơn. Đồng thời tìm hiểu cách cấu hình GPIO Input, cơ chế
Pull-up, Pull-down và sử dụng hàm HAL_GPIO_ReadPin() để đọc trạng thái
nút nhấn. 

Bên cạnh đó, xây dựng các hiệu ứng LED chạy xuôi, chạy ngược và chạy
qua lại, từ đó làm quen với tư duy lập trình theo State Machine. Ngoài
ra còn tìm hiểu nguyên lý hoạt động của bộ Timer và các thanh ghi PSC,
ARR, CNT nhằm chuẩn bị cho việc thay thế HAL_Delay() bằng Timer Polling
trong các bài học tiếp theo. 

Ngày học này giúp hình thành tư duy tổ chức chương trình theo hướng tối
ưu, nâng cao khả năng quản lý nhiều thiết bị ngoại vi và tạo nền tảng
cho việc phát triển các ứng dụng Embedded phức tạp hơn trong những buổi
học tiếp theo. 
