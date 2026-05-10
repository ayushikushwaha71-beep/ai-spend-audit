# AI Spend Audit

AI Spend Audit is a modern financial optimization platform designed to help startups, founders, and engineering teams analyze their AI tooling expenses and uncover unnecessary spending across subscriptions, seats, and API usage.

The platform generates instant, actionable audits for tools like ChatGPT, Claude, Cursor, GitHub Copilot, Gemini, and more — helping teams identify downgrade opportunities, redundant plans, and lower-cost alternatives without sacrificing productivity.

Built as part of the Credex Web Development Internship Assignment, the project focuses not only on engineering quality but also on product thinking, business credibility, and real-world usability.


# Core Features

## AI Spend Audit Engine
- Analyze AI subscription and API costs
- Detect oversized or unnecessary plans
- Recommend lower-cost alternatives
- Calculate monthly and annual savings
- Explain recommendations with financial reasoning

## Personalized Audit Reports
- AI-generated audit summaries
- Human-readable recommendations
- Savings-focused breakdown cards
- Public shareable result URLs

## Lead Capture System
- Email-based report capture
- Optional company and role fields
- Backend storage integration
- Transactional confirmation emails

## User Experience
- No login required
- Persistent form state across reloads
- Mobile responsive design
- Fast and lightweight UI
- Open Graph preview support for shared reports

---

# Supported AI Platforms

- Cursor
- GitHub Copilot
- ChatGPT
- Claude
- Anthropic API
- OpenAI API
- Gemini
- Windsurf

---

# Tech Stack

## Frontend
- Next.js
- React
- TypeScript
- Tailwind CSS

## Backend
- Next.js API Routes
- Supabase

## AI Integration
- Anthropic API

## Infrastructure & Tooling
- GitHub Actions
- Vercel
- Resend
- ESLint

---

# Why This Product Exists

Most startups significantly underestimate how much they spend on AI tools every month.

Teams often:
- pay for unnecessary enterprise plans
- duplicate capabilities across multiple tools
- overpay for seats that go unused
- ignore cheaper alternatives
- lack visibility into optimization opportunities

AI Spend Audit was designed to solve that problem with transparent, explainable recommendations instead of vague AI-generated advice.

---

# Project Structure

```bash
src/
├── app/
├── components/
├── lib/
├── services/
├── data/
├── hooks/
├── types/

docs/
tests/
prompts/
public/
