ARVEN EN
Web Builder Prompt Pack
7 Templates for Rapid Frontend Development
$19

Build stunning web interfaces. Fast.

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

WHAT'S INSIDE

7 production-ready templates for HTML, CSS, React, Vue, and Svelte.
Each template handles a complete workflow: design → code → optimization.
Works with any UI framework or vanilla JavaScript.

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

TEMPLATE #1 — COMPONENT ARCHITECTURE

USE THIS when starting a new web project.

PROMPT:
"Design the component architecture for this web app: [DESCRIBE APP]

Provide:

1) Component hierarchy (parent-child relationships)
2) Component list (name, purpose, props/inputs, outputs)
3) State management strategy (where does state live)
4) Reusable vs page-specific components
5) Folder structure for components
6) Props validation/TypeScript interfaces

Framework: [React/Vue/Svelte/Vanilla]

Example: Button (reusable) vs LoginForm (page-specific)"

ARVEN TIP: Good architecture = easy to modify. Bad architecture = spaghetti code.

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

TEMPLATE #2 — RESPONSIVE DESIGN

USE THIS for mobile-first development.

PROMPT:
"Create responsive CSS layout for: [DESCRIBE LAYOUT]

Requirements:

1) Mobile first (320px breakpoint)
2) Tablet layout (768px)
3) Desktop layout (1024px)
4) Flexbox or Grid (specify which)
5) Touch-friendly spacing (48px min buttons)
6) Font scaling (readable on all sizes)

Constraints: [No external frameworks / Use Tailwind / Use Bootstrap / etc]

Provide:
- CSS with media queries
- Visual description of each breakpoint
- Accessibility considerations"

ARVEN TIP: 60% of web traffic is mobile. Design for phones first.

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

TEMPLATE #3 — FORM VALIDATION

USE THIS for any form (login, signup, checkout).

PROMPT:
"Build form validation for: [DESCRIBE FORM FIELDS]

Include:

1) Client-side validation (email format, required fields, min length)
2) Server-side validation (prevent tampering)
3) Error messages (clear, helpful, not technical)
4) Disabled state (button disabled until valid)
5) Loading state (feedback while submitting)
6) Success state (confirmation after submit)

Fields: [
  name (required, 2-50 chars),
  email (required, valid email),
  password (required, min 8 chars, uppercase + number)
]

Framework: [React Hook Form / Formik / Vue Composition / Vanilla]"

ARVEN TIP: Bad form validation = frustrated users. Good validation = happy users.

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

TEMPLATE #4 — STATE MANAGEMENT

USE THIS when components need to share data.

PROMPT:
"Design state management for: [DESCRIBE APP]

Decide:

1) Global state (Redux/Zustand/Context/Pinia)
2) Local state (useState in React)
3) Server state (data from API)
4) UI state (modals open/closed, loading flags)

Provide:

- State structure (what data, where it lives)
- Actions/mutations (how data changes)
- Selectors (how components access data)
- Data flow diagram (user action → state update → UI rerender)

Example: User logs in → set user in global state → all components see isLoggedIn=true"

ARVEN TIP: Confusing state = bugs. Clear state = predictable behavior.

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

TEMPLATE #5 — PERFORMANCE OPTIMIZATION

USE THIS when pages load slow.

PROMPT:
"Optimize performance for this web app:

1) Code splitting (split JS by route)
2) Image optimization (responsive images, WebP, lazy loading)
3) CSS optimization (remove unused styles, minify)
4) Bundle analysis (what's taking up space)
5) Caching strategy (browser cache, service worker)
6) Metrics tracking (what to measure: FCP, LCP, CLS)

Current: [Load time, bundle size, Lighthouse score]

Target: [What you want to achieve]

Provide:
- Optimization checklist
- Tools to use (Webpack, Vite, ImageOptim, etc)
- Expected improvement"

ARVEN TIP: Every 100ms of load time = 1% drop in conversions. Speed matters.

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

TEMPLATE #6 — ACCESSIBILITY (a11y)

USE THIS so everyone can use your site.

PROMPT:
"Make this web app accessible:

1) Keyboard navigation (Tab, Enter, Escape work)
2) Screen reader support (semantic HTML, ARIA labels)
3) Color contrast (text readable for colorblind users)
4) Focus indicators (visible focus outline)
5) Form labels (every input has a label)
6) Alt text (images have descriptions)

Provide:
- HTML changes (semantic tags, ARIA)
- CSS changes (focus states, contrast)
- Testing checklist (how to verify accessibility)

Current code: [PASTE CODE]"

ARVEN TIP: 1 in 4 people have a disability. Accessibility = not optional.

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

TEMPLATE #7 — ANIMATION & INTERACTION

USE THIS for delightful user experiences.

PROMPT:
"Design animations for: [DESCRIBE INTERACTION]

Include:

1) Entrance animations (fade in, slide in, scale up)
2) Interaction feedback (button click = visual response)
3) Loading states (spinner, skeleton screens, progress bars)
4) Transitions (smooth element changes)
5) Timing (duration, easing function)
6) Performance (GPU acceleration, no jank)

Framework: [CSS Animations / Framer Motion / Vue Transitions / Vanilla JS]

Interactions:
- Button click: scale 0.95 → 1 in 200ms (ease-out)
- Page load: fade in over 300ms
- Loading: spinner rotates, pulsing opacity"

ARVEN TIP: 300ms feels instant. 3000ms feels broken. Timing is everything.

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

SUMMARY: WHEN TO USE EACH TEMPLATE

Starting new project        → Template #1 (Architecture)
Need mobile design         → Template #2 (Responsive)
Building login/forms       → Template #3 (Validation)
Sharing data between pages → Template #4 (State)
App is slow               → Template #5 (Performance)
Need accessible UI        → Template #6 (Accessibility)
Want smooth animations    → Template #7 (Animations)

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

KEY PRINCIPLES

✓ Mobile-first approach
✓ Accessible by default
✓ Performance-conscious
✓ Works with any framework
✓ Production-tested patterns
✓ Copy-paste ready

ARVEN AI Agency • arvend.io • Good Just Happens
