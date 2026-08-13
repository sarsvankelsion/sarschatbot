# 🤖 sarschatbot — Discord AI Chatbot

Chatbot AI đa năng, build trên **Next.js 16** + **AI SDK** + **Discord** — chat thông minh với streaming, lịch sử hội thoại và lưu trữ dữ liệu.

## ✨ Tính năng

- 💬 Chat AI streaming realtime (AI SDK 6, Next.js App Router)
- 🧠 Hỗ trợ nhiều model providers (xAI, OpenAI, Anthropic, AI Gateway...)
- 🔐 Xác thực Auth.js (next-auth)
- 💾 Lưu lịch sử chat với PostgreSQL (Neon) + Drizzle ORM
- 📦 File storage qua Vercel Blob
- 🗄️ Redis cache
- 🎨 UI shadcn/ui + Tailwind CSS 4 + Radix UI
- 🧪 Test với Playwright

## 🚀 Chạy local

```bash
pnpm install
pnpm db:migrate
pnpm dev
```

Yêu cầu các biến môi trường trong `.env.example` (`AUTH_SECRET`, `AI_GATEWAY_API_KEY`, `BLOB_READ_WRITE_TOKEN`, `POSTGRES_URL`, `REDIS_URL`).

## 🧰 Tech stack

| | |
|---|---|
| **Framework** | Next.js 16 (App Router, RSC, Server Actions) |
| **AI** | AI SDK 6, Vercel AI Gateway |
| **DB** | PostgreSQL + Drizzle ORM |
| **UI** | shadcn/ui, Tailwind 4, Radix, framer-motion |
| **Cache** | Redis |
| **Auth** | Auth.js v5 |
| **Test** | Playwright |

## 📄 License

MIT