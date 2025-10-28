# Hệ Thống Quản Lý Giảng Viên

## Tổng quan dự án

Dự án này là hệ thống quản lý giảng viên dành cho trường đại học, được phát triển như một phần của môn học **Nhập Môn Kỹ Thuật Phần Mềm (SOF1021)**.

## Mục tiêu dự án

Xây dựng một hệ thống quản lý thông tin giảng viên toàn diện, hỗ trợ các chức năng:
- Quản lý thông tin cá nhân của giảng viên
- Quản lý lịch giảng dạy
- Quản lý nghiên cứu khoa học
- Quản lý hoạt động chuyên môn
- Báo cáo và thống kê

## Cấu trúc dự án

```
SOF1021_NhapMonKyThuatPhanMem/
├── ASM/                    # Thư mục mã nguồn chính
│   ├── ASM.iml            # File cấu hình IntelliJ IDEA
│   └── src/               # Thư mục mã nguồn Java
│       └── Main.java      # Lớp chính (hiện tại chỉ là Hello World)
├── Document/              # Thư mục tài liệu phân tích và thiết kế
│   ├── ASM-GD1.docx      # Hướng dẫn Assignment 1
│   ├── Hệ thống quản lí 1.2.docx  # Tài liệu hệ thống quản lý
│   ├── Hệ thống quản lý giảng viên cho trường đại học.docx  # Mô tả tổng quan
│   ├── Sơ đồ hệ thống quản lý giảng viên của trường đại học  # Sơ đồ hệ thống
│   ├── Use_Case_Chi_Tiet.docx  # Use case chi tiết
│   └── Y1_Phan_tich_yeu_cau_QL_GiangVien.docx  # Phân tích yêu cầu
├── .git/                  # Thư mục Git
├── .idea/                 # Cấu hình IntelliJ IDEA
└── README.md              # Tài liệu hướng dẫn dự án
```

## Công nghệ sử dụng

- **Ngôn ngữ lập trình**: Java
- **IDE**: IntelliJ IDEA
- **Công cụ quản lý phiên bản**: Git
- **Định dạng tài liệu**: Microsoft Word (.docx)

## Cài đặt và chạy

### Yêu cầu hệ thống

- Java Development Kit (JDK) 8 trở lên
- IntelliJ IDEA (khuyến nghị) hoặc bất kỳ IDE Java nào

### Hướng dẫn cài đặt

1. Clone dự án từ repository:
   ```bash
   git clone <repository-url>
   cd SOF1021_NhapMonKyThuatPhanMem
   ```

2. Mở dự án trong IntelliJ IDEA:
   - File → Open → Chọn thư mục ASM

3. Chạy chương trình:
   - Chạy lớp `Main.java`
   - Hiện tại sẽ hiển thị "Hello World"

## Phân tích và thiết kế

Các tài liệu phân tích yêu cầu nằm trong thư mục `Document/`:

- **Y1_Phan_tich_yeu_cau_QL_GiangVien.docx**: Phân tích chi tiết yêu cầu của hệ thống
- **Use_Case_Chi_Tiet.docx**: Mô tả use case chi tiết
- **Sơ đồ hệ thống quản lý giảng viên của trường đại học**: Sơ đồ tổng quan hệ thống
- **Hệ thống quản lý giảng viên cho trường đại học.docx**: Mô tả tổng quan dự án

## Trạng thái hiện tại

- ✅ Khởi tạo cấu trúc dự án
- ✅ Thiết lập môi trường phát triển Java
- ✅ Hoàn thành phân tích yêu cầu
- 🔄 Đang phát triển các chức năng cơ bản
- ⏳ Chưa hoàn thành giao diện người dùng
- ⏳ Chưa tích hợp cơ sở dữ liệu

## Kế hoạch phát triển

### Phase 1: Cơ sở (Đã hoàn thành)
- Thiết lập môi trường phát triển
- Phân tích yêu cầu hệ thống

### Phase 2: Phát triển cốt lõi
- Thiết kế cơ sở dữ liệu
- Phát triển các lớp Entity
- Implement các chức năng cơ bản

### Phase 3: Giao diện người dùng
- Phát triển giao diện web/desktop
- Tích hợp với cơ sở dữ liệu

### Phase 4: Kiểm thử và triển khai
- Viết unit test
- Kiểm thử tích hợp
- Chuẩn bị tài liệu triển khai

## Đóng góp

Để đóng góp vào dự án:

1. Fork dự án
2. Tạo branch mới cho tính năng: `git checkout -b feature/AmazingFeature`
3. Commit thay đổi: `git commit -m 'Add some AmazingFeature'`
4. Push lên branch: `git push origin feature/AmazingFeature`
5. Tạo Pull Request

## Liên hệ

Thông tin liên hệ nhóm phát triển:
- Môn học: Nhập Môn Kỹ Thuật Phần Mềm (SOF1021)
- Giảng viên hướng dẫn: [Tên giảng viên]
- Sinh viên thực hiện: [Danh sách sinh viên]

## Giấy phép

Dự án này được phát triển cho mục đích học tập trong khuôn khổ môn học SOF1021.

---

*Lưu ý: Dự án đang trong giai đoạn phát triển ban đầu. Các chức năng sẽ được cập nhật và mở rộng theo tiến độ môn học.*
