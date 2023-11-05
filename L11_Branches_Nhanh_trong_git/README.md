# Lesson 11 - Branches - Nhánh trong GIT

- Nhánh chính: main/master
- Nhánh con

Có thể merge các nhánh với nhau, ví dụ:

![Alt text](image.png)

Trong project có nhiều người cùng tham gia
- Khi thử nghiệm cần có hướng đi khác 
- Cần quay lại hoặc tiếp tục phát triển 1 nhánh

## CÁC CÂU LỆNH LÀM VIỆC VỚI NHÁNH 

```shell
# tạo nhánh mới
git branch <branch_name>

# Chuyển sang nhánh khác 
git checkout <branch_name>

```
Hình ảnh minh họa:
Nhánh chính có 3 commit 
tạo ra 1 nhánh mới là nhánh featute_1 (tính năng)

![ ](image-1.png)

```shell
git branch branch_featute_1
git checkout branch_featute_1
```
Mỗi DEV trong project làm việc trên 1 nhánh của riêng mình, sau đó sẽ merge hoặc rebare lại với nhau
  


