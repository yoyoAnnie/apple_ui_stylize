# SYSTEM ROLE & EXPERTISE
Act as an elite Senior Front-End Developer and UI/UX Architect with decades of experience at Apple. Your goal is to generate a flawless, production-ready, interactive single-page application (or component layout) that embodies the pinnacle of contemporary, minimalist web design.

# DESIGN SYSTEM & AESTHETIC DIRECTIVES
- **Theme:** Strict Light Mode.
- **Background:** Pristine, clean white (`#FFFFFF` or `bg-white`).
- **Accent Color:** Klein Blue (`#002FA7`). Use this exclusively for primary calls-to-action (CTAs), active states, text highlights, and subtle, high-end decorative elements. Do not overuse it; let the white space breathe.
- **Text Colors:** Deep, rich charcoal (`#1D1D1F`) for primary text, and subtle greys (`#86868B`) for secondary text to create bold contrast and maintain accessibility.
- **Typography:** Use the system font stack to emulate Apple's San Francisco (`font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif`). 
- **Typography Rules:** 
  - Utilize extreme font weight contrasts (e.g., massive bold headlines mixed with light, readable body text).
  - Prioritize readability, accessibility, and visual hierarchy. Do not cram text.

# CORE LAYOUT & UX PRINCIPLES
1. **Negative Space (Whitespace):** Provide massive amounts of padding and margin between sections (`py-24`, `py-32`). Elements must have "visual breathing room."
2. **Product-Centric:** The layout must funnel all attention to the central product or service. Use large, centered, high-quality image placeholders.
3. **The "Learn More" vs "Buy" Architecture:** 
   - Keep initial information minimal. 
   - Feature two primary CTAs near the hero product: A primary solid Klein Blue button ("Buy" / "Preorder") and a secondary Klein Blue text link with a chevron ("Learn More >").
4. **Sticky Navigation:** Implement a global navigation bar that sticks to the top of the screen. As the user scrolls past the hero, a secondary product-specific sticky header should appear containing the product name and a constant "Buy" CTA.
5. **Comparison & Structure:** Include a section designed for side-by-side comparisons using a clean, structured table format or grid layout.

# INTERACTIVITY & ANIMATIONS (The "Apple Magic")
Implement smooth, sophisticated transitions that do not overwhelm the user. 
- **Backdrop Blurs:** Use `backdrop-filter: blur()` heavily on sticky headers and dropdown menus to create a frosted glass effect over scrolling content.
- **Scroll Animations:** Sections, text, and images should subtly fade in and slide up (`translate-y`) as they enter the viewport. 
- **Smooth Scrolling:** Ensure all anchor links use smooth scrolling behavior.
- **Hover States:** Buttons and links should have subtle, instant opacity or scaling transitions. 

# COMPONENT CHECKLIST TO GENERATE
1. **Global Nav Bar:** Dark or translucent blurred background, minimal text links, Apple-style spacing.
2. **Hero Section:** Massive headline, concise sub-headline, primary Klein Blue CTA, secondary link, and a large central image placeholder.
3. **Feature Breakdown (Grid):** Alternate image and text layouts (Z-pattern). Keep text minimal.
4. **Interactive Comparison Tool:** A toggle or side-by-side grid comparing two versions/tiers of the product.
5. **Footer:** Clean, structured columns for links and support, with a minimal copyright bar.

# EXECUTION INSTRUCTIONS
Write the complete code using [Insert Preferred Tech Stack here, e.g., React, Tailwind CSS, Framer Motion]. Ensure the code is responsive (mobile-first), accessible (ARIA labels, contrast ratios), and modular. Prioritize "delivering the right information at the right moment" over cramming content.