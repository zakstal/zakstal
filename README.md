# Zak Stallings

## Projects (production apps I built and operate)

### 👕✨ <img src="https://fffff.fit/favicon.ico" width="20" height="20" alt="FIT logo" /> fffff.fit — AI virtual try‑on (web + Chrome extension)
AI-powered try‑on for clothes (or *anything*) from **any website** — shop for yourself or family and share results for quick feedback.

- **Stack:** Next.js, TypeScript, Supabase (Postgres), Vercel, Stripe, Chrome Extension
- **AI:** Google Nano Banana (Replicate) for virtual try‑on generation
- **Demo image (me trying on a tent):** https://trynudyjaksxycuzgcps.supabase.co/storage/v1/object/public/user-images/5f77613f-75c2-455d-9a6a-924c46811f4e/generated/1769986393668.jpg
- **Live:** https://fffff.fit/ *(no active users yet)*

### 🎬🗣️ <img src="https://aloudstudios.net/favicon.ico" width="20" height="20" alt="Aloud logo" /> Aloud Studios — collaborative screenwriting + AI voices
A real-time collaborative screenplay editor that can generate voice audio for your script and keep screenplay text **versioned alongside audio**. *(Currently a bit broken, but the editor at the URL is live.)*

- **Stack:** Next.js, TypeScript, Supabase (Postgres), Vercel, Trigger.dev (jobs), DigitalOcean, Docker
- **Realtime collab:** CRDT (Yjs) + websockets (incl. Supabase websocket hijacking)
- **AI voices:** ElevenLabs + Hume (provider-pluggable)
- **Extras:** PDF→screenplay parsing, AI poster generation (Replicate + Flux), proper screenplay formatting, full undo/redo
- **Live:** https://aloudstudios.net/ *(no active users yet)*
- **Repo:** https://github.com/zakstal/aloud
