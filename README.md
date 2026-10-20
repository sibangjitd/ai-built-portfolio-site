# AI-built portfolio site: 54 versions, one story

How I turned my personal site ([sibangjitdas.com](https://sibangjitdas.com)) from a resume page into a storytelling page for recruiters in India and Canada, by directing Claude (Anthropic's AI) round by round, mostly by voice.

**Compare the first and the final:** [v1](versions/v1-redesign-live.html) | [v54 (live)](versions/v54-flipkart-tags.html)

## The goal

One idea: *"I walk into the gap nobody owns, and close it."* A recruiter should get who I am in 10 seconds and my career in a scroll, not a wall of bullet points.

## How I worked

- **I directed, the AI built.** I gave direction by voice, usually one change at a time. Claude generated the page with Python scripts and checked it in a real browser at laptop and phone widths.
- **Every round is a new file.** Nothing was overwritten, so all 54 versions are in [`versions/`](versions/). That is the progress record.
- **Hard rules I set:** never invent metrics or experience, keep earlier versions untouched, consult me on phrasing before rewriting, and don't publish until I say so.
- **I made the judgment calls.** Examples: I rejected "Need someone who gets it done?" because it read as a doer, not a leader, and I refused to promise "analytics roles" before I was ready, so the copy says "planning".

## Timeline

| Stage | Versions | What changed |
|---|---|---|
| Start | v1 | Redesigned resume-style site |
| Story first | v2 - v14 | Punchy hero, clean cards, career chapters, certifications |
| Structure | v15 - v25 | Fixed header, "How I work", career timeline chart, compact layout |
| Copy and skills | v26 - v40 | One locked sentence and three skill tags per role, section order, headings, role list |
| Hero diagram | v41 - v49 | Animated supply chain loop around my photo: Inbound, Inventory, Outbound, Returns, with a Data & AI ring |
| Final polish | v50 - v54 | Closing line, working Email and Contact buttons, skill tag order |

## Screenshots (laptop width)

| v1 | v14 | v23 |
|---|---|---|
| ![v1](screenshots/v01.png) | ![v14](screenshots/v14.png) | ![v23](screenshots/v23.png) |

| v29 | v41 | v49 | v54 |
|---|---|---|---|
| ![v29](screenshots/v29.png) | ![v41](screenshots/v41.png) | ![v49](screenshots/v49.png) | ![v54](screenshots/v54.png) |

## What I learned

- Small, one-change rounds beat big rewrites: every decision stayed reviewable.
- Voice is fast for direction, but anything that needs exact wording or a file check is better done in text.
- The AI will happily generate impressive-sounding copy. My job was to keep it true.

## Viewing the versions

The HTML files open as live pages through GitHub Pages. Each is a single self-contained file.
