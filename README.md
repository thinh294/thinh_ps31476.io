Bài 1:
- Tạo database SQLite chứa thông tin Quản lý cửa hàng xe máy gồm:
XEMAY(Mã xe, Tên xe, Giá bán, Hãng xe, Trạng Thái)
Trong đó:
+ Mã xe có kiểu dữ liệu là TEXT và là khóa chính trong bảng XEMAY
+ Tên xe, Hãng xe có kiểu dữ liệu là TEXT
+ Giá bán có kiểu dữ liệu là INTEGER
+ Trạng thái có kiểu dữ liệu là INTEGER với 2 giá trị 0 và 1.
1 – còn kinh doanh
0 – ngừng kinh doanh
- Nhập 5 dòng dữ liệu mẫu cho table xe máy
Bài 2:
Tạo class XeMayDAO thực hiện một số thao tác:
- Lấy danh sách xe máy mà cửa hàng còn kinh doanh (trạng thái = 1)
- Thêm thông tin xe máy mới (mặc định trạng thái = 1)
- Cập nhật thông tin xe máy hiện tại
- Xóa thông tin xe máy (cập nhật trạng thái từ 1 thành 0)
