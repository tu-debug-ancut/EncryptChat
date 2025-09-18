# LTM-1604-D14--G-i-tin-nh-n-Broadcast-qua-UDP
<h2 align="center">
    <a href="https://dainam.edu.vn/vi/khoa-cong-nghe-thong-tin">
        🎓 Faculty of Information Technology (DaiNam University)
    </a>
</h2>

<h2 align="center">
    Ứng dụng Nhắn Tin
</h2>

<div align="center">
    <p align="center">
        <img src="docs/aiotlab_logo.png" alt="AIoTLab Logo" width="170"/>
        <img src="docs/fitdnu_logo.png" alt="FIT Logo" width="180"/>
        <img src="docs/dnu_logo.png" alt="DaiNam University Logo" width="200"/>
    </p>

[![AIoTLab](https://img.shields.io/badge/AIoTLab-green?style=for-the-badge)](https://www.facebook.com/DNUAIoTLab)
[![Faculty of Information Technology](https://img.shields.io/badge/Faculty%20of%20Information%20Technology-blue?style=for-the-badge)](https://dainam.edu.vn/vi/khoa-cong-nghe-thong-tin)
[![DaiNam University](https://img.shields.io/badge/DaiNam%20University-orange?style=for-the-badge)](https://dainam.edu.vn)

</div>

## 1. Giới thiệu hệ thống

**Ứng dụng Nhắn Tin** được xây dựng theo mô hình **Client–Server**, cho phép nhiều người dùng trò chuyện trực tuyến với nhau thông qua giao diện web.  

👉 **Điểm nổi bật**:
- Gửi và nhận tin nhắn theo thời gian thực.  
- Hỗ trợ tạo và tham gia nhiều phòng chat.  
- Hiển thị danh sách người dùng đang online.  
- Giao diện thân thiện, dễ sử dụng, trực quan.  

---

## 🔧 2. Công nghệ & Ngôn ngữ sử dụng

[![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)](https://nodejs.org/)  
[![Express](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)](https://expressjs.com/)  
[![Socket.io](https://img.shields.io/badge/Socket.IO-010101?style=for-the-badge&logo=socket.io&logoColor=white)](https://socket.io/)  
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/docs/Web/HTML)  
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/docs/Web/CSS)  
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/docs/Web/JavaScript)  

**Chi tiết công nghệ:**
- **Node.js + Express**: Xây dựng backend server.  
- **Socket.IO**: Giao tiếp thời gian thực giữa client và server.  
- **HTML/CSS/JavaScript**: Xây dựng giao diện web.  

---

## 🚀 3. Một số hình ảnh

### Cấu trúc chương trình
![Cấu trúc chương trình](demo/1.png)

### Luồng xử lý
![Luồng xử lý](demo/2.png)

### Giao diện ứng dụng
![Giao diện](demo/3.png)

---

## 📝 4. Các bước cài đặt

### Yêu cầu hệ thống:
- Node.js 16+  
- Trình duyệt web (Chrome, Edge, Firefox, …)  

### Cài đặt và chạy:
```bash
# Cài đặt các thư viện cần thiết
npm install

# Chạy server
npm start
```

Sau đó mở trình duyệt và truy cập:  
```
http://localhost:3000
```

---

## 👨‍💻 5. Tác giả
**Hoàng Anh Tú**

---

## 📄 6. License
Dự án phục vụ mục đích **học tập và nghiên cứu**.  
Bạn có thể tự do sử dụng và chỉnh sửa.
