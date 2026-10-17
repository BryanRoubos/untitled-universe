# Where the Light Falls

**An original dark-fantasy story world and illustrated concept book.**  
Creative direction: Bryan Roubos · Last organized: 17 October 2026

[**Read the illustrated website**](https://bryanroubos.github.io/untitled-universe/) · [**Browse current canon**](decisions/CANON_STATUS.md) · [**Creative rules**](CREATIVE_RULES.md)

> **Author spoiler warning:** This public repository contains major ending revelations. The website's numbered chapters avoid revealing them; the GitHub lore files are intended for development.

## Where to start

| Purpose | Primary location |
| --- | --- |
| Reader-facing illustrated chapters | [Website](https://bryanroubos.github.io/untitled-universe/) · [`index.html`](index.html) |
| **Single authority for what is canon** | [`decisions/CANON_STATUS.md`](decisions/CANON_STATUS.md) |
| Current world geography and social setting | [`world/WORLD_OVERVIEW.md`](world/WORLD_OVERVIEW.md) |
| Current narrative spine and continuity | [`narrative/STORY_OUTLINE.md`](narrative/STORY_OUTLINE.md) |
| Elias, Mira and their relationship | [`characters/`](characters/) |
| Art style and approved references | [`art/ART_DIRECTION.md`](art/ART_DIRECTION.md) |
| Dated history of approvals and reversals | [`decisions/DECISION_LOG.md`](decisions/DECISION_LOG.md) |
| Open questions and working decisions | [`decisions/CANON_STATUS.md`](decisions/CANON_STATUS.md#3-open-decisions--do-not-invent) |
| Prior drafts (not current canon) | [`archive/`](archive/) |
| Previous game-medium ideas (not a commitment) | [`game-design/GAME_VISION.md`](game-design/GAME_VISION.md) |
| Current session context | [`SESSION_HANDOFF.md`](SESSION_HANDOFF.md) |

## Repository map

```text
untitled-universe/
├── index.html               # Public illustrated reading experience + Workshop
├── assets/images/           # All artwork, unchanged filenames
├── art/                     # Visual direction and approved style references
├── characters/              # Character dossiers, sibling relationship, objects
├── world/                   # City geography and societies
├── narrative/               # Current story spine and scene drafts
├── decisions/               # Canon authority and decision history
├── game-design/             # Nonbinding earlier medium exploration
├── archive/                 # Dated snapshots of superseded drafts
├── CREATIVE_RULES.md        # Creative collaboration rules
└── SESSION_HANDOFF.md       # Short current-state handoff
```

## Canon policy

**Confirmed** means explicitly approved by the creator. **Approved visual direction** establishes a style or broad design, not every object in an image. **Exploratory/open** is not canon. **Retired** means superseded or rejected. The [current canon tracker](decisions/CANON_STATUS.md) wins over historical drafts; the [decision log](decisions/DECISION_LOG.md) preserves how decisions changed.

The core city is one physically connected, vertically layered Gothic metropolis, with a lively lower city and sunlit upper districts. Elias and Mira lived in a concealed home beneath the viaducts. The full story's middle, supporting cast and precise geography are still being developed. The project's final medium remains undecided.

## Working with the site

The site is a static GitHub Pages book served from `index.html`. Chapter IDs (`#city`, `#elias`, `#mira`, `#life`, `#story`, `#atelier`) are stable navigation links; `#workshop` is the appendix. Art assets belong in `assets/images/`; keep original filenames and encode spaces in URLs. Update captions and alt text when adding art. Avoid author-only spoilers in numbered chapters, captions, or open Workshop cards.

Before publishing, check local image paths, chapter anchors, spoiler visibility, narrow-screen navigation and keyboard access to image enlargement. Keep the current canon tracker and handoff synchronized with any newly **approved** story changes.

## Historical material

The [archive](archive/) retains earlier documents for provenance. Some other older topic-specific files may still contain exploratory language; defer to the canon tracker whenever there is a conflict. No historical idea becomes canon simply because it remains in Git history.
