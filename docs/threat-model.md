# Threat model

This document is deliberately provisional. It records the questions that must
be answered once the first interaction is selected.

## Assets

- private participant inputs;
- computation results not intended for a given party;
- associations between participants;
- protocol secrets and credentials.

## Candidate adversaries

- an honest-but-curious service operator;
- a participant attempting to infer another participant's input;
- a participant repeating queries with modified inputs;
- multiple accounts controlled by one participant;
- an observer of network or application metadata.

## Initially acceptable exclusions

- a compromised participant device;
- voluntary disclosure after a result is revealed;
- production availability attacks;
- a formal guarantee against every Sybil attack;
- malicious cryptographic implementations or dependency compromise.

These are not claims of safety. They are possible boundaries for a first
artifact and must be revisited after choosing the protocol.

## Required analysis before implementation is called complete

- define which adversaries are in scope;
- state every trust and non-collusion assumption;
- analyze dictionary and repeated-query attacks;
- identify metadata leakage;
- distinguish a demonstration parameter set from production-safe parameters;
- explain what would be required for real-world deployment.

