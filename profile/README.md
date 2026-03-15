<!-- BICKOSA GitHub Organisation Profile README -->
<!-- Place this file at: .github/profile/README.md in your GitHub org -->

<div align="center">

<img src="https://avatars.githubusercontent.com/u/266512814?s=200&v=4" alt="BICKOSA — Bishop Cipriano Kihangire Old Students' Association" width="10%" />

<!-- If the banner image isn't uploaded yet, the heading below acts as the fallback -->

# BICKOSA

### Bishop Cipriano Kihangire Old Students' Association

**Per Aspera Ad Astra** — *Through Hardships to the Stars*

[![Alumni](https://img.shields.io/badge/Alumni-3%2C847%20Members-0d1b3e?style=flat-square&labelColor=0d1b3e&color=c9a84c)](https://bickosa.com)
[![Chapters](https://img.shields.io/badge/Chapters-12%20Worldwide-0d1b3e?style=flat-square&labelColor=0d1b3e&color=c9a84c)](https://bickosa.com/governance/chapters)
[![School](https://img.shields.io/badge/School-BCK%20SSS%20Luzira%2C%20Kampala-0d1b3e?style=flat-square&labelColor=152347&color=254c97)](https://bickosa.com/about)
[![License](https://img.shields.io/badge/License-MIT-0d1b3e?style=flat-square&labelColor=152347&color=254c97)](LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-0d1b3e?style=flat-square&labelColor=1a6b3c&color=dcf0e6)](CONTRIBUTING.md)

</div>

---

## Who We Are

**BICKOSA** is the official alumni association of **Bishop Cipriano Kihangire Senior Secondary School** — a private Catholic school in Luzira, Kampala, Uganda, founded in 1999 in memory of Bishop Cipriano Biyehima Kihangire.

We are old students scattered across Uganda and the world — engineers, doctors, lawyers, teachers, entrepreneurs, artists — bound by a shared foundation and a common motto. This GitHub organisation is our open-source effort to build the digital infrastructure that keeps our community connected, empowers the school we came from, and gives every old student a way to contribute.

> *"The bond of BCK is one that neither time nor distance can diminish."*

---

## What We're Building

Our digital ecosystem consists of several interconnected products. All of them are **open source** — any BICKOSA member, and any developer who believes in the mission, is welcome to contribute.

| Repository | Description | Status |
|---|---|---|
| [`bickosa-portal`](https://github.com/BICKOSA/bickosa-portal) | The core alumni portal — directory, events, donations, mentorship, careers | 🚧 In Development |
| [`bickosa-league`](https://github.com/BICKOSA/bickosa-league) | Standalone BICKOSA Sports League app — fixtures, standings, scorers, results | 🗓 Planned |
| [`bickosa-website`](https://github.com/BICKOSA/bickosa-website) | Public-facing marketing website for the association | ✅ Active |
| [`bickosa-design`](https://github.com/BICKOSA/bickosa-design) | Brand identity, design tokens, and component library | 🗓 Planned |
| [`bickosa-docs`](https://github.com/BICKOSA/bickosa-docs) | Association documents, governance records, and public archive | 🗓 Planned |
| [`.github`](https://github.com/BICKOSA/.github) | Org profile, issue templates, contribution guidelines | ✅ Active |

---

## The Alumni Portal

The flagship project. A full-stack web application that serves as the digital home for every BCK old student.

**Core features:**

- 🪪 **Verified Member Directory** — find classmates, mentors, and fellow alumni worldwide
- 📅 **Events & RSVPs** — galas, reunions, career fairs, sports days, AGMs
- 💛 **Fundraising Campaigns** — donate to school projects with full transparency and receipts
- 🌟 **Mentorship Programme** — old students guiding students and fellow alumni
- 💼 **Careers Board** — jobs, internships, and an alumni business directory
- 🏛 **Governance Hub** — leadership, constitution, annual reports, and chapter pages
- 🔒 **Privacy-first** — built in compliance with Uganda's Data Protection & Privacy Act 2019

**Tech stack:**

```
Frontend   Next.js 15 (App Router) · TypeScript · Tailwind CSS
Database   Neon (PostgreSQL) · Drizzle ORM
Auth       BetterAuth
Storage    Cloudflare R2
Email      Resend
Analytics  PostHog
Hosting    Vercel
```

---

## The Sports League

The BICKOSA Sports League gets its own dedicated application — a standalone platform that lets fans, players, and administrators follow every match from kick-off to final whistle.

**Core features:**

- ⚽ **Live Standings** — season-wide league table with points, goal difference, and form
- 📅 **Fixtures & Results** — upcoming matches and full historical scorelines
- 🥇 **Top Scorers** — golden-boot leaderboard with goals, assists, and minutes played
- 🏆 **Seasons Archive** — past season records and historical champions
- 🎽 **Team Profiles** — squad lists, player cards, and club information
- 📊 **Match Reports** — scorers, cards, and post-match statistics
- 🛠 **Admin Panel** — fixture scheduling, score entry, and squad management

The sports league is intentionally decoupled from the alumni portal so it can be publicly accessible without requiring a login, and so the codebase stays focused and easy for sports-oriented contributors to work on.

---

## Design System

All BICKOSA products follow a unified design language.

**Colors:** White and Navy Blue are primary. Gold is a prestige accent — used sparingly as a single CTA or highlight per page. Never the dominant colour of a layout.

| | Token | Hex | Role |
|---|---|---|---|
| 🟦 | `--navy-900` | `#0d1b3e` | Primary brand · navbars · buttons · body text |
| ⬜ | `--white` | `#ffffff` | Default page and card background |
| 🟡 | `--gold-500` | `#c9a84c` | Accent · single CTA per page · award badges |

**Typography:** Google Sans for headings and UI · Inter for body and data.

The full design reference is in [`bickosa-design`](https://github.com/BICKOSA/bickosa-design).

---

## Contributing

We warmly welcome contributions from BCK alumni, friends of the school, and anyone who wants to support our mission. You don't have to be a developer — there are many ways to help.

**For developers:**

1. Fork the repository you want to contribute to
2. Create a branch: `git checkout -b feature/your-feature-name`
3. Make your changes following our code conventions (TypeScript strict, Drizzle for DB, react-hook-form + zod for forms)
4. Open a pull request with a clear description of what you've built and why

**For designers:** Open a discussion or issue in `bickosa-design` with your proposals. We follow the existing brand system but always welcome refinements.

**For non-developers:** Help us by reporting bugs, writing documentation, translating content, or spreading the word among fellow alumni.

Please read our [**Contributing Guide**](CONTRIBUTING.md) and [**Code of Conduct**](CODE_OF_CONDUCT.md) before getting started.

---

## Community & Support

| Channel | Link |
|---|---|
| 🌐 Website | [bickosa.com](https://bickosa.com) |
| 💬 Discussions | [GitHub Discussions](https://github.com/orgs/BICKOSA/discussions) |
| 🐛 Bug Reports | [Portal issues](https://github.com/BICKOSA/bickosa-portal/issues) · [League issues](https://github.com/BICKOSA/bickosa-league/issues) |
| ✉️ Email | [hello@bickosa.com](mailto:hello@bickosa.com) |
| 📋 Project Board | [BICKOSA Portal Roadmap](https://github.com/orgs/BICKOSA/projects) |


---

## Governance & Transparency

BICKOSA is governed by an elected executive committee serving two-year terms. The association operates under Ugandan law and is committed to financial transparency — annual reports and audited financial summaries are published in [`bickosa-docs`](https://github.com/BICKOSA/bickosa-docs) and on the portal.

Data collected through our digital products is handled in compliance with Uganda's **Data Protection and Privacy Act, 2019** (Act 9 of 2019). See our [Privacy Policy](https://bickosa.com/privacy-policy).

---

## License

All code in this organisation is released under the [MIT License](LICENSE) unless otherwise noted in a specific repository. Governance documents and official association records remain the property of BICKOSA.

---

<div align="center">

**Built with pride by BCK old students, for BCK old students.**

*Bishop Cipriano Kihangire Senior Secondary School · Luzira, Kampala, Uganda · Est. 1999*

<br />

[![bickosa.com](https://img.shields.io/badge/Visit-bickosa.com-0d1b3e?style=for-the-badge&labelColor=0d1b3e&color=c9a84c)](https://bickosa.com)

</div>
