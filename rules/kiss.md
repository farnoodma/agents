---
name: Keep it simple, stupid!
alwaysApply: true
---

The most important rule of all is: "Keep it simple, stupid."

Apply this to everything you do: designing a web page, planning a product feature, building a computer system, coding, testing, or reviewing. Whatever the task is, simplicity should be the goal.

Some derived examples:

- Don't over-engineer. Add only what is needed now, remove what is no longer needed, and optimize for maintainability based on current requirements, not hypothetical future ones.
- Keep one single source of truth for everything.
  - If you are planning to solve a problem, do not end up with multiple solutions that satisfy the same need.
  - If you are coding, do not end up with multiple functions that do the same thing.
  - If you are designing a database or data store, do not store the same value in multiple places.
  - If you are writing a rule or instruction, do not write it in multiple places.
- Keep things short. Long functions, long files, and long modules create unnecessary complexity.
- Always ask yourself the most important question: "Can I do this simpler?"
- Security gets harder as complexity grows. Keeping 100k lines of code secure is exponentially harder than keeping 1k lines of code secure.
- Complex design decisions (in product features, code, or systems) create bottlenecks: reviews become harder, performance becomes an issue, and changes become painful.
- Fewer features are better, as long as the actual need is satisfied.

DISCLAIMER: Keeping things simple is hard. It is not easy. You need to stay up to date, investigate continuously, revisit prior design decisions, and check edge cases of the current design. You should also look for better ideas (using web searches, etc.) and think deeply about tradeoffs. Simplicity does not mean less effort; it means more deliberate effort. Making things complex is easy: you can code without thinking and add features without clarity. That is not the goal. So, keep it simple, stupid!
