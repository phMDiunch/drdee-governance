# GOVERNANCE.md

> File định hướng trung tâm của repo `drdee-governance`.
> Nếu đây là lần đầu bạn vào repo này, hãy đọc file này trước.

---

## 1. Repo này là gì?

`drdee-governance` là kho văn bản quản trị nội bộ của Nha khoa Quốc tế DR DEE.

Repo này không phải repo phần mềm. Đây là nơi lưu trữ, tổ chức và phát triển toàn bộ hệ thống văn bản phục vụ quản trị doanh nghiệp, vận hành đa chi nhánh, đào tạo và kiểm soát nội bộ.

Mục tiêu của repo này là giúp DR DEE:

- Vận hành đồng nhất giữa các chi nhánh
- Chuẩn hóa vai trò, trách nhiệm, quyền hạn
- Chuẩn hóa lương, KPI, quy trình, đào tạo
- Giảm phụ thuộc vào chỉ đạo miệng hoặc trí nhớ của quản lý
- Tạo nền để phát triển bền vững và mở rộng lâu dài

---

## 2. Repo này liên hệ với `drdee-antd` như thế nào?

- `drdee-antd`: repo phần mềm quản trị
- `drdee-governance`: repo văn bản quản trị

Hai repo tách riêng để:

- dễ commit và review hơn
- không trộn thay đổi code với thay đổi chính sách / quy trình
- giữ repo phần mềm gọn hơn
- giúp hệ thống văn bản có đời sống riêng

Khi cần tham chiếu code và tài liệu cùng lúc, mở workspace chung:

- `C:\Users\drpha\Documents\Code\drdee.code-workspace`

---

## 3. Cách hiểu hệ thống văn bản

Hệ thống tài liệu này được chia theo 5 tầng:

```text
Tầng 1 — QUY CHẾ
Tầng 2 — CHÍNH SÁCH
Tầng 3 — QUY ĐỊNH
Tầng 4 — QUY TRÌNH
Tầng 5 — BIỂU MẪU
```

### Tầng 1 — Quy chế

- Là lớp nền tảng nhất
- Xác định khung tổ chức, nguyên tắc vận hành cấp công ty
- Ít thay đổi nhất

### Tầng 2 — Chính sách

- Là các cơ chế vận hành và quản trị đã được chốt
- Ví dụ: lương, KPI, đề bạt, thưởng, phân quyền
- Review định kỳ hàng năm

### Tầng 3 — Quy định

- Là các rule cụ thể áp dụng cho nội bộ
- Ví dụ: nội quy lao động, bảo mật, tác phong, sử dụng tài sản

### Tầng 4 — Quy trình

- Là SOP, mô tả cách làm việc thực tế từng bước
- Ví dụ: tiếp nhận bệnh nhân, tuyển dụng, xử lý khiếu nại

### Tầng 5 — Biểu mẫu

- Là checklist, template, form và tài liệu thực thi

Nguyên tắc: tầng trên có giá trị ưu tiên cao hơn tầng dưới.

---

## 4. Cấu trúc thư mục của repo

```text
00-meta/                 Điều phối hệ thống văn bản
01-to-chuc/              Tổ chức, sơ đồ, quyền hạn, mô tả công việc
02-nhan-su/              Lương, KPI, quy định và quy trình nhân sự
03-van-hanh/             SOP vận hành phòng khám
04-tai-chinh/            Kiểm soát tài chính và chi tiêu nội bộ
05-van-ban-hanh-chinh/   Quyết định, thông báo, văn bản chính thức
06-dao-tao/              Đào tạo nội bộ, onboarding, thi bậc, quản lý cấp trung
07-phap-ly-va-tuan-thu/  CCHN, hồ sơ, bảo mật, tuân thủ
08-du-lieu-va-he-thong/  Chuẩn nhập liệu, lead, tài khoản, dữ liệu DrDee
```

Nếu muốn nhìn toàn cục hơn, mở tiếp:

- `00-meta/ban-do-he-thong-van-ban.md`

---

## 5. Nếu muốn viết tài liệu mới, mở gì trước?

Mỗi khi chuẩn bị viết thêm một văn bản, đọc theo thứ tự này:

1. `GOVERNANCE.md`
2. `00-meta/lo-trinh-trien-khai.md`
3. `00-meta/ban-do-he-thong-van-ban.md`
4. `00-meta/quy-uoc-soan-thao.md`
5. `00-meta/_template-van-ban.md`
6. `00-meta/danh-muc-van-ban.md`

Ý nghĩa:

- `GOVERNANCE.md`: hiểu hệ thống này vận hành thế nào
- `lo-trinh-trien-khai.md`: biết nên viết cái gì trước
- `ban-do-he-thong-van-ban.md`: tránh quên đầu mục lớn
- `quy-uoc-soan-thao.md`: giữ cách viết nhất quán
- `_template-van-ban.md`: tạo file mới đúng format
- `danh-muc-van-ban.md`: cập nhật trạng thái và theo dõi tiến độ

---

## 6. Thứ tự triển khai đúng mục tiêu

Repo này không được viết theo cảm hứng.

Nguyên tắc triển khai:

1. Viết cái ảnh hưởng trực tiếp đến vận hành trước
2. Viết cái có thể giảm tranh cãi, giảm thất thoát, giảm phụ thuộc trước
3. Chỉ tạo placeholder cho các khối chưa cần viết sâu ngay
4. Không cố làm đủ hết cùng lúc

Thứ tự ưu tiên hiện tại:

1. `02-nhan-su`
2. `03-van-hanh`
3. `04-tai-chinh`
4. `08-du-lieu-va-he-thong`
5. `06-dao-tao`
6. `07-phap-ly-va-tuan-thu`
7. `05-van-ban-hanh-chinh` hoàn thiện dần

---

## 7. Quy tắc viết văn bản trong repo này

Tóm tắt ngắn gọn:

- Viết để người dùng làm được việc ngay
- Mỗi file nên giải quyết một vấn đề chính
- Không viết quá lý thuyết nếu chưa gắn với thực tế DR DEE
- Nếu chính sách chưa chốt, ghi rõ `Đang chờ quyết định chính sách`
- Nếu chưa đủ thông tin, tạo placeholder thay vì để quên
- Luôn link chéo giữa mô tả công việc, lương, KPI, quy trình nếu có liên quan

Chi tiết đầy đủ xem tại:

- `00-meta/quy-uoc-soan-thao.md`

---

## 8. Quy trình cập nhật một văn bản

Khi chỉnh sửa tài liệu đang dùng:

1. Xác định đây là thay đổi nhỏ hay thay đổi lớn
2. Nếu thay đổi lớn, đổi trạng thái sang `Đang review`
3. Cập nhật lại `Phiên bản`, `Hiệu lực`, `Review tiếp` nếu đã ban hành lại
4. Kiểm tra xem có file liên quan nào cần sửa theo không
5. Cập nhật `00-meta/danh-muc-van-ban.md`

---

## 9. Khi nào nên tạo file mới?

Tạo file mới khi:

- nội dung đó là một policy / SOP / rule riêng biệt
- người đọc cần mở trực tiếp để dùng
- nội dung đã đủ lớn để không nên nhét chung vào file khác

Không cần tạo file mới khi:

- chỉ là một ghi chú nhỏ trong cùng một chính sách hiện hữu
- nội dung chưa đủ rõ, mới là ý tưởng rời rạc
- có thể ghi vào placeholder hoặc mục TODO trong file điều phối

---

## 10. Mục tiêu cuối cùng của repo này

Repo này không phải để “có tài liệu cho đẹp”.

Mục tiêu cuối cùng là tạo ra một hệ thống văn bản giúp DR DEE:

- vận hành được ngay cả khi người sáng lập không có mặt thường xuyên
- mở thêm chi nhánh mà không vỡ hệ thống
- đào tạo người mới nhanh hơn
- giảm rủi ro tranh cãi về người, tiền, trách nhiệm và dữ liệu
- biến tri thức quản lý thành tài sản của công ty, không nằm rải rác trong đầu từng cá nhân
