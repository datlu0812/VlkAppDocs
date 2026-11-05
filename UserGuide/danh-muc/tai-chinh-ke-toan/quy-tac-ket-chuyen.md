---
description: (Danh mục quy tắc kết chuyển)
---

# Quy tắc kết chuyển

## <mark style="color:$primary;">**Màn hình chức năng**</mark>

<figure><img src="../../.gitbook/assets/màn hình quy tắc kết chuyển.png" alt=""><figcaption></figcaption></figure>

\- Danh mục quy tắc kết chuyển trong phần mềm là chức năng cho phép thiết lập và quản lý các quy tắc kết chuyển số liệu giữa các tài khoản kế toán. Các quy tắc này được sử dụng làm căn cứ để phần mềm tự động thực hiện các bút toán kết chuyển trong quá trình khóa sổ và xác định kết quả hoạt động kinh doanh cuối kỳ.

\- Thông qua chức năng này, có thể khai báo tài khoản nguồn, tài khoản đích, hướng kết chuyển, thứ tự thực hiện và tỷ lệ kết chuyển cho từng nghiệp vụ. Khi thực hiện chức năng kết chuyển, phần mềm căn cứ vào các quy tắc đã thiết lập để xác định số liệu cần kết chuyển, giúp giảm thao tác hạch toán thủ công, hạn chế sai sót và đảm bảo tính nhất quán của dữ liệu kế toán.

#### Vai trò của quy tắc kết chuyển

* Thiết lập quy tắc kết chuyển: Khai báo các nguyên tắc chuyển số dư hoặc phát sinh giữa các tài khoản kế toán theo từng nghiệp vụ.
* Tự động hóa nghiệp vụ kế toán: Làm cơ sở để phần mềm tự động tạo bút toán kết chuyển khi kế toán thực hiện kết chuyển cuối kỳ.
* Đảm bảo trình tự kế chuyển: Thiết lập thứ tự thực hiện các quy tắc nhằm đảm bảo số liệu được kết chuyển đúng trình tự nghiệp vụ.
* Quản lý tỷ lệ kết chuyển: Cho phép xác định tỷ lệ phần trăm giá trị cần kết chuyển theo từng quy tắc.
* Kiểm soát hoạt động kết chuyển: Cho phép bật hoặc tắt trạng thái hoạt động của từng quy tắc để kiểm soát việc áp dụng.

#### Ví dụ

\- Giả sử cuối kỳ, doanh nghiệp cần thực hiện kết chuyển doanh thu bán hàng để xác định kết quả kinh doanh.

\- Kế toán thiết lập quy tắc kết chuyển như sau:

| **Nội dung** | **Giá trị**                                                           |
| ------------ | --------------------------------------------------------------------- |
| Tên quy tắc  | Kết chuyển doanh thu bán hàng                                         |
| Diễn giải    | Kết chuyển doanh thu thuần sang tài khoản xác định kết quả kinh doanh |
| TK Nợ        | 511 – Doanh thu bán hàng và cung cấp dịch vụ                          |
| TK Có        | 911 – Xác định kết quả kinh doanh                                     |
| Hướng        | Nợ → Có                                                               |
| Thứ tự       | Theo trình tự kết chuyển đã thiết lập                                 |
| Trạng thái   | Hoạt động                                                             |
| % kết chuyển | 100%                                                                  |

\- Khi thực hiện kết chuyển cuối kỳ, phần mềm căn cứ vào quy tắc đã khai báo để tạo bút toán:

* Nợ TK 511: 100.000.000 đồng
* Có TK 911: 100.000.000 đồng

\- Tương tự, doanh nghiệp có thể thiết lập các quy tắc kết chuyển chi phí như giá vốn hàng bán (TK 632), chi phí bán hàng (TK 641), chi phí quản lý doanh nghiệp (TK 642) sang TK 911 để xác định kết quả kinh doanh.

{% hint style="danger" %}
<mark style="color:$danger;">Lưu ý: Ví dụ trên giả định số liệu là doanh thu thuần đủ điều kiện kết chuyển. Viêc thiết lập tài khoản và trình tự kế chuyển cần phù hợp với chế độ kế toán doanh nghiệp đang áp dụng.</mark>
{% endhint %}

## <mark style="color:$primary;">Các chức năng trong danh mục quy tắc kết chuyển</mark>

#### 1. Tác vụ chung (<mark style="color:red;">Ctrl + U</mark>)

**+** [**Tạo mới (**<mark style="color:red;">**Alt + N**</mark>**)**](quy-tac-ket-chuyen.md#chuc-nang-tao-moi-du-lieu)**:** Thực hiện tạo mới một quy tắc kết chuyển vào hệ thống.

**+ Chỉnh sửa (**<mark style="color:red;">**Chọn dữ liệu + Enter**</mark>**):** Dùng để xem chi tiết quy tắc kết chuyển, hoặc chỉnh sửa các thông tin của quy tắc kết chuyển cần sửa.

**+ Xóa (**<mark style="color:red;">**Alt + X**</mark>**):** Xóa quy tắc kết chuyển đã chọn.

**+ Bật/tắt:** dùng để vô hiệu hóa hoặc mở lại quy tắc kết chuyển đã chọn.

**+ Sắp xếp (**<mark style="color:red;">**Alt + S**</mark>**):** Chức năng Sắp xếp dùng để thay đổi thứ tự hiển thị dữ liệu trên danh sách theo một hoặc nhiều tiêu chí, giúp dễ dàng tra cứu, kiểm tra và đối chiếu dữ liệu.

**·   Thêm điều kiện (**<mark style="color:red;">**Alt + N**</mark>**)**

**·   Xóa tất cả điều kiện (**<mark style="color:red;">**Alt + Delete**</mark>**)**

**·   Xóa một điều kiện (**<mark style="color:red;">**Alt + X**</mark>**)**

**·   Đóng (**<mark style="color:red;">**ESC**</mark>**)**

**·   Áp dụng (**<mark style="color:red;">**Alt + A**</mark>**)**

**+ Lọc (**<mark style="color:red;">**Alt + L**</mark>**):** Chức năng Lọc dùng để tìm và hiển thị các dữ liệu đáp ứng một hoặc nhiều điều kiện lọc, giúp nhanh chóng tra cứu thông tin cần thiết trên danh sách.

**·   Thêm điều kiện (**<mark style="color:red;">**Alt + N**</mark>**)**

**·   Xóa tất cả điều kiện (**<mark style="color:red;">**Alt + Delete**</mark>**)**

**·   Xóa một điều kiện (**<mark style="color:red;">**Alt + X**</mark>**)**

**·   Đóng (**<mark style="color:red;">**ESC**</mark>**)**

**·   Áp dụng (**<mark style="color:red;">**Alt + A**</mark>**)**

**+ Quy tắc mẫu:** Tự động tạo danh sách các quy tắc cơ bản cần thiết trong việc kết chuyển. Quy tắc mẫu chỉ cần tạo một lần.

**+ Làm mới dữ liệu (**<mark style="color:red;">**Phím F5**</mark>**):** Dùng để làm mới dữ liệu hiển thị để cập nhật những thay đổi mới nhất khi chỉnh sửa dữ liệu nhưng chưa được hiển thị các thông tin đã chỉnh sửa.

**+ Ẩn thanh chi tiết (**<mark style="color:red;">**Alt + V**</mark>**):** Chọn một tài khoản ngân hàng và mở view xem nhanh thông tin chi tiết tài khoản ngân hàng đó. Và thực hiện phím tắt để ẩn thanh chi tiết.

#### 2. In ấn và chia sẻ (<mark style="color:red;">Ctrl + P</mark>)

**+ In (**<mark style="color:red;">**Alt + P**</mark>**):** Thực hiện in dữ liệu

**+ Xuất file excel (**<mark style="color:red;">**Alt + E**</mark>**):** xuất danh sách dữ liệu ra file excel.

## <mark style="color:$primary;">Chức năng tạo mới dữ liệu</mark>

<figure><img src="../../.gitbook/assets/popup tạo mới quy tắc.png" alt=""><figcaption></figcaption></figure>

**+ Tạo (**<mark style="color:red;">**Ctrl+S**</mark>**)** để lưu loại chứng từ mới vào danh mục.

**+ Hủy (**<mark style="color:red;">**ESC)**</mark> thoát khỏi popup tạo mới.

| **Tên trường**           | **Ý nghĩa**                                                                              | **Phương thức nhập**                                     | **Ví dụ**                         | **Quy tắc kiểm tra**                                                                                                                                                       |
| ------------------------ | ---------------------------------------------------------------------------------------- | -------------------------------------------------------- | --------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Tên quy tắc**          | Tên gọi dùng để nhận diện và phân biệt các quy tắc kết chuyển.                           | Nhập tên mô tả nghiệp vụ kết chuyển.                     | Kết chuyển doanh thu bán hàng     | <p>+ Không được để trống.</p><p>+ Không đặt trùng tên để dễ dàng phân biệt và nhận biết trong quá trình thực hiện.</p><p>+ Đặt tên phù hợp với loại quy tắc được chọn.</p> |
| **Loại quy tắc**         | Phân loại quy tắc theo từng nhóm nghiệp vụ kế toán.                                      | Chọn loại quy tắc từ danh sách có sẵn.                   | Kết chuyển doanh thu              | + Phải chọn loại quy tắc hợp lệ trong danh mục.                                                                                                                            |
| **Mô tả**                | Cung cấp thông tin giải thích mục đích hoặc nội dung nghiệp vụ kết chuyển.               | Nhập nội dung mô tả nếu cần.                             | Kết chuyển doanh thu sang TK 911. | + Nhập chi tiết mô tả nghiệp vụ của quy tắc.                                                                                                                               |
| **Tài khoản Nợ**         | Tài khoản được thiết lập ở bên Nợ trong bút toán kết chuyển.                             | Chọn tài khoản kế toán từ danh sách hệ thống tài khoản.  | 511 – Doanh thu bán hàng          | + Phải chọn tài khoản hợp lệ và phù hợp với nghiệp vụ kết chuyển.                                                                                                          |
| **Tài khoản Có**         | Tài khoản được thiết lập ở bên Có trong bút toán kết chuyển.                             | Chọn tài khoản kế toán từ danh sách hệ thống tài khoản.  | 911 – Xác định kết quả kinh doanh | <p>+ Phải chọn tài khoản hợp lệ.</p><p>+ Kiểm tra quan hệ với tài khoản Nợ.</p>                                                                                            |
| **Nguồn kết chuyển**     | Xác định bên tài khoản được sử dụng làm nguồn lấy số liệu để kết chuyển.                 | Chọn hướng nguồn kết chuyển theo nghiệp vụ.              | Về Nợ/Vế Có                       | + Phải xác định nguồn phù hợp với tính chất tài khoản và nghiệp vụ.                                                                                                        |
| **Thứ tự thực hiện**     | Xác định thứ tự ưu tiên khi phần mềm thực hiện nhiều quy tắc kết chuyển.                 | Nhập số thứ tự thực hiện.                                | 110                               | <p>+ Phải là số nguyên hợp lệ.</p><p>+ Quy tắc có thứ tự nhỏ hơn được ưu tiên thực hiện trước.</p>                                                                         |
| **Tỷ lệ kết chuyển (%)** | Xác định tỷ lệ phần trăm số liệu được kết chuyển từ tài khoản nguồn sang tài khoản đích. | Nhập tỷ lệ kết chuyển.                                   | 100%                              | + Giá trị từ 0 đến 100%; không được nhập số âm hoặc vượt quá giới hạn.                                                                                                     |
| **Bao gồm số dư**        | Cho phép tính đến số dư tài khoản nguồn khi thực hiện kết chuyển.                        | Tích chọn nếu muốn đưa số dư vào phạm vi xử lý.          | Đã tích chọn                      | + Nhận giá trị bật/tắt; cần xác định cách lấy số dư theo bên nguồn.                                                                                                        |
| **Bao gồm chi tiết**     | Cho phép kết chuyển kèm thông tin chi tiết theo đối tượng hoặc chiều phân tích kế toán.  | Tích chọn nếu cần giữ thông tin chi tiết khi kết chuyển. | Đã tích chọn                      | + Nhận giá trị bật/tắt; cần kiểm tra tài khoản và dữ liệu nguồn có hỗ trợ theo dõi chi tiết.                                                                               |
| **Từ ngày**              | Xác định thời điểm bắt đầu áp dụng quy tắc kết chuyển.                                   | Chọn ngày bắt đầu có hiệu lực.                           | 01/01/2026                        | + Phải là ngày hợp lệ nếu có nhập.                                                                                                                                         |
| **Đến ngày**             | Xác định thời điểm kết thúc hiệu lực của quy tắc kết chuyển.                             | Chọn ngày kết thúc áp dụng quy tắc.                      | 31/12/2026                        | + Phải là ngày hợp lệ và không nhỏ hơn Từ ngày.                                                                                                                            |
| **Trạng thái theo dõi**  | Xác định quy tắc có đang được kích hoạt để áp dụng trong hệ thống hay không.             | Bật hoặc tắt công tắc trạng thái.                        | <p>Hoạt động</p><p>Vô hiệu</p>    | + Chỉ nhận hai trạng thái: Hoạt động hoặc vô hiệu. + Quy tắc vô hiệu không được áp dụng khi kết chuyển.                                                                    |
