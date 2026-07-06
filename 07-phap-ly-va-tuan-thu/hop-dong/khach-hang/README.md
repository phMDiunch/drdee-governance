# Hợp đồng Khách hàng

> **Bộ hồ sơ khách hàng đầy đủ** (không chỉ hợp đồng): hợp đồng · phiếu khám · biên bản · hướng dẫn · phiếu đồng ý. Tổ chức **theo dịch vụ**: mỗi thư mục dịch vụ là 1 bộ hồ sơ hoàn chỉnh. Phiếu đồng ý dùng chung ở [thư mục phiếu đồng ý](./phieu-dong-y/README.md).
>
> Đối tượng đọc: **Lễ tân/Thu ngân · Tư vấn viên · Bác sĩ · Điều dưỡng · Quản lý cơ sở.**
>
> 📇 **Mục lục toàn bộ giấy tờ khách hàng (tên Việt + tên Anh):** [danh-muc-ho-so-khach-hang.md](./danh-muc-ho-so-khach-hang.md)

## Cấu trúc

```
khach-hang/
├── implant/  rang-su/  chinh-nha/   ← mỗi thư mục = bộ hồ sơ dịch vụ:
│      hợp đồng · phiếu khám · phụ lục điều chỉnh/phát sinh ·
│      biên bản hoàn tất · đơn dừng/thanh lý · hướng dẫn chăm sóc
├── phieu-dong-y/                    ← thư viện phiếu đồng ý (dùng chung)
├── README.md · danh-muc-ho-so-khach-hang.md
└── phan-cong-va-kiem-soat-hop-dong-khach-hang.md   (quy chế governance)
```

---

## Ba loại giấy tờ — đừng nhầm vai

| Loại | Là gì | Ai ký (phía DR DEE) | Ký khi nào |
| ---- | ----- | ------------------- | ---------- |
| **Phiếu khám & lập kế hoạch** | Khám, chẩn đoán, kế hoạch, **mục tiêu** — thuộc **hồ sơ bệnh án**. Gồm cả **khai báo tiền sử**. | **Bác sĩ** | Ngay sau khi khám |
| **Hợp đồng dịch vụ** | Thương mại: dịch vụ, **giá**, quyền–nghĩa vụ, bảo hành | **Quản lý cơ sở** (hoặc người được ủy quyền) | Khi khách chốt |
| **Phiếu đồng ý (consent)** | Đồng ý sau khi hiểu **rủi ro** — thuộc hồ sơ bệnh án | **Bác sĩ giải thích** + khách | **Trước khi thực hiện thủ thuật** |

> **Nguyên tắc vàng:** consent do **bác sĩ giải thích trực tiếp rồi mới ký**, ký **trước** thủ thuật — KHÔNG đưa khách tự đọc tự ký, KHÔNG gộp ký một lượt cho xong.

---

## Trình tự sử dụng (theo bước)

| Bước | Ai làm | Giấy tờ | Việc cụ thể |
| ---- | ------ | ------- | ----------- |
| **1. Tiếp đón** | Lễ tân | Form bệnh nhân mới | Thu thập thông tin, tạo **Mã KH** trên DrDee |
| **2. Khám & lập kế hoạch** | Bác sĩ | **Phiếu khám** (theo dịch vụ) | Khám, ghi tiền sử, chẩn đoán, kế hoạch, **mục tiêu**; bác sĩ + khách ký |
| **3. Tư vấn & báo giá** | Tư vấn viên / Quầy | Bảng giá (trong hợp đồng) | Báo **giá niêm yết**, áp **ưu đãi theo bảng giá công bố**, chọn phương án thanh toán |
| **4. Ký hợp đồng** | Quản lý cơ sở + khách | **Hợp đồng dịch vụ** (in PHẦN B) | Điền chi phí ca, ký **2 bản** — khách giữ 1 |
| **5. Ký consent** | Bác sĩ giải thích + khách | **Đồng ý điều trị chung** + **consent đặc thù** | Ký **trước thủ thuật**; nếu dùng ảnh → thêm **Đồng ý hình ảnh** (tự nguyện) |
| **6. Thu tiền** | Lễ tân/Thu ngân + Kế toán | Chứng từ | Thu theo đợt, xuất phiếu thu/hóa đơn |
| **7. Thực hiện điều trị** | Bác sĩ + Điều dưỡng | Hồ sơ bệnh án | Ghi diễn tiến; phát sinh phải **báo & thống nhất trước** |
| **8. Lưu hồ sơ** | Điều dưỡng / Back office | Cả bộ | Gộp thành **1 bộ hồ sơ bệnh án theo khách** (giấy + DrDee) |
| **9. Bảo hành & tái khám** | Bác sĩ + Quản lý cơ sở | Theo điều khoản HĐ | Nhắc lịch, ghi nhận bảo hành/tinh chỉnh |

> Với phẫu thuật (implant, nhổ răng khôn…): **ký consent ở buổi tư vấn, trước ngày mổ** để khách có thời gian cân nhắc.

---

## Hợp đồng theo dịch vụ _(bản đề xuất — chưa ban hành)_

| Dịch vụ | Hợp đồng | Phiếu khám (hồ sơ bệnh án) |
| ------- | -------- | -------------------------- |
| **Implant** | [hop-dong-implant.md](./implant/hop-dong-implant.md) — bảo hành 2 mức (BHTD/BHUT) | [phieu-kham-implant.md](./implant/phieu-kham-implant.md) |
| **Răng sứ** | [hop-dong-rang-su.md](./rang-su/hop-dong-rang-su.md) — bảo hành 1 mức theo loại sứ | [phieu-kham-rang-su.md](./rang-su/phieu-kham-rang-su.md) |
| **Chỉnh nha** | [hop-dong-chinh-nha.md](./chinh-nha/hop-dong-chinh-nha.md) — khung + PL mắc cài/khay trong | [phieu-kham-chinh-nha.md](./chinh-nha/phieu-kham-chinh-nha.md) |

> Mỗi thư mục dịch vụ còn có **3 biên bản quá trình** (_phụ lục điều chỉnh/phát sinh_ · _hoàn tất/bàn giao_ · _đơn dừng/thanh lý_) và **hướng dẫn chăm sóc** trước–sau. Xem đầy đủ ở [Mục lục hồ sơ](./danh-muc-ho-so-khach-hang.md).
>
> Quầy dùng [Checklist ký hợp đồng](../../../03-van-hanh/kinh-doanh/bieu-mau/checklist-ky-hop-dong.md) để đối chiếu đủ giấy khi ký.

## Checklist BỘ HỒ SƠ theo dịch vụ _(in & ký cho mỗi khách)_

> Mỗi phiếu khám đã **tự chứa phần khai báo tiền sử**. Consent lấy từ [module Đồng ý điều trị](./phieu-dong-y/README.md).

**① Implant:** ☐ [HĐ implant](./implant/hop-dong-implant.md) · ☐ [Phiếu khám implant](./implant/phieu-kham-implant.md) · ☐ [Đồng ý điều trị chung](./phieu-dong-y/dong-y-dieu-tri-chung.md) · ☐ [**Đồng ý phẫu thuật implant**](./phieu-dong-y/dong-y-phau-thuat-implant.md) · ☐ (nếu nhổ răng) [Đồng ý nhổ răng](./phieu-dong-y/dong-y-nho-rang-phau-thuat.md) · ☐ (nếu dùng ảnh) [Đồng ý hình ảnh](./phieu-dong-y/dong-y-su-dung-hinh-anh.md)

**② Răng sứ:** ☐ [HĐ răng sứ](./rang-su/hop-dong-rang-su.md) · ☐ [Phiếu khám răng sứ](./rang-su/phieu-kham-rang-su.md) · ☐ [Đồng ý điều trị chung](./phieu-dong-y/dong-y-dieu-tri-chung.md) · ☐ [**Đồng ý làm răng sứ & mài răng**](./phieu-dong-y/dong-y-lam-rang-su.md) · ☐ (nếu lấy tủy) [Đồng ý nội nha](./phieu-dong-y/dong-y-noi-nha.md) · ☐ (nếu dùng ảnh) [Đồng ý hình ảnh](./phieu-dong-y/dong-y-su-dung-hinh-anh.md)

**③ Chỉnh nha:** ☐ [HĐ chỉnh nha](./chinh-nha/hop-dong-chinh-nha.md) · ☐ [Phiếu khám chỉnh nha](./chinh-nha/phieu-kham-chinh-nha.md) · ☐ [Đồng ý điều trị chung](./phieu-dong-y/dong-y-dieu-tri-chung.md) · ☐ [**Đồng ý chỉnh nha**](./phieu-dong-y/dong-y-chinh-nha.md) · ☐ (nếu nhổ răng/gây tê) phiếu tương ứng · ☐ (nếu dùng ảnh) [Đồng ý hình ảnh](./phieu-dong-y/dong-y-su-dung-hinh-anh.md)

---

## Lưu ý bắt buộc

1. **In hợp đồng chỉ từ PHẦN B** (phần đầu file là ghi chú nội bộ — không in).
2. **Khách dưới 18 tuổi hoặc hạn chế năng lực hành vi**: người đại diện/giám hộ ký.
3. **Khách không thạo tiếng Việt**: phải có người phiên dịch ký xác nhận.
4. **Giá ưu đãi** áp theo **bảng giá công bố tại thời điểm ký** — không tự ghi giá tùy tiện.
5. **Không hứa "chắc chắn đạt kết quả"** — mọi văn bản đã thống nhất là **cam kết nỗ lực chuyên môn**.
6. Lưu **01 bản mỗi giấy tờ trong hồ sơ bệnh án**; giao khách 01 bản hợp đồng. Cập nhật **DrDee** trong ngày.

---

## Dùng chung & governance

- [Thư viện Phiếu đồng ý](./phieu-dong-y/README.md) — phiếu đồng ý dùng chung mọi dịch vụ
- [Quy chế Phân công & Kiểm soát HĐ](./phan-cong-va-kiem-soat-hop-dong-khach-hang.md) — **ai chịu trách nhiệm phần nào** + vòng đời văn bản (soạn → góp ý → thẩm định → ban hành → rà soát)
- Quy trình tư vấn – chốt hợp đồng: [quy-trinh-tu-van.md](../../../03-van-hanh/kinh-doanh/quy-trinh-tu-van.md)

## Đầu mục dự kiến bổ sung

- Biên bản hoàn tất / bàn giao điều trị
