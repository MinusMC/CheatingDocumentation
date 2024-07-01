# Config

Chuyên mục này nói về config, 1 thành phần quan trọng nhất trong tất cả hack client.

## Config là gì

Config là từ viết tắt của `configuration`, nghĩa là cấu hình. Config là 1 tệp tin chứa các thông số, cấu hình cần thiết để điều chỉnh hoạt động của 1 phần mềm, phần cứng.

Về cơ bản, thay vì bạn phải nhớ trong đầu là nên bật cái nào, cấu hình ra sao, hoặc muốn chia sẻ cấu hình cho người khác thì chỉ cần lưu vào 1 file, khi muốn chỉnh lại về đúng cấu hình ấy thì chỉ cần cài lại cấu hình ấy mà không cần phải nhớ lại nó trông như thế nào.

## Làm thế nào để cài config (load config)

- Bước 1: Đảm bảo bạn đã chọn đúng config, đúng client và đã chạy client ít nhất 1 lần
- Bước 2: Mở thư mục .minecraft (không biết xem tại [đây](cach_mo_thu_muc_.minecraft.md)), sau đó mở thư mục tên client (đa số client đều có thư mục chính nó tại .minecraft)
- Bước 3: Tìm đến thư mục config (settings nếu không thấy config) và mở chúng
- Bước 4: Đưa config bạn vừa tải về vào trong thư mục
- Bước 5: Vào game
- Bước 6: Mở chat, gõ: `<prefix><command> load <name>`. Trong đó:
	+ Prefix có thể là dấu `.`, `!`, ... (đa số là dấu chấm).
	+ Command có thể là `config`, `settings`, `localsettings` (đa số là config)
	+ Name là tên config bạn vừa đưa vào

## Làm thế nào để lưu config (save config)

Chỉ cần vô game, gõ `<prefix> <command> save <name>` (tương tự ở mục cài config). File config sẽ được lưu ở `.minecraft/<tên client>/<configs hoặc settings>`
