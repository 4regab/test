Build a single-page portfolio site (vanilla HTML/CSS/JS) with the following requirements:

Structure: index.html, styles.css, app.js, /assets (icons/SVGs).
Visuals: immersive dark theme (suggested palette: #0b0f14, #0f1720, accent #7dd3fc or #9b7dff). Use a geometric sans-serif for headings and a neutral sans for body. Generous white-space, clear visual hierarchy, subtle glass/blur panels.
Background game: implemented in Canvas or WebGL-free JS. Options: interactive particle system, slow procedural starfield, or a simple playable mini-game (e.g., one-life Pong/snaker-lite) that runs quietly behind content. Must:
Be visually subtle and not hinder reading.
Auto-pause when user scrolls, focuses a form, or toggles the control.
Provide UI overlay: On/Off toggle, Mute, and Pause/Resume. Keep controls compact and accessible.
Animations: smooth, hardware-accelerated transforms; reduced-motion support via prefers-reduced-motion.
Accessibility: semantic HTML, keyboard navigable, ARIA where needed, color contrast WCAG AA.
Performance: lazy-load assets, keep JS minimal, target fast startup (Lighthouse checks).
Responsiveness: work across phone/tablet/desktop; mobile-first with breakpoints at 640px, 1024px.
Acceptances: passes keyboard navigation, background game toggles off, site readable with game off, no external heavy libs, and includes a README with run instructions.
Implementation-ready prompt (for an AI/code generator)
Generate a complete, runnable single-page portfolio project with these constraints:

Tech: plain HTML, CSS, and vanilla JS only. No frameworks. Only Google Fonts allowed (optional).
Files to produce: index.html, styles.css, app.js, README.md, and any small SVG icons in /assets.
Layout: hero with name + tagline, projects grid (3–6 projects), about section, contact footer. Use minimal copy placeholders.
Background game: a performant canvas-based particle / starfield with gentle interactivity (particles respond to pointer). Provide controls: toggle background, mute sounds, pause/resume. Game must be disabled by default on small screens (<640px).
UX polish: hover transitions, accessible focus styles, responsive UI, reduced-motion support.
Size constraints: avoid large images; inline small SVGs; total asset budget ~<200KB (excluding fonts).
Deliver unit smoke checks: site loads, background toggle works, keyboard navigation, and reduced-motion honored.
Provide short developer notes in README.md with run/test steps.
Suggested background-game options (pick one)
Particle playground: low-density attractor/repel system; particles gently move and react to pointer. No sound.
Starfield: parallax moving stars with depth; subtle glow; very low CPU.
Mini-game overlay (optional): small Snake or Pong that can be paused and moved to a modal; default background remains particle/starfield.
Minimal design tokens (copyable)
Background: #0b0f14
Surface: rgba(255,255,255,0.03)
Accent: #7dd3fc (or #9b7dff)
Text primary: #e6eef6
Radius: 12px
Transition: 200ms cubic-bezier(.2,.8,.2,1)
Acceptance criteria (concise)
Page is responsive and keyboard-accessible.
Background game runs smoothly on desktop, is off by default on mobile, and can be toggled/paused/muted.
Design reads as "polished/award-quality" (consistent spacing, micro-interactions).
No external heavy libraries; runs locally with just a static server or opening index.html.
