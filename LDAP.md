# LDAP là LDAP (Lightweight Directory Access Protocol) là một giao thức giúp thiết kế và truy xuất dữ liệu dựa trên mô hình client-server

# Directory ở đây không phải là thư mục dạng cây đơn giản mà nó là một loại hình database có tính mô tả cao, được tối ưu cho việc tìm kiếm
(cơ sở dữ liệu như dạng cây)

# LDAP server như là một cơ sở dữ liệu và client sẽ dùng giao thức LDAP để lấy thông tin từ cơ sở dữ liệu được xây dựng dựa trên nền tảng LDAP (LDAP server). 

# => LDAP thường thấy ở nơi chứa dữ liệu. Trong Windows server có thể dễ dàng nhận thấy ở Active Directory vì nó dựa trên nền tảng LDAP. 

# LDAP thích hợp với những cơ sở dữ liệu vừa và lớn. Nó tối ưu cho việc truy cập dữ liệu (đọc và tìm kiếm) hơn là update dữ liệu (viết)

# Ví dụ: Các chương trình dùng chung của Chính phủ lấy "LDAP" làm cơ sở dữ liệu người dùng và dùng chung cho tất cả các ứng dụng có sử dụng việc đăng nhập. Tất một chuyên viên, nhân viên, hay người dùng chỉ có một tài khoản duy nhất cho việc đăng nhập các chương trình dùng chung khi làm việc, và tài khoản này được cấu trúc tổ chức lưu trữ tại "LDAP". Việc đăng nhập vào các chương trình thành công hay không là do xác nhận từ phía "LDAP" (vậy LDAP như là một cơ sở dữ liệu MYSQL và web, web đăng nhập dựa trên cơ sở dữ liệu LDAP), các chương trình chỉ tích hợp các tài khoản trên LDAP để phân quyền sử dụng các chức năng của chúng  Và tôi nhận thấy, việc quy về một tài khoản như thế này cho các chương trình là một việc rất HAY. Nó giống như ở trong một tòa nhà hiện đại, với những phòng ốc chức năng và quyền hạn khác nhau, một người với một cái thẻ trên tay, anh ta có thể đi đến đâu ở bất kỳ chổ nào trong tòa nhà, và anh ta chỉ có thể làm được những nhiệm vụ gì đối với cái thẻ đo khi anh ta vào một phòng nhất định (tòa nhà đây là web, người dùng user và thẻ là tk, mk trên ldap)

# 
