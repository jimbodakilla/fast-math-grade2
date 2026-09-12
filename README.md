# Grade 2 FAST Math Trainer

A single-file practice app for **Florida FAST K–2 Mathematics (Grade 2)**, built around the
B.E.S.T. standards. Open `index.html` — no build step, no dependencies, works offline.

**Live:** https://jimbodakilla.github.io/fast-math-grade2/

## Why it exists

FAST K–2 is a computer-adaptive Star test. The Individual Student Report gives you **nine domain
scores and no question-level detail at all** — so it tells you *where* a child is losing points but
never *why*. This page closes that gap.

Enter the nine domain scores from your child's ISR and it maps each one to:

- the exact **Florida B.E.S.T. benchmarks** behind that domain (quoted from the standards document)
- the **specific misconception** most likely costing the marks
- a **four-day plan** that attacks the widest gap first

## What's in it

| | |
|---|---|
| **110 written items** | every answer key independently recomputed by a validator; benchmark limits enforced (perimeter ≤100 units, sums ≤100, coins ≤100¢, clocks on the five-minute grid) |
| **Procedural generators** | unlimited fresh questions in six domains — 90,000 generated items stress-tested against their own keys |
| **Interactive figures** | tap unit segments to count a perimeter, tap coins for a running total, tap bars, count a clock by fives, click a shape |
| **34-question mock** | two modes — *practice* (back / next / flag / pause, fixed form) and *real rules* (adaptive, answers locked, matching how FAST K–2 actually behaves) |
| **Review tab** | only the questions that went wrong, grouped by domain, with the re-teach for each and a session history |

## Two things worth knowing about FAST K–2

1. **At Grade 2 the domain titled "Perimeter, Area, and Volume" is only perimeter.** Florida's own
   description: *"counting unit segments around the boundary of a polygon (without gaps or overlaps)
   and by using whole number side lengths."* There is no area and no volume on the Grade 2 test.
2. **A domain score is an estimate, not a count of mistakes.** The state defines it as the percentage
   of grade-level items in that domain the student would be expected to answer correctly. On a
   34-item test across nine domains, a child may see only three or four items per domain — so treat
   each number as a signal with wide error bars. This app deliberately reports raw
   correct-out-of-seen rather than a score that looks comparable to the official one.

## Accessibility

Read-aloud on every question (and a visible fallback when the device has no speech engine), a free
"stop for now" exit on every screen, enforced movement breaks, pause, ≥44px touch targets throughout,
WCAG AA contrast in light and dark, and `prefers-reduced-motion` respected.

## Sources

- [Florida's B.E.S.T. Standards for Mathematics](https://cpalmsmediaprod.blob.core.windows.net/uploads/docs/standards/best/ma/mathbeststandardsfinal.pdf)
- [Understanding FAST K–2 Student Reports for Families](https://flfast.org/)
- [Statewide Assessments Accommodations Guide](https://flfast.org/)
- [Florida Statewide Assessment Schedule](https://www.fldoe.org/accountability/assessments/k-12-student-assessment/assessment-schedules.stml)

Not affiliated with the Florida Department of Education, Cambium or Renaissance Learning.

## Licence

MIT — use it, fork it, adapt it for your own child.
