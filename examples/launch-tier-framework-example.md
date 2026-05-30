# Launch tier framework example

## Scenario

Company: NorthstarOps

Product context: NorthstarOps sells operations software to B2B field service companies that coordinate technicians, parts, service-level commitments, and customer communications across multiple regions.

Fictional roadmap inputs for Q3:

1. Predictive dispatch optimizer
   - Uses service history, technician skills, parts availability, location, and SLA risk to recommend the best technician for urgent jobs.
   - Target audience: VP Operations, Dispatch Directors, Regional Service Managers.
   - Goal: drive pipeline with enterprise and upper mid-market field service teams.
   - Proof: beta customer saw a 14% reduction in missed SLA windows during a 60-day pilot.

2. Customer ETA portal
   - Gives end customers a branded page with technician ETA, job status, and rescheduling options.
   - Target audience: operations leaders, customer experience leaders, dispatch teams.
   - Goal: reduce inbound status calls and improve customer experience.
   - Proof: two design partners, no quantified results yet.

3. Mobile offline mode
   - Lets technicians view assigned jobs, capture notes, and sync updates when connectivity returns.
   - Target audience: field technicians, service managers, CS for existing customers.
   - Goal: improve adoption and retention for customers with rural or industrial job sites.
   - Proof: high volume of customer requests and support tickets.

4. Salesforce Service Cloud integration
   - Syncs work order status, account context, and service history between NorthstarOps and Salesforce.
   - Target audience: enterprise prospects and existing customers using Salesforce.
   - Goal: unblock late-stage deals and expansion opportunities.
   - Proof: three named opportunities have asked for it.

5. Admin permission templates
   - Gives admins reusable role templates for dispatchers, technicians, managers, and contractors.
   - Target audience: admins and IT owners at existing customers.
   - Goal: reduce onboarding friction and support tickets.
   - Proof: customer advisory board requested it.

6. Dark mode for dispatcher console
   - UI preference for teams running overnight dispatch operations.
   - Target audience: dispatcher users.
   - Goal: improve user satisfaction.
   - Proof: requested in community forum.

7. Executive operations dashboard
   - Shows SLA performance, technician utilization, repeat visits, regional backlog, and customer escalation trends.
   - Target audience: VP Operations, COO, regional leaders.
   - Goal: support expansion conversations and executive-level value reporting.
   - Proof: prototype validated with five customers.

## 1. Executive summary

NorthstarOps should avoid treating Q3 as one announcement-day pileup. The stronger approach is a Season of Launch around the theme "Protect every service commitment before it becomes a customer escalation." The anchor should be a Tier 1 company-level launch that bundles Predictive Dispatch Optimizer, Customer ETA Portal, and Executive Operations Dashboard into a broader story about preventing missed SLAs, giving customers clearer updates, and helping executives manage service reliability. Salesforce Service Cloud Integration should run as a Tier 2 campaign-level launch for enterprise pipeline and expansion. Mobile Offline Mode should be a Tier 3 targeted adoption and retention launch for existing customers in low-connectivity environments. Admin Permission Templates and Dark Mode should stay Tier 4 release-note or enablement-only updates.

Launch day should create awareness for the larger service reliability story. The follow-on motion should move buyers through consideration and acquisition with demos, webinars, sales plays, customer proof, and account targeting, while also driving adoption and retention among existing customers.

## 2. Roadmap classification table

| Item or bundle | Target audience | Customer problem | Business goal | Recommended tier | Rationale | Confidence |
|---|---|---|---|---|---|---|
| Service Reliability Launch: Predictive Dispatch Optimizer + Customer ETA Portal + Executive Operations Dashboard | VP Operations, COO, Dispatch Directors, CX leaders at upper mid-market and enterprise field service companies | Missed service windows, fragmented dispatch decisions, poor customer visibility, and weak executive reporting undermine SLA performance and trust | Awareness, pipeline, revenue, expansion, executive-level perception | Tier 1: Company-level launch | The bundle creates a coherent company narrative around protecting service commitments. It has buyer-level value, executive relevance, demo potential, and at least one quantified beta proof point | Medium-high |
| Salesforce Service Cloud Integration | Enterprise prospects and customers standardized on Salesforce | Service and customer teams lack shared work order/account context across systems | Pipeline acceleration, expansion, competitive response | Tier 2: Campaign-level launch | Important for a valuable segment and late-stage deals, but it is not the main company story. Best as a targeted campaign and sales play | High |
| Mobile Offline Mode | Existing customers with rural, industrial, or low-connectivity job sites; field technicians and service managers | Technicians cannot reliably update jobs in the field when connectivity drops | Adoption, retention, customer confidence | Tier 3: Targeted launch | High customer value for a specific segment, but limited broad market story. Needs lifecycle comms, CS enablement, and adoption tracking | High |
| Admin Permission Templates | Admins, IT owners, implementation teams | Admin setup takes too long and creates avoidable support questions | Adoption, onboarding efficiency, support reduction | Tier 4: Release-note or enablement-only update | Useful enhancement but not a launch moment. Communicate through release notes, docs, support, and CS | High |
| Dark Mode for Dispatcher Console | Dispatcher users, especially overnight teams | Dispatcher preference and visual comfort during long shifts | User satisfaction | Tier 4: Release-note or enablement-only update | Good product polish, not a GTM story. Include in release notes and community update | High |

## 3. Bundle vs separate recommendations

### Bundle

Bundle these three into the main Service Reliability Launch:

- Predictive Dispatch Optimizer
- Customer ETA Portal
- Executive Operations Dashboard

Why:

- They share the same strategic narrative: protect service commitments before they become customer escalations.
- They matter to the same buying committee: operations executives, dispatch leaders, and customer experience stakeholders.
- Together they show a complete before/during/after story:
  - Predict risk and assign the right technician.
  - Keep customers informed while the job is in motion.
  - Show executives where service reliability is improving or breaking down.
- The bundle is stronger than any single feature because it ladders from dispatch workflow to customer trust to executive business outcomes.

### Keep separate

Keep Salesforce Service Cloud Integration separate.

Why:

- It serves a specific systems and enterprise-sales audience.
- The business goal is pipeline acceleration and expansion among Salesforce accounts, not broad market awareness.
- It needs account targeting, sales plays, integration demos, and partner/customer proof more than a broad launch narrative.

Keep Mobile Offline Mode separate.

Why:

- It is highly valuable for a specific customer environment, but it does not belong in the main service reliability buyer narrative unless proof shows it materially reduces SLA misses.
- It should be targeted to existing customers and prospects with low-connectivity technician workflows.

Keep Admin Permission Templates and Dark Mode out of launch storytelling.

Why:

- They are useful product improvements but would dilute the main narrative.
- They are better handled through release notes, docs, in-app education, community, and support enablement.

## 4. Tier rationale by item

### Service Reliability Launch bundle

Customer impact:
- Helps operations teams assign urgent jobs faster, keep customers informed, and inspect SLA trends across regions.
- Addresses a problem customers already care about: missed commitments and escalations.

Business impact:
- Supports awareness, pipeline, revenue, and expansion.
- Gives Sales a higher-level story for VP Operations and COO conversations.

Market impact:
- Stronger than a feature announcement because it frames NorthstarOps around service reliability, not dispatch productivity alone.
- Potentially useful for PR/AR if the company can tell a broader story about rising customer expectations in field service.

Narrative impact:
- Can anchor a campaign, webinar, sales narrative, executive talk track, and demo storyline.
- Connects product capabilities to the company-level promise of protecting service commitments.

Audience breadth/specificity:
- Broad enough for priority field service segments, specific enough to avoid generic operations software language.

Proof readiness:
- Predictive Dispatch Optimizer has a quantified beta proof point.
- Executive dashboard has prototype validation.
- Customer ETA Portal still needs quantified proof.

Decision:
- Tier 1 is appropriate because the bundle can carry a company-level narrative and a full season of launch. Confidence depends on tightening proof for Customer ETA Portal.

### Salesforce Service Cloud Integration

Customer impact:
- Important for Salesforce-centric enterprise accounts that need service context and work order visibility across systems.

Business impact:
- Directly supports pipeline acceleration and expansion because named opportunities are asking for it.

Market impact:
- Useful for a targeted enterprise segment, but not broadly newsworthy unless paired with partner validation or marketplace motion.

Narrative impact:
- Supports the service reliability story as an ecosystem proof point, but should not be the headline.

Audience breadth/specificity:
- Narrow but commercially valuable.

Proof readiness:
- Strong sales signal from three named opportunities; needs demo and customer quote once live.

Decision:
- Tier 2 is appropriate: campaign-level launch with sales play, targeted account list, integration demo, and customer/prospect proof.

### Mobile Offline Mode

Customer impact:
- Very meaningful for customers whose technicians work in rural, industrial, or low-connectivity environments.

Business impact:
- Supports adoption, retention, and customer confidence.

Market impact:
- Limited broad news value.

Narrative impact:
- Could support a reliability story for specific segments, but it is more of an adoption/retention story than a buyer-market announcement.

Audience breadth/specificity:
- Specific to low-connectivity field teams.

Proof readiness:
- Strong request volume, but no outcome proof yet.

Decision:
- Tier 3 is appropriate: targeted launch through lifecycle email, CS outreach, help center, in-product education, and account-specific enablement.

### Admin Permission Templates

Customer impact:
- Improves admin setup and onboarding.

Business impact:
- Could reduce implementation friction and support tickets.

Market impact:
- Low.

Narrative impact:
- Low; does not belong in the main launch story.

Audience breadth/specificity:
- Admin and IT users at existing customers.

Proof readiness:
- Customer advisory board request is useful input, but not launch proof.

Decision:
- Tier 4 is appropriate: release notes, docs, support readiness, and CS mention in onboarding conversations.

### Dark Mode for Dispatcher Console

Customer impact:
- Helpful user preference for overnight dispatchers.

Business impact:
- User satisfaction, but unlikely to affect pipeline or retention alone.

Market impact:
- Low.

Narrative impact:
- Low.

Audience breadth/specificity:
- Dispatcher users.

Proof readiness:
- Community requests only.

Decision:
- Tier 4 is appropriate: release note and community update.

## 5. Season-of-launch plan

### Pre-launch

- Align Product, PMM, Campaigns, Sales, CS, Support, Web, Content, Creative, and Exec on the Service Reliability Launch tiering decision.
- Confirm product readiness and demo paths for Predictive Dispatch Optimizer, Customer ETA Portal, and Executive Operations Dashboard.
- Build the hero narrative: "Protect every service commitment before it becomes a customer escalation."
- Turn the beta result into a proof point: 14% reduction in missed SLA windows during a 60-day pilot.
- Secure customer quote or anonymous proof from the beta account if public approval is not available.
- Brief Sales on the target segment, pain, talk track, demo flow, objections, and target account list.
- Brief CS on existing-customer adoption opportunities and expansion paths.
- Prepare analyst/customer briefings only if the narrative is mature enough and proof is credible.
- Create the Salesforce integration target-account list and separate Tier 2 campaign plan.
- Create Mobile Offline Mode customer list based on connectivity-related support tickets and account notes.

### Launch day/window

Service Reliability Launch:

- Publish launch blog or newsroom post.
- Update website/product pages around service reliability, dispatch intelligence, customer visibility, and executive reporting.
- Release demo video showing the full workflow: risk appears, dispatcher assigns the right tech, customer gets ETA, executive sees SLA trend.
- Run executive and company social amplification.
- Send Sales launch kit and hold enablement session.
- Send customer announcement with clear "what this means for you" guidance.
- Run targeted PR/AR only if the story is framed around the market problem, not just feature availability.

Salesforce Service Cloud Integration:

- Publish integration page or marketplace listing if available.
- Send targeted sales play to account teams with named opportunities and Salesforce-heavy accounts.
- Create short integration demo and objection handling.

Mobile Offline Mode:

- Send lifecycle email and CS outreach to customers likely to benefit.
- Publish help center guide and in-app education.

Tier 4 updates:

- Include Admin Permission Templates and Dark Mode in release notes.
- Update docs and support macros.

### Follow-on weeks

- Host webinar: "How field service teams prevent missed SLAs before customers escalate."
- Publish a deeper product demo video focused on dispatch risk scoring and SLA protection.
- Build a customer story or proof asset from the beta account.
- Run a sales play for accounts with high SLA pressure, complex dispatch regions, or customer escalation pain.
- Create nurture emails around missed service windows, customer communication, and executive visibility.
- Package a CS adoption play for current customers who could activate the new capabilities.
- Run a focused campaign for Salesforce accounts with integration-specific messaging.
- Collect objection feedback from Sales and customer feedback from CS after the first 30 days.

### Adoption/proof loop

- Track adoption of the three Service Reliability features by target accounts.
- Measure demo requests, pipeline influenced, opportunity progression, and content engagement.
- Track customer usage of Customer ETA Portal and reduction in status-call volume if data is available.
- Track SLA miss rate and dispatch assignment speed for customers using Predictive Dispatch Optimizer.
- Track expansion opportunities influenced by Executive Operations Dashboard.
- Use customer results to refresh sales enablement, build a case study, and support analyst/customer proof.

## 6. Core launch content system

Hero message:
- Protect every service commitment before it becomes a customer escalation.

Sales enablement:
- Sales narrative slides for VP Operations and COO conversations
- Talk track: missed service commitments are rarely caused by one bad dispatcher; they happen when risk, technician fit, customer updates, and executive visibility are managed in separate places
- Discovery questions around SLA misses, customer escalations, repeat visits, and dispatch complexity
- Objection handling for "we already have scheduling software" and "our dispatchers can handle this manually"

Demo/video:
- Hero demo: urgent job enters the queue, SLA risk is detected, best technician is recommended, customer ETA portal updates, executive dashboard reflects trend
- Short clips for each feature in the bundle
- Separate Salesforce integration demo for enterprise deals
- Mobile Offline Mode walkthrough for CS and customer education

Case study/proof plan:
- Turn the 14% beta result into an approved proof point
- Capture before/after story from a beta customer
- Track status-call reduction for Customer ETA Portal after launch
- Build expansion proof from dashboard usage in executive business reviews

Campaign/content plan:
- Launch blog/newsroom post
- Webinar
- Product page update
- Nurture sequence for operations leaders
- LinkedIn/social posts from company and executives
- Follow-on article on preventing SLA escalations in field service

Customer/CS assets:
- Customer announcement email
- CS adoption playbook
- Help center articles
- In-app education
- EBR slide for Executive Operations Dashboard

Sales toolkit:
- Pitch deck insert
- One-page launch brief
- Target account criteria
- Discovery questions
- Demo flow
- Objection handling
- Proof points
- Salesforce integration account play

## 7. Cross-functional alignment map

Product:
- Confirm readiness, dependencies, demo environment, feature scope, and roadmap risk.

PMM:
- Own tiering recommendation, messaging, positioning, launch bill of materials, sales story, and season-of-launch plan.

Campaigns/Demand Gen:
- Build webinar, nurture, paid/organic promotion, target-account campaign, and follow-on content calendar.

PR/AR/Comms:
- Pressure-test news value, brief analysts if warranted, shape external announcement, and avoid over-claiming where proof is still developing.

Sales:
- Use the launch story in target accounts, run the Salesforce integration play, provide objection feedback, and report pipeline influence.

CS/Support:
- Drive existing-customer adoption, prepare support docs/macros, identify proof candidates, and monitor retention/customer confidence signals.

Web/Content/Creative:
- Update product pages, create launch visuals, build demo/video assets, and package follow-on content.

Exec sponsor:
- Support Tier 1 narrative, customer/analyst conversations, and executive social amplification.

## 8. Measurement plan

Awareness metrics:
- Launch page traffic
- Blog/newsroom views
- Social engagement from target personas
- Analyst/customer briefing quality
- Share of voice or qualitative market response if tracked

Consideration/acquisition metrics:
- Demo requests from target accounts
- Webinar registrations and attendance
- Content engagement by operations leaders
- New opportunities sourced or influenced
- Opportunity progression in accounts exposed to launch assets

Usage/adoption metrics:
- Activation of Predictive Dispatch Optimizer
- Customer ETA Portal setup and active usage
- Executive Operations Dashboard weekly active viewers
- Mobile Offline Mode activation among target customers

Revenue/expansion metrics:
- Pipeline influenced by Service Reliability Launch
- Salesforce integration opportunities advanced
- Expansion opportunities tied to Executive Operations Dashboard or integration demand

Retention/customer confidence metrics:
- Adoption among accounts with prior SLA or connectivity concerns
- Reduction in relevant support tickets
- Customer sentiment from CS notes and EBRs
- Case study candidates created

Qualitative feedback loop:
- Sales objection themes
- Demo questions and buyer language
- CS adoption blockers
- Customer proof gaps
- Product feedback from early usage

## 9. Risks, dependencies, and open questions

Roadmap risks:
- Customer ETA Portal proof is not yet quantified.
- Executive Operations Dashboard is prototype-validated but needs launch-readiness confirmation.
- Bundled Tier 1 launch depends on all three components being demo-ready within the same window.

Proof gaps:
- Need permission to use the 14% beta result publicly.
- Need customer quote or approved anonymized proof.
- Need early data on Customer ETA Portal reducing inbound status calls.

Narrative risks:
- The story could become too broad if it tries to include every Q3 update.
- Salesforce integration could distract from the main service reliability narrative if positioned as the headline.

Resource constraints:
- Tier 1 requires real support from Web, Creative, Campaigns, Sales Enablement, CS, and possibly PR/AR.
- If resources are limited, prioritize hero messaging, demo, sales kit, product page, customer comms, webinar, and proof development over lower-value launch-day noise.

Decisions needed:
- Can the beta customer be named?
- Is PR/AR warranted based on story and proof quality?
- Which accounts are the Tier 1 target account list?
- Which Salesforce-heavy opportunities should receive the integration play first?
- Which customers should receive Mobile Offline Mode outreach?

## 10. Move-up / move-down criteria

### Service Reliability Launch bundle

Move up or keep strong Tier 1 if:
- Beta proof is approved publicly.
- Customer ETA Portal produces quantified status-call reduction.
- Executive Operations Dashboard has strong EBR pull from customers.
- Analysts or customers validate the broader service reliability narrative.

Move down to Tier 2 if:
- One or more bundled features slips materially.
- Proof cannot be used.
- The launch becomes a collection of features without a credible executive narrative.

### Salesforce Service Cloud Integration

Move up to Tier 1 only if:
- There is a major Salesforce partnership, marketplace co-marketing moment, or strategic ecosystem narrative.
- The integration becomes central to a company-level enterprise push.

Move down to Tier 3 if:
- Only a few existing customers can use it at launch.
- Marketplace listing or demo readiness slips.
- Sales cannot identify a meaningful target account list.

### Mobile Offline Mode

Move up to Tier 2 if:
- Data shows offline usage materially reduces missed updates, job delays, or customer escalations for a priority segment.
- It becomes a competitive differentiator in an industry campaign.

Move down to Tier 4 if:
- It is basic parity with limited adoption signal.
- CS cannot identify target accounts or customer education needs.

### Admin Permission Templates and Dark Mode

Move up only if:
- Admin Permission Templates become part of a broader onboarding or enterprise governance story with measurable impact.
- Dark Mode becomes part of a user-community moment, not just a preference update.

Otherwise:
- Keep both as Tier 4 updates and avoid diluting the main launch story.
