# ĐẶC TẢ WEBSITE BLOG BÀI VIẾT CÔNG NGHỆ

## 1. Thông tin dự án

- Tên dự án: Website Blog Bài Viết Công Nghệ
- Sinh viên: Nguyễn Vũ
- Môn học: Lập trình Web
- Công nghệ sử dụng: HTML5, CSS3
- Mục tiêu: Xây dựng website giới thiệu các bài viết công nghệ với giao diện đơn giản, thân thiện và responsive.

---

## 2. Đối tượng người dùng

### Người dùng chính

- Sinh viên tìm kiếm kiến thức công nghệ.
- Người mới học lập trình Web.
- Người yêu thích tin tức công nghệ.

### Nhu cầu

- Xem các bài viết nổi bật.
- Cập nhật các bài viết mới.
- Truy cập dễ dàng trên điện thoại và máy tính.

---

## 3. Cấu trúc website

Website gồm 2 trang:

| Tên trang | Tên file |
|------------|-----------|
| Trang chủ | index.html |
| Bài viết | bai-viet.html |

---

## 4. Mô tả chức năng

### 4.1 Trang chủ (index.html)

#### Header

- Logo website.
- Menu điều hướng:
  - Trang chủ
  - Bài viết

#### Banner giới thiệu

- Tiêu đề website.
- Mô tả ngắn về nội dung website.

#### Mục bài viết nổi bật

Hiển thị 3 bài viết nổi bật:

1. AI thay đổi ngành công nghệ như thế nào?
2. Xu hướng phát triển Web năm 2026.
3. Kỹ năng lập trình cần có cho sinh viên.

#### Mục bài viết mới

Hiển thị 3 bài viết mới:

1. Học HTML CSS từ đâu?
2. Responsive Design là gì?
3. 5 mẹo tăng tốc website.

#### Footer

- Thông tin bản quyền website.

---

### 4.2 Trang bài viết (bai-viet.html)

Hiển thị toàn bộ 6 bài viết.

#### Nhóm bài viết nổi bật

- AI thay đổi ngành công nghệ như thế nào?
- Xu hướng phát triển Web năm 2026.
- Kỹ năng lập trình cần có cho sinh viên.

#### Nhóm bài viết mới

- Học HTML CSS từ đâu?
- Responsive Design là gì?
- 5 mẹo tăng tốc website.

Mỗi bài viết gồm:

- Hình ảnh minh họa.
- Tiêu đề.
- Mô tả ngắn.
- Nhãn phân loại.

---

## 5. Giao diện

### Màu sắc

- Màu chính: #2563eb
- Màu nền: #f5f7fa
- Màu chữ: #333333

### Phông chữ

- Arial, sans-serif

### Bố cục

- Header
- Nội dung chính
- Footer

Danh sách bài viết sử dụng dạng Card (thẻ).

---

## 6. Responsive

### Desktop

- Hiển thị 3 bài viết trên một hàng.

### Tablet

- Hiển thị 2 bài viết trên một hàng.

### Mobile

- Hiển thị 1 bài viết trên một hàng.
- Menu và nội dung tự động co giãn phù hợp màn hình.

---

## 7. Cấu trúc thư mục

```text
du-an-web-tinh/
│
├── public/                 : Chứa mã nguồn website
│   ├── css/                : Chứa file định dạng CSS
│   │   └── style.css
│   │
│   ├── images/             : Chứa hình ảnh sử dụng trong website
│   │
│   ├── index.html          : Trang chủ
│   └── bai-viet.html       : Trang bài viết
│
├── dacta.md                : Tài liệu đặc tả dự án
├── nhatki.md               : Nhật ký sử dụng AI

```