---
name: marketing-research
description: >
  Use this skill for any marketing research, product positioning, copywriting research, or audience profiling task.
  Triggers include: "research my product", "develop my value proposition", "profile my avatar", "understand my market",
  "create a unique mechanism", "market awareness", "market sophistication", "ideal customer profile", "ICP research",
  "positioning research", "copywriting research", "features and benefits", "competitor research", "competitive analysis",
  or any request to deeply research a product or audience for marketing purposes. Use this skill proactively whenever
  a user wants to prepare materials for sales copy, landing pages, ads, email sequences, or any persuasion-focused
  content. If a user says "help me understand my market", "I need to figure out my messaging", "who is my customer",
  or "what makes my product different", this skill applies immediately.
---

# Marketing Research Sourcebook

A structured, practitioner-grade research system for products, avatars, markets, competitors, and positioning.

---

## WRITING RULES (Apply to Every Module)

These rules govern ALL output. Follow them without exception.

**Style:**
1. Never use em dashes. Use periods, commas, colons, or separate sentences instead.
2. Minimize parenthetical content. If something matters, give it a full sentence. If it does not matter, cut it.
3. Write in active voice. Short paragraphs. Plain language. No hedging.
4. Lead every section with the sharpest insight, not setup or context. Put the point first.
5. Each sentence should earn its place. Cut filler words, throat-clearing phrases, and anything that restates what the reader already knows.
6. Use "not X, but Y" constructions sparingly. Once per section at most.

**Structure:**
7. Tables over prose. Default to tables for comparisons, feature lists, competitor maps, and multi-dimension analysis.
8. One paragraph max per competitor in landscape maps.
9. Dimensionalized benefits: 3-4 sentences. One vivid scenario, not a narrative.
10. No "Chain-Forward Summary" sections. Context carries forward internally.
11. Mechanism stories: 1 short paragraph setup + 1 short paragraph outcome.
12. Value propositions stay full-length. These are copy assets.
13. Mental model reframes: 1 example per model. Pick the strongest.
14. Target module length: 100-150 lines. Full run approximately 600-700 lines total.
15. Use web search for competitor research. Pull current data.
16. Deliver each module as a single markdown file.

---

## STEP 0: INTAKE INTERVIEW (Always Start Here)

Ask all questions at once:

```
Before we dive in, I need a few details:

1. What is your product? Short description: what it is, what it does, who it serves.
2. What are the main components, features, or chapters?
3. Who is your ideal customer? Their role, situation, and what they want.
4. Do you have any named competitors? Even 2-3 is enough.
5. What stage are you at?
   a) Just starting. Need everything.
   b) Have a product defined. Need avatar and market research.
   c) Have avatar research done. Need positioning and copy angles.
   d) Have everything. Need a competitor comparison.
```

Store answers as the **Research Context Block** and reference throughout. Never re-ask captured information.

---

## STEP 1: DIAGNOSTIC

| Stage | Module Sequence |
|-------|----------------|
| Need everything | 0, 1, 2, 3, 4 |
| Have product, need avatar + market | 2, 3, 4 |
| Have avatar, need positioning | 4, 5 |
| Need competitor comparison | 0, 4 |

Tell the user which module you are starting with and why. Then proceed.

---

## MODULE 0: COMPETITOR RESEARCH

*Goal: Map what is already promised, already heard, and where the gap is.*

Use web search to pull current competitor data.

If current X/Twitter signals matter and Hermes Tweet is installed, use it for
public posts, account context, keyword signals, or competitor narratives. Use
those signals as evidence only. If Hermes Tweet or `XQUIK_API_KEY` is
unavailable, note that live X/Twitter evidence is unavailable and continue with
web search. Never post, like, repost, follow, delete, or change account state
from this skill.

### Competitor Landscape Map

For each competitor, deliver a **single table row**:

| Competitor | Core Promise | Unique Mechanism | Target Avatar | Sophistication Level (1-5) | Positioning Gap |
|------------|-------------|-----------------|---------------|---------------------------|-----------------|

Below the table, add **one paragraph per competitor** expanding on the most strategically important gap. Then list 2-3 **saturated claims** the market has already heard too many times.

### Competitive Gap Analysis

Four concise sections. Use tables or short bullets, not paragraphs:
1. **Overcrowded angles**: what everyone is saying. 3-5 items, one line each.
2. **Underserved desires**: what no one addresses well. 3-5 items, one line each.
3. **Open positioning territories**: 3 territories, each described in 2-3 sentences.
4. **Most underserved sophistication level**: which level and why, in one paragraph.

### Differentiation Pressure Test

Deliver as a table plus brief commentary:

| Dimension | Competitors (consensus) | Our Product (potential) |
|-----------|------------------------|----------------------|

Then answer bluntly in 1-2 paragraphs: Does the product sound like anyone else? Where is it genuinely different? What stops a Level-4 buyer mid-scroll?

### Competitor Comparison Table

Close Module 0 with:

| Competitor | Core Claim | Unique Mechanism | Soph. Level | Gap/Weakness | How We Are Different |
|------------|-----------|-----------------|-------------|--------------|---------------------|

Include a final row for our product.

---

## MODULE 1: PRODUCT

*Goal: Uncover features, benefits, and a Unique Mechanism differentiated from competitors.*

Reference competitive gaps from Module 0. The mechanism must occupy territory competitors are NOT claiming.

### Features, Benefits, Dimensionalize

Deliver **directly as a table**:

| Feature | Problem Solved | Benefit | Dimensionalized Benefit (3-4 sentences) |
|---------|---------------|---------|----------------------------------------|

### Unique Mechanism

For each feature, describe how it works step-by-step: problem, actions, new outcomes. **One concise paragraph per feature.** Avoid anything competitors already claim.

### Name the Unique Mechanism

Generate 15-20 names grouped by 3-4 themes:

| Theme | Name Options |
|-------|-------------|

### Mechanism with Story

For the chosen mechanism: **1 paragraph** on how it works. **1 paragraph** on a real-world before/during/after scenario.

**On request:** Expand a specific mechanism with product detail. Generate 10 additional names. Refine names toward a specific style.

---

## MODULE 2: AVATAR

*Goal: Build a deep emotional and psychological profile of your ideal buyer.*

### Primary Desires (6)

List 6 deep emotional and psychological desires. Each: **name + 2-3 sentence description**. Go beyond surface wants. Uncover identity-level drives.

### Primary Problems (6)

List 6 problems. Mix external frustrations with internal fears. Each: **name + 2-3 sentence description**.

**On request:** Expand one problem in depth. First-person rewrite as a spouse conversation and midnight journal entry. Refine a desire for financial freedom angle.

### Primary Conflict

One paragraph. Express the tension between the top desire and the top problem. What is in the way? What have they tried? What does the internal struggle sound like?

### Master Avatar

Deliver as a **single structured table**:

| Category | Emotional Detail | Logical/Practical Detail |
|----------|-----------------|-------------------------|
| Hell (without product) | | |
| Heaven (with product) | | |
| Pains (fears, frustrations) | | |
| Gains (wants, hopes, dreams) | | |
| See (marketplace, competitors, peers) | | |
| Say (to self, team, spouse) | | |
| Hear (from board, team, vendors, inner voice) | | |
| Do (what is not working, making it worse) | | |

Each cell: 3-5 bullet points. Concise, specific, visceral.

---

## MODULE 3: MARKET

*Goal: Map where your avatar sits on Awareness and Sophistication spectrums.*

Use competitor sophistication levels from Module 0 to calibrate.

### State of Awareness

Deliver as a **table** using first-person language throughout:

| Awareness Stage | Emotional State (2-3 bullets) | Logical State (2-3 bullets) | What Moves Them Forward (1 sentence) |
|----------------|------------------------------|----------------------------|--------------------------------------|
| Unaware | | | |
| Problem-Aware | | | |
| Solution-Aware | | | |
| Product-Aware | | | |
| Most-Aware | | | |

### State of Sophistication

Deliver as a **table**:

| State | Description | 3 Claims That Land |
|-------|------------|-------------------|
| 1. First exposure | Simple, direct, bold | |
| 2. Early awareness | Dramatized, bigger | |
| 3. Jaded | New mechanism they have not seen | |
| 4. Burned | Faster, easier, more certain. Solves what past tools missed. | |
| 5. Checked out | New identity, not a better version | |

Close with one paragraph naming the primary sophistication target and why.

---

## MODULE 4: VALUE PROPOSITION

*Goal: Synthesize everything into 4 positioning statements. Emotionally resonant, logically sound, competitor-differentiated.*

Inputs needed from prior modules: Unique Mechanism, Primary Conflict, Competitive gaps, Avatar's deepest desire and deepest pain.

### Value Proposition Development

Write 4 value propositions. Each must:
1. Speak to the avatar's primary desire or pain
2. Reference the unique mechanism specifically
3. Sound nothing like what competitors are saying
4. Be detailed, specific, and emotionally resonant. Not a tagline.

**These are copy assets. Keep them full-length. One paragraph each. Do not compress.**

After the 4 VPs, add a summary table:

| VP# | Name | Core Hook | Best Used For |
|-----|------|-----------|---------------|
| 1 | | | Homepage / Hero |
| 2 | | | Product Page |
| 3 | | | Sales Deck |
| 4 | | | Thought Leadership |

**On request:** Conflict-led rewrites. Component-specific zoom for a single feature.

---

## MODULE 5: MENTAL MODELS

*Goal: Reframe research outputs through psychological and strategic lenses for fresh copy angles.*

Apply to any output from Modules 0-4. Pick the 3-4 most relevant models, not all 15. For each model used, provide **1 specific copy or messaging example**.

### Mental Model Library

**Emotion-based:**
- **Jealousy Tendency**: What do they see others achieving?
- **Loss Aversion**: What are they losing every day without this?
- **Identity Threat**: How does the problem threaten who they believe they are?
- **Social Proof Cascade**: How does others' success make them feel left behind?

**Logic-based:**
- **Inversion**: What guarantees failure? Position product as the antidote.
- **First Principles**: Strip assumptions. What is the core truth?
- **Second-Order Thinking**: What happens in 6 months if unsolved?
- **Opportunity Cost**: What are they giving up by not solving this now?

**Positioning:**
- **Category Creation**: New category, not a better version of existing?
- **Jobs To Be Done**: What job are they actually hiring this to do?
- **The Challenger Sale**: Teach something new, then position as logical next step.
- **Blue Ocean**: What can be eliminated or reduced? What new factors introduced?

**Narrative:**
- **The Hero's Journey**: Avatar as hero, product as guide.
- **Before/After/Bridge**: Vivid before, aspirational after, product as bridge.
- **Enemy Framing**: Name the external enemy so failure is not their fault.

### Output Format

Deliver as a table:

| Mental Model | Reframed Angle | Copy/Messaging Example |
|-------------|---------------|----------------------|

Close with: **Top 3 Priority Angles**. One sentence each naming the angle and where to use it.

---

## OUTPUT TEMPLATES

Generate these after completing the relevant modules.

### Avatar Profile (after Module 2)

Single-page structured profile: Avatar name, one-sentence description, top 3 desires, top 3 problems, primary conflict in one paragraph, heaven state in 3 bullets, hell state in 3 bullets, key language patterns as 5-7 phrases, awareness level, sophistication level.

### Positioning Canvas (after Modules 0, 1, 4)

Single-page structured brief: Product name, Unique Mechanism as name plus one sentence, primary competitive gap, sophistication target with rationale, 4 value propositions in one line each, top 3 copy angles, one ownable sentence no competitor is saying.

### Competitor Comparison Table (after Module 0)

Included as part of Module 0 output.

---

## FULL RESEARCH RUN

| Step | Module | Output |
|------|--------|--------|
| 1 | Intake Interview | Research Context Block |
| 2 | Module 0: Competitor Research | Landscape map + gap analysis + pressure test + comparison table |
| 3 | Module 1: Product | Feature/benefit table + Unique Mechanism name + story |
| 4 | Module 2: Avatar | Master avatar table + conflict statement |
| 5 | Module 3: Market | Awareness table + Sophistication table + target |
| 6 | Module 4: Value Proposition | 4 VPs + usage matrix |
| 7 | Module 5: Mental Models | 3-4 reframes + top 3 priority angles |
| 8 | Output Templates | Avatar Profile + Positioning Canvas |

Each module feeds the next. Never skip the intake.
