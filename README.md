# awsm-proj-plan

A skill for Claude to plan projects with multiple deliverables or a personal routine, from clarifying scope to structuring documentation.

## What it does

1. Identifies the project type: software/tool, content/series, design library, research/learning, personal/routine, or other.
2. Before planning, lists possible paths to the result, then asks guided questions in short rounds to choose among them and confirm goal, limits, deliverables, assumptions, and risks.
3. Writes the scope and breaks each deliverable into verifiable tasks, with at most 10 tasks per plan.
4. Suggests skills and connectors for each stage, checking what is actually available in the session.
5. Checks existing documentation before creating anything new, and keeps everything in a single place.
6. Changes existing files only after your approval.

It does not depend on other skills. The questioning is handled by the skill itself.

## Installation

**Option 1: copy the folder**

Copy the `awsm-proj-plan` folder to the Claude Code skills directory:

```
~/.claude/skills/awsm-proj-plan/
```

Then restart the session so the skill is loaded.

**Option 2: upload through the interface**

Upload the folder (or a zip of it) through the Claude skills screen, as a custom skill.

## Usage

Ask for a plan for a project with multiple deliverables or for a routine, for example:

> I want to plan the production of a comic series with 6 chapters.

or

> I need to organize my study and work routine for the next quarter.

The skill is also triggered by the Portuguese and English phrases defined in its description.

## Related skills (optional)

- **version-vx-x-x**: used by the software/tool type to number versions as vX.X.X. If it is not installed, the skill works without it.

## Language

The skill replies in the same language as the user's most recent chats. If usage is balanced (up to 60/40 between two languages), it asks which language the user prefers before replying.

## License

MIT. See [LICENSE](LICENSE).
