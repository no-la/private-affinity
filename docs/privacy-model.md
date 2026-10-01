# Privacy model

The privacy contract must be chosen before the cryptographic primitive.

## Candidate private inputs

- selected interests;
- intentions or activities a participant wants to try;
- compatibility preferences;
- the number and identity of non-matching participants.

This list describes possible inputs. The first product scenario will select the
minimum required set.

## Candidate outputs

The project should reveal the least informative output that still enables the
desired experience. Possible outputs, from less to more revealing, include:

1. whether a threshold was met;
2. a bounded compatibility score;
3. the number of common items;
4. the common items themselves.

No output has been selected yet.

## Parties to consider

- the participant supplying an input;
- another participant;
- a session or community operator;
- computation or storage services;
- an outside observer.

For the selected scenario, the project will document what each party knows
before, during, and after the protocol.

## Privacy-design questions

- Who must not learn each input?
- Is the output delivered to one participant or mutually?
- Does learning that no match occurred reveal sensitive information?
- Can repeated queries be combined to infer an input?
- What metadata remains visible, such as timing, peer identity, and message
  size?
- What trust or non-collusion assumption does the protocol require?

