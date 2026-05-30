# B2B PMM orchestrator example

## Scenario

Company: LedgerPilot

Product context: LedgerPilot sells AI-assisted accounting workflow software to finance teams at fast-growing B2B SaaS companies.

User request:

> We are launching an AI close assistant next quarter. We have some sales notes, a rough product brief, and an early landing page draft. I need help turning this into a real GTM plan, not just better copy.

Available inputs:

- Sales notes from five opportunities
- Product brief for the AI close assistant
- Draft landing page
- No formal positioning framework
- Two beta customers, one with quantified time savings
- Launch date target: next quarter
- Business goal: create pipeline and help sales explain the new AI workflow credibly

## 1. Diagnosis

This is not only a launch problem. It is a full GTM sequencing problem.

The request includes:

- Customer evidence: sales notes and beta feedback
- Product input: product brief
- Draft asset: landing page
- Launch need: next-quarter announcement and plan
- Sales need: clearer explanation and credibility around AI

The highest-risk failure mode is jumping straight into launch copy before the team has made the positioning choices.

Known facts:

- Target market appears to be finance teams at fast-growing B2B SaaS companies.
- The product helps with month-end close workflows.
- There is at least some customer evidence and one quantified proof point.
- Sales needs a credible way to explain AI value without sounding generic.

Assumptions to validate:

- The economic buyer is likely a VP Finance, Controller, or CFO.
- The status quo is spreadsheets, manual checklist tools, ERP exports, Slack follow-ups, and recurring close meetings.
- The real pain is not "AI automation" but late, risky, manual close coordination.

## 2. Recommended path

Use this sequence:

1. `voice-of-customer-synthesis`
2. `positioning-messaging-framework`
3. `launch-tier-framework`
4. `demo-storyline`
5. `customer-story-engine`
6. `ai-pmm-reviewer`

Why this order:

- Start with sales notes and beta feedback so the GTM story is grounded in buyer pain.
- Build positioning before launch planning so the launch has a clear audience, alternative, differentiated value, and proof.
- Classify the launch after the strategic value is clear.
- Build the demo once the positioning tells us what pain and outcome the demo needs to prove.
- Package beta proof into customer-story material.
- Review the landing page and launch assets at the end, once the strategy exists.

Do not start by rewriting the landing page. That would polish the visible symptom before fixing the GTM system.

## 3. First artifact to create

The smallest useful first artifact is a voice-of-customer synthesis from the sales notes and beta feedback.

It should produce:

- Primary buyer pains
- Buying triggers
- Current workaround/status quo
- Exact customer language
- Objections and trust concerns around AI
- Proof points already available
- Gaps in evidence
- Messaging implications

This artifact unlocks the positioning framework and prevents the team from writing generic AI messaging.

## 4. Inputs needed

Ask for only the inputs that materially improve the next step:

1. Sales notes from the five opportunities
2. Beta customer notes or quotes
3. The quantified time-savings proof point
4. Product brief for the AI close assistant
5. Draft landing page, if review is expected later

Do not ask for a full launch plan, competitive matrix, ICP doc, content calendar, or campaign brief yet. Those may come later, but they are not required to start.

## 5. Proposed workflow

### Step 1: Voice of customer synthesis

Use `voice-of-customer-synthesis` on the sales notes and beta feedback.

Expected output:

- What finance teams are actually struggling with during close
- What makes the problem urgent now
- How they solve it today
- Which words they use to describe the pain
- Which AI claims they trust or distrust
- What proof matters

Stop condition:

The team can say, "Here are the top 3 pains and here is the customer language behind them."

### Step 2: Positioning and messaging

Use `positioning-messaging-framework` after VOC.

Expected output:

- Target segment
- Primary buyer and user
- Status quo alternative
- Differentiated value
- Reasons to believe
- Positioning statement
- Messaging pillars
- Claims to avoid

Stop condition:

The team can explain who this is for, what painful old way it replaces, why LedgerPilot is better, and what proof supports the claim.

### Step 3: Launch tier and plan

Use `launch-tier-framework` once positioning is clear.

Expected output:

- Launch tier recommendation
- Rationale
- Audience and goal
- Launch narrative
- Channel mix
- Sales, customer, and product enablement plan
- Follow-on launch motions beyond announcement day

Likely recommendation:

Tier 2 campaign-level launch unless the AI assistant materially changes company positioning, has strong differentiated proof, and can support an executive/category narrative.

Stop condition:

The team knows how much GTM investment this launch deserves and what success should look like.

### Step 4: Demo storyline

Use `demo-storyline` to turn the positioning into a credible demo.

Expected output:

- Discovery questions
- Before-state workflow
- Demo data and scenario
- Key moments to show
- Proof and recap
- Buyer-specific talk track

Stop condition:

Sales can show the AI close assistant as a solution to a painful close-management problem, not as a generic AI feature tour.

### Step 5: Customer story engine

Use `customer-story-engine` for the two beta customers.

Expected output:

- Customer proof brief
- Before state
- Trigger
- Product role
- Outcome
- Approved claims and missing proof
- Reusable sales proof snippets

Stop condition:

The launch and sales story have credible proof, not invented AI claims.

### Step 6: AI PMM reviewer

Use `ai-pmm-reviewer` on the landing page, launch copy, sales narrative, and demo outline.

Expected output:

- Strategic gaps
- Generic AI language
- Unsupported claims
- Proof gaps
- Voice issues
- Recommended rewrites

Stop condition:

The launch assets are specific, believable, differentiated, and tied to customer evidence.

## 6. What not to do

Do not:

- Rewrite the landing page first
- Call this a Tier 1 launch because it includes AI
- Invent customer quotes or ROI claims
- Build a full category POV unless the company wants to own a broader market problem
- Create a giant campaign calendar before the launch tier is clear
- Let the demo become a feature walkthrough

## 7. Final orchestrator recommendation

Start with VOC synthesis.

The first agent instruction should be:

```text
Use the voice-of-customer-synthesis skill to synthesize these sales notes and beta feedback for LedgerPilot's AI close assistant. Extract pains, triggers, current workaround, exact customer language, objections, proof points, and messaging implications. Label confidence and do not invent proof.
```

After that, proceed to positioning, launch tiering, demo storyline, customer proof, and final review.
