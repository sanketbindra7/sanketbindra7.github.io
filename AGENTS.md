# AGENTS.md — Rules for AI agents working on this site

This repository is Sanket Bindra's personal website (`sanketbindra7.github.io`), served by GitHub Pages.
Any agent editing it must follow these rules.

## Source of truth
- The CV (`Sanket_Bindra_Resume_CBS_2026.pdf`) is the source of truth for all content.
- Keep the CV's section order on the site: Education → Professional Experience → Additional Information.
- Never invent, round up, or embellish numbers, titles, dates, employers, or achievements. If something is unclear, ask.

## Never publish
- Phone numbers (the CV's phone number stays off the site).
- Home or street addresses, date of birth, ID or passport numbers, or visa status.
- Salary, compensation, or expected compensation.
- Confidential client names or deal details beyond what the CV already says. Keep descriptions as written, e.g. "a USD 900M global packaging company".
- References' names or contact details, transcripts, or grade reports beyond the CGPAs in the CV.
- API keys, tokens, passwords, or `.env` files.
- The raw CV PDF, unless Sanket explicitly asks for a download link.

## Ask Sanket first before
- Any `git push`, creating or changing the GitHub repository, or enabling or changing GitHub Pages.
- Adding a new email address, social link, or any contact method.
- Adding analytics, trackers, cookies, comment widgets, or third-party scripts.
- Adding content that isn't in the CV (blog posts, opinions, project write-ups, testimonials).
- Deleting or renaming files, or changing the section order.
- Replacing or editing the profile photo (`DP.jpeg`).

## Style
- Vibe: professional but approachable. The copy should be confident and concise, not salesy.
- Colors: Columbia blue (`#B9D9EB`) as the accent, deep navy (`#0B2545` / `#1D4F91`) for text and headings, and plenty of white space.
- Navigation: streamlined. One sticky top bar with anchor links to each section. Smooth scrolling. No dropdowns.
- Layout: tiles or cards for each role and each school. Readable at phone width with no horizontal scrolling.
- Typography: one clean sans-serif (Inter via Google Fonts, with system fallbacks).
- Tech: plain static HTML and CSS, plus minimal vanilla JS only if needed. No build step or framework.
- Accessibility: semantic HTML, alt text on images, sufficient contrast, and visible focus states.
- Use USD figures and date formats exactly as written in the CV.
