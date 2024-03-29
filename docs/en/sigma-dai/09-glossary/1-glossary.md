---
title: Các khái niệm
order: 1
---

# Các khái niệm liên quan

Dưới đây là tổng quan về các khái niệm được sử dụng trong suốt Hướng dẫn sử dụng SSAI, có liên quan đến chèn quảng cáo:

### Máy chủ quảng cáo (ADS)

Một máy chủ cung cấp thông số kỹ thuật của điểm quảng cáo dựa trên các tiêu chí bao gồm các chiến dịch quảng cáo hiện tại và sở thích của người xem.

### Cấu hình(Configuration)

Một đối tượng trong SSAI mà bạn tương tác. Cấu hình chứa thông tin vị trí về máy chủ gốc và máy chủ quyết định quảng cáo (ADS). Cấu hình cũng chứa các điểm cuối cung cấp điểm truy cập vào và ra khỏi SSAI.

### Chuyển mã động(Dynamic transcoding)

Một quy trình khớp chất lượng và định dạng quảng cáo với nội dung video chính khi nội dung được yêu cầu. Chuyển mã động giúp giảm yêu cầu lưu trữ và đảm bảo rằng quá trình phát lại sẽ chuyển tiếp liền mạch giữa nội dung quảng cáo và video.

### Danh sách chỉ mục (Manifest manipulation)

Quá trình viết lại các tệp chỉ mục từ máy chủ gốc để các tệp kê khai tham chiếu đến các đoạn nội dung và quảng cáo thích hợp. Quảng cáo được xác định bởi phản hồi VAST từ máy chủ quảng cáo (ADS). Khi tiến trình phát lại, SSAI thực hiện chèn quảng cáo hoặc thay thế quảng cáo vào luồng nội dung.

### VAST

Mẫu phân phối quảng cáo video (VAST)  là các phản hồi XML mà máy chủ quyết định quảng cáo gửi đến các yêu cầu quảng cáo từ SSAI. Các câu trả lời cho biết quảng cáo mà SSAI chèn vào tệp kê khai. Để biết thêm thông tin về logic đằng sau việc chèn quảng cáo SSAI, hãy xem Tìm hiểu về hành vi chèn quảng cáo của SSAI. Để biết thêm thông tin về cách SSAI hoạt động với VAST, hãy xem các yêu cầu VAST cho máy chủ quảng cáo.

## Khái niệm cấu hình kênh

Dưới đây là tổng quan về các khái niệm liên quan đến cấu hình kênh.

### Kênh( Channels)

Một kênh tập hợp các chỉ mục nguồn của bạn thành một luồng tuyến tính. Mỗi kênh có một hoặc nhiều đầu ra chứa các URL phát lại mà người chơi truy cập. Đầu ra kênh tương ứng với cài đặt cấu hình gói mà bạn tạo cho các nguồn VOD của mình. Một kênh có lịch biểu xác định thời điểm các nguồn VOD sẽ phát trong luồng của kênh.

### Vị trí nguồn( Source locations)

Vị trí nguồn đại diện cho máy chủ gốc nơi nội dung của bạn được lưu trữ. Nó có thể là máy chủ HTTP, mạng phân phối nội dung hoặc cơ sở hạ tầng đóng gói.

### Nguồn VOD ( VOD sources)

Nguồn VOD đại diện cho một phần nội dung, chẳng hạn như phim hoặc tập của chương trình truyền hình. Bạn liên kết các nguồn VOD với các chương trình để thêm chúng vào luồng tuyến tính của kênh.

### Vmap (Video Multiple Ad Playlist)

VMAP là một định dạng cho phép tổ chức và quản lý nhiều VAST Tags trong một chuỗi quảng cáo.
