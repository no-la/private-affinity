# Product definition

## Problem

People in a community may share interests, needs, or intentions but hesitate to
publish them to the community or its operator. This prevents useful connections
from being discovered.

## Product hypothesis

A participant is more willing to provide sensitive preferences when the system
can evaluate a useful condition without disclosing the underlying input, and
only the agreed result is revealed.

## Candidate experience

1. A participant joins a small, closed session.
2. Each participant privately supplies interests or preferences.
3. The system evaluates a compatibility condition using programmable
   cryptography.
4. Only the specified result is revealed.
5. Participants decide whether to connect or disclose more.

This flow is a hypothesis, not a committed interface.

## Target outcome

The result should be an operable artifact: a web application, CLI, game, or
interactive tool. A small multi-user prototype is preferred when feasible; an
interactive single-device simulation remains acceptable if deployment would
distract from the cryptographic idea.

## Success criteria

- Programmable cryptography is necessary to the central interaction.
- A user can provide an input and observe a meaningful result.
- The project states what is secret and what is revealed.
- The reason for the selected primitive is understandable.
- Limitations and remaining leakage are documented.
- Another person can reproduce or try the result for free.

## Open product decisions

- Who is the first intended user?
- Is the interaction pairwise or group-based?
- Are inputs selected from a fixed set or freely entered?
- Is the output a Boolean threshold, a score, or a shared item?
- Is mutual consent required before revealing the result?
- Must the first version work across multiple devices?

