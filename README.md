Lab 03 - Khám phá dự án StarBlaster (SHMUP 2D)
Thông tin sinh viên
Họ tên: Nguyễn Văn Quốc

MSSV: 2312729

Lớp: CTK47B

Mô tả
Bài thực hành Lab 03 môn Game 2D Development with Unity.
Khám phá và tùy chỉnh dự án game StarBlaster - Thể loại bắn tàu không gian (Shoot 'em up) mã nguồn mở.

Các thay đổi đã thực hiện
Thay đổi vùng va chạm (Radius):
Điều chỉnh bán kính va chạm (Radius) từ 0.3 → 0.5 trên các đối tượng Circle Collider 2D (Projectiles).
Kết quả: Vùng nhận diện va chạm lớn hơn, giúp đạn dễ trúng mục tiêu, tăng cảm giác thỏa mãn cho người chơi.

Nâng cấp hệ thống bắn (Shooter System):
Chỉnh sửa thông số Base Fire Rate để tăng tốc độ ra đạn.
Thêm các Prefab đạn mới vào hệ thống bắn của tàu người chơi, tạo ra dải đạn dày đặc hơn.

Thêm máy bay địch (Enemy Waves):
Can thiệp vào EnemySpawner và cấu hình lại WaveConfigSO.
Bổ sung thêm các máy bay địch vào Scene để tăng mật độ chiến đấu và độ khó cho màn chơi.


<img width="1918" height="1113" alt="Screenshot 2026-03-27 213350" src="https://github.com/user-attachments/assets/d23bdccc-ed45-445e-8ba3-3b54f737902d" />
<img width="1919" height="1126" alt="Screenshot 2026-03-27 212011" src="https://github.com/user-attachments/assets/cd0a4373-63db-438d-ac2a-69a7dfc214ca" />

Kiến thức đã học được
Cân bằng Game (Game Balancing): Hiểu cách tinh chỉnh Radius để tạo ra sự cân bằng giữa độ khó và trải nghiệm người dùng (UX).

Cơ chế SHMUP 2D: Phân biệt cách xử lý di chuyển 8 hướng và giới hạn biên màn hình (Clamping) so với game Platformer truyền thống.

Quản lý tài nguyên bằng Scriptable Objects: Học cách sử dụng file .asset để cấu hình dữ liệu kẻ địch thay vì code cứng vào script.

Kỹ năng xử lý Git nâng cao: Thành thạo việc xử lý lỗi remote origin, quản lý nhánh và quy trình đẩy mã nguồn lên GitHub an toàn.

Tư duy hướng đối tượng (OOP): Phân tích cách tách biệt các Component (Health, Shooter, Pathfinder) để hệ thống dễ bảo trì và nâng cấp.
