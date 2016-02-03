# generate:doc:gitbook
Câu lệnh **generate:doc:gitbook** Tạo documentations cho các lệnh

**Usage:**
```
$ drupal generate:doc:gitbook [arguments] [options] 
$ gdg  
```

## Các tùy chọn có sẵn
Tùy chọn | Các chi tiết
-------|-------------
--path | Đường dẫn để render documentation
--learning | Sinh ra chi tiết mã thực thi
--help | Hiển thị thông báo giúp đỡ
--quiet | Đừng đưa ra bất cứ thông báo nào
--verbose | Tăng độ dài của các thông báo: 1 cho đầu ra thông thường, 2 cho những đầu ra dài hơn và 3 cho tìm kiếm lỗi
--version | Hiển thị phiên bản ứng dụng
--ansi | hiệu lực ANSI đầu ra
--no-ansi | Tắt ANSI đầu ra
--no-interaction | Đừng yêu cầu bất kỳ câu hỏi tương tác nào
--env | Tên môi trường
--root | Định nghĩa Drupal root dùng để thực thi lệnh
--no-debug | Tắt chế độ debug
--generate-chain | In các lựa chọn thi hành và các đối số dạng yaml, để sử dụng trong chuỗi lệnh
--generate-inline | In các lựa chọn thi hành và các đối số dạng inline, để sử dụng sau
--generate-doc | Shows command options and arguments as markdown
--target | Site name you want to interact with (for local or remote sites)
--uri | Đường dẫn site Drupal được dùng (cho môi trường multisite hoặc khi chạy trên một cổng thay thế)
--yes | Skip confirmation and proceed

## Các đối số có sẵn
Đối số | Các chi tiết
---------|-------------
command | Câu lệnh để thực thi
