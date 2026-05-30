# B2B Marketing Skills for AI Agents

Open-source B2B product marketing skills for AI agents, built from 10+ years of hands-on GTM work at Salesforce, Dropbox, Zeplin, ServiceNow, and startups.

This is not a prompt pack.

It is a practical PMM operating system for agents: customer research, positioning, messaging, launches, sales narratives, demos, customer proof, category POVs, and review workflows that keep AI output grounded in buyer truth.

## The thesis

AI will make an average PMM faster. It will not make an average PMM better.

Most AI marketing output has the same problem: it trends toward the average of everything it has seen before. The result is fluent, familiar, forgettable copy.

"Game-changing."

"Unlock growth."

"Streamline your workflow."

"Not just X, but Y."

Buyers have built an immune response to this stuff. If your messaging sounds like everyone else's, it is invisible.

The real value of AI in product marketing is not writing more words. It is helping PMMs think, synthesize, review, pressure-test, and turn messy inputs into sharper decisions.

AI gets you to 60% fast. The last 40% — the part that makes a customer say, "that's exactly my problem" — comes from customer conversations, market instinct, hard positioning choices, proof, and taste.

This repo is about encoding that last 40% into reusable agent skills.

## Why this exists

Product marketing changes shape from company to company. The product changes. The category changes. The buyer changes. The GTM motion changes.

But the fundamentals do not:

1. Know the target audience.
2. Understand their problem.
3. Understand how they solve it today.
4. Define how your product solves it better.
5. Turn that value into clear positioning and everyday language.
6. Get the story into market through sales, launches, demos, proof, content, and enablement.

Voice of the customer is the currency of PMM. Without it, you have opinion. With it, you can say, "I talked to 10 customers, and here's what they said."

These skills are built around that belief.

## What makes this different

Most marketing prompt libraries help AI produce more output.

This repo is designed to help AI agents produce better product marketing judgment.

The skills push agents to:

- start with customer truth, not clever copy
- separate what customers said from what PMM inferred
- identify the real buyer, user, influencer, and economic decision-maker
- name the status quo and real alternative
- make hard segmentation choices
- translate product capabilities into business outcomes
- distinguish positioning problems from copywriting problems
- build sales stories that reps can actually use
- create launches around customer value, not internal excitement
- pressure-test whether a message would still work if a competitor's logo were swapped in
- catch generic AI language before it reaches buyers

## Start here

If you are not sure which skill to use, start with the orchestrator.

| Skill | What it does | Example |
| --- | --- | --- |
| [B2B PMM orchestrator](skills/b2b-pmm-orchestrator/SKILL.md) | Routes vague GTM requests to the right PMM skill, sequences multi-step workflows, and keeps the agent focused on the smallest useful artifact that moves the business forward. | [example](examples/b2b-pmm-orchestrator-example.md) |

Use the orchestrator when the request is broad, messy, or cross-functional:

- "Help me with positioning."
- "We need a launch plan."
- "Turn these customer notes into messaging."
- "Make this sales deck better."
- "Build the GTM system for this product."

It diagnoses the PMM problem, chooses the right downstream skill, and prevents the agent from generating every possible artifact just because it can.

## The skill suite

| Skill | What it does | Example |
| --- | --- | --- |
| [Voice of customer synthesis](skills/voice-of-customer-synthesis/SKILL.md) | Turns calls, notes, interviews, sales feedback, surveys, and research into PMM-ready inputs: pains, triggers, JTBD, alternatives, objections, exact language, proof, and messaging implications. | [example](examples/voice-of-customer-synthesis-example.md) |
| [Positioning and messaging framework](skills/positioning-messaging-framework/SKILL.md) | Turns customer truth into target segment, buyer, real alternative, differentiated value, reasons to believe, positioning, and messaging pillars. | [example](examples/positioning-messaging-framework-example.md) |
| [Sales narrative deck](skills/sales-narrative-deck/SKILL.md) | Turns positioning into a first-call sales story with slide titles, talk track, proof, demo moments, recap, and CTA. | [example](examples/sales-narrative-deck-example.md) |
| [Launch tier framework](skills/launch-tier-framework/SKILL.md) | Classifies product moments into launch tiers and builds a season-of-launch plan instead of a one-day Big Bang. | [example](examples/launch-tier-framework-example.md) |
| [Customer story engine](skills/customer-story-engine/SKILL.md) | Turns customer wins into story briefs, case studies, one-pagers, and sales proof without inventing claims. | [example](examples/customer-story-engine-example.md) |
| [Demo storyline](skills/demo-storyline/SKILL.md) | Builds demos around buyer pain, realistic data, discovery questions, qualification signals, proof, and a clear recap. | [example](examples/demo-storyline-example.md) |
| [Category point of view](skills/category-point-of-view/SKILL.md) | Defines the market shift, problem to own, category frame, enemy/status quo, narrative pillars, and content system. | [example](examples/category-point-of-view-example.md) |
| [AI PMM reviewer](skills/ai-pmm-reviewer/SKILL.md) | Reviews AI-generated marketing against customer truth, positioning, proof, voice, plain English, and common AI tells. | [example](examples/ai-pmm-reviewer-example.md) |

## How the skills work together

You do not need every skill every time. The point is to give the agent the right PMM judgment at the right moment.

If you only read one example, start here:

- [Full GTM system example: from customer notes to launch-ready PMM system](examples/full-gtm-system-example.md)

Common workflows:

### Customer notes to positioning

```text
b2b-pmm-orchestrator
→ voice-of-customer-synthesis
→ positioning-messaging-framework
→ ai-pmm-reviewer
```

Use when you have customer calls, sales notes, or research and need sharper positioning or messaging.

### Product launch workflow

```text
b2b-pmm-orchestrator
→ launch-tier-framework
→ positioning-messaging-framework
→ demo-storyline
→ customer-story-engine
→ ai-pmm-reviewer
```

Use when a product or feature needs a GTM plan, launch tier, story, demo, proof, and final QA.

### Sales narrative workflow

```text
b2b-pmm-orchestrator
→ voice-of-customer-synthesis
→ positioning-messaging-framework
→ sales-narrative-deck
→ demo-storyline
→ ai-pmm-reviewer
```

Use when sales needs a clearer story, first-call deck, founder pitch, or executive narrative.

### Category POV workflow

```text
b2b-pmm-orchestrator
→ category-point-of-view
→ positioning-messaging-framework
→ sales-narrative-deck
→ ai-pmm-reviewer
```

Use when the company needs to own a problem, shape a market narrative, or build thought leadership that supports selling.

### Review and rescue workflow

```text
b2b-pmm-orchestrator
→ ai-pmm-reviewer
→ the domain skill that matches the problem
→ ai-pmm-reviewer
```

Use when you already have a landing page, launch post, deck, email, or AI-generated draft that feels generic or strategically weak.

## Operating principles

These are the beliefs behind the skills.

### 1. Start with the customer

If you do not know the audience, pain, status quo, trigger, and buying context, you are guessing.

### 2. Positioning is not messaging

Positioning is how you want the customer to frame the decision: who this is for, what problem it solves, what alternative it replaces, and why your product is meaningfully better.

Messaging turns that strategy into everyday language.

Copywriting makes the words clear.

Do not fix a positioning problem with prettier copy.

### 3. The status quo is usually the real competitor

The alternative is not always another vendor. It may be spreadsheets, meetings, manual work, internal tools, inertia, or doing nothing.

Strong PMM names the old way before introducing the new one.

### 4. Launches are not one day

A good launch is not a Big Bang announcement. It is a season of launch: the right narrative, tier, proof, sales motion, customer communication, campaign, demo, and follow-on tactics matched to the business goal.

### 5. Sales stories need to be usable

A sales narrative is not a brand manifesto. It has to survive a real first call, map to buyer pain, handle objections, create urgency, and give reps something useful to say.

### 6. Demos should prove the story

A demo is not a feature tour. It should show the buyer's pain, the old workflow, the new workflow, and the business outcome in a way that feels real.

### 7. Proof beats adjectives

Do not say "powerful," "seamless," or "game-changing" if a customer quote, metric, workflow, or concrete example can do the job better.

### 8. AI should review as much as it writes

AI is useful for finding gaps, comparing drafts against messaging, summarizing customer calls, and pressure-testing claims. The best use of AI is often critique, not generation.

## Who this is for

This repo is for:

- Product marketers using AI agents in real work
- Founders who need sharper B2B positioning and messaging
- GTM teams building sales narratives, launch plans, demos, and enablement
- PMM leaders building repeatable systems for research, positioning, launches, proof, and sales enablement
- AI-agent builders who want marketing workflows grounded in judgment, not generic prompts

It is especially useful for B2B SaaS, enterprise software, AI products, platform products, developer/API products, and category-creating startups where the hard part is translating complexity into clear buyer value.

## Where this comes from

These skills are based on notes, frameworks, and patterns collected across 10+ years of B2B SaaS product marketing work:

- **Salesforce:** messaging, positioning, and sales enablement for Sales Cloud in a high-velocity enterprise environment
- **Dropbox:** company-wide product launch framework, GTM strategy, and global sales enablement for Dropbox Sign
- **Zeplin:** repositioning from handoff tool to design delivery platform, market research, product launches, and persona-targeted campaigns
- **ServiceNow:** AI Trust positioning, AI Control Tower launch, C-level narrative, enterprise AI governance messaging, and field enablement
- **Startups:** AI-native GTM, interactive demo strategy, content, category narrative, and sales-efficiency work

The common thread: make complex products clear, credible, and adoptable.

## How to use

This repo is designed for AI-agent environments that support markdown-based skills.

Basic pattern:

1. Start with `b2b-pmm-orchestrator` if you are not sure which skill applies.
2. Copy or install the relevant skill into your agent environment.
3. Give the agent your product context, customer notes, sales calls, research, roadmap, or draft asset.
4. Ask the agent to use the skill.
5. Review the output like a PMM. Keep the customer truth. Sharpen the judgment. Rewrite the final words in your own voice.

Example prompts:

```text
Use the b2b-pmm-orchestrator skill to decide which PMM workflow we should run for this GTM problem. Recommend the smallest useful next artifact before generating anything.
```

```text
Use the voice-of-customer-synthesis skill to turn these customer interview notes into pains, triggers, objections, exact language, and messaging implications.
```

```text
Use the positioning-messaging-framework skill to create positioning and messaging for this B2B SaaS product. Push back if the segment is too broad or the differentiation is weak.
```

```text
Use the sales-narrative-deck skill to turn this positioning into a first-call sales deck outline for enterprise buyers.
```

```text
Use the ai-pmm-reviewer skill to review this launch post against our positioning, customer evidence, and voice. Tell me what sounds generic before rewriting it.
```

## Status

This repo is being built in public.

The goal is not to create a giant library of marketing prompts. The goal is to create a focused set of B2B product marketing skills that help AI agents produce work a senior PMM would actually respect.

## License

MIT
