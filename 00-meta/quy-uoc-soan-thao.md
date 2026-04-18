# Quy ước Soạn thảo Văn bản Quản trị DR DEE

> Mục tiêu: giúp toàn bộ hệ thống văn bản được viết nhất quán, dễ đọc, dễ review và dễ chuyển giao giữa các giai đoạn phát triển của công ty.

---

## 1. Nguyên tắc chung

1. Viết để **người vận hành dùng được ngay**, không viết để trình bày cho đẹp.
2. Một văn bản chỉ nên giải quyết **một nhóm vấn đề chính**.
3. Ưu tiên ngắn, rõ, có thể áp dụng; tránh lý thuyết dài dòng.
4. Khi chưa chốt chính sách, ghi rõ: `Đang chờ quyết định chính sách`.
5. Nếu chưa viết chi tiết ngay, tạo placeholder bằng template thay vì để quên trong đầu.

---

## 2. Cấu trúc chuẩn của một văn bản

Mỗi file nên có đủ các phần sau nếu phù hợp:

1. Mục đích
2. Phạm vi áp dụng
3. Nguyên tắc / định nghĩa
4. Nội dung chính
5. Vai trò và trách nhiệm
6. Quy trình / cách áp dụng
7. Biểu mẫu / dữ liệu liên quan
8. Điều khoản chuyển tiếp / ghi chú

Tham chiếu mẫu tại: [\_template-van-ban.md](./_template-van-ban.md)

---

## 3. Quy ước tên file

- Chữ thường, không dấu, dùng dấu gạch ngang
- Không dùng tên quá chung chung như `quy-trinh.md`, `huong-dan.md`
- Tên file phải phản ánh đúng nội dung chính

**Ví dụ đúng**:

- `quy-trinh-tiep-nhan-benh-nhan.md`
- `chinh-sach-luong-bac-si.md`
- `quy-dinh-bao-mat-thong-tin-benh-nhan.md`

---

## 4. Quy ước trạng thái văn bản

| Trạng thái      | Cách dùng                                 |
| --------------- | ----------------------------------------- |
| Đang soạn thảo  | Đã tạo file nhưng chưa áp dụng chính thức |
| Đang review     | Đang được góp ý hoặc chuẩn bị cập nhật    |
| Đang áp dụng    | Văn bản chính thức đang có hiệu lực       |
| Đã hết hiệu lực | Giữ lại để tra cứu lịch sử                |

---

## 5. Quy tắc viết nội dung

1. Mỗi đoạn nên trả lời rõ: ai làm, làm khi nào, làm thế nào.
2. Nếu có điều kiện tính lương / thưởng / KPI, luôn viết kèm ví dụ minh họa nếu có thể.
3. Nếu có ngoại lệ, phải ghi rõ ai có quyền quyết định ngoại lệ đó.
4. Nếu văn bản liên quan DrDee, nên ghi rõ dữ liệu nào phải nhập vào hệ thống.
5. Nếu văn bản có rủi ro tranh cãi cao, phải nêu rõ căn cứ xác định và người xác nhận.

---

## 6. Quy tắc liên kết chéo

Khi một văn bản liên quan trực tiếp đến văn bản khác, nên chèn link ở cuối hoặc ngay tại mục liên quan.

Ví dụ:

- Mô tả công việc ↔ Chính sách lương ↔ KPI
- Quy trình tiếp nhận ↔ Chuẩn nhập liệu DrDee ↔ Nguồn lead / giới thiệu
- Bổ nhiệm Điều dưỡng trưởng ↔ KPI quản lý ↔ Chính sách lương Điều dưỡng trưởng

---

## 7. Quy tắc cập nhật

Khi chỉnh sửa một văn bản đang áp dụng:

1. Xác định rõ đây là cập nhật nhỏ hay cập nhật lớn
2. Cập nhật nhỏ được phép sửa trực tiếp nếu không làm thay đổi bản chất chính sách, quy định hoặc cách vận hành
3. Cập nhật lớn phải đổi trạng thái văn bản sang `Đang review` trước khi chốt bản mới
4. Cập nhật lớn bao gồm: đổi cơ chế lương, KPI, phân quyền, trách nhiệm, luồng xử lý, tiêu chí đánh giá, dữ liệu bắt buộc hoặc bất kỳ nội dung nào có thể gây tranh cãi khi áp dụng
5. Khi ban hành lại sau review, phải cập nhật `Phiên bản`, `Hiệu lực`, `Review tiếp`, `Trạng thái`
6. Mọi lần cập nhật phải kiểm tra xem có văn bản liên quan nào cần sửa theo không
7. Nếu thay đổi ảnh hưởng đến văn bản khác, phải rà lại link chéo, thuật ngữ, biểu mẫu và hướng dẫn áp dụng liên quan
8. Sau khi cập nhật, phải cập nhật lại [danh-muc-van-ban.md](./danh-muc-van-ban.md)
9. Không sửa nội dung theo kiểu chắp vá làm sai logic gốc; nếu nội dung cũ không còn đúng, phải viết lại đoạn đó rõ ràng
10. Nếu chưa đủ thông tin để chốt bản mới, giữ trạng thái `Đang review` hoặc ghi rõ `Đang chờ quyết định chính sách`, không giả vờ coi như đã hoàn tất

### Checklist tối thiểu trước khi coi là cập nhật xong

- Đã xác định đây là cập nhật nhỏ hay lớn
- Đã cập nhật metadata nếu văn bản được ban hành lại
- Đã rà các file liên quan
- Đã cập nhật danh mục văn bản
- Đã kiểm tra người đọc mới có thể hiểu và áp dụng mà không cần giải thích miệng thêm

---

## 8. Thứ tự ưu tiên khi viết

Không viết theo cảm hứng. Luôn bám theo:

1. [lo-trinh-trien-khai.md](./lo-trinh-trien-khai.md)
2. [ban-do-he-thong-van-ban.md](./ban-do-he-thong-van-ban.md)
3. [danh-muc-van-ban.md](./danh-muc-van-ban.md)

---

## 9. Mục tiêu cuối cùng

Hệ thống văn bản phải giúp DR DEE:

- Vận hành đồng nhất giữa các chi nhánh
- Dễ đào tạo người mới
- Dễ kiểm soát tiền, người, dữ liệu, trách nhiệm
- Giảm phụ thuộc vào trí nhớ hoặc chỉ đạo miệng của người quản lý
