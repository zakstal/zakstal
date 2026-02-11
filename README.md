# Zak Stallings

## Projects (production apps I built and operate)

### fffff.fit — AI clothes try‑on (web + Chrome extension)
Try on clothes (or anything) from **any website** and shop for yourself or family.

- **Stack:** Next.js, TypeScript, Supabase (Postgres), Vercel, Stripe, Chrome Extension
- **AI:** Google Nano Banana via Replicate (virtual try‑on)
- **Demo:** https://trynudyjaksxycuzgcps.supabase.co/storage/v1/object/public/user-images/5f77613f-75c2-455d-9a6a-924c46811f4e/generated/1769986393668.jpg
- **Live:** https://fffff.fit/ *(no active users yet)*

### Aloud Studios — collaborative screenwriting + AI voices
Collaborative screenwriting editor with AI voice generation and versioned screenplay+audio. (Currently a bit broken, but the editor at the URL is live.)

- **Stack:** Next.js, TypeScript, Supabase (Postgres), Vercel, Trigger.dev (jobs), DigitalOcean, Docker
- **Realtime collab:** CRDT (Yjs) + websockets (incl. Supabase websocket hijacking)
- **AI:** ElevenLabs + Hume (pluggable providers)
- **Extras:** PDF→screenplay parsing, AI movie poster generation (Replicate + Flux), full screenplay formatting, undo/redo
- **Live:** https://aloudstudios.net/ *(no active users yet)*
- **Repo:** https://github.com/zakstal/aloud
