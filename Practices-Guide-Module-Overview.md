# Introduction to Modern AI — Topic-by-Topic Instructor Practice Guide
### Coding Black Females (CBF) | Modular Edition

> **Purpose:** A hands-on companion to the main Instructor Guide. This is *what you DO*, not just what you say.
> **Format:** 2 days × 2 hours = 4 hours per module | 6 Modules total
> **Audience:** Beginners, no code/math | **Brand:** `#3b3b3b` + `#d69e1d`
> **Version:** v2.1 — Module 1: Overview [ACTIVE] | Modules 2-6: [TEMPLATE READY]

---

## 0. How This Practice Guide Works

### Relationship to Main Guide

| Document | Role |
| :--- | :--- |
| **Main Instructor Guide** | Run sheet, timing, learning objectives, slide map |
| **This Practice Guide** | The *exact* activity, prompt, debrief Q, and what to listen for |

Use them side-by-side. Main guide = clock. This guide = playbook.

### The Universal Practice Pattern (Use for EVERY topic)

Never lecture >15 min. Use this loop:

```text
EXPLAIN (2-3 min max)
   ↓
DEMONSTRATE / GIVE ONE EXAMPLE (live)
   ↓
PULSE CHECK 🟢 🟡 🔴 (1 min) → If >20% 🟡/🔴 → NEW example, not repeat
   ↓
PARTICIPANT PRACTICE (2-4 min) → They try, you roam
   ↓
DEBRIEF (1-2 min) → 2 volunteers share, you name the insight
   ↓
TRANSITION → Link to next topic: "Now that we know WHAT, let's see HOW..."
```

### The 3-Slide Pulse Check — Quick Reference

**Step 1 — Tech Check (30s):** *"Can everyone still hear/see me clearly? 👍 in chat?"*

**Step 2 — Comprehension Rating (1m):**
| 🟢 Clear | 🟡 Mostly | 🔴 Lost |
| :--- | :--- | :--- |
| Move on | Give 1 *different* example | Stop, re-explain with analogy |

**Step 3 — Participation Prompt (2-3m):** Rotate:
- **Think-Pair-Share** → conceptual
- **Live "You Try It"** → demos
- **Warm Cold-Call Recall** → dense concepts ("Aisha, in your own words...")
- **Spot-the-Error** → hallucinations / evaluation
- **Rewrite Challenge** → prompting

> **Golden Rule:** Say both together: *"Quick pulse — 🟢🟡🔴, and turn to your neighbor: in one sentence, what's the difference between ML and Generative AI?"*

---

# MODULE 1: OVERVIEW — DAY 1 · FOUNDATIONS & CORE TECHNOLOGY

## Day 1 Overview at a Glance

| Time | Topic / Activity | Practice Type | Asset Needed |
| :--- | :--- | :--- | :--- |
| 0:00–0:10 | Welcome + AI in My Pocket | Icebreaker | Whiteboard / Miro |
| 0:10–0:20 | Course roadmap & Expectations | Expectation check | Slide: 6-module journey |
| 0:20–0:35 | Section 1 — Overview of AI | Human-or-AI + TPS | Scenario cards |
| 0:35–0:50 | Section 2 — Core AI Technologies | Match the Technology | 4 scenario cards |
| 0:50–1:05 | Section 3 — How Chatbots Work | Explain Simply + Spot-the-Error | Hallucination demo prompt |
| 1:05–1:10 | Pulse Check #1 | Consolidation | 🟢🟡🔴 poll |
| 1:10–1:25 | BREAK | — | Lo-fi slide |
| 1:25–1:30 | Re-entry | Recall + Tech check | — |
| 1:30–1:55 | Section 4 — What You Can Do With Chatbots (7 caps) | Demo + You Try It ×3 | Prompt Cards |
| 1:55–2:00 | Pulse Check #2 + Exit Rating | Reflection | Rating template §43 |

---

### 2. Welcome — "AI in My Pocket" (10 min)

**Learning purpose:** De-intimidate. Prove they are already AI users.

**Instructor Script:**
> "Before we learn anything new, let's find AI we already use. Turn to a partner — name ONE AI feature you used this week without thinking 'that's AI'. You have 60 seconds."

**Seed examples if quiet:** Autocorrect, Spotify Discover Weekly, Face ID, Google Maps ETA, Gmail Smart Reply, spam filter, TikTok FYP.

**Participant Practice (in pairs):**
1. Name one example
2. Explain what the system *appears* to do
3. Decide: Did you think of it as AI before?

**Debrief — Ask:** *"What do these have in common?"* → Guide to: they all learn from data/patterns to help you.

**Transition:** "You are not starting from zero. You are starting from experience. Let's map it."

**What to listen for:** If someone says "I don't use AI" — celebrate their first example, don't correct.

### 3. Course Roadmap, Content & Learning Objectives (10 min)

**Practice — Expectation Check:**
> "On a sticky note / in chat: By the end of these two sessions, what is ONE thing you would like to be able to do with AI? No filtering."

Collect 3–4 aloud. Cluster: Work / Learning / Creativity / Daily Life.

**Instructor Use:** Don't debate. Connect: "If you want [X], Module 1 gives you the 7 verbs. Module 2-6 gives you the how."

**Transition Script:**
> "Keep that goal in mind — we'll come back to it at the end of Day 2. This module is your map, not the whole journey."

### 4. Section 1 — Overview of AI (15 min)

**Topics:** What is AI? Why now? Key Insight

**Key Insight Script (Must Say):**
> "AI is not new — 1950s idea. What's new is three things together: cheap computers + massive data from phones/internet + open models anyone can use. That's the 'Why Now'."

**Practice — "Human or AI?"**

Give 5 scenarios (read aloud):
1. Spotify recommends a song you love
2. A human writes a poem
3. Your bank flags a fraud transaction
4. A calculator does 2+2
5. Google Translate converts English to Kinyarwanda

**Instructions:** Individual: 🟢=AI involved, 🔴=Not AI → Pair compare → 2 shares.

**Debrief Qs:**
- What made you classify something as AI?
- Did any example surprise you?
- Does AI always look like a chatbot? (No)

**Pulse Check:**
> "In one sentence, no jargon: What is AI?"

**If 🟡/🔴:** Use analogy: "AI = teaching computers to do tasks that usually need human judgment, by showing them lots of examples."

### 5. Section 2 — Core AI Technologies (15 min)

**Topics:** Machine Learning, Generative AI, Computer Vision, Machine Translation

**Analogy Bank (use these):**
- **ML:** Like a child learning cats — show 100 cat photos, learns pattern
- **Generative AI:** Like an artist who saw 100 cats and can now draw a *new* cat that never existed
- **Computer Vision:** Like giving the child glasses — now it can *see* the cat
- **Translation:** Like a friend who speaks two languages and learns the mapping

**Practice — "Match the Technology"**

Scenario cards (print or slide):
| Scenario | Answer |
| :--- | :--- |
| System learns patterns from examples | Machine Learning |
| System creates new text/image | Generative AI |
| System interprets an image | Computer Vision |
| System converts between languages | Machine Translation |

**Follow-up (Critical):** *"Could more than one be involved in a single app?"* → Yes! Example: Instagram: Vision (detects face) + Generative (creates filter) + ML (recommends).

**Pulse Check:** *"One important difference between ML and Generative AI in your own words?"*

**If 🟡/🔴:** Live example: "ML predicts: 'This email is spam.' GenAI creates: 'Write a spam email.' Different job."

### 6. Section 3 — How Chatbots Work (15 min) — DENSEST SECTION

**Topics:** LLMs, Transformers, Fine-tuning, Hallucinations

**Facilitator Note:** Do NOT explain Transformer architecture. Focus on *why it matters*: context.

#### Practice A — Explain It Simply (LLMs)

> "Explain what an LLM does as if explaining to a friend who knows nothing about AI. 30 seconds think, 2 shares."

**Listen for:** "Predicts next word based on patterns" — not verbatim definition.

#### Practice B — Cold-Call Recall (Warm)

> "Amina, warmly — can you tell us one thing you remember about how a chatbot generates a response? If stuck, someone help."

#### Practice C — Transformers Analogy

Sentence: "The bank is by the river bank."
Ask: *"Why does context matter here?"* → Same word, different meaning based on surrounding words. That's what Transformers are good at: context.

#### Practice D — Fine-Tuning Scenario

> "If a general AI needs to be great at medical advice for nurses, what might we change?" → Let them reason → Then label: "That's fine-tuning — take general model + train more on specific data."

#### Practice E — Hallucination Spot-the-Error (Must-Do Demo)

**Demo Script:**
1. Prompt: *"Give me 3 academic references for a paper on AI in Rwandan agriculture with links."*
2. Show plausible but fake refs
3. Then prompt: *"Are those real references? Check and be honest."*
4. AI admits hallucination.

**Ask:** *"What should make us cautious here?"* and *"How would you verify?"*

**Reinforce on slide:**
> **Generate → Question → Verify → Use**

**Pulse Check:** *"What is hallucination and what do we do when we see it?"*

### 7. Pulse Check #1 — Sections 1-3 (5 min)

Run 🟢🟡🔴 poll. Then pick ONE:

**Option A (Recall):** "In one word: AI, Machine Learning, Generative AI, Hallucination — pick one and define it."

**Option B (TPS):** "Biggest difference between ML and Generative AI?"

**Instructor Decision Tree:**
- >20% 🟡/🔴 on one concept → Stop, new example, re-poll
- <20% → "Great, we will reinforce later. Let's take a break."

### 8. Re-entry After Break (5 min)

**Script:** "Welcome back — quick tech check 👍? Before we continue, one thing you remember from first half? 2-3 voices."

Don't start with new content immediately.

### 9. Section 4 — What You Can Do With Chatbots (25 min) — HIGHEST RISK OF ZONING OUT

**The 7 Capabilities:**
1. Expand 2. Synthesize 3. Transform 4. Evaluate 5. Chat 6. Take Actions 7. Multimodal

**Chunking Rule (from Main Guide):**
```text
Caps 1–3 → Mini Pulse (30s + 1 room example)
Caps 4–6 → Mini Pulse
Cap 7 → Finale (visual wow)
```

#### Capability 1 — Expand

**Demo Prompt:** "Expand this: 'AI is useful.'"
**Practice — "Make It Bigger":** Give short idea: "Community health workshop next week." Ask chatbot to expand into invitation.

**Debrief:** Did AI add useful info or just longer words?

**Pulse Q:** "When would expanding be useful in your work?"

#### Capability 2 — Synthesize

**Practice — "Three Sources → One Summary":**
Provide 3 short WhatsApp messages about a meeting. Prompt: "Synthesize into 3 bullets: what was decided, who does what, by when."

**Debrief:** "What did AI keep vs leave out?"

#### Capability 3 — Transform

**Practice — "Same Message, Different Audience":**
One paragraph → Transform to: simpler version, professional email, version for 10-year-old.

**Insight:** Audience, tone, complexity changes — not just words.

**Mini Pulse Check #1:** "Give me one transformation you'd use at work/school."

#### Capability 4 — Evaluate

**Practice — "Spot the Problem":**
Give weak CV bullet. Prompt: "Evaluate against: clarity, impact, specificity. Score 1-10 + one fix."

**Critical Follow-up:** "Should we automatically trust AI's evaluation? No — it's a second opinion, not a judge."

#### Capability 5 — Chat

**Practice — "Conversation With Purpose":**
Prompt starter: "You are a supportive interview coach for Black women in tech. Help me practice answering 'Tell me about yourself' — ask one question at a time and give feedback."

**Instructor Point:** Value is guiding interaction to outcome, not just chatting.

#### Capability 6 — Take Actions

**Practice — "From Answer to Next Step":**
Task: "Plan a 1-hour community intro to AI session." Prompt: "Turn this into a checklist with time blocks."

**Debrief:** "Which parts still need human judgment?" → Keeps human-in-the-loop.

**Mini Pulse Check #2:** "Name one useful action workflow for you."

#### Capability 7 — Multimodal (Finale)

**Practice — "What Can AI See?":**
Use sample chart (e.g., bar chart of module completion). Everyone with image support uploads. Prompt:
> "What is this? Extract all text. Explain trend in one sentence. Suggest 3 insights."

**Debrief:** "What became possible because we added an image?"

**Key Point:** Multimodal = combine forms, not just text.

### 16. Pulse Check #2 — Day 1 Close (5 min)

**Reflection Qs:**
1. "Which of the 7 capabilities would be most useful to you tomorrow? Type number 1-7."
2. "What is one thing you learned today you didn't know before?"

**Then:** Day 1 Exit Rating (§43). Preview Day 2: "Tomorrow we learn to control these 7 verbs with better prompts."

---

# MODULE 1: OVERVIEW — DAY 2 · MODELS, PROMPTING & REAL-WORLD USE

## Day 2 Overview at a Glance

| Time | Topic / Activity | Practice | Asset |
| :--- | :--- | :--- | :--- |
| 0:00–0:10 | One Word Recap | Memory activation | Word cloud |
| 0:10–0:15 | Day 1 Recap | Address 🔴 items | 3-bullet slide |
| 0:15–0:35 | Section 5 — Types of AI Models | Match Model/Task + Demos | Coqui, Whisper samples |
| 0:35–0:50 | Section 6 — Effective Prompting | Rewrite Challenge | Prompt Cards |
| 0:50–1:05 | Section 7 — Apply AI to Daily Life | Workflow: Demo → Try → Improve | 6 workflows from slides |
| 1:05–1:10 | Pulse Check #3 | Prompt rewrite | — |
| 1:10–1:25 | BREAK | — | — |
| 1:25–1:30 | Re-entry | Tech check | — |
| 1:30–1:40 | Section 8 — Key Takeaways | Four-principle recall | — |
| 1:40–2:10 | Capstone | 2–3 exercises | Worksheets, sample chart |
| 2:10–2:15 | Final Pulse + Close | Rating + community | CBF Slack QR |

### 17. Day 2 Icebreaker — "One Word Recap" (10 min)

**Script:** "One word that summarizes Day 1 — drop in chat."

Cluster: Learning / Creating / Seeing / Talking / Verifying.

**Extension:** Pick 3 words: "Who can explain why this word represents Day 1?"

**Instructor Action:** Use Day 1 exit ratings to decide what needs 60-sec reteach. If many 🟡 on hallucinations, start there.

### 18. Section 5 — Types of AI Models (20 min)

**Topics:** Structured Data, ASR, Audio Gen, TTS (Coqui), NLP

**Teaching Frame:** Don't ask to memorize definitions. Ask "What job does this model do?"

#### Structured Data

**Demo:** Show simple table: Name | Age | District | Completed Module?
**Ask:** "What info is here? What could AI help do?" → e.g., predict who needs support, group by district.

**Focus:** Recognizing structured info.

#### 19. ASR — Automatic Speech Recognition

**Demo — "Say It, Transcribe It":**
1. Speak: "My name is [Name] and I am learning AI with Coding Black Females in Kigali."
2. Run Whisper
3. Show transcription — celebrate errors too.

**Ask:** "What was correct/incorrect? Why might it fail?" → Accent, background noise, jargon.

**Pulse Q:** "Difference between speech recognition (hears words) and text generation (creates words)?"

#### 20. Audio Generation

**Demo — "Listen and Compare":** Play sample generated audio (from deck).
**Ask:** "What appears to be generated? What should we check before using professionally?" → Consent, quality, bias.

Keep technical depth low.

#### 21. TTS — Text-to-Speech + Coqui Demo

**Instructor Sequence:**
1. Text: "Welcome to Modern AI. Start small. Experiment daily."
2. Generate with Coqui XTTS-v2 — use different voices
3. Play → Ask: "What do you notice?"

**Challenge:** "What real-world situation benefits from TTS?" → Accessibility, podcasts, low-literacy audiences.

**Backup:** Pre-recorded audio if live fails.

#### 22. NLP — Natural Language Processing

**Practice — "What is the system doing with text?"**
Give short text. Options: Understand, Transform, Analyze, Generate.

**Think-Pair-Share:** "Why is human language hard for computers?" → Sarcasm, context, many languages (Kinyarwanda!).

### 23. Model Types Consolidation (3 min)

**Match the AI Capability:** Read 6 scenarios, room calls model type.

**Pulse Q:** "Which model type was easiest/hardest?" → Use to adjust pacing.

### 24. Section 6 — Effective Prompting (15 min) — EXAMPLE-HEAVY

**The 6 Tips:**
1. Be Specific 2. Assign a Role 3. Use Examples 4. Work Step-by-Step 5. Iterate 6. Set Constraints

**Chunk:** 1-3 → Pulse, 4-6 → Capstone bridge.

#### 25. Starting Prompt (All Do This)

Give everyone: **"Write about AI."** Run it.

**Ask:** "What's wrong with this prompt?" → Collect: too broad, audience unclear, format unclear, purpose unclear, length unclear.

#### 26. Tip 1 — Be Specific

**Practice:** Transform "Write about AI" into prompt specifying: Topic, Audience, Purpose, Format, Length.

Example Good: "Write 3 bullet points for beginners explaining what Generative AI is, for a WhatsApp message to my sister."

**Debrief:** Run both, compare outputs side-by-side. Ask: "What changed?"

#### 27. Tip 2 — Assign a Role

**Practice:** "Act as an instructor teaching Black women beginners in tech with no coding background..."

Compare output. Discussion: "How did role change response?"

#### 28. Tip 3 — Use Examples

**Practice:** Give example output you want: "Here's example of friendly tone: [example]. Now write similar for [task]."

**Compare:** No example vs one example.

**Debrief:** "What did example tell AI that instruction didn't?"

#### 29. Pulse Check — Tips 1-3 (Rewrite Challenge)

**Task:** Take "Write about AI" and improve using ONE of first three tips. 3 volunteers share prompts in chat.

Don't grade right/wrong. Ask: "What makes this clearer?"

#### 30. Tip 4 — Work Step-by-Step

**Practice:** Multi-stage task: "Help me plan a workshop. Step 1 list topics, Step 2 create agenda, Step 3 write invitation."

**Debrief:** "Why break into steps?" → Easier to control, fix, verify.

#### 31. Tip 5 — Iterate

**Practice — Prompt → Inspect → Improve:**
1. Run prompt
2. Read output
3. Identify ONE weakness
4. Improve prompt
5. Run again

**Key Message Slide:** **Prompting is iterative. First answer ≠ Final answer.**

#### 32. Tip 6 — Set Constraints

**Practice:** Add constraints: Length (50 words), Audience (5th grader), Format (table), Number (3 examples), Tone (warm).

Compare outputs. Ask: "Which constraint had biggest effect?"

#### 33. Prompting Consolidation

**Repeat Challenge:** "Write about AI." — This time use DIFFERENT technique than before.

**Mantra (say aloud, put on slide):**
> **Clear input = Clear output.**

### 34. Section 7 — Apply AI to Daily Life (15 min) — 6 WORKFLOWS

> Note: Use exact 6 workflows from your slide deck. Template below attaches to each.

#### Practice Structure for EACH Workflow (3 min per workflow)

1.  **Show (30s):** Instructor demos
2.  **Identify (30s):** "What problem is AI solving here?"
3.  **Try (60s):** Participants reproduce with own example
4.  **Improve (30s):** "How could we make prompt better?"
5.  **Human Role (30s):** "What part still requires YOU?"

#### 35. Workflow Template — Copy for Each of 6 Workflows

**Workflow: [Insert exact title from slide — e.g., Email Assistant]**
- **Observe:** Instructor demos with real example
- **Task:** Repeat with your own example (e.g., your own email)
- **Prompt Challenge:** Improve one part using Tip 1-6
- **Discussion:** What did AI do well?
- **Verification:** What needs checking? (facts, tone, privacy)
- **Human Role:** What decision/judgment remains with you?
- **Pulse Q:** "Where could you use this in your own life/work this week?"

**Facilitator Tip:** After 3 workflows, quick 🟢🟡🔴 — "Useful so far?"

### 36. Pulse Check #3 — Sections 5-7 (5 min)

**Rewrite Challenge (different tip):**
> "Take 'Write about AI' and rewrite using a tip you did NOT use earlier. Share."

**Then:** "How is this version different from your first version Day 1?"

**Final Comprehension:** 🟢 Clear / 🟡 Mostly / 🔴 Need example

### 37. Section 8 — Key Takeaways (10 min)

**Practice — "Four Principles From Memory":**
Script: "Close laptops. Without looking — what were the 4 core principles? 30 seconds think, then shout."

Then reveal slide. Don't read verbatim — let them recall first (retrieval practice).

**Follow-up:** "Which principle will you actually use after today? Type 1-4."

**Instructor Note:** Principles should be actionable, e.g.:
1. AI is pattern-matching, not magic
2. Clear input = Clear output
3. Generate → Question → Verify → Use
4. Start small, experiment daily, better with friends

### 38. Day 2 Capstone — 30 Minutes (Pick 2-3 of 8)

**Setup:** Pairs/trios, breakout rooms online. 10 min per exercise + 5 min share-back. Instructor roams, not lectures.

**Goal:** Prove they can use 3 capabilities + 2 prompting tips without you.

#### 39. Capstone Exercise 1 — Transform: Translate & Reword (10 min)

**Task:**
1. Take technical paragraph (from worksheet)
2. Translate to another language (e.g., French/Kinyarwanda/Spanish)
3. Reword for 5th-grade learner
4. Compare with partner

**Prompt Tip to use:** Assign a Role ("You are primary school teacher")

**Debrief Q:** "What changed when audience changed?"

#### 40. Capstone Exercise 2 — Evaluate: Grade This + Fact Check (10 min)

**Task:**
1. Submit short essay/CV bullet/paragraph
2. Ask AI to grade against rubric (provide rubric)
3. Ask to fact-check one claim + provide sources
4. Discuss: Should we trust it?

**Prompt Tips:** Set Constraints + Use Examples

**Debrief:** "What did AI evaluate well? What would you still verify yourself?"

**Key Message:** AI assists evaluation, but you keep critical judgment.

#### 41. Capstone Exercise 3 — Multimodal: Input Image + Text (10 min)

**Task:** Upload chart/screenshot (provide sample chart: e.g., enrollment by module)
Prompt:
> "What is this? Extract all text. Explain trend in one sentence. Suggest 3 insights for program manager."

**Debrief:**
- What did AI identify?
- Was extracted text accurate?
- Did insights make sense?
- What would you verify?

### 42. Final Pulse Check (5 min)

**Reflection:**
1. "What is ONE thing you can now do with AI you couldn't confidently do before?"
2. "What will you try first tomorrow? Type in chat."

**Then:** Course-level rating (§43)

**Close Script:**
> "Start small. Experiment daily. AI is better with friends. See you in Module 2 — where we learn HOW AI learns. Drop your first win in #ai-intro this week!"

### 43. End-of-Day Rating (Use Daily)

Rate 1=low 5=high:

| Question | 1 | 2 | 3 | 4 | 5 |
| :--- | :--- | :--- | :--- | :--- | :--- |
| I could hear/see clearly | | | | | |
| Understood concepts before break | | | | | |
| Understood concepts after break | | | | | |
| Confident trying on my own | | | | | |

**Analysis:** Compare before/after break. Avg <3 → revisit next day / follow-up resource in Slack.

---

## 44. Instructor Quick-Reference: Which Practice When?

| Topic Type | Best Practice | Time | Why It Works |
| :--- | :--- | :--- | :--- |
| Intro concept | Think-Pair-Share | 3 min | Activates prior knowledge |
| Definition | Explain It Simply | 2 min | Checks true understanding |
| Tech comparison | Match the Technology | 4 min | Low stakes, visual |
| Dense technical | Warm Cold-Call Recall | 2 min | Re-explains in peer voice |
| Demo | You Try It (Live) | 3 min | Embodied learning |
| Hallucination | Spot-the-Error | 4 min | Builds critical muscle |
| Evaluation | Spot-the-Error + Fact Check | 5 min | Verify habit |
| Prompting | Rewrite Challenge | 3 min | Iterative improvement |
| Model type | Match the Task | 3 min | Application, not memorization |
| Speech/audio | Listen & Compare | 3 min | Sensory |
| Multimodal | Image + Text Challenge | 4 min | Wow moment |
| Workflow | Demo → You Try It → Improve | 3 min per wf | Personal relevance |
| End-section | 🟢🟡🔴 Pulse | 2 min | Early detection |
| End-day | Exit Rating + Reflection | 3 min | Metacognition |

## 45. Instructor Rule: Never Let Practice Become Extra Lecture

**Bad:** Explain → explain → explain → explain → "Any questions?"

**Good:** Explain (2 min) → Demo (1 min) → You Try (2 min) → Debrief (1 min) → Clarify → Move

When you say "Now you try it" — STOP TALKING. Set timer visible. Roam. Let silence be productive.

The central purpose: Spread hands-on throughout both days, not save all practice for final breakout.

---

## 46. Setup Checklist (Both Days)

- [ ] Chrome + ChatGPT/Claude logged in + tested
- [ ] Coqui TTS XTTS-v2: huggingface.co/spaces/coqui/xtts — backup audio recorded
- [ ] Whisper demo + 2× 15 sec audio samples
- [ ] Sample charts/images for multimodal (in /assets)
- [ ] Teachable Machine tested
- [ ] Prompt Cards + Model Cards + Worksheets printed / shared as PDF
- [ ] Captions enabled, font 24pt+, contrast check (gold #d69e1d on charcoal #3b3b3b = use white text on charcoal, gold for accents only)
- [ ] Poll method ready: Mentimeter / Zoom Polls / Slack emoji 🟢🟡🔴
- [ ] Code of Conduct slide ready Day 1
- [ ] Timer (visible) + CBF playlist for break

## 47. Final Instructor Mindset

Objective is NOT memorizing every AI term.

Objective is participants leaving thinking:

> **"I understand the basics, I know how to experiment, and I can start using AI in my own work and daily life."**

Use the rhythm:

```text
Explain a little.
Show an example.
Let participants try.
Check understanding.
Correct confusion.
Move forward.
```

Close with:

> **"Start small. Experiment daily. AI is better with friends."**

---

## 48. MODULE TEMPLATE — For Modules 2 to 6 (Copy-Paste Ready)

> Duplicate this for each remaining module. Keeps facilitation consistent.

### Module [N]: [Title e.g., Computer Vision] — Practice Guide

**Module Goal:** [One sentence mental model]
**Prerequisite from M1:** [What they should already know]
**New Vocab (max 5):** [terms]
**Tools:** [e.g., Roboflow, Teachable Machine] + backup recordings
**Dataset / Assets:** [Sample images, etc.]

#### Day 1 Practice Plan — [Focus e.g., How It Sees]

| Time | Topic | Practice Type | Asset |
| :--- | :--- | :--- | :--- |
| | Section 1 | | |
| | Section 2 | | |
| | Pulse Check #1 | | |

#### Day 2 Practice Plan — [Focus e.g., Build With It]

| Time | Topic | Practice Type | Asset |
| :--- | :--- | :--- | :--- |
| | Section 3 | | |
| | Capstone | | |

#### Practice Details (Use Universal Pattern)

**Topic: [Topic Name]**
- **Explain (2m):** [Core idea in plain language]
- **Demo (1m):** [Exact prompt / file to use]
- **You Try It (2m):** [What participant does]
- **Debrief Q:** [Question that surfaces insight]
- **If 🟡/🔴:** [Different analogy/example]

#### Capstone Idea — Module [N]
[One project that proves independent use: e.g., Build a Teachable Machine model that classifies...]

#### Assessment Tweaks
[Any module-specific pulse check tweaks]

---

*Prepared for Coding Black Females · Practice Guide Companion to Instructor Guide v2.1 · Module 1 ACTIVE · Last updated 2026-08-21*
*Next: Add Overview slide deck titles to §34 Workflow Template, and paste into Module 2-6 templates.*
