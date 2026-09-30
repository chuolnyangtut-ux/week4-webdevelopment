SpendWise Dashboard Shell
​This repository contains the solution for the Rebuild the Tracker's Layout with Flexbox and Grid assignment (End of Week 4).
​🌟 Overview & Features
​SpendWise is a responsive personal finance dashboard shell created with modern CSS layout techniques without relying on absolute positioning for layout structure.
​Key Highlights
​CSS Grid Page Architecture:
​Designed with grid-template-areas separating the dashboard into sidebar, header, and main layout sections.
​Flexbox Alignment:
​Flexbox is utilized internally within the Header, Navigation Sidebar, User Profile, and each individual Category Card for vertical and horizontal alignment.
​6 Detailed Financial Category Cards:
​Realistically structured cards showing spending limits, dollar totals, progress indicators, and status metrics (e.g., Food & Dining, Transportation, Housing & Rent, Entertainment, Savings, Utilities).
​CSS Custom Properties (:root):
​Brand Color (--color-brand), Accent Color (--color-accent), Surface Color (--color-surface), Primary/Secondary text variables.
​Micro-interactions & Animations:
​Subtle hover and keyboard focus states (:hover, :focus-within) on each card using transform: translateY(-4px) and box-shadow transition lasting 200ms (\le 250\text{ms}).
​Responsive Breakpoint (< 768px):
​Collapses gracefully into a single-column mobile view verified using DevTools.
​Dark Theme Stretch Goal:
​Full dark theme override utilizing @media (prefers-color-scheme: dark).
​📁 File Structure
​index.html — Semantic HTML structure containing sidebar nav, search header, and 6 financial cards.
​style.css — CSS stylesheet containing custom properties, CSS Grid layout, Flexbox components, responsive rules, and micro-interactions.
​README.md — Project summary and documentation.# week4-webdevelopment