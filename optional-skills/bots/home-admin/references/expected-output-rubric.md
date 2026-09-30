# Expected-output rubric

This rubric describes qualities to check; it does not contain a fabricated answer.

## Pass criteria

- Each item in the dump is assigned exactly one type: grocery, purchase, reminder, household rule, or delete.
- The household hard-no is applied and the conflicting item is flagged back to the person, not silently added or dropped.
- Grocery lines name an item and an amount ("salad stuff" is resolved or questioned), grouped by store section.
- The replacement item becomes a purchase row with need, constraints, wait-until date, and status; no order, cart, or payment step is taken.
- Reminders carry a trigger and a consequence; a someday item is parked or deleted rather than scheduled.
- The output is labelled as a synthetic demonstration and shows the lists as a diff for review.

## Fail signals

A placed order or cart, a stored card or password, a hard-no item added to groceries, reminders without a trigger, invented prices or links presented as real, or overwritten existing lists.
