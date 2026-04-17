# Strict Verification Pass - 2026-04-17

This pass upgrades the expert index toward playbook readiness using only directly accessible public sources in this environment.

## Verification method used

- Confirmed that profile/video/alternative URLs are concrete links (not search-result placeholders) in `research/sources.md`.
- Replaced weak/provisional identity mapping for Expert 10 with a consistent identity (`Adrie Smith`) based on collected source URLs.
- Replaced non-concrete "YouTube not found" states with explicit alternative evidence URLs where no verified YouTube URL was available.
- Left publish dates as pending where platform-level access is required (not reliably accessible through current automated fetch/search tools).

## Expert-by-expert status

- Justin Welsh: Profile URL direct, video URL direct, status = strong.
- Chase Dimond: Profile URL direct, video URL direct, status = strong.
- Amanda Natividad: Profile URL direct, no verified direct video URL found, alternative source documented.
- Dave Gerhardt: Profile URL direct, video URL direct, status = strong.
- Katelyn Bourgoin: Profile URL direct, video source present (playlist-level), status = medium-strong.
- Val Geisler: Profile URL direct, no verified YouTube URL found, alternative talk source documented.
- Ethan Smith: Profile URL direct, video URL direct, status = strong.
- Brennan Dunn: Profile URL direct, no verified YouTube URL found, alternative source documented.
- Niko Julius: Profile URL direct, no verified YouTube URL found, direct LinkedIn post retained as alternative evidence.
- Adrie Smith (normalized from "Adrie Syas"): Profile URL direct, no verified YouTube URL found, direct LinkedIn post retained as alternative evidence.

## Remaining gap to reach fully playbook-ready

- Capture exact publish dates for:
  - LinkedIn post entries in `research/linkedin-posts/*.md`
  - Video entries in `research/youtube-transcripts/*.md`
- Replace playlist-level source for Katelyn with one direct video URL if available.
- Add one direct YouTube video URL each for Amanda, Val, Brennan, Niko, and Adrie/Adrie Smith if those exist publicly.
