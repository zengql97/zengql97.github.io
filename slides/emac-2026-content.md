# EMAC 2026 Slides — 20-Minute Presentation Script
<!-- Edit text freely. Keep the slide markers (--- SLIDE N ---) and special tags intact so I can rebuild the HTML. -->
<!-- Markup: **text** = red accent highlight | *text* = muted/dim | `text` = bold white -->
<!-- Target length: ~46 sec/slide × 26 slides = ~20 min -->

---
## SLIDE 1 — Title

**Conference line:** EMAC 2026 · DIGITAL MARKETING & SOCIAL MEDIA TRACK

**Title:** Anchors' Voice Characteristics and Viewer Engagement in Live Streams

**Author:** Qingli Zeng
**Co-authors:** with co-authors Sandeep Chandukala, Hai Che, Lifeng Yang
**Affiliation:** Hebrew University of Jerusalem

<!-- SPEAKER NOTES: 30 sec hello & framing. "Today I'll show you how the way streamers SPEAK — not what's on their screen — drives two different kinds of viewer engagement, and how those effects depend on context." -->

---
## SLIDE 2 — The puzzle

In live streaming, the anchor's **voice** is the only continuous channel of communication.

- Hands are on the game — no text chat
- Face cam is small, often partially obscured
- Yet creators earn millions in subscriptions

How does ***how they speak*** — not what they show — drive viewer engagement?

<!-- SPEAKER NOTES (~60 sec): Set up the setting. Anchors compete with gameplay for the screen, can't gesture, can't type. The voice is the ONLY persistent persuasive channel. So it's a clean test bed for vocal influence in a high-stakes market. -->

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

<!-- SPEAKER NOTES (~30 sec): Big market, high stakes, no academic answer yet. -->

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

<!-- SPEAKER NOTES (~90 sec): Click through the 5 annotations live. "Notice the face cam is tiny — the anchor competes for visual attention with gameplay. The chat panel is split between paying subscribers ('sponsors' in our terminology) and non-paying viewers ('free riders'). Both groups type messages, but only one is sustained financial commitment." -->

---
## SLIDE 5 — Two kinds of engagement
<!-- Table -->

|  | Immediate — Chats | Sustained — Subscriptions |
|---|---|---|
| What | Real-time messages | Paid recurring commitment |
| Nature | Impulsive, social | Deliberate, financial |
| Drives | Community vibe | Revenue, loyalty |

These are **not the same thing.** *They likely respond to different vocal cues.*

<!-- SPEAKER NOTES (~45 sec): Central distinction. Most prior work bundles "engagement" into one variable. We separate them. The question is whether the same vocal cues drive both, or different cues drive each. -->

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

<!-- SPEAKER NOTES (~45 sec): Conceptual flow. Voice features → audience reaction → engagement. Video content is a control, not a cause. -->

---
## SLIDE 7 — Theoretical framework

`Social Approval Theory` *— Bundy & Pfarrer (2015)*
*Emotional appeals receive higher evaluations → drives* **sustained commitment**.

`Social Influence Theory` *— Cialdini (2006)*
*Persuasion effects depend on social context → drives* **moderation**.

*Together: different vocal cues map to different engagement types — and the social environment shifts these effects.*

<!-- SPEAKER NOTES (~60 sec): Two theoretical traditions. Approval Theory explains WHY emotional vocal cues should drive paid commitment — they trigger positive evaluation. Influence Theory explains WHY effects vary by context — same cue lands differently in different social environments. -->

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

<!-- SPEAKER NOTES (~30 sec): Three theoretically grounded dimensions. Energy = enthusiasm. Stress = audible effort/tension. Cognitive = analytical depth. -->

---
## SLIDE 9 — Variable definition: Energy
<!-- eyebrow: "Variable definition" -->

Anchor's `vocal energy` — enthusiasm, loudness range, and pitch dynamics in the audio signal.

<!-- Audio demos -->
- **Low energy example** — *Flat, low-affect delivery* → [media1.m4a]
- **High energy example** — *Peak excitement, intense affect* → [media2.m4a]

*Aggregated per minute from second-level audio measurements; standardized within streamer to remove baseline differences.*

<!-- SPEAKER NOTES (~75 sec — INCLUDES playing both audio clips): "Listen to this..." play LOW energy clip (~10 sec). "...and this..." play HIGH energy clip (~10 sec). "Same person, same setting, same game — but you can hear the difference. That's what our energy measure captures." -->

---
## SLIDE 10 — Variable definition: Stress Level
<!-- eyebrow: "Variable definition" -->

Audible `vocal stress` — indexed from jitter, shimmer, voice quality irregularities, and prosodic markers of tension.

<!-- Video demos -->
- **Low stress example** — *Relaxed, controlled phonation* → [media3.mp4]
- **High stress example** — *High tension, audible effort* → [media4.mp4]

*Interpreted as a signal of authenticity / emotional investment — see Finding 02.*

<!-- SPEAKER NOTES (~75 sec — INCLUDES playing both clips): "Now stress. Listen to this..." play LOW stress (~10 sec). "...vs this..." play HIGH stress (~10 sec). "The high-stress example sounds strained — that's a key signal viewers pick up on." -->

---
## SLIDE 11 — Hypotheses

1. Expressive Energy → **subscriptions**, not chats
2. Stressed tones → **both** chats and subs *(authenticity signal)*
3. Cognitive depth → **subscriptions** *(competence signal)*
4. *Channel popularity moderates* *(halo for validated anchors)*
5. *Chatroom sentiment moderates* *(positive vibe = less need for anchor energy)*

<!-- SPEAKER NOTES (~45 sec): Plain-English predictions. Energy and cognition drive deliberate behaviors (subs). Stress is special — it's an authenticity signal that drives BOTH. And we expect the social context to moderate. -->

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

<!-- SPEAKER NOTES (~45 sec): Top-25 anchors of a major US gaming platform — 35% of all viewership. Over 1,000 hours of audio/video/chat/sub records. Per-minute panel: every minute has feature values + outcomes. -->

---
## SLIDE 13 — Empirical model

`Negative Binomial` *regression with* `Gaussian Copula` *endogeneity correction*

<!-- Equation (rendered as-is in HTML) -->
μᵢ,ₜ = βₐ·Audioᵢ,ₜ₋₁ + βₘ·Modᵢ,ₜ₋₁ + βᵢ·(Audio × Mod) + β꜀·Controlsᵢ,ₜ₋₁ + λᵢ + εᵢ,ₜ

**Controls**
*Video dynamics, visual attributes, audio quality, lagged outcomes, anchor fixed effects.*

**Why copula**
*Addresses reverse causality (viewers shape anchor's voice) without needing an external instrument.*

<!-- SPEAKER NOTES (~60 sec): NB regression because DVs are counts. Lagged regressors for temporal ordering. Anchor fixed effects to absorb individual baseline differences. Copula correction because viewers' reactions can influence the anchor's subsequent voice — endogenous regressor problem. -->

---
## SLIDE 14 — Finding 01 — engagement is not unidimensional

| Vocal cue | → Chats | → Subscriptions |
|---|---|---|
| Expressive Energy | *ns* (β=0.0037) | **+** β=0.0502*** |
| Stressed | **+** β=0.0037*** | **+** β=0.0377*** |
| Cognitive | *ns* (β=0.0118) | **+** β=0.0440** |

Two distinct psychological pathways:

- **Chats** — impulsive, social → triggered only by *audible effort*
- **Subscriptions** — deliberate, financial → require *energy + effort + competence*

*** p<0.01, ** p<0.05 (baseline NB + copula, no interactions yet)

<!-- SPEAKER NOTES (~75 sec): Walk through the table. Stress is the only cue that lights up BOTH columns — chats β=.0037 and subs β=.0377, both p<0.01. Energy and cognitive depth ONLY drive subs, with no significant chat effect. Two pathways: chats respond to one signal (effort), subs aggregate three. The implication: bundling them into one 'engagement' metric — as most prior work does — masks two very different mechanisms. -->

---
## SLIDE 15 — Finding 02 — the stress paradox

*Contrary to intuition:*

> Stressed vocal tones **positively** affect engagement, both **chats** (β=0.0037***) and **subscriptions** (β=0.0377***).

**Interpretation.** *One possibility: stress may signal authenticity and emotional investment — rewarded in a media landscape saturated with polished, edited content. But the mechanism warrants further investigation.*

<!-- SPEAKER NOTES (~90 sec): The big surprise — what we call the "stress paradox." Common sense says stress should be a turn-off: a strained, tense voice is unpleasant to listen to. But our coefficients say the opposite. Subscriptions: β=0.0377 (p<0.01). Chats: β=0.0037 (p<0.01) — the largest direct effect on chats of any vocal feature we measured. Why? In a media environment saturated with polished, autotuned, edited content, AUDIBLE EFFORT becomes a credibility signal. When viewers hear strain in an anchor's voice — frustration, exertion, real reaction — they read it as "this person is genuinely invested." That's a more honest signal than perfect delivery, and it's rewarded with both immediate engagement (chats) and financial commitment (subs). -->

---
## SLIDE 16 — Finding 03 — popularity moderates

**Channel popularity** (top-5 binary) reshapes both energy and stress effects:

| Interaction | β | What it means |
|---|---|---|
| Popularity × Energy → Subs | **+0.0285*** | Halo amplifies energy's persuasive force on conversion |
| Popularity × Energy → Chats | −0.0177*** | Big crowds chat anyway — anchor energy matters less |
| Popularity × Stress → Chats | **+0.0094*** | Stress becomes a *"rallying cry"* in popular channels |
| Popularity × Stress → Subs | −0.0226*** | Established audiences want polish, not tension, for paid commitment |

*Pre-validation by popularity flips how each vocal cue lands.*

<!-- SPEAKER NOTES (~90 sec): Popularity is a halo. For energy → subs: viewers of popular channels have already validated the anchor's status, so when that anchor performs with energy, they weigh it MORE in subscription decisions — β jumps by +0.0285. For energy → chats: the opposite — in a packed chatroom, people are chatting regardless of what the anchor does (β=-0.0177). For stress, the most interesting split: stress in popular channels intensifies chat behavior, acting as a "rallying cry" for the community (β=+0.0094). But the SAME stress in popular channels HURTS subs (β=-0.0226), because established audiences expect polish for the kind of commitment that involves opening their wallet. -->

---
## SLIDE 17 — Finding 03 (cont.) — sentiment moderates

**Chatroom sentiment** (NLTK on viewer messages, lagged) further conditions vocal effects:

| Interaction | β | What it means |
|---|---|---|
| Sentiment × Energy → Subs | **−0.302*** | Positive room ⇒ anchor's energy adds less to conversion |
| Sentiment × Stress → Chats | −0.0090** | Positive sentiment slightly attenuates the stress→chat channel |

The social environment partially **substitutes** for what the anchor's voice provides.
*Consistent with Social Influence Theory.*

<!-- SPEAKER NOTES (~75 sec): When the room is already positive, viewers' need to be persuaded by the anchor diminishes. The largest moderation in the model is sentiment × energy on subs (β=-0.302, p<0.01) — once the chatroom mood is warm, the marginal value of the anchor's expressive delivery for driving subscriptions drops sharply. Same logic but smaller for stress→chats. This is Social Influence Theory in action: the social context partially substitutes for the persuasive signal from the source. -->

---
## SLIDE 18 — Robustness

**Copula correction is necessary**
- Copula terms significant (p<0.05) → viewer behavior does feed back into anchor's voice
- Without correction, audio coefficients would be biased

**Lag sensitivity** — re-estimated with two-minute lag (t−2)
- Stress and energy effects: **stable**
- Cognitive effects: **attenuate**
- *Cognitive cues may be more transient than emotional ones.*

**Other robustness** *(in appendix)*
- Alternative copula seeds, standardization choices, anchor-specific clustering — all consistent

<!-- SPEAKER NOTES (~75 sec): Three robustness pieces. First, the copula correction terms are themselves significant — which both validates our methodology and confirms there IS reverse causality between viewer reactions and anchor voice. Second, when we push the lag from t-1 to t-2, the stress and energy effects stay basically identical, but the cognitive effect attenuates. That's actually theoretically interesting — emotional cues seem to leave a longer trace in viewers' decisions than analytical/cognitive cues. Third, alternative specifications in the appendix all hold. -->

---
## SLIDE 19 — Strategic recommendations

| Audience | Strategy | Why |
|---|---|---|
| New anchors | Match sentiment | *Sentiment amplifies energy → engagement for small audiences* |
| Established anchors | Differentiate | *Popular channels chat themselves; reserve energy for conversion* |
| All anchors | Leverage stress carefully | *Stress drives engagement, but excess tension hurts subs in big channels* |

<!-- SPEAKER NOTES (~60 sec): Translate findings into managerial guidance. Different stages of an anchor's career call for different vocal strategies. Platforms can use this for coaching and creator development programs. -->

---
## SLIDE 20 — New since submission — replication data

**New wave:** Nov 2025 — Jan 2026

**1,138**
*Twitch VODs, ~22 TB of video*

**Storage:** *AWS S3; per-minute panel structure preserved*

**Purpose**
- Demonstrate findings generalize over time
- Pre-empt reviewer concerns about a single time window
- Enable response to new variable requests *(e.g., visual semantics)*

<!-- SPEAKER NOTES (~45 sec): Anticipating revision. While we wait for revision feedback, we've collected and processed a full replication wave. 1,138 fresh VODs from late 2025 into early 2026. All features extracted on AWS. Same panel structure — drop-in for replication analysis. -->

---
## SLIDE 21 — Methodology upgrade

*From proprietary closed-box to open-source, fully reproducible pipeline.*

| Construct | Original | New |
|---|---|---|
| Audio features | *Nemesysco QA5* | **openSMILE eGeMAPSv02** *(88 features)* |
| Video dynamics | *SSIM only* | SSIM + scene detection + **CLIP embeddings** |
| Audio quality | *MOSNet* | SQUIM + LUFS + voice activity + SNR |
| Linguistic controls | *Chat sentiment* | + transcript: speech rate, hesitations, lexical diversity, F–K grade |

*Transparent, replicable, finer-grained, extensible.*

<!-- SPEAKER NOTES (~60 sec): The original paper used Nemesysco — a proprietary, expensive, closed-box audio analyzer. We've fully replaced it with openSMILE's eGeMAPS, the standard non-proprietary feature set. Plus we've added modern video controls (CLIP semantic embeddings) and transcript-derived linguistic controls. Everything reproducible, no black boxes. -->

---
## SLIDE 22 — Validating the new pipeline
<!-- eyebrow: "Replication preview — eGeMAPS factor structure" -->

`Factor analysis on the new wave (34,000+ minute-observations)` recovers a **3-factor structure** that mirrors the original:

| Factor | Top loadings | Interpretation |
|---|---|---|
| **F1** | Formant amplitudes (F1, F2, F3 relative to F0) | **Expressive Energy** *(loudness/projection)* |
| **F2** | Formant frequencies + unvoiced segment length | **Cognitive Tones** *(articulation precision)* |
| **F3** | Alpha ratio, Hammarberg index, MFCC2 | **Stressed Tones** *(spectral tension)* |

*Same 3-factor structure as Nemesysco — **same constructs, transparent measurement**.*

<!-- SPEAKER NOTES (~75 sec): The big methodological win. When we run factor analysis on the new wave with eGeMAPS, we recover a clean 3-factor structure. Factor 1 picks up loudness/amplitude features — energy. Factor 2 picks up formant precision and pause structure — cognitive articulation. Factor 3 picks up spectral tension — stress. Same theoretical constructs as Nemesysco gave us, but now we know exactly what's in each factor, and anyone can reproduce it. -->

---
## SLIDE 23 — Per-minute feature snapshot
<!-- eyebrow: "What the new pipeline measures" — descriptive stats from new wave -->

| Feature | Mean | SD | What it captures |
|---|---|---|---|
| LUFS loudness | −29.8 dB | 5.2 | *Broadcast loudness (typical streaming range)* |
| VAD ratio | 0.34 | 0.27 | *Anchor speaking ~1/3 of the time* |
| Speech rate | 80 w/min | 59 | *Conversational pace, high variance* |
| Lexical diversity | 0.64 | 0.16 | *Type-token ratio in transcripts* |
| Intra-minute SSIM | 0.62 | 0.17 | *Visual stability across seconds within minute* |
| Inter-minute CLIP cosine | — | — | *Semantic shift between consecutive minutes* |

*Distributions are well-behaved and theoretically interpretable across all 1,131 streams.*

<!-- SPEAKER NOTES (~60 sec): Sanity check that the new pipeline produces reasonable numbers. LUFS at -30 dB is exactly what streaming guidelines target. VAD ratio of 0.34 — anchors speak about a third of the time, leaving room for gameplay audio. Speech rate of 80 wpm with high variance reflects the mix of intense action and quieter moments. The SSIM and CLIP measures capture visual dynamics at two different timescales. -->

---
## SLIDE 24 — Contributions

1. **Engagement is multidimensional**
   *Different psychological pathways for different behaviors.*

2. **Stress is not always negative**
   *It can function as an authenticity signal in digital communication.*

3. **Social Approval and Social Influence work together**
   *Main effects plus contextual moderation.*

4. **A methodological template**
   *For analyzing multimodal interactions in digital settings.*

<!-- SPEAKER NOTES (~60 sec): Four contributions. Engagement isn't one thing. Stress can be a positive signal in the right context. Two persuasion theories together explain more than either alone. And we offer a fully reproducible template for measuring complex multimodal cues. -->

---
## SLIDE 25 — Limitations & future research

**Limitations**
- Top-25 streamers — long tail
- Single platform *(Twitch)*
- Single category *(gaming)*

**In progress**
- Replication on 2025–26 wave *(features extracted, regression next)*
- Per-minute facial semantics *(CLIP)*
- Cross-category generalization *(Just Chatting, IRL, music)*
- Live broadcast vs. VOD viewer differences

<!-- SPEAKER NOTES (~45 sec): Honest about scope. Top streamers — long tail of small creators may behave differently. One platform, one category. Future work goes broader. The replication wave features are extracted; running the regression model on it is next. -->

---
## SLIDE 26 — Thank you

**Thank you.**

Qingli Zeng · Hebrew University of Jerusalem
qingli.zeng@mail.huji.ac.il

<!-- SPEAKER NOTES: Open Q&A. Anticipate questions on:
1. Why top-25 only? Data quality + sufficient variation
2. Why copula not IV? No clean instrument for vocal characteristics; copula is the standard marketing-science fix
3. How do you separate vocal cues from game content? Video controls (SSIM, scene detection, CLIP) absorb visual dynamics
4. How does eGeMAPS map to the original Nemesysco factors? See slide 20 — same 3-factor structure recovered
5. Can platforms operationalize this? Yes — see strategic recommendations slide
-->
