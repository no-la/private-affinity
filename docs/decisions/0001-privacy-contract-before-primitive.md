# ADR-0001: Start from the privacy contract

- Status: Accepted
- Date: 2026-10-01

## Context

The project exists to build an artifact using programmable cryptography. PSI,
zero-knowledge proofs, MPC, FHE, and threshold cryptography could each support
different interactions and trust models. Selecting one before defining the
experience would allow the technology to dictate the product and could result
in unnecessary disclosure or complexity.

## Decision

Define the user interaction, private inputs, revealed result, parties, and trust
assumptions before selecting the cryptographic primitive or system topology.

Anonymous affinity matching is the initial idea, but it does not constrain the
final interaction or implementation.

## Consequences

- No cryptographic primitive is selected by this ADR.
- The next project milestone is a concrete privacy contract for one interaction.
- Candidate protocols will be compared against the same product and privacy
  requirements.
- A simpler artifact is acceptable when it demonstrates the chosen capability
  more clearly.
