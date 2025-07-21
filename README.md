# Flappy-Bird

Đây là một bản sao đơn giản của trò chơi **Flappy Bird** nổi tiếng, được xây dựng bằng **HTML5**, **CSS**, và **JavaScript** sử dụng **Canvas API**.  
Dự án này phù hợp để học tập, tìm hiểu cách tạo một trò chơi đơn giản trên trình duyệt mà không cần framework.

## 🎮 Demo

Bạn có thể chơi trực tiếp tại: https://panbap.github.io/Flappy-Bird/

## 📷 Ảnh minh hoạ

![Flappy Bird Screenshot](screenshot.png)  

## 🚀 Tính năng

- Giao diện đơn giản, dễ sử dụng
- Dùng Canvas để vẽ và xử lý đồ hoạ
- Hiển thị điểm số hiện tại và điểm cao nhất
- Thiết kế đáp ứng với nhiều kích thước màn hình (responsive)

## 🧑‍💻 Công nghệ sử dụng

- HTML5
- CSS3
- JavaScript (Canvas API)

## 📁 Cấu trúc dự án
```text
├── index.html
├── README.md
├── flappy.js (đang sử dụng CDN)
└── /assets (thư mục ảnh/âm thanh nếu bạn tự lưu trữ)
```
less
Copy
Edit

## 📦 Cách chạy dự án trên máy tính

1. Clone repo về máy:
    ```bash
    git clone https://github.com/ten-cua-ban/flappy-bird-clone.git
    cd flappy-bird-clone
    ```

2. Mở file `index.html` bằng trình duyệt:
    - Có thể kéo thả vào trình duyệt, hoặc:
    ```bash
    open index.html
    ```

3. Bắt đầu chơi!

> ⚠️ Lưu ý: Hiện tại dự án sử dụng script từ bên ngoài:
> `https://cdn.jsdelivr.net/gh/Panbap/js/game/flappy.js`  
> Nếu bạn muốn tùy chỉnh logic trò chơi, nên tải file này về và chỉnh sửa trực tiếp.

## 📱 Thiết kế Responsive

Trò chơi tự động thay đổi bố cục cho phù hợp với các kích thước màn hình:

- `> 768px`: Hiển thị kiểu desktop
- `≤ 768px`: Giao diện cho tablet/di động
- `≤ 480px`: Thu nhỏ font và sắp xếp lại điểm số

## 📜 Giấy phép

---

**Chúc bạn chơi vui & học lập trình thật tốt! 🚀**
