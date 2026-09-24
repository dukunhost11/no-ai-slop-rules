# COMPONENTS

Reuse existing components whenever possible.

**Before creating a new component:**
1. Search the existing project.
2. Determine whether an existing component can be reused.
3. Extend the existing component if appropriate.
4. Only create a new component when necessary.

**Avoid:**
- card nesting
- unnecessary wrappers
- duplicate components
- duplicate styles
- unnecessary abstraction

Every component should have a clear purpose.

## Border Radius
Avoid excessive rounded UI. Do not make everything `border-radius: 9999px`.

Use radius according to component purpose:
- **small controls:** 8–12px
- **cards:** 14–20px
- **large surfaces:** 20–28px
- **pills:** only when semantically appropriate
