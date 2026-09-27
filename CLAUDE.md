# Claude instructions

## Skills discovery

Before starting a non-trivial task, use the `find-skills` skill
(`.claude/skills/find-skills/SKILL.md`) to check whether an existing agent skill
covers the task (`npx skills find <query>`, leaderboard at https://skills.sh/).
Prefer well-known sources (`vercel-labs`, `anthropics`, `microsoft`) with 1K+
installs, and tell the user which skill you found before installing it
(`npx skills add <owner/repo@skill> -g -y`).
