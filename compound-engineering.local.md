---
review_agents: [code-simplicity-reviewer, security-sentinel, performance-oracle, architecture-strategist]
plan_review_agents: [code-simplicity-reviewer]
tdd_enabled: false
review_mode: bulk
---

# Review Context

Add project-specific review instructions here.
These notes are passed to all review agents during /workflows:review and /workflows:work.

Examples:
- "We use SQLite FTS5 BM25 for search -- verify rank semantics (more negative = better)"
- "Our seahorse memory engine is performance-critical"
- "Frontend uses React + TypeScript"
