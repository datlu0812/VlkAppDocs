---
description: (Giới thiệu chức năng tồn kho đầu kỳ)
---

# Tồn kho đầu kỳ

## <mark style="color:$primary;">Màn hình chức năng</mark>

<figure><img src="../.gitbook/assets/màn hình chức năng tồn kho đầu kỳ.png" alt=""><figcaption></figcaption></figure>

## <mark style="color:$primary;">Giới thiệu chức năng</mark>

\- Chức năng Tồn kho đầu kỳ được sử dụng để khai báo và quản lý số lượng, giá trị tồn kho ban đầu của vật tư, hàng hóa, thành phẩm tại thời điểm bắt đầu hạch toán trên phần mềm.

\- Chức năng cho phép lựa chọn kho, kỳ nhận tồn và nhập thông tin tồn kho cho từng mặt hàng, bao gồm mã hàng, tài khoản kho, số lượng, giá trị và đơn giá.

\- Dữ liệu tồn kho đầu kỳ là cơ sở để hệ thống theo dõi tình hình nhập, xuất, tồn và tính giá vốn hàng hóa tỏng các kỳ kế toán tiếp theo.

#### Các bước mở chức năng tồn kho đầu kỳ

Bước 1: Vào danh mục **Kho** **(**<mark style="color:red;">**Phím tắt Ctrl + 5**</mark>**)**

Bước 2: Chọn chức năng tồn kho đầu kỳ **(**<mark style="color:red;">**Phím tắt Alt + O**</mark>**)**, trong mục xử lý kho **(**<mark style="color:red;">**Phím tắt F2**</mark>**)**

## <mark style="color:$primary;">Các nhóm chức năng trên màn hình</mark>

#### 1. Nhóm chức năng thao tác

\- Bao gồm các chức năng thực hiện xử lý dữ liệu tồn kho đầu kỳ

| **Tên chức năng**                                                            | **Ý nghĩa**                                                                          |
| ---------------------------------------------------------------------------- | ------------------------------------------------------------------------------------ |
| **Lưu (**<mark style="color:red;">**Phím tắt Ctrl + S**</mark>**)**          | Lưu thông tin tồn kho đầu kỳ sau khi hoàn tất việc khai báo hoặc điều chỉnh dữ liệu. |
| **Thêm mặt hàng (**<mark style="color:red;">**Phím tắt Alt + N**</mark>**)** | Thêm một dòng dữ liệu mới để khai báo tồn kho đầu kỳ cho mặt hàng khác.              |
| **Nạp dữ liệu (**<mark style="color:red;">**Phím tắt Alt + I**</mark>**)**   | Nhập dữ liệu tồn kho đầu kỳ từ nguồn dữ liệu bên ngoài vào hệ thống.                 |
| **Tải lại (**<mark style="color:red;">**Phím tắt F5**</mark>**)**            | Tải lại dữ liệu trên màn hình để cập nhật thông tin tồn kho đầu kỳ hiện tại.         |

#### 2. Nhóm thông tin kho và nhận tồn

&#x20;\- Gồm các chức năng liên quan đến xác định kho và thời gian để thực hiện xử lý.

| **Tên trường**                                                             | **Ý nghĩa**                                                                                                       |
| -------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------- |
| **Kho (**<mark style="color:red;">**Phím tắt Alt + H**</mark>**)**         | Lựa chọn kho cần khai báo tồn kho đầu kỳ. chọn kho tương ứng trong danh sách kho đã được thiết lập trên hệ thống. |
| **Kỳ nhận tồn (**<mark style="color:red;">**Phím tắt Alt + T**</mark>**)** | Xác định tháng và năm bắt đầu ghi nhận số liệu tồn kho đầu kỳ.                                                    |

#### &#x20;3. Khu vực cảnh báo, thông báo thông tin

\- Hệ thống hiển thị thông tin về kỳ nhận tồn và cảnh báo khi thực hiện điều chỉnh tồn kho đầu kỳ.

* **Thông tin kỳ nhận tồn:** Cho biết kỳ bắt đầu hạch toán và ngày phiếu ghi nhận tồn kho.

**Ví dụ:** Kỳ bắt đầu hạch toán 01/2026, phiếu ghi ngày 31/12/2025.

* **Cảnh báo điều chỉnh tồn kho đầu kỳ:** Khi đơn vị đã cso chứng từ ghi sổ, hệ thống cảnh báo việc thay đổi số dư tồn kho có thể ảnh hưởng đến giá vốn và số liệu kho của các kỳ sau.

\- Thông báo cũng hướng dẫn sau khi lưu cần nhập về đối ứng ở mục Số dư đầu kỳ để số dư cân, sau đó thực hiện chạy sổ lại từ tháng đầu.

#### &#x20;4. Bảng khai báo thông tin tồn kho đầu kỳ

&#x20;\- Đây là khu vực trực tiếp khai báo số lượng và giá trị tồn kho ban đầu cho từng mặt hàng.

<table data-header-hidden data-search="false"><thead><tr><th></th><th></th></tr></thead><tbody><tr><td><strong>Tên cột</strong></td><td><strong>Ý nghĩa</strong></td></tr><tr><td><strong>STT</strong></td><td>Số thứ tự của mặt hàng trong danh sách, được hệ thống tự động đánh số.</td></tr><tr><td><strong>Mã hàng</strong></td><td>Mã định danh của vật tư, hàng hóa hoặc thành phẩm. lựa chọn mã hàng từ danh mục đã khai báo.</td></tr><tr><td><strong>Tên mặt hàng</strong></td><td>Tên của mặt hàng tương ứng với mã hàng được lựa chọn.</td></tr><tr><td><strong>ĐVT</strong></td><td>Đơn vị tính của mặt hàng, được hệ thống hiển thị theo thông tin trong danh mục hàng hóa.</td></tr><tr><td><strong>TK kho</strong></td><td>Tài khoản kế toán dùng để theo dõi giá trị hàng tồn kho. lựa chọn tài khoản phù hợp với mặt hàng.</td></tr><tr><td><strong>Số lượng</strong></td><td>Số lượng hàng hóa thực tế còn tồn tại tại thời điểm nhận tồn đầu kỳ.</td></tr><tr><td><strong>Giá trị</strong></td><td>Tổng giá trị tồn kho đầu kỳ của mặt hàng được khai báo.</td></tr><tr><td><strong>Đơn giá</strong></td><td>Giá trị tính trên một đơn vị hàng hóa tồn kho đầu kỳ.</td></tr><tr><td><strong>Xóa (Phím tắt Alt + X)</strong></td><td>Sử dụng mũi tên lên xuống để chọn loại hàng cần xóa sau đó Xóa dòng mặt hàng khỏi danh sách khai báo tồn kho đầu kỳ.</td></tr></tbody></table>

## <mark style="color:$primary;">Hướng dẫn sử dụng chức năng</mark>

{% stepper %}
{% step %}
#### Bước 1. Chọn kho

\- Tại trường Kho **(**<mark style="color:red;">**Phím tắt Alt + H**</mark>**)**, lựa chọn kho cần khai báo tồn kho đầu kỳ.
{% endstep %}

{% step %}
#### Bước 2. Chọn kỳ nhận tồn

\- Tại trường Kỳ nhận tồn **(**<mark style="color:red;">**Phím tắt Alt + T**</mark>**)**, chọn tháng và năm bắt đầu ghi nhận số liệu tồn kho.
{% endstep %}

{% step %}
#### Bước 3. Thêm mặt hàng

\- Nhấn Thêm mặt hàng **(**<mark style="color:red;">**Phím tắt Alt + A**</mark>**)** để tạo dòng khai báo mới.
{% endstep %}

{% step %}
#### Bước 4. Nhập thông tin tồn kho

\- Tại dòng dữ liệu vừa thêm, thực hiện điền các thông tin:

* Chọn mã hàng cần khai báo.
* Kiểm tra tên mặt hàng và đơn vị tính.
* Chọn tài khoản kho tương ứng
* Nhập số lượng tồn đầu kỳ
* Nhập giá trị tồn kho
* Kiểm tra đơn giá của mặt hàng

\- Thực hiện tương tự đối với các mặt hàng khác.
{% endstep %}

{% step %}
#### Bước 5. Lưu dữ liệu

\- Sau khi hoàn tất khai báo, nhấn Lưu **(**<mark style="color:red;">**Phím tắt Ctrl + S**</mark>**)** để ghi nhận thông tin tồn kho đầu kỳ vào hệ thống.
{% endstep %}
{% endstepper %}

**Ví dụ minh họa:**

Một doanh nghiệp bắt đầu sử dụng phần mềm từ tháng 01/2026, có mặt hàng Gương nhôm 4 ly tồn kho tại kho KH001 với thông tin:

<table data-header-hidden data-search="false"><thead><tr><th></th><th></th></tr></thead><tbody><tr><td><strong>Thông tin</strong></td><td><strong>Giá trị</strong></td></tr><tr><td><strong>Mã hàng</strong></td><td>GN0041</td></tr><tr><td><strong>Tên mặt hàng</strong></td><td>Gương nhôm 4ly (1.25*2.14)</td></tr><tr><td><strong>ĐVT</strong></td><td>m2</td></tr><tr><td><strong>TK kho</strong></td><td>156</td></tr><tr><td><strong>Số lượng</strong></td><td>150</td></tr><tr><td><strong>Giá trị</strong></td><td>150.000.000 đồng</td></tr><tr><td><strong>Đơn giá</strong></td><td>1.000.000 đồng</td></tr></tbody></table>

&#x20;⇒ Sau khi khai báo và lưu, hệ thống ghi nhận số liệu tồn kho ban đầu để tiếp tục theo dõi các nghiệp vụ nhập, xuất và tồn kho phát sinh từ kỳ kế toán 01/2026.

{% hint style="danger" %}
<mark style="color:$danger;">**Lưu ý khi sử dụng:**</mark>

* <mark style="color:$danger;">Mặt hàng cần được khai báo trong danh mục vật tư, hàng hóa, thành phẩm trước khi thực hiện nhận tồn.</mark>
* <mark style="color:$danger;">Cần lựa chọn đúng kho và tài khoản kho tương ứng với từng mặt hàng.</mark>
* <mark style="color:$danger;">Kiểm tra số lượng, giá trị và đơn giá để đảm bảo dữ liệu tồn kho đầu kỳ chính xác.</mark>
* <mark style="color:$danger;">Nếu đơn vị đã có chứng từ ghi sổ, việc điều chỉnh tồn kho đầu kỳ có thể ảnh hưởng đến giá vốn và số liệu kho của các kỳ sau.</mark>
* <mark style="color:$danger;">Khi thực hiện điều chỉnh theo cảnh báo của hệ thống, cần nhập số dư đối ứng tại mục Số dư đầu kỳ để đảm bảo cân đối kế toán và chạy sổ lại từ tháng đầu.</mark>
{% endhint %}
