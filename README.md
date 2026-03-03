# Upskill

> The OnlyFans of tribal knowledge. For the experts who are retiring.

A master electrician retires after 38 years. Everything she knows about wire sizing in
humid climates, which inspectors flag which violations, how to pull conduit through a
wall that wasn't built for it — that knowledge is not on the internet. It lives in her head.
Her employer gets it for free until her last day. After that it's gone.

Upskill gives her a paywall, an AI production crew, and an AR delivery channel.
She uploads one video. AI turns it into a sellable, spatially-anchored training module.
Learners pay to unlock it. She earns while she sleeps.

## The Tier Model

**Free tier** — scrapable information. What you can already find on the internet:
manufacturer specs, code text, YouTube tutorials. Upskill surfaces it, organized by trade.

**Paid tier** — the tribal knowledge you cannot scrape. The expert's 20–40 years of
judgment: what the spec doesn't say, what the inspector actually looks for, the shortcut
that saves 3 hours, the mistake that costs $40K. Delivered live, as AR coaching,
spatially anchored in 3D over your actual work while both your hands are in it.

```
Free:  "NEC 210.52 — kitchen receptacles required every 4 feet along counter wall"
Paid:  "In Honolulu inspections, they measure from the centerline of the outlet box,
        not the faceplate. Flag it now or they'll make you redo the whole run."
        → delivered as an AR overlay while you're standing at the wall, hands in the panel
```

## How It Works

### For the Expert (Creator)

Upload anything — a video of yourself working, a voice note, a PDF you've carried
around for years.

```
Video of master electrician pulling wire through conduit
  → Gemini: extracts steps, wire gauge, code refs, timing from audio + visuals
  → NanoBanana 2: generates character-consistent visual step cards (no film crew)
  → Lyria: narrates each step in professional audio
  → Module published on Upskill behind a paywall
  → Expert earns every time a learner unlocks it
```

No camera? Drop a PDF or type what you know. Gemini reads it, structures it into steps,
NanoBanana illustrates it, Lyria narrates it. **The AI is the production company.**

### For the Learner

Buy a module. Point your phone at your work area (or put on Snap Spectacles).

```
AR overlay: Step 4 anchored in 3D space over your actual work surface
Lyria narrates: "Strip 6 inches — stay outside the box knockout"
Gemini watches your camera: "Good. Now secure with a connector before entering the box."
Ask anything: "What does the inspector actually flag here?" → the expert's real answer
```

The free tier tells you what the code says.
The paid tier tells you what the expert knows — while you're doing the work.

## The Commerce Layer

- Expert sets their price per module unlock or subscription
- Upskill takes 20% — same model as OnlyFans
- Expert keeps 80%: passive income from knowledge that currently earns them nothing
- Modules are locked by default — learner pays to unlock
- AR delivery is the product. The spatial 3D overlay is what they're paying for.

## Why Now

> "We have people retiring who built stadiums. We're trying to figure out how to capture
> that knowledge before it walks out the door." — Gene Hodge, VP Innovation, Mortenson Construction

> "This data sometimes just resides in the heads of experienced employees."
> — Aviad Almagor, VP Technology Innovation, Trimble

- **349,000 skilled worker shortage** right now (Associated Builders & Contractors, Jan 2026)
- **41% of the construction workforce retiring by 2031** (NCCRE)
- The tribal knowledge walks out the door at retirement. Upskill is the last chance to monetize it.

## What Wasn't Possible 6 Months Ago

- **NanoBanana 2**: Character-consistent frames across a full module — a professional
  training video without a film crew. That's new.
- **Gemini long context**: 200-page installation manual + voice notes + tribal knowledge →
  structured steps in one context window. That's new.
- **Lyria + spatial AR**: The expert's knowledge narrated live, anchored to 3D space as
  you work. Not a video. Not a manual. Coaching. That's new.

## Tech Stack

| Layer | Technology |
|---|---|
| Knowledge extraction (video + audio) | Gemini 3.1 (long context, multimodal) |
| Visual step generation | NanoBanana 2 (character consistency) |
| Step narration | Lyria (transformational audio) |
| AR delivery — spatial 3D | World Labs (spatial anchoring) |
| AR overlay — phone | Web canvas + camera feed (free to access) |
| AR overlay — premium | Snap Spectacles (hands-free, both hands on the work) |
| Paywall / Commerce | Stripe |
| Backend | Supabase + Railway (MMCP orchestration) |

## Demo

Coffee. Not electrical panels. Everyone in the room understands pour-over.

**Free tier**: "Here's how pour-over works. Grind ratio 1:15. Bloom 30s. Total pour 3 min."
*(This is scrapable. It's on every coffee blog.)*

**Paid tier**: Upload the barista's video.

1. Gemini: "Found 8 steps — grind, bloom, pour rate, temperature..."
2. NanoBanana 2: visual step cards appear, same character across all 8
3. Lyria narrates step 3: *"Start your bloom — 60g water, 45-second wait"*
4. Point laptop camera at a coffee setup on the table
5. AR overlay anchored in 3D: Step 3 badge floats over the cup. Timer starts.
6. Ask aloud: *"Why does the grind matter so much?"* → the barista's actual answer
7. Pitch: *"She's been doing this for 12 years. That answer? Not on any blog.
   312 subscribers at $4.99. $1,500 this month from knowledge she gives away free at work."*

## Status

Built for the [YC × Google DeepMind Multimodal Frontier Hackathon](https://partiful.com/e/N6DXsxlF6IrHw7AKMeZ8) (March 7, 2026, San Francisco).

Backend infrastructure (MMCP orchestration, Gemini video analysis, WorldLabs spatial anchoring) — operational.
NanoBanana 2 + Lyria + Gemini 3.1 keys received day-of. Stubs ready to swap.

See [SPECTACLES.md](./SPECTACLES.md) for the Snap Spectacles hands-free tier.

---

Built by [VIS INC](https://github.com/ChainMailGlobal) — the same team building AI permit intelligence for the construction industry.
