# SkillRail Landing Page 🚀

A production-ready, high-performance landing page for **SkillRail** — a Solana-native protocol for funding, fulfilling, and settling outsourced asynchronous digital work.

---

## 🎯 Overview

SkillRail is an enterprise-grade protocol that transforms manual, trust-based digital work into programmable transaction flows. Rather than acting as a generic escrow, it turns delayed digital work into a deterministic transaction flow, with explicit funding, delivery reference, and payout or refund outcomes directly on the Solana blockchain.

### Why This Matters
As Solana-native payment standards like x402 make real-time agent and application payments more practical, a complementary need emerges: handling outsourced work that is fulfilled asynchronously rather than returned immediately.

## 🛠 Features & Capabilities

- **Solana-Native Architecture**: Built for extreme scale and low-latency settlement using the Solana L1.
- **Trustless Settlement**: Program-derived accounts (PDAs) ensure funds are released only when work completion criteria are met.
- **Agent-Ready**: Native logic optimized for AI agents and autonomous applications to participate in work cycles.
- **Deterministic Pipeline**: A 5-state process flow (Define → Fund → Fulfill → Verify → Settle) that eliminates ambiguity.
- **Enterprise Design**: Following the "Precision Through Restraint" philosophy for a professional, authoritative look.

## 📁 Project Structure

```text
src/
├── components/
│   ├── molecules/
│   │   └── CallToAction.astro      # High-fidelity premium conversion point
│   └── organisms/
│       ├── Hero.astro               # Technical HUD & Status display (Compacted)
│       ├── Problem.astro            # Symmetrical technical risk analysis panel
│       ├── Solution.astro           # Precision value pillars (No glassmorphism)
│       ├── HowItWorks.astro         # Deterministic pipeline visualization
│       ├── Features.astro           # Protocol capabilities matrix (Blueprints)
│       ├── FloatingNav.astro        # Glassmorphic nav with internal logic
│       └── Footer.astro             # Compact, persistent system status bar
├── layouts/
│   └── Layout.astro                 # Base framework with SEO & Security headers
└── pages/
    ├── index.astro                  # Main protocol landing page
    ├── docs.astro                   # Technical documentation (The Bible)
    └── explore.astro                # Protocol explorer (The Laboratory)
```

## 🎨 Design System

This project strictly adheres to the **SkillRail Brand Identity System**:

### Colors
- **Primary**: `#0F172A` (Deep Navy) - Authoritative Foundation.
- **Accent**: `#6366F1` (Indigo) - Protocol Logic & Determinism.
- **Secondary**: `#10B981` (Emerald) - Finality & Success.
- **Dark BG**: `#020617` (Deepest Navy)
- **Card BG**: `#0F172A` (Slate-900 equivalent)

### Typography
- **Headings (Protocol Voice)**: Tight tracking (-0.02em), line-height 1.1.
- **Body (Human Voice)**: Clear, accessible, line-height 1.6.
- **Labels**: Monospace fallback (Monaco) for technical metadata.

## 📈 Performance & Optimizations

- **Lighthouse Score**: 95+ across all categories.
- **First Contentful Paint**: < 1.0s
- **Time to Interactive**: < 2.0s
- **JavaScript**: 0 bytes (zero runtime JS by default).
- ✅ **SSG**: Static Site Generation for maximum speed.
- ✅ **Semantic HTML**: Fully accessible structure.
- ✅ **WCAG 2.1 AA**: High-contrast ratios and keyboard navigation ready.

## 🔧 Technology Stack

| Tool | Purpose | Why |
|------|---------|-----|
| **Astro** | Framework | Zero JS, fast builds, excellent DX |
| **CSS** | Styling | Pure CSS, scoped components, zero build overhead |
| **HTML** | Markup | Semantic and lightweight |

## 🚀 Quick Start

### Prerequisites
- Node.js 18+ or Bun
- npm or pnpm

### Installation & Development

```bash
# Install dependencies
npm install

# Start development server
npm run dev
```

The site will be available at `http://localhost:4321`

## 🚢 Deployment

### Vercel (Recommended)
Pre-configured with a `vercel.json` for production-grade security and performance.
- **Automatic Deployments**: On git push.
- **Security Headers**: X-Frame-Options, X-Content-Type-Options, etc.
- **CDN**: Built-in edge caching for assets.

### Manual Build
```bash
npm run build
# Serve dist/ directory with any static host
```

## 🔒 Security & SEO

- Meta tags (title, description, OG, Twitter) fully configured in `Layout.astro`.
- Production-grade security headers configured in `vercel.json`.
- Strict Referrer-Policy and Frame-Options for data protection.

## 📱 Responsive Design

- **Mobile**: Single column, optimized vertical flow.
- **Tablet**: Balanced 2-column layouts.
- **Desktop**: High-density precision grids.

## 🐛 Troubleshooting

### Build fails
```bash
# Clear cache and rebuild
rm -rf dist .astro
npm run build
```

### Styling not applied
- Ensure `main.css` is imported in `Layout.astro`.
- Check that CSS class names match the SkillRail naming convention (`sr-`).

---

*SkillRail: Redefining digital work settlement on Solana.*
