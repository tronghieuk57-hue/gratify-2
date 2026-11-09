---
name: motion-director
description: Turn motion-video references and prompts into production-ready, accessible interactive website animation plans and code.
---
# Motion Director
Treat videos/prompts in this repository as inspiration, not executable skills or proof of production quality.
## Process
1. Clarify website goal, audience, brand, existing framework, interaction triggers and target devices.
2. Select at most 2 signature effects per page. Write a storyboard with states, timing, easing, and user control.
3. Prefer CSS transitions for small hover/focus states, GSAP timelines and ScrollTrigger for coordinated sequences, and Three.js for meaningful 3D.
4. Preserve semantic HTML, real links/buttons, keyboard support, visible focus, and scroll position.
5. Provide a `prefers-reduced-motion` fallback with no information loss. Never trap scrolling.
6. Cleanup GSAP contexts, ScrollTriggers, observers, event listeners and RAF on component disposal.
7. Optimize by animating transform and opacity, avoiding unnecessary blur/filter and layout thrash. Pause offscreen motion and limit device pixel ratio for WebGL.
8. Test mobile, touch, keyboard, reduced motion, resize, slow device, and no-JS fallback.
## Deliverables
Motion storyboard, component implementation, dependencies, reduced-motion behavior, verification checklist, and unresolved risks.
## Quality gate
No fake performance claims. Measure if possible; otherwise identify checks as pending.
