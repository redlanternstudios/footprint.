# Footprint Community Opportunity Network Scope Lock

Version: 2.0

Lock date: 2026 07 13

Owner: Ro

Design authority: SwarmClaw under the canonical Claudex rules

Status: LOCKED BY LATEST USER DIRECTION

## OBJECTIVE

Build Footprint as an autonomous LinkedIn centered community that welcomes people, invites them to share work and ideas, evaluates submissions fairly, and routes legitimate people toward useful outcomes without overwhelming the audience.

The community creates value for others first. Rory, Keymon, RedLantern Studios, and their products gain reach through transparent service, useful commentary, credible proof, and relevant relationships.

## REALITY CHECK

VERIFIED: A LinkedIn Page has followers, not friends. Footprint may invite relevant first degree connections to follow within LinkedIn rules. It must not automate personal connection requests.

VERIFIED: A LinkedIn Group can send an automatic welcome note to new members.

VERIFIED: A LinkedIn Page may reply only after a member messages the Page first.

VERIFIED: LinkedIn names Bird CRM, Brandwatch, Hootsuite, Oktopost, Sprinklr, and Zoho as current Page messaging API partners.

VERIFIED: Zapier supports LinkedIn publishing actions but exposes no LinkedIn trigger or search action.

VERIFIED: The built in n8n LinkedIn node creates posts as a person or organization. It does not receive Page messages.

PARTIAL: Zapier is available and n8n runs locally. Live credentials, workflow endpoints, persistence, and public reach are not yet verified.

UNKNOWN: Which approved LinkedIn messaging partner will provide the inbox connection.

UNKNOWN: Whether the Footprint Page, Group, and newsletter already exist.

UNKNOWN: Whether Rory and Keymon have granted final written identity and content permissions for every proposed action.

## GOVERNING INTERPRETATION OF FULL AUTONOMY

VERIFIED: Ro requires Footprint to operate without routine human review from its first public day.

VERIFIED: Setup therefore includes private commissioning before the first public day.

VERIFIED: Commissioning must include credentials, authority records, consent, deterministic policy checks, adversarial cases, shadow decisions, rollback tests, and the kill switch.

VERIFIED: After commissioning passes, the engine may welcome, classify, request clarification, recommend private resources, draft, schedule, publish, respond, measure, abstain, correct, and pause without routine approval.

VERIFIED: A consent request is part of the autonomous workflow. A submission cannot be made public until the contributor grants asset specific publication permission.

VERIFIED: Safe silence is a valid autonomous decision.

## PRIMARY USER STORY

As a Footprint community member, I want to share something I am building and receive a respectful, useful response so that I leave with more clarity, reach, support, or connection than I arrived with.

As Ro, I want that service loop to run autonomously and create trusted reach for the community, Rory, Keymon, and RedLantern Studios without engagement manipulation or audience fatigue.

## PRODUCT SURFACES

### LinkedIn Page

Purpose: public discovery, publishing, messages, featured community work, commentary, Page analytics, and invitations to follow.

### LinkedIn Group

Purpose: belonging, automatic welcome note, discussion, feedback, member introductions, and recognition of useful contributors.

### LinkedIn newsletter

Purpose: a durable recurring digest whose subscribers can receive LinkedIn, push, and email notifications when LinkedIn makes those channels available.

### Owned Footprint site

Purpose: submission instructions, consent records, contributor profiles, durable features, search discovery, corrections, removal requests, and proof that does not depend on one platform.

### Footprint control room

Purpose: nontechnical visibility into inbox state, decisions, consent, editorial work, schedule pressure, experiments, fairness, incidents, and the kill switch.

## VALUE ROUTES

Every legitimate submission receives one or more routes.

1. Clarification request.
2. Private encouragement with a concrete observation.
3. Presentation or positioning guidance.
4. Relevant resource.
5. Group feedback invitation.
6. Introduction to a relevant person when both sides consent.
7. Comment or repost recommendation.
8. Short Page spotlight.
9. Full feature or interview.
10. Newsletter inclusion.
11. Rory or Keymon commentary when identity permission and relevance are present.
12. RedLantern collaboration or service conversation when the commercial connection is transparent.

Rejection without explanation is not a default route. Fraud, abuse, unsafe content, repeated spam, or explicit platform violations may receive a brief boundary response or no response when safety requires it.

## CONTENT ALLOCATION

The initial editorial budget is:

1. Seventy percent community work, ideas, lessons, and opportunities.
2. Twenty percent Rory or Keymon commentary that adds real professional value to a community topic.
3. Ten percent transparent Footprint, RedLantern, or product proof.

The Saturation Governor enforces this budget over a rolling thirty day window. A founder or product item may never be disguised as a community feature.

## AUDIENCE AND GEOGRAPHY

VERIFIED: Footprint is not Muslim centered.

VERIFIED: It may serve people across professional, creative, technical, entrepreneurial, and community circles.

VERIFIED: Geographic relevance may use truthful location, local institutions, events, time zones, community needs, and service availability.

VERIFIED: Footprint must not create fake local pages, false proximity, or doorway content.

## INTEGRATION ARCHITECTURE

The required message path is:

1. Member messages the LinkedIn Page.
2. An approved LinkedIn messaging partner receives the conversation.
3. The partner sends the event to local n8n through a supported connector, webhook, or sanctioned API.
4. n8n writes the normalized conversation and consent state to Supabase.
5. SwarmClaw evaluates the submission through structured tasks.
6. n8n applies deterministic policy and routing rules.
7. The response returns through the approved partner.
8. Public assets enter the editorial and saturation workflow only after asset specific consent.

Publishing may use the official n8n LinkedIn node, Zapier LinkedIn actions, or an approved Community Management API adapter. One publishing route is primary. A second route is failover only after duplicate prevention is proven.

Zapier is an integration bridge. It does not own business logic. n8n remains the business logic and workflow authority.

## SWARMCLAW OPERATING MODEL

Footprint uses the existing SwarmClaw organization and its separation of powers.

1. RESEARCH gathers official platform evidence.
2. PM owns user stories, acceptance criteria, and route definitions.
3. DESIGN produces the v0 control room specification.
4. ARCHITECT owns structural decisions.
5. DATA owns schema review.
6. BACKEND proposes Supabase and n8n implementation.
7. FRONTEND proposes the control room implementation.
8. BRAND COPY and MARKETING create editorial patterns.
9. ASO SEO owns owned search guidance.
10. TRUTH verifies claims and evidence boundaries.
11. SECURITY verifies secrets, RLS, privacy, and webhook integrity.
12. COMPLIANCE verifies consent, platform rules, and removal paths.
13. REVIEW and QA verify implementation and behavior.
14. RUNTIME owns queues, retries, and dead letters.
15. ROBBY gives final release authorization after independent gates pass.

No agent may create and approve its own public action.

## SCOPE IN

1. LinkedIn Page setup guidance and complete profile requirements.
2. LinkedIn Group purpose, rules, welcome note, and discussion cadence.
3. Page messaging topics that invite work, ideas, questions, collaboration, and support.
4. Approved Page messaging partner integration.
5. Submission normalization and evidence capture.
6. Safety, authenticity, readiness, consent, relevance, and community value evaluation.
7. Opportunity routing across private and public outcomes.
8. Contributor consent, attribution preferences, edit requests, and withdrawal.
9. Editorial creation for the Page, Group, newsletter, and owned site.
10. Transparent Rory, Keymon, RedLantern, and product participation.
11. Shared saturation control across identities and topics.
12. Official LinkedIn publishing connections.
13. Controlled experiments for topic, format, opening, length, call to action, creator participation, geography, and time.
14. Qualified outcome, trust, fairness, and audience fatigue measurement.
15. Search authority through useful owned contributor and topic pages.
16. PostHog critical events and Sentry errors with context.
17. Audit receipts, corrections, retractions, removal, and kill switch.
18. Autonomous operation after commissioning.

## SCOPE OUT

1. Browser scraping or browser automation against LinkedIn.
2. Automated personal connection requests.
3. Automated unsolicited direct messages.
4. Automated likes, comments, follows, mentions, or reposts outside an official permission.
5. Engagement pods or coordinated artificial reactions.
6. Buying followers, comments, shares, placements, or backlinks.
7. Comment bait, false urgency, manufactured controversy, or hidden founder promotion.
8. Publishing private message content without asset specific consent.
9. Ranking people by follower count, polish, wealth, prestige, or friendship.
10. Treating low production quality as low community value.
11. Promising reach, virality, ranking, employment, investment, sales, or introductions.
12. Scaled low value search pages or fake geographic pages.
13. Publishing under Keymon without active written authority.
14. Routing Rory promotion through The Lantern.
15. Publishing blocked or private product claims.

## LEGITIMACY MODEL

Footprint does not use one opaque legitimacy score. It stores separate dimensions.

1. Authenticity: evidence that the person and work are real.
2. Safety: fraud, abuse, harmful claims, malware, exploitation, or prohibited material.
3. Rights: permission to use names, words, images, links, and media.
4. Readiness: whether the work can be understood and responsibly represented.
5. Community value: usefulness, originality, learning value, or opportunity for others.
6. Relevance: fit with current audience, topic, geography, and timing.
7. Confidence: how certain the engine is about each conclusion.

Low confidence routes to clarification or abstention. It does not silently become a negative judgment about the person.

## COMMISSIONING GATES

1. All platform actions use sanctioned connections.
2. The Page message partner is connected and passes receive and reply tests.
3. The publishing route passes publish, verify, deduplicate, retract, and failure tests.
4. Supabase RLS denies unauthorized access.
5. Consent state is machine readable and enforced before public generation.
6. One hundred representative private cases pass the policy harness.
7. Catastrophic boundary cases pass at one hundred percent.
8. The first twenty planned public assets run in shadow mode against a frozen expected decision set.
9. The kill switch stops inbox replies and publishing while preserving the audit log.
10. Dead letter recovery is verified.
11. SwarmClaw live model routing is verified against the canonical bridge warning.
12. Rory and Keymon identity authority records are active for only the allowed actions.

## ACCEPTANCE CRITERIA

AC1: A new member receives the Group welcome note once and only once.

AC2: A new Page message receives an acknowledgement through an approved partner within the configured service target.

AC3: The system can classify a submission without using follower count or production polish as a quality shortcut.

AC4: Every legitimate submission receives at least one useful route.

AC5: No private material becomes public before asset specific consent is recorded.

AC6: A contributor can request correction or removal and the system completes it across every controlled surface.

AC7: The rolling content mix remains within its configured community, commentary, and studio budgets.

AC8: The engine delays or skips an otherwise eligible post when topic, identity, circle, or audience fatigue exceeds policy.

AC9: Every public claim resolves to current evidence and active identity permission.

AC10: Every automated LinkedIn action resolves to an official connection and permitted action type.

AC11: Experiments optimize qualified community outcomes and trust, not raw reaction count alone.

AC12: The engine can operate for thirty days after commissioning without routine approval, a consent incident, a platform policy incident, or an unexplained public claim.

## DEFINITION OF DONE

All acceptance criteria pass with receipts. The Page, Group, message partner, n8n workflows, Supabase policies, SwarmClaw tasks, publishing route, analytics, control room, correction path, dead letter path, and kill switch are live and verified.

The system is not done when the interface renders. It is done when a real inbound submission can safely travel from Page message to useful outcome and, when consented, to a measured public feature.

## CHANGE RULE

Any change to identity authority, public consent, messaging provider, permitted LinkedIn action, content allocation, catastrophic boundary, or publication threshold requires a versioned scope revision and receipt.

