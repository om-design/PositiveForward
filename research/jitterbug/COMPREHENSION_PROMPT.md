# Positive Forward: Jitterbug calibration prompt

26 November 2026 | Proposed calibration instrument | Copyright © 2026 omdesign. All rights reserved.

Provide this with the pinned [Jitterbug specification](https://github.com/om-design/JitterbugNetworkTopology/blob/c2543a277b644175091c4bec3051abc875a423fd/SPECIFICATION.md) only, in the guided condition. Record the exact specification and prompt versions. Keep the evaluator key separate from initial model inputs. No implementation or simulation is requested yet.

Use the elementary relationships and operating sequence in the supplied specification as the basis of your answers. Do not supply missing engineering details from a familiar networking system. Distinguish what follows from the specification, what requires a chosen implementation profile, and what cannot happen in the stated environment. Describe the state changes in each case, rather than naming a conventional protocol.

1. A resting node A attempts communication with B. B is unavailable. C and D are potential contacts not currently enabled at A. Describe what A can change, whether B must respond, and what remains dependent on contact feasibility.
2. Suppose the communication from A reaches C carrying an expansion count of 3. Follow the count through two further successful onward transfers. What happens at each receiving node? Does an onward value of zero end the message's lifetime?
3. A receiving node sees a positive count of 1. Its return timer will expire later. Its next message carries 0. What changes immediately and what can remain unchanged until the return condition?
4. A node has successfully forwarded a message and retains a local copy, but makes no further transmission attempt. What evidence of a new obstruction exists?
5. A simulation increases scan frequency and permits more copies, while holding every node's enabled connection set constant. Which part of the Jitterbug architecture has not been represented?
6. A local expansion concludes, and a similar disturbance arises later. Which information can survive contraction, and which exact selection rule is specified?
7. Two groups have no contact between them for the entire experiment, and no carrier can bridge them. What can expansion accomplish and what can it not accomplish?
8. The same local obstruction occurs in networks of 100 and 100,000 nodes. Does the countdown alone prove that aggregate expansion cost is equal? Identify what would have to be measured.
9. A model proposes three successive degrees of local expansion corresponding to received counts 3, 2 and 1. Does this represent the reference architecture? What, if anything, establishes the numerical connection limits?

After the cases, state the minimum outstanding decisions that prevent an unambiguous reference implementation. Do not implement until the evaluator has reviewed the responses. Do not change the specification to make a case easier to answer.

## Evaluation boundary

This public prompt illustrates a proposed calibration method. It is not a validated assessment or evidence of model comprehension. For controlled research, keep expected answers and held-out variants outside the tested model's accessible materials, record any known exposure to the public cases, and use new cases where necessary.
