# 🧠 G0DM0D3 - AI Chat & Research Interface

> **Advanced AI chat interface, prompt engineering suite, and research platform supporting multi-model LLM inference, dataset inspection, and Docker deployment.**

---

## ✨ Key Features

- ⚡ **Next.js 14 & React 18 Architecture**
  - High-performance web application powered by Next.js App Router, Tailwind CSS, Framer Motion, and Zustand state management.

- 🤖 **Multi-Provider LLM Integration**
  - Connects seamlessly to OpenAI API, HuggingFace Inference APIs, and custom REST gateways (`api/server.ts`).

- 📑 **Integrated Research & Paper Viewer**
  - Built-in Markdown renderer with syntax highlighting for inspecting AI research papers (`PAPER.md`) and benchmark datasets.

- 🐳 **Docker & Nginx Production Ready**
  - Multi-stage `Dockerfile`, `docker-compose.yml`, and optimized Nginx configuration for containerized deployment.

---

## 🛠️ Tech Stack

- **Framework**: Next.js 14, React 18, TypeScript 5
- **Styling**: Tailwind CSS, Framer Motion, Lucide Icons
- **State Management**: Zustand
- **Backend API**: Express.js (`tsx`), OpenAI SDK
- **Containerization**: Docker, Docker Compose, Nginx

---

## 🚀 Getting Started

### Prerequisites
- Node.js 18+ and `npm`
- (Optional) Docker & Docker Compose

### 1. Local Development
```bash
git clone https://github.com/Omkar4812x/AI-Models-GODMODE.git
cd AI-Models-GODMODE
npm install
npm run dev
```
Open `http://localhost:3000` in your browser.

### 2. Docker Deployment
```bash
docker-compose up --build -d
```

---

## 📄 License

Distributed under the AGPL-3.0 License.
