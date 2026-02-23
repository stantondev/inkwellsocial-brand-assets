# Inkwell Brand & Style Guide

**Version 1.0 — February 2026**
Maintained at: [github.com/stantondev/inkwellsocial-brand-assets](https://github.com/stantondev/inkwellsocial-brand-assets)

---

## Table of Contents

1. [Brand Foundation](#1-brand-foundation)
2. [Logo System](#2-logo-system)
3. [Color Palette](#3-color-palette)
4. [Typography](#4-typography)
5. [Voice & Tone](#5-voice--tone)
6. [Iconography](#6-iconography)
7. [UI Patterns & Components](#7-ui-patterns--components)
8. [Photography & Imagery](#8-photography--imagery)
9. [Don'ts & Common Mistakes](#9-donts--common-mistakes)
10. [Implementation Reference](#10-implementation-reference)

---

## 1. Brand Foundation

### What Inkwell Is

Inkwell is a federated social journaling platform. LiveJournal's intimacy. Early MySpace's creativity. Rebuilt on open standards for 2026. No ads, no algorithm, no surveillance.

It is a place where people write — not to build audiences or optimize engagement, but because they have something to say and people they trust to say it to.

### Mission

To give writers a home on the internet that belongs to them.

### Values

**Independence** — No algorithmic feeds. No ad tech. User-owned data. Built on ActivityPub so the network outlives any single company.

**Craft** — Writing deserves a beautiful tool. Every interaction should feel intentional, not optimized.

**Intimacy** — Pen pals, not followers. Small worlds, not mass audiences. Connection over reach.

**Openness** — Open source code. Open standards. Community-driven roadmap. Nothing hidden.

### Positioning

> "LiveJournal meets Substack, rebuilt on open standards for 2026."

Inkwell is not a social network. It is not a blogging platform. It is not a microblogging app. It is a journaling platform that is also social — the distinction matters and should always be preserved in how we talk about the product.

### Brand Personality

Five adjectives, in order of weight:

| Adjective | What it means in practice |
|---|---|
| **Literary** | The design and language feel at home in a bookstore or library |
| **Principled** | Clear values, not vague mission statements — we say no to specific things |
| **Intimate** | Small scale, human scale — this is not a broadcast medium |
| **Crafted** | Every detail is considered; nothing feels placeholder or generic |
| **Independent** | Anti-corporate, anti-algorithm, proud to be small and weird |

### Taglines

**Primary:**
> "Your journal. Your pen pals. Your space."

**Secondary / Supplementary:**
> "No ads, ever."
> "Built in the open."
> "Write for yourself. Share with the people you trust."

### What Inkwell Is Not

Use this list to prevent brand dilution. Inkwell is:

- **Not a social network.** There are no follower counts on profiles. No engagement metrics.
- **Not a content farm.** The goal is not "more content." The goal is better writing.
- **Not a metrics game.** No likes, no retweets, no share counts. Stamps are reactions, not scores.
- **Not a platform for everyone.** This is for people who value writing and don't want algorithmic amplification.

### Target Audience

**Primary**: Writers who journal. People who used LiveJournal, Deadjournal, Dreamwidth, or early Tumblr and have never found a worthy successor.

**Secondary**: Indie web advocates. ActivityPub enthusiasts. Anyone who believes the internet should be human-scale.

**Tertiary**: Substack writers who want a more social, federated, non-commercial alternative.

---

## 2. Logo System

> The full logo creation guide with step-by-step instructions is in `logo-creation-guide.md`.

### Concept

The primary Inkwell mark is a **fountain pen writing "Inkwell" in cursive calligraphy**. The act of writing is the logo. The pen nib is the standalone icon.

This communicates what Inkwell is about in a single image: craft, handwriting, the analog sensibility brought into the digital age.

### Marks

| Mark | Use |
|---|---|
| **Primary logo** | Fountain pen nib + "Inkwell" cursive wordmark (horizontal layout) |
| **Wordmark only** | "Inkwell" in cursive — for contexts where the nib is implied |
| **Icon / App mark** | Fountain pen nib in isolation — favicon, app icons, avatars, small contexts |

### Wordmark Style

- Font: Custom or hand-lettered based on "Great Vibes" (modern calligraphy) as the starting reference
- Case: Capitalized "Inkwell" — not all-caps, not all-lowercase
- Color: Ink Midnight (`#1a2744`) on light backgrounds; white on dark backgrounds
- The nib and the start of the "I" should share a visual connection — the nib appears to be in the act of writing the word

### Color Variations

| Variation | When to Use |
|---|---|
| **Full color** (`#1a2744` on cream) | Default — marketing, website, print |
| **White knockout** | Dark backgrounds, photos, dark mode contexts |
| **Black** | High-contrast print, single-color reproduction |
| **Ink Midnight only** | Digital contexts requiring one color |

### Clear Space

The minimum clear space around the logo on all sides equals the height of the lowercase "k" in the wordmark. Never crowd the logo.

### Minimum Sizes

| Context | Minimum Size |
|---|---|
| Full logo (nib + wordmark) | 120px wide |
| Wordmark alone | 80px wide |
| Icon / nib mark | 24px wide |

### Logo Don'ts

- Do not stretch or distort the proportions
- Do not rotate the logo (the nib mark has a deliberate 45° angle built in)
- Do not add drop shadows, glows, or effects
- Do not recolor to anything outside the approved variations
- Do not use on a busy photographic background without a clear shield/container
- Do not lock the logo up with other logos without adequate clear space
- Do not recreate the wordmark in a different font — the calligraphy is the mark

---

## 3. Color Palette

### Philosophy

Inkwell's colors are grounded in the physical world of writing: the deep navy-black of fresh fountain pen ink, the warm cream of quality paper, the warm gray of aged leather. The palette is deliberately **not "tech."** No bright SaaS blues or startup greens.

The shift to ink blue from purple was intentional: the color IS the product. We are an ink company.

### Primary Brand Colors

| Name | Hex | CSS Variable | Use |
|---|---|---|---|
| **Ink Midnight** | `#1a2744` | `--ink-midnight` | Logo, headings, primary CTAs, brand anchor |
| **Ink Deep** | `#2d4a8a` | `--ink-deep` | Accent, links, active states, interactive elements |
| **Ink Bright** | `#3b5ea6` | `--ink-bright` | Hover states, highlights, secondary buttons |
| **Ink Light** | `#e8eef7` | `--ink-light` | Subtle tinted backgrounds, accent surfaces |

**Accessibility note**: Ink Midnight (`#1a2744`) on Cream (`#fafaf9`) has a contrast ratio of ~14:1 — far exceeds WCAG AA and AAA. Ink Deep (`#2d4a8a`) on cream is ~7:1 — passes AAA.

### Neutral Palette

These are warm neutrals — never cold gray. They evoke paper, aged text, and natural materials.

| Name | Hex | CSS Variable | Use |
|---|---|---|---|
| **Cream** | `#fafaf9` | `--background` | Page background |
| **White** | `#ffffff` | `--surface` | Cards, modals, elevated surfaces |
| **Off-white** | `#f5f5f4` | `--surface-hover` | Hover states on cards |
| **Foreground** | `#1c1917` | `--foreground` | Primary text — not pure black, warm near-black |
| **Ink text** | `#292524` | `--ink` | Body prose text (slightly warmer than foreground) |
| **Muted** | `#78716c` | `--muted` | Secondary text, captions, placeholders |
| **Border** | `#e7e5e4` | `--border` | Subtle dividers, card borders |
| **Border strong** | `#d6d3d1` | `--border-strong` | More visible dividers, table lines |

### Semantic Colors

| Name | Hex | CSS Variable | Use |
|---|---|---|---|
| **Success** | `#16a34a` | `--success` | Confirmations, positive states |
| **Warning** | `#d97706` | `--warning` | Cautions, pending states |
| **Danger** | `#dc2626` | `--danger` | Errors, destructive actions |

### Dark Mode

Dark mode uses warm dark tones — not cold charcoal. Think aged paper in low candlelight.

| Light Mode Value | Dark Mode Value | Variable |
|---|---|---|
| `#fafaf9` (cream) | `#0c0a09` (near-black, warm) | `--background` |
| `#ffffff` (white) | `#1c1917` (dark warm brown) | `--surface` |
| `#f5f5f4` | `#292524` | `--surface-hover` |
| `#1c1917` (near-black) | `#e7e5e4` (light) | `--foreground` |
| `#78716c` | `#a8a29e` | `--muted` |
| `#e7e5e4` | `#292524` | `--border` |
| `#2d4a8a` (ink deep) | `#93b4f0` (lighter blue) | `--accent` |
| `#e8eef7` (ink light) | `#1a2744` (ink midnight) | `--accent-light` |
| `#1a2744` (ink midnight) | `#c4d8f8` (very light blue) | `--accent-dark` |

### Color Don'ts

- Never use pure black (`#000000`) for text — use `--foreground` (`#1c1917`)
- Never use pure white (`#ffffff`) for backgrounds — use `--background` (`#fafaf9`)
- Never use `#7c3aed` (the old purple) in new brand contexts — it has been retired
- Do not add transparency/opacity to the ink brand colors; use the palette as defined
- Do not use the semantic colors (success/warning/danger) as brand or decorative colors

### The 8 Profile Themes

Users can customize their profiles with 8 built-in themes. These are **product features, not brand colors** — they are intentionally expressive and do not need to align with the core brand palette. They exist to give users creative control.

| Theme | Accent | Spirit |
|---|---|---|
| Default | Ink Deep blue | The Inkwell brand |
| Cottagecore | `#8b6f47` warm brown | Botanical, earthy |
| Vaporwave | `#ff71ce` hot pink | Retro 80s, neon |
| Dark Academia | `#c4a265` gold | Moody libraries |
| Retro Web | `#ff00ff` magenta | GeoCities nostalgia |
| Midnight | `#6366f1` indigo | Deep dark cool |
| Pastel Dream | `#e879a8` rose | Soft rainbow |
| Ocean | `#2ec4b6` teal | Deep sea |

---

## 4. Typography

### Philosophy

Type is the product. Inkwell is about writing, so the typography must be excellent. We use two typefaces only: a humanist serif for display and headings, and system sans-serif for UI. Nothing else.

### Typefaces

#### Lora — Display & Headings
- Source: [Google Fonts — Lora](https://fonts.google.com/specimen/Lora)
- Weights: 400 (Regular), 600 (SemiBold), 700 (Bold)
- Character: Literary, humanist, warm. Designed for screen readability with ink-inspired details.
- Use for: Page titles, section headings, entry prose headings, logo wordmark pairing, pull quotes, marketing headlines
- CSS: `font-family: "Lora", Georgia, serif;` / `var(--font-lora, Georgia, serif)`

#### System Sans-Serif — UI & Body
- Stack: `system-ui, -apple-system, "Segoe UI", Inter, sans-serif`
- Weights: 400 (Regular), 500 (Medium), 600 (SemiBold)
- Character: Clean, neutral, fast-loading. Renders as the platform's best native font.
- Use for: Navigation, buttons, labels, form fields, captions, metadata, settings UI
- CSS: `font-family: system-ui, -apple-system, sans-serif;`

#### Cascadia Code — Monospace
- Stack: `"Cascadia Code", "Source Code Pro", Menlo, Consolas, monospace`
- Use for: Code blocks in entries, technical documentation — never for UI

### Type Scale

| Level | Size | Weight | Font | Use |
|---|---|---|---|---|
| **Display XL** | 3.5–6rem | 700 | Lora | Landing page hero |
| **Display** | 2–3rem | 700 | Lora | Page titles |
| **H1** | 1.875rem | 600 | Lora | Section titles |
| **H2** | 1.5rem | 600 | Lora | Sub-sections |
| **H3** | 1.25rem | 600 | Lora | Within-section heads |
| **Body prose** | 1.125rem | 400 | Lora | Entry content |
| **Body UI** | 1rem | 400 | System sans | General UI text |
| **Small / Caption** | 0.875rem | 400 | System sans | Timestamps, metadata |
| **Label / Tag** | 0.75rem | 500 | System sans, uppercase | Tags, badges, labels |

### Line Heights (Leading)

| Context | Line Height | Rationale |
|---|---|---|
| Prose / entries | 1.85 | Generous — reading long-form needs room to breathe |
| Headings | 1.25–1.3 | Tight — display type pairs better close |
| UI / navigation | 1.5–1.6 | Comfortable for interaction targets |
| Labels / tags | 1.25 | Dense but readable at small sizes |

### Typography Rules

1. **Left-align body text** — never center-align paragraphs. Center is reserved for hero headlines and marketing callouts only.
2. **Never use more than two typefaces** in a single layout — Lora + system sans is the limit.
3. **Maximum line length**: ~70–75 characters for prose (use `max-w-2xl` or `max-w-prose`). Long lines destroy readability.
4. **Heading hierarchy matters** — never skip levels (H1 → H3 without H2 in between).
5. **Italic Lora for pull quotes** — use sparingly, max once per page.

---

## 5. Voice & Tone

### Core Voice Attributes

**Honest.** We say what we mean. We don't hide limitations. We don't spin bad news.

**Direct.** Short sentences. Active voice. No corporate hedging. If we can say it in 10 words, we don't use 20.

**Literary.** We are not afraid of a good sentence. The brand sounds like it was written by someone who reads. But not pretentious — accessible literary.

**Warm, not cheerful.** There is a difference. Warm is genuine. Cheerful is performed. Inkwell is for people who keep journals — they don't want to be greeted with exclamation points.

### Writing Style

| Do | Don't |
|---|---|
| "Your journal" | "Your content" |
| "Pen pals" | "Followers" or "connections" |
| "Writers" or "journalers" | "Users" or "creators" |
| "No algorithm" | "Organic reach" |
| "Built in the open" | "Transparent by design" |
| "Start writing" | "Get started!" |
| "Something went wrong." | "Oops! That didn't work 😅" |
| "Sign out" | "Log out" |
| Short, declarative: "No ads. Ever." | "We are committed to an ad-free experience" |

### Voice by Context

**Marketing / landing page**: Manifesto-style. Short declarative sentences. Speak in second person. State what we are and what we're not.

> "Your journal. Your pen pals. Your space. No algorithm. No ads. Built on open standards so the network belongs to everyone."

**Onboarding**: Warm and clear. Minimal steps. Don't over-explain. Trust the user to figure things out.

> "What's your username? Pick something you'll be comfortable sharing."

**Error messages**: Plain. Specific where possible. No humor in errors — people are frustrated.

> "Couldn't save your entry. Check your connection and try again."

**Empty states**: Orienting, not cute. Give people a clear next step.

> "Nothing here yet. Your feed grows as you follow pen pals."

**Notifications / confirmations**: Brief and unambiguous.

> "Entry published." (not "Your entry has been successfully published to your journal!")

### What We Never Write

- Exclamation points in error messages or neutral states
- Phrases like "Oops!", "Uh oh!", "Whoops!"
- Corporate buzzwords: leverage, synergy, ecosystem, stakeholders, optimize, empower
- Fake urgency: "Don't miss out!", "Limited time!", "Act now!"
- Passive voice on CTAs: "Submit" → "Save" or "Publish" or "Post"

---

## 6. Iconography

### Style Guidelines

Inkwell icons should feel like they could be drawn with a fountain pen — organic, humanist, slightly imperfect.

- **Stroke weight**: 1.5px, rounded caps and joins
- **Style**: Outline/line icons as default; filled only for active/selected states
- **Corner radius**: Slightly rounded — not sharp geometric, not fully circular
- **Optical sizing**: Icons should be designed at 24px and scaled down. At 16px, simplify shapes.

### Size System

| Size | Use |
|---|---|
| 16px | Inline with text, dense UI (tables, lists) |
| 20px | Standard navigation and action icons |
| 24px | Feature icons, primary actions |
| 48px | Empty state illustrations, onboarding |
| 96px+ | Marketing illustrations, feature callouts |

### The Stamp System

The 7 stamp types are Inkwell's signature iconography. They are product icons, not UI icons — designed to feel like actual postage stamps:

| Stamp | Meaning |
|---|---|
| `felt` | This resonated with me emotionally |
| `holding_space` | I'm here with you |
| `beautifully_said` | The writing itself moved me |
| `rooting` | I'm cheering for you |
| `throwback` | This took me back |
| `i_cannot` | This is too relatable / funny |
| `supporter` | Plus subscriber exclusive — highest show of appreciation |

Stamps render with `mix-blend-mode: multiply` at 75% opacity to simulate ink on paper. This is intentional — preserve it.

### Icon Sourcing

When sourcing or creating new icons:
- Start with [Lucide](https://lucide.dev/) — closest match to our humanist line style
- Heroicons (outline variant) as second choice
- Custom SVGs should follow the same 1.5px stroke / rounded cap spec
- Avoid: Material Design icons (too geometric), Feather (too thin), Font Awesome (too corporate)

---

## 7. UI Patterns & Components

### Cards & Surfaces

The foundational card pattern:

```
Background:   var(--surface)     → #ffffff
Border:       1px solid var(--border) → #e7e5e4
Border-radius: 12px (rounded-xl)
Padding:      16px–24px (p-4 to p-6)
Hover state:  background var(--surface-hover) → #f5f5f4
```

Cards never use drop shadows — borders and subtle backgrounds create depth without shadows, which feel too "material" for Inkwell's flat-paper aesthetic.

### Buttons

| Type | Background | Text | Border |
|---|---|---|---|
| **Primary** | `var(--ink-midnight)` `#1a2744` | White | None |
| **Secondary** | Transparent | `var(--foreground)` | `1px var(--border)` |
| **Danger** | `var(--danger)` `#dc2626` | White | None |
| **Ghost** | Transparent | `var(--muted)` | None |

- Shape: `border-radius: 9999px` (pill / fully rounded)
- Padding: `12px 20px` (py-3 px-5)
- Font: System sans, 14px, 500 weight
- Transition: 150ms ease on background and color

### Form Fields

```
Background:    var(--surface)
Border:        1px solid var(--border)
Border-radius: 8px (rounded-lg)
Focus ring:    2px var(--ink-deep) with 2px offset
Placeholder:   var(--muted) color
```

### Journal Pages (Feed UI)

The page-turning feed is a signature Inkwell experience. Key parameters:

- Paper texture: CSS SVG noise filter overlay
- Page shadow: `box-shadow` suggesting physical book edge
- Spine divider: 1px `var(--border)` line between left/right pages on desktop
- Corner marks: Decorative L-shape marks in bottom-right corner of each page
- Single page on mobile, two-page spread on desktop

### Spacing

Base unit: 4px (1 = 4px, 2 = 8px, 4 = 16px, 6 = 24px, etc.)

Prefer: generous whitespace. The content should breathe. Dense UIs signal algorithmic pressure — Inkwell should feel spacious.

### Animation

- Duration: 150–300ms
- Easing: `ease`, `ease-in-out` — never linear for UI feedback
- `prefers-reduced-motion` must always be respected — all decorative animations should respect this media query
- Entrance animations (journal pages): use Framer Motion with `initial → animate` — fallback to instant on reduced motion
- Never animate content shifts that change layout (CLS)

### Focus States

Focus rings must always be visible — never `outline: none` without a replacement.

- Default: `outline: 2px solid var(--ink-deep); outline-offset: 2px`
- On dark backgrounds: `outline: 2px solid var(--ink-bright)`

---

## 8. Photography & Imagery

### Photography Style

Inkwell's visual world is **analog and tactile**. Photography should feel like it belongs in an indie bookstore or a stationery brand catalog.

**Do use:**
- Close-ups of paper, handwriting, ink, notebooks, quills and fountain pens
- Bookshelves, libraries, reading nooks
- Natural materials: wood, leather, paper, fabric
- Soft, natural lighting — warm tones, slight overexposure
- Texture: paper grain, ink bleed, linen

**Don't use:**
- Stock photo people at computers
- Generic coffee-and-laptop flatlay
- Bright neon or digital glitch aesthetics
- Stark, cold photography (cool-tone "tech" look)
- Overhead "product on white" style

### Illustrations

When using illustration:
- Flat but with subtle texture — not pure vector/Dribbble aesthetic
- Slightly imperfect line quality — suggests a human drew it
- Paper grain overlay on illustration surfaces where appropriate
- Color palette should draw from the Inkwell brand palette, not introduce new hues

### Profile Theme Previews

When showcasing the 8 profile themes (marketing, onboarding, etc.), show them as color swatch grids — don't try to show screenshots of full profiles as brand imagery. The themes are a user feature, not a brand statement.

---

## 9. Don'ts & Common Mistakes

### Color

- **Don't** use `#7c3aed` (old purple) in any new design work — it has been retired from the brand
- **Don't** use pure `#000000` black — always use `#1c1917` (warm near-black)
- **Don't** use pure `#ffffff` white for page backgrounds — use `#fafaf9` (cream)
- **Don't** add gradients to the logo or to the primary brand mark
- **Don't** use the semantic colors (danger red, warning amber) as decorative accents

### Typography

- **Don't** introduce a third typeface — Lora + system sans is the complete stack
- **Don't** center-align body paragraphs
- **Don't** use all-caps for headings in running text (only in labels/tags)
- **Don't** set body prose at less than 1rem or with less than 1.6 line-height

### Logo

- **Don't** use `inkwell` (all lowercase) as the wordmark — it is "Inkwell" (capitalized)
- **Don't** recreate the wordmark in a different font — the calligraphy IS the mark
- **Don't** place the logo on backgrounds where it won't have sufficient contrast
- **Don't** add the logo to every page section — it appears in nav and footer only

### Voice

- **Don't** call writers "users" or "creators"
- **Don't** use exclamation points in error states or neutral UI
- **Don't** use passive voice in CTAs
- **Don't** describe engagement in metric terms ("reach", "impressions", "engagement rate")

### UI

- **Don't** remove visible focus rings — ever
- **Don't** use `box-shadow` for card depth (we use borders)
- **Don't** center-align button icons without text (use icon + label where possible)
- **Don't** use `overflow: hidden` on elements that contain popups — use `FloatingPopup` portal instead

---

## 10. Implementation Reference

This section is for developers building Inkwell features.

### CSS Variables (globals.css)

```css
/* Brand colors — light mode */
--ink-midnight: #1a2744;
--ink-deep: #2d4a8a;
--ink-bright: #3b5ea6;
--ink-light: #e8eef7;

/* Neutrals */
--background: #fafaf9;
--surface: #ffffff;
--surface-hover: #f5f5f4;
--foreground: #1c1917;
--ink: #292524;
--muted: #78716c;
--border: #e7e5e4;
--border-strong: #d6d3d1;

/* Semantic */
--success: #16a34a;
--warning: #d97706;
--danger: #dc2626;

/* Typography */
--serif: "Lora", Georgia, serif;
```

### Key Component Files

| File | What it does |
|---|---|
| `apps/web/src/app/globals.css` | All CSS custom properties, dark mode, prose styles |
| `apps/web/src/lib/profile-themes.ts` | 8 theme presets (product feature, not brand) |
| `apps/web/src/lib/profile-styles.ts` | `buildProfileStyles()` — resolves theme + user overrides |
| `apps/web/src/components/nav.tsx` | Logo SVG and nav layout |
| `apps/web/src/components/footer.tsx` | Footer with brand links |
| `apps/web/src/components/stamp-config.tsx` | Stamp type definitions and icons |
| `apps/web/src/components/floating-popup.tsx` | Portal-based popup (required for all dropdowns) |

### Popups

Any dropdown, tooltip, or popup that appears inside a feed entry card MUST use the `FloatingPopup` component. The journal feed uses `overflow: hidden` on `.journal-page` and `overflow-x: auto` on `.journal-scroll`, which clips absolutely-positioned children. `FloatingPopup` uses `createPortal` to render at `document.body` instead.

### API Calls from Client Components

All `"use client"` components must call same-origin Next.js proxy routes at `apps/web/src/app/api/...` — never call `api.inkwell.social` directly. The two domains are different origins and CORS will block direct calls.

### Profile Theme CSS Variables

`buildProfileStyles()` in `apps/web/src/lib/profile-styles.ts` resolves a user's theme + custom overrides into CSS custom properties set on the profile wrapper div. This is what makes all descendant elements (including `.prose-entry`) inherit theme-appropriate colors. Without this, prose text would use the site default and become invisible on dark themes.

---

## Revision History

| Version | Date | Changes |
|---|---|---|
| 1.0 | February 2026 | Initial brand style guide. Retiring purple accent, introducing ink blue palette. |

---

*Inkwell Brand & Style Guide is maintained by Stanton Melvin. Questions: [hello@inkwell.social](mailto:hello@inkwell.social)*
