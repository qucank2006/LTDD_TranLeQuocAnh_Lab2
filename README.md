# Business Card

Ứng dụng Android **Business Card** được xây dựng bằng **Kotlin + Jetpack Compose**.

## Giới thiệu

Dự án hiển thị một thẻ danh thiếp đơn giản gồm:
- Tên và chức danh
- Ảnh/logo đại diện
- Thông tin liên hệ: số điện thoại, mạng xã hội, email

## Yêu cầu hệ thống

Trước khi tải và chạy dự án, bạn cần:
- **Android Studio** bản mới
- **JDK** đi kèm Android Studio hoặc JDK tương thích
- Kết nối Internet để tải Gradle và các thư viện lần đầu
- Android Emulator hoặc thiết bị thật để chạy ứng dụng

## Cách tải dự án

Bạn có thể tải dự án theo một trong các cách sau:

### Cách 1: Clone từ GitHub bằng Git

Mở Terminal / PowerShell và chạy:

```powershell
git clone <link-repository-cua-ban>
```

Sau đó vào thư mục dự án:

```powershell
cd BusinessCard
```

### Cách 2: Tải file ZIP

Nếu dự án được đăng trên GitHub/GitLab/Bitbucket:
1. Vào trang repository
2. Chọn **Code** hoặc **Download ZIP**
3. Giải nén file ZIP ra máy tính
4. Mở thư mục dự án đã giải nén bằng Android Studio

## Cách mở dự án trong Android Studio

1. Mở **Android Studio**
2. Chọn **Open**
3. Trỏ tới thư mục gốc của dự án `BusinessCard`
4. Chờ Android Studio sync Gradle xong
5. Nếu được hỏi, chọn **Trust Project** hoặc **Sync Now**

## Cách chạy ứng dụng

1. Kết nối điện thoại Android hoặc mở **Android Emulator**
2. Chọn thiết bị ở thanh công cụ Android Studio
3. Nhấn **Run** hoặc phím tắt `Shift + F10`
4. Đợi ứng dụng build và cài đặt lên thiết bị

## Cấu trúc dự án

```text
BusinessCard/
├─ app/
│  ├─ src/main/java/com/example/businesscard/
│  │  ├─ MainActivity.kt
│  │  └─ ui/theme/
│  └─ src/main/AndroidManifest.xml
├─ build.gradle.kts
├─ settings.gradle.kts
└─ README.md
```

## Thông tin kỹ thuật

- **Ngôn ngữ:** Kotlin
- **UI:** Jetpack Compose
- **minSdk:** 24
- **targetSdk:** 36
- **compileSdk:** 36

## Chỉnh sửa nội dung thẻ danh thiếp

Bạn có thể thay đổi thông tin hiển thị trong file:

```text
app/src/main/java/com/example/businesscard/MainActivity.kt
```

Các phần thường cần sửa:
- Tên
- Chức danh
- Số điện thoại
- Email
- Mạng xã hội
- Logo / ảnh đại diện

## Lưu ý

- Lần đầu build có thể mất thời gian vì Gradle phải tải dependencies.
- Nếu gặp lỗi sync, hãy kiểm tra lại phiên bản Android Studio và kết nối mạng.
- File `local.properties` thường chứa đường dẫn SDK trên máy của bạn và không nên chia sẻ lên repository công khai.


