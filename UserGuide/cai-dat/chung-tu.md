---
description: (Cài đặt chứng từ)
icon: file
---

# Chứng từ

## <mark style="color:$primary;">Màn hình chức năng</mark>

<figure><img src="../.gitbook/assets/màn hình 1.png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/màn hình 2.png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/màn hình 3.png" alt=""><figcaption></figcaption></figure>

## <mark style="color:$primary;">Giới thiệu chức năng</mark>

&#x20;\- Chức năng cài đặt chứng từ cho phép thiết lập các quy tắc và thông số mặc định liên quan đến việc lập, quản lý, xử lý và ghi nhận chứng từ kế toán trên phần mềm.

\- Chức năng có thể tùy chỉnh cách đánh số chứng từ, thiết lập thông tin hóa đơn điện tử, quy định các điều kiện nhập liệu, thiết lập quy tắc tính thuế và thanh toán. Những thiết lập này giúp thống nhất quy trình lập chứng từ, hạn chế sai sót trong quá trình nhập liệu và phù hợp với quy trình quản lý của từng doanh nghiệp.

#### 1. Nhóm đánh số chứng từ.

\- Nhóm đánh số chứng từ cho phép thiết lập quy tắc tự động tạo số chứng từ, định dạng số chứng từ và cách sắp xếp chứng từ trên hệ thống.

\- Nhóm này giúp đảm báo mỗi chứng từ được cấp số theo một quy tắc thống nhất, dễ nhận biết, tra cứu và quản lý trong quá trình hạch toán kế toán.

| **Tên trường**                | **Ý nghĩa**                                                                                  | **Cách thiết lập**                                                                           | **Ví dụ**                                            |
| ----------------------------- | -------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------- | ---------------------------------------------------- |
| **Tự động đánh số**           | Cho phép phần mềm tự động tạo số chứng từ khi lập chứng từ mới.                              | Bật để phần mềm tự cấp số chứng từ, tắt nếu muốn tự nhập số theo quy trình của doanh nghiệp. | Bật: Phần mềm tự sinh số CT001, CT002...             |
| **Cho nhập số thủ công**      | Cho phép tự nhập hoặc điều chỉnh số chứng từ thay vì sử dụng hoàn toàn số tự động.           | Bật nếu muốn cho phép nhập số chứng từ bằng tay.                                             |   nhập số PT001.                                     |
| **Định dạng đánh số**         | Quy định cấu trúc tạo số chứng từ, bao gồm các thành phần như mã loại chứng từ và số thứ tự. | Chọn định dạng đánh số phù hợp.                                                              | Loại + Số: BH00001.                                  |
| **Số ký tự phân số**          | Quy định số lượng chữ số được sử dụng để hiển thị phần số thứ tự của chứng từ.               | Nhập số lượng chữ số mong muốn.                                                              | Nhập 5: 00001, 00002, 00003...                       |
| **Đặt lại số theo năm**       | Cho phép phần mềm bắt đầu lại số thứ tự chứng từ khi chuyển sang năm tài chính mới.          | Bật nếu muốn số chứng từ được đánh lại từ đầu mỗi năm.                                       | Năm 2026: BH00001; năm 2027: BH00001.                |
| **Tiền tố chứng từ**          | Cho phép thiết lập tiền tố riêng cho từng loại chứng từ nhằm phân biệt các nhóm chứng từ.    | Khai báo tiền tố tương ứng với từng loại chứng từ.                                           | PT cho phiếu thu, PC cho phiếu chi, BH cho bán hàng. |
| **Sắp xếp chứng từ mặc định** | Quy định thứ tự hiển thị danh sách chứng từ khi truy cập màn hình quản lý chứng từ.          | Chọn tiêu chí sắp xếp phù hợp.                                                               | Ngày + Loại + Số chứng từ.                           |

**Giải thích thêm một số thiết lập:**

* Tự động đánh số: Khi được bật, phần mềm sẽ tự động cấp số cho chứng từ theo quy tắc đã thiết lập. Không cần nhập số thứ tự mỗi lần lập chứng từ.
* Định dạng đánh số: Giúp doanh nghiệp xây dựng quy tắc đặt số chứng từ thống nhất. Ví dụ: chứng từ bán hàng có thể sử dụng tiền tố **BH** kết hợp với số thứ tự.

#### 2. Nhóm hóa đơn điện tử

\- Nhóm hóa đơn điện tử cho phép thiết lập các thông tin mặc định và cấu hình kết nối liên quan đến việc thiết lập, phát hành hóa đơn điện tử trên phần mềm.

\- Các thiết lập trong nhóm này giúp đảm bảo thông tin hóa đơn được sử dụng thống nhất, thuận tiện khi lập hóa đơn và kết nối với nhà cung cấp dịch vụ hóa đơn điện tử.

| **Tên trường**                   | **Ý nghĩa**                                                                  | **Cách thiết lập**                                                            | **Ví dụ**              |
| -------------------------------- | ---------------------------------------------------------------------------- | ----------------------------------------------------------------------------- | ---------------------- |
| **Seri hóa đơn mặc định**        | Xác định ký hiệu seri hóa đơn được sử dụng mặc định khi lập hóa đơn điện tử. | Nhập ký hiệu seri hóa đơn do đơn vị phát hành hoặc đăng ký sử dụng.           | 1C24TAA                |
| **Mẫu số hóa đơn**               | Quản lý thông tin mẫu số hóa đơn điện tử mà doanh nghiệp sử dụng.            | Truy cập để khai báo hoặc lựa chọn mẫu số hóa đơn phù hợp.                    | Mẫu số 1               |
| **Nhà cung cấp hóa đơn điện tử** | Thiết lập thông tin kết nối với đơn vị cung cấp dịch vụ hóa đơn điện tử.     | Chọn hoặc cấu hình nhà cung cấp hóa đơn điện tử mà doanh nghiệp đang sử dụng. | VNPT, Viettel, MISA... |

**Mục đích sử dụng:**

* Thiết lập sẵn ký hiệu và mẫu số hóa đơn, hạn chế việc nhập lại thông tin khi lập hóa đơn.
* Quản lý thông tin mẫu hóa đơn doanh nghiệp đang sử dụng.
* Hỗ trợ kết nối với nhà cung cấp dịch vụ hóa đơn điện tử để thực hiện các nghiệp vụ phát hành hóa đơn nếu phần mềm có tích hợp.

#### 3. Nhóm quy tắc nhập liệu

\- Nhóm quy tắc nhập liệu cho phép thiết lập các quy định trong quá trình lập và xử lý chứng từ kế toán. Các thiết lập này giúp kiểm soát thao tác nhập liệu chứng từ, đảm bảo chứng từ được nhập đầy đủ thông tin và tuân thủ quy trình kế toán của doanh nghiệp.

\- Đây là nhóm có nhiều thiết lập ảnh hưởng trực tiếp đến quá trình lập, lưu và ghi sổ chứng từ.

| **Tên trường**                   | **Ý nghĩa**                                                                                  | **Cách thiết lập**                                                                                                 | **Ví dụ**                                                                                      |
| -------------------------------- | -------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------- |
| **Tự động ghi sổ**               | Cho phép phần mềm tự động ghi sổ chứng từ sau khi lập và lưu chứng từ mới.                   | Bật để tự động ghi sổ; tắt nếu muốn kiểm tra chứng từ trước khi ghi sổ.                                            | Bật: Chứng từ được tự động ghi sổ sau khi lưu.                                                 |
| **Sửa chứng từ đã ghi sổ**       | Cho phép chỉnh sửa nội dung chứng từ ngay cả khi chứng từ đã được ghi sổ.                    | Bật nếu cho phép chỉnh sửa; tắt để hạn chế chỉnh sửa chứng từ đã ghi sổ.                                           | Bật: có thể sửa nội dung chứng từ đã ghi sổ.                                                   |
| **Diễn giải bắt buộc**           | Quy định phải nhập nội dung diễn giải khi lập chứng từ.                                      | Bật để yêu cầu nhập diễn giải trước khi lưu chứng từ.                                                              | Mua hàng hóa phục vụ hoạt động kinh doanh.                                                     |
| **Mẫu diễn giải mặc định**       | Cho phép thiết lập nội dung diễn giải tự động được tạo sẵn khi lập chứng từ mới.             | Nhập nội dung mẫu hoặc sử dụng các biến thông tin có sẵn để phần mềm tự động điền dữ liệu.                         | Phiếu nhập kho hàng hóa tháng 10/2026.                                                         |
| **Quy tắc tính giá bảng kê**     | Thiết lập cách thức tính giá trị trên bảng kê chi tiết của chứng từ.                         | Chọn phương thức tính giá theo tùy chọn mà phần mềm cung cấp.                                                      | Theo tùy chọn đang được thiết lập trên phần mềm.                                               |
| **Giữ thông tin chứng từ trước** | Cho phép giữ lại một số thông tin từ chứng từ vừa lưu khi chọn chức năng lưu và tạo mới.     | Bật để kế thừa thông tin từ chứng từ trước; tắt nếu muốn tạo chứng từ mới với các trường thông tin được làm trống. | Lưu phiếu chi trước, chọn tạo mới và tiếp tục sử dụng thông tin đối tượng của phiếu chi trước. |
| **Phê duyệt trước khi ghi sổ**   | Thiết lập quy trình yêu cầu chứng từ phải được phê duyệt trước khi thực hiện ghi sổ kế toán. | Truy cập để thiết lập quy trình hoặc đối tượng có quyền phê duyệt theo chức năng phần mềm.                         | Chứng từ do nhân viên lập cần được kế toán trưởng phê duyệt trước khi ghi sổ.                  |

**Giải thích chi tiết các trường mẫu diễn giải mặc định**

\- Trường mẫu diễn giải mạc định cho phép thiết lập sẵn nội dung diễn giải cho chứng từ. Phần mềm có thể tự động thay thế các biến thông tin bằng dữ liệu thực tế của chứng từ khi lập mới.

**Các biến thông tin được hỗ trợ trên giao diện gồm:**

| **Biến thông tin**    | **Ý nghĩa**                               | **Ví dụ nội dung được thay thế** |
| --------------------- | ----------------------------------------- | -------------------------------- |
| **Tên loại chứng từ** | Tên của loại chứng từ đang lập.           | Phiếu thu                        |
| **Mã loại chứng từ**  | Mã nhận diện loại chứng từ.               | PT                               |
| **Ngày chứng từ**     | Ngày lập chứng từ.                        | 06/10/2026                       |
| **Ngày (dd)**         | Ngày trong tháng của chứng từ.            | 06                               |
| **Tháng (MM)**        | Tháng lập chứng từ.                       | 10                               |
| **Năm (yyyy)**        | Năm lập chứng từ.                         | 2026                             |
| **Tên đối tượng**     | Tên đối tượng liên quan đến chứng từ.     | Công ty TNHH ABC                 |
| **Đối tượng bên Nợ**  | Đối tượng hạch toán được khai báo bên Nợ. | Công ty TNHH ABC                 |
| **Đối tượng bên Có**  | Đối tượng hạch toán được khai báo bên Có. | Công ty TNHH XYZ                 |
| **Số hóa đơn**        | Số hóa đơn liên quan đến chứng từ.        | 0000123                          |
| **Ký hiệu hóa đơn**   | Ký hiệu của hóa đơn liên quan.            | 1C24TAA                          |
| **Tài khoản Nợ**      | Tài khoản kế toán được ghi nhận bên Nợ.   | 111                              |
| **Tài khoản Có**      | Tài khoản kế toán được ghi nhận bên Có.   | 511                              |
| **Số tiền**           | Giá trị tiền của nghiệp vụ kế toán.       | 5.000.000                        |
| **Loại tiền**         | Loại tiền tệ được sử dụng trong chứng từ. | VND                              |
| **Tiền hàng hóa**     | Tổng giá trị tiền hàng hóa trên chứng từ. | 5.000.000                        |

**Ví dụ sử dụng thiết lập mẫu diễn giải:**

<p align="center"><em>(Tên loại chứng từ) - (Tên đối tượng) - Ngày (Ngày chứng từ)</em></p>

* Khi lập một phiếu thu cho Công ty TNHH ABC vào ngày 06/12/2026, phần mềm có thể tự động tạo nội dung diễn giải dựa vào thiết lập trên:

<p align="center"><em>(Phiếu thu) - (Công ty TNHH ABC) - ngày(06/10/2026)</em></p>

\- Nếu để trống trường này, phần mềm sẽ sử dụng mẫu diễn giải mặc định theo loại chứng từ.

#### 4. Nhóm thuế và thanh toán

\- Nhóm thuế và thanh toán cho phép thiết lập các thông tin mặc định liên quan đến thuế, thời hạn và phương thức thanh toán khi lập chứng từ kế toán.

\- Những thiết lập này giúp phần mềm hỗ trợ tính toán thuế, xác định thời hạn thanh toán và chuẩn hóa thông tin thanh toán trên chứng từ, giảm thao tác nhập liệu thủ công.

| **Tên trường**                      | **Ý nghĩa**                                                                                                           | **Cách thiết lập**                                                            | **Ví dụ**                                                           |
| ----------------------------------- | --------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------- | ------------------------------------------------------------------- |
| **Thuế suất mặc định (%)**          | Xác định mức thuế suất được phần mềm tự động đề xuất khi lập chứng từ có phát sinh thuế.                              | Nhập hoặc chọn mức thuế suất mặc định phù hợp với hoạt động của doanh nghiệp. | 10%                                                                 |
| **Tự động tính thuế**               | Cho phép phần mềm tự động tính tiền thuế dựa trên dữ liệu hàng hóa, dịch vụ và thuế suất được khai báo trên chứng từ. | Bật để phần mềm tự tính tiền thuế; tắt nếu muốn nhập tiền thuế thủ công.      | Tiền hàng 10.000.000 đồng, thuế suất 10%, tiền thuế 1.000.000 đồng. |
| **Thời hạn thanh toán mặc định**    | Xác định số ngày thanh toán được đề xuất khi lập chứng từ liên quan đến công nợ.                                      | Nhập số ngày thanh toán mặc định của doanh nghiệp.                            | 30 ngày kể từ ngày chứng từ.                                        |
| **Phương thức thanh toán mặc định** | Xác định phương thức thanh toán được tự động đề xuất khi lập chứng từ.                                                | Chọn phương thức thanh toán thường được doanh nghiệp sử dụng.                 | Tiền mặt hoặc chuyển khoản.                                         |
| **In chứng từ nháp**                | Cho phép in chứng từ ngay cả khi chứng từ chưa được ghi sổ kế toán.                                                   | Bật để cho phép in chứng từ nháp; tắt nếu chỉ cho phép in chứng từ đã ghi sổ. | In phiếu chi để kiểm tra trước khi ghi sổ.                          |
| **Bắt buộc đính kèm**               | Yêu cầu đính kèm tệp tài liệu liên quan trước khi lưu chứng từ.                                                       | Bật để bắt buộc đính kèm tệp; tắt nếu không yêu cầu tài liệu đính kèm.        | Đính kèm hóa đơn, hợp đồng hoặc phiếu giao hàng.                    |

{% hint style="danger" %}
<mark style="color:$danger;">**Lưu ý khi sử dụng chức năng cài đặt chứng từ:**</mark>

* <mark style="color:$danger;">Nên thiết lập các quy tắc đánh số chứng từ trước khi bắt đầu nhập liệu để đảm bảo số chứng từ được tạo thống nhất.</mark>
* <mark style="color:$danger;">Các thiết lập như tự động ghi sổ, cho phép sửa chứng từ đã ghi sổ và phê duyệt trước khi ghi sổ cần được cân nhắc theo quy trình kiểm soát nội bộ của doanh nghiệp.</mark>
* <mark style="color:$danger;">Thuế suất mạc định chỉ có tính chất đề xuất cần kiểm tra mức thuế suất áp dụng thực tế cho từng nghiệp vụ.</mark>
* <mark style="color:$danger;">Việc thay đổi các thiết lập có thể ảnh hưởng đến quá trình lập và xử lý chứng từ sau này. Vì vậy, nên kiểm tra kỹ trước khi lưu cấu hình.</mark>
{% endhint %}

