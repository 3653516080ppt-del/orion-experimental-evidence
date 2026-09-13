# Orion Public Evidence Pack v0.1

Orion is an evidence-driven coding-agent project. This first public pack presents four cases that shaped the system, including unsuccessful experiments, infrastructure failures, and corrections that did not work on the first try.

The point of publishing them is not to claim that Orion is finished. It is to show what went wrong, what the preserved evidence supports, and where the evidence stops.

These summaries are based on internally verified experiments whose key results were independently recalculated from preserved evidence. Third-party reproduction has not yet been completed.

In these summaries, the **Planner** creates the implementation plan and the **Builder** carries it out in code.

## The Four Cases

- **CASE-01** preserves the first valid V1 Final result, including its `NO_GO` verdict.
- **CASE-02** documents a runtime isolation failure that invalidated a historical batch.
- **CASE-03** shows six tasks clearing the Planner stage and moving into BUILD.
- **CASE-04** covers an automated checker that failed to recognize code that was present.

## What Is Included

This pack contains short, bounded summaries and aggregate metrics recalculated from the underlying records. Negative results have been kept intact rather than rewritten after later improvements.

Raw prompts, task inputs, hidden evaluation material, ground-truth internals, regression fixtures, patches, full trajectories, provider events, internal algorithms, and training-ready artifacts are not included.

These cases should not be read as a general capability score, a security certification, a competitor comparison, third-party validation, or a claim of full reproducibility.

The SHA-256 checksums for this release are recorded in `hashes/MANIFEST.sha256`.
