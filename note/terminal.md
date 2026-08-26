# Terminal
## 1. Terminal là gì?
**Terminal** = nơi nhập lệnh để điều khiển máy tính bằng câu lệnh.
**PowerShell** = một loại Terminal của Windows.
## 2. Di chuyển thư mục
cd <thu_muc>
```
→ Đi vào thư mục.
cd ..
```
→ Quay lên thư mục cha.
dir```
→ Xem file và thư mục hiện tại
## 3. C++ với g++
**g++** = trình biên dịch (Compiler) C++.
Kiểm tra g++:
g++ --version
``
Biên dịch:
g++ "main.cpp" -o "main.exe"
```
* `-o` = đặt tên file đầu ra.
* `main.cpp` = file mã nguồn.
* `main.exe` = chương trình sau khi biên dịch.
Chạy chương trình:
.\main.exe
```
## 4. Quy trình C++
```text
main.cpp
   ↓
g++ (Compiler)
   ↓
main.exe
   ↓
Chạy chương trình
```
**Source Code** = mã nguồn.
**Compile** = biên dịch mã nguồn thành chương trình có thể chạy.
**`.cpp`** = file mã nguồn C++.
**`.exe`** = file chương trình thực thi trên Windows.
## 5. Đường dẫn
**Path** = đường dẫn đến file/thư mục.
Ví dụ:
```text
D:\Documents\IT-Nguyễn Xuân Anh Minh\C++\day0\main.cpp
```
Nếu Terminal đang ở thư mục gốc:
g++ ".\C++\day0\main.cpp" -o ".\C++\day0\main.exe"
```
## 6. Lỗi cần nhớ
`g++ is not recognized`
→ Windows chưa tìm thấy `g++`, thường liên quan đến **PATH**.
`No such file or directory`
→ Đường dẫn hoặc tên file không đúng, hoặc đang đứng sai thư mục.
### Câu nhớ nhanh
```text
cd     → di chuyển
cd ..  → quay lên
dir    → xem thư mục
g++    → biên dịch C++
.\xxx.exe → chạy chương trình
```
