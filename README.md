# Hệ Thống Quản Lý Spa

Hệ thống quản lý spa được xây dựng bằng HTML, Tailwind CSS và JavaScript, với giao diện người dùng hiện đại và dễ sử dụng.

## Tính năng chính

- **Quản lý khách hàng**: Thêm, sửa, xóa và theo dõi thông tin khách hàng
- **Đặt lịch hẹn**: Quản lý lịch hẹn với khách hàng
- **Quản lý dịch vụ**: Danh sách các dịch vụ spa và gói combo
- **Quản lý nhân viên**: Thông tin và lịch làm việc của nhân viên
- **Báo cáo thống kê**: Theo dõi doanh thu và hoạt động kinh doanh

## Cài đặt

1. Đảm bảo máy tính đã cài đặt Python 3.x
2. Clone repository này về máy
3. Chạy server bằng lệnh:
```bash
python3 server.py
```
4. Mở trình duyệt và truy cập: http://localhost:8000

## Tài khoản mặc định

- Tên đăng nhập: admin
- Mật khẩu: admin

## Cấu trúc thư mục

```
spa-management/
├── index.html          # Trang đăng nhập
├── server.py          # Server Python đơn giản
├── pages/             # Các trang chức năng
│   ├── dashboard.html  # Trang tổng quan
│   ├── customers.html  # Quản lý khách hàng
│   ├── services.html   # Quản lý dịch vụ
│   ├── appointments.html # Đặt lịch
│   ├── staff.html     # Quản lý nhân viên
│   └── reports.html   # Báo cáo thống kê
└── README.md          # Tài liệu hướng dẫn
```

## Công nghệ sử dụng

- HTML5
- Tailwind CSS (thông qua CDN)
- JavaScript (Vanilla JS)
- Font Awesome Icons
- Google Fonts
- Chart.js (cho biểu đồ thống kê)

## Hướng dẫn sử dụng

1. **Đăng nhập**
   - Sử dụng tài khoản mặc định để đăng nhập
   - Sau khi đăng nhập thành công, hệ thống sẽ chuyển đến trang Dashboard

2. **Quản lý khách hàng**
   - Thêm khách hàng mới
   - Xem danh sách và thông tin chi tiết khách hàng
   - Cập nhật thông tin khách hàng
   - Xóa khách hàng

3. **Đặt lịch hẹn**
   - Xem lịch hẹn theo ngày/tuần/tháng
   - Thêm lịch hẹn mới
   - Cập nhật hoặc hủy lịch hẹn

4. **Quản lý dịch vụ**
   - Thêm dịch vụ mới
   - Cập nhật thông tin và giá dịch vụ
   - Quản lý các gói combo

5. **Quản lý nhân viên**
   - Thêm nhân viên mới
   - Phân công lịch làm việc
   - Theo dõi hiệu suất

6. **Báo cáo thống kê**
   - Xem báo cáo doanh thu
   - Thống kê khách hàng
   - Đánh giá hiệu suất nhân viên
   - Phân tích xu hướng dịch vụ

## Phát triển trong tương lai

- [ ] Thêm tính năng gửi email/SMS nhắc lịch hẹn
- [ ] Tích hợp thanh toán trực tuyến
- [ ] Thêm tính năng đặt lịch online cho khách hàng
- [ ] Phát triển ứng dụng mobile
- [ ] Tích hợp hệ thống khuyến mãi và tích điểm

## Đóng góp

Mọi đóng góp để cải thiện hệ thống đều được hoan nghênh. Vui lòng tạo issue hoặc pull request để đóng góp.

## Giấy phép

[MIT License](LICENSE)
