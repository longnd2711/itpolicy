Dưới đây là nội dung triển khai chi tiết cho **Phần II: Tiêu chuẩn & Quản lý thiết bị**. Phần này giải quyết trực tiếp các lỗ hổng về Onboarding/Offboarding, quản lý phần mềm bản quyền và cam kết 100% thiết bị được quản lý tập trung đã nêu trong Đề xuất.

---

## PHẦN II: TIÊU CHUẨN & QUẢN LÝ THIẾT BỊ

### Điều 5. Quy định về Cấp phát và Thu hồi thiết bị (Onboarding / Offboarding)
Nhằm đảm bảo an toàn dữ liệu và tối ưu hóa tài nguyên, việc cấp phát và thu hồi tài sản CNTT phải tuân thủ quy trình chặt chẽ:

1. **Quy trình Cấp phát (Onboarding):**
   * Bộ phận Nhân sự (HR) có trách nhiệm thông báo cho Bộ phận IT (BP IT) bằng văn bản hoặc qua hệ thống nội bộ ít nhất **03 ngày làm việc** trước khi nhân sự mới tiếp nhận công việc.
   * BP IT căn cứ vào tính chất công việc và cấp bậc để chuẩn bị thiết bị (Laptop/PC), cấu hình tiêu chuẩn, khởi tạo email và phân quyền hệ thống tương ứng.
   * Nhân sự nhận thiết bị phải kiểm tra tình trạng vật lý, khả năng hoạt động và ký xác nhận vào **Biên bản Bàn giao tài sản CNTT**.

2. **Quy trình Thu hồi (Offboarding):**
   * Ngay khi có quyết định nghỉ việc hoặc chấm dứt hợp đồng, Bộ phận HR phải lập tức thông báo cho BP IT.
   * Trong vòng **04 giờ làm việc** kể từ thời điểm nhân sự chính thức nghỉ, BP IT thực hiện: 
     * Khóa (Disable) toàn bộ tài khoản Email, phần mềm, hệ thống nội bộ của nhân sự đó.
     * Cắt quyền truy cập từ xa (VPN, Cloud Drive).
   * Nhân sự nghỉ việc có trách nhiệm bàn giao lại nguyên trạng thiết bị phần cứng cho BP IT. Dữ liệu công việc trên máy sẽ được IT sao lưu (Backup) cho Quản lý trực tiếp và tiến hành xóa trắng (Wipe) thiết bị theo chuẩn an toàn để cấp phát cho người tiếp theo.

### Điều 6. Sử dụng thiết bị do Công ty cấp phát
Tài sản CNTT do Công ty cấp phát nhằm mục đích phục vụ công việc. CBNV có nghĩa vụ sử dụng đúng mục đích và bảo vệ tài sản:

1. **Trách nhiệm bảo quản vật lý:**
   * Không để thiết bị tại các khu vực thiếu an toàn (trong xe ô tô không người trông, nơi công cộng, nơi có nhiệt độ/độ ẩm khắc nghiệt).
   * Trong trường hợp xảy ra rơi vỡ, hỏng hóc hoặc mất cắp, CBNV phải báo cáo ngay lập tức cho BP IT và Quản lý trực tiếp (chậm nhất trong vòng 12 giờ) để kịp thời khóa thiết bị từ xa, chặn rò rỉ dữ liệu.
2. **Hành vi nghiêm cấm:**
   * Sử dụng thiết bị của Công ty để truy cập, lưu trữ, phát tán các nội dung đồi trụy, phản động hoặc vi phạm pháp luật.
   * Sử dụng thiết bị để tham gia cá cược, đánh bạc trực tuyến, hoặc đào tiền ảo (Crypto mining) gây quá tải và hư hại phần cứng.
   * Cho mượn, cho thuê, cầm cố hoặc cho phép người ngoài (bao gồm cả thành viên gia đình) sử dụng máy tính của Công ty.

### Điều 7. Cài đặt phần mềm và Quản lý bản quyền (Kiểm soát 100%)
Đây là nguyên tắc bắt buộc nhằm ngăn chặn rủi ro lây nhiễm Ransomware, mã độc và vi phạm pháp luật về Sở hữu trí tuệ:

1. **Quản lý thiết bị tập trung (MDM):**
   * **100% thiết bị** máy tính, laptop cấp phát cho CBNV phải được cài đặt phần mềm quản lý đầu cuối tập trung (MDM/UEM) của BP IT trước khi bàn giao.
   * CBNV nghiêm cấm hành vi tự ý gỡ bỏ, vô hiệu hóa phần mềm MDM, phần mềm diệt Virus (Antivirus) hay các công cụ giám sát do IT cài đặt.
2. **Quyền quản trị máy tính (Admin Rights):**
   * Theo cấu hình tiêu chuẩn, CBNV sẽ sử dụng máy tính dưới quyền người dùng tiêu chuẩn (Standard User). 
   * CBNV không được cung cấp mật khẩu Quản trị viên nội bộ (Local Admin) để tự cài đặt phần mềm nhằm giảm thiểu rủi ro bảo mật. Các yêu cầu cài đặt phần mềm mới phải được gửi Ticket đến BP IT.
3. **Tuyệt đối không sử dụng phần mềm vi phạm bản quyền:**
   * Chỉ những phần mềm do BP IT phê duyệt và cung cấp bản quyền mới được phép hoạt động trên thiết bị công ty.
   * Nghiêm cấm mọi hành vi tải, cài đặt, sử dụng các phần mềm bẻ khóa (Crack, Keygen, Patch, Pirated software). Nếu Công ty bị phạt từ các cơ quan thanh tra bản quyền do lỗi cố tình cài đặt của cá nhân, cá nhân đó phải hoàn toàn chịu trách nhiệm bồi thường thiệt hại.

### Điều 8. Chính sách sử dụng thiết bị cá nhân (BYOD)
Đối với các trường hợp được sự đồng ý của Ban Giám đốc cho phép sử dụng thiết bị cá nhân (Laptop, Điện thoại thông minh) để xử lý công việc và truy cập dữ liệu nội bộ:

1. **Điều kiện kết nối an toàn:** 
   * Thiết bị cá nhân phải được đăng ký thông tin với BP IT trước khi truy cập mạng nội bộ.
   * Thiết bị phải đáp ứng tiêu chuẩn bảo mật tối thiểu theo chính sách hiện hành của Công ty.
2. **Kiểm soát dữ liệu trên thiết bị cá nhân:**
   * Dữ liệu Công ty lưu trữ trên thiết bị cá nhân là tài sản của Công ty.
   * Khi nhân sự nghỉ việc hoặc thiết bị cá nhân bị mất, BP IT có quyền yêu cầu/thực hiện xóa từ xa/vô hiệu hóa **riêng biệt phần dữ liệu công việc** trên thiết bị đó (thông qua môi trường ứng dụng quản lý công việc được cài đặt sẵn).
