# ⭐ Git — Highlight Day 0

## 1. Bản chất Git

**Git** = Version Control (quản lý phiên bản).

Git giúp theo dõi thay đổi và lưu lại lịch sử các phiên bản của dự án.

**Repository** = kho được Git quản lý.

`.git` = nơi Git lưu dữ liệu quản lý Repository.

---

## 2. Quy trình quan trọng nhất

```text
Sửa / tạo file
      ↓
git status
      ↓
git add
      ↓
Staging Area
      ↓
git commit
      ↓
Commit (phiên bản)
      ↓
git push
      ↓
GitHub
```

### Nhớ:

* `status` → xem Git đang thấy gì.
* `add` → đưa thay đổi vào vùng chuẩn bị.
* `commit` → tạo phiên bản chính thức.
* `push` → đưa Commit lên GitHub.

---

## 3. Local và Remote

```text
Local Repository
      │
      │ git push
      ↓
Remote Repository
(GitHub)
```

* **Local** = Repository trên máy.
* **Remote** = Repository ở nơi khác.
* `origin` = tên mặc định của Remote.
* `master` = Branch hiện tại.
* `origin/master` = Branch `master` trên Remote.

---

## 4. Commit

Mỗi Commit có:

* **Commit ID** → mã định danh phiên bản.
* **Author** → người tạo Commit.
* **Date** → thời gian tạo.
* **Message** → mô tả thay đổi.

Ví dụ:

```text
a299930 Add gitignore
```

---

## 5. Kiểm tra lịch sử

```bash
git log --oneline
```

→ Xem lịch sử Commit ngắn gọn.

```bash
git log
```

→ Xem thông tin Commit chi tiết.

**HEAD** = vị trí hiện tại Git đang đứng.

---

## 6. `.gitignore`

`.gitignore` = danh sách file Git bỏ qua.

Ví dụ:

```text
*.exe
```

→ Git bỏ qua tất cả file `.exe`.

```text
main.cpp   → theo dõi ✅
main.exe   → bỏ qua ❌
```

---

## ⭐ 7. Công thức phải nhớ

```text
git init
→ tạo Repository

git status
→ kiểm tra

git add
→ chuẩn bị

git commit
→ tạo phiên bản

git push
→ đưa lên GitHub

git log
→ xem lịch sử
```

> **Git không tự tạo phiên bản khi mình sửa file.
> Phiên bản được tạo khi mình Commit.**
