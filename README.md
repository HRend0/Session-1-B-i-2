# Session-1-B-i-2
[Bài tập] Hệ thống quản lý đơn hàng Thương mại điện tử
Bài 1:
- Thực thể: Khách hàng (KhachHang), Sản phẩm (SanPham), Đơn hàng (DonHang), Nhân viên (NhanVien), Chi tiết đơn hàng (ChiTietDonHang) - Thực thể yếu.
- Primary Key: Mã khách hàng (KhachHang), Mã sản phẩm (SanPham), Mã đơn hàng (DonHang), Mã nhân viên (NhanVien).
Bài 2:
- Xác định mối quan hệ giữa các thực thể:
  + KhachHang - DonHang: 1 Khách hàng có thể đặt nhiều đơn hàng, 1 đơn hàng chỉ có thể thuộc về 1 khách hàng do đó đây là mối quan hệ 1-N.
  + DonHang - SanPham (ChiTietDonHang): 1 đơn hàng có thể có nhiều sản phẩm trong đó, 1 sản phẩm có thể thuộc nhiều đơn hàng do đó đây là mối quan hệ N-N.
  + NhanVien - DonHang: 1 nhân viên có thể xử lý nhiều đơn hàng, 1 đơn hàng cũng có thể được xử lý bởi nhiều nhân viên do đó đây là mối quan hệ N-N.
