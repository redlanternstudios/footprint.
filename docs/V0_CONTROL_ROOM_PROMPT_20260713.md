# v0 Prompt for the Footprint Control Room

Version: 1.0

Consumer: SwarmClaw DESIGN and v0

## MASTER PROMPT

Create a production quality responsive control room for Footprint, a community opportunity network centered on LinkedIn.

Footprint welcomes people, invites them to share work and ideas, evaluates each submission fairly, provides useful private help, obtains permission for public use, creates community features, prevents audience saturation, and measures real contributor outcomes.

This interface is for Rory and trusted operators. It is not a social media scheduler and it is not a routine approval queue. After commissioning, the engine operates autonomously. The interface explains what it did, why it did it, what is waiting, what it declined, and whether trust or platform risk requires attention.

Use Next.js App Router, TypeScript, Tailwind, shadcn components, and accessible semantic HTML. Produce real component structure ready to connect to Supabase and n8n. Do not use fake processing controls or decorative charts without named data.

## VISUAL DIRECTION

Create a calm, confident, editorial operating environment.

Use warm cream as the main surface, deep black for structure, restrained lantern red for decisions and attention, muted olive for healthy community signals, and amber for uncertainty. Avoid a generic blue software dashboard.

Typography should feel like a serious editorial studio paired with a precise operating system. Use a readable sans serif for interface text and a restrained editorial serif for major page titles or contributor stories.

The interface should feel human and community centered. Contributor names, work, consent, and outcomes are more prominent than engagement totals.

Use generous spacing, quiet dividers, clear status language, and small explanatory text. Avoid excessive cards, gradients, glass effects, glowing borders, or crowded metric walls.

## GLOBAL NAVIGATION

Create a desktop sidebar and a mobile bottom or drawer navigation with these destinations:

1. Today
2. Community Inbox
3. Opportunities
4. Editorial
5. Calendar
6. Algorithm Lab
7. Community Graph
8. Trust and Fairness
9. Integrations
10. Incidents
11. Settings

The top bar shows Footprint status, autonomous mode, current Page connection, n8n health, message partner health, next planned public action, and a clearly protected kill switch.

## SCREEN 1: TODAY

Create a plain language command view that answers:

1. Is Footprint healthy?
2. What did it do today?
3. Who did it help?
4. What will it do next?
5. What is waiting and why?
6. Is the audience becoming saturated?
7. Does anything require human authority rather than routine approval?

Show:

1. New submissions.
2. Useful private routes sent.
3. Consent requests active.
4. Public features scheduled.
5. Qualified outcomes recorded.
6. Trust signals.
7. Current rolling content allocation with community, Rory or Keymon commentary, and studio content.
8. A chronological action receipt stream.

Every metric has a short definition available through an information control.

## SCREEN 2: COMMUNITY INBOX

Create a three pane inbox.

Left pane: filters for new, clarification, private help, consent, public candidate, correction, removal, safety, and dead letter.

Center pane: conversation list showing contributor, topic, location when voluntarily supplied, last message, state, response target, and risk marker.

Right pane: full conversation and submission context.

The right pane includes:

1. Original message and attachments.
2. Automated disclosure state.
3. Work links.
4. Evidence.
5. Separate evaluation dimensions for authenticity, safety, rights, readiness, community value, relevance, and confidence.
6. Missing information.
7. Recommended useful routes.
8. Consent scope.
9. Complete decision explanation.
10. Action receipts.

Do not display one legitimacy score.

Do not use follower count as a quality indicator.

## SCREEN 3: OPPORTUNITIES

Create a board and list toggle for useful routes.

Columns:

1. Clarify
2. Encourage
3. Improve presentation
4. Share resource
5. Invite Group feedback
6. Consider introduction
7. Recommend comment or repost
8. Short spotlight
9. Full feature
10. Newsletter
11. Collaboration
12. Closed with outcome

Each item shows the person, work, route reason, expected human value, audience fit, geography, consent state, and due time.

Opening an item shows why this route is better than the alternatives.

## SCREEN 4: EDITORIAL

Create a pipeline for public assets.

Stages:

1. Proposed
2. Waiting for contributor consent
3. Consented
4. Claim verification
5. Saturation check
6. Scheduled
7. Published
8. Measuring
9. Correction or removal

The asset detail shows:

1. Contributor and attribution preferences.
2. Exact consented text and media.
3. Public claims and evidence links.
4. Intended audience and topic.
5. Identity voice.
6. Geographic cell.
7. Content allocation category.
8. Similarity to recent content.
9. Publication adapter and idempotency key.
10. Platform result.

Allow an operator to inspect and intervene, but do not make approval the default workflow.

## SCREEN 5: CALENDAR

Create a weekly and monthly editorial calendar.

Show Page posts, Group prompts, newsletter editions, owned site features, contributor follow ups, and experiment observation windows.

Layer on saturation pressure for identity, contributor, topic, geography, circle, and overall audience.

Use calm pressure bands named Healthy, Watch, Delay, and Pause.

Show why the engine moved or skipped an item.

## SCREEN 6: ALGORITHM LAB

Create an experiment workspace that avoids pretending the LinkedIn algorithm is known.

Show:

1. Current hypotheses.
2. Test variable.
3. Matched audience or topic.
4. Observation window.
5. Exposure threshold.
6. Qualified community outcomes.
7. Saves, sends, substantive comments, relevant follows, messages, and contributor outcomes.
8. Negative signals such as hides, unfollows, complaints, corrections, and removals.
9. Decision after observation.
10. Confidence and unknowns.

Create separate sections for topic, format, opening, length, question, time, geography, and contributor participation.

Do not create an algorithm score or virality guarantee.

## SCREEN 7: COMMUNITY GRAPH

Create an understandable graph and list view of contributors, topics, organizations, market cells, Group conversations, introductions, and outcomes.

The graph should reveal over concentration and ignored circles without exposing private message text.

Filters include topic, geography, career stage when voluntarily supplied, relationship distance, route, and outcome.

Show a prominent reminder that sensitive traits are not inferred for targeting.

## SCREEN 8: TRUST AND FAIRNESS

Create a trust center with:

1. Consent coverage.
2. Correction and removal performance.
3. Public claim evidence coverage.
4. Attention distribution.
5. Exploration allocation.
6. Relationship distance distribution.
7. Founder and studio allocation compliance.
8. Identity authority status.
9. Platform permission status.
10. Safety and privacy incidents.

Show exceptions with clear human language and source evidence.

## SCREEN 9: INTEGRATIONS

Create connection cards for:

1. LinkedIn Page.
2. LinkedIn Group.
3. LinkedIn newsletter.
4. Approved Page messaging partner.
5. n8n.
6. Zapier.
7. Supabase.
8. Owned Footprint site.
9. PostHog.
10. Sentry.
11. Claudex.
12. SwarmClaw.

Each card shows sanctioned capabilities, denied capabilities, last successful event, credential health without exposing secrets, current latency, retry state, and connection receipts.

For LinkedIn, clearly distinguish publishing from Page message access.

## SCREEN 10: INCIDENTS

Create an incident view for consent breach, wrong identity, unsupported claim, duplicate publication, partner outage, n8n outage, Supabase denial, platform warning, correction, removal, and dead letter.

Each incident shows impact, containment, affected assets, contributor communication, root cause, regression case, recovery state, and restart authority.

## SCREEN 11: SETTINGS

Create settings for:

1. Content allocation.
2. Maximum cadence.
3. Topic rest periods.
4. Contributor rest periods.
5. Market cells.
6. Message topics.
7. Welcome note.
8. Consent language.
9. Identity authority.
10. Experiment bounds.
11. Notification rules.
12. Kill switch behavior.

Policy changes need a version, reason, effective time, and receipt.

## REQUIRED STATES

Build polished states for:

1. First setup.
2. Empty inbox.
3. Loading.
4. Partial data.
5. Offline n8n.
6. Partner disconnected.
7. LinkedIn publishing disconnected.
8. Permission denied.
9. Dead letter.
10. Autonomous mode paused.
11. No eligible content and safe silence.
12. Correction active.
13. Removal active.
14. Mobile use.

## ACCESSIBILITY

Meet WCAG AA contrast.

Every status uses text and icon, not color alone.

Keyboard navigation must work for every screen.

Focus states must be obvious.

Charts need accessible summaries.

The graph needs a complete list alternative.

The kill switch needs a confirmation step and clear consequence copy.

## DATA CONTRACT

Use typed placeholder interfaces that map to the entities in the SwarmClaw build brief. Mark all placeholder data clearly in development and structure components so Supabase records and n8n workflow events can replace it directly.

Do not hide business logic inside React components or route handlers. Every state changing action calls a named n8n workflow. Every read comes from authorized Supabase views or a thin read adapter.

## DELIVERY

Generate the full responsive application shell, navigation, all screens, reusable status components, contributor and submission detail patterns, tables, filters, charts with accessible summaries, error boundaries, loading skeletons, empty states, and mobile behavior.

Prioritize Today, Community Inbox, Submission Detail, Editorial Asset Detail, Calendar, Algorithm Lab, Trust and Fairness, and Integrations in the first generated version.

