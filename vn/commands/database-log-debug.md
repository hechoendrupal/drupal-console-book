# database:log:debug
Hiển thị các dấu sự kiện hiện tại cho ứng dụng

**Usage:**
```
$ drupal database:log:debug [arguments] [options]
```

## Các tùy chọn có sẵn
Tùy chọn | Các chi tiết
-------|-------------
--type | Sự kiện được lọc bời một kiểu chỉ định
--severity | Sự kiện được lọc bời một cấp chỉ định của severity
--user-id | Sự kiện được lọc bời một user id cụ thể
--reverse | Đảo ngược trình tự của Sự kiện
--limit | Giới hạn kết quả cho một số cụ thể
--offset | Điểm bắt đầu của một giới hạn

## Các đối số có sẵn
Đối số | Các chi tiết
---------|-------------
event-id | DBlog sự kiện ID
