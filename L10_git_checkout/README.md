# Câu lệnh git checkout - chuyển đổi giữa các commit trong git

Cú pháp: 
```shell
git checkout <commit hash>
# commit hash: là một mã của commit
# Thay đổi vị trí của HEAD, để quay về code cũ làm việc 
```
Từ đó có thể quay về bất cứ commit nào để làm việc
VD: Tạo ra 1 repo 
```shell
git init VD_1
cd VD_1
echo "Hello" > hello.txt
# Tạo 1 thư mục 
mkdir Folder_1
cd Folder_1
echo "Folder 1" > Folder_1.txt
cd .. 
# add và commit
git add .
git commit -m "Tao file hello và thu muc folder_1"
# Không cần git push

# dùng git log để xem các commit
git log 

# Tạo ra 1 file khác
echo "noi dung" > a.txt
git add .
git commit -m "tao file a"

# dùng lệnh git log để kiểm tra
git log
# Muốn qua lại đoạn code được commit đầu tiên
# dùng lệnh git checkout chỉ cần gõ vài kĩ tự đầu tiên và TAB
git checkout <XXXXXX> # Gõ khoảng 5 -7 kí tự và enter

# dùng git log để xem - đã quay lại code cũ
```
# TRẠNG THÁI: "detached HEAD state" là gì ? 
vì có thể đi đến các commit để làm việc
nhưng từ đó sẽ sinh tra trạng thái "detached HEAD state" vì HEAD có thể sẽ ko ở branch chính nữa. Nhưng điều này là hợp lệ, các xử lí:

- tắt thông báo đó
- merge các nhánh
