# Connected Feedback Prototype

Bản thử nghiệm giao diện quản lý feedback học viên theo mô hình bản đồ ý tưởng tương tự Connected Papers.

## Chạy trong VS Code

1. Mở thư mục project bằng VS Code.
2. Mở thư mục `dist`.
3. Nhấp chuột phải vào `index.html` và chọn **Open with Live Server**.

Nếu chưa có Live Server, có thể cài extension **Live Server** của Ritwick Dey. Prototype không cần cài package hoặc database.

## Chức năng hiện có

- Tạo lớp bằng mã lớp và danh sách học sinh.
- Bấm trực tiếp vào card lớp để mở màn hình nhập feedback.
- Nhập feedback cho toàn bộ học sinh trong lớp bằng table.
- Tìm kiếm, lọc trạng thái và sắp xếp danh sách học sinh.
- Tự động lưu nháp trong phiên, dùng comment mẫu và xem evidence đề xuất.
- Hoàn tất nhiều feedback cùng lúc theo ngày và môn học.
- Nhập comment tự nhiên sau từng buổi học.
- Chọn hoặc nhập môn học tương ứng với comment.
- Xem feedback riêng theo từng môn và tạo một feedback tổng hợp trong ngày.
- Tách comment thành evidence và đề xuất pattern.
- Giáo viên xác nhận hoặc đổi loại evidence trước khi lưu.
- Cập nhật evidence đã xác nhận vào Student Map.
- Chọn học viên và xem Student Map.
- Class Pattern hiển thị nhiều học sinh có điểm chung trên một cửa sổ rộng.
- Node chỉ hiển thị ý chính; bấm vào node để xem môn học, pattern và bằng chứng chi tiết.
- Đặt lịch kiểm tra lại ngay khi xác nhận evidence.
- Xem lịch follow-up chung hoặc lịch riêng của từng lớp và cập nhật trạng thái theo dõi.
- Xem lại lịch sử feedback theo từng ngày.
- Bấm vào node để chọn ý feedback.
- Tạo bản nháp feedback từ các ý đã chọn.
- Sao chép feedback.
- Hiển thị phù hợp trên laptop và điện thoại.

## Dữ liệu ban đầu

- Giữ sẵn hai lớp `VAP-7D` và `VAP-8B` cùng danh sách học sinh.
- Giữ danh sách môn học: Maths, ELA, Social Studies, Science, Grammar, Spanish và English Communication.
- Không kèm bất kỳ feedback, evidence, pattern hay lịch follow-up mẫu nào.

## Giới hạn của prototype

- Dữ liệu hiện là dữ liệu mẫu trong `dist/app.js`.
- Chưa có đăng nhập, lưu dữ liệu hoặc AI.
- Nội dung sẽ trở về trạng thái ban đầu khi tải lại trang.
