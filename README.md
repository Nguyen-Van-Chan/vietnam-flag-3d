# Lá Cờ Việt Nam 3D - Kỷ Niệm 50 Năm Giải Phóng Miền Nam

Dự án này tạo ra một hiệu ứng 3D của lá cờ Việt Nam với animation vẽ từng nét, chuyển màu, và hiệu ứng sóng, được xây dựng bằng **Three.js**. Dự án nhằm kỷ niệm 50 năm Ngày Giải phóng Miền Nam, Thống nhất Đất nước (30/4/1975 - 30/4/2025).

## Tính năng
- Vẽ từng nét viền chữ nhật và ngôi sao của lá cờ Việt Nam.
- Hiệu ứng chuyển màu từ viền trắng sang nền đỏ và ngôi sao vàng.
- Hiệu ứng sóng động cho lá cờ khi hoàn thiện.
- Văn bản 3D hiển thị thông điệp kỷ niệm.
- Tối ưu hóa hiệu suất với LOD (Level of Detail).

## Công nghệ sử dụng
- **Three.js** (r128): Thư viện JavaScript để tạo hiệu ứng 3D.
- **HTML5 Canvas**: Để vẽ texture lá cờ động.
- **JavaScript**: Xử lý logic animation và tương tác.

## Cài đặt và chạy dự án

### Yêu cầu
- Trình duyệt web hiện đại (Chrome, Firefox, Edge, v.v.).
- Không cần cài đặt thêm thư viện vì Three.js được tải từ CDN.

### Hướng dẫn
1. **Tải dự án**:
   ```bash
   git clone https://github.com/Nguyen-Van-Chan/vietnam-flag-3d.git
   ```
2. **Mở file `index.html`**:
   - Di chuyển vào thư mục dự án:
     ```bash
     cd <your-repo-name>
     ```
   - Mở file `index.html` trực tiếp trong trình duyệt hoặc sử dụng một web server đơn giản (khuyến nghị):
     ```bash
     npx http-server
     ```
   - Truy cập `http://localhost:8080` để xem kết quả.

## Cấu trúc thư mục
```
vietnam-flag-3d/
├── index.html      # File HTML chính chứa code Three.js
└── README.md       # File hướng dẫn này
```

## Gợi ý tùy chỉnh
- **Thay đổi nền**: Cập nhật màu nền trong CSS (`body { background: #000000; }`) hoặc thêm hình nền bằng cách chỉnh sửa phần code bị comment trong `index.html`.
- **Điều chỉnh tốc độ animation**: Thay đổi giá trị `animationTime += 0.02` trong hàm `animate` để tăng/giảm tốc độ.
- **Thêm font khác**: Thay URL font trong phần tải `FontLoader` để sử dụng font 3D khác.

## Đóng góp
1. Fork dự án này.
2. Tạo nhánh mới:
   ```bash
   git checkout -b feature/<tên-tính-năng>
   ```
3. Commit thay đổi:
   ```bash
   git commit -m "Mô tả thay đổi"
   ```
4. Push lên nhánh:
   ```bash
   git push origin feature/<tên-tính-năng>
   ```
5. Tạo Pull Request trên GitHub.

## Liên hệ
Nếu bạn có câu hỏi hoặc góp ý, vui lòng mở một issue trên GitHub hoặc liên hệ qua Email: [support@techspherex.com]  

## Giấy phép
Dự án này được cấp phép theo [MIT License](LICENSE).

**Tác giả**:

Email: [support@techspherex.com]  
GitHub: [https://github.com/Nguyen-Van-Chan](https://github.com/Nguyen-Van-Chan)
**Ngày tạo**: Tháng 4, 2025