# 🤖 AI × Sáng Tạo Nội Dung Số

> **Bài tập:** Sử dụng công cụ AI tạo sinh hỗ trợ quá trình sáng tạo nội dung số  
> **Sinh viên:** Nguyễn Tuấn Thành — MSSV: 25112107  
> **Ngày nộp:** 22/04/2026

## 📋 Mô tả dự án

Dự án tạo ra một **trang web infographic tương tác** kết hợp báo cáo chi tiết về chủ đề **"Trí tuệ nhân tạo trong sáng tạo nội dung số"**. Toàn bộ nội dung (infographic + báo cáo 4-5 trang) được gộp trong **một trang duy nhất**, deploy lên GitHub Pages.

## 🛠️ Công cụ AI đã sử dụng

| # | Công cụ | Loại | Vai trò |
|---|---------|------|---------|
| 1 | **Google Gemini** | AI tạo văn bản | Tạo nội dung xu hướng AI, phân tích ưu/nhược điểm, nội dung đạo đức |
| 2 | **AI Image Generator (Imagen)** | AI tạo hình ảnh | Tạo 5 hình minh họa: banner, so sánh, workflow, đạo đức, mockup |
| 3 | **Claude AI (Antigravity)** | AI hỗ trợ thiết kế | Tạo code HTML/CSS/JS, bố cục responsive, animations |

## 📊 Tỷ lệ đóng góp

- **Con người: ~55%** — Ý tưởng, chỉnh sửa nội dung, tùy chỉnh thiết kế, viết báo cáo, tích hợp
- **AI: ~45%** — Tạo nội dung nền tảng, hình ảnh, code ban đầu

## 📁 Cấu trúc thư mục

```
gen-ai-workflow-assignment/
├── index.html          # Trang chính (infographic + báo cáo gộp)
├── styles.css          # Stylesheet (editorial magazine style)
├── script.js           # JavaScript (nav, animations, lightbox)
├── images/             # Hình ảnh do AI tạo
│   ├── ai_hero_banner.png
│   ├── ai_tools_comparison.png
│   ├── ai_workflow_process.png
│   ├── ai_ethics_balance.png
│   └── ai_text_generation.png
└── README.md           # File này
```

## 🌐 Demo

🔗 **GitHub Pages:** [Xem trang web](https://thanhnguyn.github.io/gen-ai-workflow-assignment/)

> ⚠️ Thay link trên bằng link GitHub Pages thực tế của bạn

## 🚀 Chạy local

Chỉ cần mở file `index.html` trong trình duyệt, hoặc dùng Live Server:

```bash
# Nếu có VS Code + Live Server extension
# Click chuột phải index.html → Open with Live Server

# Hoặc dùng Python
python -m http.server 8000
```

## 📝 Nội dung báo cáo (tóm tắt)

1. **Giới thiệu dự án** — Mục tiêu, chủ đề, hình thức sản phẩm
2. **Chi tiết 3 công cụ AI** — Prompt đã sử dụng, kết quả, cách chỉnh sửa
3. **Quy trình sáng tạo** — 5 bước kết hợp AI và sáng tạo cá nhân
4. **So sánh công cụ** — Bảng so sánh 6 tiêu chí, phân tích ưu/nhược điểm từng công cụ
5. **Đạo đức AI** — Bản quyền, minh bạch, kỹ năng, công bằng tiếp cận
6. **Kết luận** — Vai trò AI, cách thay đổi quy trình, bài học rút ra

## ⚙️ Công nghệ sử dụng

- HTML5 / CSS3 / Vanilla JavaScript
- Google Fonts (Outfit, JetBrains Mono)
- Responsive Design (Mobile-first)
- CSS Animations & Scroll Reveal
- Thiết kế: Editorial Magazine + Bento Grid + Mesh Gradient + Grain Texture

## 📄 License

Dự án này được tạo cho mục đích học tập. Nội dung và hình ảnh được tạo với sự hỗ trợ của AI tạo sinh.
