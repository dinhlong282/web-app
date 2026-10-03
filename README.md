# Bloody Roar 2: The New Breed - 3D Web Edition (Đấu Trường Thú 2)

Dự án tái hiện lại siêu phẩm đối kháng 3D huyền thoại trên hệ máy PS1 (**Đấu Trường Thú 2**) với nền tảng WebGL / Three.js, hệ thống hóa thú chân thực, tuyệt kỹ nộ khí điện ảnh Beast Drive, âm thanh sống động và đồ họa võ đài lồng sắt kịch tính.

---

## 🌟 Các Tính Năng Nổi Bật

1. **Cơ Chế Hóa Thú Chân Thực (Beast Transformation)**:
   - **Tích nộ (Beast Gauge)** khi tấn công và chịu sát thương.
   - Bấm nút **Beast (L)** để kích hoạt tiếng gầm rung chuyển, nổ sóng xung kích (Shockwave) đẩy lùi đối phương và chuyển dạng tức thì.
   - Ở dạng thú: Mở khóa các đòn cào xé tàn khốc, tăng tốc độ di chuyển, tự động hồi phục sinh lực và mở khóa **Beast Drive**.
   - Nếu thanh thú cạn kiệt trong khi bị đánh gục, cơ thể sẽ phát nổ hiệu ứng vỡ kính (Glass Break) và rơi về dạng người!

2. **Tuyệt Chiêu Cuối Điện Ảnh (Beast Drive)**:
   - Camera zoom cận cảnh, đóng băng thời gian trong khoảnh khắc bùng nổ năng lượng.
   - Thực hiện chuỗi combo hàng chục cú đánh liên hoàn uy lực:
     - **Yugo**: *Spiral Fang* (Xoáy lốc móng vuốt sói).
     - **Shenlong**: *Tiger Renkan Ten-Hit Palm* (Liên hoàn thập chưởng mãnh hổ).
     - **Bakuryu**: *Izuna Mole Drop* (Nhẫn thuật phóng khói, cào xoay mũi khoan và nện đầu đối thủ xuống sàn đấu).

3. **Võ Đài Lồng Sắt Phản Xạ 3D (Reactive Steel Cage Arena)**:
   - Sàn đấu bát giác phong cách ngầm PS1 với logo Bloody Roar 2 rực lửa.
   - Khi võ sĩ bị đánh văng vào hàng rào thép, lồng sắt sẽ rung lắc và tóe tia lửa va chạm cực kỳ đã mắt.

4. **Âm Thanh & Giọng Đọc Trọng Tài PS1**:
   - Web Audio API synthesizer tái tạo âm thanh đấm, đá, chém vuốt, tiếng gầm rú và tiếng kính vỡ.
   - Giọng đọc trọng tài kinh điển: *"ROUND 1"*, *"READY... FIGHT!"*, *"BEAST!"*, *"BEAST DRIVE!"*, *"K.O.!"*, *"YOU WIN!"*.
   - Nhạc nền đối kháng guitar điện & trống dồn dập chuẩn phong cách thập niên 90.

---

## 🎮 Hướng Dẫn Điều Khiển (Controls)

| Hành Động | Người Chơi 1 (1P) | Người Chơi 2 (2P) | Tay Cầm Gamepad |
| :--- | :--- | :--- | :--- |
| **Di chuyển / Nhảy / Ngồi** | `W`, `A`, `S`, `D` | Phím Mũi Tên (`↑`, `↓`, `←`, `→`) | D-Pad / Cần Left Stick |
| **Đấm (Punch)** | `J` | `Numpad 1` / `O` | Nút Vuông (Square / X) |
| **Đá (Kick)** | `K` | `Numpad 2` / `P` | Nút X (Cross / A) |
| **Hóa Thú (Beast)** | `L` | `Numpad 3` / `]` | Nút Tròn (Circle / B) |
| **Đỡ đòn (Guard)** | `U` | `Numpad 4` / `[` | `R1` / `L1` |
| **Né 3D (Sidestep L/R)** | `Q` / `E` | `Numpad 7` / `9` | `L2` / `R2` |
| **Beast Drive (Chiêu Cuối)** | `Space` / `I` | `Numpad 0` / `Enter` | Tam Giác (Triangle / Y) |

---

## 🚀 Cách Chạy Game

### Cách 1: Chạy bằng file `start.bat` (Khuyên dùng)
- Nhấp đúp chuột vào file `start.bat` trong thư mục game. Trình duyệt sẽ tự động mở tại `http://localhost:3000`.

### Cách 2: Dùng lệnh Node.js
```bash
node server.js
```
Sau đó truy cập trình duyệt: `http://localhost:3000`

### Cách 3: Mở trực tiếp
- Mở trực tiếp file `index.html` bằng Google Chrome, Microsoft Edge hoặc Firefox.
