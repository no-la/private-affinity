# Private Affinity

Private Affinity is a programmable cryptography project for discovering shared
interests or compatibility without revealing participants' private inputs.

## Status

The project is in its concept and protocol-design phase. Anonymous matching is
the initial product idea, not a fixed implementation specification.

## Goal

Build something people can operate and experience—not merely a standalone
cryptographic calculation—and demonstrate what becomes possible when private
inputs remain hidden during computation.

The first version should:

- use programmable cryptography as a core capability;
- make a meaningful decision from private participant inputs;
- reveal only a deliberately chosen result;
- run or be reproducible at no cost;
- explain its privacy boundary and limitations.

## Initial product idea

Participants in a small, closed community privately provide interests or
intentions. The system evaluates a compatibility condition and enables a
connection only when the chosen condition is satisfied.

This is a starting point. The interaction, revealed result, cryptographic
primitive, and delivery format remain open until they have been evaluated
together.

## Design principle

Choose the experience and privacy contract first, then select an appropriate
primitive such as PSI, zero-knowledge proofs, MPC, FHE, or threshold
cryptography. A primitive is not the product by itself.

## Documentation

- [Product definition](docs/product.md)
- [Privacy model](docs/privacy-model.md)
- [Threat model](docs/threat-model.md)
- [Architecture decisions](docs/decisions/README.md)

## Current non-goals

- production-grade availability;
- commercial authentication and monitoring;
- large-scale deployment;
- a formal security audit;
- complete Sybil resistance.

These can be reconsidered if the selected experience requires them.

## Next decision

Define one concrete user interaction and its privacy contract: who supplies
which secret, who performs the computation, and exactly what each party learns.

