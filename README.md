# Minecraft Stone Clicker

Một mini game clicker đơn giản được xây dựng bằng HTML, CSS và JavaScript, lấy cảm hứng từ Minecraft.

## Tính Năng

* Click vào cục đá Minecraft để nhận điểm.
* Hiệu ứng đá rung/vỡ khi click.
* Hiệu ứng +1 bay lên.
* Hệ thống thành tựu kiểu Minecraft.
* Thanh XP và Level.
* Lưu điểm tự động bằng LocalStorage.
* Nhạc nền Minecraft.
* Giao diện nền Minecraft toàn màn hình.
* Tương thích PC và thiết bị di động.

## Cấu Trúc Thư Mục

```text
/
├─ index.html
└─ music/
   └─ sweden.mp3
```

## Cài Đặt

1. Tải file `index.html`.
2. Tạo thư mục `music`.
3. Thêm một bài nhạc Minecraft vào thư mục `music`.
4. Đổi tên file nhạc thành:

```text
sweden.mp3
```

5. Mở `index.html` bằng trình duyệt hoặc upload lên hosting.

## Thành Tựu

| Điểm   | Thành Tựu                   |
| ------ | --------------------------- |
| 10     | Người Đập Đá Tập Sự         |
| 50     | Đá Và Chỉ Có Đá             |
| 100    | Chuyên Gia Đập Đá           |
| 500    | Máy Khoan Công Nghiệp       |
| 1000   | Vua Cục Đá                  |
| 5000   | Đá Không Thể Bị Phá Hủy     |
| 10000  | Tại Sao Bạn Vẫn Đang Click? |
| 50000  | Nỗi Ám Ảnh Cục Đá           |
| 100000 | Trở Thành Một Với Đá        |

## Lưu Dữ Liệu

Điểm số được lưu bằng LocalStorage của trình duyệt.

Dữ liệu sẽ được giữ lại khi:

* Tải lại trang.
* Đóng và mở lại trình duyệt.

Dữ liệu sẽ mất khi:

* Xóa dữ liệu trang web.
* Xóa LocalStorage của trình duyệt.

## Tùy Chỉnh

### Thay Nhạc Nền

Thay file:

```text
music/sweden.mp3
```

bằng bài nhạc Minecraft khác như:

* Sweden
* Wet Hands
* Mice on Venus
* Subwoofer Lullaby

### Thay Hình Cục Đá

Sửa thuộc tính `src` trong:

```html
<img id="stone" src="...">
```

### Thêm Thành Tựu

Tìm đoạn:

```javascript
const achievements = {
};
```

và thêm các mốc điểm mới.

## Công Nghệ Sử Dụng

* HTML5
* CSS3
* JavaScript (Vanilla)

## Giấy Phép

Dự án được tạo cho mục đích học tập và giải trí. Minecraft là thương hiệu thuộc Mojang Studios.
