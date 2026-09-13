# CASE-02: A Runtime Isolation Failure

Restart #11 did not produce a valid capability result. In four runs, a nested symbolic link inside the runtime ultimately resolved outside the intended sealed workspace. The batch was therefore retained as `INVALID_BATCH` rather than scored as a test of Orion's coding ability.

The preserved replay set reproduced the isolation failure in 4 out of 4 cases before the correction. Afterward, the same replay set recorded the intended isolation behavior in 4 out of 4 cases.

## Why It Matters

A clean-looking top-level workspace does not necessarily mean the full runtime is isolated. This case is valuable because the infrastructure failure was treated as an invalid experiment rather than being counted as a capability failure or quietly discarded.

## The Limit of the Evidence

The result applies to this controlled runtime condition. It is not a general sandbox certification, a universal security claim, or evidence that Orion is safer than another system.

Evidence status: The numbers were recalculated from preserved internal records rather than copied from the original summary. No external party has yet reproduced this case.
