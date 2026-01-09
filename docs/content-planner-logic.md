---
id: PROJECT-PLANNER-001
tech_stack: [FastAPI, Next.js, SQLite, Vertex AI]
agent_roles: [Architect, Researcher, Copywriter]
---

# LOGIC VẬN HÀNH AI CONTENT PLANNER

## 1. Cổng kết nối Tri thức (MCP Integration)
- [cite_start]**Chỉ thị:** Ứng dụng phải kết nối với máy chủ MCP để truy vấn thời gian thực từ kho `Spa-Context-Hub`[cite: 127, 211].
- [cite_start]**Nguồn chân lý:** Nếu thông tin trong dự án mâu thuẫn với `global-rules.md`, quy tắc toàn cầu được ưu tiên tuyệt đối[cite: 105].

## 2. Quy trình Lập kế hoạch (Core Logic)
1. **Input:** Người dùng nhập mục tiêu tháng (Ví dụ: "Tăng doanh số trị mụn").
2. [cite_start]**Analysis:** Agent Researcher truy cập `marketing-domain.md` để lấy danh sách các dịch vụ trị mụn và máy móc tương ứng[cite: 396].
3. [cite_start]**Execution:** Agent Copywriter sinh 30 tiêu đề bài viết dựa trên phong cách đã định nghĩa ở `global-rules.md` [cite: 681-684].

## 3. Hệ thống Rào cản (Guardrails)
- [cite_start]**Logic:** "Bánh mì kẹp" (Sandwich Architecture) [cite: 478-486].
  - [cite_start]**Lớp trên:** Kiểm tra từ khóa bị cấm (Tránh ảo giác y khoa) [cite: 480-481].
  - [cite_start]**Lớp dưới:** Kiểm tra định dạng (Đảm bảo xuất ra đúng lịch JSON/Calendar) [cite: 486-489].
