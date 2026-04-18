# Bảng giá & Khuyến mại

> ⚠️ **PLACEHOLDER — chưa có nội dung.** Anh Đức sẽ cung cấp/trao đổi bảng giá và chương trình khuyến mại sau. Thư mục này mới dựng khung để thống nhất cách quản lý.

## Nguyên tắc 3 tầng giá

| Tầng | Là gì | Tính chất | Ở đâu |
| ---- | ----- | --------- | ----- |
| **1. Hợp đồng** | Văn bản pháp lý ký với khách | Ổn định | `07-phap-ly-va-tuan-thu/hop-dong/` — **nhúng bảng giá niêm yết trực tiếp** (khỏi truy vết) |
| **2. Bảng giá niêm yết** | Bảng giá chuẩn có phiên bản + hiệu lực | Đổi vài lần/năm | [`niem-yet/`](./niem-yet/) — bản gốc dùng chung |
| **3. Khuyến mại** | Chương trình ưu đãi theo tháng/quý | Thay đổi liên tục | [`khuyen-mai/`](./khuyen-mai/) — lưu trữ theo kỳ |

## Quy ước

1. **Hợp đồng khách hàng ghi bảng giá niêm yết trực tiếp trong hợp đồng** (theo quyết định vận hành — để ký nhanh, không phải mở nhiều tài liệu). Khi bảng giá niêm yết thay đổi, cập nhật đồng thời bản gốc tại [`niem-yet/`](./niem-yet/) và bảng giá nhúng trong các hợp đồng liên quan.
2. **Giá ưu đãi/khuyến mại KHÔNG nhúng vào hợp đồng.** Hợp đồng chỉ ghi giá niêm yết; ưu đãi thực tế điền theo ca (mục "Chi phí ca điều trị") theo chương trình đang hiệu lực khi ký.
3. **Mỗi chương trình khuyến mại là 1 file có ngày hiệu lực** trong [`khuyen-mai/`](./khuyen-mai/), lưu lại kể cả khi hết hạn — làm **bằng chứng đối chiếu** khi khách khiếu nại về giá tại thời điểm ký.

## Cấu trúc

```
bang-gia/
├── README.md              ← file này
├── niem-yet/              ← bảng giá niêm yết chuẩn (versioned)
│   └── (implant · rang-su · chinh-nha · … — cung cấp sau)
└── khuyen-mai/            ← chương trình khuyến mại theo kỳ (archive)
    └── (2026-Q3 · … — cung cấp sau)
```

## Trạng thái

- 🔨 Khung placeholder — **chờ anh Đức cung cấp nội dung bảng giá & chương trình khuyến mại**.
