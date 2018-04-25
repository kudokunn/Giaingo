Phân biệt: IOPS, LATENCY VÀ THROUGHPUT
IOPS: Input Output per Second: 

 + IOPS là đơn vị đo lường được sử dụng cho các thiết bị lưu trữ như HDD, SSD hoặc SAN – cho biết số lượng tác vụ Write hoặc Read được hoàn thành trong 1 giây.
 + Đổi IOPS => MB/s: IOPS x 4 or 8 or 32 / 1024 = tốc độ MB/giây. Ví dụ chúng ta có chỉ số IOPS là 90.000 thì phép tính sẽ là 90.000 x 4 / 1024 = 351,56 MB/giây. Do vậy, chỉ số IOPS càng lớn càng tốt.

+ Average IO size x IOPS = Throughput in MB/s với: 
IO size: kích thước data khi ứng dụng, service, hệ điều hành request truy cập vào ổ đĩa. Ex: 4 KB, 8 KB, 32 KB
Average latency: độ trễ trung bình: Mỗi request IO sẽ mất một thời gian để hoàn thành đó là độ trễ trung bình. (ms). Thông số càng thấp càng tốt. Latency=1/IOSP <chu kỳ và tần số)
 
+ Throughput là thông số được biết tới phổ biến nhất của ổ cứng, chỉ ra tốc độ transfer data
