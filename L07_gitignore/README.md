# Lesson 7 gitignore

Chỉ định tệp/thư mục sẽ được git bỏ qua
Tạo ra 1 file .gitignore
ghi tên các loại file 
các file hoặc thư mục ko muốn thêm vào repository


```shell
# Tạo file gitignore
touch .gitignore
# tạo file txt
echo "Hi! My friend" > Hi.txt
# tạo thư mục
mkdir KienNguyen 
echo "KienNguyen" > .gitignore
echo "Hi.txt" >> .gitignore # >> ĐỂ GHI VÀO DÒNG KHÁC
echo "*.log" >> gitignore # tất cả các file .log
```
