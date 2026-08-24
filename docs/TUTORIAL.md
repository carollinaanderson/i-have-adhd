# 🎬 TUTORIAL — write ADHD-friendly output in 5 minutes

> The fastest way to see why this skill exists: compare the two answers below to the question *"my deploy failed, what should I do?"*

## Before (typical agent output)

> "Your deployment failed. This could be caused by several factors including but not limited to configuration drift, insufficient permissions, or upstream service degradation. I'd recommend investigating the logs in your CI pipeline, checking the status of the environment..."

**Your ADHD brain:** where's the fix???

## After (with i-have-adhd)

1. **Do this first (2 min):** open the CI logs → copy the 5 lines around the first `ERROR`.
2. **Then:** paste them here — I'll pinpoint the exact cause.
3. **While you wait:** check that your branch matches `main` (30 sec).

*Nice — you already made the first move. Progress!*

## The 6 rules, with examples

| Rule | Bad | Good |
|---|---|---|
| Lead with action | "There are several things to consider..." | "Do this first (2 min):" |
| Number everything | bullets, bullets, bullets | 1. · 2. · 3. |
| Restate state | assumes you remember context | "We're at step 3 of 5. Done so far: ✓ 1, ✓ 2" |
| Quarantine tangents | side note in the middle of the answer | side note moved to a clearly labeled aside at the end |
| Time estimates | "soon" / "shortly" | "2 min" / "~15 min" |
| Show wins | work is invisible | "You've already completed 2 of 5 steps ✅" |

## Try it yourself

1. Install the skill (see [INSTALL.md](INSTALL.md))
2. Open any agent session and type `/i-have-adhd`
3. Ask it a real question — then ask the *same* question in a fresh session without the skill
4. Keep the version that lets you act faster — that's the whole point
