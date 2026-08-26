# Git
## 1. Git là gì?
Git (Version Control - quản lý phiên bản) là hệ thống theo dõi và quản lý thay đổi của dự án.
**Repository (repo)** = kho lưu trữ được Git quản lý.
**GitHub** = nền tảng trực tuyến để lưu trữ và chia sẻ Repository.
## 2. Quy trình cơ bản
```text
Tạo / sửa file
    ↓
git add
    ↓
Staged (vùng chuẩn bị)
    ↓
git commit
    ↓
Commit (phiên bản được ghi nhận)
```
## 3. Các lệnh đã học
```bash
git --version
```
→ Kiểm tra phiên bản Git.
```bash
git init
```
→ Khởi tạo Repository.
```bash
git status
```
→ Xem trạng thái Repository.
```bash
git add <file>
```
→ Đưa file vào Staging Area.
```bash
git commit -m "noi dung"
`
→ Ghi nhận phiên bản.
```bash
git config --global user.name "Ten"
git config --global user.email "Email"
```

→ Cấu hình tên và email cho Git.

## 4. Thuật ngữ cần nhớ

* **Working Directory** = thư mục đang làm việc.
* **Untracked** = chưa được Git theo dõi.
* **Staged** = đã đưa vào vùng chuẩn bị Commit.
* **Commit** = phiên bản đã được ghi nhận.
* **Local** = trên máy tính.
* **Remote** = kho ở nơi khác, ví dụ GitHub.
* **Push** = đẩy thay đổi lên GitHub.
* **Pull** = lấy thay đổi từ GitHub về.
* **Clone** = sao chép Repository về máy.
* **Branch** = nhánh phát triển.
* **Merge** = hợp nhất các nhánh.

## 5. Câu nhớ nhanh

> `init` → bắt đầu quản lý
> `status` → xem trạng thái
> `add` → đưa vào vùng chuẩn bị
> `commit` → ghi nhận phiên bản
> `push` → đẩy lên GitHub
> `pull` → lấy về máy

Học Git và GitHub - Day 0