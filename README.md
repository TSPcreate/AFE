# AFE (AI For Education)

AFE is an AI-assisted revision companion that generates challenging GCSE-style past papers,
helps students self-mark, and recommends personalised micro-tasks. This repository currently
contains the initial landing page for the project.

## Getting started

The landing page is a static site served from the `public/` directory.

```bash
# From the repository root
python3 -m http.server 8000 --directory public
```

Then visit http://localhost:8000 in your browser.

## Project roadmap

1. Build authentication and a personalised dashboard to track subject progress.
2. Implement the paper generator backed by a static question bank (before AI integration).
3. Deliver paper viewing, marking, and reflection workflows end-to-end.
4. Integrate the AI model that dynamically composes new past papers.

See `AI_AGENT.md` for context, decisions, and next steps tracked for contributors.
