# BUS - DỰ ÁN ANDROID

Dự án này đóng gói mã nguồn Java/Kotlin gốc vào nền tảng Android WebView:
- **Hoạt động ngoại tuyến (Offline):** Không cần kết nối Internet đối với giao diện và dữ liệu có sẵn.
- **Tích hợp tính năng web:** Bật sẵn JavaScript và DOM Storage để các chức năng tương tác và `localStorage` hoạt động ổn định.
- **Tên ứng dụng:** Ha Noi Bus Office
- **Mã định danh (`applicationId`):** `vn.hanoibus.office`
- **Phiên bản Android tối thiểu:** Android 6.0 (API 23)

---

## CÁCH TẠO FILE APK

1. Cài đặt phần mềm **Android Studio** trên máy tính.
2. Mở Android Studio > chọn **Open**, tìm đến thư mục `HaNoiBusOffice` (thư mục có chứa file `settings.gradle`).
3. Chờ hệ thống Gradle đồng bộ (sync) và cài đặt **Android SDK Platform 35** nếu có thông báo yêu cầu.
4. Trên thanh công cụ, chọn **Build** > **Build Bundle(s) / APK(s)** > **Build APK(s)**.
5. Sau khi biên dịch xong, file APK (bản debug) thường nằm tại đường dẫn:
   `app/build/outputs/apk/debug/app-debug.apk`
6. Chép file APK sang điện thoại Android, mở file và cấp quyền cho phép cài đặt ứng dụng từ nguồn không xác định nếu thiết bị yêu cầu.

---

## LƯU Ý

- Đây là bộ mã nguồn gốc dành cho Android Studio, chưa phải file APK đã đóng gói hoàn chỉnh.
- Môi trường tạo file hiện tại không tích hợp sẵn Android SDK/Gradle nên không thể xuất trực tiếp ra file APK tại đây.
- File giao diện HTML gốc được lưu tại: `app/src/main/assets/index.html`.
- Toàn bộ dữ liệu yêu thích và tùy chỉnh của người dùng được lưu cục bộ trong `localStorage` của WebView trên thiết bị.

---

## BẢN QUYỀN & THÔNG TIN PHÁT HÀNH

- **Bản quyền:** Dự án mã nguồn mở — cho phép tự do sao chép, phân phối và chỉnh sửa, vui lòng ghi rõ thông tin ghi công tác giả gốc khi sử dụng lại.
- **Nhà phát hành:** VMN Studios 95
- **Tác giả:** Vũ Minh Ngọc ©️ 2026
