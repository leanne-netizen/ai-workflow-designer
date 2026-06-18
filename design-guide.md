# Leanne Summers — AI Workflow Designer
## Website Design Guide
*For designer briefing, brand consistency, and site builder implementation*

---

## 1. Project Overview

**Site name:** Leanne Summers — AI Workflow Designer
**Pages:** Home, About, Contact
**Purpose:** Position Leanne as a trusted, done-for-you AI workflow builder for solo business owners. Convert visitors into enquiries via a low-pressure contact form.
**Audience:** Solo business owners who are competent, busy, and ready to stop managing their tools manually.

---

## 2. Brand Identity

### Logo

**Monogram mark**
- "LS" initials inside a thin-stroke circle
- Style: Classic, elegant, editorial
- Use on: Favicon, mobile nav, small-format placements
- Never distort, recolour outside approved palette, or add effects

**Wordmark**
- "Leanne" — bold weight, lowercase, serif
- "Summers" — medium/regular weight, title case, same serif
- Descriptor — "AI Workflow Designer" — light weight, lowercase or small caps, sans-serif
- Relationship: Monogram mark sits left of wordmark in horizontal layout; mark sits above wordmark in stacked layout

**Logo colour usage**
- On white/light backgrounds: #272525 (near-black)
- On dark/teal backgrounds: White (#FFFFFF)
- On coral backgrounds: White (#FFFFFF) only
- Never use mid-grey or colour versions for the logo mark itself

**Clear space**
- Minimum clear space around the logo = height of the "L" in the monogram on all sides
- Never crowd with other elements

---

## 3. Colour System

### Primary Palette

| Name | Hex | Use |
|---|---|---|
| Ink | #272525 | Primary headings, logo, nav text |
| Charcoal | #404040 | Body text, secondary headings |
| Mid Grey | #8C8C8C | Supporting text, captions, labels, metadata |
| Silver | #A6A8AA | Borders, dividers, placeholder text |
| Fog | #D0D1D3 | Subtle backgrounds, section breaks, input borders |
| White | #FFFFFF | Primary page background, card backgrounds |

### Accent Palette

| Name | Hex | Use |
|---|---|---|
| Coral | #FE7061 | Primary CTA buttons, key highlights, links on hover, pull quotes |
| Teal | #03A6A6 | Secondary accent, active states, inline links, tech-forward moments |

### Colour Rules

- **Page backgrounds:** Always white or Fog (#D0D1D3) — never dark
- **Primary CTA:** Always Coral (#FE7061) with white text
- **Secondary CTA / ghost button:** Ink (#272525) border + text, transparent background
- **Links:** Teal (#03A6A6) underline; Coral (#FE7061) on hover
- **Section dividers:** Fog or a thin 1px Silver (#A6A8AA) rule
- **Teal section backgrounds:** Use sparingly — one section per page maximum
- **Never** use Coral and Teal in the same component (they compete)

---

## 4. Typography

### Typeface Selection

**Heading font:** Playfair Display (Google Fonts — free)
- Matches the character of the logo serif
- Use for: H1, H2, pull quotes, hero text
- Weight: 700 (Bold) for H1; 600 (SemiBold) for H2/H3

**Body font:** Source Sans Pro (Google Fonts — free)
- Clean, legible, and classically proportioned — complements Playfair Display's elegance without competing
- Use for: Body copy, labels, navigation, form fields, captions
- Weight: 400 (Regular) for body; 600 (SemiBold) for subheadings, nav, and button labels

### Type Scale

| Element | Font | Size (desktop) | Size (mobile) | Weight | Line Height |
|---|---|---|---|---|---|
| H1 Hero | Playfair Display | 56px | 36px | 700 | 1.15 |
| H2 Section | Playfair Display | 38px | 28px | 600 | 1.2 |
| H3 Card/sub | Playfair Display | 26px | 22px | 600 | 1.3 |
| Body large | Source Sans Pro | 18px | 17px | 400 | 1.7 |
| Body standard | Source Sans Pro | 16px | 15px | 400 | 1.65 |
| Label / eyebrow | Source Sans Pro | 12px | 12px | 600 | 1.5 |
| Button | Source Sans Pro | 15px | 15px | 600 | 1 |
| Caption | Source Sans Pro | 13px | 13px | 400 | 1.5 |

### Typography Rules

- Eyebrow labels (section identifiers above headings): ALL CAPS, Source Sans Pro 600, #8C8C8C, letter-spacing: 0.12em
- Never use Playfair Display for body copy — it's decorative only
- Italic: Use Playfair Display italic for pull quotes and testimonial text only
- Heading colour: Always #272525 unless on a dark/teal background (then white)
- Body colour: #404040 on white; white on dark backgrounds
- Max line length: 680px / ~70 characters for body copy — never full-width

---

## 5. Layout & Grid

### Grid System

- **Max content width:** 1200px
- **Gutter:** 24px (mobile), 40px (tablet), 60px (desktop)
- **Columns:** 12-column grid; most content sits in 8 of 12 columns, centred
- **Narrow content width:** 720px — use for body copy, about text, single-column sections

### Spacing Scale

| Token | Value | Use |
|---|---|---|
| XS | 8px | Icon gaps, tight label spacing |
| S | 16px | Component internal padding |
| M | 32px | Between elements within a section |
| L | 64px | Between sections (mobile: 48px) |
| XL | 96px | Major section breaks (mobile: 64px) |
| XXL | 128px | Hero padding (mobile: 80px) |

### Section Rhythm

Every section follows this pattern:
1. Eyebrow label (optional)
2. Heading (H2 or H3)
3. Body text or component
4. CTA or link (optional)

Sections alternate between: white background → Fog background → white → Teal accent (one only)

---

## 6. UI Components

### Buttons

**Primary (CTA)**
- Background: #FE7061 (Coral)
- Text: #FFFFFF, Source Sans Pro 600, 15px
- Padding: 14px 32px
- Border radius: 4px
- Hover: darken 8% (#E55A4A)
- No shadow, no gradient

**Secondary (Ghost)**
- Background: transparent
- Border: 2px solid #272525
- Text: #272525, Source Sans Pro 600, 15px
- Padding: 12px 30px
- Border radius: 4px
- Hover: background #272525, text white

**Text link**
- Colour: #03A6A6 (Teal)
- Style: underline
- Hover: #FE7061 (Coral)
- No button chrome

### Navigation

- Background: White, full-width, 1px bottom border in #D0D1D3
- Logo: Left-aligned
- Nav links: Right-aligned, Source Sans Pro 600, 15px, #272525
- Active link: Coral (#FE7061) underline
- Mobile: Hamburger → full-screen overlay, links stacked
- Sticky on scroll: Yes — nav stays fixed at top

### Cards (Service Cards)

- Background: White
- Border: 1px solid #D0D1D3
- Border radius: 6px
- Padding: 32px
- Heading: H3, Playfair Display
- Body: Source Sans Pro 400, 16px
- Hover: border-color shifts to #03A6A6 (Teal), subtle box-shadow (0 4px 16px rgba(0,0,0,0.08))

### Pull Quotes / Testimonials

- Font: Playfair Display italic, 24px, #272525
- Left border: 3px solid #FE7061
- Padding-left: 24px
- Attribution: Source Sans Pro 400, 14px, #8C8C8C

### Dividers

- Thin rule: 1px, #D0D1D3, full section width
- Section accent: 40px wide, 3px tall, #FE7061, centred — use after H2 in hero and key sections

### Forms

- Input height: 48px
- Border: 1px solid #A6A8AA
- Border radius: 4px
- Focus border: #03A6A6 (Teal), 2px
- Placeholder text: #A6A8AA
- Label: Source Sans Pro 600, 14px, #404040, above the field
- Error state: Border #FE7061, error text below in Source Sans Pro 400 13px #FE7061
- Submit button: Primary CTA style

---

## 7. Imagery & Visual Style

### Photography Direction

- Style: Warm, real, slightly editorial — not stock, not staged
- Subject: Leanne in her actual workspace (laptop, natural light, Hoi An context welcome)
- Colour treatment: Natural tones that sit comfortably with the Coral/Teal palette — no heavy filters
- Mood: Calm confidence, not hustle. Morning light, not late-night grind.

### Illustrations / Icons

- Use line icons only — 1.5px stroke, #272525 or #03A6A6
- No filled/solid icons
- Icon size in UI: 20px × 20px; in feature sections: 32px × 32px

### Decorative Elements

- Thin horizontal rules in #FE7061 or #03A6A6 (3px height, 40px width) as accent marks
- Avoid: gradients, drop shadows on images, busy backgrounds, blob shapes
- Permitted texture: very subtle noise/grain on Teal section backgrounds only (opacity ≤ 5%)

---

## 8. Tone of Voice

*(Full brand voice guide exists as brand-voice.txt — this is the working summary)*

**Core identity:** Built by someone who actually uses this stuff. Not a developer — a working business owner who fixed her own days, then started fixing other people's.

**Voice character:** Honest without being self-deprecating. Warm without being performative. Capable without bragging.

**Five pillars:**
1. **Earned authority** — Lead with proof, not claims. "I've run this every morning for six months" beats "expert in AI."
2. **Specificity over enthusiasm** — Describe the moment, not the transformation. Concrete always wins.
3. **Dry wit, not jokes** — It's there quietly. Never performed. Never explained.
4. **Restraint as respect** — One clean point, then stop. Trust the reader.
5. **First-person as a bridge** — "Me, every morning. You, after we're done." Story serves the reader.

**Language to use:** sorted, handled, done, before, already, just, one, clear, no more
**Language to avoid:** transform, powerful, seamless, unlock, leverage, synergy, scalable, streamlined, robust, optimize

---

## 9. Page Structure & Copy Map

### HOME PAGE

**Section 1 — Hero**
- Layout: Full-width, white background, centred text, generous top padding (XXL)
- Eyebrow: "AI Workflow Designer" — Source Sans Pro 600, 12px, #8C8C8C, ALL CAPS, letter-spacing 0.12em
- H1: "Your day, sorted before your coffee goes cold." — Playfair Display 700, 56px
- Subhead: "I build AI-powered workflows that gather everything, surface what matters, suggest what's next — and then get out of the way." — Source Sans Pro 400, 20px, #404040, max-width 620px
- CTA: Primary button — "Tell me what's eating your mornings" → links to Contact
- Accent: 40px coral rule beneath the eyebrow

**Section 2 — Credibility / Story intro**
- Layout: White background, narrow content width (720px), centred
- Eyebrow: "Built by someone who actually uses this stuff."
- Body copy: From home-copy.txt — "I'm not a developer. I'm a solo business owner who got fed up starting every day from scratch..."
- End with the pull quote: *"All done, enjoy your day."* — pull quote component, coral left-border

**Section 3 — What I Build (Services)**
- Layout: White background, 3-column card grid (desktop), 1-column stack (mobile)
- Eyebrow: "What I build"
- H2: "The workflows that get your mornings back."
- Card 1: "Morning workflow systems" — icon + H3 + body
- Card 2: "AI + Notion databases" — icon + H3 + body
- Card 3: "Repetitive task automation" — icon + H3 + body
- (Copy from home-copy.txt — service descriptions)

**Section 4 — Social Proof / Quote**
- Layout: Fog (#D0D1D3) background, full-width, centred
- Pull quote: *"Before I've finished my coffee, my day is set up, my tasks are handled, and the system says — all done, enjoy your day."*
- Attribution: "Me, every morning. You, after we're done."
- Font: Playfair Display italic, 28px

**Section 5 — CTA Banner**
- Layout: Teal (#03A6A6) background, white text, centred, padding L top/bottom
- H2: "Tell me what's eating your mornings." — Playfair Display 600, white
- Body: "No pitch deck. No jargon. Just tell me what you do, what's repetitive and draining, and what you wish you could hand off." — Source Sans Pro 400, white, 70% opacity
- CTA button: Ghost button style (white border + white text)

---

### ABOUT PAGE

**Section 1 — Hero**
- Layout: White, narrow (720px), left-aligned text
- Eyebrow: "About"
- H1: "Built by someone who actually uses this stuff." — Playfair Display 700
- Optional: Hero photo of Leanne (natural light, workspace)

**Section 2 — Third-person intro block**
- Layout: Fog background, 720px, centred, generous padding
- Style: Slightly set-apart from main body — use a subtle left border in #D0D1D3
- Copy: "Leanne Summers builds AI-powered workflow systems for solo business owners who are done managing their tools and ready to trust them..."
- End with italic: *"Okay, that's enough of that."*

**Section 3 — The actual story**
- Layout: White, 720px, standard body copy
- H2: "Here's the actual story." — Playfair Display
- Body: Full story from about-copy.txt — "I run a wedding celebrant business in Vietnam..."
- Use section dividers (1px Fog rule) between the story, quality, and "why I do this" blocks

**Section 4 — Quality callout**
- Layout: White, 720px — but treat as a distinct block
- Optional: subtle left border accent in Coral
- Copy: "A word on quality..." section from about-copy.txt

**Section 5 — Who this is for**
- Layout: Fog background, 720px, centred
- H2: "Who this is for." — Playfair Display
- Body: "Solo business owners who are competent, busy, and slightly tired of being the person who holds everything in their head..."

**Section 6 — CTA**
- Same CTA banner as homepage

---

### CONTACT PAGE

**Section 1 — Header**
- Layout: White, narrow, centred
- H1: "Tell me what's eating your mornings." — Playfair Display 700
- Subhead: "No pitch deck. No jargon. Just tell me what you do, what's repetitive and draining, and what you wish you could hand off. We'll figure out if I can help." — Source Sans Pro 400, 20px, #404040

**Section 2 — Contact Form**
- Layout: White, max-width 560px, centred
- Fields:
  - Name (text input, full width)
  - Email (email input, full width)
  - "What do you do?" (text input, full width)
  - "What's eating your mornings?" (textarea, full width, min-height 140px)
  - "What would you love to hand off?" (textarea, full width, min-height 100px)
- Submit: Primary CTA button, full width — "Send it over"
- Below form: Source Sans Pro 14px, #8C8C8C — "I read every message personally and reply within 2 business days."

---

## 10. Site Builder Instructions

### Recommended Platforms (in order of preference)

1. **Webflow** — Best for design fidelity; all type/colour tokens can be set as global variables
2. **Framer** — Strong for animation; good CMS for future content
3. **Squarespace** — Easiest to maintain; some design constraints
4. **WordPress + Kadence or GeneratePress** — If more control/ownership needed

### Global Tokens to Set Up First

Before building any pages, configure these as global design tokens / style variables:

```
--color-ink: #272525
--color-charcoal: #404040
--color-mid-grey: #8C8C8C
--color-silver: #A6A8AA
--color-fog: #D0D1D3
--color-coral: #FE7061
--color-teal: #03A6A6
--color-white: #FFFFFF

--font-heading: 'Playfair Display', Georgia, serif
--font-body: 'Source Sans Pro', system-ui, sans-serif

--radius-sm: 4px
--radius-md: 6px

--max-width-content: 1200px
--max-width-body: 720px
--max-width-hero-sub: 620px
```

### Font Loading

Add to `<head>`:
```html
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Source+Sans+Pro:wght@400;600&family=Playfair+Display:ital,wght@0,600;0,700;1,400&display=swap" rel="stylesheet">
```

### SEO Essentials

- Page title: "Leanne Summers — AI Workflow Designer"
- Meta description (home): "I build AI-powered workflows for solo business owners who are ready to stop managing their tools and start trusting them. Based in Vietnam. Working everywhere."
- OG image: Logo on white background, or Leanne hero photo — 1200×630px
- Alt text: All images require descriptive alt text

### Mobile Behaviour

- Nav collapses to hamburger at 768px
- All 3-column card grids collapse to single column at 640px
- Hero H1 drops from 56px → 36px at 768px
- Section padding reduces from 96px → 64px at 768px
- All body text minimum 15px on mobile — never smaller

---

## 11. What Not To Do

- No drop shadows on images
- No gradient backgrounds
- No more than two accent colours in any single section
- No centred body copy blocks longer than 3 lines
- No button text in ALL CAPS
- No Lorem Ipsum — use actual copy from the provided files
- No stock photography of anonymous people at laptops
- No busy hero backgrounds — white or Fog only
- Never use both Coral and Teal in the same visual component

---

*Design guide created: April 2026*
*Brand source: theleannesummers.com + Leanne Summers Brand Guide*
*Copy source: home-copy.txt, about-copy.txt, brand-voice.txt*
