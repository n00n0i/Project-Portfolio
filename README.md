# 📋 Project Portfolio

> ตารางรวมโปรเจคที่กำลังพัฒนา หรือดำเนินงานอยู่

---

## 📊 Project List

| ลำดับ | ชื่อโปรเจค | GitHub URL | Status | คนทำ | หมายเหตุ |
|--------|-----------|------------|--------|--------|------------|
| 1 | **EGS (Experience Graph System)** | [n00n0i/egs](https://github.com/n00n0i/egs) | ✅ Done (Phase 1) | 🥑 กะเพรา | E2E 10/10 ผ่าน, รอ Phase 2: AI Auto-Generate + UXUI Polish |
| 2 | **ThaiDoc AI** | [n00n0i/thaidoc-ai](https://github.com/n00n0i/thaidoc-ai) | 🚀 In Progress | 🥑 กะทิ | OCR as a Service + Receipt Extractor |
| 3 | **ThaiTutor AI** | [n00n0i/thai-tutor-ai](https://github.com/n00n0i/thai-tutor-ai) | 🚀 Deployed ✅ | 🥑 กะทิ | Live: http://100.68.71.89:3782 · LLM: deepseek-v4-pro (Ollama Cloud) · Thai UI + Kanit font · พี่ติวเตอร์ไทย personality · ภาษาถิ่น: กลาง/อีสาน/ใต้ · Dogfood 17/17 tests ผ่าน · Context truncation fix |
| 4 | **ExamWise (คลังข้อสอบ)** | [n00n0i/examwise](https://github.com/n00n0i/examwise) | 🚀 In Progress | 🥑 กะเพรา | AI-powered Thai govt exam bank · LLM: gemma4:31b-cloud (Ollama Cloud) · PDF upload → AI extract + generate questions · Print-ready PDF export · Live: http://134.185.162.253:7103 |
| 5 | **LightRAG Gateway** | [n00n0i/lightrag-gateway](https://github.com/n00n0i/lightrag-gateway) | 🚀 Deployed ✅ | 🥑 กะเพรา | Multi-tenant FastAPI gateway + React Admin Dashboard · E2E tests: 9/9 passed · Bugs fixed: POST /admin/tenants Body params, created_at missing in response, Invalid Date display · Live: http://100.68.71.89:9507 |
| 6 | **h-engine** | [n00n0i/h-engine](https://github.com/n00n0i/h-engine) | 🚀 In Progress | 🥑 กะเพรา | Flow Studio runtime + Page Builder · FlowRuntime E2E tests WIP · Bug #3 (RSC prefetch blocking) ✅ Fixed · Bug #4 (Renderer `width` crash) 🐜 Pending |

---

## ✍️ วิธีอัพเดท

เมื่อมีโปรเจคใหม่ หรือต้องการอัพเดตสถานะ ให้ทำตามขั้นตอนนี้:

### 1. Clone repo นี้มาแก้

```bash
git clone https://github.com/n00n0i/egs-project.git
cd egs-project
```

### 2. แก้ไขไฟล์ README.md

เพิ่มแถวในตาราง หรือแก้ไข Status ให้ตรงกับปัจจุบัน:

| ลำดับ | ชื่อโปรเจค | GitHub URL | Status | คนทำ | หมายเหตุ |
|--------|-----------|------------|--------|--------|------------|
| 1 | EGS | [n00n0i/egs](https://github.com/n00n0i/egs) | ✅ Done (Phase 1) | 🥑 กะเพรา | E2E 10/10 ผ่าน, รอ Phase 2 |
| 2 | ชื่อโปรเจคใหม่ | [n00n0i/xxx](https://github.com/n00n0i/xxx) | 🚀 In Progress | ชื่อคนทำ | ระบุอะไรกำลังทำอยู่ |

**Status ที่ใช้:**
- `✅ Done` — เสร็จสมบูรณ์
- `🚀 In Progress` — กำลังพัฒนา
- `⏸️ On Hold` — พักไว้ก่อน
- `🐜 Bug` — มีปัญหาที่ต้องแก้

### 3. Commit และ Push กลับ

```bash
git add README.md
git commit -m "Update: เพิ่มโปรเจค xxx และอัพเดทสถานะ"
git push origin main
```

---

*Repo นี้อัพเดตล่าสุด: 2026-05-03*
