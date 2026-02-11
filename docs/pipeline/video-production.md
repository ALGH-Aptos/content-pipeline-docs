# Stage 4: Video Production

## The Most Complex Stage in the Pipeline

This is where a script becomes a video. What sounds simple on the surface — "produce a video from a script" — is actually a **12-step sub-pipeline** that coordinates multiple services, generates dozens of intermediate assets, and uses intelligent optimization to keep production costs manageable.

This stage produces a complete video with:

- A **talking-head presenter** (AI-generated avatar)
- **Supporting b-roll visuals** that appear during key moments
- **Full narration audio** synced to the presenter
- **Smooth transitions** between presenter and visual segments

---

## How It Works

The 12 steps are grouped into four phases.

### Phase 1: Script Preparation

The personalized script needs to be prepared for video production. This involves two things:

**Cleaning the script** — Removing any formatting or structural markers so the system is working with pure narration text.

**Marking visual positions** — The system analyzes the script and identifies the moments where it makes sense to cut away from the presenter and show a supporting visual instead. These positions are marked with descriptions of what the visual should depict.

This is an important creative decision — it determines the visual rhythm of the entire video. The system places **10–13 visual markers** per script, creating a natural flow between the presenter talking directly to camera and supporting visuals that reinforce what's being said.

### Phase 2: Audio & Timing

With the script prepared, the system generates and analyzes the narration audio:

**Narration generation** — The clean script is sent to a text-to-speech service, which produces a high-quality spoken narration using the account's assigned voice. Each account has its own voice, so videos across different accounts sound distinct.

**Precision transcription** — The generated audio is then transcribed back at the word level, producing exact timestamps for every single word spoken. This creates a precise timing map of the entire narration.

**Visual timing alignment** — The visual markers from Phase 1 are matched against the word-level timestamps. Using intelligent matching, the system determines exactly *when* in the audio each visual should appear and for how long.

This gives the system a frame-accurate timeline: it knows exactly which seconds need the presenter on screen and which seconds should show supporting visuals.

### Phase 3: Asset Generation

This is where the actual video assets are created. Two things happen **in parallel** to save time:

**Presenter rendering** — The system renders the talking-head presenter. Rather than rendering the presenter for the entire video duration, the system uses **intelligent rendering optimization** — it only generates presenter footage for the specific moments where the presenter will actually be visible on screen.

This is a critical cost and efficiency optimization. Presenter rendering is one of the most expensive operations in the pipeline, and this approach dramatically reduces both the time and cost required.

**Visual clip generation** — While the presenter is being rendered, the system simultaneously generates the supporting visual clips. Each clip is created from the descriptions placed during script preparation. The system also maintains a **visual asset library** that allows it to reuse previously generated clips when appropriate, avoiding redundant generation.

By running these two processes in parallel, the pipeline eliminates what would otherwise be a significant bottleneck.

### Phase 4: Final Assembly

With all the assets ready — presenter clips, visual clips, and the full narration audio — the system assembles the final video:

1. The presenter clips are placed at their designated positions on the timeline
2. The visual clips fill in the remaining segments
3. The full narration audio is laid over the entire timeline
4. Transitions are applied between segments for a polished look

The result is a seamless video where the presenter appears to naturally alternate between speaking to camera and showing supporting visuals.

---

## Why This Matters

Video production is typically the most expensive and time-consuming part of content creation. This stage handles it entirely automatically — and does so in a way that's **dramatically more cost-efficient** than a naive approach would be.

The key innovations here are:

- **Intelligent rendering optimization** that reduces the most expensive operation to a fraction of its full cost
- **Parallel processing** that eliminates bottleneck wait times
- **Asset reuse** that avoids redundant generation across videos
- **Precision timing** that ensures everything syncs at the frame level

This is a 12-step process coordinating 4+ external services, dozens of intermediate files, and parallel job management — all fully automated.

---

## What Comes Out

The output is a **complete video** with talking-head presenter, supporting visuals, full narration audio, and transitions. This video then moves to Stage 5, where branded visual overlays are added.

<figure style="text-align: center;">
  <img src="../../assets/images/video-production-flow.svg" alt="Video Production Flow" style="width: 100%; height: 600px; border-radius: 12px;">
</figure>

---

<p style="text-align: center; color: gray; font-size: 0.85em;">
ALGH — Content Pipeline Automation
</p>
