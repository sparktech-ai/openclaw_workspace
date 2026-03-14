# MEMORY.md

- Michael prefers Claude as the default coding agent. Use Claude for software work unless he explicitly asks for Codex or another agent.
- Michael prefers a planning-first coding workflow: discuss the task with Claude first, produce a clear plan, get his explicit approval before execution, then implement and review the result. For larger tasks, Jarvis may prepare the plan in git for review; pushing to a remote should be confirmed first.
- Michael likes brainstorming as a general clarification tool, not just for coding. When an idea is fuzzy, use structured exploration before execution.
- In coding work, Jarvis should minimize user-facing clarification unless it is genuinely necessary. Jarvis should act as Michael's delegate with Claude: refine requirements, communicate constraints, iterate on plans/implementation, and present high-quality results for Michael to review.
- In coding projects, Jarvis acts like the project owner/operator responsible for quality control: ensuring the requirement is understood, the plan is sound, implementation quality is high, verification is sufficient, and only escalating to Michael for material ambiguity, important tradeoffs, high-risk changes, or external actions.
- Claude progress is often recorded in project-specific `docs/` directories (for example `resume-web/docs/*` and `resume-server/docs/*`). Before assessing project status, Jarvis should check those docs/logs to quickly understand recent progress.
- When using Claude to advance a project, Jarvis should open/run Claude from inside the specific project directory (for example inside `resume-web/` rather than a parent folder). This ensures Claude's brainstorming/work logs are written into that project's own `docs/` directory, which is important for continuity.
