
# 📱 Xây dựng ứng dụng di động quản lý kho hàng tại xưởng sơn xe máy Cần Thơ

📌 **Đồ án môn Hệ thống thông tin 3**  
📍 Trường Đại học Kỹ thuật – Công nghệ Cần Thơ (CTUT)  

👨‍💻 **Sinh viên thực hiện:**  
- Huỳnh Như Ý – HTTT2211015  

👨‍🏫 **Giảng viên hướng dẫn:**  
- TS. Nguyễn Trung Việt  

---

## 🎯 Mục tiêu của hệ thống

- Hỗ trợ xưởng sơn quản lý các đơn hàng từ cửa hàng.
- Theo dõi quy trình tiếp nhận, kiểm tra, sơn và giao hàng.
- Ghi chú nội bộ, phản hồi rõ ràng với khách hàng.
- Tăng tính minh bạch và hiệu quả cho quy trình làm việc.

---

## 🔄 Quy trình tiếp nhận và kiểm tra đơn hàng tại xưởng

1. **Cửa hàng gửi dàn áo đến xưởng**
   - Cửa hàng nhắn **tên và số lượng** hàng qua Zalo cho xưởng.
   - Gửi hàng thông qua **đơn vị vận chuyển**.

2. **Xưởng tiếp nhận hàng**
   - Nhân viên **nhận hàng** từ đơn vị vận chuyển.
   - Hàng được **khui tại khu vực có camera** giám sát để đảm bảo minh bạch.

3. **Nhập thông tin và kiểm hàng**
   - Nhân viên kiểm tra **số lượng thực tế**.
   - Nếu có phát sinh lỗi (**thiếu/dư**), nhân viên sẽ **ghi chú ngay trên ứng dụng**.

4. **Phản hồi với cửa hàng**
   - Quản lý hoặc nhân viên **nhắn tin báo đã kiểm hàng** cho cửa hàng.
   - Cửa hàng có thể **xem lại thông tin đơn hàng trên ứng dụng**.

5. **Hoàn thành sơn và đóng gói**
   - Kiểm tra số lượng hàng sau sơn.
   - Đóng gói và **niêm phong bằng mã vạch**.
   - Giao lại cho **đơn vị vận chuyển**.

6. **Cửa hàng nhận hàng**
   - Cửa hàng **kiểm tra số lượng** so với ban đầu.
   - Nếu có **thiếu/vỡ**, liên hệ đơn vị vận chuyển.
   - Nếu lỗi do xưởng đóng gói, xưởng **chịu trách nhiệm xử lý**.

---

## 👥 Người dùng & Chức năng

### 🔐 Tất cả người dùng:
- Đăng nhập / Đăng xuất  
- Quên mật khẩu  
- Đổi mật khẩu  
- Chỉnh sửa thông tin cá nhân  

---

### 👨‍🔧 Chủ xưởng:
- Thêm / sửa / xóa đơn tồn  
- Duyệt và cập nhật trạng thái đơn tồn:
  - Chưa sơn  
  - Đang sơn  
  - Đã sơn xong  
- Lọc / tìm kiếm hàng theo tên  
- Xem danh sách, chi tiết đơn tồn  
- Xuất file tổng đơn hàng  
- Xem thống kê số lượng đơn tồn  
- Cập nhật trạng thái giao hàng:
  - Đã nhận – Đang giao – Đã giao  
- Ghi chú nội bộ (chỉ chủ và nhân viên thấy)  
- Gửi thông báo cho cửa hàng  

---

### 👷 Nhân viên:
- Thêm và cập nhật đơn tồn  
- Cập nhật trạng thái đơn (gửi lên cho chủ xưởng duyệt)  
- Lọc / tìm kiếm hàng theo tên  
- Xem danh sách, chi tiết đơn  
- Ghi chú nội bộ  

---

### 🏪 Cửa hàng (khách hàng):
- Xem trạng thái đơn đã gửi  
- Lọc / tìm kiếm theo tên hàng  
- Nhận thông báo khi đơn hoàn tất  
- Xem chi tiết đơn  
- Xem danh sách đơn đã gửi đến xưởng  

---

## 🛠️ Công nghệ sử dụng

| Thành phần         | Công nghệ sử dụng           |
|--------------------|-----------------------------|
| Ứng dụng chính     | Flutter (Dart)              |
| Backend / API      | Firebase / Laravel / Node   |
| Cơ sở dữ liệu       | Firebase Firestore / MySQL  |
| Authentication     | Firebase Auth               |
| Thiết kế giao diện | Material Design             |

---

## 💡 Điểm nổi bật

- 🔐 Hệ thống phân quyền rõ ràng  
- 📲 Gửi thông báo realtime đến cửa hàng  
- 📁 Hỗ trợ xuất file Excel đơn hàng
- 📊 Thống kê đơn hàng theo trạng thái và số lượng  

---

## 📬 Liên hệ

- 👩‍💻 **Sinh viên:** Huỳnh Như Ý – HTTT2211015  
- 📞 0982 147 252  
- 📧 huynhnhuy.tech@gmail.com
- 🔗 GitHub: [https://github.com/NhuYtech](https://github.com/NhuYtech)  

---

💻 *Source code đang được phát triển tại:*  
🔗 [https://github.com/NhuYtech/MotorbikePaintManager](https://github.com/NhuYtech/MotorbikePaintManager)
