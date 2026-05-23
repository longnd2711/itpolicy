# itpolicy
Dựa trên nội dung file HTML trình bày Đề xuất Chính sách CNTT (với 3 trụ cột chính, các rủi ro đã nêu như BYOD, Onboarding/Offboarding, Nghị định 13, bản quyền phần mềm...), đây là **Dàn ý chi tiết cho Văn bản Chính sách Quản trị CNTT** để bạn đính kèm trình Tổng Giám đốc ký duyệt.

---

# DÀN Ý: CHÍNH SÁCH QUẢN TRỊ CÔNG NGHỆ THÔNG TIN
**Mã tài liệu:** IT-POL-001 | **Phiên bản:** 1.0 | **Bộ phận:** IT

## PHẦN I: QUY ĐỊNH CHUNG
1. **Mục đích:** 
   * Xây dựng khung quản trị an toàn thông tin, bảo vệ tài sản dữ liệu của Công ty.
   * Định hướng hành vi sử dụng công nghệ an toàn, tuân thủ pháp luật.
2. **Phạm vi & Đối tượng áp dụng:** 
   * Toàn bộ Cán bộ nhân viên (CBNV), thực tập sinh, đối tác làm việc tại mạng lưới của Công ty.
3. **Căn cứ & Tài liệu tham khảo:**
   * Nội quy lao động của Công ty.
   * *Nghị định 13/2023/NĐ-CP* về bảo vệ dữ liệu cá nhân.
4. **Giải thích từ ngữ:** (Định nghĩa ngắn gọn về IT Policy, BYOD, Cloud, MDM, VPN, Ransomware...).

## PHẦN II: TIÊU CHUẨN & QUẢN LÝ THIẾT BỊ (Trụ cột 1)
1. **Quy định về Cấp phát và Thu hồi thiết bị (Onboarding / Offboarding):**
   * Tiêu chuẩn thiết bị theo từng vị trí/cấp bậc.
   * Quy trình IT setup tài khoản khi có nhân sự mới.
   * Quy trình khóa tài khoản, thu hồi và wipe (xóa) dữ liệu ngay khi nhân sự nghỉ việc.
2. **Quy định sử dụng Thiết bị do Công ty cấp phát:**
   * Trách nhiệm bảo quản vật lý (chống mất cắp, hư hỏng).
   * Nghiêm cấm sử dụng thiết bị Công ty cho mục đích cá nhân vi phạm pháp luật, cá cược, xem nội dung độc hại.
3. **Quy định về Cài đặt Phần mềm & Bản quyền:**
   * **100% thiết bị** phải được quản lý qua hệ thống tập trung (MDM) của IT.
   * Nhân viên không có quyền Admin, không tự ý cài đặt phần mềm.
   * Nghiêm cấm sử dụng phần mềm bẻ khóa (crack/pirated) để tránh rủi ro mã độc và vi phạm bản quyền.
4. **Chính sách BYOD (Bring Your Own Device - Sử dụng thiết bị cá nhân):**
   * Điều kiện để thiết bị cá nhân được phép truy cập mạng/dữ liệu công ty.
   * Yêu cầu cài đặt phần mềm giám sát công việc (nếu có) trên thiết bị cá nhân.

## PHẦN III: BẢO MẬT THÔNG TIN & DỮ LIỆU (Trụ cột 2)
1. **Quản lý Tài khoản & Định danh:**
   * Tiêu chuẩn mật khẩu mạnh (độ dài, ký tự đặc biệt, chu kỳ thay đổi mật khẩu 90 ngày/lần).
   * Không chia sẻ mật khẩu cho người khác dưới mọi hình thức.
   * Bắt buộc áp dụng Xác thực 2 yếu tố (MFA/2FA) cho các hệ thống quan trọng.
2. **Phân quyền truy cập (Nguyên tắc Đặc quyền tối thiểu):**
   * Nhân sự chỉ được cấp quyền truy cập vào dữ liệu/phần mềm phục vụ trực tiếp cho công việc của mình.
   * Phê duyệt của Quản lý cấp cao khi cần cấp quyền truy cập đặc biệt.
3. **Bảo vệ Dữ liệu Cá nhân & Tuân thủ Pháp lý:**
   * Các quy định về thu thập, xử lý và lưu trữ thông tin khách hàng, nhân sự đúng theo *Nghị định 13/2023/NĐ-CP*.
   * Nghiêm cấm tự ý sao chép, gửi dữ liệu nhạy cảm của công ty qua email cá nhân hoặc nền tảng chat bên ngoài.
4. **Kiểm soát thiết bị lưu trữ ngoài:**
   * Khóa cổng USB truyền dữ liệu (chỉ mở cho các cá nhân được phê duyệt).
   * Bắt buộc mã hóa (BitLocker/FileVault) trên các ổ cứng của thiết bị công ty.

## PHẦN IV: SỬ DỤNG MẠNG & LƯU TRỮ ĐÁM MÂY (Trụ cột 3)
1. **Kết nối Mạng nội bộ (LAN/Wi-Fi):**
   * Phân tách rạch ròi giữa Mạng Công ty (dành cho thiết bị đã xác thực) và Mạng Khách (Guest - chỉ có Internet, không truy cập dữ liệu nội bộ).
2. **Làm việc từ xa & VPN:**
   * Quy định bắt buộc dùng VPN công ty khi truy cập hệ thống nội bộ từ mạng công cộng (quán cafe, sân bay...).
   * Cấm sử dụng các mạng Wi-Fi công cộng không có mật khẩu để gửi dữ liệu công ty.
3. **Lưu trữ & Chia sẻ trên Đám mây (Cloud):**
   * Chỉ sử dụng nền tảng Cloud được Công ty cấp phép (VD: Google Workspace, Microsoft OneDrive/SharePoint...).
   * Tuyệt đối không lưu trữ dữ liệu công việc lên các tài khoản Cloud cá nhân (Google Drive cá nhân, Dropbox cá nhân) để tránh lãng phí tài nguyên và rò rỉ dữ liệu.

## PHẦN V: QUY TRÌNH ỨNG PHÓ SỰ CỐ
1. **Báo cáo sự cố an toàn thông tin:**
   * Quy trình xử lý khi phát hiện: Mất thiết bị, nhận email lừa đảo (phishing), máy tính bị nhiễm virus/Ransomware.
   * Đường dây nóng / Hệ thống Ticketing của BP IT.
2. **Kế hoạch duy trì kinh doanh (BCP):**
   * Quy định về việc IT sao lưu (Backup) dữ liệu định kỳ.

## PHẦN VI: TRÁCH NHIỆM THI HÀNH
1. **Trách nhiệm của Người lao động:** Đọc, hiểu, ký cam kết tuân thủ IT Policy.
2. **Trách nhiệm của Bộ phận IT:** Cung cấp thiết bị, giám sát hệ thống (100% Endpoint), hỗ trợ kỹ thuật và báo cáo định kỳ cho Ban Giám đốc.
3. **Trách nhiệm của Bộ phận HR:** Phối hợp chặt chẽ với IT trong khâu tiếp nhận nhân sự mới và xử lý thủ tục nhân sự nghỉ việc.
4. **Trách nhiệm của Quản lý các cấp:** Đôn đốc, giám sát nhân sự trong phòng ban tuân thủ chính sách.

## PHẦN VII: CHẾ TÀI XỬ LÝ VI PHẠM
*(Mức độ xử lý tùy thuộc vào hậu quả gây ra cho Công ty)*
* **Vi phạm nhẹ:** Nhắc nhở, lập biên bản, khóa tài khoản tạm thời để đào tạo lại.
* **Vi phạm trung bình:** Cảnh cáo toàn công ty, trừ điểm KPI/thưởng.
* **Vi phạm nghiêm trọng** *(Cố ý đánh cắp dữ liệu, làm lây lan mã độc gây đình trệ vận hành...)*: Sa thải ngay lập tức, yêu cầu bồi thường thiệt hại và/hoặc chuyển hồ sơ cho cơ quan chức năng có thẩm quyền xử lý theo pháp luật.

---
**PHỤ LỤC ĐÍNH KÈM:**
* Biểu mẫu: Ký nhận Bàn giao tài sản CNTT.
* Biểu mẫu: Cam kết Bảo mật Thông tin (NDA & IT Policy).
* Biểu mẫu: Yêu cầu Cấp quyền truy cập hệ thống / Mở khóa USB.

*Bạn có thể copy dàn ý này ra file Word để đính kèm cùng bản trình chiếu. Dàn ý này cover 100% các vấn đề thực trạng và mục tiêu bạn đã nêu trong file HTML.*
