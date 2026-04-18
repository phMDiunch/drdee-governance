<!--
Loại văn bản : Biểu mẫu điều phối
Phiên bản    : 1.0
Hiệu lực     : 05/07/2026
Review tiếp  : 05/10/2026
Người ban hành: Tổng giám đốc
Trạng thái   : Đang áp dụng
-->

# Phân tích Thiếu & Kế hoạch Tổng

> File này trả lời 3 câu: **(1)** repo đang thiếu gì so với một hệ thống nha khoa vận hành thật, **(2)** cái gì viết trước, **(3)** mỗi khối gồm những văn bản nào.
> Đọc kèm [Lộ trình triển khai](./lo-trinh-trien-khai.md) (theo mốc thời gian) và [Bản đồ](./ban-do-he-thong-van-ban.md) (theo trạng thái).

---

## 1. Bức tranh tổng — repo đã phủ đến đâu

| Trụ cột                          | Mức phủ | Ghi chú |
| -------------------------------- | ------- | ------- |
| 01 Tổ chức                       | ~75%    | Thiếu MTCV marketing/sale online/IT/kho, khung năng lực |
| 02 Nhân sự (lương, KPI, quy trình)| ~80%   | Xương sống mạnh; đóng nốt marketing, đánh giá thử việc, đề bạt |
| 03 Vận hành — Kinh doanh         | ~90%    | Rất tốt, gần đủ dùng |
| 03 Vận hành — Marketing & CSKH   | ~5%     | Gần như trống — anh nhấn mạnh mảng này |
| 04 Tài chính                     | 0%      | Mới placeholder |
| 05 Văn bản hành chính            | ~5%     | Mới placeholder |
| 06 Đào tạo                       | 0%      | Mới placeholder |
| 07 Pháp lý — Hợp đồng            | ~70%    | Mẫu hợp đồng tốt |
| 07 Pháp lý — Tuân thủ chuyên môn | ~10%    | Hồ sơ bệnh án, bảo mật, chính sách bán chưa có |
| 08 Dữ liệu & hệ thống            | 0%      | Mới placeholder |
| **03 Y khoa — an toàn y tế**     | 0%      | **Nhóm SOP bắt buộc pháp lý (03/y-khoa), chưa viết** |

**Kết luận:** repo đã chuẩn real-world ở phần *con người & kinh doanh* (lương/KPI/tư vấn/hợp đồng). Rủi ro lớn nhất nằm ở phần *tuân thủ y tế* (khối **03/y-khoa** + hồ sơ bệnh án của 07) — đây là thứ Sở Y tế kiểm tra và là rủi ro pháp lý/uy tín cao nhất.

---

## 2. Bốn khoảng trống ưu tiên (xếp theo rủi ro)

### ① Chuyên môn lâm sàng & an toàn y tế → khối **03-van-hanh/y-khoa/**
Bắt buộc với cơ sở khám chữa bệnh. Thiếu = rủi ro đình chỉ hoạt động, tai biến, kiện tụng.
- Kiểm soát nhiễm khuẩn & tiệt trùng
- An toàn bức xạ (X-quang / CBCT)
- Quản lý chất thải y tế
- Xử trí tai biến & cấp cứu
- Quản lý thuốc & vật tư y tế
- Phác đồ chuyên môn chuẩn theo nhóm dịch vụ
- An toàn người bệnh & báo cáo sự cố

### ② Marketing vận hành → **03-van-hanh/marketing/** + MTCV trong 01
Anh nhấn mạnh nhưng repo mới có lương/KPI, chưa có SOP và MTCV.
- MTCV: Content, Biên kịch, Quay dựng, Thiết kế, Sale online
- Quy trình sản xuất nội dung (ý tưởng → kịch bản → quay → dựng → duyệt → đăng)
- **Quy định duyệt nội dung y tế** (tránh vi phạm quảng cáo dịch vụ khám chữa bệnh — rủi ro pháp lý riêng của ngành)
- Quản lý kênh (fanpage, TikTok, website, Zalo OA) & lịch đăng
- Phối hợp Marketing → Sale online → Lễ tân (bàn giao lead)

### ③ Khách hàng & chính sách bán → **07** (chính sách) + **03/cham-soc-khach-hang/**
Hợp đồng đã có, nhưng *chính sách nền* phía sau thì chưa.
- Chính sách giá & bảng giá dịch vụ
- Chính sách bán / khuyến mãi / trả góp
- Chính sách bảo hành (bản chính sách, khác với cam kết trong hợp đồng)
- Chăm sóc sau điều trị: tái khám, nhắc bảo hành, thu review & giới thiệu
- Chương trình khách hàng thân thiết

### ④ Tài chính & dữ liệu → **04** + **08**
Chống thất thoát tiền, hàng, dữ liệu — theo đúng lộ trình gốc.
- 04: phân quyền chi tiêu, mua hàng, kiểm kê, hoàn tiền/miễn giảm, đối soát doanh thu, kiểm soát hoa hồng
- 08: chuẩn nhập liệu DrDee, phân quyền tài khoản, vòng đời tài khoản, xử lý sai dữ liệu

---

## 3. Kế hoạch xây theo đợt (bám lộ trình gốc)

Nguyên tắc: mỗi đợt **chốt trọn 1 cụm** rồi mới sang cụm sau; cập nhật trạng thái trong [danh mục](./danh-muc-van-ban.md).

| Đợt | Cụm | Đầu việc chính | Vì sao đợt này |
| --- | --- | --- | --- |
| **A** | Đóng nốt 02 + 03 kinh doanh | KPI/lương marketing hoàn chỉnh, đánh giá thử việc, đề bạt/miễn nhiệm | Gần xong, dứt điểm để khỏi dở dang |
| **B** | 03 Marketing + CSKH + MTCV còn thiếu | SOP sản xuất content, duyệt nội dung y tế, MTCV marketing/sale online, CSKH sau điều trị | Mảng anh nhấn mạnh, đang trống |
| **C** | 04 Tài chính | Phân quyền chi tiêu, mua hàng, kiểm kê, hoàn tiền, đối soát, hoa hồng | Chống thất thoát |
| **D** | 08 Dữ liệu & hệ thống | Chuẩn nhập liệu DrDee, phân quyền & vòng đời tài khoản | Nền dữ liệu cho tài chính & vận hành |
| **E** | **03/y-khoa — An toàn y tế** | Nhiễm khuẩn, bức xạ, chất thải, tai biến, thuốc/vật tư, phác đồ | Bắt buộc pháp lý — không để trễ hơn |
| **F** | 07 Tuân thủ chuyên môn | Hồ sơ bệnh án, bảo mật/hình ảnh BN, chính sách bán/giá/bảo hành | Khép rủi ro pháp lý |
| **G** | 06 Đào tạo + 05 Hành chính | Onboarding theo vị trí, thi bậc, mẫu quyết định/thông báo | Chuẩn hóa để scale |

> Ghi chú: khối 03/y-khoa có thể **kéo lên song song với đợt B** nếu sắp có đợt thanh tra hoặc mở cơ sở mới, vì đây là điều kiện cấp phép.

---

## 4. Danh sách văn bản cần tạo (theo trụ cột)

### 01 — MTCV còn thiếu
`mo-ta-cong-viec/`: `sale-online.md`, `marketing-content.md`, `marketing-bien-kich.md`, `marketing-quay-dung.md`, `marketing-thiet-ke.md`, `it-data.md`, `thu-kho-vat-tu.md`

### 03 — Marketing (`03-van-hanh/marketing/`)
`quy-trinh-san-xuat-noi-dung.md`, `quy-dinh-duyet-noi-dung-y-te.md`, `quan-ly-kenh-va-lich-dang.md`, `quy-trinh-ban-giao-lead.md`, `chuan-thuong-hieu-hinh-anh.md`, `bieu-mau/` (brief content, kịch bản, lịch đăng)

### 03 — Chăm sóc khách hàng (`03-van-hanh/cham-soc-khach-hang/`)
`quy-trinh-tai-kham-va-bao-hanh.md`, `quy-trinh-thu-thap-review-gioi-thieu.md`, `chuong-trinh-khach-hang-than-thiet.md`

### 04 — Tài chính
`phan-quyen-chi-tieu.md`, `quy-trinh-mua-hang.md`, `quy-trinh-kiem-ke-kho.md`, `quy-trinh-hoan-tien-mien-giam.md`, `doi-soat-doanh-thu.md`, `kiem-soat-hoa-hong.md`

### 08 — Dữ liệu & hệ thống
`chuan-nhap-lieu-drdee.md`, `phan-quyen-tai-khoan.md`, `vong-doi-tai-khoan.md`, `xu-ly-sai-du-lieu.md`, `bao-mat-thiet-bi-truy-cap.md`

### 03 — Y khoa: an toàn & chuyên môn (`03-van-hanh/y-khoa/`)
`kiem-soat-nhiem-khuan.md`, `an-toan-buc-xa.md`, `quan-ly-chat-thai-y-te.md`, `xu-tri-tai-bien-cap-cuu.md`, `quan-ly-thuoc-vat-tu-y-te.md`, `phac-do-chuyen-mon/` (theo nhóm dịch vụ), `an-toan-nguoi-benh-bao-cao-su-co.md`

### 07 — Tuân thủ chuyên môn & chính sách bán
`ho-so-benh-an/` (chuẩn lập–lưu–tra cứu), `bao-mat-va-hinh-anh-benh-nhan.md`, `lam-viec-voi-co-quan-quan-ly.md`, và cụm **chính sách bán**: `chinh-sach-gia-va-bang-gia.md`, `chinh-sach-ban-khuyen-mai.md`, `chinh-sach-bao-hanh.md`

### 05 — Hành chính
`_mau-quyet-dinh.md`, `_mau-thong-bao.md`, `_mau-bien-ban.md`

---

## 5. Cách dùng file này

1. Chọn đợt đang làm (mục 3).
2. Lấy danh sách file của cụm đó (mục 4).
3. Với mỗi file: đọc [quy ước soạn thảo](./quy-uoc-soan-thao.md), tạo từ [template](./_template-van-ban.md), viết.
4. Cập nhật [danh mục](./danh-muc-van-ban.md) và tick trạng thái trong [bản đồ](./ban-do-he-thong-van-ban.md).
5. Khi phát sinh đầu mục mới, bổ sung vào mục 4 file này.
