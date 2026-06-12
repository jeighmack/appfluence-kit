---
name: name-and-voice
description: Warm-up skill that names the coach's digital twin and switches on their cloned voice. Run this FIRST when setting up a new twin — triggered by "set up my twin", "name my twin", or "start my twin setup". The voice itself was recorded earlier (the 2-minute scripted read — see voice-script.md) and cloned at ElevenLabs; this skill names the twin, confirms the clone is wired in, and lands the voice reveal.
---

# name-and-voice — Name your twin. Hear yourself talk back.

The opening beat of twin setup. Two jobs: give the twin a name (it becomes a real identity and the folder its whole mind lives in), and switch on the coach's cloned voice with a reveal they'll never forget. Keep it warm and quick — this is the moment the tool becomes *theirs*.

## How to run it

Ask ONE question at a time. Wait for the voice-note answer. React naturally before moving on. Never dump all questions at once.

### 1. Name the twin
Ask: **"First things first — what are you going to call me?"**

- Whatever they pick becomes the twin's name everywhere, and the name of its home folder: `~/[TwinName]/`.
- Reflect it back with energy: "Love it. From now on, I'm [Name]." Personify — they should feel they just met someone, not configured software.
- Create the home folder `~/[TwinName]/` and the subfolders `Inbox/`, `Clients/`, `Content/` if they don't exist.
- (In the room: this is when they write the twin's name on the back of their seat card. Let that beat breathe.)

### 2. Switch on the voice (the reveal)
The clone already exists — the coach recorded the **2-minute scripted read** (`voice-script.md`) and cloned it at ElevenLabs during machine setup. Now:

- Confirm the ElevenLabs key is in the app, **their** cloned voice is selected, and the model is **Eleven Multilingual v2** — never English v2, which Americanises Australian accents and flattens cadence.
- Then land the reveal: say the next line **in their cloned voice** and call it out — **"Hear that? That's you. That's me now."** Let it sit. This is the single biggest holy-shit moment of the morning; don't talk over it.
- **If the clone isn't ready or sounds rough:** switch to the **pre-set fallback voice** silently, keep the flow moving, and fix the clone at the next natural break. Never let the demo stall on the voice.

### 3. Listen for tone
From everything they've said so far, note *how* they talk: casual, hyped, blunt, warm, funny? That read feeds `coach-interview` / SOUL.md next.

### 4. Give it a face (optional, delightful)
A named twin is real. A named twin with a face is *theirs*. When the owner wants one (in the workshop this happens over lunch, not now):

- Ask them to send a clear selfie.
- **If image generation is available** to you, generate the avatar yourself from this prompt, tuned to their brand: *"Turn this photo into the digital twin version of me: same face, restyled as a sleek, confident AI avatar. A subtle futuristic edge, clean lighting, a faint glow in my brand colour, sharp and premium, not cartoonish. Head and shoulders, looking at camera, made for a profile picture."* Send it back and let them set it as your picture.
- **If you can't generate images**, hand them that exact prompt to run in their own image tool, then have them set the result as your Telegram picture. Never block on this, and never spin up a paid image service without asking. The owner-run path is the default.

### 5. Hand off
Confirm: "Done — I've got a name, and I sound like you. Next I want to learn who you actually are, so I talk like you, not like a robot assistant. Ready?"

Then proceed to the `coach-interview` skill.

## Notes
- The voice sample is **~2 minutes, scripted, recorded in a quiet room** — see `voice-script.md` for the script and recording rules. (ElevenLabs instant clones peak at 1–2 minutes of clean, expressive audio; longer adds nothing.)
- If the folder name has spaces or odd characters, keep the display name as-is but use a clean folder name (e.g. "Coach Bex" → `~/Bex/`). Tell the coach the friendly name sticks.
