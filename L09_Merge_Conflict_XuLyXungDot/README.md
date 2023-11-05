# Merge conflict - Xu ly xung dot

Cách sửa lỗi thủ công
## Dùng các lênh pull - push - fetch để kiểm tra vị trí xung đột
Tìm các sự khác biệt giữa local file và file ở central Repo. Sửa trong IDE.
```shell
git push
# Khi push phát hiện lỗi 
# Dùng lệnh git pull và git fetch
git fetch
git pull 
# Tìm ra file bị xung đột, đọc lỗi 
# Sửa lại sao cho ko có sự khác biệt
# sau đó add, commit và push lên lại 
git add .
git commit -m '...'
git push
```
