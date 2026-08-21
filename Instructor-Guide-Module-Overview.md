# Introduction to Modern AI — Instructor Guide
### Coding Black Females (CBF)

> **Modular Edition — Designed to grow with the course**

**Format:** 2 days × 2 hours per module = 4 hours per module  
**Total Course:** 6 Modules = 24 hours  
**Audience:** Beginners, no coding/math background required  
**Tone:** Warm, empowering, jargon-free, practical  
**Brand:** `#3b3b3b` (charcoal) + `#d69e1d` (gold) + White  
**Version:** v2.0 — Module 1: Overview [ACTIVE] | Modules 2-6: [TEMPLATE]

---

## 0. How To Use This Guide (Read First)

### The Architecture: One Guide, Six Modules

This is a **living document**. Module 1 is complete. Modules 2–6 use the same skeleton — you only replace the content blocks.

```
course-root/
├── module-01-overview/           <- THIS FILE (v2.0 complete)
├── module-02-ai-ml-models/       <- uses same template (§1-§8)
├── module-03-computer-vision/
├── module-04-translation/
├── module-05-chatbots/
├── module-06-generative-agentic/
└── assets/
    ├── slides/ (Overview deck ref)
    ├── prompt-cards.pdf
    ├── model-cards.pdf
    └── worksheets/
```

**To add a new module:**
1. Duplicate §3 and §4 structure
2. Replace Learning Objectives, Key Concepts, and Demos
3. Keep §2 (3-Slide Pulse Check) and §5 (Exit Rating) identical for consistency
4. Update §7 Timing Summary

### Course Narrative Arc

| Module | Title | Core Question It Answers |
| :--- | :--- | :--- |
| **M1** | **Overview — What is Modern AI?** | *What is AI and why should I care now?* |
| M2 | AI & ML Models | *How does AI actually learn?* |
| M3 | Computer Vision | *How does AI see?* |
| M4 | Translation | *How does AI understand languages?* |
| M5 | Chatbots | *How do I talk to AI effectively?* |
| M6 | Generative AI & Agentic AI | *How does AI create and act on its own?* |

> **Instructor Principle:** Every module should answer "What can *I* do with this tomorrow?" — not just "What is this?"

---

## 1. How This Module Is Organized

This module runs as **two 2-hour sessions** rather than one long block. Keeping each day self-contained makes it easier to schedule, easier for participants to stay engaged, and easier for you to adapt on the fly.

Rather than saving all hands-on practice for a single breakout block at the end, participation is spread **throughout both days** using the **3-Slide Pulse Check** method (§2) — a short, repeatable check-in placed after every few slides.

| Day | Focus | Sections Covered |
| :--- | :--- | :--- |
| **Day 1 · Foundations & Core Technology** | Building the mental model | Course Intro → Overview of AI → Core AI Technologies → How Chatbots Work → What You Can Do With Chatbots |
| **Day 2 · Models, Prompting & Real-World Use** | Applying it hands-on | Types of AI Models → Effective Prompting → AI in Daily Life → Key Takeaways → Capstone Breakout |

**How to read this guide:**
- §2 explains the core facilitation method — read this first.
- §3–4 are the day-by-day run sheets, with timings, scripts, and facilitation notes.
- §5–8 are reference material: rating templates, capstone activity, timing summary, and setup checklist.
- §9 is the MODULE TEMPLATE for Modules 2-6.

---

## 2. Facilitation Methodology: The "3-Slide Pulse Check"

**The Rule:** After roughly every 3 slides (or one full section), stop talking and hand the room back to participants for 2–4 minutes. Never run more than ~15 minutes of one-way delivery without a check-in.

### Step 1 — Tech & Sound Check (30 sec)

> Script: *"Can everyone still hear/see me clearly? Thumbs up if yes. If you're online, drop a 👍 in chat."*

This matters most in the first 10 minutes and right after breaks.

### Step 2 — Comprehension Rating (1 min)

Use a simple visual scale — works in person (hand signals) and virtually (chat/emoji/poll):

| Signal | In-person | Virtual | Meaning | Instructor Action |
| :--- | :--- | :--- | :--- | :--- |
| 🟢 | Thumbs up / open hand | Type "🟢" or "got it" | Clear, ready to move on | Move on |
| 🟡 | Flat hand, wobble | Type "🟡" or "mostly" | Understood gist, some gaps | Give 1 different example |
| 🔴 | Thumbs down / fist | Type "🔴" or "lost" | Needs re-explanation | Pause, re-explain with analogy |

**Threshold Rule:** If >20% show 🟡/🔴, pause and re-explain using a *different* example than the one just used — don't just repeat louder.

### Step 3 — Participation Prompt (2–3 min)

Rotate these so it doesn't feel repetitive:

| Technique | Best used after | How it works |
| :--- | :--- | :--- |
| **Think–Pair–Share** | Conceptual sections | 30 sec silent think → 1 min pair → 2–3 volunteers share |
| **Live "You Try It"** | Any demo section | You demo live, then everyone opens chatbot and repeats exact prompt |
| **Cold-Call Recall (Warm)** | Dense/technical sections | Ask a specific participant by name, warmly, to restate one idea |
| **Spot-the-Error** | Hallucination / Evaluate | Show a wrong AI answer; ask room to identify what's wrong and why |
| **Rewrite Challenge** | Prompting Tips | Give weak prompt ("Write about AI"); participants improve it |

> **Facilitator Tip:** Combine Step 2 + 3: *"Quick pulse check — thumbs up/down on that, and turn to your neighbor: in one sentence, what's the difference between Machine Learning and Generative AI?"*

### CBF-Specific Facilitation Notes

- **Normalize not knowing:** Start with "There are no silly questions here. AI was built to feel intimidating, we're here to demystify it together."
- **Affirm lived experience:** When someone mentions autocorrect, Face ID, etc., explicitly connect: "You are *already* an AI user."
- **Name diversity:** If cold-calling, use names from attendance list, ensure you're not repeatedly calling the same confident voices.

---

## 3. Day 1 — Foundations & Core Technology (2 hours)

### Learning Objectives (Day 1)

By end of Day 1, learners will be able to:
1. Define AI in plain language and explain why this moment (Why Now) matters
2. Distinguish between Machine Learning, Generative AI, Computer Vision, and Translation
3. Describe at a high level how chatbots work (LLM → Transformer → Fine-tuning)
4. List 3 examples of AI they already use daily

### Common Misconceptions to Address

- "AI is magic / super intelligent" → Reframe: Pattern-matching on massive data, not thinking
- "AI will replace me" → Reframe: Tool that amplifies, not replaces — show human-in-the-loop
- "You need to be technical to use AI" → Prove wrong via live demos

### Icebreaker (Day 1) — "AI in My Pocket" (10 min)

**Prompt:** *"Name ONE AI tool you already used this week without thinking of it as 'AI'."*
Examples to seed if room is quiet: autocorrect, Spotify recommendations, Face ID, Google Maps ETA, spam filter, TikTok FYP.

Collect 4–5 examples out loud. Write them on board/slide.

*Purpose: proves AI is already familiar, lowers intimidation.*

### Day 1 Timeline

| Time | Duration | Activity | Slides / Assets | Instructor Notes |
| :--- | :--- | :--- | :--- | :--- |
| 0:00–0:10 | 10 min | Welcome + Icebreaker | Title slide | Code of Conduct, pronouns, community channel #ai-intro |
| 0:10–0:20 | 10 min | Course Roadmap | Course Content, Learning Objectives | Show the 6-module journey. Emphasize: Module 1 is the map, not the whole territory. |
| 0:20–0:35 | 15 min | **Section 1 — Overview of AI** | What is AI, Why Now, Key Insight | **Key Insight Script:** "AI is not new. What's new is: cheap compute + massive data + open models. That's the 'Why Now'." Pulse Check after. |
| 0:35–0:50 | 15 min | **Section 2 — Core AI Technologies** | ML, GenAI, Vision, Translation | Use analogy: ML = learning from examples (like a child seeing 100 cats). GenAI = learning to *create* new cats. Vision = learning to *see* cats. |
| 0:50–1:05 | 15 min | **Section 3 — How Chatbots Work** | LLMs, Transformers, Fine-Tuning, Hallucination demo | **Demo:** Show hallucination live: Ask ChatGPT "Give me 3 fake references for a paper on X". Then ask it "Are those real?" — shows self-correction. |
| 1:05–1:10 | 5 min | 🔔 **Pulse Check #1** | — | Covers Sections 1–3. Use Cold-Call Recall: "What's one difference between ML and GenAI in your own words?" |
| **1:10–1:25** | **15 min** | **BREAK** | — | Play lo-fi / CBF playlist. Leave a "Be back at HH:MM" slide. |
| 1:25–1:30 | 5 min | Re-entry Check | — | Tech & Sound Check (Step 1). Recap 3 bullets from pre-break. |
| 1:30–1:55 | 25 min | **Section 4 — What You Can Do With Chatbots** (7 capabilities) | Expand, Synthesize, Transform, Evaluate, Chat, Take Actions, Multimodal | **DO NOT demo all 7 back-to-back.** Chunk: 1-3 → mini pulse, 4-6 → mini pulse, 7 as finale (most visual). Live "You Try It" after each chunk. |
| 1:55–2:00 | 5 min | 🔔 **Pulse Check #2 + Exit Rating** | §5 template | Day 1 close: "What's one thing you're excited to try tonight?" |

#### Facilitating Section 4 — The 7 Capabilities (High Risk of Zoning Out)

1.  **Expand:** "Explain blockchain like I'm 5" → Show how AI expands a tiny prompt
2.  **Synthesize:** Summarize long article/meeting notes
3.  **Transform:** Change tone, translate, reword
4.  **Evaluate:** Grade essay against rubric
5.  **Chat:** Roleplay, coaching
6.  **Take Actions:** Make a table, plan
7.  **Multimodal:** Upload image + ask about it (end on high note)

**Script for transition:** "If you remember nothing else, remember these 7 verbs. If you can do these 7 things, you can do 90% of what people do with AI at work."

---

## 4. Day 2 — Models, Prompting & Real-World Use (2 hours)

### Learning Objectives (Day 2)

By end of Day 2, learners will be able to:
1. Identify 4 types of AI models (Structured Data, ASR, Audio Gen/TTS, NLP) and one use case for each
2. Apply 6 prompting principles to improve AI outputs
3. Build 2 personal workflows using AI in daily life
4. Complete a capstone task using at least 3 chatbot capabilities

### Icebreaker (Day 2) — "One Word Recap" (10 min)

Prompt: *"One word that summarizes what you remember from Day 1 — drop it in chat or shout it."*
Instructor clusters words on screen/whiteboard (e.g., groups: Learning, Creating, Seeing, Talking).

*Purpose: reactivates memory, informal comprehension check, low-effort.*

### Day 2 Timeline

| Time | Duration | Activity | Slides / Assets | Instructor Notes |
| :--- | :--- | :--- | :--- | :--- |
| 0:00–0:10 | 10 min | Icebreaker: "One Word Recap" | Word cloud slide | Celebrate recall. No wrong answers. |
| 0:10–0:15 | 5 min | Day 1 Recap | 3-bullet summary | Address any 🔴 flagged from Day 1 exit rating. "Yesterday a few of us were 🟡 on Transformers — let's revisit that in 30 seconds..." |
| 0:15–0:35 | 20 min | **Section 5 — Types of AI Models** | Structured Data, ASR/Whisper, Audio Gen/TTS + Coqui demo, NLP | **Demos:** Coqui TTS XTTS-v2 (clone voice), Whisper (transcribe 15 sec audio). Have backup recordings if live fails. |
| 0:35–0:50 | 15 min | **Section 6 — Tips for Effective Prompting** | 6 tips: Specific, Role, Examples, Step-by-Step, Iterate, Constraints | **Chunk 3+3.** Tips 1-3 → Rewrite Challenge. Tips 4-6 → second rewrite. Mantra: *"Clear input = Clear output."* |
| 0:50–1:05 | 15 min | **Section 7 — Apply AI to Daily Life** | 6 workflows (email, learning, job search, budgeting, etc.) | Ask: "Which of these would save you 1 hour this week?" — makes it personal. |
| 1:05–1:10 | 5 min | 🔔 **Pulse Check #3** | — | Covers 5–7. Use Rewrite Challenge: Give weak prompt "Write about AI", improve using one tip. |
| **1:10–1:25** | **15 min** | **BREAK** | — | — |
| 1:25–1:30 | 5 min | Re-entry Check | — | — |
| 1:30–1:40 | 10 min | **Section 8 — Key Takeaways** | 4 core principles | Don't read slides verbatim. Ask room to guess the takeaways before revealing. |
| 1:40–2:10 | 30 min | **Capstone Breakout Activity** | §6 | Pick 2–3 exercises. Use breakout rooms/pairs. Instructor roams. |
| 2:10–2:15 | 5 min | 🔔 **Final Pulse Check + Close-out** | §5 | Course-level exit rating. Point to Slack #ai-intro. Close with: *"Start small. Experiment daily. AI is better with friends."* |

---

## 5. End-of-Session Rating (Exit Pulse Check)

Run at end of **each day** (2–3 min). Use Mentimeter, Zoom Poll, Slack emoji, or sticky notes.

**Rate today's session (1 = low, 5 = high):**

| Question | 1 | 2 | 3 | 4 | 5 |
| :--- | :--- | :--- | :--- | :--- | :--- |
| I could hear/see the material clearly | | | | | |
| I understood the concepts before the break | | | | | |
| I understood the concepts after the break | | | | | |
| I feel confident trying this on my own | | | | | |

**Analysis for instructor:**
- Compare before vs after break scores. Drop = break ran long / re-entry recap too short.
- Avg <3 = revisit in next day's recap or follow-up resource.
- Track 🟢/🟡/🔴 ratio across modules to spot consistently hard sections.

---

## 6. Capstone Breakout Activity (Day 2, 30 min)

> Goal: Apply at least 3 capabilities + 2 prompting tips in one workflow.

**Setup:** Pairs (or trios online). Each pair picks ONE track. 10 min per task, then 5 min share-back.

### Recommended Combo (widest skill coverage):

**Track A — Transform (10 min)**
Take a technical paragraph (provided in worksheet). Translate to another language (e.g., Kinyarwanda/French), then reword for a 5th grader. Compare results with partner. Prompt tip: *Assign a Role* ("You are a primary school teacher").

**Track B — Evaluate (10 min)**
Submit a short essay/CV bullet. Ask AI to grade against rubric + fact-check one claim with sources. Prompt tip: *Set Constraints* + *Use Examples*.
*Spot-the-Error moment:* Does AI invent sources? Discuss.

**Track C — Multimodal (10 min)**
Upload a chart/screenshot (sample provided). Ask: "What is this? Extract all text. Explain trend. Suggest 3 insights." Prompt tip: *Be Specific* + *Step-by-Step*.

**Debrief Script (5 min):**
- "What surprised you?"
- "What failed? What did you do to fix the prompt?"
- "Which of these could you use at work/school tomorrow?"

---

## 7. Quick Reference — Full Timing Summary

| | Day 1 | Day 2 |
| :--- | :--- | :--- |
| **Icebreaker** | AI in My Pocket (10m) | One Word Recap (10m) |
| **Content blocks** | Overview → Core Tech → Chatbots → Capabilities | Model Types → Prompting → Daily Life → Takeaways |
| **Break** | 15 min @ ~70 min mark | 15 min @ ~70 min mark |
| **Pulse Checks** | 2 (mid + exit) | 2 (mid + final) + re-entry checks |
| **Activity** | Embedded "You Try It" per capability | 30-min capstone (2–3 exercises) |
| **Total** | 120 min | 120 min |

**Module 1 Slide-to-Time Mapping:**
- Slides 1-10: Day 1 0:10-0:20
- Slides 11-25: Day 1 0:20-1:05
- Slides 26-45: Day 1 1:30-1:55 (Capabilities)
- Slides 46-60: Day 2 0:15-0:35 (Model Types)
- Slides 61-75: Day 2 0:35-1:05 (Prompting + Daily Life)

---

## 8. Setup Checklist (Both Days)

### Tech & Accounts
- [ ] Chrome browser, ChatGPT + Claude accounts logged in and tested
- [ ] Coqui TTS XTTS-v2 space open: huggingface.co/spaces/coqui/xtts
- [ ] Whisper demo + 2 sample audio files (15 sec each)
- [ ] Teachable Machine (teachablemachine.withgoogle.com) tested
- [ ] Sample charts/images for multimodal demo (in /assets)

### Materials
- [ ] Prompt Cards / Model Cards / Worksheet printed or shared digitally
- [ ] Slide deck loaded, presenter view tested, captions enabled
- [ ] Poll tool ready (Mentimeter / Zoom Polls / Slack emoji) for Pulse Checks
- [ ] Backup: Pre-recorded screen captures of all demos (if WiFi fails)

### Room & Culture
- [ ] CBF Code of Conduct reviewed (Day 1 start, 2 min)
- [ ] Community channel: #ai-intro link/QR displayed
- [ ] Accessibility: Captions on, font size 24pt+, gold on charcoal has 4.5:1 contrast check
- [ ] Timer visible for breakout activities

---

## 9. MODULE TEMPLATE — For Modules 2 to 6

> Copy this section for each new module. Replace bracketed fields.

### Module [N]: [Title] — Instructor Guide

**Module Goal:** [One sentence: what mental model will they have after?]
**Prerequisite from M1:** [e.g., "Understand what Generative AI is"]
**New Vocabulary:** [3-5 terms max]

#### Learning Objectives
By end of this module, learners will be able to:
1. [Objective]
2. [Objective]
3. [Objective]

#### Day 1 & Day 2 Focus
| Day | Focus | Sections |
| :--- | :--- | :--- |
| Day 1 | [e.g., How it works] | [Section list] |
| Day 2 | [e.g., Build with it] | [Section list + Capstone] |

#### Demos & Tools for This Module
- Tool: [e.g., Roboflow for Vision] — Link: — Backup plan:
- Dataset: [e.g., Sample images]
- Prompt Pack: [Module-specific prompt starters]

#### Common Misconceptions
- [Misconception → Reframe]

#### Capstone Idea
[One hands-on project that proves they can use this module independently]

#### Assessment / Pulse Check Tweaks
[Any module-specific tweaks to §2 method]

---

### Appendix A: Instructor Scripts (Module 1)

**Opening Script (Day 1):**
> "Welcome to Introduction to Modern AI. I'm [Name] from Coding Black Females. This is Module 1 of 6 — today is not about becoming an AI engineer in 4 hours. It's about building your map of the territory, so the next 5 modules feel familiar, not scary. You've already used AI this week — let's prove it."

**Closing Script (Day 2):**
> "You now have 7 verbs, 6 prompting tips, and 4 model types in your toolkit. That's more than most people who claim to 'know AI'. For Module 2, we'll go deeper into how AI actually learns — bring your curiosity and your 'AI in My Pocket' examples."

### Appendix B: Prompt Starter Pack (Module 1)

```
1. Expand: "Explain [topic] to me like I'm 12, then like I'm an expert. What's the difference?"
2. Synthesize: "Summarize this [paste text] in 3 bullet points + 1 question I should ask next."
3. Transform: "Rewrite this email in a friendly but professional tone. Keep all facts."
4. Evaluate: "Grade this paragraph against: clarity, accuracy, tone. Give 1-10 and one fix for each."
5. Chat: "You are a career coach for Black women in tech. Help me practice answering [question]."
6. Take Actions: "Create a 3-day learning plan for [topic] with 30 min per day."
7. Multimodal: "What do you see in this image? List objects, then suggest 3 insights."
```

---

*Prepared for Coding Black Females · Module 1 Owner: [Instructor Name] · Last updated: 2026-08-21*
*Next steps: Upload Overview slides to /assets/slides/ and update Slide-to-Time mapping in §7.*
