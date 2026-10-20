---
description: (Giới thiệu chức năng sao lưu & khôi phục kho dữ liệu)
icon: trash-can-undo
---

# Sao lưu & Khôi phục kho dữ liệu

## <mark style="color:$primary;">1. Chức năng sao lưu kho dữ liệu</mark>

\- Chức năng [**Sao lưu kho dữ liệu**](sao-luu-kho-du-lieu.md) cho phép tạo và lưu lại một bản sao của kho dữ liệu kế toán đang sử dụng. Bản sao lưu giúp bảo vệ dữ liệu kế toán, hạn chế nguy cơ mất dữ liệu khi xảy ra sự cố hệ thống, lỗi phần mềm hoặc trong quá trình nâng cấp, thay đổi thiết bị.

\- Ngoài ra có thể thực hiện sao lưu định kỳ để lưu giữ thông tin kế toán tại từng thời điểm, phục vụ việc khôi phục dữ liệu khi cần thiết.

**Ví dụ:** Cuối tháng, kế toán thực hiện sao lưu kho dữ liệu để lưu lại toàn bộ dữ liệu kế toán đã nhập. Nếu sau đó xảy ra lỗi làm mất hoặc sai lệch dữ liệu, bản sao lưu có thể được sử dụng để khôi phục dữ liệu về trạng thái tại thời điểm sao lưu, tùy theo cơ chế của hệ thống.

## <mark style="color:$primary;">2. Chức năng Khôi phục / Nạp kho dữ liệu</mark>

\- Chức năng [**Khôi phục / Nạp kho dữ liệu**](khoi-phuc-nap-kho-du-lieu.md) cho phép khôi phục kho dữ liệu từ bản sao lưu hoặc nạp một kho dữ liệu đã có vào hệ thống để tiếp tục sử dụng.

\- Chức năng này thường được sử dụng khi cần phục hồi dữ liệu sau sự cố, chuyển dữ liệu sang máy tính hoặc môi trường làm việc khác, hoặc mở lại kho dữ liệu kế toán đã được lưu trữ trước đó.

**Ví dụ:** Doanh nghiệp cài đặt lại phần mềm kế toán trên máy tính mới. Kế toán sử dụng chức năng Khôi phục / Nạp kho dữ liệu để đưa kho dữ liệu đã sao lưu vào hệ thống, sau đó tiếp tục làm việc với dữ liệu kế toán đã có.

## <mark style="color:$primary;">3. Phân biệt hai chức năng</mark>

| **Tiêu chí**          | [**Sao lưu kho dữ liệu**](sao-luu-kho-du-lieu.md)            | [**Khôi phục / Nạp kho dữ liệu**](khoi-phuc-nap-kho-du-lieu.md)      |
| --------------------- | ------------------------------------------------------------ | -------------------------------------------------------------------- |
| **Mục đích**          | Tạo bản sao để bảo vệ dữ liệu                                | Đưa dữ liệu đã lưu vào hệ thống để sử dụng lại                       |
| **Hướng xử lý**       | Từ kho dữ liệu đang sử dụng tạo bản sao lưu                  | Từ bản sao lưu hoặc kho dữ liệu có sẵn nạp vào hệ thống              |
| **Thời điểm sử dụng** | Định kỳ, trước khi nâng cấp hoặc thay đổi dữ liệu quan trọng | Khi mất dữ liệu, chuyển máy tính hoặc cần sử dụng kho dữ liệu đã lưu |
| **Kết quả**           | Có bản sao lưu để dự phòng                                   | Kho dữ liệu được khôi phục hoặc nạp vào hệ thống                     |

## <mark style="color:$primary;">4. Ý nghĩa đối với hệ thống kế toán</mark>

\- Hai chức năng này hỗ trợ doanh nghiệp quản lý và bảo vệ dữ liệu kế toán trong suốt quá trình sử dụng phần mềm. Sao lưu giúp giảm rủi ro mất dữ liệu, còn khôi phục/nạp dữ liệu giúp duy trì tính liên tục của công việc kế toán khi xảy ra sự cố hoặc thay đổi môi trường làm việc.

{% hint style="danger" %}
<mark style="color:$danger;">**Lưu ý**</mark><mark style="color:$danger;">: Trước khi khôi phục hoặc nạp kho dữ liệu, người dùng nên kiểm tra đúng bản dữ liệu cần sử dụng. Nếu thao tác khôi phục ghi đè lên kho dữ liệu hiện tại, dữ liệu phát sinh sau thời điểm sao lưu có thể bị mất. Vì vậy, nên sao lưu kho dữ liệu hiện tại trước khi thực hiện thao tác này</mark>
{% endhint %}
