---
name: @dewebkiller
description: "GitHub profile skill from @dewebkiller. Use it when the task would benefit from mimicking this developer's repo choices, coding style, and implementation techniques."
---

## What they tend to build
- Mostly **frontend-heavy brochure sites** and **WordPress theme work**: static marketing pages, organization sites, landing pages, and child themes.
- Repeated structure: **shared header/footer**, page-specific templates, and lots of content pages named by slug (`about.php`, `faq.php`, `privacy-policy.php`, etc.).
- They also build **small UI components** like a Bootstrap mega menu, plus full site templates for brands/organizations.

## Coding patterns to mirror
- Prefer **simple, direct page composition** over abstraction unless the site is clearly repeating sections.
- Use **PHP includes** for common layout parts (`header.php`, `footer.php`, sidebar/components) and keep page files thin.
- Organize assets in familiar buckets: `css/`, `js/`, `images/`, with extra `sections/` or `components/` folders when templates need reuse.
- Lean on **Bootstrap 5 markup patterns** and class-based layout rather than custom framework code.
- Expect **animation and interaction libraries** to be wired in lightly: `animate.css`, `AOS`, `Swiper`, `Fancybox`, `Hover.css`.
- When styling, they seem comfortable with **plain CSS plus SCSS** and **CSS variables** rather than complex build systems.
- Keep naming practical and readable; many repos use **descriptive page filenames** and straightforward README copy.

## Product and UI taste
- The phrase “**clean and simple**” appears directly in their Bootstrap menu repo, and their projects reflect that: **clear layouts, easy navigation, content-first pages**.
- UI taste skews toward **classic business-site presentation** with motion used for polish, not novelty.
- Likely values:
  - strong header/navigation
  - structured content sections
  - subtle animation
  - common marketing-site widgets like sliders, galleries, accordions, and megamenus
- Expect **WordPress/theme-friendly design** that is easy for non-technical editors to maintain.

## Tech stack clues
- Strong signals for:
  - **HTML / CSS / JavaScript**
  - **PHP**
  - **WordPress**
  - **Bootstrap 5**
  - **SASS/SCSS**
  - **MySQL**
  - **React** appears in profile tools, but the repos shown are mostly traditional frontend/WordPress
- Design/tooling signals from the profile: **Figma, Framer, Illustrator, Photoshop, Sketch, InVision**.
- Repo evidence shows a practical static-site workflow:
  - `sass --watch scss:css`
  - lots of page-level PHP templates
  - minimal package complexity
  - library-driven enhancement over custom JS frameworks

## When to inspect repos first
- Before changing any **WordPress theme/child theme**, inspect how the repo handles `header.php`, `footer.php`, template parts, and asset loading.
- Before adding a new page to a static site, inspect:
  - existing **section/component patterns**
  - how navigation is assembled
  - naming conventions for slugs and templates
- Inspect first if the task involves:
  - Bootstrap layout changes
  - SCSS/CSS variable updates
  - animation behavior
  - reusable content blocks
  - site-wide header/footer or sidebar changes
- If the repo is large and page-heavy, mirror the existing pattern instead of introducing a new architecture.

## Repo Map

- [dewebkiller/bootstrapmenu](https://github.com/dewebkiller/bootstrapmenu): Clean and simple Bootstrap mega menu combined with animate.css (1 stars, CSS)
- [dewebkiller/lodbod](https://github.com/dewebkiller/lodbod): Lodbod is a digital logistics platform that connects shippers directly with vehicle owners and drivers. We make moving goods simple, transparent, and reliable for everyone. (0 stars, JavaScript)
- [dewebkiller/partyhtml](https://github.com/dewebkiller/partyhtml): Party depot HTML (0 stars, JavaScript)
- [dewebkiller/cofsun-nepal](https://github.com/dewebkiller/cofsun-nepal): The static website for the Cofsun Nepal (0 stars, PHP)
- [dewebkiller/dasgongbad](https://github.com/dewebkiller/dasgongbad): The theme for dasgongbad (0 stars, PHP)
- [dewebkiller/hello-academy-child](https://github.com/dewebkiller/hello-academy-child): The child theme for hello academy (0 stars, PHP)
- [dewebkiller/sg-fc0d96fa](https://github.com/dewebkiller/sg-fc0d96fa): smartsvn (0 stars)
- [dewebkiller/post-template](https://github.com/dewebkiller/post-template): Post template for post (0 stars, PHP)
- [dewebkiller/747lives](https://github.com/dewebkiller/747lives): WordPresss theme for 747lives (0 stars, PHP)
- [dewebkiller/accepted-payment-methods](https://github.com/dewebkiller/accepted-payment-methods): Show accepted payment methods in wordpress site (0 stars, PHP)
- [dewebkiller/axis-theme](https://github.com/dewebkiller/axis-theme): Axis infosys WP Theme (0 stars, PHP)
- [dewebkiller/dewebkiller](https://github.com/dewebkiller/dewebkiller): My personal repository (0 stars)

## How To Use This Skill

- Reach for this skill when the user asks for Niresh Shrestha's style, when the repo stack matches this person's ecosystem, or when studying their real code would reduce made-up output.
- Pick one or more relevant repositories from the list above based on the current task.
- Clone the most relevant repository or repositories into `/tmp` for temporary inspection.
- Study the implementation details, naming patterns, architecture, UI taste, and tooling choices there.
- Return to the main task and apply the useful patterns you observed instead of copying blindly.
- Treat the upstream repositories as reference material for style and technique, then adapt them to the current codebase responsibly.
