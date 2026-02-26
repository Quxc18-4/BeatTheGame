# Beat The Game (2D Platformer RPG)



**Beat The Game** là một dự án nhập vai hành động 2D tập trung vào hệ thống chiến đấu và các trận đấu Boss đầy thử thách. Dự án này minh chứng cho khả năng xây dựng kiến trúc game có thể mở rộng (scalable) và tối ưu hóa hiệu năng.


##### Media \& Demos



* Video Gameplay Demo: [Link Demo Các Chức Năng](https://drive.google.com/drive/folders/1RBnKdXhQenAz_m37AlU0GBF6Ej4qclgg?usp=drive_link)



##### Tính năng Kỹ thuật Nổi bật (Technical Highlights)



1\. Dynamic Boss AI System 



* Cơ chế: Sử dụng Random Pool kết hợp với Finite State Machine (FSM).



* Chi tiết: Boss không tấn công theo chu kỳ lặp lại mà chọn chiêu thức dựa trên xác suất và khoảng cách với người chơi, tạo ra trải nghiệm chiến đấu khó đoán và hấp dẫn.



2\. Data-Driven Architecture 



* Công nghệ: ScriptableObjects.



* Lợi ích: Tách biệt dữ liệu (máu, sát thương, cấu hình quái vật) khỏi logic code. Điều này cho phép thay đổi chỉ số game (balancing) cực nhanh mà không cần build lại mã nguồn.



3\. Hiệu năng \& Tối ưu hóa 



* Object Pooling: Áp dụng cho toàn bộ hệ thống đạn (projectiles), hiệu ứng (VFX) và quái vật nhỏ để giảm thiểu việc khởi tạo/xóa liên tục (Garbage Collection), giúp duy trì FPS ổn định.



* Physics 2D: Tối ưu hóa xử lý va chạm và layer để tránh lãng phí tài nguyên tính toán.



##### Hướng dẫn Cài đặt (Installation \& Setup)



Để chạy dự án này trên máy cục bộ, bạn hãy làm theo các bước sau:



1. Yêu cầu hệ thống: Unity Editor phiên bản 2022.3 LTS hoặc mới hơn.



2\. Clone Repository:



Bash

&nbsp;	git clone https://github.com/Quxc18-4/Beat-The-Game.git



3\. Mở dự án:



* Mở Unity Hub.



* Chọn Add -> trỏ đến thư mục vừa clone.



* Chờ Unity import các package (như Cinemachine, Input System nếu có dùng).



4\. Chạy Game: Mở Scene MainMenu hoặc Level1 trong thư mục Assets/Scenes và nhấn Play.



##### Cấu trúc Thư mục Chính (Project Structure)



* \_Scripts/: Chứa toàn bộ logic C# (AI, Player Controller, Systems).



* ScriptableObjects/: Các file chứa dữ liệu cấu hình game.



* Prefabs/: Các đối tượng đã được đóng gói sẵn để tái sử dụng.



* Animations/: Hệ thống Animator và các clip chuyển động.





##### 📧 Liên hệ



* Họ tên: Danh Minh Quốc 



* Email: danhminhquoc1804@gmail.com 



* GitHub: Quxc18-4
