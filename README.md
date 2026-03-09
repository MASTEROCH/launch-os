# Launch OS

> Guided launch system for startups — from idea to first customers.

A full-featured SaaS platform built with **React**, **TypeScript**, **Tailwind CSS v4**, and **React Router**.

## Tech Stack

- **React 18** + TypeScript
- **Tailwind CSS v4** with custom theme tokens
- **React Router** (data mode, not react-router-dom)
- **Motion** (formerly Framer Motion) for animations
- **Recharts** for analytics charts
- **Sonner** for toast notifications
- **Radix UI** primitives for accessible components
- **jsPDF** for invoice PDF generation
- **canvas-confetti** for celebration effects
- **react-dnd** for drag-and-drop
- **Lucide React** for icons

## Features

### 5-Step Launch Pipeline
1. **Clarify** — Define your product, audience, and value proposition
2. **Package** — AI generates launch materials (one-liner, pitch, landing copy, FAQ, platform content)
3. **Route** — Find and connect distribution channels (490+)
4. **Launch** — Execute distribution across all channels
5. **Improve** — Analyze results and optimize

### Core Modules
- **Mission Control Dashboard** — Overview with draggable checklist, stats, charts
- **Project Wizard** — 5-step guided project creation with AI content generation
- **Package Builder** — Edit and manage AI-generated launch materials
- **Launch Engine** — Review and distribute content across channels
- **Launch Tracker** — Real-time distribution progress tracking
- **Analytics Dashboard** — Traffic, engagement, and platform performance
- **Token Marketplace** — Purchase tokens for distribution
- **Community Hub** — Leaderboard, network, rooms, badges, feed
- **Messages** — Direct messaging between founders
- **Settings** — Profile, notifications, billing with plan management
- **Referral Program** — Infinite-depth referral tree with token rewards

### Coming Soon (Locked)
- CRM
- Finance/Accounting
- Investor Hub
- Automations

### Design
- Apple Design inspired UI
- iOS-style mobile navigation with bottom tab bar + More sheet
- Liquid Glass effects (blur, saturation)
- Dark/Light theme with smooth transitions
- Pull-to-refresh with rubber band physics
- Swipe-back gesture navigation
- Command palette (Cmd+K)
- RU/EN localization

### Pricing Plans
- **Starter** — $19/mo
- **Growth** — $49/mo (most popular)
- **Viral** — $129/mo

Token packs: Boost Pack, Power Pack, Mega Pack

## Getting Started

```bash
pnpm install
pnpm dev
```

## Project Structure

```
src/
├── app/
│   ├── App.tsx              # Root with RouterProvider
│   ├── routes.ts            # React Router configuration
│   └── components/
│       ├── Layout.tsx        # Main layout with sidebar + mobile nav
│       ├── Dashboard.tsx     # Mission Control
│       ├── ProjectWizard.tsx # 5-step project creation
│       ├── PackageBuilder.tsx# AI content management
│       ├── LaunchEngine.tsx  # Content distribution
│       ├── LaunchTracker.tsx # Progress tracking
│       ├── Growth.tsx        # Channels + Referrals
│       ├── SettingsPage.tsx  # Account management
│       ├── i18n.tsx          # RU/EN translations
│       ├── user-progress.ts  # localStorage state management
│       └── ui/              # Radix-based UI primitives
└── styles/
    ├── theme.css            # Design tokens + light/dark themes
    ├── tailwind.css          # Tailwind v4 config
    ├── fonts.css             # Font imports
    └── index.css             # Style entry point
```

## License

All rights reserved. © 2026 Launch OS.
