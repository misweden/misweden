# Hi, I'm Mustafa 👋

Co-founder of **[JobbEliten](https://www.jobbeliten.se)**, a Swedish job-search service that finds matching jobs, writes a personal cover letter for each one and applies on the user's behalf.

## What I build

**JobbEliten**: Next.js · TypeScript · Supabase (Postgres) · Gemini/LLMs · Playwright · Vercel · GitHub Actions

- **LLM pipeline:** matching between CVs and 50 000+ job ads, personal cover letters in the ad's language, and answers to free-text application questions. Includes per-call timeouts, model fallbacks and graceful degradation when the model fails.
- **Form robot:** a Playwright robot and Chrome extension that fill in and submit application forms on Teamtailor, Varbi, ReachMee, Ponty and more. It handles multi-step forms, file uploads, dropdowns and multi-select questions, and has safety checks: no captcha bypassing, no double submissions and quiet hours at night.
- **Automation:** nightly job ingest, scheduled matching and sending (Vercel Cron and GitHub Actions), a mail queue and an alarm when scheduled jobs stall.
- **Product and integrations:** Gmail sending (Google OAuth, verified for `gmail.send`), paid plans with Stripe, waitlist and invite flow, admin panel, and privacy and terms pages written for GDPR.

**Numbers so far:** 80+ users, 500+ applications sent automatically, 1 200+ automated tests.

## Tools

TypeScript · React / Next.js · Node.js · PostgreSQL / Supabase · Playwright · LLM APIs (Gemini, Claude) · Stripe · Vercel · GitHub Actions · AI-assisted development (Claude Code)

## Contact

📍 Stockholm · 🌐 [jobbeliten.se](https://www.jobbeliten.se)
