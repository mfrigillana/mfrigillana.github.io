# Marion Frigillana

**Enterprise CX Solutions Architect · Perth, Western Australia**

Live site: **[mfrigillana.github.io](https://mfrigillana.github.io)**

I ship enterprise CX platforms into production, and I'm building the AI layer that's reshaping them.

12+ years in tech, including 7 years delivering Genesys Cloud CX contact centres for banks, governments and global brands across EMEA, North America and APAC. I've delivered Copilot, Agent Assist and conversational AI into production, and I now lead digital transformation, for the Philippine Honorary Consulate in Perth.

Open to roles in Perth and remote. Full Australian working rights.

---

## What's on the site

| Section | What it does |
|---|---|
| **Circuit** | Who I am in thirty seconds: three domains (CX platforms, AI layer, community tech) wired to a core chip. Hover or tap a card to trace its skills and projects. |
| **Skills** | A periodic table of 84 skills in ten groups. Pick one and the rest of the page lights up the projects and roles that used it. There are no self ratings. |
| **Projects** | Thirteen projects on three orbits (enterprise delivery, community and civic, academe and R&D), each with an animated cover and a detail view. |
| **Experience** | Roles, education and certifications, linked to the skills behind them. |
| **Learning** | 132 LinkedIn Learning courses grouped into nine themes, plus certifications and coursework in progress. |
| **Terminal** | A small command line for exploring by keyboard. Type `help` to start. |
| **Résumé** | Plain semantic HTML that ATS parsers read cleanly. Prints straight to PDF. |
| **Connect** | A contact form, LinkedIn, and email and phone revealed on request. |

## How it's built

- **One file.** The whole site is a single `index.html`: HTML, CSS, JavaScript, SVG and the logo. Nothing to install and no build step to deploy.
- **Written by hand.** No framework and no libraries. The only external resource is Google Fonts.
- **One data model.** Skills, projects, roles and courses live in one object, and every interactive view reads from it, so a selection in one place shows up everywhere.
- **Animated in SVG.** Each project cover tells its story in motion. Animations pause when they scroll out of view.
- **Accessible.** Keyboard navigation throughout, visible focus, screen reader labels, and a reduced motion mode that stops animation.
- **Responsive.** Tested from 320px phones to 1920px desktops, with a bottom tab bar on mobile and dark and light themes.

## Security

A portfolio has no logins or secrets, so the focus is on keeping the page itself trustworthy and keeping bots out of the inbox.

- **Content Security Policy** pinned to sha256 hashes of the exact inline script and style. Nothing else is allowed to run.
- **Trusted Types** enforced. The code never turns strings into HTML, so injected markup cannot execute.
- **Contact details** are assembled at runtime and never appear in the page source.
- **Contact form** with a honeypot field, a minimum fill time, an interaction check, a link limit and a one minute cooldown. Messages are relayed by Formspree.
- **Deterrents** for casual copying: the right click menu is off outside form fields, and the page blanks briefly when common screenshot shortcuts fire. No web page can fully stop screenshots, and this one does not pretend to.

## Updating the site

The security policy is tied to the exact bytes of the inline script and style. **If `index.html` is edited by hand, including pasting in analytics or tracking snippets, the hashes must be regenerated**, or the browser will block the edited code.

## Repository

| File | Purpose |
|---|---|
| `index.html` | The site |
| `robots.txt` | Crawler rules |
| `mf_logo.png` | Logo |
| `README.md` | This file |

## Contact

Use the **Connect** section on [the site](https://mfrigillana.github.io/#connect), or find me on [LinkedIn](https://www.linkedin.com/in/mfrigillana).

## Rights

© 2026 Marion Frigillana. All rights reserved. The content, design and code are not licensed for reuse. Client and product names belong to their owners.
