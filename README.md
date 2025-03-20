# Studio Ảnh Phép Thuật Gemini

Studio Ảnh Phép Thuật Gemini là một ứng dụng web đơn giản, được xây dựng bằng HTML, CSS và JavaScript thuần. Ứng dụng này cho phép người dùng tải lên hình ảnh và nhập chỉ dẫn sáng tạo để tạo ra hình ảnh mới thông qua API Gemini. Ngoài ra, ứng dụng còn hỗ trợ sử dụng nhiều ảnh tải lên (ví dụ: ảnh chính và ảnh tham chiếu) để thực hiện ghép ảnh hay chỉnh sửa theo yêu cầu.

## Tính năng chính

- **Tải lên hình ảnh**: Hỗ trợ kéo thả hoặc nhấp để tải lên nhiều hình ảnh.
- **Chọn vai trò ảnh**: Nếu tải lên nhiều ảnh, ứng dụng sẽ sử dụng ảnh đầu tiên làm ảnh chính và ảnh thứ hai làm ảnh tham chiếu.
- **Nhập chỉ dẫn sáng tạo**: Gõ chỉ dẫn (hiệu quả nhất với tiếng Anh) để kích hoạt quá trình tạo ảnh bằng API Gemini.
- **Tối ưu gợi ý**: Có chế độ tối ưu tự động cho chỉ dẫn, giúp tăng tỉ lệ tạo ảnh thành công.
- **Hiệu ứng UI/UX hiện đại**: Giao diện tối giản, hiện đại với header, footer đẹp mắt và các hiệu ứng chuyển động mượt mà.
- **Thông báo và hướng dẫn trực quan**: Ứng dụng hiển thị thông báo, hiệu ứng và tooltip hướng dẫn khi cần.

## Công nghệ sử dụng

- **HTML/CSS/JavaScript thuần**: Không sử dụng framework bên ngoài cho phần front-end.
- **API Gemini**: Gọi API của Google để tạo nội dung dựa trên chỉ dẫn và dữ liệu hình ảnh tải lên.

## Cài đặt và chạy ứng dụng

1. **Clone Repository:**

   ```bash
   git clone https://github.com/danvufs/Gemini-Image-Studio.git
   cd Gemini-Image-Studio
2. **Mở file trong trình duyệt:**

Ứng dụng không cần backend hay build tool phức tạp. Bạn chỉ cần mở file index.html trong trình duyệt hiện đại (Chrome, Firefox, Edge,...) để chạy ứng dụng.

Ví dụ:

Kích đúp file index.html hoặc
Sử dụng một server cục bộ (ví dụ: Live Server trong VSCode).
3. **Cấu hình API Key:**

Trong file index.html, bạn cần cập nhật biến API_KEY với khóa API của bạn (được cấp bởi Google). Tìm dòng sau trong phần <script> và thay đổi giá trị:

js
Copy
const API_KEY = "YOUR_API_KEY_HERE";
## Hướng dẫn sử dụng
1 **Tải lên hình ảnh:**
Nhấp vào khu vực "Nhấp hoặc kéo thả ảnh" để tải lên hình ảnh từ máy tính của bạn. Nếu tải lên nhiều ảnh, ảnh đầu tiên sẽ được sử dụng làm ảnh chính và ảnh thứ hai sẽ dùng làm ảnh tham chiếu.

2. **Nhập chỉ dẫn:**
Gõ vào ô nhập chỉ dẫn sáng tạo (hiệu quả nhất khi sử dụng tiếng Anh) để mô tả ý tưởng của bạn. Bạn có thể nhấp vào các nút gợi ý để lấy ý tưởng nhanh.

3. **Chế độ tối ưu:**
Bật chế độ "Sử dụng tối ưu ma thuật" nếu bạn muốn hệ thống tự động cải thiện chỉ dẫn để tăng tỉ lệ tạo ảnh thành công.

4. **Tạo ảnh:**
Nhấp vào nút "✨ Tạo ảnh ma thuật" để gửi yêu cầu đến API. Ứng dụng sẽ hiển thị thông báo trạng thái và kết quả tạo ảnh sau vài giây.

## Cấu trúc dự án
css
Copy
.
├── index.html       # File chính chứa HTML, CSS và JavaScript của ứng dụng.
└── README.md        # File hướng dẫn và mô tả dự án.
Góp ý & Phản hồi
Nếu bạn có bất kỳ góp ý, thắc mắc hoặc muốn đóng góp cải tiến, vui lòng tạo một issue hoặc pull request trên GitHub.

## License
Dự án này được cấp phép theo MIT License.
