# Code review guidelines

This document is meant to be a guide to getting a review process started, and not as something to be rigidly followed. You have the flexibility to determine how each review should go.

- The goals of code review:
  - Improve code quality, correctness, understanding, security, performance, scalability, and maintainability
  - Remove as many bugs as possible at an early stage
  - Spread the knowledge of the project
  - Learn from each other
- Make sure any unit tests for the code run with no failures. That includes no breaking changes and no regressions.
- Every engineer needs to have their code reviewed by at least one other engineer, preferably two.
- Have an automated system for code linting, formatting, and syntax-checking in place so reviewers need not review these things; Let the automatic tools do them.
- Each reviewer should write any comments in the code review system, not elsewhere.
- Reviewer notes can include: comments on code that is good, code that was not as good, suggestions for improvement of that code, and any questions regarding design decisions, potential logical flaws, etc. Any code that was particularly inspiring should be shared with the team. Conversely, poor code should only be privately commented.
- Try to keep reviewed code under 400 lines of code (LOC). More than this, and it will be too much to do a good job of reviewing in a reasonable time frame.
- For longer reviews, reviewers should take a break after about 1 hour and do something else, then come back to the review later in the day. Often this results in a new perspective.
- Any code criticism should be directed at the code, not the one who wrote it; don't get personal.
- It's OK for a reviewer to not find anything and say "It looks good."
- In practice, engineers should review all their code before creating a pull request.

Tips:
- In Github, make use of the “Draft PR” feature. This allows an engineer to signal to others that this is a work in progress (WIP). This may help others give guidance before too much useless work is done.
