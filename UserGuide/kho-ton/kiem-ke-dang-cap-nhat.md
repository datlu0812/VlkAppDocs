# Kiểm kê (Đang cập nhật)

## <mark style="color:$primary;">Màn hình chức năng</mark>

<figure><img src="../.gitbook/assets/màn hình kiểm kê.png" alt=""><figcaption></figcaption></figure>

## <mark style="color:$primary;">Giới thiệu chức năng</mark>

\- Chức năng Kiểm kê đươc sử dụng để kiểm tra, đối chiếu số lượng vật tư, hàng hóa, thành phẩm thực tế tại kho với số lượng tồn kho được ghi nhận trên sổ kế toán.

\- Thông qua chức năng này có thể tạo phiên kiểm kê cho từng kho, xác minh ngày kiểm kê, lấy số liệu tồn kho trên sổ, nhập số lượng thực tế sau khi kiểm đếm và xác định chênh lệch giữa hai nguồn dữ liệu.

\- Sau khi hoàn tất kiểm kê, hệ thống hỗ trợ lưu phiên kiểm kê, in biên bản kiểm kê theo **mẫu 05 - VT** và sinh chứng từ điều chỉnh đối với những mặt hàng có chênh lệch.

\- Chức năng giúp doanh nghiệp:

* Kiểm tra tính chính xác của số liệu tồn kho trên phần mềm.
* Phát hiện hàng hóa thừa, thiếu so với những mặt hàng có chênh lệch.
* Theo dõi tiến độ và kết quả kiểm kê theo từng kho, từng ngày.
* Làm căn cứ lập chứng từu điều chỉnh tăng, giảm hàng tồn kho khi phát sinh chênh lệch.

## <mark style="color:$primary;">Các chức năng trên màn hình kiểm kê</mark>

#### **1. Màn hình danh sách phiên kiểm kê**

\- Đây là màn hình hiển thị các phiên kiểm kê đã được tạo trên hệ thống

<figure><img src="../.gitbook/assets/màn hình chức năng (2).png" alt=""><figcaption></figcaption></figure>

**Nhóm chức năng thao tác**

| **Tên chức năng** | **Ý nghĩa**                                                                                                 |
| ----------------- | ----------------------------------------------------------------------------------------------------------- |
| **Lấy số sổ**     | Tạo phiên kiểm kê mới bằng cách lấy số liệu tồn kho trên sổ kế toán theo kho và ngày kiểm kê được lựa chọn. |
| **Mở phiên**      | Mở phiên kiểm kê đã chọn để tiếp tục nhập số liệu, kiểm tra hoặc xem kết quả kiểm kê.                       |
| **Tải lại**       | Cập nhật lại danh sách phiên kiểm kê và trạng thái dữ liệu mới nhất.                                        |

**Nhóm thông tin tạo phiên kiểm kê**

| **Tên trường**    | **Ý nghĩa**                                                     |
| ----------------- | --------------------------------------------------------------- |
| **Kho**           | Lựa chọn kho cần thực hiện kiểm kê.                             |
| **Ngày kiểm kê**  | Xác định ngày thực hiện kiểm kê hàng hóa tại kho.               |
| **Người kiểm kê** | Người chịu trách nhiệm thực hiện hoặc ghi nhận kết quả kiểm kê. |

**Bảng danh sách phiên kiểm kê**

| Tên cột       | Ý nghĩa                                                                                                  |
| ------------- | -------------------------------------------------------------------------------------------------------- |
| Kho           | Kho được thực hiện kiểm kê.                                                                              |
| Ngày kiểm kê  | Ngày thực hiện phiên kiểm kê.                                                                            |
| Trạng thái    | Tình trạng xử lý của phiên kiểm kê, bao gồm Nháp và Đã chốt.                                             |
| Tiến độ       | Thể hiện số lượng mặt hàng đã kiểm đếm trên tổng số mặt hàng trong phiên hoặc thông báo kết quả kiểm kê. |
| Người kiểm kê | Tên người thực hiện phiên kiểm kê.                                                                       |
| Lập lúc       | Thời điểm phiên kiểm kê được tạo trên hệ thống.                                                          |

**Các trạng thái của sổ kiểm kê**

| **Trạng thái** | **Ý nghĩa**                                                                                                           |
| -------------- | --------------------------------------------------------------------------------------------------------------------- |
| **Nháp**       | Phiên kiểm kê đang trong quá trình thực hiện, người dùng có thể tiếp tục nhập số lượng thực tế và hoàn thiện dữ liệu. |
| **Đã chốt**    | Phiên kiểm kê đã hoàn tất. Hệ thống ghi nhận kết quả kiểm kê và không còn thực hiện chỉnh sửa như phiên nháp.         |

{% hint style="danger" %}
<mark style="color:$danger;">**Lưu ý:**</mark> <mark style="color:$danger;"></mark><mark style="color:$danger;">Khi lấy số sổ, hệ thống lấy số liệu tồn kho theo kho đến hết ngày kiểm kê và giữ nguyên số liệu này trong phiên, kể cả khi có chứng từ mới phát sinh sau đó.</mark>
{% endhint %}

#### 2. Màn hình chi tiết phiên kiểm kê

&#x20;\- Đây là khu vực trực tiếp nhập số lượng thực tế, theo dõi chênh lệch và xử lý kết quả kiểm kê.

<figure><img src="../.gitbook/assets/màn hình chi tiết kiểm kê.png" alt=""><figcaption></figcaption></figure>

**Nhóm các chức năng thao tác**

| **Tên chức năng**            | **Ý nghĩa**                                                                                                                                  |
| ---------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------- |
| **Lưu nháp**                 | Lưu kết quả kiểm kê đang thực hiện nhưng chưa chốt phiên, cho phép tiếp tục chỉnh sửa và hoàn thiện sau.                                     |
| **Điền theo số sổ**          | Tự động điền số lượng thực tế theo số lượng tồn trên sổ kế toán. Hỗ trợ  trong trường hợp số liệu kiểm đếm thực tế khớp với số liệu trên sổ. |
| **In 05-VT**                 | In biên bản kiểm kê vật tư, công cụ, sản phẩm, hàng hóa theo mẫu 05-VT.                                                                      |
| **Sinh chứng từ điều chỉnh** | Tạo chứng từ điều chỉnh tăng hoặc giảm hàng tồn kho dựa trên kết quả chênh lệch kiểm kê.                                                     |
| **Danh sách phiên**          | Quay lại màn hình danh sách các phiên kiểm kê đã tạo.                                                                                        |

**Nhóm công cụ hỗ trợ**

| **Tên chức năng**                   | **Ý nghĩa**                                                                     |
| ----------------------------------- | ------------------------------------------------------------------------------- |
| **Chỉ hiện chênh lệch và chưa đếm** | Lọc danh sách, chỉ hiển thị các mặt hàng có chênh lệch hoặc chưa được kiểm đếm. |
| **Tìm theo mã hoặc tên hàng**       | Tìm kiếm nhanh mặt hàng cần kiểm kê theo mã hàng hoặc tên hàng.                 |

**Các thông tin trên bảng kiểm kê**

| **Tên cột**            | **Ý nghĩa**                                                                                           |
| ---------------------- | ----------------------------------------------------------------------------------------------------- |
| **STT**                | Số thứ tự của mặt hàng trong danh sách kiểm kê.                                                       |
| **Mã hàng**            | Mã định danh của vật tư, hàng hóa hoặc thành phẩm được đưa vào phiên kiểm kê.                         |
| **Tên mặt hàng**       | Tên của mặt hàng tương ứng với mã hàng.                                                               |
| **ĐVT**                | Đơn vị tính của mặt hàng.                                                                             |
| **Đơn giá**            | Đơn giá được sử dụng để tính giá trị hàng tồn kho và xác định giá trị chênh lệch.                     |
| **Số lượng sổ**        | Số lượng tồn kho được ghi nhận trên sổ kế toán tại ngày kiểm kê.                                      |
| **Giá trị sổ**         | Tổng giá trị hàng tồn kho theo số liệu trên sổ kế toán.                                               |
| **Thực đếm**           | Số lượng hàng hóa thực tế được kiểm đếm tại kho.  nhập thông tin này sau khi kiểm kê.                 |
| **Giá trị thực tế**    | Tổng giá trị hàng hóa được tính theo số lượng thực đếm và đơn giá tương ứng.                          |
| **Chênh lệch**         | Số lượng chênh lệch giữa thực tế kiểm đếm và số lượng trên sổ kế toán.                                |
| **Giá trị chênh lệch** | Giá trị tiền tương ứng với phần hàng hóa chênh lệch.                                                  |
| **Trạng thái**         | Kết quả đối chiếu giữa số lượng thực tế và số lượng trên sổ, bao gồm Khớp, Thừa, Thiếu hoặc Chưa đếm. |

**Nguyên tắc xác định chênh lệch:**

<p align="center"><mark style="color:$primary;"><strong>Chênh lệch = Thực đếm - Số lượng sổ</strong></mark></p>

* **Khớp:** Số lượng thực tế bằng số lượng trên sổ.
* **Thừa:** Số lượng thực tế lớn hơn số lượng trên sổ.
* **Thiếu:** Sổ lượng thực tế nhỏ hơn số lượng trên sổ.
* **Chưa đếm:** Chưa nhập số lượng kiểm đếm thực tế.

**Một số thông báo kết quả trên màn hình:**

* **Không có chênh lệch nên không tạo chứng từ:** Tất cả mặt hàng đã kiểm kê đều khớp với số liệu trên sổ, không phát sinh chứng từ điều chỉnh.
* **Chênh lệch:** Có mặt hàng thừa hoặc thiếu so với số liệu kế toán, cần kiểm tra và xử lý.

## <mark style="color:$primary;">Hướng dẫn sử dụng chức năng kiểm kê</mark>

{% stepper %}
{% step %}
#### Bước 1. Tạo phiên kiểm kê mới

\- Tại màn hình Kho chọn chức năng Kiểm kê (<mark style="color:red;">**Phím tắt Alt +**</mark> ) và thực hiện:

1. Chọn kho cần kiểm kê tại trường Kho (<mark style="color:red;">**Phím tắt Alt +**</mark> ).
2. Chọn ngày thực hiện kiểm kê tại trường ngày kiểm kê (<mark style="color:red;">**Phím tắt Alt + T**</mark>)
3. Nhập tên người thực hiện tại trường dữ liệu Người kiểm kê (Mạc định sẽ lấy theo tên tài khoản đăng nhập)
4. Nhấn Lấy số sổ để tạo phiên kiểm kê mới.

\- Sau khi tạo phiên, hệ thống lấy danh sách mặt hàng và số lượng tồn kho theo sổ kế toán của kho đến hết ngày kiểm kê.
{% endstep %}

{% step %}
#### Nhập số lượng kiểm đếm thực tế

\- Tại màn hình chi tiết phiên kiểm kê:

1. Kiểm tra danh sách mặt hàng được hệ thống lấy từ sổ kế toán.
2. Tiến hành kiểm đếm số lượng thực tế của từng mặt hàng tại kho.
3. Nhập số lượng thực tế vào cột Thực đếm.
4. Kiểm tra các thông tin Giá trị thực tế, chênh lệch, giá trị chênh lệch và trạng thái.

\- Hệ thống tự động tính toán và xác định tình trạng chênh lệch sau khi nhập số lượng thực tế.
{% endstep %}

{% step %}
#### Bước 3. Lưu kết quả kiểm kê

&#x20;\- Sau khi nhập số lượng thực tế, nhấn Lưu nháp để lưu lại kết quả kiểm kê, có thể tiếp tục mở phiên kiểm kê đã lưu để bổ sung hoặc điều chỉnh số liệu trước khi chốt phiên.
{% endstep %}

{% step %}
#### Bước 4. Kiểm tra kết quả kiểm kê

&#x20;\- Sử dụng chức năng Chỉ hiện chênh lệch và chưa đếm để lọc những mặt hàng cần kiểm tra lại.

\- Đối chiếu các thông tin:

* Số lượng sổ
* Số lượng thực tế
* Số lượng chênh lệch
* Giá trị chênh lệch

&#x20;\- Nếu phát hiện sai lệch, cần kiểm tra lại số liệu kiểm đếm hoặc thông tin hàng hóa trước khi thực hiện các bước tiếp theo.
{% endstep %}

{% step %}
#### Bước 5. In biên bản kiểm kê

\- Nhấn In 05-VT để mở giao diện in biên bản kiểm kê.

\- Tại giao diện cấu hình in, có thể bổ sung các thông tin:

<table data-header-hidden data-search="false"><thead><tr><th></th><th></th></tr></thead><tbody><tr><td><strong>Tên trường</strong></td><td><strong>Ý nghĩa</strong></td></tr><tr><td><strong>Thời điểm kiểm kê</strong></td><td>Ghi nhận giờ thực hiện kiểm kê.</td></tr><tr><td><strong>Trưởng ban/Chủ tịch Hội đồng</strong></td><td>Họ tên và chức vụ của người đứng đầu hội đồng kiểm kê.</td></tr><tr><td><strong>Đại diện</strong></td><td>Thông tin người đại diện tham gia hội đồng kiểm kê.</td></tr><tr><td><strong>Ủy viên thứ nhất</strong></td><td>Họ tên, chức vụ và thông tin đại diện của thành viên thứ nhất.</td></tr><tr><td><strong>Ủy viên thứ hai</strong></td><td>Họ tên, chức vụ và thông tin đại diện của thành viên thứ hai.</td></tr><tr><td><strong>Lưu cấu hình</strong></td><td>Lưu lại thông tin đã thiết lập để sử dụng cho những lần in tiếp theo.</td></tr></tbody></table>
{% endstep %}

{% step %}
#### Bước 6. Sinh chứng từ điều chỉnh

&#x20;\- Sau khi hoàn tấ kiểm kê và xác định có chênh lệch, nhấn Sinh chứng từ điều chỉnh để tạo chứng từ điều chỉnh tăng hoặc giảm hàng tồn kho theo kết quả kiểm kê.

* **Hàng hóa thừa:** Làm căn cứ ghi nhận điều chỉnh tăng hàng tồn kho.
* **Hàng hóa thiếu:** Làm căn cứ ghi nhận điều chỉnh giảm hàng tồn kho.

\- Trước khi sinh chứng từ, cần kiểm tra số liệu và đảm bảo thông tin đơn giá của các mặt hàng đã đầy đủ.
{% endstep %}
{% endstepper %}

**Ví dụ minh họa nghiệp vụ kiểm kê**

\- Doanh nghiệp tiến hành kiểm kê mặt hàng Gương nhôm 4ly tại khi KH001.

| **Nội dung**         | **Số lượng** |
| -------------------- | ------------ |
| **Số lượng trên sổ** | 150          |
| **Số lượng thực tế** | 145          |
| **Chênh lệch**       | -5           |
| **Trạng thái**       | Thiếu        |

&#x20;\- Kết quả kiểm kê cho thấy mặt hàng bị thiếu 5 đơn vị so với số liệu trên kế toán.

\- Cần xác định nguyên nhân thiếu hụt, lập biên bản kiểm kê và thực hiện sinh chứng từ điều chỉnh giảm hàng tồn kho theo quy trình của doanh nghiệp.

{% hint style="danger" %}
<mark style="color:$danger;">**Lưu ý:**</mark>

* <mark style="color:$danger;">Cần chọn đúng kho và ngày kiểm kê trước khi lấy số liệu trên sổ.</mark>
* <mark style="color:$danger;">Số liệu tồn kho trên sổ được cố định theo thời điểm lấy số sổ của phiên kiểm kê.</mark>
* <mark style="color:$danger;">Cần nhập đầy đủ số lượng thực tế cho các mặt hàng trước khi hoàn tất kiểm kê.</mark>
* <mark style="color:$danger;">Kiểm tra kỹ các mặt hàng có trạng thái Thừa hoặc Thiếu để tránh sai lệch do nhập nhầm số lượng.</mark>
* <mark style="color:$danger;">Nếu không phát sinh chênh lệch, hệ thống có thể chốt phiên mà không cần tạo chứng từ điều chỉnh.</mark>
* <mark style="color:$danger;">Trước khi sinh chứng từ điều chỉnh, cần kiểm tra đơn giá và dữ liệu tính giá của hàng hóa.</mark>
* <mark style="color:$danger;">Biên bản kiểm kê cần được lưu trữ để phục vụ công tác đối chiếu và kiểm tra kế toán.</mark>
{% endhint %}
