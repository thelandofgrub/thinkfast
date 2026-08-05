# thinkfast
an engaging browser-based choice-reaction trainer, brought to you by The Land of Grub, to improve cognitive processing speed.

See it. Hear it. Move.
Brought to you by The Land of Grub.

THINKFAST is a browser-based choice-reaction training application. It presents numbers 1–12 on a clock-style dial, displays or speaks a target number, and measures the time between cue activation and the user’s correct response. Five-round sessions combine speed, accuracy, consistency, progressive challenge, and personal history in one focused experience.
THINKFAST is a performance-practice tool, not a medical device, diagnostic test, or treatment.

Documentation
  •	Product and user guide — purpose, audience, complete feature reference, session instructions, metrics, research context, privacy, and troubleshooting.
  •	Technical reference — architecture, timing model, state flow, algorithms, data model, development, testing, and maintenance.
  •	Promotional toolkit — positioning, approved claims, descriptions, launch copy, social content, email copy, and press boilerplate.

Quick start
Requirements: Node.js 22.13 or newer.
  npm install
  npm run dev

Open the local URL shown in the terminal. Common project commands:
  npm run build
  npm test
  npm run lint
  npm start

Technology
  •	React 19 and TypeScript
  •	vinext/Vite application runtime
  •	Browser Speech Synthesis API for spoken cues
  •	performance.now() for in-browser response timing
  •	Browser localStorage for up to 30 completed-session records
  •	Responsive CSS with high-contrast, larger-target, and reduced-motion options

Project structure
  app/page.tsx          Core training experience and application logic
  app/globals.css       Brand, responsive layout, dial, feedback, and accessibility styles
  app/layout.tsx        Metadata, fonts, and application shell
  public/               Social image, favicon, and static assets
  tests/                Render/build verification
  docs/                 Product, technical, and promotional documentation

Research and measurement note
The age-reference panel is adapted from a published two-choice visual reaction-time study and is deliberately labeled approximate. THINKFAST is a different 12-target task, and browser, display, input device, audio, fatigue, attention, and environment can affect recorded times. Use the same device and input method when comparing personal sessions.

Brand
•	Product name: THINKFAST
•	Tagline: See it. Hear it. Move.
•	Attribution: Brought to you by The Land of Grub
•	Brand promise: focused, measurable practice for a faster and more consistent response process

