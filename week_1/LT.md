# 1. Docker, docker-compose là gì ?

## Docker

Docker là nền tảng phần mềm cho phép bạn dựng, kiểm thử và triển khai ứng dụng một cách nhanh chóng. Docker đóng gói
phần mềm vào các đơn vị tiêu chuẩn hóa được gọi là container có mọi thứ mà phần mềm cần để chạy, trong đó có thư viện,
công cụ hệ thống, mã và thời gian chạy. Bằng cách sử dụng Docker, bạn có thể nhanh chóng triển khai và thay đổi quy mô
ứng dụng vào bất kỳ môi trường nào và biết chắc rằng mã của bạn sẽ chạy được.

## docker-compose

Docker compose là công cụ dùng để định nghĩa và run multi-container cho Docker application. Với compose bạn sử dụng file
YAML để config các services cho application của bạn.

# 2. Linux VS Unix VS BSD hay *nix? macOS thuộc loại nào?

## Unix

Unix là một hệ điều hành được phát triển lần đầu tiên vào thập kỷ 60 và đã được phát triển không ngừng kể từ đó. Đây là
một hệ thống ổn định, đa người dùng, đa tác vụ cho máy chủ, máy tính để bàn và máy tính xách tay.

## Linux

Linux là một hệ điều hành máy tính mã nguồn mở, được phát triển dựa trên kernel Linux. Kernel Linux là phần cốt lõi của
hệ điều hành, điều này quản lý tài nguyên của máy tính như bộ nhớ, bộ xử lý, thiết bị ngoại vi và cung cấp giao diện
giữa phần cứng và phần mềm khác. Hệ điều hành Linux thường đi kèm với các thành phần và công cụ phần mềm mã nguồn mở
khác, tạo thành một hệ thống hoàn chỉnh cho việc sử dụng máy tính. Linux được sử dụng rộng rãi trên nhiều loại thiết bị,
từ máy tính cá nhân đến máy chủ và thiết bị nhúng. Nó là một trong những hệ điều hành phổ biến nhất trên thế giới và
được sử dụng trong nhiều môi trường công nghiệp và doanh nghiệp.

## BSD

BSD (Berkeley Software Distribution) là một họ các hệ điều hành Unix-like được phát triển từ mã nguồn mở, ban đầu bắt
nguồn từ Đại học California, Berkeley. BSD bao gồm nhiều biến thể như FreeBSD, OpenBSD, NetBSD và một số hệ điều hành
khác. Các hệ điều hành BSD chia sẻ nguồn gốc chung từ BSD UNIX phát triển tại Đại học California, Berkeley, từ đó chúng
có nhiều điểm tương đồng về kiến trúc và triết lý với UNIX.

## *nix

*nix là một thuật ngữ tổng quát được sử dụng để chỉ tất cả các hệ điều hành dựa trên Unix, bao gồm Unix, Linux, BSD và
cả macOS. Thuật ngữ này được sử dụng để chỉ một nhóm rộng lớn các hệ điều hành có nguồn gốc từ Unix, mà không cần phải
liệt kê tất cả chúng một cách cụ thể.

*nix đã có sự ảnh hưởng rất lớn đến ngành công nghiệp máy tính và là nền tảng cho nhiều ứng dụng và dịch vụ trên toàn
thế giới.

## macOS

macOS là hệ điều hành được phát triển bởi Apple Inc. để chạy trên các máy tính cá nhân và máy tính xách tay của họ. Được
giới thiệu lần đầu vào năm 2001 dưới tên Mac OS X, macOS hiện là phiên bản tiếp theo của hệ điều hành Mac OS.

macOS thuộc loại hệ điều hành UNIX.

# 3. Alpine vs Ubuntu ?

Alpine Linux và Ubuntu là hai hệ điều hành Linux phổ biến nhưng có những đặc điểm khác nhau, bao gồm:

## 3.1. Kích thước và tài nguyên:

- Alpine Linux được thiết kế để nhỏ gọn và tối ưu, có kích thước cài đặt rất nhỏ (thường chỉ vài chục MB). Điều này làm
  cho Alpine Linux trở thành lựa chọn phổ biến cho việc triển khai trên các môi trường có tài nguyên hạn chế, như
  container.

- Ubuntu có kích thước cài đặt lớn hơn, với nhiều gói phần mềm tích hợp sẵn. Điều này có nghĩa là Ubuntu thường cần
  nhiều tài nguyên hơn để hoạt động hiệu quả hơn Alpine.

## 3.2. Mục tiêu sử dụng:

- Alpine Linux thường được sử dụng trong các môi trường như container, máy chủ, hệ thống nhúng hoặc môi trường đòi hỏi
  hiệu suất và bảo mật cao.

- Ubuntu thường được sử dụng trong các môi trường máy tính cá nhân, máy chủ và đám mây, cũng như trong phát triển phần
  mềm và desktop.

## 3.3. Quản lý gói và cộng đồng:

- Alpine Linux sử dụng hệ thống quản lý gói APK (Alpine Package Keeper), trong khi Ubuntu sử dụng APT (Advanced Package
  Tool). Cả hai hệ thống đều cung cấp một loạt các gói phần mềm và có cộng đồng phát triển lớn.

- Ubuntu có một cộng đồng lớn hơn, với nhiều tài liệu và hỗ trợ sẵn có hơn Alpine Linux.

# 4. VNC

- VNC viết tắt của Virtual Network Computing, là một phương tiện để điều khiển và sử dụng một máy tính từ xa thông qua
mạng Internet hoặc mạng nội bộ. Với VNC, người dùng có thể truy cập và điều khiển máy tính từ xa như thể họ đang ngồi
trước máy tính đó, dù ở bất kỳ đâu có kết nối Internet.

- Cách hoạt động cơ bản của VNC là máy tính máy chủ cung cấp một giao diện người dùng đồ họa (ví dụ: màn hình desktop)
thông qua giao thức mạng. Máy tính điều khiển (còn gọi là máy tính khách hoặc máy tính viewer) sử dụng một ứng dụng VNC
để kết nối đến máy tính máy chủ và hiển thị giao diện người dùng của nó, cũng như gửi các tín hiệu điều khiển như di
chuyển chuột, nhấn các phím, và thao tác khác.

- VNC là một công nghệ phổ biến trong các tình huống như hỗ trợ từ xa, quản trị hệ thống, giảng dạy từ xa, hoặc làm việc
từ xa. Có nhiều phần mềm VNC khác nhau có sẵn, bao gồm RealVNC, TightVNC, UltraVNC, và nhiều hơn nữa, cùng với các dịch
vụ và giải pháp dựa trên VNC cho các mục đích cụ thể.






