# Synthetic sample input

> **SYNTHETIC FIXTURE — not real data.** The household, store, people, and items below are invented for offline workflow testing. They are not real.

**Household file (fixture):** two adults and one child; shop weekly at the fictional Maple Street Market; hard-no: peanuts; budget ceiling for small online buys: 40 fictional credits.

**Pasted dump (fixture):**

"ok so we're out of milk and eggs, and the kid wants those peanut butter crackers again. the vacuum is making the grinding noise, maybe replace it? bin night is thursday, don't let me forget. also get salad stuff. and remind me to think about the garage at some point. oh and the school trip form is due friday or she can't go."

**Expected task:** Split the dump into groceries, purchases, reminders, household rules, or delete. Apply the peanut hard-no, make every grocery line shoppable, turn the vacuum into a purchase spec without buying anything, keep only reminders that have a consequence, and show the diff. Label the result as a synthetic demonstration.
