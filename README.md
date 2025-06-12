# demo-gitflow

# GIT là gì ?

- Git là hệ thống quản lý phiên bản phân tán

- Theo dõi lịch sử thay đổi của dự án ( mã code, ...)

- Quản lý nhiều nhánh phát triển song song

- Cho phép nhiều người cùng làm việc trên một dự án mà không bị xung đột (conflict)

# Các khái niệm cơ bản trong GIT

## Repository

- Kho chứa mã nguồn, có thể là local hoặc remote (sever)

## Commit

- Ghi lại trạng thái của một mã nguồn ( sự kiện ) tại một thời điểm nhất

## Branch

- Nhánh phát triển riêng biệt 

## Merge

- Gộp nội dung của một branch vào nhánh khác

## Clone

- Tải repo từ server về máy

## Pull 

- Lấy code mới nhất từ nhánh trên server về local

## Push

- Đẩy code commit từ local lên server

# Một số câu lệnh GIT cơ bản

- git init: Khai báo một sự án bắt đầu sử dụng git

- git status : Kiểm tra trạng thái thay đổi  của các file trong dự án

- git add file_name: Xác nhận (thêm ) file thay đổi vào repo của local ( sẵn sàng cho commit)

- git add . : Xác nhận(thêm) tất cả các file thay đổi vào repo local ( sẵn sàng cho commit)

- git commit -m "Your comment" : Đẩy các file thay đổi vào store local sẵn sàng cho push code lên server và đồng thời thêm comment

- git push origin your_branch: Đẩy code từ local vào nhánh your_branch trên server

- git checkout -b branch_name : Tạo một nhánh mới có tên là branch_name đồng thời di chuyển sang nhánh đó

Khở tạo repository => clone code về máy local => Thêm file mới và thay đổi file cũ => commit code => push code lên nhánh mới