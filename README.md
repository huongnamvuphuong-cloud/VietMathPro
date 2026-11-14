# VietMathPro

VietMathPro giúp soạn và sửa công thức toán trong Microsoft Word.

## Chức năng chạy cục bộ

- Trong **VietMathPro → Đề Word → Định dạng văn bản**, chọn **Vùng được chọn** hoặc **Cả tài liệu**. Công cụ dọn markup, đặt chữ Times New Roman 12, chuẩn hóa nhãn Câu/Bài và căn tab phương án A–D theo cách của ThangLong. Dữ liệu công thức nhúng được kiểm tra trước và sau khi định dạng. Có thể hoàn tác bằng Ctrl+Z.
- Chọn **Hình học & Đồ thị** để vẽ hình phẳng, dựng hình theo quan hệ hình học, đồng bộ hai chiều trực tiếp với mã TikZ (tọa độ biểu thức như trung điểm, chân đường cao, giao điểm, đánh dấu góc/cạnh và nhãn độ dài), hoặc vẽ đồ thị hàm số và xuất bảng biến thiên sang Word. Biểu thức hàm số và mọi ô toán học trong bảng biến thiên là công thức MathType có thể mở/sửa.
- Các thao tác tạo mới, sửa, định dạng, hoặc chuyển từ LaTeX/Word Equation của VietMathPro luôn tạo OLE `Equation.DSMT4` với luồng `Equation Native`/MTEF thật. Vì vậy tệp vẫn dùng được trên máy chỉ cài Word và MathType desktop, không cần cài VietMathPro hay giữ metadata của ứng dụng. Lệnh xuất riêng sang LaTeX hoặc Word Equation vẫn cần do người dùng chủ động chọn.

Các chức năng này chạy trên máy, không yêu cầu đăng nhập, tài khoản, dịch vụ AI/OCR hay dịch vụ Idquiz.

## Tải và cài

Mở [Releases](https://github.com/huongnamvuphuong-cloud/VietMathPro/releases/latest), tải `VietMathPro-x.y.z-Setup.exe`, lưu công việc và đóng Word trước khi chạy bộ cài. Bộ cài cài cho tài khoản Windows hiện tại, hỗ trợ Word 32-bit và 64-bit. Nếu máy thiếu WebView2, quá trình cài cần Internet để tải runtime của Microsoft.

Có thể dùng tệp `VietMathPro-x.y.z-Portable.zip` để chạy portable; xem `HUONG-DAN-CAI-DAT.txt` trong Release.

Nếu cài xong mà Word không có tab VietMathPro: đóng Word, mở VietMathPro, chọn **Trợ giúp → Sửa tab VietMathPro trong Word…**, rồi mở lại Word. Bản portable chạy `Install-WordAddin.cmd`. Cách xử lý khi phần mềm diệt virus xóa file hoặc máy chặn add-in nằm trong `HUONG-DAN-SUA-ADDIN.txt` kèm bộ cài.

## Cập nhật

Trong VietMathPro, mở **Trợ giúp → Kiểm tra cập nhật…**. Có thể bật hoặc tắt thông báo tự động tại cửa sổ cập nhật. Từ 1.4.10, sau khi tải xong, chọn **Cài đặt** để chương trình yêu cầu đóng VietMathPro và Word, hoặc **Hủy** để cập nhật sau. Nếu Word hỏi lưu tài liệu, hãy xử lý hộp thoại; nếu ứng dụng vẫn mở, hãy lưu và đóng thủ công. Bộ cài chỉ chạy khi các ứng dụng đã đóng và SHA-256 hợp lệ.

## Yêu cầu

- Windows 10 hoặc mới hơn.
- Microsoft Word desktop để dùng add-in Word.
- .NET Framework 4.6.2 trở lên.

## Bản quyền

VietMathPro hiện được phân phối ở dạng bộ cài. Các thư viện bên thứ ba có bản quyền riêng; danh sách nằm trong tệp `THIRD-PARTY.md` của gói.
