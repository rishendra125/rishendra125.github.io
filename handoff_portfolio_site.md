# Handoff: Portfolio Site — Build Brief

## Instructions for the new chat — read fully before responding

Read this entire file first. Then:

1. **Do NOT start building anything** — no code, no files, no repo setup.
2. **Summarise back what you understand the scope to be**, so I can confirm before you proceed.
3. **Ask any clarifying questions in one go**, not spread across turns.
4. **Wait for my explicit go-ahead** before building anything.

---

## Background

I'm a Senior Consultant with a PMO/project/program management background, pivoting toward AI Product Manager roles alongside my PMO job search. Over the past few months I've built 5 real AI portfolio projects, each pushed to GitHub with working code — not just PRDs or mockups.

The problem: these projects are scattered across separate GitHub repos with technical READMEs. A recruiter gives a portfolio about 30 seconds of attention — right now there's no single page where they can scan all 5 projects at a glance and click through to whichever interests them.

**Inspiration (not to copy, just the format idea):** saw another AI PM's portfolio site (shrikantmaliwal.framer.website) — one clean landing page, each project as a short one-liner with a link out. His portfolio is documentation-led (PDFs, PRDs). Mine should be the opposite — **build-led**: the whole point is proving I can actually ship working code, not just write specs. Link straight to GitHub repos as the primary action, not buried behind a PDF.

---

## Scope

**Format:** Simple static site — HTML/markdown, no build tooling, no frameworks. Free to host on GitHub Pages.

**Tone/portrayal:** Everything described in plain, layman's terms. No jargon, no AI-buzzword-heavy descriptions. Someone with zero technical background should understand what each project does after reading one sentence.

**Structure:** Single landing page. Not split into "AI projects" vs "corporate/PMO background" sections — keep it focused purely on the AI/technical project work for now.

**The 5 projects to feature**, with plain-language descriptions already drafted (use these, don't reinvent):

| Project | GitHub link | Plain description |
|---|---|---|
| QueryGPT MVP | https://github.com/rishendra125/querygpt_mvp | Lets you ask a database a plain-English question and get the right answer back — no SQL knowledge needed. Inspired by how Uber built a similar internal tool. |
| Spec Audit Tool | https://github.com/rishendra125/spec_audit_tool | Reviews a product spec before it gets built and flags what's missing — edge cases nobody thought of, requirements that can't be tested, numbers with no source behind them. |
| MeetingMeet | https://github.com/rishendra125/meetingmeet | Takes a meeting transcript, figures out the action items, decides what's safe to share vs. what should stay private, and drafts emails using only the safe parts. |
| Instagram → YouTube Song Sync | https://github.com/rishendra125/instagram_youtube_song_sync | Takes music saved on Instagram and automatically builds a matching YouTube playlist — no manual searching. |
| Scrum RAG Chatbot | https://github.com/rishendra125/scrum-rag-chatbot | A chatbot that answers Scrum questions by actually reading the official Scrum.org guides first, rather than guessing. |

Do not include "my-firstouting" (throwaway test repo) or RetroLoop/InsureEase (not currently on GitHub) — keep to exactly these 5.

---

## What each project entry should contain

- Project name
- One-sentence plain description (from the table above — refine wording if needed, but keep it simple, not technical)
- Link to the GitHub repo
- Optionally: 2-3 bullet points on what makes it interesting (e.g. "caught 4 real bugs through live testing," "eval harness with golden dataset") — but only if it doesn't turn into jargon

---

## Style requirements

- Plain language throughout — this is the same "layman's terms" instruction driving the whole brief.
- No em-dashes, no over-polished AI-sounding phrasing.
- Clean, uncluttered — closer to a simple list than a heavily designed portfolio site.
- Mobile-friendly (recruiters often view on phone).

---

## Not yet decided — flag back to me, don't assume

- **Build path:** Cowork or Claude Code — not decided. Recommend one with reasoning if you have a preference, but confirm with me before proceeding either way.
- **Hosting:** Planning on GitHub Pages (free, fits since everything's already on GitHub) — confirm this is right before setting it up.
- **Personal intro/tagline:** This brief doesn't include one — ask me for a short intro line about who I am before building, rather than inventing one.
- **Contact info:** Ask whether I want email/LinkedIn visible on the page, and get the actual details from me rather than placeholder text.

---

## Change Log
- **Aug 2026:** Created after reviewing another AI PM's portfolio site and comparing it against my GitHub profile.
