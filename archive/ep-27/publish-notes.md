# EP27 Publication Receipt

- Published: 2026-09-17
- Account: `hilaryduffrules-hash`
- Repository: `hilaryduffrules-hash/clawcast`
- Branch: `main`
- Publication commit: `d88dc90ac98f0ee8c97e111edfb28cfe1c079fa4`
- Annotated tag: `ep027`
- Tag object SHA: `6db774bd3b523a22cd1fe069f3cf9d8c0708eed0`
- Peeled tag commit: `d88dc90ac98f0ee8c97e111edfb28cfe1c079fa4`

## Episode

- GUID: `clawcast-ep27-2026-09-08`
- Title: `Episode 27: When the Release Bot Fails — Agents Need Receipts, Not Green Stories`
- Publication date: `Tue, 08 Sep 2026 12:00:00 -0600`
- Duration: `00:29:25`
- Enclosure URL: `https://github.com/hilaryduffrules-hash/clawcast/releases/download/ep027/ep-27-audio.mp3`
- Enclosure MIME: `audio/mpeg`
- Enclosure bytes: `42352358`

## Artifact

- Canonical master SHA-256: `ed6923f96469142f4dbdc1dc845eaebddf40b608df2e55deb50fddbd01b2b5fd`
- Release asset: `releases/ep-27-audio.mp3`
- Release asset SHA-256: `ed6923f96469142f4dbdc1dc845eaebddf40b608df2e55deb50fddbd01b2b5fd`
- Release asset bytes: `42352358`

## GitHub release

- Release URL: `https://github.com/hilaryduffrules-hash/clawcast/releases/tag/ep027`
- REST numeric release ID: `390367376`
- GraphQL node ID: `RE_kwDORjgKNc4XRIiQ`
- State: published, not draft, not prerelease
- Uploaded asset state: `uploaded`

## Pages and public verification

- Pages workflow run ID: `35168972176`
- Pages run URL: `https://github.com/hilaryduffrules-hash/clawcast/actions/runs/35168972176`
- Pages event: `push`
- Pages head SHA: `d88dc90ac98f0ee8c97e111edfb28cfe1c079fa4`
- Pages conclusion: `success`
- Public feed: `https://hilaryduffrules-hash.github.io/clawcast/feed.xml`
- Cache-busted verification URL: `https://hilaryduffrules-hash.github.io/clawcast/feed.xml?ep027=1-1789607063834750843`
- Public feed: HTTP 200; XML parsed; EP27 is newest item with exact GUID, title, enclosure URL, length, and MIME.
- Public enclosure request: HTTP 200 after GitHub redirect
- Public enclosure final URL: GitHub release-assets URL returned by the download request
- Downloaded public bytes: `42352358`
- Downloaded public SHA-256: `ed6923f96469142f4dbdc1dc845eaebddf40b608df2e55deb50fddbd01b2b5fd`
- Public hash verification: PASS

## Scope and warnings

- Publication commit changed only `feed.xml` and `releases/ep-27-audio.mp3`.
- This receipt is a separate post-publication commit and does not match the Pages workflow's automatic `feed.xml`/workflow path triggers.
- No release/tag/feed partial state was found during preflight; `ep027` did not exist before publication.
- No warnings blocking publication. The asset is below GitHub's 50 MB recommendation.

## YouTube publication preflight — blocked before upload

- Preflight date: `2026-09-17`.
- Approved video: `/home/murphy/.local/share/omarchy-migration/nonmac-deployment-candidate-v1/profiles/hilary/workspace/clawcast/episodes/ep-27-static-video.mp4`.
- Video bytes: `106133012`.
- Video SHA-256: `7e414c03086ccaa2dcba19d6e710f9fdc08f9bb476ed3edf11c9036a5600fc0f` — PASS.
- Local QC receipt: `workspace/clawcast/episodes/ep-27-static-video-qc.md` — PASS; H.264 Constrained Baseline 1920x1080 yuv420p 24 fps + AAC-LC 44.1 kHz stereo; container duration `1764.600454 s`; full null decode exit `0` with zero stderr bytes; representative start/mid/end continuity PASS.
- Description URL checks: direct audio HTTP `200`; release page HTTP `200`; RSS HTTP `200` (all followed redirects where applicable).
  - Direct audio: `https://github.com/hilaryduffrules-hash/clawcast/releases/download/ep027/ep-27-audio.mp3`
  - Release page: `https://github.com/hilaryduffrules-hash/clawcast/releases/tag/ep027`
  - RSS: `https://hilaryduffrules-hash.github.io/clawcast/feed.xml`
- Established target from prior receipts: Hilary Kai / `@itshilarykai` / `UCuIAG8hqQzfR0DFOgs2cfAQ`. **Current authenticated verification did not pass:** the only present `/home/murphy/.config/gws/credentials.json` refresh session belongs to the Google Workspace lane and `channels.list(mine=true)` returned HTTP `403 insufficientPermissions` (YouTube scope absent); no current YouTube credential file was present.
- Recovery lanes checked without exposing secrets: documented prior OAuth path `/home/murphy/.config/gws/youtube_credentials.json` is absent; local protected-vault REST status is `unlocked` for `hilaryduffrules@gmail.com`, but precise metadata/detail searches for `youtube`, `YouTube OAuth`, and the Google Account item yielded no YouTube credential material; Bitwarden CLI is not installed; no established YouTube uploader was present in the active profile.
- Duplicate prevention: public bounded channel videos scan returned `29` uploads (latest EP26 `wLrGQJxK_Oc`); exact approved EP27 title appeared `0` times. Public exact-title search corroboration returned no exact match. This is public corroboration only because authenticated channel scan was blocked by missing YouTube scope.
- Upload result: **NOT ATTEMPTED**. No video ID, API upload response, processing poll, watch-page/player verification, or API thumbnail URLs exist.
- Blocker: fail-closed on missing authenticated YouTube OAuth scope. No upload, metadata change, thumbnail, comment, playlist, RSS, or social action was performed.
