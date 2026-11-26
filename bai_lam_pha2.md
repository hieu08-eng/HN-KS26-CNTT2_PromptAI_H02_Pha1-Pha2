# BÀI LÀM PHA 2 – HACKATHON 02

- **Mã đề:** 06
- **Họ tên:** Đặng Đình Hiếu
- **Lớp:**HN-KS26-CNTT2
- **Link repository Pha2:**
- **Công cụ AI đã dùng (ChatGPT/Claude/Gemini):**

> Pha 2 (20 phút cuối). Mỗi mục: mở cuộc trò chuyện mới, gửi nguyên văn prompt đã viết trong bai_lam_pha1.md, dán câu trả lời và link chia sẻ vào đây. Xong, kéo thả file này vào repository Pha2.

## 4.2. Trích xuất tin nhắn đặt bàn ra JSON

**KET QUA AI**

```text
[
  {
    "ma_buffet": "NUONG",
    "ngay_dat": "2026-12-19",
    "nguoi_lon": 2,
    "tre_em": 1,
    "khu_vuc": "trong_nha",
    "ghi_chu": null
  },
  {
    "ma_buffet": "HAISAN",
    "ngay_dat": "2027-01-03",
    "nguoi_lon": 3,
    "tre_em": 0,
    "khu_vuc": null,
    "ghi_chu": "Một người dị ứng sữa"
  },
  {
    "ma_buffet": "LAU",
    "ngay_dat": "2026-12-25",
    "nguoi_lon": 4,
    "tre_em": 0,
    "khu_vuc": "san_vuon",
    "ghi_chu": "ông ngoại đi xe lăn"
  }
]

**Link trò chuyện:**https://share.gemini.google/BOnYZ5UUhUss

## 4.3. Báo giá bằng Chain-of-Thought

**KET QUA AI**
Đúng
```text
Bước 1: Tính tiền 10 người lớnGiá buffet nướng (NUONG): 399.000 đồng/người lớnPhép tính: $10 \times 399.000 = 3.990.000\text{ đồng}$Bước 2: Tính tiền trẻ em và cộng tổng tiền trẻ em3 trẻ em cao 1,1 m, 1,2 m và 1,35 m (nằm trong khoảng từ 1 m đến 1,4 m, tính 50% giá người lớn):Đơn giá 1 trẻ em: $399.000 \times 50\% = 199.500\text{ đồng}$Tiền 3 trẻ em: $3 \times 199.500 = 598.500\text{ đồng}$1 bé cao 0,8 m (dưới 1 m, miễn phí): $1 \times 0 = 0\text{ đồng}$Tổng tiền trẻ em: $598.500 + 0 = 598.500\text{ đồng}$Bước 3: Tính tổng tiền người lớn và trẻ emPhép tính: $3.990.000 + 598.500 = 4.588.500\text{ đồng}$Bước 4: Tính mức giảm giáĐoàn có 10 người lớn (đủ điều kiện từ 10 người lớn trở lên) nên được giảm 5% trên tổng tiền buffet:Mức giảm giá: $4.588.500 \times 5\% = 229.425\text{ đồng}$Tiền buffet sau giảm giá: $4.588.500 - 229.425 = 4.359.075\text{ đồng}$Bước 5: Tính mức phụ thu và cộng vàoPhụ thu 1 phòng riêng: $1 \times 500.000 = 500.000\text{ đồng}$Cộng phụ thu vào tiền buffet sau giảm giá: $4.359.075 + 500.000 = 4.859.075\text{ đồng}$Bước 6: Cộng tiền sau giảm giá và phụ thu để tính tổng tiềnPhép tính: $4.359.075 + 500.000 = 4.859.075\text{ đồng}$
```

**Link trò chuyện:**https://share.gemini.google/PzaqEyVt4EpY

### b) Kiểm tra kết quả AI

AI đúng

## 4.4. Dây chuyền xử lý khiếu nại – kết quả Trạm 1

**KET QUA AI**

```text
{"loai_su_co": "thieu_mon", "so_khach": 5, "so_mon_bi_thieu": 2, "tom_tat": "Khách ăn buffet 5 người phản ánh hết tôm hùm và cua suốt buổi tối dù đã chờ bổ sung."}
```

**Link trò chuyện:**https://share.gemini.google/5zmO5nfPE6HW

## 4.5. Prompt chấm bài theo Rubric

**KET QUA AI**

```text
(Dán câu trả lời của AI vào đây (bấm nút Copy dưới câu trả lời) – xoá dòng này)
```

**Link trò chuyện:**
