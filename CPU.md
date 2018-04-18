## Core vs Threat

### Core 
là CPU độc lập, bây giờ người ta có thể nhồi mấy cái CPU vào 1 chỗ tạo thành cái CPU có 2,4,6,8 CPU trong nhân hiểu là số core . Thông thường số code thường là số chẵn.

### Threat:
Khi cần làm gì đó thì phần mềm gửi xung tín hiệu cho CPU xử lý, thời sơ khai thì CPU chỉ xử lý 1
việc vào 1 thời điểm, đơn giản: Một nhân cpu có 3 hoạt động là nhận dữ liệu, xử lý dữ liệu, xuất dữ liệu.
1luồng tín hiệu vào sẽ phải chạy hết 3 hoạt động đó thì mới quay lại từ đầu. vậy khi mà cpu đang ở
giai đoạn xử lý dữ liệu thì khối nhận dữ liệu sẽ phải chờ, cũng như thế khi cpu đang ở khối xuất dữ
liệu thì 2 khối kia sẽ chờ, rất lãng phí. do đó người ta cho 2 luồng dữ liệu vào đồng thời, vậy thì khi
luồng 1 đang ở khối 2 thì luồng 2 đang ở khối 1, dữ liệu đc xếp chồng và xử lý liên tục. đó gọi là
công nghệ siêu phân luồng

 ### Các loại tiến trình bao gồm:
 
* Tổng số tiến trình (total) 
* Số đang hoạt động (running) 
* Số đang ngủ/chờ (sleeping) 
* Số đã dừng (stopped) 
* Số tiến trình dừng nhưng vẫn lưu trong talbe process (zombie)

P/S: Tiến trình quá trình zombie hoặc ngừng hoạt động là một tiến trình đã hoàn thành nhưng vẫn có một entry trong process table: đó là một tiến trình trong "Trạng thái đã chấm dứt" . Điều này xảy ra đối với các trình con, nơi entry vẫn cần thiết để cho phép tiến trình cha đọc được trạng thái exit của tiến trình con.
