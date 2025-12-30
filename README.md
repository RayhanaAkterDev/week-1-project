# week-1-project

An accessible landing page built using pure semantic HTML.  

Focuses on correct document structure, form elements, keyboard navigation, and accessibility best practices—without relying on CSS or JavaScript.

## What this project focuses on

- Using semantic HTML tags (`header`, `nav`, `main`, `section`, `article`, `footer`) instead of random `divs`
- Understanding when `div` is allowed (layout/grouping only, no meaning)
- Building a logical heading hierarchy (`h1` → `h2` → `h3`)
- Creating accessible **forms** with proper `label`, `fieldset`, and `legend`
- Writing useful `alt` text for **images** - (describe purpose, not appearance)
- Knowing when to use `figure` / `figcaption` - (only when the image needs extra explanation)
- Using `article` for **self-contained** content (*cards*, *blog posts*, *services*)
- Understanding that **“card”** is a visual concept, not an **HTML** tag
- Keeping the page fully keyboard navigable by default (no tabindex misuse)
- Using `target="_blank"` safely with `rel="noopener noreferrer"`
- Knowing when `ARIA` is NOT needed (*semantic HTML first, ARIA last)*
- Using `<aside>` only for related but secondary content
- Avoiding unnecessary **ARIA roles** when native **HTML** already provides meaning

## Accessibility reminders (quick memory notes)

- Semantic HTML = built-in accessibility
- `div` is not bad, misuse of `div` is bad
- Use `article` when content makes sense on its own
- Do NOT add `ARIA` if **HTML** already does the job
- One `h1` per page, not per section
- Images need `alt`, **decorative images can be empty alt**
- Use `figure` only if the **image needs explanation**
- Use `aria-label` only when **purpose is unclear**
- Use `aria-describedby` only when **helper text exists**
- Keyboard users should never get stuck
- Accessibility is about **meaning**, not appearance

## Tech used

- HTML5
- Semantic markup
- Accessibility best practices (WCAG-aligned basics)

## Live link

👉 **Netlify Live Link:** https://week-01-semantic-html5-mini-project.netlify.app/
