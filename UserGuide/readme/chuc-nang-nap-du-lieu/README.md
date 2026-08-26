---
icon: desktop-arrow-down
layout:
  width: default
  title:
    visible: true
  description:
    visible: true
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
  metadata:
    visible: true
  tags:
    visible: true
  actions:
    visible: true
---

# Chức năng Nạp dữ liệu

## <mark style="color:blue;">Giới thiệu chức năng Nạp dữ liệu</mark>

Chức năng **Nạp dữ liệu từ file** cho phép người dùng import dữ liệu từ các file đã chuẩn bị sẵn vào hệ thống. Người dùng có thể lựa chọn loại dữ liệu cần nạp, cấu hình thông tin import, gán các cột dữ liệu từ file với các trường thông tin tương ứng trên hệ thống, thực hiện đối chiếu dữ liệu và kiểm tra tính hợp lệ trước khi lưu dữ liệu.

Chức năng hỗ trợ người dùng chuẩn hóa dữ liệu thông qua **file mẫu import**, đồng thời cho phép đính kèm file bằng thao tác kéo thả hoặc lựa chọn trực tiếp từ máy tính. Người dùng cũng có thể thực hiện các cấu hình chi tiết như thông tin chứng từ, định khoản mặc định, nguồn dữ liệu số tiền, thuế, tự động tạo sản phẩm/đối tác và các tùy chọn xác thực nâng cao.

### Các chức năng chính

#### 1. Màn hình chức năng

Màn hình Nạp dữ liệu gồm các thành phần chính:

* Đường dẫn chức năng: hiển thị đường dẫn chức năng hiện tại
* Sơ đồ các bước thực hiện import
* Nhóm các nút chức năng nạp dữ liệu
* Hiển thị nội dung dữ liệu, cấu hình dữ liệu import
* Hiển thị hướng dẫn và các cảnh báo khi import

#### 2. Nạp Hóa đơn đầu vào và Hóa đơn đầu ra

Quy trình nạp dữ liệu hóa đơn gồm **4 bước**:

**Chọn dữ liệu & cấu hình → Gán cột dữ liệu → Đối chiếu hàng hóa → Kiểm tra & Lưu.**

Người dùng thực hiện:

* Chọn loại dữ liệu và tải file mẫu.
* Chuẩn hóa dữ liệu theo cấu trúc file mẫu.
* Đính kèm file import.
* Thiết lập cấu hình chứng từ, định khoản, số tiền, VAT và dữ liệu tự động sinh.
* Gán các cột trong file với trường dữ liệu của hệ thống.
* Đối chiếu hàng hóa với dữ liệu đã có hoặc tạo mới sản phẩm.
* Xác nhận, kiểm tra tính hợp lệ và lưu dữ liệu vào hệ thống.

#### 3. Nạp Bảng kê ngân hàng

Đối với loại dữ liệu **Bảng kê ngân hàng**, quy trình được rút gọn còn **3 bước**:

**Chọn dữ liệu & cấu hình → Gán cột dữ liệu → Kiểm tra & Lưu.**

Quy trình này **không có bước Đối chiếu hàng hóa**, do đặc thù dữ liệu bảng kê ngân hàng. Người dùng thực hiện cấu hình tiền tệ, tỷ giá, tài khoản ngân hàng, định khoản mặc định và các tùy chọn liên quan trước khi gán cột dữ liệu và kiểm tra lưu.

### Tóm tắt

Chức năng **Nạp dữ liệu** giúp đơn giản hóa quá trình đưa dữ liệu từ file vào hệ thống bằng cách cung cấp quy trình kiểm soát theo từng bước, từ **chuẩn bị dữ liệu → cấu hình → gán dữ liệu → đối chiếu → xác thực → lưu**. Tùy theo loại dữ liệu được lựa chọn, hệ thống sẽ tự động áp dụng quy trình import phù hợp.
