<div align="center">

# TEX — تكس

### Textile · Engineering · Techs

**The bilingual knowledge infrastructure for Textile Engineering.**  
Built by a textile engineer who codes. For the community.

[![License: MIT](https://img.shields.io/badge/License-MIT-teal.svg)](https://opensource.org/licenses/MIT)
[![Status: Active Development](https://img.shields.io/badge/Status-Active%20Development-gold.svg)]()
[![Language: Arabic + English](https://img.shields.io/badge/Language-Arabic%20%2B%20English-navy.svg)]()
[![Stack: Next.js](https://img.shields.io/badge/Stack-Next.js%2014-black.svg)](https://nextjs.org/)

</div>

---

## What Is TEX?

TEX is an open-source, bilingual (Arabic/English) knowledge platform built specifically for Egyptian textile engineering students, professors, and industry professionals.

It solves three problems that have never been solved:

| Problem | Reality | What TEX Does |
|--------|---------|---------------|
| **No quality Arabic resources** | Egyptian textile engineering students rely on low-quality, machine-translated PDFs. Quality textbooks (Merkel, Handbook of Technical Textiles) are English-only. | Curated, community-verified bilingual resource library with professor-approved content |
| **Poor technical writing** | Students submit disorganized reports because no structured tool exists. Professors waste time correcting format instead of substance. | AI-assisted technical report generator with textile-specific templates (yarn testing, fabric analysis, composite characterization) |
| **Fragmented community** | Only two universities in Egypt teach textile engineering (Alexandria, Mansoura). No shared platform exists between them or with industry. | Role-based community — professors, students, industry engineers — in one place |

TEX is **infrastructure, not content**. The community fills it. The platform holds it.

---

## Why Open Source?

The community TEX serves — Arabic-speaking engineering students in Egypt and the MENA region — has been underserved by every existing platform. ResearchGate is English-only. University LMS systems are siloed per institution. Generic Arabic forums have zero quality control.

Making TEX open source is a commitment: this knowledge infrastructure belongs to the community it serves. Not behind a paywall. Not controlled by an institution. Forkable. Extendable. Transparent.

The bilingual tooling being built here (RTL-native document editor, Arabic/English technical report generation, bilingual full-text search, textile engineering domain terminology engine) doesn't exist anywhere in open source. It gets built here, in the open, for anyone in the Arabic-language engineering education space to use or build on.

---

## Tech Stack

| Layer | Technology | Why |
|-------|-----------|-----|
| Framework | Next.js 14 (App Router) | SSR for SEO on resource pages; strong i18n support |
| Styling | Tailwind CSS + shadcn/ui | Rapid build; RTL-compatible utility classes |
| Database | PostgreSQL via Supabase | Full SQL; built-in auth; realtime for future features |
| Auth | Supabase Auth + custom RBAC | Role-based access control at server level |
| File Storage | Supabase Storage | Integrated with DB; handles PDFs and documents |
| AI | Anthropic Claude API | Report generator paragraph assist; no custom training |
| PDF Generation | React-PDF | Bilingual PDF output from report templates |
| Deployment | Vercel | Zero-config Next.js; scales with traffic |
| i18n | next-intl | `/ar` and `/en` routing; RTL/LTR at layout level |
| Search | Supabase pg_search → Algolia (Phase 2) | Start free; upgrade when complexity demands |

---

## Roadmap

**Intial Sprint (current focus):**
- Auth system + Supabase setup
- Resource library (upload + browse + search)
- Template for data materials

---

## The Name

**TEX** carries three simultaneous readings:

- **Textile** — the domain, the origin, the community it serves
- **Tex** — the international yarn count unit (g/1000m). A technical measurement only a textile engineer would recognize
- **Techs** — the technology layer, the digital future being built on top of the oldest craft

The old and the new. Neither makes sense without the other.

---

## About the Founder

Built by **Ziad Elnagar** — textile engineer (BSc, Alexandria University), frontend developer, music producer. Graduated from the same system TEX is trying to fix. Builds at the intersection of craft and code.

- GitHub: [@ZiadNagar](https://github.com/ZiadNagar)
- Dev.to: [dev.to/ziadelnagar](https://dev.to/ziadelnagar)

---

## License

MIT License — see [LICENSE](./LICENSE) for details.

Open source. For the community. By one of their own.

---

<div align="center">

**TEX — تكس**  
*Textile · Engineering · Techs*

</div>
