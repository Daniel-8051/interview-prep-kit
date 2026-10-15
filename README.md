# Interview Prep Kit

Software engineering interview prep as five [Claude Code](https://claude.com/claude-code) skills.

The skills ask the questions. You write the answers. Nothing here writes your stories for you, because anything you didn't write yourself is something you can't defend under follow-up.

## Setup

1. Clone this repo (or use it as a template) and open it in Claude Code. The skills in `.claude/skills/` load automatically.
2. Put your current CV in `cv/current.md`.
3. Brain-dump one project into `corpus/<project-name>.md`. See `corpus/README.md`.

That's it. Start with the sceptic on that project.

## Layout

| Path | What it is |
|---|---|
| `corpus/` | One file per project, in your words. The source for everything else. |
| `misses.md` | Every gap that caught you out. Your revision list. |
| `cv/current.md` | Your real CV. Gitignored. |
| `applications/` | One folder per job, made by the recruiter. |
| `practice/` | Coding exercises, made by the reviewer. |

`corpus/` and `misses.md` are the two that matter. The skills just fill them.

## The skills

| Skill | Say | What it does | What it never does |
|---|---|---|---|
| **sceptic** | "grill me about X" | Appends hard questions to a corpus entry | Edit your words or answer for you |
| **architect** | "architect me" | Runs a live system-design interview | Hint at requirements or components before the debrief |
| **reviewer** | "give me a coding problem" | Writes a half-built Java exercise into `practice/`, then reviews your solution | Respond to anything but `done` or `stuck` while you work |
| **examiner** | "run a technical screen" | Asks broad fundamentals questions, one follow-up each | Correct you mid-round |
| **recruiter** | "run the recruiter on X" | Compares a job description to your CV and corpus, grades your bullets | Write bullets, unless you explicitly ask it to |

The sceptic and recruiter read your corpus. The architect, reviewer and examiner don't, because they test fresh thinking.

All of them except the sceptic append what you missed to `misses.md`.

## How to use it

**1. Build the corpus first.**
Dump each project once into `corpus/`. Run the sceptic on it and answer its questions inline. Repeat until a round lands nothing. Do this for your three or four best projects before anything else. Every behavioural and "tell me about" question draws from here.

**2. Log sceptic misses yourself.**
When a sceptic question stings, copy it into `misses.md`. This is the one step no skill does for you, on purpose: you decide what's a real gap.

**3. Practise regularly.**
Rotate the architect (system design), reviewer (coding) and examiner (fundamentals). One session a day is plenty. Each feeds its gaps into `misses.md`.

**4. Apply for a job.**
Run the recruiter on the job description. It tells you what the role really wants, where you're covered, and where you aren't. Write your tailored bullets in `draft-bullets.md` and let it grade them. Real experience gaps go to `misses.md` as things to prepare an honest answer for.

**5. Before an interview.**
Read `misses.md` top to bottom. That's the revision.

## Tips

- **Commit after every session.** Small and often. Your history then shows what you practised.
- **Keep your repo private.** Once you fill it, it holds your CV, projects and weak spots.
- **Don't build more tooling.** It feels like progress and isn't. If you're tempted, run a sceptic round instead.
- **Whiteboard mode (optional).** If you connect an Excalidraw MCP server (for example `claude mcp add excalidraw -- npx -y mcp-excalidraw-server`) with its canvas at `http://127.0.0.1:3000`, the architect lets you draw your design on a canvas and reads it back. Without it, you describe the design in text.
- **Change the seeds.** `architect/seeds.md`, `reviewer/seeds.md` and `examiner/topics.md` hold the starting questions. Edit them to suit your stack or level. The reviewer is Java by default.
