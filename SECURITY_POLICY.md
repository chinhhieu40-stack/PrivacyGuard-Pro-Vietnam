## ⚖️ THỎA THUẬN SỬ DỤNG CÓ ĐẠO ĐỨC & CHỐNG MÃ ĐỘC (ETHICAL USE POLICY)

Mặc dù dự án PrivacyGuard Pro được cấp phép theo giấy phép MIT License (cho phép tự do sử dụng, chỉnh sửa), Tác giả (**Nguyễn Quang Minh / N14QM**) đặt ra các điều kiện ràng buộc đạo đức và kỹ thuật bắt buộc đối với mọi cá nhân/tổ chức khi tiếp cận mã nguồn này.

Việc tải xuống, clone, fork hoặc sử dụng bất kỳ phần nào của mã nguồn đồng nghĩa với việc người dùng đã đọc, hiểu và cam kết tuân thủ tuyệt đối các quy tắc sau:

### 1. CẤM TUYỆT ĐỐI BIẾN ĐỔI THÀNH MÃ ĐỘC (MALWARE TRANSFORMATION BAN)
Người dùng KHÔNG ĐƯỢC PHÉP thực hiện bất kỳ hành vi nào nhằm mục đích:
*   Chèn, nhúng hoặc tích hợp các payload độc hại (virus, worm, trojan, ransomware, spyware, keylogger, cryptominer...) vào mã nguồn gốc.
*   Sửa đổi logic cốt lõi của ứng dụng để vô hiệu hóa cơ chế phòng vệ hệ thống, đánh cắp dữ liệu người dùng hoặc chiếm quyền điều khiển từ xa (RCE).
*   Tạo ra các phiên bản fork/biến thể có chứa后门 (backdoor) hoặc lỗ hổng cố ý thiết kế sẵn.

### 2. CẤM PHÁT TÁN DƯỚI DANH NGHĨA CỦA TÁC GIẢ (IMPERSONATION BAN)
Nếu người dùng tiến hành chỉnh sửa mã nguồn (dù vì mục đích gì):
*   **BẮT BUỘC** phải gỡ bỏ hoàn toàn tên thương hiệu "PrivacyGuard Pro", logo ASCII Art, và thông tin tác giả "Nguyễn Quang Minh (N14QM)" khỏi giao diện người dùng (UI), tiêu đề cửa sổ, và metadata file (.exe/.py).
*   Phiên bản chỉnh sửa phải được đổi tên rõ ràng (ví dụ: `[Tên_Của_Bạn]_Modified_Fork`) để tránh nhầm lẫn với bản gốc chính chủ.
*   Nghiêm cấm phát tán file binary (.exe) đã qua chỉnh sửa lên các nền tảng công cộng (GitHub Releases, VirusTotal, Website...) dưới đường link hoặc hồ sơ cá nhân của Tác giả gốc.

### 3. TRÁCH NHIỆM PHÁP LÝ & HẬU QUẢ (LEGAL LIABILITY)
Tác giả cam kết mã nguồn gốc tại thời điểm commit là sạch sẽ và minh bạch. Tuy nhiên:
*   Tác giả **KHÔNG CHỊU TRÁCH NHIỆM** cho bất kỳ hậu quả pháp lý, thiệt hại tài sản, hay xâm phạm quyền riêng tư nào xảy ra do hành vi lạm dụng, chỉnh sửa trái phép của bên thứ ba.
*   Mọi hành vi vi phạm Mục 1 và Mục 2 sẽ bị coi là sự vi phạm nghiêm trọng niềm tin cộng đồng Open Source. Tác giả có quyền:
    1.  Công khai danh tính kẻ vi phạm (nếu xác định được qua IP/Account GitHub/Twitter/Facebook).
    2.  Báo cáo trực tiếp tới các tổ chức an ninh mạng (CERT.VN, Interpol Cybercrime Division nếu liên quan xuyên quốc gia) kèm theo bằng chứng forensic (hashes, timestamps, diffs).
    3.  Khởi kiện dân sự đòi bồi thường thiệt hại về danh tiếng theo Luật Sở hữu Trí tuệ Việt Nam và Luật Bản quyền Quốc tế (DMCA).

### 4. CƠ CHẾ GIÁM SÁT CỘNG ĐỒNG (COMMUNITY WATCHDOG)
Mã nguồn này mở cho tất cả mọi người cùng audit. Bất kỳ ai phát hiện hành vi suspicious (đáng ngờ) trong các fork/pr đều có quyền report issue ngay lập tức. Cộng đồng là tuyến phòng thủ cuối cùng chống lại mã độc trá hình.

> *"Code is Law, but Ethics is Higher."*  
> Hãy viết code để bảo vệ, đừng dùng nó để hủy diệt.