# K58KTP.01
ĐỒ ÁN PHÂN TÍCH THIẾT KẾ HỆ THỐNG MSSV K225480106088 HỌ VÀ TÊN : TẠ PHẠM ĐÌNH HÒA TÊN ĐỀ TÀI : QUẢN LÝ TIỆM CẦM ĐỒ
I. Phân tích hệ thống
## DÀN Ý PHÂN TÍCH VÀ THIẾT KẾ HỆ THỐNG QUẢN LÝ TIỆM CẦM ĐỒ
## I. Giới thiệu hệ thống
Mô tả bài toán

Tiệm cầm đồ cung cấp dịch vụ vay tiền bằng cách thế chấp tài sản.

Hệ thống giúp quản lý thông tin khách hàng, tài sản, hợp đồng, thanh toán, và trạng thái tài sản.

Mục tiêu hệ thống

Tự động hóa quy trình quản lý cầm đồ.
 
Giảm thiểu sai sót trong quản lý thông tin.

Theo dõi thanh toán, nhắc nhở hợp đồng đến hạn.

## II. Phân tích hệ thống
1. Các đối tượng tham gia
Khách hàng: Đăng ký cầm đồ, thanh toán, chuộc tài sản.

Nhân viên: Quản lý hợp đồng, khách hàng, tài sản.

Quản lý: Theo dõi báo cáo doanh thu, tình trạng hoạt động.

2. Chức năng chính của hệ thống
Quản lý khách hàng

Thêm/Sửa/Xóa thông tin khách hàng.

Tìm kiếm khách hàng theo CMND/CCCD, tên, số điện thoại.

Quản lý tài sản cầm cố

Lưu trữ thông tin tài sản (tên, loại, mô tả, giá trị định giá).

Quản lý trạng thái tài sản (Đang cầm, Đã chuộc, Thanh lý).

Quản lý hợp đồng cầm đồ

Tạo hợp đồng mới (thông tin khách hàng, tài sản, số tiền vay, lãi suất).

Theo dõi ngày đáo hạn, trạng thái hợp đồng.

Quản lý thanh toán

Ghi nhận thanh toán lãi, gốc, phí trễ hạn.

Xuất biên lai thanh toán.

Quản lý nhân viên

Thêm/Sửa/Xóa thông tin nhân viên.

Phân quyền truy cập hệ thống.

Báo cáo thống kê

Doanh thu theo tháng, năm.

Danh sách hợp đồng sắp hết hạn.

Tổng hợp số lượng tài sản bị thanh lý.

## III. Thiết kế hệ thống
1. Sơ đồ Use Case
Các tác nhân: Khách hàng, Nhân viên, Quản lý.

Các chức năng chính như đã nêu ở phần II.

2. Sơ đồ ERD (Mô hình dữ liệu quan hệ)
Bảng Khách hàng (Customer)

Bảng Tài sản cầm cố (PawnedAsset)

Bảng Hợp đồng cầm đồ (PawnContract)

Bảng Thanh toán (Payment)

Bảng Nhân viên (Employee)

3. Sơ đồ luồng dữ liệu (DFD)
Level 0: Quản lý khách hàng, tài sản, hợp đồng, thanh toán.

Level 1: Các bước xử lý dữ liệu chi tiết.

4. Thiết kế giao diện
Màn hình đăng nhập

Màn hình quản lý khách hàng

Màn hình quản lý tài sản

Màn hình tạo hợp đồng

Màn hình thanh toán

Màn hình báo cáo thống kê

## IV. Công nghệ sử dụng
Frontend: React.js / Vue.js

Backend: Node.js (Express) hoặc Django

Database: MySQL / PostgreSQL

Triển khai: Docker, AWS/GCP

## V. Kết luận
Hệ thống giúp quản lý hiệu quả khách hàng, hợp đồng, tài sản và thanh toán.

Giảm thiểu rủi ro, tăng hiệu suất vận hành tiệm cầm đồ.

Dễ mở rộng và nâng cấp trong tương lai.
