# VietRAG 🇻🇳

**Nền tảng AI Chatbot cho Doanh Nghiệp Việt Nam**

Upload tài liệu → AI đọc hiểu → Chatbot trả lời theo dữ liệu riêng của bạn

---

## ✨ Tính năng

- 📄 **Upload tài liệu** — PDF, DOCX, TXT, hình ảnh
- 🤖 **AI Chatbot** — Trả lời dựa trên dữ liệu riêng
- 🔍 **Deep Document Understanding** — OCR, phân tích layout
- 🌐 **API Compatible** — Tương thích OpenAI API
- 🔒 **Self-hosted** — Data giữ riêng, không chia sẻ
- 🇻🇳 **Tiếng Việt** — UI tiếng Việt, tối ưu cho tiếng Việt

## 🚀 Bắt đầu nhanh

```bash
# Clone repo
git clone https://github.com/chaudl113/ragflow.git
cd ragflow

# Start services
cd docker
docker compose -f docker-compose-base.yml up -d

# Setup backend
cd ..
uv sync --python 3.13 --all-extras
source .venv/bin/activate
export PYTHONPATH=$(pwd)
bash docker/launch_backend_service.sh

# Setup frontend
cd web
npm install
npm run dev
```

## 💰 Bảng giá

| Gói | Giá | Tính năng |
|-----|-----|-----------|
| Free | 0đ | 100MB, 1000 queries/tháng |
| Starter | 199k/tháng | 1GB, 10k queries, 3 chatbots |
| Pro | 499k/tháng | 10GB, 100k queries, 10 chatbots |
| Enterprise | Liên hệ | Unlimited, custom, SLA |

## 🎯 Khách hàng mục tiêu

- SME VN cần customer support AI
- Công ty luật: tìm kiếm hợp đồng
- Phòng khám: tìm kiếm hồ sơ bệnh án
- E-commerce: tìm kiếm sản phẩm
- Giáo dục: chatbot tài liệu học tập

## 📄 License

Apache License 2.0

---

**Forked from [infiniflow/ragflow](https://github.com/infiniflow/ragflow)** — 81.5k⭐
