# Footprint Algorithm and Community Growth CTP

Version: 1.0

Date: 2026 07 13

Decision owner: Ro

Scope owner: Footprint version 2

## PROMPT CONTRACT

### GOAL

Design a fully autonomous Footprint engine that uses public knowledge about LinkedIn ranking, community behavior, search discovery, and responsible experimentation to help community members while building trusted reach for Rory, Keymon, RedLantern Studios, and Footprint.

### CONSTRAINTS

1. The public loop must run without routine approval after private commissioning.
2. No scraping, browser automation, connection automation, engagement pods, false geography, purchased engagement, or unsolicited messages.
3. LinkedIn Page messages require an approved LinkedIn messaging partner.
4. Zapier and the built in n8n LinkedIn node may publish but do not receive LinkedIn messages.
5. n8n owns business logic.
6. Supabase owns durable state with RLS.
7. SwarmClaw uses its existing separation of powers.
8. Contributor value, consent, safety, and fairness outrank vanity metrics.
9. Founder and product promotion must be transparent.
10. The Lantern may not carry Rory promotion.
11. Keymon identity actions require active written authority.
12. No algorithm outcome can be guaranteed.

### FORMAT

Full CTP with three passes, ten layers, behavioral driver separation, assumptions, cold start, complete logic chain, community context, execution system, acceptance criteria, definition of done, constructive criticism, destructive criticism, one recommendation, and KPI framework.

### FAILURE

This plan fails if it treats algorithm folklore as fact, optimizes raw engagement at the expense of trust, assumes Zapier or n8n can read the LinkedIn inbox, exposes private submissions, buries founder promotion inside community content, creates a popularity contest, or claims full autonomy without a private commissioning gate.

## OBJECTIVE

Build a community opportunity router that earns distribution by consistently producing relevant, useful, trustworthy professional content for people who are likely to value it.

The engine should not try to game an algorithm. It should create the signals that ranking systems are designed to recognize while protecting the humans whose work creates those signals.

## REALITY CHECK

VERIFIED: LinkedIn states that feed ranking uses hundreds of signals drawn from identity, content, and activity context.

VERIFIED: LinkedIn identifies location, workplace, skills, background, topic, recency, source relationship, language, constructive conversation, tags, reactions, comments, shares, dwell, follows, and recent interaction as relevance signals.

VERIFIED: LinkedIn engineering describes multiple first pass rankers, a second pass ranker, and reranking. This means no single tactic controls distribution.

VERIFIED: LinkedIn engineering has used skip probability and dwell related features to improve ranking. Clicks alone are noisy.

VERIFIED: LinkedIn states that content is initially distributed based partly on connection strength, notification state, and connection activity.

VERIFIED: LinkedIn recommends professional relevance, deep insight, useful lessons, timely ideas, and avoiding overly promotional content.

VERIFIED: LinkedIn says complete Pages receive thirty percent more weekly views.

VERIFIED: LinkedIn says Pages that post weekly receive five times more followers and grow seven times faster than Pages that post monthly.

VERIFIED: LinkedIn Group activity can affect feed personalization.

VERIFIED: LinkedIn newsletters may notify subscribers through LinkedIn, push, and email surfaces.

VERIFIED: LinkedIn prohibits unauthorized automated activity and scraping.

VERIFIED: Google prohibits scaled low value content and doorway pages.

PARTIAL: These official disclosures identify signal families and platform behavior. They do not disclose current weights, thresholds, or a universal best posting time.

UNKNOWN: Footprint audience response, Page baseline, follower graph, topic affinity, format preference, geographic concentration, and optimal cadence.

ASSUMED: A community service loop will create more durable trust than a founder promotion loop. This is the governing product hypothesis and must be measured.

## THREE PASS ANALYSIS

### Pass 1: surface answer

Complete the Page, publish useful community features consistently, welcome members, ask good questions, respond quickly, schedule at audience appropriate times, and measure what performs.

### Pass 2: challenge

That answer treats reach as a posting problem. Footprint is actually a supply, trust, permission, relevance, and network graph problem.

Without a healthy submission supply, the system becomes generic content marketing. Without consent and evidence, it becomes a reputation risk. Without contributor participation, distribution remains trapped inside the Page graph. Without useful private outcomes, people who are not featured feel extracted from. Without a saturation governor, three identities and several products can appear coordinated and self serving.

### Pass 3: governing truth

Footprint should optimize the complete community outcome loop:

Invite a real person. Receive real work. Understand it. Help privately. Obtain permission. Publish the right representation. Activate the contributor and relevant circles voluntarily. Continue a constructive conversation. Measure what happened for the contributor. Learn without sacrificing fairness.

The algorithm benefits are downstream of that loop. Relevance, dwell, substantive comments, shares, follows, relationship affinity, newsletter subscriptions, Group participation, branded search, and qualified messages are consequences of useful community work.

Pass 3 governs every system decision below.

## TEN LAYER ANALYSIS

### Load bearing claim A: useful community content can create algorithmic distribution without manipulation

1. Surface: feature interesting work and LinkedIn will show it to more people.

2. Root cause: ranking systems need evidence that a specific item is useful to a specific person at a specific time.

3. First order: clear professional value, a recognizable topic, and a strong opening reduce immediate skipping.

4. Second order: the contributor and relevant readers add context through real comments, saves, sends, follows, and voluntary shares.

5. Third order: repeated useful interactions strengthen relationship and topic affinity, increasing the chance future Footprint items are considered relevant.

6. Upstream dependencies: legitimate submissions, editorial quality, accurate tagging, contributor permission, topic taxonomy, audience circles, and a publishing connection.

7. Downstream dependencies: Page growth, Group participation, newsletter subscriptions, owned site discovery, contributor outcomes, and relationship intelligence.

8. Failure modes: shallow features, generic praise, comment bait, irrelevant tags, repetitive formats, excessive volume, or choosing famous people because they already distribute well.

9. Recovery: lower volume, restore community allocation, diversify contributors, ask fewer but better questions, revise topic cells, and pause formats that create skips or complaints.

10. Strategic implication: Footprint should optimize qualified usefulness per audience exposure, not engagement per post.

### Load bearing claim B: full autonomy can begin on the first public day

1. Surface: agents can receive, judge, write, publish, and reply automatically.

2. Root cause: Ro wants leverage without becoming the daily approval queue.

3. First order: public actions happen quickly and consistently.

4. Second order: any consent, truth, identity, or safety mistake also happens quickly and consistently.

5. Third order: one public breach can weaken contributor trust, founder trust, Page trust, and product trust together.

6. Upstream dependencies: private commissioning, deterministic policy, sanction approved connections, real test cases, identity authority, consent state, rollback, and a kill switch.

7. Downstream dependencies: all publishing, messaging, introductions, corrections, and learning.

8. Failure modes: private text becomes a post, Keymon is represented without authority, unsafe work is amplified, the same person receives duplicate replies, or the publisher retries into duplicate posts.

9. Recovery: immediate pause, correction, removal, contributor notice, receipt, root cause fix, regression case, and controlled restart.

10. Strategic implication: full autonomy is valid only as a public operating mode after private commissioning. Commissioning is setup, not public human review.

### Load bearing claim C: LinkedIn can be the primary intake and reach surface

1. Surface: the Page receives messages, welcomes people, and publishes community work.

2. Root cause: LinkedIn already contains professional identity, work context, relationships, and distribution.

3. First order: members can submit with less friction and featured work can reach professional networks.

4. Second order: Footprint depends on LinkedIn permissions, partner availability, account health, and changing platform behavior.

5. Third order: platform concentration can erase intake and distribution at the same time.

6. Upstream dependencies: Page, Group, newsletter eligibility, approved messaging partner, publishing access, admins, and policy compliance.

7. Downstream dependencies: submission volume, public reach, analytics, community graph, and contributor discovery.

8. Failure modes: assuming inbox access from Zapier, using unofficial automation, partner outage, Page restriction, Group spam, or notification fatigue.

9. Recovery: owned site submission form, email consent path, durable contributor pages, exportable state, partner adapter replacement, and a publication queue that can pause safely.

10. Strategic implication: LinkedIn is the lead surface, but Footprint must own the community record, consent, learning, and durable content.

## BEHAVIORAL DRIVER SEPARATION

### Driver

People share work when they believe they will be understood, respected, and helped.

People follow and return when Footprint repeatedly improves their professional awareness, opportunities, or confidence.

Contributors participate in distribution when the feature represents them well and sharing it feels useful rather than transactional.

### Mechanism

Page messages, Group welcome, submission analysis, content generation, scheduling, newsletter, search pages, analytics, and agent orchestration.

### Constraint

The limiting constraint is not content production. It is trustworthy supply and responsible routing through sanctioned platform access.

### Governing choice

Spend engineering effort on consent, value routing, quality, evidence, and feedback before increasing posting volume.

## ASSUMPTIONS AUDIT

### A1

ASSUMED: People will message a Page with work and ideas.

Risk: the inbox stays empty.

Resolution: seed the first one hundred relevant followers from existing first degree networks, publish a clear invitation, enable useful message topics, and compare Page messages with owned form submissions.

### A2

ASSUMED: An approved messaging partner can send events into n8n.

Risk: the selected partner manages messages but cannot expose a suitable webhook or API.

Resolution: run a partner proof before selection. Required proof is inbound event, outbound reply, attachment metadata, conversation identifier, member identifier, timestamp, retry behavior, and data deletion path.

### A3

ASSUMED: Local n8n is available reliably enough for an always active public inbox.

Risk: laptop sleep, network change, process failure, or tunnel failure interrupts the community.

Resolution: measure uptime and wake behavior. Production autonomy requires an always reachable runtime, even if the current development runtime remains local.

### A4

ASSUMED: Contributors will consent to features.

Risk: useful submissions remain private.

Resolution: make private help valuable by itself. Ask for consent only after showing the proposed representation.

### A5

ASSUMED: Rory and Keymon commentary adds value rather than crowding out community voices.

Risk: Footprint feels like a founder funnel.

Resolution: enforce the seventy, twenty, ten allocation and measure contributor perception separately from reach.

### A6

ASSUMED: One content strategy can serve multiple geographies.

Risk: timing, language, examples, and opportunities feel generic.

Resolution: use market cells with truthful local context and require sufficient audience evidence before creating a local cadence.

### A7

ASSUMED: SwarmClaw local model quality is sufficient for public editorial and nuanced safety decisions.

Risk: shallow reasoning or inconsistent decisions.

Resolution: commissioning evals compare the live routed models against a frozen expected set. The canonical bridge currently records unresolved routing conflict, so live routing is UNKNOWN until verified.

## COLD START

Footprint begins without a trusted contributor supply, content baseline, audience fatigue baseline, or known topic graph.

The cold start plan has four stages.

### Stage 1: foundation

1. Complete every Page field with accurate keywords, location, description, site, and visual identity.
2. Assign more than one Page admin.
3. Create a Group purpose, rules, automatic welcome note, and initial discussion schedule.
4. Publish submission instructions and consent rules on the owned site.
5. Create the first topic taxonomy and geographic cells from real studio relationships.

### Stage 2: seed supply

1. Invite relevant first degree contacts to follow within LinkedIn invitation rules.
2. Use Premium Page automatic invitation for recent engagers only if the Page has that feature and it is intentionally enabled.
3. Invite a small qualified initial Group cohort.
4. Commission ten founding community features from people who explicitly agree to participate.
5. Publish a clear recurring invitation to message the Page with work, ideas, questions, or opportunities.

### Stage 3: fixed learning cadence

Initial public budget:

1. Three Page posts each week.
2. Two Group prompts each week.
3. One community roundup every two weeks through the newsletter when available.
4. One owned site feature each week.
5. No more than one public feature per contributor in thirty days unless a material new event occurs.
6. No more than one identity or product item in any seven day window during the first month.

These are commissioning defaults, not universal algorithm facts.

### Stage 4: bounded adaptation

The engine may increase or reduce cadence only after four complete weeks and sufficient exposure. It may never exceed configured maximums without a scope revision.

## COMPLETE LOGIC CHAIN

### Inputs

1. Page message event from an approved partner.
2. Group membership and discussion events available through official surfaces.
3. Owned submission form.
4. Public work links supplied by the contributor.
5. Contributor identity and consent state.
6. Page, Group, newsletter, site, and post analytics.
7. Current Claudex identity and product authority.
8. Topic, audience, geography, and schedule state.

### Normalization

n8n creates one submission record, one contributor record, one conversation record, provenance, attachments, content hashes, and consent state. Duplicate detection runs before any response or evaluation.

### Evaluation

SwarmClaw produces structured findings for authenticity, safety, rights, readiness, community value, relevance, and confidence. Each finding names its evidence and uncertainty.

Deterministic n8n policy applies hard rules. The model cannot override missing consent, disabled identity authority, prohibited content, or platform permission.

### Routing

The router selects one or more useful outcomes. It does not force every submission into feature or reject.

### Editorial

The engine creates a proposed representation, extracts every factual claim, validates evidence, and sends the contributor the exact asset for asset specific consent when public use is proposed.

### Saturation

The governor checks contributor frequency, topic frequency, identity mix, circle exposure, geographic relevance, recent similarity, negative signals, and current experiment allocation.

### Publication

n8n sends an idempotent publication job through the official adapter. It stores the request identifier, platform identifier, final content hash, time, and adapter receipt.

### Conversation

Footprint replies to substantive comments and questions with useful context. It does not manufacture comments or ask unrelated people to react.

### Measurement

The engine records exposure, dwell proxies when available, reactions, comments, comment quality, saves, sends, follower changes, newsletter subscriptions, messages, Group participation, site visits, contributor outcomes, hides, complaints, corrections, and removals.

### Learning

The experiment service updates bounded priors for format, topic, opening, length, timing, geography, and call to action. It does not optimize on a single post and does not change hard policy.

### Feedback

The contributor receives a follow up asking whether the route created a useful result. This outcome enters the next planning cycle.

## OPEN SOURCE ALGORITHM PLAYBOOK

### 1. Identity relevance

Action: complete the Page and contributor context accurately. Use clear topic language, truthful location, accurate organization data, and relevant skills.

Reason: LinkedIn identifies identity context such as location, workplace, skills, and background as feed signals. Page completeness also improves Page discovery.

Boundary: do not stuff keywords or attach irrelevant identities.

### 2. Content relevance

Action: each post answers a professional question, teaches a lesson, surfaces a credible opportunity, or helps the audience understand a real piece of work.

Reason: LinkedIn explicitly references knowledge, advice, topic, recency, language, and constructive professional conversation.

Boundary: community features need a useful reader takeaway. Praise alone is not enough.

### 3. Immediate skip reduction

Action: the first screen states the person, the problem, the work, and why it matters. Visual assets remain readable on mobile. Long assets earn their length through substance.

Reason: LinkedIn engineering describes a skip probability objective based on dwell behavior.

Boundary: no sensational opening that the body does not fulfill.

### 4. Time well spent

Action: use native text, images, video, and documents when the format makes the work easier to understand. Use documents for frameworks, process, before and after evidence, or compact portfolios.

Reason: dwell can carry more information than a binary click. LinkedIn also states that time well spent matters more than blindly increasing time.

Boundary: do not pad content to create artificial dwell.

### 5. Constructive conversation

Action: end with one real question the featured person and relevant readers can answer from experience. Respond with substance. Invite disagreement when it improves the topic.

Reason: LinkedIn identifies constructive professional conversation and engagement as signals.

Boundary: no reaction bait, forced tagging, or generic prompts.

### 6. Relationship affinity

Action: feature people whose work is relevant to existing circles, then allow their participation to introduce Footprint to adjacent circles organically.

Reason: LinkedIn uses relationship and interaction history in ranking.

Boundary: contributor sharing is optional. The message should say they may share if the representation feels useful and accurate.

### 7. Topic consistency with diversity

Action: maintain a stable set of Footprint topic pillars while rotating people, perspectives, geography, and format.

Reason: consistent topic signals help the system and the audience understand what Footprint is for. Diversity prevents fatigue and popularity lock in.

Boundary: a topic pillar is not permission to repeat the same observation.

### 8. Recency and timing

Action: publish when the featured work is timely and when the relevant market cell is likely awake. Learn local windows from Footprint data.

Reason: LinkedIn lists recency and contextual features such as time of day.

Boundary: there is no verified universal best posting time. Footprint must test its own audience.

### 9. Page and Group complement

Action: Page posts introduce work publicly. Group discussions invite deeper feedback and belonging. Valuable Group participation can produce later Page features with consent.

Reason: LinkedIn states that Group activity can affect feed personalization.

Boundary: do not duplicate every Page post into the Group. The Group needs a distinct reason to exist.

### 10. Newsletter notification surface

Action: create a recurring digest containing the strongest community lessons and opportunities, not a list of links.

Reason: LinkedIn newsletters can notify subscribers across multiple surfaces.

Boundary: use a stable schedule and do not publish an edition without enough value.

### 11. Owned search authority

Action: publish unique contributor stories and topic guides with clear authorship, dates, corrections, structured organization data, descriptive titles, internal links, and useful public proof.

Reason: owned media compounds independently of the social feed. Google permits useful original content and rejects scaled low value or doorway pages.

Boundary: no city page exists unless it contains real local contributors, institutions, events, or service context.

### 12. Negative signal protection

Action: monitor hides, unfollows, complaints, removals, low quality comments, repeated skips where measurable, follower loss, and topic fatigue.

Reason: low quality content is tapered and negative behavior indicates lost trust.

Boundary: a post with low reactions is not automatically bad. Qualified outcomes may occur privately.

## EXPERIMENT SYSTEM

### Objective function

The primary objective is qualified community value per one thousand relevant impressions.

The score combines:

1. Contributor reported useful outcome.
2. Qualified inbound message.
3. Save or send when available.
4. Substantive comment.
5. Relevant follow or newsletter subscription.
6. Owned feature visit and meaningful completion.
7. Introduction accepted by both parties.
8. Opportunity or collaboration movement.

Penalties include:

1. Hide, unfollow, spam report, or complaint.
2. Correction or removal caused by Footprint error.
3. Consent failure.
4. Platform warning.
5. Audience concentration or contributor inequality.
6. Founder allocation violation.

### Test variables

1. Topic.
2. Format.
3. Opening pattern.
4. Post length.
5. Question type.
6. Contributor quote placement.
7. Time window.
8. Geographic cell.
9. Page versus newsletter treatment.
10. Contributor participation.

### Test rules

1. Change one major variable inside a matched test when practical.
2. Require a minimum exposure threshold before judging.
3. Use rolling baselines by topic and format.
4. Preserve an exploration budget so new people and formats can enter.
5. Do not suppress a deserving contributor because a similar person previously underperformed.
6. Do not reuse a winner until audience fatigue appears.
7. No experiment may weaken consent, truth, safety, identity authority, accessibility, or platform policy.
8. Record hypotheses before publication.
9. Record decisions after the observation window.
10. Treat algorithm changes as normal uncertainty, not emergencies.

## COMMUNITY AND CULTURAL CONTEXT

Footprint serves people whose work may be early, underfunded, poorly presented, geographically overlooked, or outside dominant professional networks.

The engine must not reproduce status bias by equating polish, credentials, follower count, company prestige, English fluency, or proximity to Rory with value.

Fairness controls include:

1. Separate authenticity from presentation quality.
2. Preserve an exploration allocation for new and underrepresented contributors.
3. Measure feature share by topic, geography, career stage, and relationship distance when lawful and voluntarily supplied.
4. Review whether the same circles repeatedly receive attention.
5. Provide useful private routes to people whose work is not publication ready.
6. Explain public selection in terms of reader relevance and readiness, not personal worth.
7. Honor name, pronoun, attribution, link, image, edit, and withdrawal preferences.
8. Never infer sensitive traits for targeting.

## EXECUTION

### Daily autonomous loop

1. Receive messages and form submissions.
2. Acknowledge and disclose the use of service providers and automated review.
3. Normalize and deduplicate.
4. Screen safety and rights.
5. Evaluate authenticity, readiness, community value, relevance, and confidence.
6. Send clarification or useful private route.
7. Create proposed public treatment when eligible.
8. Obtain asset specific consent.
9. Apply evidence, identity, saturation, and experiment gates.
10. Publish through the sanctioned adapter.
11. Monitor responses and answer useful questions.
12. Record outcomes, errors, and learning.

### Weekly autonomous loop

1. Build the next editorial allocation.
2. Check the seventy, twenty, ten mix.
3. Review topic and geographic gaps.
4. Publish or skip the roundup.
5. Report qualified outcomes and negative signals.
6. Update bounded experiment priors.
7. Run dead letter and correction audits.

### Monthly autonomous loop

1. Run fairness and concentration audit.
2. Run platform policy and official documentation review.
3. Revalidate credentials and permissions.
4. Revalidate identity authority and consent templates.
5. Test the kill switch and rollback in a safe environment.
6. Refresh search content only when new evidence adds value.

## ACCEPTANCE CRITERIA

AC1: Every ranked action displays the identity, content, activity, geography, timing, trust, and saturation reasons that affected it.

AC2: The system never claims to know the LinkedIn ranking weight of a signal.

AC3: Page completion is one hundred percent for all available relevant fields.

AC4: The first public month maintains the fixed cadence unless the governor reduces it for quality or safety.

AC5: Every post has a stated audience, professional value, evidence bundle, consent state, topic, and desired outcome.

AC6: Contributor follower count is excluded from legitimacy and community value decisions.

AC7: Public selection provides an exploration allocation for new contributors and topics.

AC8: No contributor is asked to share as a condition of support or publication.

AC9: The system tracks negative trust signals and can automatically reduce exposure.

AC10: Every experiment has a recorded hypothesis, variable, safety boundary, observation window, and conclusion.

AC11: Owned search pages contain unique evidence and useful reader value.

AC12: Full autonomy cannot activate until the approved message partner and publishing adapter pass live tests.

## DEFINITION OF DONE

1. Scope version 2 is registered.
2. The sanctioned connection architecture is live.
3. Page, Group, newsletter when eligible, and owned site are configured.
4. The Page is complete.
5. Group welcome and Page acknowledgement are tested.
6. One hundred private commissioning cases pass.
7. Twenty frozen shadow publication cases pass.
8. Consent, correction, removal, deduplication, rollback, and kill switch pass.
9. The first ten founding contributors have explicit permission.
10. Analytics measure the full community outcome loop.
11. The control room explains every decision in plain language.
12. Thirty autonomous public days complete without a catastrophic boundary miss.

## CONSTRUCTIVE CRITICISM

The strongest part of the concept is the value exchange. People are not merely content sources. They can receive help even when they are not featured.

The weakest part is the phrase organically get placed in everyone's algorithm. No system can ethically or technically guarantee that outcome. The correct promise is that Footprint will increase the probability of relevant distribution by producing useful work, activating real relationships, and learning from observable outcomes.

The highest leverage product decision is to make opportunity routing the center and publishing one route among many.

## DESTRUCTIVE CRITICISM

### Failure path 1: disguised founder funnel

Trigger: Rory, Keymon, and product content gradually consumes the community allocation.

Impact: people conclude that their work is being used as an audience acquisition device.

Mitigation: hard rolling allocation, transparent labels, independent fairness audit, and contributor outcome measurement.

Residual risk: moderate because editorial incentives naturally drift toward owned products.

### Failure path 2: popularity capture

Trigger: the learner favors people with large networks because their features produce more reactions and shares.

Impact: smaller creators become structurally invisible.

Mitigation: remove follower count from legitimacy, normalize outcomes by relevant exposure, preserve exploration, and audit relationship distance.

Residual risk: moderate because network effects still influence distribution.

### Failure path 3: private message breach

Trigger: a model converts an inbound message into a post before asset specific consent.

Impact: direct trust breach and possible legal or platform consequences.

Mitigation: deterministic consent gate before public generation and again before publication.

Residual risk: low only if both gates are outside model control.

### Failure path 4: unofficial inbox automation

Trigger: the team assumes Zapier, n8n, or a browser agent can read LinkedIn Page messages.

Impact: the engine does not function or violates platform rules.

Mitigation: approved messaging partner proof is the first connection gate.

Residual risk: high until a partner is selected and tested.

### Failure path 5: local runtime outage

Trigger: the local n8n host sleeps, loses network access, or restarts.

Impact: late responses, missed events, duplicate retries, and broken trust.

Mitigation: durable queues, event replay, idempotency, health monitoring, and an always reachable production runtime.

Residual risk: high if autonomy depends on a laptop process.

### Failure path 6: model routing conflict

Trigger: SwarmClaw files and live runtime use different model routing.

Impact: commissioning evidence does not represent the production system.

Mitigation: resolve the canonical bridge warning and capture live model receipts before evals.

Residual risk: high until verified.

### Failure path 7: content automation becomes noise

Trigger: the engine rewards cadence and fills empty slots with weak posts.

Impact: higher skip probability, unfollows, low trust, and declining Page relevance.

Mitigation: quality floor, safe silence, fixed maximums, and no minimum quota that overrides value.

Residual risk: low when silence is treated as success.

## RESULT

Footprint is buildable as a fully autonomous public engine after private commissioning. The algorithm strategy is not a bag of hacks. It is a controlled relevance system grounded in official signal families, real community outcomes, contributor consent, and bounded experimentation.

## SINGLE RECOMMENDATION

Build the approved LinkedIn Page messaging partner proof first, then connect it to a single n8n submission and opportunity routing loop before any publisher work.

This is the highest leverage action because inbox access is the entry point for the community, the consent flow, the evaluation system, and the public content supply.

Confidence: high.

Decision deadline: before SwarmClaw or v0 implementation begins.

## KPI FRAMEWORK

### North star

Qualified community outcomes per one hundred legitimate submissions.

Baseline: UNKNOWN.

Initial target: establish after the first one hundred legitimate submissions.

### Trust KPIs

1. Consent incidents. Target: zero.
2. Unexplained public claims. Target: zero.
3. Platform warnings caused by Footprint. Target: zero.
4. Contributor requested corrections caused by engine error. Target: below one percent after commissioning.
5. Removal completion time. Target: configured and verified before launch.

### Community KPIs

1. Percentage of legitimate submissions receiving a useful route. Target: one hundred percent.
2. Contributor reported useful outcome rate.
3. Introductions accepted by both parties.
4. Group first contribution rate.
5. Repeat contributor and referral rate.
6. Distribution of attention across relationship distance, topic, geography, and career stage.

### Reach KPIs

1. Relevant impressions per post.
2. Saves and sends per one thousand relevant impressions when available.
3. Substantive comments per one thousand relevant impressions.
4. Page follower conversion.
5. Newsletter subscription conversion.
6. Qualified inbound messages.
7. Branded and contributor search discovery.

### Saturation KPIs

1. Posts per identity and topic.
2. Repeat exposure per circle.
3. Hide, unfollow, and complaint rate.
4. Similarity to recent content.
5. Community, commentary, and studio allocation compliance.

### Operations KPIs

1. Message acknowledgement time.
2. Time to useful route.
3. Time to consented publication.
4. Duplicate response and duplicate publication rate. Target: zero.
5. Dead letter age.
6. Workflow uptime.
7. Cost per legitimate submission and per qualified outcome.

## PRIMARY SOURCES

LinkedIn feed relevance:

https://www.linkedin.com/help/linkedin/answer/a1339724

LinkedIn feed ranking overview:

https://www.linkedin.com/help/linkedin/answer/a9554004

LinkedIn feed engineering:

https://engineering.linkedin.com/teams/data/artificial-intelligence/feed

LinkedIn dwell engineering:

https://www.linkedin.com/blog/engineering/feed/understanding-feed-dwell-time

LinkedIn content distribution:

https://www.linkedin.com/help/linkedin/answer/a516930

LinkedIn Page practices:

https://www.linkedin.com/help/linkedin/answer/a553289/create-a-linkedin-page-best-practices

LinkedIn Page posts:

https://www.linkedin.com/help/linkedin/answer/a1660869

LinkedIn Group practices:

https://www.linkedin.com/help/linkedin/answer/a568276/linkedin-groups-best-practices

LinkedIn Group reach:

https://www.linkedin.com/help/linkedin/answer/a790825

LinkedIn newsletters:

https://www.linkedin.com/help/linkedin/answer/a521736

LinkedIn Page invitations:

https://www.linkedin.com/help/linkedin/answer/a1313099

LinkedIn Page messages:

https://www.linkedin.com/help/linkedin/answer/a1356464

LinkedIn messaging partner setup:

https://www.linkedin.com/help/billing/answer/a6246714

LinkedIn automated activity policy:

https://www.linkedin.com/help/linkedin/answer/a1340567

LinkedIn Community Management API:

https://learn.microsoft.com/en-us/linkedin/marketing/community-management/community-management-overview

Zapier LinkedIn capabilities:

https://help.zapier.com/hc/en-us/articles/8495987891853-How-to-get-started-with-LinkedIn-on-Zapier

n8n LinkedIn capabilities:

https://docs.n8n.io/integrations/builtin/app-nodes/n8n-nodes-base.linkedin/

Google spam policies:

https://developers.google.com/search/docs/essentials/spam-policies

Google Organization structured data:

https://developers.google.com/search/docs/appearance/structured-data/organization

