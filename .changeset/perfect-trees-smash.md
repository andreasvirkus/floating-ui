---
'@floating-ui/react': minor
---

chore: deprecate `inner` and `useInnerOffset`. This technique of aligning an inner element to the reference has poor performance with longer lists, doesn't fit with the middleware paradigm, doesn't work on touch, and has a better custom alternative using native `onScroll` that is encouraged instead.
