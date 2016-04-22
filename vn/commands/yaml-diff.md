# yaml:diff
So sánh hai files YAML để xác định sự khác nhau giữa chúng

**Usage:**
```
$ drupal yaml:diff [arguments] [options]
$ yd  
```

## Các tùy chọn có sẵn
Tùy chọn | Các chi tiết
-------|-------------
--stats | In các đặc tính về sự so sánh các files YAML
--negate | Xác định chế độ so sánh bằng nhau và khác nhau, các giá trị có thể TRUE/FALSE hoặc 0/1
--limit | Giới hạn các kết quả đến một số cụ thể
--offset | Điểm bắt đầu của một giới hạn

## Các đối số có sẵn
Đối số | Các chi tiết
---------|-------------
yaml-left | File YAML được sử dụng để dựa vào đó so sánh
yaml-right | File YAML được sử dụng để xác định các phần thiếu sót hoặc các sự khác nhau với file gốc YAML
