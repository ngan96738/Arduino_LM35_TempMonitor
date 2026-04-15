# Dự án đo nhiệt độ LM35 (Tuần 03)

Đây là bài thực hành môn Mạng Cảm Biến, quản lý phiên bản với Git và GitHub.

## Thành viên nhóm
* **[Nguyễn Hoàng Bảo Ngân]** - [N23DCCI048] (Nhóm trưởng)
* **[Nguyễn Hoàng Bảo Ngân]** - [N23DCCI048] (Thành viên)

## Tính năng dự án
* Đọc nhiệt độ từ 3 kênh cảm biến: A0, A1, A2.
* Tự động lấy trung bình 10 lần đo để giảm nhiễu tín hiệu.
* Gửi dữ liệu qua Serial bằng định dạng **JSON**.

## Cấu trúc thư mục
* `firmware/`: Chứa mã nguồn chạy trên Arduino.
* `docs/`: Chứa tài liệu và báo cáo.