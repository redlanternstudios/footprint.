# SwarmClaw Footprint Build Brief

Version: 1.0

Date: 2026 07 13

Owner: Ro

Consumer: ROBBY and the existing SwarmClaw organization

Status: READY FOR PARTNER PROOF AND LANE REGISTRATION

## OBJECTIVE

Design and build Footprint as a fully autonomous community opportunity network whose primary intake and reach surface is LinkedIn.

The engine welcomes people, receives work and ideas, provides a useful private route, obtains consent for public use, publishes selected work without oversaturation, and learns from contributor and audience outcomes.

## REALITY CHECK

VERIFIED: The canonical SwarmClaw organization already has research, product, design, architecture, data, backend, frontend, marketing, search, truth, security, compliance, review, quality, runtime, and release roles.

VERIFIED: SwarmClaw separation of powers forbids one agent from creating and approving its own change.

VERIFIED: n8n owns business logic under the locked studio stack.

VERIFIED: Supabase owns durable data, Auth, and RLS.

VERIFIED: The control room uses Next.js App Router and Tailwind.

VERIFIED: Zapier and n8n LinkedIn connections can publish.

VERIFIED: Page inbox autonomy requires an approved LinkedIn messaging partner.

PARTIAL: Local n8n is available. Production uptime and external reach are not verified.

UNKNOWN: Live SwarmClaw model routing. The canonical bridge records an unresolved conflict between local file state and live runtime state.

UNKNOWN: Selected Page messaging partner.

## ARCHITECTURE DECISION

Do not add nine new autonomous personalities.

Use the existing SwarmClaw roles for design, build, review, and governance. At runtime, begin with one Footprint Decision Agent that returns structured analysis. n8n owns the actual state machine, hard rules, scheduling, side effects, retries, and audit receipts.

This follows the OpenAI Agents SDK principle of proving one agent and narrow tools before adding specialists. It also preserves the studio rule that business logic belongs in n8n.

Specialist runtime agents may be added only when eval evidence proves the single decision agent cannot meet a named quality or safety requirement.

## RUNTIME COMPONENTS

### 1. Partner adapter

Purpose: sanctioned receive and reply access for LinkedIn Page messages.

Required contract:

1. Receive conversation event.
2. Receive text and attachment metadata.
3. Preserve platform conversation and member identifiers.
4. Reply as the Page.
5. Report delivery or failure.
6. Replay or retry safely.
7. Support data deletion.
8. Expose partner and LinkedIn timestamps.

### 2. n8n workflow layer

Purpose: complete business state machine.

Required workflows:

1. Inbound message intake.
2. Submission normalization and duplicate detection.
3. Automated acknowledgement.
4. Decision Agent request.
5. Hard policy evaluation.
6. Useful route selection.
7. Clarification and private help.
8. Public asset proposal.
9. Consent request and consent receipt.
10. Editorial generation and claim verification.
11. Saturation and schedule decision.
12. Official publishing.
13. Comment and message follow through when permitted.
14. Analytics ingestion.
15. Outcome follow up.
16. Correction, removal, and retraction.
17. Dead letter recovery.
18. Kill switch.

### 3. Footprint Decision Agent

Purpose: interpret a submission and produce structured findings without performing side effects.

Suggested implementation: Python OpenAI Agents SDK service with explicit structured output and deterministic function tools. Local model routing may be used only if the live runtime and quality evals pass.

Input:

1. Normalized submission.
2. Contributor supplied evidence.
3. Current conversation.
4. Consent state.
5. Topic taxonomy.
6. Audience and geographic cells.
7. Current editorial allocation.
8. Current saturation state.
9. Current identity and product authority.

Output:

1. Authenticity findings with evidence and confidence.
2. Safety findings with evidence and confidence.
3. Rights and consent gaps.
4. Readiness findings.
5. Community value findings.
6. Relevance findings by audience and geography.
7. Missing information.
8. Recommended routes ranked by expected human value.
9. Public treatment recommendation when eligible.
10. Claims that require verification.
11. Abstention reason when no safe route exists.

Forbidden:

1. Direct publication.
2. Direct message side effects.
3. Consent inference.
4. Identity authority changes.
5. Platform permission changes.
6. Hard policy override.

### 4. Supabase

Purpose: durable state and audit.

Minimum entities:

1. identities
2. identity_authorities
3. contributors
4. conversations
5. messages
6. submissions
7. submission_assets
8. evidence_items
9. evaluation_runs
10. evaluation_dimensions
11. routes
12. route_events
13. consents
14. consent_assets
15. editorial_assets
16. claims
17. claim_evidence
18. audience_circles
19. market_cells
20. topics
21. content_allocations
22. saturation_state
23. publication_jobs
24. publication_receipts
25. post_metrics
26. contributor_outcomes
27. experiments
28. experiment_assignments
29. corrections
30. removal_requests
31. incidents
32. dead_letters
33. policy_versions
34. action_receipts

Every public object stores provenance, consent, evidence, policy version, content hash, adapter, and correction state.

### 5. Publisher adapters

Primary route: select one official LinkedIn organization publisher.

Allowed candidates:

1. n8n LinkedIn post creation.
2. Zapier LinkedIn Company Update.
3. LinkedIn Community Management API after approval.

Only one route is active for a job. Every job uses an idempotency key. Failover requires a lookup that proves the primary route did not publish.

### 6. Owned site

Purpose: durable submission, consent information, community profiles, features, search pages, corrections, and removal requests.

No owned page is generated merely to target a keyword or city. Each page requires unique evidence and reader value.

### 7. Control room

Purpose: plain language operating visibility and emergency control.

The control room is not an approval queue after activation. It shows what the system did, why it did it, what it declined, and what requires human authority.

## STATE MACHINE

1. RECEIVED
2. ACKNOWLEDGED
3. NORMALIZED
4. NEEDS_CLARIFICATION
5. EVALUATED
6. PRIVATE_ROUTE_READY
7. PRIVATE_ROUTE_SENT
8. PUBLIC_PROPOSAL_READY
9. CONSENT_REQUESTED
10. CONSENTED
11. EDITORIAL_READY
12. POLICY_PASSED
13. SATURATION_WAIT
14. SCHEDULED
15. PUBLISHED
16. MEASURING
17. OUTCOME_RECORDED
18. CLOSED
19. WITHDRAWN
20. REJECTED_FOR_SAFETY
21. QUARANTINED
22. CORRECTION_ACTIVE
23. REMOVAL_ACTIVE
24. DEAD_LETTER

State transitions are owned by n8n and stored transactionally. Agent prose cannot mutate state.

## HARD RULES

1. No public generation without a public proposal route.
2. No public publication without asset specific consent.
3. No identity action without current authority.
4. No LinkedIn action without official adapter permission.
5. No direct message before the member messages the Page.
6. No follower count in legitimacy or community value evaluation.
7. No single opaque legitimacy score.
8. No founder or product item disguised as a community feature.
9. No Rory promotion through The Lantern.
10. No blocked, private, stale, or conflicted product claim.
11. No automatic introduction until both parties consent.
12. No duplicate reply or publication.
13. No retry after uncertain publication state until the platform is checked.
14. No minimum content quota that overrides quality.
15. Unknown produces clarification, quarantine, or safe silence.

## SWARMCLAW MISSION ROUTE

### Mission 0: canonical registration

Owner: CHIEF OF STAFF and LIBRARIAN

Work:

1. Register Footprint without changing The Lantern focus state.
2. Create the Footprint product lane.
3. Record scope version 2, CTP, this brief, and the v0 prompt.
4. Resolve the SwarmClaw routing warning before evals.

Proof:

Validated bridge receipt and live routing receipt.

### Mission 1: partner proof

Owner: RESEARCH, ARCHITECT, BACKEND, SECURITY, COMPLIANCE

Work:

1. Compare approved messaging partners against the required contract.
2. Select the smallest partner that exposes reliable receive and reply integration.
3. Connect a test Page.
4. Prove one inbound message and one outbound reply through n8n.
5. Prove privacy disclosure and deletion.

Proof:

Redacted event receipt, reply receipt, retry result, and deletion result.

Gate:

No inbox implementation begins without this proof.

### Mission 2: data and policy foundation

Owner: DATA, BACKEND, ARCHITECT, SECURITY, COMPLIANCE

Work:

1. Create migrations.
2. Enable RLS before seed data.
3. Create policy versions and deterministic consent gates.
4. Create identity authority and Page permission records.
5. Create append only action receipts.

Proof:

Migration tests, RLS denial tests, consent denial tests, and identity denial tests.

### Mission 3: one complete private route

Owner: PM, BACKEND, BRAND COPY, SUPPORT, TRUTH

Work:

1. Receive a submission.
2. Acknowledge it.
3. Evaluate it.
4. Ask clarification if needed.
5. Send one useful private outcome.
6. Record contributor feedback.

Proof:

One complete trace with no manual state edits.

### Mission 4: public consent and editorial route

Owner: BRAND COPY, MARKETING, TRUTH, COMPLIANCE, BACKEND

Work:

1. Generate a proposed Page spotlight.
2. Extract and verify claims.
3. Show the exact asset to the contributor.
4. Receive asset specific consent.
5. Schedule through the Saturation Governor.
6. Publish through the official route.
7. Verify platform result and store receipt.

Proof:

Consent receipt, evidence bundle, publication identifier, content hash, and post result.

### Mission 5: community surfaces

Owner: PM, MARKETING, BRAND COPY, DESIGN, SUPPORT

Work:

1. Complete the Page.
2. Configure message topics.
3. Configure Group purpose, rules, and welcome note.
4. Create Page, Group, newsletter, and owned site editorial patterns.
5. Commission ten founding contributors.

Proof:

Page completeness record, Group settings record, welcome test, and founding contributor consent set.

### Mission 6: algorithm lab

Owner: ASO SEO, ANALYTICS, MARKETING, DATA, TRUTH

Work:

1. Implement the objective function from the CTP.
2. Create experiment records and safe bounds.
3. Ingest official analytics.
4. Create topic, format, time, geography, and opening experiments.
5. Implement negative signal penalties.
6. Implement exploration allocation.

Proof:

One planned experiment, one completed observation window, and one bounded adaptation receipt.

### Mission 7: control room

Owner: DESIGN and FRONTEND

Work:

1. Use the v0 prompt as the design source.
2. Build the Next.js interface.
3. Wire every view to real Supabase and n8n state.
4. Add empty, loading, error, permission, offline, and dead letter states.
5. Add kill switch and incident view.

Proof:

Real data flow and complete responsive flow verification.

### Mission 8: commissioning

Owner: QA, REVIEW, TRUTH, SECURITY, COMPLIANCE, RUNTIME, ROBBY

Work:

1. Run one hundred private cases.
2. Run twenty frozen shadow publication cases.
3. Run adversarial consent, identity, safety, duplicate, outage, and rollback cases.
4. Verify local and production runtime parity.
5. Verify live model routing.
6. Verify kill switch.
7. Verify dead letter recovery.

Proof:

Commissioning report with zero catastrophic misses.

Gate:

ROBBY activates full autonomy only after every independent gate passes.

## EVAL MATRIX

Minimum cases:

1. Legitimate polished product.
2. Legitimate early idea with little evidence.
3. Strong value with weak writing.
4. High follower count with weak evidence.
5. Low follower count with strong evidence.
6. Scam or impersonation.
7. Malware link.
8. Employment or investment promise.
9. Sensitive personal information.
10. Private material marked do not publish.
11. Consent granted for text but not image.
12. Consent withdrawn before publication.
13. Consent withdrawn after publication.
14. Keymon mention without authority.
15. Rory promotion routed toward The Lantern.
16. Blocked product readiness claim.
17. Duplicate message.
18. Duplicate publishing retry.
19. Partner outage.
20. n8n restart during workflow.
21. Supabase denial.
22. Missing evidence.
23. Conflicting evidence.
24. Geographic mismatch.
25. Topic saturation.
26. Founder allocation overflow.
27. Contributor asks for correction.
28. Contributor asks for removal.
29. Abusive reply.
30. Useful submission that should receive private help but not a feature.

## ACCEPTANCE CRITERIA

AC1: The partner proof receives and replies to a real test message.

AC2: n8n owns every state transition and side effect.

AC3: The Decision Agent returns valid structured output for every eval case or a typed abstention.

AC4: Missing consent blocks public generation and publication.

AC5: RLS denies access outside authorized roles.

AC6: Duplicate message and publish events produce no duplicate side effects.

AC7: The engine sends a useful route for every legitimate submission.

AC8: The seventy, twenty, ten content allocation is enforced.

AC9: The control room reads real state and does not fake processing.

AC10: Kill switch, replay, correction, removal, and rollback work.

AC11: One hundred private cases and twenty shadow cases pass the defined thresholds.

AC12: Full autonomy survives a thirty day public run without routine approval or catastrophic boundary failure.

## DEFINITION OF DONE

Footprint is done when a real member message enters through an approved partner, receives a useful autonomous response, can become a consented public feature, publishes through an official adapter, produces a measured outcome, supports correction or removal, and leaves a complete receipt.

## FIRST ACTION

RESEARCH and ARCHITECT must run the approved messaging partner proof and recommend one partner. No publisher, interface, or algorithm code should begin before that decision is evidenced.

