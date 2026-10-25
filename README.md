# Lê Quốc Nghĩa (Lucas)

> Dùng nhiều AI không đồng nghĩa có hệ thống AI. Prompt đổi theo từng model; bối cảnh (Context) và quy trình (Workflow) mới là tài sản giữ lại lâu dài.

Tôi xây dựng **[OPCAIOS](https://opcaios.org)** tại Hà Nội.

Tôi không xuất thân từ trường lớp công nghệ. Mọi thứ trên GitHub này bắt đầu từ việc tự giải quyết những đầu việc lặp đi lặp lại mỗi ngày của chính mình: tự học, dựng thử, làm hỏng rồi sửa lại cho tới khi chạy ổn.

Hiện toàn bộ công việc của tôi vận hành trên hệ thống tự dựng: quy trình tự động bằng `n8n`, kho tri thức Markdown trên `Obsidian` đồng bộ với `PostgreSQL / pgvector`, và các AI Agent chạy phối hợp liên máy qua `MCP` cùng git worktree song song. Từ trang chủ [opcaios.org](https://opcaios.org), nền tảng học tập [khoahoc.opcaios.org](https://khoahoc.opcaios.org), hệ thống quản lý công việc cho đến luồng xuất bản nội dung đều do tôi trực tiếp viết và vận hành hằng ngày.

### Những thứ tôi đang xây và dùng thật

- **OPCAIOS (Business OS cho người làm một mình & đội nhỏ 1–5 người):** Gom bốn mảng công việc rời rạc (Mục tiêu, Nội dung & CRM, Bàn giao dự án, Tự động hóa) vào một vòng lặp vận hành thống nhất, luôn có bước duyệt của con người trước khi xuất bản.
- **Hạ tầng Đa Agent & Bộ nhớ 3 tầng:** Điều phối nhiều coding/ops agent chạy song song trên các máy chuyên biệt qua mạng riêng `Tailscale`, kết hợp bộ nhớ phiên làm việc, tìm kiếm ngữ nghĩa `pgvector` và kho tài liệu gốc `.md`.
- **Công cụ sản xuất & bản địa hóa nội dung:** Trình dựng video tự động trên nền web/desktop, tiện ích lồng tiếng Việt thời gian thực trên trình duyệt (`FastAPI`, `FFmpeg`, `TTS`), và quy trình biến ghi chép chuyên môn thành nội dung đa kênh có theo dõi phản hồi khách hàng.

### Kho mã nguồn công khai tiêu biểu

| Repository | Mô tả |
| :--- | :--- |
| **[second-brain-os](https://github.com/lucas10xai/second-brain-os)** | Kho tri thức Markdown bản tiếng Việt do AI Agent hỗ trợ duy trì, kèm 5 sổ tay thực hành và bộ Skills/Commands. |
| **[course-landing-themes](https://github.com/lucas10xai/course-landing-themes)** | Agent Skill thiết kế trang giới thiệu khóa học và sách với bản sắc thị giác riêng, nội dung trung thực và kiểm thử trước khi lên trang. |
| **[social-media-skills](https://github.com/lucas10xai/social-media-skills)** | Bộ kỹ năng (Skills) chuẩn hóa quy trình biên tập và phân phối nội dung mạng xã hội cho AI Agent. |
| **[n8n-template](https://github.com/lucas10xai/n8n-template)** | Bộ mẫu workflow `n8n` tự động hóa SEO, biên tập và phân phối nội dung. |

### Công cụ quen thuộc

- **Ngôn ngữ & Web:** `TypeScript` · `Next.js` · `Node.js` · `Python` · `FastAPI` · `Tailwind CSS`
- **Dữ liệu & Hạ tầng:** `PostgreSQL` · `pgvector` · `Supabase` · `Docker` · `Nginx` · `Cloudflare` · `Tailscale`
- **AI & Tự động hóa:** `Claude Code` · `MCP` · `n8n` · `Obsidian` · `Git Worktrees` · `FFmpeg`

### Nguyên tắc làm việc

1. **Chỉ chia sẻ cái đã chạy thật:** Cái gì đã dùng ổn trong công việc của mình thì mới đem ra hướng dẫn hoặc bàn giao; chưa thử thì nói rõ là chưa thử.
2. **Tự động hóa có kiểm soát:** Việc lặp lại có quy tắc rõ ràng thì giao cho code và `n8n`; AI phụ trách phần nháp và tổng hợp; quyết định cuối cùng luôn thuộc về con người.
3. **Đủ gọn để tự vận hành:** Hệ thống bàn giao cho doanh nghiệp nhỏ phải để người không chuyên kỹ thuật vẫn tự chạy được mà không phụ thuộc lâu dài vào người dựng.

### Kết nối

- **Website:** [opcaios.org](https://opcaios.org) · [Giới thiệu chi tiết](https://opcaios.org/about) · [Blog thực chiến](https://opcaios.org/blog)
- **Học liệu:** [khoahoc.opcaios.org](https://khoahoc.opcaios.org)
- **Mạng xã hội:** [Facebook (@nghiaos)](https://www.facebook.com/nghiaos) · [X (@nghia_lucas)](https://x.com/nghia_lucas)
- **Email:** [contact@opcaios.org](mailto:contact@opcaios.org)

---

## English Summary

> Using ten AI tools is not the same as running an AI system. Prompts expire with every model release; structured context and workflows compound over time.

I'm **Le Quoc Nghia (Lucas)**, a self-taught builder in Hanoi behind **[OPCAIOS](https://opcaios.org/en/about)**.

I didn't study computer science at school. Everything here grew out of automating repetitive work in my own day-to-day operations: trying tools at night, breaking things, and rebuilding them until they stayed up reliably.

Today my daily work runs on systems I built and maintain myself: deterministic `n8n` workflows, a structured `Obsidian` + `PostgreSQL / pgvector` knowledge base, and multi-machine AI agents coordinated through `MCP` and isolated git worktrees. I build practical AI automation and operating systems for solo operators and small teams (1–5 people). Every tool and workflow I share or hand over runs in my own daily operations first, with no made-up numbers or inflated promises.

**Links:** [opcaios.org](https://opcaios.org) · [About (EN)](https://opcaios.org/en/about) · [Courses](https://khoahoc.opcaios.org) · [Facebook](https://www.facebook.com/nghiaos) · [X (@nghia_lucas)](https://x.com/nghia_lucas) · [contact@opcaios.org](mailto:contact@opcaios.org)
