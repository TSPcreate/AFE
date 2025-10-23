# AFE Master Agent Log

_Last updated: 2025-10-23 22:00 UTC_

## Vision & context
- **Project name:** AFE (AI For Education)
- **Goal:** Provide GCSE students with dynamically generated exam-style papers, guided marking, and actionable revision feedback.
- **Long-term workflow:**
  1. Landing Page
  2. Sign In / Create Account
  3. Dashboard (progress overview + generate paper)
  4. Paper Generator (choose type → generate)
  5. Paper View (read / download / answer)
  6. Mark Scheme (model answers)
  7. Self-Mark (enter scores)
  8. Feedback & Reflection (advice + micro-tasks)
  9. Dashboard (updated progress & next steps)
- **Design direction:** Clean interface inspired by markme.ai with a blue + black visual theme.
- **Content:** AI-powered generator planned; temporary static question bank will be used before integration.

## Current state (2025-10)
- ✅ Static landing page implemented in `public/` with sections for hero, features, workflow, insights, and call-to-action.
- ✅ README updated with project introduction and instructions for serving the static page.
- 🚧 No build tooling yet (pure HTML/CSS). Future work may adopt a framework such as React/Next.js once dynamic flows begin.
- 🚧 No backend, authentication, or database configured.

## Decisions & rationale
- **Initial delivery:** Start with a fast, framework-agnostic landing page to iterate on content while the product scope is refined.
- **Styling:** Custom CSS with focus on blue/black gradients and card-based layout to mirror the requested aesthetic.
- **Serving strategy:** Use a simple static server (`python3 -m http.server`) until the project requires a more complex stack.

## Next priorities
1. Gather feedback on landing page copy, layout, and theme.
2. Choose frontend framework (e.g., React/Next.js) for authenticated dashboard and dynamic interactions.
3. Design data structures for the static question bank that will power the generator MVP.
4. Outline API contracts for self-marking, reflections, and progress tracking modules.

## How to contribute next
- Align upcoming work with the workflow stages above.
- Update this log after each significant change to keep agents in sync.
- When implementing interactive flows, introduce component/page structure within the selected framework and document decisions here.
