# Lesson 4 - How to create a reponsitory
## The key word.
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