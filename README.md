# Tên Dự Án (ví dụ: Website Quản lý...)

Đây là repo cho dự án [Tên].

## 🚀 Hướng dẫn Cài đặt

1.  **Clone repo:**
    ```bash
    git clone [https://store.steampowered.com/app/3241660/REPO/?l=vietnamese&snr=1_4_4__tab-TopGrossing](https://store.steampowered.com/app/3241660/REPO/?l=vietnamese&snr=1_4_4__tab-TopGrossing)
    cd [Tên thư mục dự án]
    ```

2.  **Cài đặt thư viện:**
    ```bash
    npm install
    ```

3.  **Thiết lập Biến Môi trường:**
    * Tạo một file tên là `.env` ở thư mục gốc.
    * Copy toàn bộ nội dung từ file `.env.example`.
    * Liên hệ [Tên bạn] để nhận API keys và điền vào file `.env`.

4.  **Chạy dự án:**
    ```bash
    npm start
    ```

## 📁 Cấu trúc Thư mục

* `/src/components`: Các component UI tái sử dụng.
* `/src/pages`: Các trang hoàn chỉnh.
* `/src/context`: React Context (AuthContext...).
* `/src/services`: Logic gọi Firebase (firestoreService...).