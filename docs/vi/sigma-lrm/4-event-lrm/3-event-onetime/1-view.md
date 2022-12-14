---
title: Xem giao diện
order: 1
---
# Bảng chú thích

Giải thích về 1 số từ ngữ dùng trong tài liệu, tránh trường hợp nhầm lẫn, hiểu nhầm ý

| Tên   | Giải thích |
| ---- | --------- |
| Thời gian sự kiện  |    Sử dụng để chỉ về thời gian của event đã được tạo ra, đầy đủ thông tin và hiển thị lên Timeline        |
| Thời gian lập lịch   |      Sử dụng để chỉ event chưa được tạo ra khi tạo mới, tại trường chọn thời gian( Ngày/ giờ)  |
|Kiểu sự kiện  | Sử dụng để chỉ 3 loại của kênh: Live/ SCTE 35/ VOD       |
|Kiểu xuất bản|Sử dụng để chỉ 2 loại: OneTime/ Schedule|
|Current Time| Thời gian hiện tại |
|Start Date| Ngày bắt đầu, định dạng năm/ tháng/ ngày, trường hợp đầu vào sử dụng từ tiếng Anh để phù hợp với công thức|
|Start Time| Thời gian bắt đầu, định dạng 24 tiếng giờ:phút:giây |
|Stop Date| Ngày kết thúc, định dạng năm/ tháng/ ngày|
|Stop Date| Thời gian kết thúc, định dạng 24 tiếng giờ:phút:giây |

## Xem giao diện biên tập sự kiện một khoảng
Màn hình mặc định ở giao diện Danh sách kênh

Hệ thống hiển thị dòng **"Chi tiết"** khi **di chuyển chuột** vào icon **chi tiết**.

Người dùng CMS click vào **icon Chi tiết** tại cột hành động 


Hệ thống hiển thị giao diện sự kiện với Tiêu đề **tên kênh vừa chọn**

![](../../images/Ui_Event_channel.png)

Thông tin kênh: Các thông tin của kênh sẽ được hiển thị ở phần này và hiển thị mặc định.

* Các thông tin chi biết gồm 2 Tab: **Tab Sự kiện** và **Tab Lập lịch sự kiện**.
   * Tab sự kiện:  Gồm **Dòng thời gian sự kiện** chạy từ 00:00:00 đến 23:59:59 hiển thị tất cả các chương trình, loại sự kiện trong ngày và **Danh sách sự kiện** tương ứng trong ngày bên dưới (bao gồm cả 2 loại sự kiện).
   
   * Tab Lập lịch sự kiện: Gồm danh sách Lập lịch sự kiện.

 ***Tab Sự kiện***

 Đây là khu vực **hiển thị tất cả các event**(bao gồm sự kiện một lần và lập lịch) trong 1 ngày( bắt đầu từ 00:00:00 đến 23:59:59)

###  Dòng thời gian sự kiện 
Dòng thời gian sự kiện bao gồm các thông tin theo thứ tự từ trên xuống như sau:
* **Trạng thái**: Mỗi sự kiện sau khi được tạo sẽ có các trạng thái chuẩn bị/ sẵn sàng/ hoàn thành/ lỗi ( trừ trường hợp VOD luôn ở trạng thái sẵn sàng) được quy định dựa theo mốc thời gian sự kiện so với thời gian thực.
* **Nút thêm sự kiện**.
* **Chọn ngày**: bộ lọc tìm kiếm theo ngày hỗ trợ người dùng tìm kiếm và có cái nhìn khái quát hơn.
* **Icon đồng bộ**: luôn làm mới hệ thống trong 10s.
* **Thanh trượt** chạy từ 00:00 đến 24:00 của 1 ngày và cách đều nhau 6 tiếng giúp khái quát thời gian trên dòng dự kiện, người dùng có thể thực hiện các thao tác trượt đoạn thời gian.
* Nội dung chính:
    * **Program**: Các chương trình gốc với thời lượng chạy xuyên suốt trong ngày, có các mốc chỉ nhằm đánh dấu thời gian.
    * **Loại sự kiện**: SCTE35/Live/VOD
    * **Dấu gạch đứng** biểu thị cho **trục thời gian thực**.
    * **Thanh cuộn ngang**
    * Có 2 loại sự kiện là **Sự kiện một khoảng** ( không có icon đống hồ đính kèm phía trên và **sự kiện lập lịch**( có **icon đống hồ** đính kèm phía trên) gồm:
       * Tên sự kiện
       * Phạm vi thời gian: Hiển thị giờ:phút:giây ngày-tháng-năm
       * Nội dung đa phương tiện( chỉ hiển thị ở trạng thái sẵn sàng)

    *Lưu ý:* Khi di chuyển chuột vào sự kiện, chuột chuyển thành hình bàn tay với thông tin chi tiết
* **Di chuyển đến hiện tại**: **Chỉ sử dụng với ngày hiện tại**, click vào icon, dòng thời gian sẽ di chuyển tới mốc thời gian hiện tại( current Time)
* **Phóng to** mức độ từ 50% đến 200% đối với khoảng cách đều thời gian để xem các sự kiện chi tiết hơn.

### Danh sách sự kiện

Đây là danh sách sự kiện hiển thị tất cả sự kiện có trong ngày bao gồm **sự kiện một khoảng** và **sự kiện lập lịch** tương ứng với ngày trong Dòng thời gian sự kiện, 
* Thời gian hiển thị bên góc phải tương ứng với thời gian lựa chọn bộ lọc ở dòng thời gian sự kiện
* **ID**: Do hệ thống sinh ra sau khi tạo mới sự kiện
* **Tên sự kiện**: tên đã được đặt trước đó
* **Loại sự kiện**: người dùng đã chọn trước đó
* **Kiểu xuất bản**: hiển thị cả 2 kiểu xuất bản và lập lịch trong ngày
* **Phạm vi thời gian**: Hiển thị tới giờ: phút:giây ngày-tháng-năm
* **Loại trừ**: kênh bị loại trừ sẽ không được hiển thị nội dung thay thế.
* **Nội dung đa phương tiện**: chỉ cấu hình với loại sự kiện VOD/ Live
* **Mô tả**: mô tả ngắn gọn về kênh, không hiển thị tới người xem.
* Hành động sửa, xoá (**sửa chỉ hiển thị đối với loại sự kiện một khoảng, disable với sự kiện lập lịch**).