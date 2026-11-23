# Release notes

## 1.0.1 beta 1 — November 23, 2026

- Correct answers now show **Correct!** without an explanation card full of details.
- Wrong answers show the correct shuffled choice and a short explanation.
- **Learn more** expands the three other choices’ rationales; **Show less** collapses them. The correct rationale is no longer repeated.
- Both outcomes wait for **Next question**; no automatic jump.
- Existing questions, scheduling, local storage and signing identity are preserved.

Validation: 26 automated tests, 0 failures/errors/skips; Android lint 0 errors, 6 nonblocking warnings. The exact APK passed Android 16 emulator upgrade, correct/wrong feedback, expand/collapse and restart checks; saved study progress survived the update.

## 1.0 beta 1 — November 23, 2026

- 160 original questions mapped to all 19 objectives across five CC domains.
- Endless shuffled practice, domain focus and missed-question review.
- Correct-answer and distractor explanations.
- Local resumable progress, including selected choice and shuffled order.
- Android Back navigation and protection against duplicate/stale answer callbacks.
- Offline operation without account, models, ads or purchases.

Validation: 25 automated tests, 0 failures/errors/skips; Android lint 0 errors, 6 nonblocking warnings; Android 16 emulator practice/navigation/restart checks; owner-reported Galaxy S24 Ultra use.

This is the same tested APK as the initial personal build. Debug-signed beta; app source is not published.
