# Stage 5: Visual Overlays

## Branded Logo Animations, Timed to the Narration

When a video mentions a specific entity — a cryptocurrency, a company, a platform — this stage detects that mention and overlays an animated logo at exactly the right moment. It's a polished, professional touch that makes the content feel curated rather than auto-generated.

---

## How It Works

This stage runs through a 5-step process.

### Step 1: Script Scanning

The system scans the narration script for **mentions of known entities**. It works from a maintained asset library that maps keywords and aliases to logo assets.

For example, if the script mentions "Ripple" or "XRP" or "$XRP" — all of these resolve to the same entity in the asset library. The scanning is smart enough to handle aliases, abbreviations, and common variations.

To keep the video from feeling cluttered, the system limits how many times a single entity's logo can appear. If an entity is mentioned several times throughout the script, only the key appearances are selected.

### Step 2: Timestamp Matching

Once the entity mentions are identified, the system needs to know exactly *when* in the video they occur. Using word-level audio transcription, each mention is matched to a precise timestamp in the narration.

This ensures the logo appears at the exact moment the entity is mentioned — not a second too early or too late.

### Step 3: Animation Style Selection

Not every logo should animate the same way. The system uses AI to select an **animation style** for each overlay based on the context — what entity is being mentioned, what's being said about it, and the emotional tone of the moment.

Available animation styles include:

- **Fade** — Clean, subtle appearance
- **Swing** — Punchy snap-in with energy
- **Bounce** — Elastic overshoot for playful moments
- **Zoom** — Cinematic scale-in for dramatic reveals
- **Shake** — Impact effect for bold statements

The style is chosen to complement the content, not distract from it.

### Step 4: Overlay Rendering

Each logo animation is rendered individually as a **transparent overlay** — meaning it can be placed on top of the video without blocking the underlying content. The rendering uses a dedicated animation engine that produces broadcast-quality motion graphics.

### Step 5: Video Compositing

The rendered overlays are composited onto the video at their designated timestamps. The result is a video where logos appear naturally alongside the narration, enhancing the professional feel of the content.

---

## The Asset Library

The system maintains a curated library of logo assets organized by category:

- **Cryptocurrencies** — Major tokens and protocols with multiple logo variants
- **Entities** — Companies, platforms, and organizations referenced in content

Each asset entry includes aliases (all the ways it might be mentioned in a script) and one or more logo files. The library is extensible — adding a new entity is as simple as adding an asset folder and updating the index.

---

## Why This Matters

Logo overlays are a common feature in professional social media content, but doing them manually is tedious — you'd need to identify every mention, find the right logo, animate it, time it to the narration, and composite it. For a 30-second video, that's easily an hour of editing work.

This stage does it all automatically, with **frame-accurate timing** and **context-aware animation styles**. It turns every video into something that looks hand-crafted by a professional editor.

---

## What Comes Out

The output is the **video with branded logo overlays** added at all relevant moments. This feeds into Stage 6, where captions are applied as the final enhancement.

<figure style="text-align: center;">
  <img src="../../assets/images/visual-overlays-flow.svg" alt="Visual Overlays Flow" style="width: 100%; height: 500px; border-radius: 12px;">
</figure>

---

<p style="text-align: center; color: gray; font-size: 0.85em;">
ALGH — Content Pipeline Automation
</p>
