# Social Flow AI

An AI-powered social media management platform for creating, scheduling, and analyzing content across multiple platforms.

## Overview

Social Flow AI helps you streamline your social media workflow by combining AI content generation, a visual post calendar, media management, and business analytics in one place.

## Features

- **AI Content Generator** — Generate post copy and branded images using AI
- **Post Scheduler & Calendar** — Plan and schedule content across social platforms
- **Media Library** — Manage and edit your media assets and templates
- **Business Analysis** — Analyze website content and extract brand insights
- **Multi-Platform Support** — Connect and post to Meta (Facebook/Instagram) and TikTok
- **Knowledge Base** — Store brand guidelines and content topics for consistent output
- **Referrals** — Built-in referral tracking system
- **Settings & Account Management** — Manage connected social accounts

## Tech Stack

- **Frontend:** React 18, Vite, Tailwind CSS, shadcn/ui
- **State Management:** TanStack Query (React Query)
- **Routing:** React Router DOM
- **Backend / Platform:** [Base44](https://base44.com)
- **AI Integrations:** OpenAI (image generation, content), ChatGPT
- **Social APIs:** Meta Graph API, TikTok API

## Prerequisites

- Node.js 18+
- npm or yarn
- A [Base44](https://base44.com) account

## Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/social-flow-ai.git
   cd social-flow-ai
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up environment variables**

   Create a `.env.local` file in the root directory:
   ```env
   VITE_BASE44_APP_ID=your_app_id
   VITE_BASE44_APP_BASE_URL=your_backend_url
   ```

4. **Run the development server**
   ```bash
   npm run dev
   ```

   The app will be available at `http://localhost:5173`.

## Project Structure

```
social-flow-ai/
├── src/
│   ├── api/              # API client setup
│   ├── components/       # Reusable UI components
│   │   ├── analysis/
│   │   ├── calendar/
│   │   ├── create/
│   │   ├── dashboard/
│   │   ├── media/
│   │   ├── settings/
│   │   └── ui/           # shadcn/ui base components
│   ├── hooks/            # Custom React hooks
│   ├── lib/              # Auth, utilities, routing
│   ├── pages/            # Page-level components
│   └── utils/
├── base44/
│   ├── entities/         # Data models
│   └── functions/        # Backend serverless functions
├── index.html
├── vite.config.js
└── tailwind.config.js
```

## Deployment

Open [Base44.com](https://base44.com), connect your repository, and click **Publish**. Any changes pushed to the main branch will be reflected in the Base44 Builder.

For more details, see the [Base44 GitHub integration docs](https://docs.base44.com/Integrations/Using-GitHub).

## Contributing

Contributions and suggestions are welcome! See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.
