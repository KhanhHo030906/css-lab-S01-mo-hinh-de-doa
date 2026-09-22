# Khai sử dụng công cụ hỗ trợ

Mỗi bài nộp có một tệp như tệp này. Ba cột, một dòng cho một lần dùng.

| Dùng công cụ nào | Cho việc gì | Bạn đã kiểm lại ra sao |
|---|---|---|
| Claude AI | Hướng dẫn cài đặt môi trường (Python, Docker, jsonschema, pytest) và xử lý lỗi terminal (Git Bash vs PowerShell) | Tự chạy từng lệnh trên máy, đối chiếu thông báo lỗi thực tế với hướng dẫn, chỉ tiếp tục khi `make preflight` và `pytest` báo đúng như dự kiến |
| Claude AI | Gợi ý cách chia hệ thống ShopLab thành 3 thành phần và vẽ sơ đồ luồng dữ liệu | Tự đối chiếu sơ đồ với luồng nghiệp vụ thực tế của một trang bán hàng (đăng nhập, đặt hàng) trước khi dùng để viết mối đe dọa |
| Claude AI | Soạn nháp 8 mối đe dọa và gán số nguyên lý mẫu (do AI tự đề xuất, không phải nội dung chính thức của môn học) | Đọc lại từng câu, kiểm tra có khớp với hệ thống ShopLab không, và cần tự đối chiếu lại số nguyên lý với tài liệu môn học trước khi nộp chính thức |
| Claude AI | Soạn nháp phần giải thích lý do chọn 3 mối xử lý trong README | Tự kiểm tra lại các con số tác động/khả năng có khớp với bảng mối đe dọa đã điền trong `threat-model.json` không |
| Claude AI | Hướng dẫn các lệnh git (commit, push) để nộp bài | Tự chạy `git status` kiểm tra danh sách file trước khi commit, xác nhận trên GitHub sau khi push |

Không dùng công cụ nào thì viết một dòng "Không dùng". Khai đầy đủ không bị trừ điểm.