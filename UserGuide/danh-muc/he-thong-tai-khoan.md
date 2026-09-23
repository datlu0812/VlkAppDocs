---
description: (Danh mục hệ thống tài khoản)
---

# Hệ thống tài khoản

## <mark style="color:$primary;">Màn hình chức năng</mark>

<figure><img src="../.gitbook/assets/Màn hình hệ thống tài khoản.png" alt=""><figcaption></figcaption></figure>

## <mark style="color:$primary;">Giới thiệu Hệ thống tài khoản</mark>

\- Hệ thống tài khoản là chức năng dùng để khai báo, quản lý và sử dụng các tài khoản kế toán phục vụ việc ghi nhận và phân loại các nghiệp vụ kinh tế, tài chính phát sinh trong doanh nghiệp.

\- Mỗi tài khoản kế toán đại diện cho một nhóm đối tượng hoặc nội dung kinh tế nhất định, giúp doanh nghiệp theo dõi các biến động về tài sản, nợ phải trả, vốn chủ sở hữu, doanh thu, chi phí và kết quả hoạt động kinh doanh.

## <mark style="color:$primary;">Vai trò của Hệ thống tài khoản</mark>

Hệ thống tài khoản là cơ sở để thực hiện định khoản kế toán trên chứng từ. Khi lập chứng từ, lựa chọn TK Nợ và TK Có phù hợp với nghiệp vụ phát sinh.

**Ví dụ:**

Doanh nghiệp mua hàng hóa và thanh toán bằng tiền mặt:

Nợ TK 156 – Hàng hóa: 10.000.000\
Có TK 111 – Tiền mặt: 10.000.000

**Trong đó:**

TK 156 dùng để phản ánh giá trị hàng hóa của doanh nghiệp.

TK 111 dùng để phản ánh tiền mặt tại quỹ.

Tổng số tiền TK Nợ = TK Có, đảm bảo nguyên tắc cân đối của định khoản.

## <mark style="color:$primary;">Các thông tin thường có trong Hệ thống tài khoản</mark>

<table data-header-hidden><thead><tr><th></th><th></th><th></th><th width="109"></th><th></th></tr></thead><tbody><tr><td><strong>Tên trường</strong></td><td><strong>Ý nghĩa</strong></td><td><strong>Phương thức nhập</strong></td><td><strong>Ví dụ</strong></td><td><strong>Quy tắc kiểm tra</strong></td></tr><tr><td><strong>Tài khoản</strong></td><td>Số hiệu dùng để nhận diện tài khoản kế toán và phân biệt giữa các tài khoản trong hệ thống.</td><td>Nhập số hiệu tài khoản theo hệ thống tài khoản kế toán áp dụng.</td><td>111</td><td>Không được trùng số hiệu tài khoản; phải đúng định dạng theo quy định/cấu hình của hệ thống.</td></tr><tr><td><strong>Tên tài khoản</strong></td><td>Tên mô tả nội dung kinh tế được phản ánh trên tài khoản.</td><td>Nhập tên tài khoản tương ứng với số hiệu tài khoản.</td><td>Tiền mặt</td><td>Không để trống; tên tài khoản cần phù hợp với số hiệu tài khoản.</td></tr><tr><td><strong>Tài khoản cha</strong></td><td>Xác định tài khoản cấp trên của tài khoản đang khai báo, giúp xây dựng cấu trúc phân cấp tài khoản.</td><td>Chọn tài khoản cha nếu tài khoản là tài khoản chi tiết/cấp dưới.</td><td>111</td><td>Tài khoản cha phải tồn tại trong hệ thống và không được thiết lập quan hệ phân cấp không hợp lệ.</td></tr><tr><td><strong>Bậc tài khoản</strong></td><td>Cho biết tài khoản đang thuộc cấp nào trong hệ thống tài khoản.</td><td>Hệ thống xác định dựa trên cấu trúc tài khoản và tài khoản cha.</td><td>Cấp 1</td><td>Bậc tài khoản phải phù hợp với cấu trúc phân cấp của tài khoản.</td></tr><tr><td><strong>Trạng thái</strong></td><td>Cho biết tài khoản hiện có được phép sử dụng trong hệ thống hay không.</td><td>Chọn hoặc thiết lập trạng thái tài khoản theo nhu cầu quản lý.</td><td>Hoạt động</td><td>Tài khoản ở trạng thái ngừng hoạt động không được sử dụng cho các nghiệp vụ mới nếu hệ thống áp dụng quy tắc này.</td></tr></tbody></table>

## <mark style="color:$primary;">Ví dụ một số tài khoản thường dùng</mark>

| **Số hiệu** | **Tên tài khoản**                      | **Nội dung theo dõi**                                       |
| ----------- | -------------------------------------- | ----------------------------------------------------------- |
| 111         | Tiền mặt                               | Tiền mặt tại quỹ của doanh nghiệp                           |
| 112         | Tiền gửi ngân hàng                     | Tiền gửi tại ngân hàng                                      |
| 131         | Phải thu của khách hàng                | Các khoản khách hàng còn phải thanh toán                    |
| 156         | Hàng hóa                               | Giá trị hàng hóa của doanh nghiệp                           |
| 331         | Phải trả cho người bán                 | Các khoản doanh nghiệp còn phải thanh toán cho nhà cung cấp |
| 511         | Doanh thu bán hàng và cung cấp dịch vụ | Doanh thu từ hoạt động bán hàng, cung cấp dịch vụ           |
| 632         | Giá vốn hàng bán                       | Giá vốn của hàng hóa, sản phẩm, dịch vụ đã bán              |
| 642         | Chi phí quản lý doanh nghiệp           | Các chi phí phục vụ hoạt động quản lý doanh nghiệp          |

## <mark style="color:$primary;">Các chức năng trong danh mục hệ thống tài khoản</mark>

#### Tác vụ chung (<mark style="color:red;">Ctrl + U</mark>)

\+ **Tạo mới** **(**<mark style="color:red;">**Alt +N**</mark>**)**:

\+ **Nạp dữ liệu** **(**<mark style="color:red;">**Alt + I**</mark>**)**:

\+ **Chỉnh sửa (**<mark style="color:red;">**Chọn dữ liệu + Enter**</mark>**)**:

\+ **Xóa (**<mark style="color:red;">**Alt + X**</mark>**)**:

\+ **Sắp xếp (**<mark style="color:red;">**Alt + S**</mark>**)**: Chức năng Sắp xếp dùng để thay đổi thứ tự hiển thị dữ liệu trên danh sách theo một hoặc nhiều tiêu chí, giúp dễ dàng tra cứu, kiểm tra và đối chiếu chứng từ.

* **Thêm điều kiện (**<mark style="color:red;">**Alt + N**</mark>**):**
* **Xóa tất cả điều kiện (**<mark style="color:red;">**Alt + Delete**</mark>**):**
* **Xóa một điều kiện (**<mark style="color:red;">**Alt + X**</mark>**):**
* **Đóng (**<mark style="color:red;">**ESC**</mark>**):**
* **Áp dụng (**<mark style="color:red;">**Alt + A**</mark>**):**

\+ **Lọc (**<mark style="color:red;">**Alt + L**</mark>**)**: Chức năng Lọc cho phép lọc và hiển thị các chứng từ hoặc dữ liệu đáp ứng một hoặc nhiều điều kiện lọc, giúp nhanh chóng tra cứu thông tin cần thiết trên danh sách.

* **Thêm điều kiện (**<mark style="color:red;">**Alt + N**</mark>**):**
* **Xóa tất cả điều kiện (**<mark style="color:red;">**Alt + Delete**</mark>**):**
* **Xóa một điều kiện (**<mark style="color:red;">**Alt + X**</mark>**):**
* **Đóng (**<mark style="color:red;">**ESC**</mark>**):**
* **Áp dụng (**<mark style="color:red;">**Alt + A**</mark>**):**

\+ **Điều chỉnh cột hiển thị (**<mark style="color:red;">**Alt + D**</mark>**)**: dùng để tùy chỉnh cách hiển thị các cột dữ liệu trên màn hình danh sách, bao gồm sắp xếp thứ tự cột và ẩn/hiện cột theo nhu cầu sử dụng.

* **Hiện/đóng tất cả (**<mark style="color:red;">**Ctrl + A**</mark>**):**
* **Đóng (**<mark style="color:red;">**ESC**</mark>**):**
* **Áp dụng (**<mark style="color:red;">**Alt + A**</mark>**):**

\+ **Tìm kiếm nhanh (**<mark style="color:red;">**Ctrl + F**</mark>**)**: thực hiện tìm kiếm theo nội dung nhập vào để tìm kiếm nhanh chứng từ.

\+ **Làm mới dữ liệu (**<mark style="color:red;">**Phím F5**</mark>**)**: Dùng để làm mới dữ liệu hiển thị để cập nhật những thay đổi mới nhất khi chỉnh sửa dữ liệu nhưng chưa được hiển thị các thông tin đã chỉnh sửa.

\+ **Ẩn thanh chi tiết (**<mark style="color:red;">**Alt + V**</mark>**)**: Chọn một chứng từ và mở view xem nhanh thông tin chi tiết chứng từ đó.

#### In ấn và chia sẻ (<mark style="color:red;">Ctrl + P</mark>)

\+ **In (**<mark style="color:red;">**Alt + P**</mark>**)**:

\+ **Xuất file excel (**<mark style="color:red;">**Alt + E**</mark>**)**:
