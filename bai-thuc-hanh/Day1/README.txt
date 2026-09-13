=========================================
NGÀY 1 - LÀM QUEN VỚI STM32
=========================================

Ngày đầu tiên tập trung làm quen với hệ sinh thái phát triển của STM32,
bao gồm môi trường lập trình STM32CubeIDE, cách tạo một dự án mới và
cấu trúc cơ bản của chương trình STM32.

Trong buổi học, thực hiện các bài thực hành điều khiển LED bằng thư viện
HAL để hiểu cách cấu hình GPIO Output, cách sử dụng các hàm
HAL_GPIO_WritePin(), HAL_GPIO_TogglePin() và HAL_Delay(). Đồng thời
quan sát sự thay đổi của LED khi thay đổi thời gian trễ, từ đó hiểu được
mối quan hệ giữa chương trình và phần cứng. 

Ngoài việc hoàn thành các bài tập Blink LED với nhiều tốc độ và điều
khiển hai LED hoạt động luân phiên, buổi học còn giúp nắm được cấu trúc
một project STM32, vai trò của hàm main(), vòng lặp while(1), các hàm
khởi tạo hệ thống và quy trình nạp chương trình xuống vi điều khiển để
kiểm tra kết quả thực tế. 

Đây là bước khởi đầu quan trọng, tạo nền tảng để tiếp tục tìm hiểu các
ngoại vi khác của STM32 cũng như phát triển các ứng dụng Embedded trong
những buổi học tiếp theo.
