# Spruce Hollow — Session Handoff
**Last session:** April 15, 2026
**For:** Next Claude session picking up this project

---

## Project at a glance

Supernatural horror feature. 140-page script (`spruce_hollow_FEB2026.fdx`). Four college-aged friends trapped in an abandoned juvenile detention facility in Western Maryland. Two dead by end of act 3. The facility wins.

- **Script:** 120 filmable scenes, 158 total (incl. inserts/supers)
- **Shoot days:** 61 estimated
- **Budget range:** $237K–$290K (low tier, non-union, owner-operator)
- **42% night shoots** — major cost driver

---

## What's live

### GitHub Pages site
- **URL:** https://mim18-code.github.io/spruce-hollow-locations/
- **Repo:** https://github.com/MIM18-code/spruce-hollow-locations
- **Account:** MIM18-code (gh CLI authenticated)
- All 10 location images download locally and served from `img/` (verified 200 OK). Wikimedia Commons hotlinking rate-limited their IPs, so images were pulled via Python urllib with policy-compliant User-Agent and resized to ~800px JPEGs (60–240KB each, ~960KB total bundle).

### Files in the working directory
- `index.html` — the deployed location scouting site (1,431+ lines). Single-file, Leaflet map, tier filters, expandable cards, responsive, dark theme.
- `img/` — 10 JPEGs served from GitHub Pages
- `Spruce_Hollow_Breakdown.md` — full production breakdown (locations, cast, day/night, special requirements, scheduling notes, budget)
- `DEEP_RESEARCH_PROMPT.md` — 14-question deep research prompt used to commission the follow-up research reports
- `Film Location Scouting Research Deep Dive.txt` — one of the three deep research reports that came back (the other two: `deep-research-report (11).md` and `SPRUCE HOLLOW — Location Scouting Deep Research Re 2.md`)

---

## Decisions made this session

### Removed / downgraded (impossible or impaired)
| Location | Why |
|---|---|
| Harrisburg State Hospital | Actively demolished, felony trespass |
| Forest Haven | Federal land, lawsuit active since 1976 |
| Victor Cullen Center | Active DJS facility, abuse litigation |
| Henryton State Hospital | Demolished 2013 |
| Rosewood Center | Redeveloped by Stevenson University |
| **Alfred D. Noyes** (was Tier 1) | Research confirmed: $6M active dehardening per FY26 Budget Bill Ch. 602/2025. 2021 PREA audit shows single "H" building, not a multi-building campus. No central yard. Rooms are youth living units, not cells. Window effectively closed. |
| **Mid-Orange / Warwick** (was Tier 1) | Research confirmed campus is now "Hudson Sports Complex" — thriving commercial/recreational redevelopment. A24's *Sing Sing* (2023) and *Marty Supreme* (2024) did film there, but authentic decay aesthetic is gone. |

### Tiers as they stand
- **Tier 1:** Pennhurst (PA), Trans-Allegheny Lunatic Asylum (WV)
- **Tier 2:** Alfred D. Noyes (MD, downgraded), Mid-Orange (NY, downgraded), Glenn Dale (MD), Crownsville (MD), Glen Mills (PA), SCI Cresson (PA)
- **Tier 3:** Thunder Bridge (VA), WV Penitentiary (WV), Rockland (NY), Letchworth (NY)

### Critical new warning on the site
**Maryland Film Tax Credit sunsets June 30, 2026** unless General Assembly extends. Department of Legislative Services recommended it expire. Red callout is live in the Blueprint section and on the MD incentive card.

### Strategic recommendation (now in the footer)
**WV-primary (TALA) + MD-secondary (Green Ridge) split shoot before June 30** to capture both tax credits.
- WV: 27% refundable + 4% bonus for 10 WV residents = **31%**, no cap, $50K min, transferable
- MD: 28% refundable, but sunset in ~10 weeks

---

## Confirmed intelligence from the research reports

| Fact | Source |
|---|---|
| Pennhurst: feature film *Devon* (2024) shot there. Active production bookings confirmed. Paracon expo May 16-17, 2026. | `deep-research-report (11).md`, `Re 2.md` |
| TALA: Oct 2025 crew identified as JCFilms *The Asylum* (dir. Jason Campbell). ONE DAY ONLY, not multi-week. Contact 304-269-5070 M-F 9-5. | `Re 2.md` |
| TALA solitary wing: ~12 cells, ~8×10 ft, metal doors largely intact, barred windows, "stable decay" | `deep-research-report (11).md` |
| Sleighton Farm (adjacent to Glen Mills): major arson fire June 2024 destroyed 100-year-old dorm. PSP arson investigation active. | `Re 2.md` |
| Glen Mills active portion: Clock Tower Schools (610-459-8100), 20-bed provisional license, run by former Glen Mills executive Christopher Spriggs. Vacant portions have no identifiable single contact. | `deep-research-report (11).md` |
| Suburban Studios LaVale (formerly Motel 6, 12310 Winchester Rd SW): still operational, ~$45-55/night production buyout rate for 60+ day bookings. GM phone (301) 729-4100 per `Film Location Scouting Research Deep Dive.txt`, (301) 729-6700 per VisitMaryland listing. **Test both.** |
| Green Ridge State Forest film permit: $500 admin fee via Park Manager (301-478-3124, Flintstone, MD). No statutory timeline, budget 2-4 weeks. | `Re 2.md` |
| Flintstone Post Office/Gas Station (21600 National Pike NE) — confirmed standing, active USPS. Phone (301) 478-3109. Filming would require USPS/federal approval. | `Re 2.md` |
| MD tax credit: Small Film $25K min / $125K max credit. Standard $250K min. Catherine Batavick at MFO for under-$500K productions, 443-865-9000. | `Film Location Scouting Research Deep Dive.txt` |

---

## Open questions / gaps the research couldn't close

1. **TALA multi-week rate** — JCFilms was 1 day. No public data on a 20–30 day rental. Need to call 304-269-5070 directly.
2. **Pennhurst multi-week rate** — Floor price $1,250 for small paranormal; feature rates undisclosed. Call 484-886-6080.
3. **SCI Cresson film access terms** — info@cressonsanatorium.com / 814-940-5353. Their urbex photography business is documented; feature production is not.
4. **Green Ridge SF fire roads with closed canopy** — requires physical scout drive. Candidates flagged: Merten's Avenue, Stafford Road, Tower Road. CCC structures: research reports disagree (one says CCC foundations remain, another says all removed by 1936). Site visit resolves this.
5. **Route 40/68 gas station inventory** — no public database. Recommended: Google Street View sweep Hancock → Cumberland, then a half-day scout drive.
6. **Local crew pool in Cumberland/Frostburg** — research couldn't confirm a regional film crew exists. Likely need Baltimore/DC imports.
7. **Child performer agencies in Baltimore/DC** — research named Agency 615 (MD), Showcase Models & Talent (DC), Dove Agency (NoVA). Unverified roster availability.
8. **MD tax credit extension status** — need someone watching the General Assembly. As of Apr 15, 2026, DLS has only recommended sunset; no bill text seen.

---

## First calls when production is ready

| # | Who | Phone | Ask |
|---|---|---|---|
| 1 | Catherine Batavick, MD Film Office | 443-865-9000 | MD credit timeline. Is there a sunset extension in the current session? Pre-qualification for split-state shoot? |
| 2 | Trans-Allegheny Lunatic Asylum | 304-269-5070 | Multi-day/multi-week rate for crew of 25-30. Seclusion wing scout with camera. Exterior night shooting permitted? |
| 3 | Pennhurst Asylum | 484-886-6080 | Production rate card. Off-season (Feb–May) multi-week buyout. Can they provide cell environment or is art dept build required? |
| 4 | Green Ridge State Forest | 301-478-3124 | Commercial film permit app. Overnight shoot permissions. Which roads offer closed canopy. Standing CCC structures? |
| 5 | Suburban Studios LaVale | 301-729-4100 or 301-729-6700 | 60+ day production buyout rate. RV/bus parking confirmation. |
| 6 | WV Film Office | (via WV Division of Culture & History) | Pre-qualify WV portion of budget. 4% bonus threshold clarification. |

---

## Design system in place (for future UI work)

The site uses a custom "Appalachian institutional decay" aesthetic:
- **Fonts:** DM Serif Display (display) / Inter (body) / JetBrains Mono (labels, addresses)
- **Palette:** Forest greens + institutional concrete + warning amber. All CSS variables in `:root` — don't hardcode colors.
- **Tier colors:** green (Tier 1), amber (Tier 2), brown (Tier 3), blue (Secondary), red (eliminated — currently unused since all eliminated are removed)
- **Components:** Location cards with expandable details, Leaflet map with color-coded pins, scorecard table, tier filter chips, callout boxes (green / amber / red accent), incentive cards, checklist
- **Placeholder system:** When `imgUrl` is empty, card falls back to CSS gradient with `placeholderType` data attribute (institution / forest / highway / motel / secondary). Atmospheric repeating-linear-gradient scanlines overlay.
- **GitHub Pages:** Single `index.html`, no build step. Leaflet from CDN. All images in `img/` directory.

---

## Immediate productive next moves (in priority order)

1. **Book the TALA scout** — Call 304-269-5070 this week. Get eyes on the seclusion wing with a camera. This is the single highest-leverage decision — if TALA works, the shoot anchors there on the 31% refundable credit.
2. **File MD credit pre-qualification** — Even while still deciding. Catherine Batavick, 443-865-9000. Lock in the 28% before the June 30 risk date.
3. **Pennhurst rate inquiry** — Parallel path. 484-886-6080. Ask specifically for off-season (Feb–May) multi-week buyout pricing.
4. **Green Ridge SF permit app + scout drive** — If any MD exterior days are happening, this needs to start. 2-4 week permit timeline means starting now if June shoot window is realistic.
5. **VFX budget revision** — Current budget has $1,500 for VFX. Actual needs (ghost compositing, face morphing, body horror, video distortion, text self-carving) are $15K–$30K. Bully! Entertainment, Word of Mouth, Pixeldust Studios (all Baltimore/MD) were named in research. Get quotes from two.
6. **Intimacy coordinator** — Not budgeted. Scene 99-116 requires one. SAG-AFTRA Intimacy Coordinators committee has a vetted list.

---

## What NOT to revisit

- The breakdown / budget / schedule numbers are solid — they're grounded in the actual script and the film-budget MCP's calibration. Don't re-derive.
- The eliminated locations stay eliminated. Victor Cullen / Harrisburg / Forest Haven / Henryton / Rosewood are all permanently impossible.
- Don't try to hotlink Wikimedia Commons images — they 429 rate-limit. Use the local `img/` directory. If new images needed, download via Python urllib with a compliant User-Agent that identifies the project and contact.

---

## If something breaks on GitHub Pages

- Check https://github.com/MIM18-code/spruce-hollow-locations/actions for Pages deploy status
- All 10 images verified loading as of Apr 15 23:00 via `curl -I https://mim18-code.github.io/spruce-hollow-locations/img/{name}`
- Leaflet loads from `unpkg.com/leaflet@1.9.4` — if CDN breaks, pin locally
- No build step. `git push` is deploy.

---

## Known inconsistencies to resolve eventually

- Two different phone numbers surfaced for Suburban Studios LaVale (301-729-4100 vs 301-729-6700). Call both.
- Research report 1 (`Film Location Scouting Research Deep Dive.txt`) says CCC structures at Green Ridge still standing (stone culverts, masonry bridges). Research report 2 (`deep-research-report (11).md`) says all CCC structures removed by 1936. Physical scout resolves.
- Research report 1 describes a "one-day filming" at TALA as a multi-day residency ($20K-$25K/week). Research report 2 correctly identifies it as a 1-day JCFilms shoot. Report 2 is more trustworthy here — it names the production, director, and dates. Treat report 1's TALA rental rate as speculation.

---

*Handoff written by Claude. If you're the next session, the user is Joshua Land (MindInMotion). He's the writer/director/producer — owner-operator — so crew rates in the budget zero out the director/producer line. The film is personal for him. He wrote the script over multiple revisions (Feb 2026 is the shooting draft). Treat his decisions on story/tone as authoritative. He wants practical, grounded information — he's allergic to AI overhedging and likes short, direct answers with concrete numbers and contact info.*
