---
description: (Giới thiệu chức năng chạy sổ)
icon: play
---

# Chức năng chạy sổ

## <mark style="color:$primary;">Thao tác mở màn hình chức năng chạy sổ</mark>

<figure><img src="../.gitbook/assets/thao tác mở chạy sổ 1.png" alt=""><figcaption></figcaption></figure>

{% stepper %}
{% step %}
### Bước 1

Trong menu chọn danh mục Chứng từ (<mark style="color:red;">**Phím tắt Ctrl + 1**</mark>)
{% endstep %}

{% step %}
### Bước 2

Chọn chức năng Chạy sổ (<mark style="color:red;">**Phím tắt Alt + C**</mark>)
{% endstep %}
{% endstepper %}

## <mark style="color:$primary;">Giới thiệu chức năng chạy sổ</mark>

\- Chức năng Chạy sổ dùng để thực hiện xử lý và cập nhật dữ liệu kế toán theo từng tháng trên hệ thống. Sau khi nhập chứng từ, hệ thống sẽ hiện các bước xử lý như tính giá vốn, kết chuyển lãi lỗ và cập nhật số dư tài khoản, giúp dữ liệu kế toán đưuọc hoàn thiện để phục vụ việc xem báo cáo và kiểm tra số liệu.

\- Màn hình Chạy sổ cho phép lựa chọn khoảng thời gian cần xử lý, theo dõi tình trạng chạy sổ của từng tháng và kiểm tra các chứng từ chưa được đưa vào quá trình chạy sổ.

## <mark style="color:$primary;">Các khu vực chức năng trên màn hình</mark>

<figure><img src="../.gitbook/assets/màn hình chức năng chạy sổ.png" alt=""><figcaption></figcaption></figure>

#### 1. Nhóm thao tác chức năng chạy sổ

**Gồm các nút:**

* Chạy sổ (<mark style="color:red;">**Phím tắt Alt + C**</mark>): Thực hiện xử lý dữ liệu kế toán cho khoảng thời gian đã chọn. Hệ thống tiến hành các bước xử lý cần thiết như tính giá vốn, kết chuyển lãi lỗ và cập nhật số dư.
* Làm mới (<mark style="color:red;">**Phím tắt F5**</mark>): Tải lại dữ liệu trên màn hình, cập nhật trạng thái chạy sổ và số lượng chứng từ theo dữ liệu hiện tại.
* Mở báo cáo (<mark style="color:red;">**Phím tắt Alt + O**</mark>): Mở báo cáo liên quan để kiểm tra số liệu kế toán sau quá trình chạy sổ. Cụ thể là bảng cân đối phát sinh.

\- Cho phép thực hiện chạy sổ, cập nhật trạng thái và xem báo cáo liên quan.

#### 2. Chọn khoảng thời gian chạy sổ

&#x20;\- Chọn khoảng thời gian cần chạy sổ (<mark style="color:red;">**Phím tắt Alt + T**</mark>). Hệ thống sẽ hiển thị tình trạng và các tháng thuộc thời gian đã chọn để theo dõi và xử lý.

#### 3. Các thông báo tình trạng chạy sổ

&#x20;\- Thông báo các tháng không có chứng từ ghi sổ, hệ thống chỉ chuyển số dư qua các tháng này.

&#x20;\- Thông báo số lượng chứng từ nhập ngoài lượt chạy và cho phép xem lại các chứng từ này trước khi chạy số.

\- Thông báo các lỗi trong quá trình chạy sổ.

#### 4. Bảng thông tin chạy sổ theo tháng đã chọn

\- Hiển thị thông tin chi tiết của từng tháng trong khoảng thời gian lựa chọn, bao gồm số chứng từ đã ghi sổ, sổ chứng từ nhập, trạng thái chạy sổ và các bước xử lý được thực hiện.

| **Tên cột**            | **Ý nghĩa**                                                                                                                 |
| ---------------------- | --------------------------------------------------------------------------------------------------------------------------- |
| **Tháng**              | Tháng kế toán cần thực hiện chạy sổ. Mỗi dòng tương ứng với một tháng trong khoảng thời gian đã chọn.                       |
| **Chứng từ đã ghi sổ** | Số lượng chứng từ đã được ghi sổ trong tháng, phản ánh số chứng từ đã được xử lý và ghi nhận vào dữ liệu kế toán.           |
| **Chứng từ nhập**      | Số lượng chứng từ được nhập trong tháng, bao gồm các chứng từ cần được xử lý khi thực hiện chạy sổ.                         |
| **Trạng thái**         | Cho biết tình trạng xử lý chạy sổ của tháng. Ví dụ: Cần chạy là tháng chưa thực hiện chạy sổ hoặc cần chạy lại.             |
| **Các bước**           | Liệt kê các nghiệp vụ hệ thống sẽ thực hiện trong quá trình chạy sổ, như tính giá vốn, kết chuyển lãi lỗ và cập nhật số dư. |

## <mark style="color:$primary;">Hướng dẫn quy trình sử dụng chức năng chạy sổ</mark>

{% stepper %}
{% step %}
**Bước 1: Chọn khoảng thời gian (**<mark style="color:red;">**Phím tắt Alt + T**</mark>**)**

&#x20;\- Chọn khoảng thời gian tháng/năm cần chạy sổ trên bộ lọc thời gian ở góc bên phải màn hình.
{% endstep %}

{% step %}
**Bước 2: Kiểm tra dữ liệu**

\- Kiểm tra số chứng từ đã ghi sổ, số chứng từ đã nhập và trạng thái chạy sổ của từng tháng. Nếu có thông báo chứng từ nhập ngoài lượt chạy, chọn **Xem chứng từ nhập** để kiểm tra.
{% endstep %}

{% step %}
**Bước 3: Thực hiện chạy sổ**

\- Nhấn nút chạy sổ (<mark style="color:red;">**Phím tắt Alt + C**</mark>) để hệ thống thực hiện xử lý dữ liệu kế toán cho khoảng thời gian đã chọn ở **Bước 1**.
{% endstep %}

{% step %}
**Bước 4: Kiểm tra kết quả**

\- Sau khi chạy sổ hoàn tất, kiểm tra trạng thái xử lý và chọn Mở báo cáo (<mark style="color:red;">**Phím tắt Alt + O**</mark>) để xem, đối chiếu số liệu kế toán.
{% endstep %}
{% endstepper %}

{% hint style="danger" %}
### <mark style="color:$danger;">**Lưu ý khi chạy sổ**</mark>

<mark style="color:$danger;">· Kiểm tra chứng từ đã nhập đầy đủ và đúng thông tin trước khi thực hiện chạy sổ.</mark>

<mark style="color:$danger;">· Đối với các tháng không có chứng từ ghi sổ, hệ thống sẽ thực hiện chuyển số dư qua các tháng theo thông báo trên màn hình.</mark>

<mark style="color:$danger;">· Nếu có chứng từ nhập ngoài lượt chạy, người dùng nên kiểm tra các chứng từ này để đảm bảo dữ liệu được đưa vào đúng kỳ xử lý.</mark>

<mark style="color:$danger;">· Khi phát sinh thay đổi hoặc bổ sung chứng từ thuộc kỳ đã chạy, cần kiểm tra trạng thái chạy sổ và thực hiện chạy lại khi hệ thống yêu cầu.</mark>

<mark style="color:$danger;">· Nên kiểm tra báo cáo sau khi chạy sổ để đảm bảo số liệu được cập nhật đầy đủ.</mark>
{% endhint %}
