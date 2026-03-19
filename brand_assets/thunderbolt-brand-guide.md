**THUNDERBOLT SYSTEMS**

Brand Asset Guide

Design System, Colour Palette, Typography, Components & Usage Guidelines

_For Claude Code / Developer Reference_

March 2026 — v1.0

# **1\. Brand Overview**

Thunderbolt Systems is an AI consulting and automation firm specialising in custom AI agent systems for online coaches, course creators, and info-product sellers. The brand communicates technical authority, speed of execution, and tangible business results.

**Brand Personality**

- Direct and no-nonsense — we state what the system does and what it replaces

- Technically credible — we name the tools (GHL, ManyChat, Claude API) without being intimidating

- Results-focused — every claim ties to a measurable outcome (booked calls, recovered leads, hours saved)

- Modern and premium — dark, clean aesthetic signals cutting-edge technology

- Coach-first framing — the AI is infrastructure, the coach is the expert

**Brand Tagline**

**AI Systems That Sell For You.**

**Brand Keywords**

Automation · Intelligence · Systems · Speed · Precision · Scale · Infrastructure

# **2\. Logo**

The Thunderbolt Systems logo consists of a triple lightning bolt mark paired with the wordmark. The lightning bolts use navy blue (\#1B2A6E) as the primary colour with black outlines. The wordmark uses a bold, condensed sans-serif in black.

**Logo Variants**

**Primary (White Background):** Full-colour logo with navy blue bolts and black wordmark on white/light backgrounds.

**Reversed (Dark Background):** White wordmark with navy blue bolts on dark backgrounds. This is the primary variant for the website.

**Monochrome:** All-white version for use on coloured backgrounds or overlays.

**Logo Files**

**Word_logo.png:** Primary logo on white background

**Word.png:** Logo variant on dark background (dark mark, right-aligned bolt)

**Word_logo_2.png:** Logo variant on dark background (dark mark, left-aligned bolt)

**Clear Space & Minimum Size**

Maintain a clear space around the logo equal to the height of one lightning bolt on all sides. Minimum display width: 120px for digital, 30mm for print.

**Logo Don’ts**

- Never rotate, skew, or distort the logo

- Never change the colours of the lightning bolts independently

- Never place the full-colour logo on a busy or low-contrast background

- Never recreate the logo in a different font

# **3\. Colour Palette**

The colour system is designed for a dark-mode-first website experience, with high contrast and selective use of accent colours. The palette is split into three tiers: primary brand colours, surface/background colours, and semantic accent colours.

## **3.1 Primary Brand Colours**

| Swatch | Name              | Hex      | Role                | Usage                                  |
| :----- | :---------------- | :------- | :------------------ | :------------------------------------- |
|        | **Navy Blue**     | \#1B2A6E | Primary Brand       | Logo, headings on light BGs            |
|        | **Electric Blue** | \#3B82F6 | Primary Accent      | CTAs, links, interactive elements      |
|        | **Neon Blue**     | \#60A5FA | Accent Highlight    | Hover states, highlights, glow effects |
|        | **Pure White**    | \#FFFFFF | Primary Text (Dark) | Body text on dark backgrounds          |
|        | **Off White**     | \#E8E8ED | Secondary Text      | Secondary text on dark backgrounds     |

## **3.2 Surface & Background Colours**

| Swatch | Name             | Hex      | Role                 | Usage                               |
| :----- | :--------------- | :------- | :------------------- | :---------------------------------- |
|        | **Deep Black**   | \#0A0A0F | Background Primary   | Page background, hero sections      |
|        | **Dark Surface** | \#111118 | Background Secondary | Card backgrounds, elevated surfaces |
|        | **Charcoal**     | \#1A1A24 | Background Tertiary  | Borders, dividers, subtle depth     |
|        | **Border Dark**  | \#2A2A3A | Border Default       | Borders, separators, outlines       |
|        | **Mid Grey**     | \#555570 | Muted Text           | Muted text, disabled states         |
|        | **Soft Grey**    | \#8888A0 | Tertiary Text        | Captions, eyebrow text, labels      |

## **3.3 Semantic Accent Colours**

| Swatch | Name              | Hex      | Role             | Usage                             |
| :----- | :---------------- | :------- | :--------------- | :-------------------------------- |
|        | **Success Green** | \#34D399 | Success / Active | Status tags, positive indicators  |
|        | **Warning Amber** | \#FBBF24 | Warning          | Caution states, pending items     |
|        | **Error Red**     | \#EF4444 | Error / Danger   | Error states, destructive actions |
|        | **Purple**        | \#A78BFA | Code / Technical | Code snippets, tech references    |

**CSS Variables (for Claude Code)**

_Include these as CSS custom properties at the :root level:_

\--color-bg-primary: \#0A0A0F;

\--color-bg-secondary: \#111118;

\--color-bg-tertiary: \#1A1A24;

\--color-border: \#2A2A3A;

\--color-brand-navy: \#1B2A6E;

\--color-accent-blue: \#3B82F6;

\--color-accent-neon: \#60A5FA;

\--color-text-primary: \#FFFFFF;

\--color-text-secondary: \#E8E8ED;

\--color-text-muted: \#8888A0;

\--color-text-dim: \#555570;

\--color-success: \#34D399;

\--color-warning: \#FBBF24;

\--color-error: \#EF4444;

\--color-code: \#A78BFA;

# **4\. Typography**

The type system uses a distinctive display font for headlines paired with a clean geometric sans-serif for body text, and a monospace font for code and technical elements. This mirrors the BURN & CO. reference site’s approach of mixing a bold display face with clean supporting type.

## **4.1 Font Stack**

| Font               | Usage                                               | Fallback Stack | Weights       |
| :----------------- | :-------------------------------------------------- | :------------- | :------------ |
| **Space Grotesk**  | Hero headlines, section titles, display text        | sans-serif     | 700, 800      |
| **DM Sans**        | Body copy, navigation, UI labels, buttons           | sans-serif     | 400, 500, 700 |
| **JetBrains Mono** | Code snippets, technical text, data, eyebrow labels | monospace      | 400, 500      |

_Note: Space Grotesk was chosen because the BURN & CO. reference uses a similar geometric display face with strong uppercase presence. If a more unique option is preferred, consider alternatives like Satoshi, General Sans, or Clash Display from Fontshare (all free for commercial use)._

## **4.2 Type Scale**

All sizes in rem (base 16px). Use these consistently across all pages.

**Display / Hero:** 4rem–5rem (64–80px) — Space Grotesk 800, uppercase, tight letter-spacing (-0.02em)

**H1 / Section Title:** 2.5rem–3rem (40–48px) — Space Grotesk 700, uppercase, letter-spacing (-0.01em)

**H2 / Subsection:** 1.5rem–2rem (24–32px) — DM Sans 700

**H3 / Card Title:** 1.25rem (20px) — DM Sans 700

**Body:** 1rem (16px) — DM Sans 400, line-height 1.7

**Small / Caption:** 0.875rem (14px) — DM Sans 400, colour: text-muted

**Eyebrow:** 0.75rem (12px) — JetBrains Mono 500, uppercase, letter-spacing 0.15em, colour: text-muted

**Code:** 0.875rem (14px) — JetBrains Mono 400

## **4.3 Google Fonts Import**

@import url('https://fonts.googleapis.com/css2?family=Space+Grotesk:wght@700;800\&family=DM+Sans:wght@400;500;700\&family=JetBrains+Mono:wght@400;500\&display=swap');

# **5\. Component Design System**

These specifications define how key UI components should be built, ensuring consistency with the BURN & CO. reference layout adapted to the Thunderbolt Systems brand.

## **5.1 Buttons**

**Primary CTA**

**Background:** \#3B82F6 (Electric Blue)

**Text:** \#FFFFFF, DM Sans 500, 14px, uppercase, letter-spacing 0.1em

**Padding:** 14px 32px

**Border radius:** 6px (slightly rounded, not pill-shaped)

**Hover:** Background shifts to \#60A5FA (Neon Blue), add subtle glow: box-shadow 0 0 20px rgba(59, 130, 246, 0.4)

**Arrow icon:** Include a → arrow after the text, with a subtle slide-right animation on hover

**Secondary / Ghost Button**

**Background:** transparent

**Border:** 1px solid \#2A2A3A

**Text:** \#E8E8ED, DM Sans 500

**Hover:** Border colour shifts to \#3B82F6, text colour shifts to \#3B82F6

## **5.2 Cards (Framework Section)**

**Background:** \#111118 (Dark Surface)

**Border:** 1px solid \#2A2A3A

**Border radius:** 12px

**Padding:** 32px

**Hover:** Border colour transitions to \#3B82F6 with 0.3s ease, subtle upward translate (-4px)

**Number:** JetBrains Mono 500, 12px, colour \#8888A0, with a /// prefix

**Title:** Space Grotesk 700, 20px, uppercase, colour \#FFFFFF

**Body:** DM Sans 400, 15px, colour \#8888A0, line-height 1.7

## **5.3 Service Rows (Operational Success Section)**

**Layout:** Horizontal row with number | title \+ subtitle | description | status tag

**Background:** Transparent, with a 1px bottom border in \#2A2A3A

**Number:** Space Grotesk 700, 24px, colour \#3B82F6

**Title:** DM Sans 700, 16px, colour \#FFFFFF

**Subtitle:** JetBrains Mono 400, 11px, colour \#555570, uppercase, letter-spacing 0.1em

**Description:** DM Sans 400, 14px, colour \#8888A0

**Status Tag:** JetBrains Mono 500, 11px, uppercase, padding 6px 12px, border-radius 4px, background varies per tag

**Status Tag Colours**

**CORE SYSTEM:** Background \#3B82F620, text \#3B82F6

**HIGH ROI:** Background \#34D39920, text \#34D399

**TIME SAVER:** Background \#FBBF2420, text \#FBBF24

**REVENUE ENGINE:** Background \#EF444420, text \#EF4444

**SCALE TOOL:** Background \#A78BFA20, text \#A78BFA

## **5.4 Scrolling Ticker Bar**

**Background:** \#3B82F6 (Electric Blue), full width

**Text:** \#FFFFFF, JetBrains Mono 500, 13px, uppercase, letter-spacing 0.15em

**Animation:** CSS infinite scroll, translateX(-50%) over 20s linear, duplicated content for seamless loop

**Separator:** /// between each item

## **5.5 Code Snippet Panel**

**Background:** \#0A0A0F (Deep Black) with 1px border \#2A2A3A

**Top bar:** Three coloured dots (red \#EF4444, yellow \#FBBF24, green \#34D399) to mimic a terminal window

**Font:** JetBrains Mono 400, 13px, colour \#E8E8ED

**Comment lines:** Colour \#555570

**Keywords:** Colour \#A78BFA (purple)

**Strings:** Colour \#34D399 (green)

**Functions:** Colour \#60A5FA (neon blue)

# **6\. Layout & Spacing**

## **6.1 Grid**

**Container max-width:** 1200px, centred

**Side padding:** 24px on mobile, 48px on tablet, 64px on desktop

**Column grid:** 12-column grid with 24px gutters

## **6.2 Section Spacing**

**Between major sections:** 120px–160px vertical padding

**Between subsections:** 64px–80px

**Between heading and content:** 24px–32px

**Between body paragraphs:** 16px

## **6.3 Responsive Breakpoints**

**Mobile:** \< 640px — single column, stacked cards

**Tablet:** 640px–1024px — 2-column grid for cards

**Desktop:** \> 1024px — full 3-column framework, side-by-side hero

# **7\. Animations & Effects**

The site should feel alive and technical without being distracting. All animations should be smooth and purposeful.

**Page Load**

- Hero headline: stagger fade-up, each word appearing 0.1s apart

- Subheadline and CTA: fade-up with 0.3s delay after headline completes

- Ticker bar: begins scrolling immediately

**Scroll Animations**

- Section headlines: fade-up when entering viewport (IntersectionObserver, threshold 0.2)

- Cards: stagger fade-up, 0.15s delay between each card

- Service rows: slide in from left, 0.1s stagger

**Hover Effects**

- CTAs: background colour shift \+ glow shadow \+ arrow slide-right

- Cards: border colour transition \+ subtle translateY(-4px)

- Service rows: subtle background lighten to \#111118

**Background Effects**

- Hero section: subtle gradient mesh or grid pattern overlay at 5–10% opacity

- Code snippet: subtle scanline effect or pulsing cursor animation

- Overall: no particle effects or 3D — keep it clean and fast-loading

# **8\. Claude Code Implementation Notes**

This section contains specific instructions for when this guide is used as a reference alongside Claude Code to build the website.

**Tech Stack Recommendation**

- Framework: Next.js 14+ (App Router) or plain HTML/CSS/JS if simpler

- Styling: Tailwind CSS with custom theme config matching the colour variables in Section 3

- Animations: Framer Motion for React, or CSS animations for static builds

- Fonts: Google Fonts (see import string in Section 4.3)

- Hosting: Vercel (if Next.js) or Netlify

**File Structure Suggestion**

/src

/components

    Hero.tsx

    TickerBar.tsx

    ProblemSection.tsx

    Framework.tsx

    Services.tsx

    CTA.tsx

    Footer.tsx

/styles

    globals.css (CSS variables from Section 3\)

/assets

    logo-white.png

    logo-dark.png

**Key Development Notes**

- The website is a single-page scrolling site (no routing needed beyond the home page)

- All sections should be accessible via smooth scroll from navigation

- The CTA button should link to a Calendly or GHL booking page (URL to be provided)

- Mobile-first responsive design is critical — most coach/creator audiences browse on mobile

- Page load speed matters: lazy-load images, minimise JS bundle, use system font fallbacks until Google Fonts load

- The code snippet in the problem section is decorative — it doesn’t need to be syntactically valid, just visually compelling
