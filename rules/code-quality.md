# CODE QUALITY

The AI must:
- inspect the project before coding
- reuse existing code
- avoid unnecessary files
- avoid unnecessary dependencies
- avoid unnecessary rewrites
- avoid modifying unrelated files
- keep code maintainable
- keep components reusable
- follow the project's existing architecture

Do not rewrite working code simply to make it look different.
Do not install a dependency when native functionality or an existing dependency is sufficient.

## Design Decision System
When choosing between:
- more effects vs fewer effects -> choose fewer.
- more components vs fewer components -> choose fewer.
- more colors vs fewer colors -> choose fewer.
- more animations vs subtle animation -> choose subtle animation.
- more decoration vs stronger typography -> choose stronger typography.
- more abstraction vs simpler implementation -> choose simpler implementation.

## Self Review
Before completing a task, the AI must review its output and check:
- Did I add unnecessary gradients/shadows/glass?
- Did I use too many colors/fonts/rounded cards?
- Did I create unnecessary components/files/dependencies?
- Does the UI look generic/AI-generated?
- Is typography strong, spacing consistent, hierarchy obvious, and accessible?

If visual slop exists: REMOVE IT. Fix typography, spacing, hierarchy, composition, or color instead of adding decoration.
