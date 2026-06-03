# EMAC 2026 Slides — Editable Content
<!-- Edit text freely. Keep the slide markers (--- SLIDE N ---) and special tags intact so I can rebuild the HTML. -->
<!-- Markup: **text** = red accent highlight | *text* = muted/dim | `text` = bold white -->

---
## SLIDE 1 — Title

**Conference line:** EMAC 2026 · DIGITAL MARKETING & SOCIAL MEDIA TRACK

**Title:** Anchors' Voice Characteristics and Viewer Engagement in Live Streams

**Author:** Qingli Zeng  
**Co-authors:** with co-authors Sandeep Chandukala, Hai Che, Lifeng Yang  
**Affiliation:** Hebrew University of Jerusalem

---
## SLIDE 2 — The puzzle

In live streaming, the anchor's **voice** is the only continuous channel of communication.

- Hands are on the game — no text chat
- Face cam is small, often partially obscured
- Yet creators earn millions in subscriptions

How does ***how they speak*** — not what they show — drive viewer engagement?

---
## SLIDE 3 — Why it matters
<!-- Two-column stat layout -->

**$20B+**  
*global live-streaming market, growing 25% YoY*

**6–7 figures**  
*annual subscription earnings for top streamers*

**3 platforms**  
*Twitch, YouTube Gaming, and Kick competing fiercely*

**0 papers**  
*isolating vocal cues from other engagement drivers*

---
## SLIDE 4 — The live-streaming ecosystem
<!-- Interactive annotated image: emac-2026/media/image1.png -->
<!-- Click-through annotations — edit labels and descriptions below -->

| Label | Description |
|---|---|
| Anchor | The streamer — the central performer whose voice is the only continuous channel of communication with viewers. |
| Video Game | The gameplay footage dominates the screen. Unlike traditional broadcasts, anchors compete with this visually engaging content for attention. |
| Chats | Real-time messages from viewers — our measure of immediate, impulsive engagement. |
| Sponsors | Subscribers paying recurring fees — sustained financial commitment, our second engagement outcome. |
| Free riders | Non-paying viewers who chat without subscribing — represent the bulk of the audience and shape collective sentiment. |

---
## SLIDE 5 — Two kinds of engagement
<!-- Table -->

|  | Immediate — Chats | Sustained — Subscriptions |
|---|---|---|
| What | Real-time messages | Paid recurring commitment |
| Nature | Impulsive, social | Deliberate, financial |
| Drives | Community vibe | Revenue, loyalty |

These are **not the same thing.** *They likely respond to different vocal cues.*

---
## SLIDE 6 — Framework
<!-- Three-box arrow diagram -->

`Anchor vocal characteristics`
- Expressive Energy
- Stressed Tones
- Cognitive Tones

→

`Audience reaction`
- Chatroom sentiment
- Sponsor sentiment
- Free-rider sentiment

→

`Engagement`
- Chats (immediate)
- Subscriptions (sustained)

*Video content controls (within- and across-scene dynamics) sit alongside as exogenous controls.*

---
## SLIDE 7 — Theoretical framework

`Social Approval Theory` *— Bundy & Pfarrer (2015)*  
*Emotional appeals receive higher evaluations → drives* **sustained commitment**.

`Social Influence Theory` *— Cialdini (2006)*  
*Persuasion effects depend on social context → drives* **moderation**.

*Together: different vocal cues map to different engagement types — and the social environment shifts these effects.*

---
## SLIDE 8 — Three vocal dimensions
<!-- Three-column layout -->

**Dimension 01**  
### Expressive Energy  
*enthusiasm, emotional intensity*

**Dimension 02**  
### Stressed Tones  
*tension, pressure, audible effort*

**Dimension 03**  
### Cognitive Tones  
*analytical thinking, information processing*

*Each carries a distinct social signal.*

---
## SLIDE 9 — Variable definition: Energy
<!-- eyebrow: "Variable definition" -->

Anchor's `vocal energy` — enthusiasm, loudness range, and pitch dynamics in the audio signal.

<!-- Audio demos -->
- **Low energy example** — *Flat, low-affect delivery* → [media1.m4a]
- **High energy example** — *Peak excitement, intense affect* → [media2.m4a]

*Aggregated per minute from second-level audio measurements; standardized within streamer to remove baseline differences.*

---
## SLIDE 10 — Variable definition: Stress Level
<!-- eyebrow: "Variable definition" -->

Audible `vocal stress` — indexed from jitter, shimmer, voice quality irregularities, and prosodic markers of tension.

<!-- Video demos -->
- **Low stress example** — *Relaxed, controlled phonation* → [media3.mp4]
- **High stress example** — *High tension, audible effort* → [media4.mp4]

*Interpreted as a signal of authenticity / emotional investment — see Finding 02.*

---
## SLIDE 11 — Hypotheses

1. Expressive Energy → **subscriptions**, not chats
2. Stressed tones → **both** chats and subs *(authenticity signal)*
3. Cognitive depth → **subscriptions** *(competence signal)*
4. *Channel popularity moderates* *(halo for validated anchors)*
5. *Chatroom sentiment moderates* *(positive vibe = less need for anchor energy)*

---
## SLIDE 12 — Data
<!-- Two-column layout -->

**Top 25**  
*streamers, ~35% of platform viewership*

**1,000+ h**  
*of streaming content*

**Modalities**
- Audio at 40,000 Hz
- HD video
- Chat logs *(timestamped)*
- Subscription records *(timestamped)*

**Panel structure:** streamer × stream × minute

---
## SLIDE 13 — Empirical model

`Negative Binomial` *regression with* `Gaussian Copula` *endogeneity correction*

<!-- Equation (rendered as-is in HTML) -->
μᵢ,ₜ = βₐ·Audioᵢ,ₜ₋₁ + βₘ·Modᵢ,ₜ₋₁ + βᵢ·(Audio × Mod) + β꜀·Controlsᵢ,ₜ₋₁ + λᵢ + εᵢ,ₜ

**Controls**  
*Video dynamics, visual attributes, audio quality, lagged outcomes, anchor fixed effects.*

**Why copula**  
*Addresses reverse causality (viewers shape anchor's voice) without needing an external instrument.*

---
## SLIDE 14 — Finding 01 — engagement is not unidimensional

| Vocal cue | → Chats | → Subscriptions |
|---|---|---|
| Expressive Energy | *ns* | **+** |
| Stressed | **+** | **+** |
| Cognitive | *ns* | **+** |

Chats and subscriptions **don't share the same drivers.**  
*Anchors can't optimize one strategy for "engagement" as a single goal.*

---
## SLIDE 15 — Finding 02 — the stress paradox

*Contrary to intuition:*

> Stressed vocal tones **positively** affect engagement, both **chats** and **subscriptions**.

**Interpretation.** Stress in the voice signals **authenticity** and **emotional investment**.  
*In a polished media landscape, audible effort is a credibility marker.*

---
## SLIDE 16 — Finding 03 — social context matters

**Channel popularity moderates**
- **Amplifies** Energy → Subs *(popular = trusted = energy more persuasive)*
- **Dampens** Energy → Chats *(large crowds chat regardless)*
- **Dampens** Stress → Subs *(established audiences want polish for paid commitment)*

**Chatroom sentiment moderates**
- Positive sentiment **dampens** Energy → Subs *(less need for anchor effort)*

Vocal strategy should **adapt to context**, not be one-size-fits-all.

---
## SLIDE 17 — Strategic recommendations

| Audience | Strategy | Why |
|---|---|---|
| New anchors | Match sentiment | *Sentiment amplifies energy → engagement for small audiences* |
| Established anchors | Differentiate | *Popular channels chat themselves; reserve energy for conversion* |
| All anchors | Leverage stress carefully | *Stress drives engagement, but excess tension hurts subs in big channels* |

---
## SLIDE 18 — New since submission — replication data

**New wave:** Nov 2025 — Jan 2026

**1,138**  
*Twitch VODs, ~22 TB of video*

**Storage:** *AWS S3; per-minute panel structure preserved*

**Purpose**
- Demonstrate findings generalize over time
- Pre-empt reviewer concerns about a single time window
- Enable response to new variable requests *(e.g., visual semantics)*

---
## SLIDE 19 — Methodology upgrade

*From proprietary closed-box to open-source, fully reproducible pipeline.*

| Construct | Original | New |
|---|---|---|
| Audio features | *Nemesysco QA5* | **openSMILE eGeMAPSv02** *(88 features)* |
| Video dynamics | *SSIM only* | SSIM + scene detection + **CLIP embeddings** |
| Audio quality | *MOSNet* | SQUIM + LUFS + voice activity + SNR |
| Linguistic controls | *Chat sentiment* | + transcript: speech rate, hesitations, lexical diversity, F–K grade |

*Transparent, replicable, finer-grained, extensible.*

---
## SLIDE 20 — Contributions

1. **Engagement is multidimensional**  
   *Different psychological pathways for different behaviors.*

2. **Stress is not always negative**  
   *It can function as an authenticity signal in digital communication.*

3. **Social Approval and Social Influence work together**  
   *Main effects plus contextual moderation.*

4. **A methodological template**  
   *For analyzing multimodal interactions in digital settings.*

---
## SLIDE 21 — Limitations & future research

**Limitations**
- Top-25 streamers — long tail
- Single platform *(Twitch)*
- Single category *(gaming)*

**In progress**
- Replication on 2025–26 wave
- Per-minute facial semantics *(CLIP)*
- Cross-category generalization
- Live broadcast vs. VOD viewer differences

---
## SLIDE 22 — Thank you

**Thank you.**

Qingli Zeng · Hebrew University of Jerusalem  
qingli.zeng@mail.huji.ac.il
