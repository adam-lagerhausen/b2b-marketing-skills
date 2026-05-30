# Demo storyline example

## Example request

Use the `demo-storyline` skill to create a short B2B SaaS demo storyline.

Product context:

- Product: PipelineGuard, a revenue operations platform that detects risky enterprise deals and recommends next-best actions.
- Audience: VP Sales, RevOps leaders, and frontline sales managers at 300-2,000 employee B2B SaaS companies.
- Buyer pain: Forecast calls rely on rep notes, stale CRM fields, and manager intuition. Leaders find out too late that high-value deals are missing stakeholders, next steps, or executive alignment.
- Current workflow: Salesforce reports, spreadsheets, Slack deal reviews, and weekly forecast calls.
- Desired outcome: Improve forecast confidence and help managers intervene earlier on risky deals.
- Sales stage: First discovery call with a 12-minute product demo.
- Qualification goal: Confirm whether the buyer has enough pipeline risk, forecast pressure, and RevOps ownership to justify a deeper evaluation.
- Proof available: One customer reduced slipped enterprise opportunities by 18% in one quarter.

## Demo objective

Show how PipelineGuard helps sales and RevOps teams move from reactive forecast inspection to proactive deal-risk management.

## Target audience and assumed pain

Primary audience: VP Sales and RevOps leader.

Assumed pain: The team has a growing enterprise pipeline, but forecast confidence is low because deal health is assembled manually from CRM fields, rep updates, and manager judgment.

## Qualification goal

Learn whether pipeline risk is a real business problem, who owns the forecast process, what systems hold the data, and whether the buyer would prioritize a pilot around enterprise deal inspection.

## Scenario setup

"I will show one enterprise pipeline review. We will look at three deals that all look healthy in the CRM, identify which one is actually at risk, and show how a manager would act before the forecast call. I will pause after each step so you can tell me whether this matches how your team works."

## Realistic demo data

- Quarter: Q3 FY27
- Segment: North America Enterprise
- Manager: Priya Shah, Director of Enterprise Sales
- Rep: Marcus Lee
- Account: Northstar Logistics
- Opportunity: Northstar Logistics - Global Routing Platform
- Opportunity value: $420,000 ARR
- Stage: Security review
- Close date: August 28, 2027
- Risk score: 72 out of 100
- Risk reasons: no economic buyer activity in 21 days, procurement not added to plan, next meeting missing, mutual action plan incomplete
- Recommended action: Schedule VP-to-VP alignment call and add procurement owner by Friday

## Demo flow

### 1. Start with the forecast view

Product moment: PipelineGuard risk dashboard for Q3 enterprise opportunities.

Buyer pain it maps to: Leaders can see pipeline amount, but not which deals deserve attention before they slip.

What to say:

"Most teams already have dashboards that show stage, amount, and close date. The problem is that these fields often make risky deals look fine until the last two weeks of the quarter. Here, PipelineGuard starts with the same enterprise pipeline but adds a deal-risk layer based on activity, stakeholder coverage, next steps, and mutual action plan health."

What to show:

- Q3 enterprise pipeline filtered to opportunities above $250,000 ARR
- Three deals sorted by forecast category
- Risk badges next to Northstar Logistics, FinBank Systems, and ApexCare Health

Discovery question:

"On your current forecast call, how do managers decide which deals need deeper inspection?"

Pause/checkpoint:

"Does this resemble the way your team reviews enterprise pipeline today, or is your inspection process different?"

Likely confusion or objection:

"We already have Salesforce reports for this."

How to address it:

"That makes sense. This is not replacing the CRM report. The question is whether the report can tell you which deal is risky before the rep or manager has manually pieced it together. PipelineGuard is using CRM plus activity and process signals to prioritize where managers should spend time."

### 2. Open the risky deal

Product moment: Deal detail page for Northstar Logistics.

Buyer pain it maps to: Managers waste time reading notes and Slack threads to understand why a deal is at risk.

What to say:

"Let's open Northstar. On paper, this is a $420,000 ARR deal in security review with a close date this quarter. But the risk score is high because the signals behind the deal are not matching the forecast confidence."

What to show:

- Risk score: 72/100
- Timeline showing no economic buyer activity in 21 days
- Missing procurement stakeholder
- Mutual action plan with legal review complete, security review active, procurement blank, executive alignment blank

Discovery question:

"When a deal like this is forecasted to close, which of these signals would your managers trust most: activity, stakeholder coverage, next step quality, or rep judgment?"

Pause/checkpoint:

"Is this the level of detail a manager would need, or would they need to see different evidence before acting?"

Likely confusion or objection:

"How does it know the economic buyer is missing?"

How to address it:

"For the demo, the system is using contact role, meeting participation, email activity, and mutual action plan ownership. In a real evaluation, we would validate which signals are reliable in your Salesforce and engagement data."

### 3. Show the recommended manager action

Product moment: Recommended next-best action panel.

Buyer pain it maps to: Risk is identified too late, and managers still have to decide what to do next.

What to say:

"The goal is not just to flag a red deal. The goal is to make the manager's next move obvious. For Northstar, PipelineGuard recommends a VP-to-VP alignment call and adding procurement to the mutual action plan by Friday, because those are the two gaps most likely to block an August close."

What to show:

- Recommended action: Schedule VP-to-VP alignment call
- Suggested message for Marcus Lee to send to the champion
- Task assigned to Priya Shah to confirm procurement owner
- Expected impact: reduces close-date risk from high to medium if completed this week

Discovery question:

"When your managers spot risk today, do they have a standard playbook for what action to take, or does it depend on the manager?"

Pause/checkpoint:

"Would this kind of recommended action be helpful for your managers, or would they see it as too prescriptive?"

Likely confusion or objection:

"Our managers may not want a tool telling them how to run deals."

How to address it:

"That is a good concern. The recommendation is meant to create consistency, not remove judgment. Managers can accept it, edit it, or dismiss it, and RevOps can see which plays actually improve deal outcomes."

### 4. Close the loop for RevOps

Product moment: RevOps view showing recurring risk patterns across enterprise deals.

Buyer pain it maps to: RevOps can report forecast misses after the fact but struggles to identify process patterns early.

What to say:

"For RevOps, the value is not only one saved deal. It is seeing the pattern across the quarter. In this view, 37% of enterprise deals above $250,000 ARR are missing procurement before security review. That gives RevOps a process issue to fix, not just a list of deals to chase."

What to show:

- Risk pattern: procurement missing before security review in 14 of 38 enterprise deals
- Segment affected: North America Enterprise
- Suggested process change: require procurement owner before stage 5
- Customer proof placeholder: slipped enterprise opportunities reduced by 18% in one quarter

Discovery question:

"If you could see one recurring risk pattern across your enterprise pipeline, what would be most valuable: missing stakeholders, weak next steps, low activity, or stage aging?"

Pause/checkpoint:

"Is this more of a sales management problem for your team, a RevOps process problem, or both?"

Likely confusion or objection:

"This depends on data quality. Our CRM is not perfect."

How to address it:

"That is usually true. A pilot should start by testing a narrow set of signals where the data is reliable enough to drive action. We do not need perfect CRM hygiene to find useful risk patterns, but we do need to validate which signals are trustworthy."

## Recap slide

Title: PipelineGuard helps your team catch deal risk before the forecast slips

- Pain confirmed: Enterprise forecast reviews depend on manual inspection across CRM fields, rep updates, and manager judgment.
- What the demo showed: PipelineGuard identified a risky $420,000 ARR deal, explained the risk drivers, recommended a manager action, and surfaced a broader RevOps process pattern.
- Value: Managers know where to intervene earlier, RevOps sees repeatable risk patterns, and sales leaders get a more trustworthy forecast.
- Proof: One customer reduced slipped enterprise opportunities by 18% in one quarter.
- Open questions: Which CRM and engagement signals are reliable, who owns risk playbooks, and which segment should be used for a pilot.
- Recommended next step: Run a 30-minute pilot scoping session with VP Sales, RevOps, and one enterprise sales manager using last quarter's slipped deals.

## Qualification signals to listen for

Positive signals:

- Buyer describes a specific forecast miss or slipped enterprise deal.
- Buyer names the current forecast owner and inspection process.
- Buyer asks whether PipelineGuard integrates with Salesforce, Gong, Outreach, or Clari.
- Buyer wants to test the model on last quarter's opportunities.
- Buyer asks which managers or segments should join a pilot.

Negative signals:

- Buyer is only curious about AI scoring but has no forecast pain.
- Buyer cannot identify who would own the workflow.
- Buyer says managers already inspect deals consistently and do not need a process change.
- Buyer asks for a recording but does not agree to a deeper working session.

## Assumptions and missing proof

- Assumption: The buyer has enough Salesforce and engagement data to create basic risk signals.
- Assumption: Enterprise deals have a multi-stakeholder sales process where missing procurement or executive alignment matters.
- Missing proof: Need customer-approved quote and details behind the 18% reduction in slipped opportunities.
- Missing proof: Need implementation timeline and data requirements for a pilot.
