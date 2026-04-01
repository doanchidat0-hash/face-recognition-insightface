# Hệ thống nhận diện khuôn mặt và điểm danh tự động

Dự án ứng dụng trí tuệ nhân tạo (AI) và thị giác máy tính để tự động hóa quy trình điểm danh, được xây dựng bằng Python.

## 🚀 Công nghệ sử dụng
* **Ngôn ngữ:** Python
* **Thư viện AI/Computer Vision:** OpenCV, InsightFace
* **Xử lý dữ liệu:** Pandas, OpenPyXL (Xuất file Excel)

## 💡 Tính năng chính
* Nhận diện khuôn mặt với độ chính xác cao thông qua model InsightFace.
* Giao diện người dùng (GUI) đơn giản, dễ thao tác.
* Tự động lưu trữ lịch sử nhận diện và xuất báo cáo điểm danh ra file Excel (`danh_sach_cham_cong.xlsx`).

## 📁 Cấu trúc thư mục (Source code)
* `cuocthiAI.py`: Module chứa logic xử lý nhận diện AI lõi.
* `giao_dien.py`: Mã nguồn xây dựng giao diện ứng dụng.
* `images/`: Thư mục chứa dữ liệu hình ảnh.

*(Lưu ý: Thư mục chứa model AI InsightFace đã được lược bỏ khỏi Repository này do giới hạn dung lượng).*
