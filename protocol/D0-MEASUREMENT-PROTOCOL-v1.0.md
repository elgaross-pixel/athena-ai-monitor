# D0 Measurement Protocol v1.0

Status: ACTIVE
Established: 2026-10-01

## Objective
Establish the pre-intervention baseline for product visibility and characterization in consumer AI recommendation surfaces.

## Surfaces
ChatGPT; Gemini; Perplexity; Microsoft Copilot; Claude; Grok.

Consumer/search responses are the target. API-model output must not be silently substituted. Failed/unavailable measurements are UNRESOLVED, not zero.

## Capture
For each run record: checkpoint, prompt ID and exact text, surface, date/time, target offer, full answer, citations/URLs, products named and order, target mentioned yes/no, target explicitly recommended yes/no, position when determinable, AI-O characterization, factual errors/uncertainty, notes.

## AI-V
Report mention presence/rate, recommendation presence/rate and position where determinable. Missing runs are excluded and reported.

## AI-O
Record target audience/use case, capabilities, price/value characterization, strengths, limitations, comparative claims and recommendation rationale. Do not collapse AI-O into an overall winner score.

## Integrity
Capture intended D0 before the next deliberate AI-visibility intervention on SelectVerdict or Search Data Bench. Existing site state is the pre-intervention state. Later checkpoints use Frozen Prompt Set v1.0 verbatim.
