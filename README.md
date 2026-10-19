# Phần 1: Lỗi khiến Exel"dở chứng"
- Gộp ô ở tiêu đề 
- Có dòng trống ở giữa
- Thừa khoảng trắng 
# Phần 2:các bước sửa trong 1 phút
- Bỏ gộp ô:Bôi đen hàng tiêu đề -> bấm nút Merge&Center để bỏ gộp ô.
- Xóa dòng trống:Click chuột vào hàng trống rồi chọn delete
 - Dùng hàm TRIM xóa dấu cách thừa
 - Cú pháp: =TRIM(ô_cần_làm_sạch)
 - Cách làm:Tạo 1 cột mới bên cạnh.Gõ =TRIM(B2) rồi kéo xuống hết bảng để làm sạch chữ "Hỏng".Copy cột mới .Dán giá trị (Paste Values - 123) đè lại cột cũ .Xóa cột mới đi.
