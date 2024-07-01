# Anti VPN và cách bypass

Anti VPN là 1 trong những công cụ cho phép chặn toàn bộ các IP đến từ các nhà cung cấp dịch vụ VPN như SoftEther VPN, NordVPN, ... Vào 1 ngày đẹp trời, bạn đang cheat các server LuckyVN, BlocksMC tự nhiên bị ban và bạn không thể tạo acc mới do bạn bị IP Ban. Vậy phải làm thế nào? Xem hướng dẫn bên dưới.

## Làm thế nào để kiểm tra địa chỉ IP? (Nếu đã biết, bỏ qua)
Rất đơn giản, lên Google gõ `what is my ip` và Google sẽ trả cho bạn địa chỉ. Hãy ghi lại ra 1 chỗ nào đó trước khi đổi IP!

## Bypass AntiVPN thông thường
Một số server sử dụng AntiVPN: LuckyVN (bị ban bởi staff là bị ban bởi IP), BlocksMC, Hypixel, ...

Hầu hết các server được liệt kê trong này đều có AntiVPN khá yêu nên bạn có thể sử dụng [VpnGate](https://www.vpngate.net/en/download.aspx), NordVPN, ... để bypass dễ dàng

Và một trong những VPN phổ biến nhất hiện nay là VPNGate. Vậy làm thế nào để cài nó? Làm theo các bước dưới đây:
- Bước 1: Tải VPNGate tại https://www.vpngate.net/en/download.aspx và cài đặt.
- Bước 2: Mở phần mềm SoftEther VPNGate, click vào "VPN Gate Public VPN Relay Servers.
- Bước 3: Chọn máy chủ mà bạn muốn fake ip đến và chọn nó, nếu hiện bản chọn method UDP hoặc TCP thì cứ ấn OK.
- Bước 4: Đổi acc và chơi thôi.

  
## Bypass mọi loại AntiVPN

Một số server như [Pika Network](https://pikanetwork.net), [Lucky Network](https://luckynetwork.net) sử dụng [v4Guard](https://v4guard.io/), nên bạn không thể sử dụng cách trên được. Ngoài ra cách này áp dụng với bất kì AntiVPN nào khác. 

Cách bypass đơn giản nhất: Dùng 4G :trollface:, vâng đúng rồi đó. 4G chính là 1 nguồn VPN hoàn toàn hợp lệ mà các AntiVPN không thể chặn được. Chỉ cần phát wifi là bạn có thể sử dụng, nhưng giá của nó khá mắc (Viettel bán các gói data như ST15K 3GB / 3 ngày, ST30K 7GB / 7 ngày).

Cách đơn giản thứ 2: Tắt cục wifi (Modem Router, Modem Wifi) và bật lại. \
Lưu ý: `Không áp dụng với Viettel, VNPT mới đăng kí dưới 12 tháng (do nhà mạng để cục wifi nằm trong 1 proxy, được gọi là CGNAT), nhà mạng FPT có xác suất 50/50.`

Đối với nhà mạng FPT, chúng ta có thể đổi IP mà không cần phải tắt cục wifi:
- Bước 1: Vào trình duyệt web, mở trang [login page của router](192.168.1.1) (192.168.1.1/192.168.1.0/192.168.0.1/... | bình thường  là 192.168.1.1).
- Bước 2: Đăng nhập vào (thông tin đăng nhập bình thường dán ở mặt sau router).
![image](https://github.com/MinusMC/docs-cheating/assets/152876934/29510029-c8ce-4764-a294-50925b3397c0)
- Bước 3: Tìm mục WAN/PPPOE ấn vào Reconnect PPPOE.
![image](https://github.com/MinusMC/docs-cheating/assets/152876934/0e8e60fa-71fd-40e5-b4c2-3b7e351497b6)
![image](https://github.com/MinusMC/docs-cheating/assets/152876934/7c673673-fcd5-4772-8507-9d611d66a601)
- Bước 4: Đợi khoảng từ 2 - 5s cho router kết nối lại đến nhà mạng. Sau đó IP của bạn sẽ được thay đổi

Lưu ý: `Đối với một số router FPT (như AC1000F) thì phải đợi từ 1 - 2 phút sau khi nhận IP mới thành công, nếu không, router sẽ có 1 lỗi là No IP (Không nhận địa chỉ IP).`

Cách 3: Mua proxy. Có rất nhiều nhà cung cấp proxy khác nhau như mproxy.vn, LiquidProxy (liquidproxy.net), ...
Lưu ý: Sử dụng proxy miễn phí trên google không có tác dụng trên các server dùng v4guard.
