------------------------------------------------
## Basic

### LDAP là: 

LDAP (Lightweight Directory Access Protocol) là một giao thức giúp thiết kế và truy xuất dữ liệu dựa trên mô hình client-server

### Directory ở đây không phải là 

Thư mục dạng cây đơn giản mà nó là một loại hình database có tính mô tả cao, được tối ưu cho việc tìm kiếm (cơ sở dữ liệu như dạng cây)

### LDAP server như là 

Một cơ sở dữ liệu và client sẽ dùng giao thức LDAP để lấy thông tin từ cơ sở dữ liệu được xây dựng dựa trên nền tảng LDAP (LDAP server). ???

### => LDAP thường thấy ở nơi chứa dữ liệu. Trong Windows server có thể dễ dàng nhận thấy ở Active Directory vì nó dựa trên nền tảng LDAP. 

### LDAP thích hợp với những cơ sở dữ liệu vừa và lớn. Nó tối ưu cho việc truy cập dữ liệu (đọc và tìm kiếm) hơn là update dữ liệu (viết)

### Ví dụ: 

Các chương trình dùng chung của Chính phủ lấy "LDAP" làm cơ sở dữ liệu người dùng và dùng chung cho tất cả các ứng dụng có sử dụng việc đăng nhập. Tất một chuyên viên, nhân viên, hay người dùng chỉ có một tài khoản duy nhất cho việc đăng nhập các chương trình dùng chung khi làm việc, và tài khoản này được cấu trúc tổ chức lưu trữ tại "LDAP". Việc đăng nhập vào các chương trình thành công hay không là do xác nhận từ phía "LDAP" (vậy LDAP như là một cơ sở dữ liệu MYSQL và web, web đăng nhập dựa trên cơ sở dữ liệu LDAP), các chương trình chỉ tích hợp các tài khoản trên LDAP để phân quyền sử dụng các chức năng của chúng.

--------------------------------------------

## Advance: 

### LDAP là: 

*Lightweight Directory Access Protocol, là một giao thức mở được sử dụng cho việc lưu trữ và gọi lại dữ liệu từ một cấu trúc cây thư mục phân cấp. Thông thường được sử dụng để lưu trữ thông tin về một tổ chức và các tài sản cũng như người dùng của tổ chức ấy.

* Là một giao thức truyền thông định nghĩa các phương thức mà một dịch vụ thư mục có thể được truy xuất

* Định hình cách dữ liệu trong một dịch vụ thư mục có thể đại diện cho người dùng, xác định các yêu cầu đối với các thành phần sử dụng tạo lên data entries trong một dịch vụ thư mục, và vạch ra cách mà các thành phần khác nhau được sử dụng để tạo ra entry.

### Service Directory: 

* Một dịch vụ thư mục được sử dụng để lưu trữ, tổ chức và trình diễn dữ liệu theo định dạng key-value.

* Dữ liệu được lưu trữ trong dịch vụ thư mục được sử dụng để xác định những đặc tính của một thực thể . Ví dụ một đối tượng vật lý được biểu diễn trong dịch vụ thư mục là một sổ địa chỉ. Ví dụ mỗi người được biểu diễn như một entry trong thư mục, với cặp key-value mô tả thông tin liên hệ, nơi kinh doanh,... 

###  
