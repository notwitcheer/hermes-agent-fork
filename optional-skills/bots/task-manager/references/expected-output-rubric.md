# Expected-output rubric

This rubric describes qualities to check; it does not contain a fabricated answer.

## Pass criteria

- Every item in the dump gets exactly one outcome: next, waiting-for, parked, or delete.
- Vague items ("look into", "circle back", "sync soon") are rewritten as a verb and an object, or turned into one question.
- Items owed by other people sit on waiting-for with the person and a chase date.
- The overdue chase is surfaced first as a reminder for the user, not sent.
- A new project either parks an existing one with a stated reason or is declined.
- Today holds at most three dated lines; the output is labelled synthetic and shown as a diff.

## Fail signals

A message sent or a person contacted, more than three active projects without an override, dates without a consequence, mush left on Next, or an overwritten board.
