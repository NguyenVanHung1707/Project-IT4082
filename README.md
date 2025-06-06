


# 🏢 PHẦN MỀM QUẢN LÝ THU PHÍ CHUNG CƯ

## 📌 Giới thiệu
Phần mềm quản lý thu phí chung cư được xây dựng nhằm số hóa và tối ưu quy trình quản lý tài chính tại các khu chung cư hiện đại. Hệ thống giúp Ban quản trị dễ dàng theo dõi, lập danh sách thu phí, quản lý cư dân và báo cáo thống kê minh bạch.

## 🧱 Kiến trúc hệ thống
Dự án sử dụng kiến trúc **Client-Server** rõ ràng, phân tách frontend và backend:

- **Frontend:** ReactJS + Material UI (MUI)  
- **Biểu đồ trực quan:** ECharts, ApexCharts  
- **Backend:** Spring Boot (Java)  
- **Cơ sở dữ liệu:** PostgreSQL  
- **Giao tiếp API:** RESTful API

---

## ⚙️ Tính năng chính

### 🎯 Dành cho Ban quản trị
- Quản lý thông tin cư dân, căn hộ
- Tạo và gửi thông báo thu phí hàng tháng
- Quản lý các khoản phí (dịch vụ, quản lý, tự nguyện)
- Phân quyền người dùng theo vai trò
- Thống kê trực quan bằng biểu đồ (thu chi, nợ phí...)

### 👥 Dành cho cư dân
- Tra cứu thông tin khoản phí cá nhân
- Xem lịch sử thanh toán
- Nhận thông báo từ Ban quản trị

---

## 🚀 Hướng dẫn cài đặt

### 1. Yêu cầu hệ thống
- Node.js >= 16.x  
- Java 17  
- PostgreSQL >= 13  
- Maven >= 3.8  

---

### 2. Khởi chạy backend (Spring Boot)

```bash
cd backend
./mvnw spring-boot:run
````

> Cấu hình database tại `src/main/resources/application.properties`

---

### 3. Khởi chạy frontend (ReactJS)

```bash
cd frontend
npm install
npm start
```

---

## 🔐 Bảo mật & Phân quyền

* Xác thực bằng JWT Token
* Phân quyền người dùng (Admin, Quản lý, Cư dân)
* Mã hóa thông tin nhạy cảm

---

## 🔮 Định hướng phát triển

* 📱 Phát triển ứng dụng di động (Android/iOS)
* 📊 Tích hợp AI/ML cho phân tích dữ liệu nâng cao
* 🛠️ Thêm tính năng quản lý sự cố, bảo trì, dịch vụ tiện ích
* 🔐 Tăng cường bảo mật: mã hóa mạnh, xác thực đa yếu tố

---

## 📷 Giao diện (Demo)

---
![image](https://github.com/user-attachments/assets/a1cf2549-0866-4b43-9aad-bf2f284c5532)
![image](https://github.com/user-attachments/assets/302a41df-331b-4bdf-a1ef-96e7bcb3ac7b)
![image](https://github.com/user-attachments/assets/0007788a-5f57-4151-8990-334e8841f051)
![image](https://github.com/user-attachments/assets/f4df8331-bb58-4887-a163-cb525648d4ab)


---


## 📬 Liên hệ

> 📧 Email: hungnguyen.170704@gmail.com

> 💼 LinkedIn: https://www.facebook.com/NguyenVanHung.1707/

> 🚀 Dự án được phát triển bởi nhóm 20 – Trường Đại học Bách khoa Hà Nội

Nguyễn Văn Hưng	  20225634

Tạ Duy Lâm	      20225729

Trần Doãn Huy  	  20225859

Võ Anh Khôi	      20225870

Nguyễn Quốc Khánh	20225866

