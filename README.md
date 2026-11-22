# FreeFrame Studio

Free AI creative studio — an OpenArt / tezu-style toolkit that runs on free APIs and your own device. No sign-up, no credits.

**Live:** https://jaykk99.github.io/freeframe-studio/

| Tool | What it does | Runs on |
|---|---|---|
| Create | Text-to-image, 20 styles, shot/lighting/lens builder, ✨ AI prompt enhance, 🎲 surprise, seed lock, up to 2 characters per scene, prompt history | Pollinations (Flux) |
| Remix / Variations | Image-to-image "edit with words", new-seed variations | Pollinations |
| Characters | Turnaround reference sheets with locked seed, portrait, edit/regenerate, ✨ invent a character | Pollinations |
| Editor | AI background removal + replace (solid/gradient/blur), 2×/4× upscale, crop, rotate/flip, 9 filters, 8 adjustments, text, undo, PNG/JPG/WebP | Your device (@imgly/background-removal) |
| Video | ✨ 3D parallax from an AI depth map, 8 camera moves, 6 looks, captions, music, frame-perfect MP4 | Your device (Depth Anything via transformers.js, WebGL, WebCodecs + mp4-muxer) |
| Story | AI writes the shots, generates each scene, cuts a video with crossfades, captions and music | Pollinations + your device |
| Library | Favourites, filters, search, saved videos | IndexedDB on your device |

Pro ($19 one-time at Monico Labs): 2K exports (2048px long edge) + commercial-use licence. Unlock in the app with your Monico access code — free stays free at 1024px, personal use.

Free-tier limits: Pollinations allows 1 image and 1 AI text reply every 45 s per visitor — FreeFrame queues jobs and shows a countdown. Images carry a small pollinations.ai watermark.
