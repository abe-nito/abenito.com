# abenito.com

Personal site for Abe Nito, product designer at Microsoft (Vancouver). Hosted on GitHub Pages from this repo (main branch, root), with the domain at GoDaddy. DNS is already set up, so don't change it.

## Files
- `index.html`: the home page, plain HTML/CSS. No frameworks or build step.
- `portfolio.html`: the portfolio, behind a simple client-side password (SHA-256 hash in the page; not real security, so nothing confidential goes in it). Same styles as the home page.
- `resume.pdf`: linked from the page. File names are case-sensitive, so keep it exactly `resume.pdf`.
- `CNAME`: contains `abenito.com`. Never delete or edit it.

## Current design
- A "work in progress" home page. The headline animates between "Hello" and "Kamusta" (it respects reduced motion).
- Copy: "I'm Abe Nito / — product designer at Microsoft."
- Links: Portfolio ("View" opens a password popup; correct password goes to portfolio.html; popup has a "No password? Email hello@abenito.com for access" mailto link), Resume (resume.pdf), Email (hello@abenito.com), LinkedIn (linkedin.com/in/abenito).
- Style: Helvetica ("Helvetica Neue", Helvetica, Arial), a very light canary yellow background (#FFFADB), dark text (#14211D), thin lines between links, and a black circle SVG favicon.

## Analytics
- Google Analytics 4, Measurement ID `G-T7JPN658FL`, on both pages (gtag snippet at the top of `<head>`). Keep it on any new page.
- A small bottom-left notice ("OK" / "Opt out") stores the choice in localStorage and updates consent mode. Ads storage is always denied.
- Custom events: `portfolio_open`, `portfolio_unlocked`, `portfolio_wrong_password`, `resume_click`, `email_click`, `linkedin_click`, `request_access`. Use `track('name')` for new ones.

## How to work
- Change only what Abe asks. Don't redesign or switch fonts unless asked.
- Commit to main with a short, clear message so the change goes live, then tell Abe it'll be live on abenito.com in a minute or two.
- Everything here is public. Flag phone numbers or internal Microsoft figures before publishing.
- Keep replies short and casual.
