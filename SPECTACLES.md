# Upskill × Snap Spectacles

> Hands-free AR coaching from the expert who's retiring. Both hands on the work.

The master plumber can't hold your hand on every job. But she can coach you through
Spectacles — step by step, spatially anchored in 3D over your actual work surface,
while both your hands are in the wall.

## Why Spectacles Is the Right Delivery Device for This

Phone AR works. But you're holding the phone.

Trades work requires both hands. You can't hold a phone and pull wire at the same time.
You can't look at a screen while your hands are in a wet wall joint.

Spectacles fixes that. The coaching is in your field of view. Both hands are free.
The expert's knowledge is delivered exactly where and when you need it — while you're doing the work.

## The Tier Structure

| Tier | Device | AR Delivery | Price |
|---|---|---|---|
| Free | Any | Scrapable info, general how-tos | Free |
| Standard | Phone | Canvas AR overlay, one hand | $4.99–$9.99 / unlock |
| Premium | Snap Spectacles | Spatial 3D, hands-free, voice Q&A | $14.99–$29.99 / unlock |

The knowledge is the same. The delivery is different.
Spectacles earns the premium because it unlocks work that physically requires both hands.

## Creator → Learner Flow

Expert creates once (no Spectacles required to create):

```
Expert uploads video (phone, laptop, or just text/PDF)
  → Gemini extracts steps + timing + tribal knowledge from audio + visuals
  → NanoBanana 2 generates character-consistent visual step cards
  → Lyria narrates each step in professional audio
  → Module published with Standard + Spectacles tier pricing
```

Learner buys Spectacles tier:

```
Step cards render as Snap Lenses in field of view
Lyria narrates in-ear — hands free, head up
Gemini watches camera feed: real-time coaching ("that joint needs more flux")
World Labs spatially anchors each step to the actual work surface
Voice Q&A: "What does the inspector actually look for here?" → expert's real answer
```

## Snap Platform Integration

| Feature | Implementation |
|---|---|
| Step overlays | Snap Lens / Camera Kit (same codebase as phone canvas tier) |
| Spatial anchoring | World Labs 3D — steps anchored to physical surfaces |
| Real-time coaching | Gemini multimodal watching camera feed via Snap |
| Voice Q&A | Gemini audio — ask the expert anything, answered from their tribal knowledge |
| Narration | Lyria — professional audio, plays hands-free in-ear |
| Commerce | Stripe paywall — Spectacles tier unlocked separately |

## The Tribal Knowledge Angle

The free tier is what you can scrape: code text, manufacturer specs, YouTube tutorials.

The Spectacles tier is what you cannot scrape: the expert's 20–40 years of judgment,
delivered spatially, in 3D, over your actual work, while your hands are in it.

```
Free:   "ADA grab bar height: 33–36 inches AFF"
Paid:   "Honolulu inspectors measure from the centerline of the blocking, not the
         finished wall surface. Add a blocking note to your submittal drawings.
         I've seen this fail final inspection 11 times."
         → delivered as a Snap Lens anchored to the wall while you're installing
```

## Use Cases Where Spectacles Is the Only Option

- Electrical panel work (both hands in live adjacent circuits)
- Plumbing joint work (both hands holding pipe + torch)
- HVAC refrigerant line connections (both hands on fittings)
- Welding (helmet down, both hands on torch + workpiece)
- Surgical and medical procedures (both hands sterile, in the field)
- Restaurant prep techniques (both hands on food + tools)

In every case: the expert's coaching needs to be in your field of view,
not on a screen you have to look away from.

## Built For

Snap Spectacles Commerce + AR Hackathon, 2026.

Stack: Snap Lens Studio (step overlays) + World Labs 3D (spatial anchoring)
+ Gemini 3.1 (coaching) + Lyria (narration) + NanoBanana 2 (visual steps) + Stripe (paywall).

See the main [Upskill README](./README.md) for the full platform.
