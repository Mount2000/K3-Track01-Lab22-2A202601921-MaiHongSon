THÔNG TIN TỔNG HỢP CÁ NHÂN

Họ tên: Nguyễn Tuấn Vũ
Mã học viên: 2A202601845
Ngành: Giáo dục – AI Tutor

1. Ý tưởng sản phẩm
VietNamese AI Tutor là gia sư AI tự động giúp người nước ngoài học từ vựng, phát âm, ngữ pháp, hội thoại và văn hóa Việt Nam.

2. Mức tự động hóa
Fully-automated trong bài học thông thường. Khi không chắc chắn hoặc gặp nội dung nhạy cảm, AI phải xin lỗi, không suy đoán và chuyển tới từ điển, giáo trình chính thức hoặc người phụ trách.

3. Các rủi ro chính
- AI dạy câu sai, tục tĩu hoặc xúc phạm khiến người học sử dụng sai ngoài đời.
- AI tạo stereotype hoặc nội dung thiếu tôn trọng vùng miền và văn hóa Việt Nam.
- AI đưa đáp án trực tiếp khiến người học phụ thuộc và không thể tự giao tiếp.

4. Người bị ảnh hưởng
- Người nước ngoài học tiếng Việt.
- Người Việt và các cộng đồng vùng miền được AI mô tả.
- Giảng viên và đơn vị vận hành sản phẩm.

5. Failure modes và failure layers
- harmful-advice → user-experience
- bias-fairness → model
- over-reliance → user-experience
Ngoài ra, governance-process có thể làm harm tăng nếu nội dung không được kiểm duyệt.

6. Những việc bắt buộc có con người kiểm tra
- Duyệt joke, tiếng lóng và nội dung văn hóa trước khi phát hành.
- Kiểm thử nội dung đại diện cho miền Bắc, Trung và Nam.
- Duyệt cách AI đưa gợi ý để tránh làm hộ người học.
- Duyệt consent, lưu trữ và xóa bản ghi âm.
- Phê duyệt legal classification trước pilot.

7. Guardrails quan trọng nhất
- Không có nội dung tục tĩu, xúc phạm hoặc phân biệt nghiêm trọng.
- Chỉ dùng nguồn học liệu đã được duyệt.
- AI phải hướng dẫn từng bước thay vì đưa đáp án ngay.
- Không lưu bản ghi âm nếu người học chưa đồng ý.
- Khi vượt ngưỡng rủi ro phải dừng bài học và review.

8. KPI/KRI
- Ít nhất 70% người học pilot cải thiện tối thiểu 20% điểm kiểm tra độc lập sau 4 tuần.
- Không quá 2 nội dung sai hoặc phản cảm trên 1.000 lượt tương tác.
- Chênh lệch điểm giữa bài có AI và bài không có AI không quá 10%.

9. Release decision
research-only

Lý do: chưa có bằng chứng kiểm duyệt nội dung, fairness test, guardrail chống phụ thuộc, privacy evidence và signed legal classification memo. Chỉ xem xét mở pilot sau khi hoàn thành các blocker này.

10. Pattern rút ra cho nhóm
AI càng tự động và phục vụ càng nhiều người thì lỗi nội dung càng dễ lan rộng. Human oversight cần nằm ở bước duyệt nội dung, kiểm thử trước release, giám sát production và xử lý khi vượt ngưỡng; không chỉ kiểm tra model.