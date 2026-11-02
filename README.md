Từ điển Anh - Việt Mini
Bài tập lớn môn Kỹ thuật Lập trình C. Gồm chương trình C chạy trên dòng lệnh và một trang web minh họa.

Giới thiệu
Các từ được lưu trong mảng struct luôn sắp xếp theo chữ cái, nên tra từ bằng tìm kiếm nhị phân (Binary Search). Dữ liệu lưu vào tudien.txt nên không mất khi tắt chương trình.

Chức năng
Tra từ Anh → Việt
Tra từ Việt → Anh
Thêm từ mới (tự động lưu)
Thoát
Chạy chương trình
gcc -Wall -Wextra -o tudien_don_gian tudien_don_gian.c
./tudien_don_gian
Lần đầu chạy, chương trình tự tạo tudien.txt. Mỗi dòng có dạng tu_anh|nghia_viet, ví dụ apple|quả táo.

Các lệnh C chính
Lệnh	Mục đích
fgets	Nhập một dòng từ bàn phím an toàn, không tràn bộ đệm
strcspn	Xóa ký tự xuống dòng còn sót sau fgets
atoi	Đổi lựa chọn menu từ chuỗi sang số
tolower	Tra từ không phân biệt hoa/thường
strcmp	So sánh chuỗi, dùng trong Binary Search
strstr	Tìm từ khóa trong nghĩa (tra Việt → Anh)
strtok	Tách mỗi dòng trong tệp thành từ Anh và nghĩa Việt
fopen, fprintf, fclose	Đọc và ghi tệp tudien.txt
Trang web minh họa
Mô phỏng cùng logic với chương trình C và hiển thị số bước Binary Search sau mỗi lần tra.

Liên kết: (dán liên kết vào đây)
