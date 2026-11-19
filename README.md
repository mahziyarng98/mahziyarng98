# Mahziyar

**Penetration tester, Next.js developer, and Linux app builder.** I build and review web apps with security in mind, and ship Rust desktop tools with automated tests and Linux release packages.

[![Open to freelance work](https://img.shields.io/badge/Open_to-freelance_work-2ea44f)](#hire-me)

---

## What I do

**Secure Next.js development**
New apps or features built security-first: authentication and session handling, authorization checks on every Server Action and API route, input validation, security headers and CSP, safe handling of secrets and environment variables, and a lean dependency tree.

**Security review and pentest of Next.js and web apps**
Manual testing against the OWASP Top 10, with attention to Next.js-specific pitfalls: unprotected Server Actions, middleware-only auth, server data leaking into client components, `NEXT_PUBLIC_` secrets, SSRF through server-side fetches, and misconfigured caching. You get a written report with reproduction steps, impact, severity, and concrete fixes, plus a retest once the fixes are in.

**Fix and harden**
I can implement the fixes from a review myself, so findings turn into merged code and not just a PDF.

I test only with written authorization and an agreed scope.

**Linux applications**
I also build desktop tools in Rust: Cawget, a segmented download manager with a CLI and a Svelte/Tauri interface, and Crab Player, a native egui/libmpv media player. Both have automated checks, installable releases, and documented limitations.

## Tech stack

- **Web:** Next.js, TypeScript, JavaScript, React, Tailwind CSS
- **Desktop:** Rust, Tauri, Svelte, egui, libmpv; Linux packaging
- **Security:** Burp Suite, Nmap, ffuf, Gobuster, Subfinder, Amass, httpx, Nuclei; reconnaissance, subdomain enumeration, OSINT, Bash and Linux tooling
- **Also shipped:** Firefox WebExtensions (Manifest V3), QML / Quickshell plugins

## Selected work

| Project | What it is |
|---|---|
| [**cawget**](https://github.com/mahziyarng98/cawget) | Segmented HTTP/HTTPS download manager: Rust engine and CLI, Svelte/Tauri desktop app, resume and scheduling, integration tests, and Linux release packages. |
| [**crab-player**](https://github.com/mahziyarng98/crab-player) | Native Linux media player built with Rust, egui, and libmpv; includes CI, performance measurements, and packages for several Linux distributions. |
| [**nextjs-pentest-lab**](https://github.com/mahziyarng98/nextjs-pentest-lab) | Deliberately vulnerable Next.js shop with a full pentest report: 7 findings (IDOR, broken access control, SQL injection, XSS and more) and a `fixed` branch showing every remediation. |
| [**omarchy-gravity**](https://github.com/mahziyarng98/omarchy-gravity) | Orbital app launcher for the Omarchy desktop shell, ranked by how often you actually launch each app. Has tests and an external contributor. |
| [**jalali-calendar**](https://github.com/mahziyarng98/jalali-calendar) | Jalali (Solar Hijri) date, clock, and Iranian holidays for the Omarchy bar, with tested date conversion. |

For installation, test commands, and known limitations, see each project's README. Please use the project's security policy for vulnerability reports.

## Hire me

Have a Next.js app that needs building, reviewing, or hardening? Get in touch:

**Email:** [mahziyarng98@gmail.com](mailto:mahziyarng98@gmail.com)
