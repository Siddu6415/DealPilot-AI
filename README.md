# DealPilot AI

> **Negotiate Smarter. Deal Better. Close with Confidence.**

DealPilot AI is an enterprise-grade, full-stack AI-powered commercial negotiation platform designed for buyers and sellers to negotiate valuations, exchange multi-attribute structured offers, discover mutually beneficial non-monetary compromises, and execute certified bilateral agreements.

---

## Project Structure

This repository contains the full application in `dealpilot-ai/`:

- `dealpilot-ai/client/`: React 19, Vite, JavaScript, React Router v7, Agora RTC Web SDK NG, Lucide React, and Custom Glassmorphic Design System.
- `dealpilot-ai/server/`: Node.js, Express.js, Socket.io, Agora RTC Token Builder, Google Gemini AI SDK (`@google/genai`), and PostgreSQL database with persistent fallback.
- `dealpilot-ai/README.md`: Complete documentation, API endpoints, testing, and deployment guide.

---

## Quick Start

```bash
# Start backend server (Port 5001)
cd dealpilot-ai/server
npm install
npm run dev

# Start frontend client (Port 5173)
cd dealpilot-ai/client
npm install
npm run dev
```

For full setup, architecture details, and test instructions, see [dealpilot-ai/README.md](file:///Users/manjunath/DealPilot%20AI/dealpilot-ai/README.md).
