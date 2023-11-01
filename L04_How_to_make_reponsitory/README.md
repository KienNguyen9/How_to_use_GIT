# Lesson 4 - How to create a reponsitory
## The key-words.
- Repository: (Kho lưu trữ)
- commit: (Một đơn vị làm việc)
- branch: (Nhánh)
- main/master: (tên của repo chính - main repo)
- merge/rebase: kết hợp 2 nhánh với nhau
- develop: tên 1 nhánh hoặc 1 lập trình viên
## Some statements (một số câu lệnh hay gặp)

```shell
git --help # show the help - hiển thị trợ giúp
git --version #version of git in your computer
git status # the status of the repo - hiển thị trạng thái kho lưu trữ
git log # history of repo - hiển thị lịch sử các commit 
```
## The statements to create new reponsitory
```shell
git init repo-mane #create a new repo
git clone repo-name clone-name # clone a repo to your PC
git config -l #show config
git config -f [--scope] [option_name] [value]
# Scope : --system -> all client
#         --global -> liên quan đến repo(s)
#         --local  -> liên quan đến 1 repo
```
## Exercise 1
1. Chọn 1 thư mục
2. mở git bash here
3. gõ lệnh: git init EX1 (Tạo repo EX1 - Là 1 floder - branch master/main)
4. gõ lệnh : cd EX1 (có folder .git chứa các thông tin)
5. xem thông tinh trong folder ẩn .git
```shell
git init EX1 # create repo(folder) EX1 (master/main branch)
cd EX1
```
