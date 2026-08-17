# Dreaming Loop — Weekly Improvement Pass

1. Read dreaming-state.md to find last_reviewed_date.
2. Read all entries in progress.md dated AFTER that date.
3. Look for any failure or correction that appears MORE THAN ONCE
   across different entries — a real repeated pattern, not a single
   occurrence.
4. For each repeated pattern found, draft the SMALLEST possible
   change to a skill file (e.g. .claude/skills/fix-bugs.md) that
   would prevent it. Do not rewrite whole files — add one precise
   line or rule.
5. Also look for one existing rule in the current skills that no
   recent run actually needed — propose deleting it.
6. Put all proposed changes on a new branch (claude/dreaming-*),
   never commit directly to main.
7. Open a PR. The PR description MUST cite evidence: which dated
   log entries support each proposed change, how many times the
   pattern occurred, and why this specific change would prevent it.
8. If no repeated pattern is found, say so explicitly — do not
   invent one.
9. Update dreaming-state.md with today's date as the new
   last_reviewed_date, and commit that on the same branch.
