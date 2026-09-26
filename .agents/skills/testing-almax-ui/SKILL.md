---
name: testing-almax-ui
description: Run and visually test the static almaX diamond parameter UI and canvas views.
---

# Local setup
Open `index.html` with a `file://` URL in Chrome. No package install, build, local server, or authentication is required. OpenCV loads from docs.opencv.org for image tools; inspect browser console separately if those tools are in scope.

# View and input testing
- The app initially maximizes Crown View. Click its top-right Restore View button to reveal both canvases, then maximize Profile using the equivalent button in Profile.
- Use real range drags and capture screenshots while the mouse remains pressed to verify live updates.
- Range Home/End selects endpoints; arrow keys use the configured step.
- Window widths below 800 CSS pixels move the sidebar beneath the canvas. Scroll over the sidebar or use the page scrollbar: wheel gestures over canvas change diagram zoom.
- Reset Alignment restores a diagram accidentally zoomed or panned.
- In Overlay Offset, clicking Circle or Table arms one target; click it again to disarm. Armed Crown View drags move that shape instead of panning. The sidebar reset recenters the armed shape, or both when none is armed.
- For offset transform testing, first move both shapes differently, then wheel-zoom and Shift+wheel-rotate the diagram. Verify local offsets persist and new drags follow the pointer. Disarm before testing ordinary panning.
- Compare results and canvas labels with independently calculated values; do not treat DOM text as evidence of canvas rendering.

## Devin Secrets Needed
None for the local parameter UI.
