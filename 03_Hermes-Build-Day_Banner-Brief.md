# Banner brief — Hermes Agent Build Day 2026 (bản ít chữ)

## Spec
- **1080 × 1080 px** (1:1), xuất thêm bản 2160 × 2160 cho Luma. PNG/JPG, dưới 5 MB.
- Lề an toàn **80 px** mỗi cạnh, vì Luma bo góc ảnh cover.
- Phong cách: tối giản, nhiều khoảng trống, tối đa 2 màu cộng 1 màu nhấn.
- Mọi thành phần căn giữa theo trục dọc, trừ footer của bản Social post.
- Làm 2 phiên bản dùng chung phần trên: **Luma cover** và **Social post**.

## Bản 1 — Luma cover

```
┌──────────────────────────────────────────────┐
│                                              │
│             [Logo Vibe AI Labs]              │  ① Logo Vibe AI Labs, căn giữa
│                                              │
│              ┌────────────────┐              │
│              │                │              │
│              │  LOGO HERMES   │              │  ② Logo Hermes, khoảng 40% chiều rộng
│              │  (Nous Girl)   │              │
│              │                │              │
│              └────────────────┘              │
│                                              │
│        HERMES AGENT BUILD DAY 2026           │  ③ Tiêu đề 1 dòng, lớn nhất
│                                              │
│        $3K CASH + $5K OPENAI CREDITS         │  ④ Giải thưởng, màu nhấn
│                                              │
│      SAT 31.10 · 09:00–17:00 · HCMC          │  ⑤ Ngày · giờ · nơi
│                                              │
└──────────────────────────────────────────────┘
```

## Bản 2 — Social post (Facebook / X)

```
┌──────────────────────────────────────────────┐
│                                              │
│             [Logo Vibe AI Labs]              │  ①
│                                              │
│              ┌────────────────┐              │
│              │                │              │
│              │  LOGO HERMES   │              │  ②
│              │  (Nous Girl)   │              │
│              │                │              │
│              └────────────────┘              │
│                                              │
│        HERMES AGENT BUILD DAY 2026           │  ③
│                                              │
│        $3K CASH + $5K OPENAI CREDITS         │  ④
│                                              │
│      SAT 31.10 · 09:00–17:00 · HCMC          │  ⑤
│                                              │
│──────────────────────────────────────────────│
│  APPLY BY 28.10                     ┌─────┐  │  ⑥ Hạn đăng ký (căn trái)
│  Free · Register on Luma            │ QR  │  │  ⑦ CTA + QR tới Luma (căn phải)
│                                     └─────┘  │
└──────────────────────────────────────────────┘
```

## Toàn bộ chữ trên banner
| # | Text | Luma cover | Social post |
|---|---|---|---|
| ① | Logo Vibe AI Labs | ✓ | ✓ |
| ② | Logo Hermes | ✓ | ✓ |
| ③ | `HERMES AGENT BUILD DAY 2026` | ✓ | ✓ |
| ④ | `$3K CASH + $5K OPENAI CREDITS` | ✓ | ✓ |
| ⑤ | `SAT 31.10 · 09:00–17:00 · HCMC` | ✓ | ✓ |
| ⑥ | `APPLY BY 28.10` | | ✓ |
| ⑦ | `Free · Register on Luma` + QR code tới {LUMA_LINK} | | ✓ |

- QR tối thiểu **160 × 160 px**, đặt trên nền sáng, có viền trắng. Quét thử trước khi xuất file.

## Logo Hermes
- Logo chính thức là hình minh hoạ **"Nous Girl"**, đen trắng. File gốc đã tải về `assets/hermes-logo/`, lấy từ repo chính thức github.com/NousResearch/hermes-agent (thư mục `assets/`):
  - `nous-girl-black.svg`: logo đen, nền trong suốt, dùng trên nền sáng
  - `nous-girl-white.svg`: logo trắng, nền trong suốt, dùng trên nền tối
  - `icon-master.svg` / `icon-master-dark.svg`: bản icon app dạng squircle
- Dùng nguyên bản: không đổi màu, không cắt, không méo tỷ lệ, không ghép thêm chi tiết.
- Logo Vibe AI Labs ① nhỏ hơn logo Hermes ② để thể hiện đúng vai trò đơn vị tổ chức.
- **Không** đặt hai logo cạnh nhau kiểu `Vibe AI Labs × Hermes`, vì cách đặt đó ngầm hiểu là đối tác chính thức.

## Không dùng
- Logo Nous Research, logo OpenAI.
- Địa chỉ venue.
