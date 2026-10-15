# DealPilot AI 🤝

**Negotiate Smarter. Deal Better. Close with Confidence.**

DealPilot AI is an AI-powered negotiation platform that helps people negotiate deals through real-time communication, structured offers, counteroffers, and AI-generated compromise suggestions.

The platform aims to make negotiations more transparent, collaborative, and efficient by helping both parties explore mutually beneficial agreements.

## ✨ Key Features

- **Negotiation Rooms:** Create or join rooms to negotiate with another party.
- **Offers and Counteroffers:** Submit, review, and respond to proposed deals.
- **AI-Powered Suggestions:** Get AI-generated compromise recommendations to help move negotiations forward.
- **Real-Time Communication:** Support live audio communication through Agora.
- **Negotiation History:** Track offers, counteroffers, and previous negotiation activity.
- **Flexible Deal Terms:** Discuss pricing, payment conditions, delivery timelines, and other deal requirements.
- **Mutual Agreement:** Finalize an agreement only after both parties approve the proposed terms.
- **Responsive Interface:** Access the platform across desktop and mobile screen sizes.

## 🛠️ Tech Stack

| Component | Technology |
|---|---|
| Frontend | React, Vite |
| Backend | Node.js, Express |
| Database | PostgreSQL |
| Database Platform | Supabase |
| AI Integration | Google Gemini API |
| Real-Time Audio | Agora RTC |
| Version Control | Git and GitHub |

## 🏗️ Architecture

DealPilot AI uses a client-server architecture.

1. **Frontend:** React provides the user interface for negotiation rooms, offers, and agreements.
2. **Backend:** Express handles API requests, business logic, and negotiation workflows.
3. **Database:** PostgreSQL stores application data, including negotiation details and offer history.
4. **AI Service:** Google Gemini generates contextual negotiation and compromise suggestions.
5. **Audio Communication:** Agora RTC supports real-time voice communication.

Sensitive credentials are configured through environment variables and must remain on the server or in the appropriate secure configuration.

## 📁 Project Structure

```text
dealpilot-ai/
├── client/              # React + Vite frontend
├── server/              # Node.js + Express backend
├── README.md
└── .gitignore
```

The exact files and folders may vary as development progresses.

## 🚀 Getting Started

### Prerequisites

Install the following:

- Node.js and npm
- Git
- A Supabase project with PostgreSQL
- A Google Gemini API key
- Agora credentials for real-time audio features

### 1. Clone the repository

```bash
git clone https://github.com/rohanmshet003-rora/DealPilot-AI.git
cd DealPilot-AI
```

### 2. Configure the backend

Navigate to the server directory:

```bash
cd server
npm install
```

Create a `.env` file in the server directory and configure the environment variables required by your implementation.

Example placeholders:

```env
PORT=5000
DATABASE_URL=your_postgresql_connection_string
GEMINI_API_KEY=your_gemini_api_key
AGORA_APP_ID=your_agora_app_id
AGORA_APP_CERTIFICATE=your_agora_app_certificate
JWT_SECRET=your_long_random_secret
```

Replace the placeholders with your own credentials locally. Never commit the real values to GitHub.

Start the backend using the start command configured in `server/package.json`. For example:

```bash
npm run dev
```

### 3. Configure the frontend

Open another terminal:

```bash
cd client
npm install
npm run dev
```

Open the local URL printed by Vite in your terminal.

**Note:** The exact commands and environment variable names should match the current project configuration. Check the relevant `package.json` files before running the application.

## 🔐 Security

- Keep API keys, database credentials, and authentication secrets out of source code.
- Store private configuration in environment files that are excluded from Git.
- Never commit `.env` files or production credentials.
- Validate and authorize requests on the backend.
- Protect negotiation rooms and agreement operations from unauthorized access.
- Rotate any credentials that have been accidentally exposed.

## 🗺️ Future Enhancements

- AI-assisted negotiation strategies tailored to deal objectives.
- Improved agreement summaries and term comparisons.
- Additional negotiation analytics and insights.
- Enhanced authentication and role-based permissions.
- Deployment with production monitoring and automated testing.

## 🎯 Project Goal

DealPilot AI aims to bridge the gap between traditional negotiation and intelligent digital collaboration by helping parties communicate clearly, explore fair compromises, and reach mutually approved agreements.

---

**DealPilot AI — Negotiate Smarter. Deal Better. Close with Confidence.**