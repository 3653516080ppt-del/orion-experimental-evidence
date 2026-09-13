# CASE-04: When Correct Work Looked Missing

In two controlled cases, an automated checker inspected the repository after the Builder finished and reported that expected code was missing, even though the code was present. Across repeated checks, this produced four false negatives.

After the correction, the same cases produced no false negatives. Five controls also produced neither a false positive nor a false negative. Preserved validation records show 40 out of 40 focused tests and 489 out of 489 full regression tests passing.

## Why It Matters

An autonomous coding system can reject correct work when two parts of the system refer to the same code in different ways. If observation failure is not separated from implementation failure, the system records the wrong root cause and may attempt an unnecessary repair.

## The Limit of the Evidence

The controls cover a bounded set of cases. They do not certify every language, parser shape, or program structure, and they do not show that Builder quality is universally solved.

Evidence status: The numbers were recalculated from preserved internal records rather than copied from the original summary. No external party has yet reproduced this case.
