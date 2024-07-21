Ứng dụng Mobile Đọc Thông Tin Thẻ Visa/Master
Giới thiệu
Dự án này xây dựng một ứng dụng di động để đọc các thông tin từ thẻ Visa và Master có gắn chip. Ứng dụng sử dụng công nghệ NFC để quét và trích xuất thông tin từ thẻ một cách nhanh chóng và bảo mật.

Tính năng chính
Đọc thông tin thẻ: Trích xuất các thông tin cần thiết từ thẻ Visa và Master thông qua giao tiếp NFC.
Hiển thị thông tin: Hiển thị các thông tin đã đọc được từ thẻ trên giao diện ứng dụng.
Bảo mật: Đảm bảo rằng thông tin thẻ được xử lý và lưu trữ an toàn.
Công nghệ sử dụng
Ngôn ngữ lập trình: Dart (Flutter)
Giao tiếp NFC: Thư viện nfc_in_flutter
Cơ sở dữ liệu: SQLite cho việc lưu trữ cục bộ
Cấu trúc dự án
/
├── android/               # Thư mục chứa mã nguồn cho Android
├── ios/                   # Thư mục chứa mã nguồn cho iOS
├── lib/                   # Thư mục chứa mã nguồn chính của Flutter
│   ├── main.dart          # File khởi động của ứng dụng
│   ├── screens/           # Thư mục chứa các màn hình của ứng dụng
│   └── widgets/           # Thư mục chứa các widget tái sử dụng
├── test/                  # Thư mục chứa các bài kiểm tra
├── pubspec.yaml           # File cấu hình dự án Flutter
└── README.md              # File tài liệu dự án
