---
version: "2.0"
name: "UrbanNest Interiors — Soft Transition"
description: "A premium, editorial interior-design website combining a light sage canvas, architectural photography, spacious layouts, and subtle image-warp transitions. Designed to communicate trust, warmth, personalization, and refined residential living."

design_direction:
  style: "Editorial Minimalism / Organic Modern"
  mood: "Calm, refined, warm, contemporary, architectural"
  inspiration:
    - "Whitespace and visual balance"
    - "Subtle background warping between image panels"
    - "Smooth easing and controlled transitions"
    - "Architectural editorial photography"
  principles:
    - "Content and photography take priority over decoration."
    - "Use whitespace to establish hierarchy."
    - "Transitions should feel fluid rather than theatrical."
    - "Every section should guide visitors toward discovery or enquiry."
    - "Maintain a consistent visual rhythm across the entire website."

colors:
  primary: "#EAF6EE"
  secondary: "#344C3D"
  tertiary: "#A7BEAC"
  accent: "#6F8D74"
  neutral: "#FFFFFF"
  background: "#EAF6EE"
  surface: "#F5FAF6"
  surface-elevated: "#FFFFFF"
  text-primary: "#26372D"
  text-secondary: "#66766A"
  text-muted: "#849187"
  border: "#D5E4D8"
  border-strong: "#B6CDBB"
  button-primary: "#344C3D"
  button-primary-hover: "#26372D"
  button-primary-text: "#FFFFFF"
  button-secondary: "#FFFFFF"
  button-secondary-text: "#344C3D"
  image-overlay: "rgba(24, 39, 29, 0.18)"
  focus-ring: "#6F8D74"
  success: "#3F7550"
  warning: "#98733A"
  error: "#B94D4D"

typography:
  font-display:
    fontFamily: "Playfair Display"
    fontSize: "clamp(3rem, 6.5vw, 6.25rem)"
    fontWeight: 400
    lineHeight: 0.98
    letterSpacing: "-0.045em"

  heading-xl:
    fontFamily: "Playfair Display"
    fontSize: "clamp(2.5rem, 4.5vw, 4.5rem)"
    fontWeight: 400
    lineHeight: 1.08
    letterSpacing: "-0.035em"

  heading-lg:
    fontFamily: "Playfair Display"
    fontSize: "clamp(2rem, 3vw, 3.25rem)"
    fontWeight: 400
    lineHeight: 1.15
    letterSpacing: "-0.025em"

  heading-md:
    fontFamily: "Inter"
    fontSize: "1.25rem"
    fontWeight: 500
    lineHeight: 1.4
    letterSpacing: "-0.02em"

  body-lg:
    fontFamily: "Inter"
    fontSize: "1.125rem"
    fontWeight: 400
    lineHeight: 1.8

  body-md:
    fontFamily: "Inter"
    fontSize: "0.9375rem"
    fontWeight: 400
    lineHeight: 1.75

  label-md:
    fontFamily: "Inter"
    fontSize: "0.6875rem"
    fontWeight: 500
    lineHeight: 1.5
    letterSpacing: "0.16em"
    textTransform: "uppercase"

  navigation:
    fontFamily: "Inter"
    fontSize: "0.8125rem"
    fontWeight: 500
    lineHeight: 1.5

layout:
  type: "Responsive Editorial Grid"
  content-width: "1440px"
  wide-content-width: "1600px"
  page-gutter: "clamp(20px, 5vw, 80px)"
  section-padding: "clamp(64px, 9vw, 144px)"
  section-padding-compact: "clamp(40px, 5vw, 80px)"
  grid-columns: 12
  grid-gap: "clamp(16px, 2vw, 32px)"
  base-unit: "4px"

spacing:
  1: "4px"
  2: "8px"
  3: "12px"
  4: "16px"
  5: "20px"
  6: "24px"
  8: "32px"
  10: "40px"
  12: "48px"
  16: "64px"
  20: "80px"
  24: "96px"
  32: "128px"

rounded:
  sm: "4px"
  md: "8px"
  lg: "12px"
  xl: "20px"
  image: "4px"
  pill: "999px"

elevation:
  none: "none"
  subtle: "0 4px 24px rgba(38, 55, 45, 0.045)"
  medium: "0 12px 40px rgba(38, 55, 45, 0.08)"
  overlay: "0 16px 48px rgba(20, 35, 25, 0.16)"

components:
  navbar:
    background: "#EAF6EE"
    textColor: "#26372D"
    height: "88px"
    mobileHeight: "68px"
    position: "sticky"
    borderBottom: "1px solid rgba(52, 76, 61, 0.10)"

  button-primary:
    background: "{colors.button-primary}"
    textColor: "{colors.button-primary-text}"
    borderRadius: "{rounded.sm}"
    padding: "15px 24px"
    typography: "{typography.navigation}"
    transition: "background-color 200ms ease, transform 200ms ease"

  button-secondary:
    background: "{colors.button-secondary}"
    textColor: "{colors.button-secondary-text}"
    border: "1px solid {colors.border-strong}"
    borderRadius: "{rounded.sm}"
    padding: "15px 24px"

  button-text:
    background: "transparent"
    textColor: "{colors.text-primary}"
    borderBottom: "1px solid {colors.border-strong}"
    padding: "0 0 5px 0"

  card:
    background: "{colors.surface-elevated}"
    border: "1px solid {colors.border}"
    borderRadius: "{rounded.md}"
    padding: "24px"
    shadow: "{elevation.none}"

  image-card:
    background: "{colors.surface}"
    borderRadius: "{rounded.image}"
    overflow: "hidden"
    imageFit: "cover"
    imageTransition: "transform 700ms cubic-bezier(0.22, 1, 0.36, 1)"

  form-field:
    background: "#FFFFFF"
    border: "1px solid {colors.border}"
    borderRadius: "{rounded.sm}"
    padding: "14px 16px"
    focusBorder: "{colors.focus-ring}"

---

# UrbanNest Interiors — Design Specification

## 1. Design Overview

UrbanNest Interiors is a Hyderabad-based interior design and home
transformation brand.

The website should feel like a contemporary architecture and lifestyle
publication rather than a conventional contractor website.

The experience should communicate:

- Thoughtful residential and commercial design.
- A balance between aesthetics and functionality.
- Premium visual presentation without intimidating customers.
- A transparent and approachable design process.
- A clear path from browsing inspiration to booking a consultation.

### Visual identity

Use a soft sage-tinted canvas, forest-green typography, generous
whitespace, large architectural images, editorial typography, and
carefully controlled motion.

The visual language should be warm and tactile, with clean geometry
rather than excessive decoration.

### Core design rule

# Let the space breathe.

Avoid filling every section with cards, badges, borders, icons, or
animations. Use photography, typography, composition, and spacing
to establish the hierarchy.

---

## 2. Color System

### Primary canvas — #EAF6EE

The defining color of the new variation.

Use it for the main page background, navigation, spacious editorial
sections, and selected transition panels.

The background must remain visibly light. Do not reuse the original
dark interface as the default canvas.

### Supporting palette

| Role | Color | Usage |
|---|---|---|
| Primary canvas | #EAF6EE | Main background |
| Forest green | #344C3D | Primary buttons and emphasis |
| Deep forest | #26372D | Headings and high-contrast text |
| Sage | #A7BEAC | Supporting surfaces and accents |
| Muted green | #6F8D74 | Secondary actions and details |
| White | #FFFFFF | Cards, forms, image framing |
| Soft border | #D5E4D8 | Dividers and outlines |
| Secondary text | #66766A | Paragraphs and descriptions |
| Muted text | #849187 | Low-emphasis metadata |

### Color usage rules

- Use #EAF6EE as the primary background across the majority of
  the homepage.
- Use #344C3D for high-priority actions and selected text emphasis.
- Use #26372D for readable headings.
- Use white surfaces selectively to separate content groups.
- Use sage tones for subtle transitions and supporting details.
- Maintain accessible contrast for all text and controls.
- Do not use neon green, cyan, or the previous dark background palette.
- Avoid large decorative gradients that compete with photography.

### Optional background treatment

Use a restrained gradient only for image overlays or transition
panels:

`linear-gradient(135deg, #EAF6EE 0%, #DCECE0 100%)`

Keep the majority of the canvas flat and calm.

---

## 3. Typography

### Display typography

Use Playfair Display for large headlines, editorial statements,
and selected project titles.

Display headings should feel architectural and sophisticated,
with generous scale and carefully controlled line breaks.

Example:

"Designing Spaces
That Feel Like Home."

### Supporting typography

Use Inter for body copy, navigation, forms, buttons, captions,
and functional interface elements.

Use a small uppercase label above major section headings to create
an editorial rhythm.

Example:

`OUR APPROACH`

### Typography rules

- Use a clear hierarchy with no more than three font families.
- Keep body text comfortable to read on desktop and mobile.
- Limit hero text width to approximately 10–12 words per line.
- Avoid overly tight line heights for body paragraphs.
- Avoid using monospace typography as the dominant text style.
- Use italic display text sparingly for emphasis.
- Do not use oversized headings in every section.

---

## 4. Global Layout

### Grid system

Use a responsive 12-column editorial grid on desktop.

Use asymmetrical compositions where appropriate, but preserve
alignment between section headings, images, and content blocks.

The layout should feel structured without appearing rigid.

### Desktop

- Maximum content width: 1440px.
- Page gutters: approximately 5vw.
- Hero image: approximately 50–65% of the visible hero area.
- Use asymmetric image and text proportions.
- Alternate between full-width compositions and contained sections.
- Allow generous vertical whitespace between major sections.

### Tablet

- Reduce page gutters and heading sizes.
- Use two-column layouts where they remain comfortable.
- Allow project galleries to become two-column grids.
- Reduce decorative animation complexity when necessary.

### Mobile

- Use a single-column content flow.
- Keep navigation compact and accessible.
- Stack hero copy and photography.
- Preserve comfortable touch targets.
- Avoid horizontal overflow and clipped text.
- Reduce transition displacement and image distortion.
- Keep contact actions easy to reach.

### Spacing principle

Use the 4px base spacing scale.

Major section spacing should be substantially larger than spacing
between related text elements.

Do not compress sections simply to fit more content above the fold.

---

## 5. Navigation

### Structure

- UrbanNest Interiors logo.
- Home.
- Services.
- Projects.
- About Us.
- Contact.
- Primary action: Get a Quote.

### Behavior

The navigation should remain simple and unobtrusive.

Use a sticky header with the light sage background. A subtle
background opacity or border adjustment may be applied after
scrolling, provided text contrast remains strong.

Navigation links should transition through a restrained color
change and underline animation.

The quote button should use a solid forest-green background.

On mobile, use an accessible menu button and a compact navigation
panel. Close the panel after navigation.

Do not add excessive navigation items or animated decorative icons.

---

## 6. Homepage Structure

### Section 01 — Hero

Purpose: Establish the brand identity and encourage visitors to
explore the studio's work.

Content:

Eyebrow:
INTERIOR DESIGN STUDIO · HYDERABAD

Headline:
Designing Spaces That Feel Like Home.

Description:
Thoughtfully designed interiors that bring together comfort,
elegance, and everyday functionality.

Primary CTA:
Explore Our Projects

Secondary CTA:
Book a Consultation

Visual direction:

Use a large, high-quality photograph of a contemporary living
space with warm wood, natural materials, soft furnishings,
and daylight.

The hero should have an editorial composition, with text aligned
to one side and a dominant image on the other or beneath it.

Use a restrained entrance transition for the headline and image.

Avoid generic gradients, decorative dashboard panels, and
excessive floating UI elements.

### Section 02 — Studio Introduction

Eyebrow:
OUR PHILOSOPHY

Heading:
Spaces Designed Around You.

Describe UrbanNest's approach to combining personal taste,
functional planning, material selection, and practical execution.

Use a two-column layout with a short editorial paragraph and
an architectural image or material detail.

Keep the content concise and authentic.

### Section 03 — Services

Eyebrow:
WHAT WE DO

Heading:
Considered Design. Complete Solutions.

Feature four primary service categories:

1. Residential Interiors
2. Modular Kitchens
3. Office Interiors
4. Custom Furniture

Each service should include a photograph, a concise description,
and a simple text link.

Additional services can be introduced on the full services page:

- Space Planning
- Home Renovation
- 3D Design Visualization
- Smart Home Integration

Use image-led cards with minimal borders and restrained hover
movement.

Avoid turning the service section into a dense grid of boxed text.

### Section 04 — Featured Projects

Eyebrow:
SELECTED WORK

Heading:
Spaces With Their Own Story.

Display selected residential and commercial projects in an
asymmetric editorial gallery.

Recommended composition:

- One large featured project.
- Two smaller supporting projects.
- A clear project title and category for each image.
- A link to view the complete project.

Project details may include location, property type, design
approach, and materials used.

Use actual project photography where available. Do not present
stock photographs as completed client projects.

### Section 05 — Why UrbanNest

Eyebrow:
THE URBANNEST DIFFERENCE

Heading:
Beautiful by Design. Practical by Nature.

Communicate the brand's differentiators:

- Personalized design concepts.
- Budget-conscious premium interiors.
- Functional and modern layouts.
- Realistic 3D visualizations.
- End-to-end project coordination.
- Transparent project estimates.

Use a split composition with a large photograph and a structured
list of benefits.

Do not invent project counts, client ratings, awards, or delivery
statistics.

### Section 06 — Design Process

Eyebrow:
HOW WE WORK

Heading:
From First Conversation to Final Reveal.

Present four steps:

01 — Discover
Understand the client's lifestyle, needs, preferences, and budget.

02 — Design
Develop the layout, material palette, furniture concepts, and
3D visualizations.

03 — Execute
Coordinate procurement, furniture, and on-site execution.

04 — Deliver
Complete the agreed scope and hand over the finished space.

Use a clean horizontal timeline on desktop and a vertical timeline
on mobile.

Keep the numbers subtle and the descriptions concise.

### Section 07 — Pricing

Eyebrow:
PLANNING YOUR PROJECT

Heading:
A Clearer Starting Point.

Display indicative starting prices from the supplied business
information:

- 2BHK Interior Package — ₹3.5 Lakhs.
- Modular Kitchen — ₹1.2 Lakhs.
- Office Interior Setup — ₹5 Lakhs.
- Wardrobe Design — ₹65,000.

Explain that final costs depend on project dimensions, materials,
finishes, and scope.

Use minimal pricing cards with clear descriptions and a quote CTA.

Do not imply that every package includes the same materials,
furniture, appliances, or installation services.

### Section 08 — Testimonials

Eyebrow:
CLIENT EXPERIENCES

Heading:
Thoughtfully Designed. Personally Experienced.

Use genuine customer feedback only.

A testimonial can include a short quotation, the client's
approved name or initials, and the relevant project type.

If verified testimonials are not available, omit this section
or display an appropriately labelled placeholder during development.

Do not fabricate reviews or customer identities.

### Section 09 — Contact

Eyebrow:
LET'S BEGIN

Heading:
Tell Us About Your Space.

Include a simple enquiry form with:

- Full name.
- Phone number.
- Email address.
- Service required.
- Approximate budget.
- Project location.
- Project details.

Primary action:
Request a Consultation

Provide clear validation, loading, success, and error states.

The form must be connected to an actual submission service
before it is treated as operational.

### Section 10 — Footer

Include:

- UrbanNest Interiors logo.
- Brand tagline.
- Main navigation.
- Services.
- Hyderabad address.
- Business phone number.
- Website and verified social links.
- Copyright notice.

Use the forest-green color for the footer only if it creates a
clear visual ending to the light editorial page.

Keep the footer compact and organized.

---

## 7. Image Direction

### Photography style

Use authentic architectural and interior-design photography.

Preferred subjects:

- Contemporary living rooms.
- Modular kitchens.
- Warm minimalist bedrooms.
- Custom wardrobes.
- Refined office interiors.
- Natural materials and furniture details.
- Design consultation and material selection.

### Image treatment

- Prefer natural daylight and realistic materials.
- Use warm wood, stone, linen, ceramics, and subtle greenery.
- Maintain consistent color grading across the gallery.
- Use object-fit: cover for image containers.
- Preserve appropriate focal points on mobile.
- Avoid excessive saturation, artificial HDR, and strong filters.
- Do not apply heavy green overlays to every image.

### Image transitions

Images may scale very slightly on hover.

For large image changes, use a restrained distortion or warping
transition inspired by the referenced transition experiment.

The image itself should remain the main visual focus.

---

## 8. Motion and Interaction

### Motion direction

Motion should feel fluid, subtle, and intentional.

Use transitions to improve continuity between sections and images,
not to decorate every element.

### Timing

| Interaction | Duration |
|---|---:|
| Link hover | 150–200ms |
| Button hover | 200ms |
| Image hover | 500–700ms |
| Section reveal | 600–900ms |
| Image transition | 700–1000ms |

### Easing

Use:

- ease for simple interface feedback.
- cubic-bezier(0.4, 0, 0.2, 1) for standard transitions.
- cubic-bezier(0.22, 1, 0.36, 1) for smooth image reveals.
- Carefully controlled custom easing for image warping.

### Transition inspiration

The referenced Dribbble experiment explores a subtle warp effect
on a background slider and emphasizes the importance of easing.

Translate this idea into an understated interior-design
experience:

1. The current image begins to soften or distort slightly.
2. The next image moves into position.
3. The distortion resolves as the new image becomes clear.
4. Text and project metadata transition without losing readability.

Keep the effect brief and restrained.

Do not distort important text or essential interface controls.

### Where to use transitions

- Featured project image changes.
- Hero image transitions, if the hero is implemented as a slider.
- Project detail image galleries.
- Selected section reveals.
- Small button and navigation interactions.

Do not force a transition into every page section.

### Implementation guidance

Use CSS transitions for standard interface interactions.

Use GSAP with ScrollTrigger only where more precise sequencing
or scroll-based reveals genuinely improve the experience.

Use a dedicated animation approach for image warping if required.
A shader-based effect is optional, not a mandatory dependency.

For shader or canvas effects, provide a normal image fallback.

Respect the prefers-reduced-motion media query and disable
nonessential distortion for users who prefer reduced motion.

Keep the experience responsive and avoid animation-related
layout shifts.

---

## 9. Surface and Component Styling

### Cards

Cards should feel light and understated.

Prefer white surfaces with subtle borders and minimal shadows.

Use images to provide visual depth rather than stacking shadows,
blur, gradients, and glass effects.

### Buttons

Primary buttons:

- Forest-green background.
- White text.
- Small corner radius.
- Clear hover and keyboard-focus states.

Secondary buttons:

- Transparent or white background.
- Forest-green text.
- Thin sage border.

Text links:

- Minimal decoration.
- Subtle underline transition.
- Consistent focus visibility.

### Borders

Use #D5E4D8 for subtle dividers and outlines.

Avoid outlining every section or enclosing all content in cards.

### Icons

Use a consistent thin-line icon set.

Icons should support meaning rather than serve as decoration.

Use simple arrows for project navigation and text links where
appropriate.

---

## 10. Accessibility and Responsiveness

- Maintain readable text contrast against #EAF6EE.
- Use semantic heading levels and landmarks.
- Give every meaningful image descriptive alt text.
- Provide accessible labels and errors for all form fields.
- Support keyboard navigation and visible focus indicators.
- Ensure interactive elements have appropriate touch targets.
- Avoid conveying information through color alone.
- Respect reduced-motion preferences.
- Prevent layout shifts during image loading.
- Ensure navigation and forms work on small screens.
- Preserve content readability if animations fail.

---

## 11. Performance

- Use responsive image sizes and modern image formats.
- Lazy-load below-the-fold images.
- Prioritize loading the main hero image.
- Avoid unnecessary animation libraries.
- Keep image transitions lightweight on mobile devices.
- Avoid large, continuously animated WebGL backgrounds.
- Provide static fallbacks for canvas and shader effects.
- Prevent horizontal scrolling and unnecessary layout recalculation.

The website should remain visually complete and usable even when
all decorative motion is disabled.

---

## 12. Do's and Don'ts

### Do

- Use #EAF6EE as the dominant background color.
- Preserve a coherent editorial grid.
- Use photography to communicate quality.
- Give headings room to breathe.
- Use forest green for primary actions.
- Keep transitions subtle and purposeful.
- Maintain consistent image proportions and color grading.
- Make the quote and consultation actions easy to find.
- Use genuine business information and project imagery.
- Ensure the design works on desktop, tablet, and mobile.

### Don't

- Do not reuse the original near-black dashboard appearance.
- Do not use neon green or cyan as prominent accents.
- Do not turn the homepage into an analytics dashboard.
- Do not surround every section with a card.
- Do not use excessive glassmorphism or backdrop blur.
- Do not animate every heading and image independently.
- Do not introduce random corner radii or inconsistent spacing.
- Do not use distorted imagery that interferes with content.
- Do not invent testimonials, ratings, or business achievements.
- Do not sacrifice accessibility or performance for animation.

---

## 13. Final Design Goal

The final experience should feel like a premium, contemporary
interior-design studio with a calm visual identity.

The light sage canvas establishes the atmosphere. Forest-green
typography creates hierarchy. Architectural photography provides
the emotional connection. Editorial spacing gives each section
room to breathe. Carefully eased image transitions provide the
distinctive interactive detail.

The result should feel sophisticated without being cold, premium
without being inaccessible, and animated without being distracting.

**Design principle: A calm canvas, considered spaces, and
transitions that feel as natural as moving through a home.**