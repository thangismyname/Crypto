## Tạo repository (repo) 
git init 
=> nhánh chính: master

### git init -b main
=> Tạo repo local vs nhánh chính có tên main

## git remote add origin + <url repo>
=> Liên kết repo local vs repo remote

## Ko đưa thư mực node_modules lên repo remote
=> Node_modueles chiếm dung lượng rất lớn
=> Node_modules có thể cài lại thông qua câu lệnh : npm i
### file .gitignore quy định những thư mục hay file ko đc phép đẩy lên repo remote

### git status 
=> Kiểm tra sự thay đổi của các file trong dự án

### git add 
=> Thêm file vào trong staging
### git add . ==> dùng để thêm tất cả các file ở trong thư mực hiện tại 
### git add -A => dùng để thêm tất cả các file ở trong dự án vào trong staging
### git add <đường dẫn file> => Chỉ thêm file cụ thể vào trong staging

### working directory (file màu đỏ)
### staging (file màu xanh)
=> lúc này file sẵn sàng để đưa lên repo remote

### config git (chỉ chạy duy nhất 1 lần)
### config git
### git config --global user.name ""

### git commit 
=> dùng để gắn message vào trong những file đc phép đưa lên repo remote
=> mỗi commit có một mã sha (id)

### git log
=> Kiểm tra lịch sử commit

### git push -u origin <tên nhánh>
=> đưa code lên repo remote
=> từ lần push code thứ 2 : git push

### git pull
=> pull code ở repo remote về local

git pull --no-ff

### git clone <url repo>
=> Dùng để clone source code của 1 repo bất kỳ