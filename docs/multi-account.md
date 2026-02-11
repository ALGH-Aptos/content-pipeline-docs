# Multi-Account Scaling

## One Pipeline, Many Voices

The Content Pipeline isn't designed for a single account — it's built from the ground up to support **multiple accounts**, each with its own distinct identity. The same trending topic can produce entirely different videos for different accounts, each one feeling authentically tailored to that account's audience.

---

## How Accounts Are Structured

Each account in the system is defined by a set of configuration files that capture its identity:

| Component | What It Defines |
|-----------|----------------|
| **Account Configuration** | Core metadata — the account's name, platform, and which voice and avatar to use for video production |
| **Personality Profile** | The account's voice and tone — how it speaks, its energy level, vocabulary, and mannerisms |
| **Video Style Guide** | How the account's videos are structured — hook timing, pacing, call-to-action format, and formatting preferences |

Together, these files give the pipeline everything it needs to produce content that feels authentic to each account.

---

## What Changes Per Account

When the pipeline runs for a specific account, several stages adapt to that account's identity:

### Script Personalization
The base script (which is the same regardless of account) gets rewritten to match the account's personality. A formal, analytical account will deliver the same information very differently than a casual, high-energy account.

### Voice
Each account has its own assigned voice for narration. The text-to-speech stage uses the account's specific voice configuration, so every video sounds like *that* account.

### Visual Presenter
Each account has its own AI avatar. The talking-head presenter in the video matches the account's assigned visual identity.

### Output Isolation
Every account has its own run history. Outputs, intermediate files, and metadata are all organized by account — nothing bleeds across accounts.

---

## Adding a New Account

Scaling to a new account is a straightforward process:

1. **Create the account's directory** with the required configuration files
2. **Define the personality** — describe how this account talks, its tone, its mannerisms
3. **Define the video style** — set the pacing, hook format, and structural preferences
4. **Assign a voice and avatar** — configure which voice and presenter to use

Once configured, the account is ready to receive content through the pipeline. No code changes are required — the pipeline reads the account's configuration at runtime and adapts automatically.

---

## Running Across Accounts

The pipeline can process the same topic for multiple accounts sequentially. Each run is independent:

- **Account A** gets the topic → script is personalized in Account A's voice → video produced with Account A's avatar and voice → overlays and captions applied → finished video for Account A
- **Account B** gets the same topic → script is personalized in Account B's voice → video produced with Account B's avatar and voice → overlays and captions applied → finished video for Account B

The base research and script generation only happen once. The personalization, production, and enhancement stages run independently per account.

---

## Why This Matters

Operating multiple social media accounts at scale is a massive operational challenge. Each account needs:

- Consistent voice and personality across every piece of content
- Unique delivery so accounts don't feel like copies of each other
- Independent output management and tracking
- The ability to cover the same topics without producing duplicate content

Doing this manually would require a dedicated content creator for each account. This system handles it through configuration — **each new account is a configuration file, not a new hire**.

---

!!! info "Placeholder for Diagram"
    A future revision will include a visual showing how a single topic flows through the pipeline for multiple accounts in parallel, producing distinct outputs.

---

<p style="text-align: center; color: gray; font-size: 0.85em;">
ALGH — Content Pipeline Automation
</p>
