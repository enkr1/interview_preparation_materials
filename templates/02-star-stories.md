# STAR Story Bank

Behavioural interview answers, captured while the work is fresh. Append a new story whenever you ship something meaningful. When prepping, filter by tag to find what fits the role.

## How to use

1. **Capture while it's fresh.** After shipping a project, fixing an outage, or making a hard call, spend 5 minutes adding a story here. Memory degrades fast.
2. **Tag aggressively.** Use tags to filter for the right story per role (`#scaling`, `#leadership`, `#conflict`, `#failure`, `#ambiguity`).
3. **Before an interview, pick 5.** Match tags to the role. Rehearse them out loud, not silently.

## Template

```markdown
## [Story title, short and memorable]

**Tags:** #tag1 #tag2 #tag3

**Situation:** [One line. What was the context?]

**Task:** [What was expected of you? What was at stake?]

**Action:** [What did YOU specifically do? Use "I" not "we". Include technical decisions and trade-offs.]

**Result:** [Measurable outcome. Numbers if possible. What changed because of you?]

**Reflection:** [What would you do differently? This signals growth, not weakness.]
```

## Example

## Migrated legacy auth without downtime

**Tags:** #backend #migration #zero-downtime #ownership

**Situation:** Our 8-year-old auth service was blocking three teams from shipping. Two prior attempts to migrate had failed.

**Task:** Lead the migration to a new identity provider with zero user-facing downtime, across 12M active sessions.

**Action:** I designed a dual-write phase to keep both systems in sync, wrote a session-replay test harness, and shipped behind a feature flag with 1%/10%/50%/100% rollout. When we hit a token-refresh bug at 10%, I rolled back, fixed it in 4 hours, and resumed.

**Result:** Migration completed in 6 weeks (estimate was 12). Zero user complaints. Three teams unblocked. The test harness became the standard for future migrations.

**Reflection:** I should have invested in the test harness earlier. It saved us once at 10% rollout but I built it reactively. Now I treat the test harness as a deliverable, not an afterthought.

---

<!-- Add your stories below this line -->

## [Your first story title]

**Tags:** #tag1 #tag2

**Situation:** [...]

**Task:** [...]

**Action:** [...]

**Result:** [...]

**Reflection:** [...]
