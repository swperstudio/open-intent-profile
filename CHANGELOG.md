# Changelog

## v0.2.0 (12 October 2026)

Why: the `sponsored` flag contradicted the spec's core claim that the best product should win, not the biggest budget. v0.2 makes that claim a principle, closes the commission loophole, defines merit so it can't be turned into a gameable badge, and lets a profile start small enough that people will actually use it. Full reasoning is in the commit message for this release.

- New principle: money never bends the match.
- Removed the `sponsored` flag. Replaced it with a no-paid-influence rule and a `commercial` declaration on every recommendation, including affiliate and commission relationships.
- Added "Starting small": a profile can be just an owner and one active brief. Agents must work with sparse profiles.
- Defined merit as personal fit times evidence. No global scores. Evidence includes what owners report back, not only certificates.
- Product claims moved to a planned companion spec. A claim without evidence is weighed as a claim, not a fact.
- Said what claiming support for the spec means.
- Added `examples/profile-minimal.json`.
- Trimmed open questions to the ones that need outside help.

## v0.1.0 (3 October 2026)

- First public draft.
