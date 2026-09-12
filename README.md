# Sparkbuild — First Three Screens

A three-screen interactive concept for finding real-world SaaS project ideas. The visual direction is dark mode with yellow spark accents. The dominant landing action is **Browse ideas**.

## Need, persona, capability, and value

- **Need:** Aspiring software engineers struggle to find good ideas for personal, resume-building projects, so they spend their limited coding time searching through generic idea lists or building projects they are not excited about.
- **Persona:** Aspiring beginner software engineers with a limited portfolio and limited free time to spend on personal projects for their resume and personal growth.
- **Capability:** Find a real-world, well-defined SaaS project idea that matches their interests, skill level, and available time.
- **Fundamental value:** Direction. The developer quickly finds something impactful to build without wasting time thinking of ideas or settling for a generic project.

## Screens

1. **Landing:** Introduces the marketplace and communicates direction with one primary Browse ideas action. It earns its place by establishing purpose and value. Design question: Can a visitor quickly understand what the product does, how it helps, and what to click next?
2. **Browse ideas:** Groups project descriptions, categories, difficulty, and time estimates in filterable cards. It earns its place by demonstrating discovery and comparison. Design question: Do cards and filters help developers quickly identify a suitable idea?
3. **Idea details:** Shows the problem, intended users, first-version scope, skills, time, and contributor, with a save action. It earns its place by providing enough detail to choose a project. Design question: Does the screen provide enough information for a developer to confidently choose the project?

## Prototype scope

Six fictional sample ideas and contributors; no accounts, payment processing, or backend. Search and filters work together. Saving lasts for the current page session. All screens link home. Estimated effort is illustrative.

## Assignment work still to complete

- Human review of initial output, then at least one meaningful design revision on a branch, merged through a pull request.
- Feedback questions and predictions covering need, value, persona, and capability.
- First-read evaluation, design justification, and a concrete before-and-after comparison.
- Public GitHub repository and public live URL for the final submission.

The initial AI output is preserved in the first commit. No user review or feedback findings are claimed yet.

## Running locally

Serve the `dist` folder with any static HTTP server. No dependency installation or build step is required. Navigation uses URL hashes so the three screens work on static hosting.

## Validation notes

JavaScript syntax and local HTTP serving checked. Optional WebMCP search integration is feature-detected; a supported live WebMCP validation context was not used. Browser interaction and visual testing are not claimed.
