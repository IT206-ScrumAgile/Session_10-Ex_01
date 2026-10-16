# BÀI THỰC HÀNH 1 – CHUẨN BỊ SPRINT REVIEW RIKKEISAFE

## Nhiệm vụ 1 - Hoàn thành phiếu chuẩn bị Sprint Review

| Bước | Việc cụ thể cho buổi Review này |
|---|---|
| 1. Chốt mục tiêu và người tham gia | Mục tiêu: xem người dùng có tự kiểm tra được số, link và hiểu cảnh báo không. Mời đủ 3 Stakeholders. |
| 2. Kiểm tra Increment | **PBI được trình diễn là Done:** PBI-01 (Kiểm tra số điện thoại), PBI-02 (Kiểm tra đường link), PBI-03 (Gửi báo cáo số hoặc link đáng ngờ) – cả 3 đạt đủ 5 điều kiện DoD.<br>**PBI phải nói rõ là chưa Done, kèm điều kiện DoD chưa đạt:**<br>- PBI-04 (Lưu lịch sử kiểm tra): chưa đạt điều kiện (1) làm đủ các chức năng đã thống nhất – còn thiếu xóa lịch sử và lọc theo loại.<br>- PBI-05 (Hướng dẫn khi đã lỡ chuyển tiền): chưa đạt điều kiện (2) review chéo và điều kiện (3) kiểm thử trên điện thoại (mới kiểm thử trên máy tính). |
| 3. Chọn User Journey và người demo | **User Journey:** Nhận tin nhắn có số điện thoại lạ → mở RikkeiSafe → nhập số điện thoại để kiểm tra → xem cảnh báo kèm lý do → dán đường link đáng ngờ để kiểm tra → xem cảnh báo kèm lý do → gửi báo cáo số hoặc link đáng ngờ.<br>**Người demo:** Thu An (Developer) thao tác trực tiếp trên bản chạy được bằng tài khoản dùng thử; Ngọc Hương (Product Owner) dẫn dắt và giải thích ý nghĩa với người dùng. |
| 4. Chuẩn bị kỹ thuật | Kiểm tra bản chạy được, tài khoản dùng thử, đường truyền họp trực tuyến. |
| 5. Chuẩn bị trao đổi | **2 câu hỏi mở dành cho Stakeholders:**<br>(1) Khi xem cảnh báo, anh/chị hiểu vì sao số điện thoại hoặc đường link bị cho là đáng ngờ chưa? Phần nào còn khó hiểu?<br>(2) Nếu tự dùng trên điện thoại, anh/chị thấy bước nào khi kiểm tra hoặc gửi báo cáo còn vướng, và anh/chị mong muốn điều gì thêm? |
| 6. Chia thời gian | Xem lịch trình ở Nhiệm vụ 2. |

## Nhiệm vụ 2 - Sửa lịch trình Sprint Review

| Thời gian | Hoạt động | Nhận xét và cách sửa |
|---|---|---|
| 0–5' | Product Owner nhắc Sprint Goal. | Phù hợp, giữ nguyên. |
| 5–20' | Product Owner trình diễn cả 5 PBI, giới thiệu PBI-05 là đã hoàn thành. | **Sai:** (1) PBI-05 chưa Done (chưa review chéo, mới kiểm thử trên máy tính) nhưng bị giới thiệu là đã hoàn thành; PBI-04 cũng chưa Done (thiếu 2 chức năng) mà vẫn đưa vào trình diễn; (2) Product Owner trình diễn, trong khi Developers là người làm ra sản phẩm.<br>**Sửa:** Developer (Thu An) demo bản chạy được theo User Journey, chỉ với PBI-01, 02, 03 (đã Done). Product Owner nói rõ PBI-04 và PBI-05 chưa Done, kèm điều kiện DoD chưa đạt, không trình diễn như sản phẩm đã hoàn thành. |
| 20–32' | Từng Developer lần lượt báo cáo việc cá nhân mình đã làm. | **Sai:** Sprint Review là để kiểm tra Increment và lấy Feedback từ Stakeholders, không phải họp báo cáo công việc cá nhân; Stakeholders chỉ ngồi nghe, không có cơ hội dùng thử và góp ý.<br>**Sửa:** Product Owner đặt 2 câu hỏi mở cho Stakeholders, mời cô Mai, anh Phúc, chị Vy xem/dùng thử và nói ý kiến. Developers lắng nghe, trả lời thắc mắc về sản phẩm; Product Owner/Scrum Team ghi lại Feedback, không hứa làm ngay. |
| 32–35' | Stakeholders được nói trong 3 phút cuối; Scrum Master chốt góp ý nào sẽ làm ở Sprint sau. | **Sai:** (1) Stakeholders chỉ có 3 phút cuối, quá ít; (2) Scrum Master không quyết định việc gì được làm; thứ tự ưu tiên Product Backlog do Product Owner quyết định, và chưa thể chốt ngay tại buổi Review.<br>**Sửa:** Stakeholders đã góp ý xuyên suốt ở phần 20–32'. Ở 3 phút cuối, Product Owner tóm tắt các Feedback đã ghi, nói rõ sẽ đưa vào Product Backlog để xem xét, chưa cam kết làm Sprint sau. Scrum Master hỗ trợ giữ thời gian và cảm ơn các Stakeholders. |

## Nhiệm vụ 3 - Ghi nhận Feedback

| Mã | Góp ý | Cách xử lý |
|---|---|---|
| FB-01 | Anh Phúc: nên có nút hướng dẫn gọi ngân hàng khi người dùng báo đã chuyển tiền. | Ghi vào Product Backlog để Product Owner xem xét cùng PBI-05; chưa hứa làm ngay. |
| FB-02 | Chị Vy: muốn thêm chức năng chia sẻ cảnh báo cho người thân. Việc này nằm ngoài Sprint Goal. | Product Owner (Ngọc Hương) ghi vào Product Backlog như một ý tưởng/PBI mới, sau đó xem xét giá trị và độ ưu tiên so với các PBI khác. Vì nằm ngoài Sprint Goal nên không đưa vào Sprint hiện tại, chưa hứa làm ngay; cảm ơn chị Vy đã góp ý. |
| FB-03 | Cô Mai: dán đường link rất dài thì nút "Kiểm tra" bị đẩy ra ngoài màn hình điện thoại (PBI-02). | Ghi vào Product Backlog dưới dạng lỗi hiển thị trên điện thoại của PBI-02. Developers tái hiện lỗi trên điện thoại và tìm nguyên nhân; Product Owner xem xét độ ưu tiên (đề xuất cao vì ảnh hưởng người dùng lớn tuổi) và sắp xếp vào Sprint sau; chưa hứa làm ngay. |
