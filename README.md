**ỨNG DỤNG KẾT NỐI HAI ỨNG DỤNG FLASK QUA MẠNG LAN ĐỂ QUẢN LÝ SINH VIÊN**

Đây là một mô hình ứng dụng web bao gồm 2 ứng dụng Flask độc lập chạy trên 2 máy tính khác nhau trong cùng mạng LAN. Ứng dụng mô phỏng giao tiếp giữa các hệ thống qua API HTTP, cụ thể:

- App1: Chạy ở máy A, đóng vai trò trò chơi là API máy chủ, quản lý cơ sở dữ liệu sinh viên (lưu trữ, cung cấp API).
- App2: Chạy ở máy B, gọi API từ App1 để tra cứu thông tin sinh viên theo mã sinh viên.

**Công nghệ sử dụng**

- API phụ trợ: Python Flask
- Người dùng giao diện : HTML + Bootstrap
- Cơ sở dữ liệu : SQL Server (kết nối với pyodbc)
- Giao tiếp : RESTful API (Flask → Flask)
- Giao tiếp liên máy : HTTP qua IP + Port
  
**Giao diện minh họa**

**Nhập thông tin sinh viên**
<img width="1380" height="735" alt="image" src="https://github.com/user-attachments/assets/33b8fc21-ad15-49d6-977e-8dea2a8280da" />

**Tra cứu sinh viên**
<img width="1393" height="557" alt="image" src="https://github.com/user-attachments/assets/3171f51c-d760-400b-ae7f-ccc60222207f" />
