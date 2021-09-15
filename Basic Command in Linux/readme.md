# Basic Commands in Linux


- `pwd:` xác định vị trí thư mục hiện tại
- `whoami`: Xác định người dùng hiện tại
- `cd:` Điều hướng tới thư mục khác | __..__ đại diện cho thư mục cha của thử mục hiện tại, __~__ đại diện cho home.
-  `ls [option]`: Liệt kê các file và thư mục trong vị trí hiện tại
- `man, -h,...`: Các ứng dụng, tool đa số đều có hướng dẫn sử dụng, lệnh này để đọc chúng.


### Finding Stuff

- `locate`: Tìm kiếm và hiển thị mọi thứ chứa từ khóa mà bạn muốn tìm trên toàn bộ hệ thống tệp. Nhược điểm là csdl của lệnh này được update một lần mỗi ngày nên những file mới tạo trong ngày có thể không tìm thấy.
- `whereis`: Sử dụng để tìm kiếm các file binary
- `find directory [-Option] Expression` : Một công cụ tìm rất hữu ích. Chỉ định thư mục tìm kiếm cùng các biểu thức để giới hạn phạm vi
Ví dụ tìm file tên __KMA__ trong toàn thư mục hệ thống:

```
find / -type f -name KMA

```

- `grep` : tìm kiếm thông qua từ khóa trong một đầu vào
- `ps`: hiển thị thông tin về các tiến trình(process) đang chạy trên hệ thống.


### MODIFYING FILES AND DIRECTORIES

- `cat`: Hiển thị nội dung file
- `cat > name`: Tạo file
- `touch`: tạo file
- `mkdir`: Tạo thư mục
- `cp`: copy thư mục
- `mv`: di chuyển hoặc rename file
- `rm`: xóa file 
- `rmdir`: xóa thư mục trống, nếu muốn xóa thư mục không trống dùng `rm -r`
- `>` chuyển hướng đầu vào một tệp và ghi đè nó
- `>>`: Thêm vào không ghi đè
- 
- 
