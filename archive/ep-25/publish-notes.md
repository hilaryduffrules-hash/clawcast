# Claw Cast EP25 publication receipt

- Approved master: `/home/murphy/.hermes/profiles/hilary/workspace/clawcast/episodes/ep-25-audio.mp3`
- Published asset: `releases/ep-25-audio.mp3` / `ep-25-audio.mp3`
- Title: Episode 25: The Retry Is the Attack Surface — When Agents Repeat the Wrong Thing
- GUID: `clawcast-ep25-2026-08-25`
- Publication date: Tue, 25 Aug 2026 12:00:00 -0600
- Duration: 00:31:38 (local ffprobe 1898.396735s)
- MIME: `audio/mpeg`
- Length: 45,562,324 bytes
- SHA-256: `efa2553398358cef22bdffbcec7c67db7ea6f107f811769ecafc7ecbedf93c73`

## Preflight and publication

- Account: `hilaryduffrules-hash` (authenticated via `HOME=/home/murphy gh`; token not exposed)
- Repository: `hilaryduffrules-hash/clawcast`; branch `main`; origin SSH remote; API permission `ADMIN`.
- Preflight working tree was clean; latest local/remote episode was EP24 (`df5c44f`).
- Release commit: `ed379a5e76f62ce4cafc8f52402a0727d16f6ce6`
- Annotated tag: `ep025`; tag object type `tag`; `git rev-parse ep025^{}` equals the release commit above.
- Release URL: https://github.com/hilaryduffrules-hash/clawcast/releases/tag/ep025
- Release numeric ID: `377284728`
- Release GraphQL node ID: `RE_kwDORjgKNc4WfOh4`
- Release published, non-draft, non-prerelease; asset state `uploaded`, exact size and GitHub asset digest match.

## Public verification

- Asset URL: https://github.com/hilaryduffrules-hash/clawcast/releases/download/ep025/ep-25-audio.mp3
- Independent download on 2026-08-26: HTTP 200; 45,562,324 bytes; SHA-256 exactly matched approved master. GitHub download response Content-Type was `application/octet-stream`; RSS enclosure MIME is `audio/mpeg`.
- Initial cache-busted Pages feed polls on 2026-08-26: HTTP 200 but all 12 bounded polls remained stale at EP24; EP25 GUID/title/enclosure were not observed. The workflow had only a broad `push` trigger and no `workflow_dispatch`; the empty follow-up trigger commit was not a durable recovery mechanism.
- Durable workflow fix commit: `7838b19d06494eaf6852642d928293ecefdce198` (restrict push trigger to `feed.xml` and workflow changes; add `workflow_dispatch`). Pages push run `32993039659` and recovery dispatch run `32993287332` completed successfully. Cache-busted public feed verification: HTTP 200, XML parsed, newest GUID `clawcast-ep25-2026-08-25`, exact title and enclosure URL/length/type observed. Enclosure independently returned HTTP 200; downloaded 45,562,324 bytes and SHA-256 `efa2553398358cef22bdffbcec7c67db7ea6f107f811769ecafc7ecbedf93c73`, matching the approved master.

## Scope and exclusions

Only `feed.xml`, `releases/ep-25-audio.mp3`, and this receipt were changed for EP25, plus one empty Pages-trigger commit (`e923009`) after the release commit. Prior episode entries/assets were preserved. No YouTube, video, or social actions were performed.
