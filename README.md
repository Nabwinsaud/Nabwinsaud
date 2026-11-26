# Nabin Saud

I build harnesses for AI agents, and tools for people who live in the terminal. Kathmandu, Nepal.

```text
┌─ claude ─────────────┬─ nvim ───────────────┐
│ agent working on     │ reading the diff     │
│ KAN-3 in a worktree  │ it just wrote        │
├─ forgeline run ──────┼─ git ────────────────┤
│ review → approve     │ PR #12 merged ✓      │
└──────────────────────┴──────────────────────┘
```

Most days look like that: panes in Rex, Neovim, a couple of agents
running next to me. I'm less excited about "AI writes my code" than about everything *around* the agent:
the gates, hooks, state machines and review loops that turn its output into something you'd actually
merge.

## Now

**[Forgeline](https://github.com/Nabwinsaud/forgeline)**: an agentic software factory for Claude Code.
A ticket goes in. Out come a spec, code, tests, a security pass, a deterministic gate, parallel reviewers
and a PR, with the merge policy written in code. Agents judge, code decides.

```sh
npm create forgeline      # set it up in any repo
```

## Things I've built

| | |
|---|---|
| [forgeline](https://github.com/Nabwinsaud/forgeline) | ticket → shipped feature with Claude Code agents, guard hooks and a gate they can't edit |
| [mantra](https://github.com/Nabwinsaud/mantra) | keyboard-first PostgreSQL IDE for the terminal |
| [paisa](https://github.com/Nabwinsaud/paisa) | one SDK for Nepali payment gateways (eSewa, Khalti), plus a NestJS adapter |
| [nvim-config](https://github.com/Nabwinsaud/nvim-config) | the editor setup behind all of it |
| [mac-tapper](https://github.com/Nabwinsaud/mac-tapper) | knock on your MacBook, it makes a sound. Because why not |

## How I work

- **Terminal first.** Rex for sessions and panes, Neovim, CLIs over dashboards.
- **Agents as teammates, with limits.** Claude Code, Codex, OpenCode, each in its own worktree with
  its own tools. Reviewers that can't edit. Builders that can't merge.
- **Boring guardrails win.** Tests that gate, policy in code, the commit SHA that passed is the one that ships.
- **Still a backend engineer underneath.** Go, TypeScript (Node, NestJS), PostgreSQL.

## Thinking about

- where the gate should live so an agent with a shell can't route around it
- review loops between agents that converge instead of nitpicking forever
- writing business rules down so agents follow them instead of guessing

## Say hi

[nabinsaud.com.np](https://nabinsaud.com.np) · [@NabwinSaud](https://x.com/NabwinSaud) · nabinsaud2059@gmail.com

If you're building agent harnesses too, I'd like to compare notes.
