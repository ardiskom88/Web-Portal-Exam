---
name: ExamGuard
colors:
  surface: '#f8f9ff'
  surface-dim: '#cbdbf5'
  surface-bright: '#f8f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eff4ff'
  surface-container: '#e5eeff'
  surface-container-high: '#dce9ff'
  surface-container-highest: '#d3e4fe'
  on-surface: '#0b1c30'
  on-surface-variant: '#464555'
  inverse-surface: '#213145'
  inverse-on-surface: '#eaf1ff'
  outline: '#777587'
  outline-variant: '#c7c4d8'
  surface-tint: '#4d44e3'
  primary: '#3525cd'
  on-primary: '#ffffff'
  primary-container: '#4f46e5'
  on-primary-container: '#dad7ff'
  inverse-primary: '#c3c0ff'
  secondary: '#565e74'
  on-secondary: '#ffffff'
  secondary-container: '#dae2fd'
  on-secondary-container: '#5c647a'
  tertiary: '#005338'
  on-tertiary: '#ffffff'
  tertiary-container: '#006e4b'
  on-tertiary-container: '#67f4b7'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e2dfff'
  primary-fixed-dim: '#c3c0ff'
  on-primary-fixed: '#0f0069'
  on-primary-fixed-variant: '#3323cc'
  secondary-fixed: '#dae2fd'
  secondary-fixed-dim: '#bec6e0'
  on-secondary-fixed: '#131b2e'
  on-secondary-fixed-variant: '#3f465c'
  tertiary-fixed: '#6ffbbe'
  tertiary-fixed-dim: '#4edea3'
  on-tertiary-fixed: '#002113'
  on-tertiary-fixed-variant: '#005236'
  background: '#f8f9ff'
  on-background: '#0b1c30'
  surface-variant: '#d3e4fe'
typography:
  headline-xl:
    fontFamily: Plus Jakarta Sans
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-xl-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 30px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.005em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 24px
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 26px
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 22px
  body-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 18px
  label-lg:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
  code-mono:
    fontFamily: JetBrains Mono
    fontSize: 13px
    fontWeight: '500'
    lineHeight: 18px
    letterSpacing: 0.02em
  timer-display:
    fontFamily: JetBrains Mono
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 28px
    letterSpacing: -0.02em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 1rem
  margin: 2rem
  margin-mobile: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system establishes an environment of unwavering academic integrity, operational focus, and enterprise-grade reliability. Tailored for high-stakes online examinations, certification authorities, and institutional proctoring, the interface projects absolute authority while minimizing test-taker cognitive friction. 

The aesthetic is **Corporate / Modern** inflected with **Precision High-Trust SaaS**:
- **Clarity over novelty:** Every pixel reinforces focus, calm execution, and situational awareness. Distracting micro-interactions, decorative flourishes, and playful skeuomorphism are intentionally omitted.
- **Architectural firmness:** Dense, well-structured telemetry data, real-time proctoring indicators, and clear boundaries establish a controlled, tamper-resistant environment.
- **Immediate emotional grounding:** Test candidates encounter a calm, distraction-free environment that reduces exam anxiety; proctors and invigilators receive high-fidelity, high-contrast signals that allow rapid scanning and intervention.

## Colors

The palette leverages high-contrast functional color assignments to distinguish situational states instantly:

- **Primary (`#4F46E5` Indigo):** Applied to dominant active actions, selected states, verified checkpoints, and primary navigational waypoints. It signals secure verification and technical precision without inducing the stress associated with alert colors.
- **Secondary (`#0F172A` Deep Slate / Navy):** Serves as the structural anchor. Applied to dominant top bars, sidebar controls, primary headers, and deep-ground modal backdrops.
- **Functional Semantics:**
  - **Success Emerald (`#10B981`):** Applied to active camera streams, green-flagged biometric verifications, secure connection indicators, and successful answer submissions.
  - **Warning Amber (`#F59E0B`):** Denotes minor telemetry warnings (e.g., low network bandwidth, face tracking partially obscured, audio thresholds exceeded).
  - **Violation Crimson (`#EF4444`):** High-priority infractions requiring immediate intervention (e.g., multi-face detection, window defocus, secondary monitor detected, clipboard breach).
- **Background & Surfaces:** Light mode default with crisp `#FFFFFF` card layers elevated above a subdued `#F8FAFC` base background, framed with subtle `#E2E8F0` borders to avoid visual vibration during multi-hour testing sessions.

## Typography

The typographic hierarchy serves two distinct needs: high readability during sustained reading (exam questions, comprehension passages) and instantaneous recognition of real-time monitoring data.

- **Plus Jakarta Sans** is leveraged for section headings, modal titles, and assessment branding, offering modern geometric crispness with humanistic approachability.
- **Inter** handles all body content, instructions, long-form test prompts, and standard UI interactions due to its neutral optical characteristics and superior legibility at compact sizes.
- **JetBrains Mono** is introduced for critical numeric and state information: countdown timers, security hash codes, IP addresses, student identification keys, and proctor log timestamps. It guarantees fixed numeric widths, preventing layout jitter during real-time countdown updates.

## Layout & Spacing

The layout is built on a responsive 12-column fluid grid system pinned inside a max-width container of 1440px for assessment consoles, expanding to 100% edge-to-edge for multi-stream proctor monitoring desks.

- **Candidate Exam View:** Strict two-column operational layout. A responsive main column (8 cols) housing the question canvas, and a fixed contextual rail (4 cols) housing the live webcam feed, question navigation matrix, and remaining time telemetry.
- **Proctor Multi-Feed View:** Dynamic fluid CSS grid scaling from 1 to 4 columns depending on active viewport and density mode, maintaining 16:9 aspect ratios for candidate video streams.
- **Breakpoints:**
  - **Mobile (< 768px):** Rails fold into an off-canvas drawer or a sticky bottom action sheet; timers and security badges anchor to a condensed sticky top bar.
  - **Tablet (768px - 1024px):** Single primary work pane with expandable floating diagnostics.
  - **Desktop (> 1024px):** Full multi-pane telemetry and synchronous question panel active simultaneously.

## Elevation & Depth

This system utilizes **low-contrast outlines paired with controlled ambient shadows**, avoiding heavy skeuomorphism and opaque floating layers that create visual clutter during high-focus tasks:

- **Level 0 (Canvas Base):** Tinted neutral background (`#F8FAFC`). Flat, non-interactive.
- **Level 1 (Cards, Modules, Input Containers):** Pure `#FFFFFF` surface with a subtle `1px` border (`#E2E8F0`) and an ambient shadow: `0 1px 3px 0 rgba(15, 23, 42, 0.05)`.
- **Level 2 (Telemetry Overlays & Hover Cards):** Surface elevated with `0 4px 6px -1px rgba(15, 23, 42, 0.08), 0 2px 4px -2px rgba(15, 23, 42, 0.04)`.
- **Level 3 (Modals, Proctor Interventions, Urgent Dialogs):** High-priority containment surfaces layered over a 40% deep slate backdrop blur (`rgba(15, 23, 42, 0.6) backdrop-filter: blur(4px)`), with elevation shadow `0 20px 25px -5px rgba(15, 23, 42, 0.15)`.
- **Security Flag Hierarchy:** When a card or stream transitions to a warning or violation state, visual depth is reinforced through an inner border glow (e.g., `box-shadow: inset 0 0 0 1px #EF4444`) rather than intrusive volumetric drop-shadows.

## Shapes

The design system implements a **Soft** shape language (`roundedness: 1`):
- Standard interactive elements, inputs, and telemetry chips leverage `0.25rem` (4px) to `0.375rem` (6px) corners.
- Base cards, data tables, video viewports, and floating drawers utilize `0.5rem` (8px).
- Modals and large dialog containers employ a maximum radius of `0.75rem` (12px).

This restrained curvature preserves a disciplined, institutional cadence characteristic of government standards, academic certifying boards, and high-security enterprise tooling, discarding the overly casual, bubbly appearance of modern consumer software.

## Components

### Buttons
- **Primary:** `#4F46E5` background, white text, solid `0.375rem` radius. Subtle hover shift to `#4338CA`. Active state retains `0 0 0 3px rgba(79, 70, 229, 0.2)`.
- **Destructive / Flag:** `#EF4444` background with pure white text, reserved for terminating exams, revoking access, or submitting final violation reports.
- **Secondary / Ghost:** Transparent surface with a clean `1px` `#CBD5E1` border and `#1E293B` text. Never competes with the primary exam progression action.
- **Size Specs:** Explicit hit target of minimum `40px` height on desktop, scaling to `48px` on touch interfaces to prevent mis-clicks under exam stress.

### Status Badges & Chips
- Designed with micro-metrics in mind. Uses a structural pair: a subtle `6px` pulsating or solid status dot alongside concise JetBrains Mono / Inter text.
- **Active/Secure:** `#ECFDF5` background, `#047857` text, `#10B981` dot.
- **Warning:** `#FFFBEB` background, `#B45309` text, `#F59E0B` dot.
- **Critical Breach:** `#FEF2F2` background, `#B91C1C` text, `#EF4444` dot.

### Question Navigation Matrix
- Grid of compact numeric squares (36x36px).
- **Answered:** Solid `#4F46E5` with white text.
- **Flagged for Review:** `#FEF3C7` background with `#D97706` upper-right corner dog-ear badge.
- **Unvisited:** Crisp `#FFFFFF` background with `1px` `#E2E8F0` border.
- **Current Active:** `2px` solid `#0F172A` outline.

### Input Fields & Radio Choice Cards
- **Multiple Choice Options:** Full-width interactive surface cards instead of bare radio buttons. Selecting an answer transforms the entire container's border to `2px solid #4F46E5` and tints the background to `#EEF2FF`.
- **Text Inputs:** Pure white background, `1px solid #CBD5E1`, transitioning to `#4F46E5` border with an indigo focus ring on focus. Monospace formatting activated automatically for verification codes and access keys.

### Telemetry Cards & Video Viewports
- Compact webcam monitor framed in a solid `#0F172A` wrapper.
- Integrated overlay banners indicating real-time statuses (e.g., "AI Proctor Active", "Audio: Normal", "Gaze Tracked").
- Overlays must maintain an opaque or semi-translucent backdrop (`rgba(15, 23, 42, 0.75)`) to preserve high readability regardless of underlying camera lighting conditions.

### Alert Banners
- Full-width or inline banner cards with high-contrast left border accents (`4px` solid `#EF4444`, `#F59E0B`, or `#4F46E5`).
- Includes a dedicated action link (e.g., "Resolve Connection", "Acknowledge Warning") and an unambiguous description of the violation or system notice.