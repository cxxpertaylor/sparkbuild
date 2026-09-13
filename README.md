# Sparkbuild — First Three Screens

A three-screen interactive concept for finding real-world SaaS project ideas. The visual direction is dark mode with yellow spark accents. The dominant landing action is **Find your passion project**.

## Need, persona, capability, and value

- **Need:** Aspiring software engineers struggle to find good ideas for personal, resume-building projects, so they spend their limited coding time searching through generic idea lists or building projects they are not excited about.
- **Persona:** Aspiring beginner software engineers with a limited portfolio and limited free time to spend on personal projects for their resume and personal growth.
- **Capability:** Find a real-world, well-defined SaaS project idea that matches their interests, skill level, and available time.
- **Fundamental value:** Direction. The developer quickly finds something impactful to build without wasting time thinking of ideas or settling for a generic project.

## Screens

1. **Landing:** Introduces the marketplace and communicates direction with one primary Find your passion project action. It earns its place by establishing purpose and value. Design question: Can a visitor quickly understand what the product does, how it helps, and what to click next?
2. **Browse ideas:** Groups project descriptions, categories, difficulty, and time estimates in filterable cards. It earns its place by demonstrating discovery and comparison. Design question: Do cards and filters help developers quickly identify a suitable idea?
3. **Idea details:** Shows the problem, intended users, first-version scope, skills, time, and contributor, with a save action. It earns its place by providing enough detail to choose a project. Design question: Does the screen provide enough information for a developer to confidently choose the project?

## Prototype scope

Six fictional sample ideas and contributors; no accounts, payment processing, or backend. Search and filters work together. Saving lasts for the current page session. All screens link home. Estimated effort is illustrative.

## Meaningful homepage revision

During review, the owner found the initial home screen distracting because it contained too much text in different sizes and fonts. The featured project, supporting paragraphs, and heading competed for attention.

On the `simplify-homepage` branch, the revision centers the motto “You have the skills. All you need is a spark.” and a single prominent “Find your passion project” button. The featured project and secondary hero copy are removed. Three numbered steps—Choose a real problem, Build it, Add it to your resume—are connected by a line, using connectedness and continuity to communicate an ordered process. Consistent type and proximity group the motto and primary action.

Design question: Does a simpler visual hierarchy make the primary action and intended payoff clearer at first glance? The expected improvement is a more obvious starting point and less competing information; this has not yet been tested with target users.

Before: [initial home screen source](https://github.com/cxxpertaylor/sparkbuild/blob/2ea4e2bf796fc040b24f3664b83772d36347aae6/dist/app.js). After: the revised home screen on this branch. The original commit remains unchanged for comparison.

## Assignment work still to complete

- Review the homepage revision and merge its branch through a pull request.
- Feedback questions and predictions covering need, value, persona, and capability.
- First-read evaluation, design justification, and a concrete before-and-after comparison.
- Public GitHub repository and public live URL for the final submission.

The initial AI output is preserved in the first commit. The owner's design review is recorded above; no target-user feedback findings are claimed.

## Running locally

Serve the `dist` folder with any static HTTP server. No dependency installation or build step is required. Navigation uses URL hashes so the three screens work on static hosting.

## Validation notes

JavaScript syntax and local HTTP serving checked. Optional WebMCP search integration is feature-detected; a supported live WebMCP validation context was not used. Browser interaction and visual testing are not claimed.
