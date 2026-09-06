# Claw Cast EP26 publication receipt

- Approved/canonical master: `/home/murphy/.hermes/profiles/hilary/workspace/clawcast/episodes/ep-26-audio.mp3`
- Published asset: `releases/ep-26-audio.mp3` / `ep-26-audio.mp3`
- Title: Episode 26: The Verification Loop — When Systems Certify Their Own Blind Spots
- GUID: `clawcast-ep26-2026-09-01`
- Publication date: Tue, 01 Sep 2026 12:00:00 -0600
- Duration: 00:38:54 (2334.354286s)
- MIME: `audio/mpeg`
- Length: 56,025,266 bytes
- SHA-256: `33fd907e809e1900b2d7afcf82db651e023f6df45eead84b66b672a1ed13a41d`

## Preflight and publication

- Retrieval/verification date: 2026-09-06 UTC.
- Account: `hilaryduffrules-hash` via `HOME=/home/murphy gh`; token not exposed.
- Repository: `hilaryduffrules-hash/clawcast`; branch `main`; API permission `ADMIN`; working tree clean before publication.
- Master provenance: QC and production notes identify `episodes/ep-26-audio.mp3` as the 192 kbps stereo NotebookLM production master; local SHA, size, ffprobe metadata, and full ffmpeg null decode were rechecked before write (decode exit 0, stderr 0 bytes).
- Release commit: `76024598548157a01a6a017a06f0f762aec050bd`.
- Annotated tag: `ep026`; tag object `80b66d171009b318e4a23bca25f551639ac1792b`; object type `tag`; peeled commit `76024598548157a01a6a017a06f0f762aec050bd`; remote tag confirmed.
- Release numeric ID: `383433583`.
- Release GraphQL node ID: `RE_kwDORjgKNc4W2rtv`.
- Release URL: https://github.com/hilaryduffrules-hash/clawcast/releases/tag/ep026
- Release state: published, non-draft, non-prerelease.
- Release asset: `ep-26-audio.mp3`, uploaded, 56,025,266 bytes, GitHub digest `sha256:33fd907e809e1900b2d7afcf82db651e023f6df45eead84b66b672a1ed13a41d`.
- GitHub warned that the repository copy is 53.43 MiB, above the recommended 50.00 MB; publication succeeded and the canonical master was preserved unchanged.

## Pages and public verification

- Pages workflow run: `34005655753` — completed successfully; https://github.com/hilaryduffrules-hash/clawcast/actions/runs/34005655753 (push-triggered run for the release commit).
- A manually dispatched duplicate run `34005670661` was also initiated; the push-triggered run above completed successfully and was used for verification.
- Cache-busted feed check: `https://hilaryduffrules-hash.github.io/clawcast/feed.xml?ep26verify=20260906-0209` returned HTTP 200, `application/xml`, and parseable XML. EP26 was newest: GUID `clawcast-ep26-2026-09-01`, exact title, pubDate, enclosure URL, length `56025266`, and type `audio/mpeg`.
- Public asset URL: https://github.com/hilaryduffrules-hash/clawcast/releases/download/ep026/ep-26-audio.mp3
- Independent asset download on 2026-09-06 UTC: HTTP 200 after GitHub's redirect; final response `application/octet-stream`; 56,025,266 bytes; SHA-256 exactly matched the canonical master. The redirect/content type differs from the RSS declaration as expected for GitHub release downloads.

## Scope and exclusions

The release commit changed only `feed.xml` and `releases/ep-26-audio.mp3`; prior feed items/assets were preserved. This receipt is the only subsequent archive change. No video, YouTube, or social actions were performed.


## YouTube static-cover publication (2026-09-06 UTC)

- Authorization: Murphy explicitly approved EP26 static-cover video creation and public YouTube upload in the active thread; no custom thumbnail, comments, social posts, metadata extras, or additional uploads.
- Established cover provenance: `/home/murphy/.hermes/profiles/hilary/workspace/clawcast/episodes/ep-24-static-cover.png`, prior accepted EP25 static-cover source; 1920x1080 RGB PNG; SHA-256 `99e698d0a3dbb2196e894d9078912ab672ccfa8e723dae08b6a9772137fdf740`. Visual inspection: readable “THE CLAW CAST / Bitcoin. Nostr. No Noise.”, non-black Bitcoin/claw artwork, 16:9, no corruption.
- Approved audio: `/home/murphy/clawcast/releases/ep-26-audio.mp3`; bytes 56,025,266; SHA-256 `33fd907e809e1900b2d7afcf82db651e023f6df45eead84b66b672a1ed13a41d`; source runtime 2334.354286 s.
- Render command: `ffmpeg -y -loglevel error -loop 1 -framerate 24 -i ep-24-static-cover.png -i /home/murphy/clawcast/releases/ep-26-audio.mp3 -map 0:v:0 -map 1:a:0 -t 2334.354286 -c:v libx264 -preset ultrafast -tune stillimage -crf 23 -pix_fmt yuv420p -r 24 -vf scale=1920:1080:force_original_aspect_ratio=decrease,pad=1920:1080:(ow-iw)/2:(oh-ih)/2:black,format=yuv420p -c:a aac -b:a 192k -ar 44100 -ac 2 -movflags +faststart ep-26-static-video.mp4`.
- Output: `/home/murphy/.hermes/profiles/hilary/workspace/clawcast/episodes/ep-26-static-video.mp4`; bytes 142826690; SHA-256 `ff2c2958f52be79a02d3896bd5eea4dab9c20618b8748139ed11e9cb42aadffd`. ffprobe: H.264 1920x1080 yuv420p 24 fps; AAC-LC 44100 Hz stereo; container 2334.375000 s; audio 2334.325011 s; container delta +0.020714 s; audio delta -0.029275 s. Full decode exit 0; stderr 0 bytes.
- Representative frames: start `f50529dfaf884e09b4381368a462e7a7c10c6ac82a3c336841f1b2ceb9de3209`, midpoint `93be726da47b86bdc3016650e65499e3b3fc23214cc00fcf4268ebf4caa24e9f`, near-end `13b0ed3fad55f23dcde0c9f29a9276c7a03068b14e94206cbe7ddf0571e4ca76`; visual inspection found the same established cover at all positions.
- OAuth preflight: `channels.list(mine=true)` returned channel ID `UCuIAG8hqQzfR0DFOgs2cfAQ`, title `Hilary Kai`, handle `@itshilarykai`, privacy `public`. Exact-title duplicate search completed before upload; none found. Verified audio/RSS URLs HTTP 200 before write.
- Upload: exactly one public `videos.insert`; exact title `Episode 26: The Verification Loop — When Systems Certify Their Own Blind Spots`; video ID `wLrGQJxK_Oc`; watch URL https://www.youtube.com/watch?v=wLrGQJxK_Oc.
- Processing polls: 10 states; initial uploaded/processing/P0D, duration appeared at poll 3 as PT38M55S, final `uploadStatus=processed`, `privacyStatus=public`, `processingStatus=succeeded`, duration `PT38M55S`. YouTube whole-second rounding is within local runtime tolerance.
- Independent public verification: watch HTTP 200; ID/title markers matched; player video ID `wLrGQJxK_Oc`, title matched, channel ID `UCuIAG8hqQzfR0DFOgs2cfAQ`, length `2334` s, playability `OK`, embed allowed `True`, adaptive formats 7, muxed formats 0.
- Thumbnail probes: default, medium, and high API-provided URLs each returned HTTP 404 / image/jpeg 1097 bytes at verification time; recorded as delayed thumbnail availability. No custom thumbnail was set.
- Evidence files: `episodes/ep-26-static-video-ffprobe.json`, `episodes/ep-26-static-video-decode.stderr`, `episodes/ep-26-static-video-sha256.txt`, `episodes/ep-26-youtube-api-receipt.json`, `episodes/ep-26-youtube-verification.json`.
- Scope: this receipt update only; no RSS/Pages changes and no unrelated repository files.
