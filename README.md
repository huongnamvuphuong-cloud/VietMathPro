# VietMathPro

VietMathPro giúp soạn và sửa công thức toán trong Microsoft Word.

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
