# Project: Mastering Codex

## Purpose
Build a one-page landing page for withfouad’s YouTube video **“Mastering Codex.”** Viewers arrive through a link shared at the end of the video. Make the page feel like a natural continuation of the video: focused, useful, and easy to navigate.

## Scope and implementation
- Deliver the entire site in one `index.html`, with inline CSS and JavaScript.
- Use plain HTML, CSS, and JavaScript. No frameworks, build steps, package dependencies, or component libraries.
- Keep the page usable when opened directly in a browser. Use relative paths for any approved local assets.
- Build mobile first, then enhance the layout for larger screens. Avoid horizontal scrolling and overly wide text.
- Use JavaScript only when it adds clear value; core content and navigation must work without it.

## Brand and visual direction
- Brand name: **withfouad**. Preserve this spelling and lowercase styling.
- Background: **#030303**. Text: **#FFFFFF**. Sole accent color: **#D10F0F**.
- Use red sparingly for the primary call to action and meaningful emphasis. Do not introduce other accent colors.
- Use **Inter Tight** for interface text, body copy, and primary headings; use **Instrument Serif** for selective editorial emphasis.
- Load these font families explicitly, with sensible sans-serif and serif fallbacks. Do not make content visibility depend on font loading.
- Aim for a confident, minimal editorial design: strong typography, generous spacing, clear hierarchy, and restrained decoration.
- Avoid generic card grids, excessive borders, gradients, glows, and gratuitous animation.

## Content and page structure
- Lead with “Mastering Codex,” the withfouad identity, and a short explanation of what viewers can do next.
- Favor one clear primary action. Add supporting sections only when they help viewers use the video’s material.
- Keep copy concise, direct, and welcoming. Assume visitors have just watched the video; avoid redundant introductory marketing.
- Do not invent video URLs, downloads, resources, testimonials, statistics, offers, or social links. Use provided information and identify missing destinations during handoff.
- Do not ship misleading buttons or links that appear functional but do nothing.

## Accessibility and interaction
- Use semantic landmarks, one `h1`, logical heading order, and descriptive links.
- Use real buttons for actions and anchors for navigation. Support keyboard operation and visible focus states.
- Maintain readable contrast; verify any red text or white-on-red controls before use. Never convey meaning through color alone.
- Provide comfortable touch targets, readable mobile text, and appropriate alternative text for meaningful images.
- Respect `prefers-reduced-motion`. Avoid autoplay media and distracting motion.

## Verification and handoff
- Check narrow mobile and wide desktop layouts, text wrapping, keyboard navigation, and every interactive element.
- Confirm the page has no horizontal overflow, broken assets, JavaScript errors, or dead links.
- Keep metadata accurate: a descriptive page title, description, and viewport declaration. Add sharing metadata only when real URLs and assets are available.
- Keep changes within the requested scope. Report what changed, what was checked, and any missing content or destinations.
