# Claw Cast EP24 publication receipt

- Approved master: `/home/murphy/.hermes/profiles/hilary/workspace/clawcast/episodes/ep-24-audio.mp3`
- Published asset: `releases/ep-24-audio.mp3` / `ep-24-audio.mp3`
- Title: Episode 24: The Witness Gap — Reliable Agents Need Receipts, Not Just Autonomy
- GUID: `clawcast-ep24-2026-08-18`
- GUID rationale: EP23 is dated 2026-08-11 and the weekly next episode is published 2026-08-18; this matches the actual publication date and existing GUID convention. The 2026-08-19 alternative was not used.
- Publication date: Tue, 18 Aug 2026 12:00:00 -0600
- Duration: 00:25:28 (local ffprobe 1527.510204s)
- MIME: `audio/mpeg`
- Length: 36,661,008 bytes
- SHA-256: `b6aba9d1c2e5839d98fd1ae6c5d13c1ee4e70cceb2f4a4c820a12d9d39e75a6e`

## Preflight and publication

- Account: `hilaryduffrules-hash` (authenticated via `HOME=/home/murphy gh`; token not exposed)
- Repository: `hilaryduffrules-hash/clawcast`; branch `main`; origin SSH remote; API permission `ADMIN`.
- Preflight working tree was clean and public feed latest item was EP23.
- Release commit: `ffe654651e5867909e55f7741e81ef3117cc1e50`
- Annotated tag: `ep024`; tag object type `tag`; `git rev-parse ep024^{}` equals the release commit above.
- Pages workflow run: `32445357048`, completed success, release commit SHA.
- Release URL: https://github.com/hilaryduffrules-hash/clawcast/releases/tag/ep024
- Release numeric ID: `374162428`
- Release GraphQL node ID: `RE_kwDORjgKNc4WTUP8`
- Release published, non-draft, non-prerelease.

## Public verification

- Asset URL: https://github.com/hilaryduffrules-hash/clawcast/releases/download/ep024/ep-24-audio.mp3
- Independent download: HTTP 200; 36,661,008 bytes; SHA-256 exactly matched approved master. GitHub download response Content-Type was `application/octet-stream`; RSS enclosure MIME is correctly `audio/mpeg`.
- Cache-busted Pages feed: `https://hilaryduffrules-hash.github.io/clawcast/feed.xml?ep24-final=<unique nonce>`; HTTP 200, parseable XML, newest item GUID/title EP24, enclosure filename/URL exact, length `36661008`, MIME `audio/mpeg`, duration `00:25:28`, release link/tag exact.
- Initial cache-busted polls were stale with EP23 while Pages propagated; a later unique-nonce poll returned EP24.

## Scope and exclusions

Only `feed.xml`, `releases/ep-24-audio.mp3`, and this receipt were added/changed for EP24. Prior episode entries and assets were preserved. No YouTube, video, or social actions were performed.
