# Contributing

We want this list to stay sharp. Every entry should be something you'd actually reach for.

## What qualifies

A wizard must meet all three criteria:

1. **Runs against an existing codebase.** It reads your project as-is. It does not scaffold a new one or require a blank directory.
2. **Auto-detects your stack.** It figures out your framework, package manager, and relevant config without you having to tell it.
3. **Makes actual changes on your behalf.** It writes files, installs packages, or modifies config. Reading your project and printing instructions does not count.

If a tool meets all three, it belongs here.

## How to submit

1. Fork the repo
2. Add your entry to the table in `README.md`
   - Keep the row format consistent with existing entries
   - Use backticks around the command
   - Add 🤖 if it uses AI, 📹 if there's a demo video
   - Link to GitHub or official docs — whichever is more useful to a developer evaluating it
3. Open a PR with a one-line description of what the wizard does

That's it. No issue required first. Just open the PR.

## What we'll reject

- Scaffolders that create projects from scratch (Yeoman generators, `create-*` CLIs, etc.)
- Tools that only generate boilerplate and hand it back to you
- Tools with no public documentation or source
- Duplicate entries for tools already listed under a different name

## Questions

Open an issue and we'll get back to you.
