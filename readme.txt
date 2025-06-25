# LAB 3 - Xử lý ảnh số

## Mô tả

Thư mục này chứa các bài thực hành và bài tập về các phép biến đổi hình học cơ bản trong xử lý ảnh số, bao gồm:
- Tịnh tiến (dịch chuyển ảnh)
- Xoay ảnh
- Phóng to, thu nhỏ ảnh
- Biến đổi theo hàm tọa độ (Coordinate Map)
- Cắt ảnh, lưu ảnh
- Hiển thị tọa độ điểm ảnh

Các bài thực hành sử dụng thư viện Python như: `numpy`, `scipy`, `imageio`, `matplotlib`, và (tùy chọn) `opencv-python`.

---

## Cấu trúc thư mục

- **lab3/**: Chứa các file code thực hành Lab 3.
- **btaplab3/**: Chứa các file code bài tập Lab 3.
- **exercise/**: Thư mục chứa các ảnh mẫu để thực hành và làm bài tập.

---

## Hướng dẫn sử dụng

1. **Cài đặt thư viện cần thiết:**
    ```
    pip install numpy scipy imageio matplotlib opencv-python
    ```

2. **Chạy các file code:**
    - Mở file `.py` tương ứng trong thư mục `lab3` hoặc `btaplab3`.
    - Đảm bảo các ảnh mẫu đã được đặt trong thư mục `exercise`.
    - Chạy file bằng lệnh:
      ```
      python ten_file.py
      ```
    - Làm theo hướng dẫn trên màn hình để chọn phép biến đổi và ảnh cần thao tác.

3. **Lưu ý:**
    - Nếu ảnh quá lớn, chương trình sẽ tự động thu nhỏ để xử lý nhanh hơn.
    - Kết quả sẽ được hiển thị bằng cửa sổ đồ họa (`matplotlib`).

