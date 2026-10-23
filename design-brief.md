# FATHIUM Landing Page Redesign Brief
## Objective
Redesign the existing FATHIUM nutritional supplement landing page into a premium, modern, advanced e-commerce experience for the Moroccan market. The page must maintain RTL support, use the existing tech stack (HTML5 + Tailwind CSS + Vanilla JS), and deliver a conversion-focused, premium wellness aesthetic.

## Target Audience
Moroccan consumers seeking health and wellness products; value-conscious buyers looking for premium quality at competitive prices; Arabic-speaking users who expect intuitive RTL layout and localized content.

## Aesthetic Direction
- **Premium minimalist wellness**: Clean white backgrounds exclusively (no cream #FBF9F4 or subtle colored backgrounds) with deep forest green (#176B45) as the primary brand color
- **Modern advanced design**: Large product photography, strong typography hierarchy, subtle micro-interactions, layered shadows for depth, and card-based layouts with proper spacing
- **No decorative effects**: No gradients, blur, neon, or excessive animations; focus on typography, spacing, composition, and usability
- **Professional art direction**: Visually balanced, not generic; Moroccan premium brand identity with trustworthy, clean design language

## Content Structure (Preserve all existing Arabic content)
1. **Hero Section**: 2-column desktop grid, dynamic pricing display, clear offer selectors (1kg: 299 MAD, 2kg: 499 MAD with 99 MAD savings + free delivery)
2. **Key Stats Section**: Highlight 99 DH savings, free delivery, and quality guarantees with white backgrounds and subtle borders
3. **Product Details/Ingredients/Benefits**: 2-column grids for better readability, improved spacing, and visual hierarchy
4. **Usage Instructions**: 3-column grid with one highlighted card using brand border, clean white backgrounds
5. **How It Works/FAQ**: Enhanced accordion interactions, proper spacing, hover effects
6. **Pricing/Offers Section**: Clean card design, "الأفضل قيمة" badge for the bundle offer, improved visual hierarchy
7. **Order Form**: Grouped fieldsets, sticky order summary, enhanced form validation with proper focus states
8. **Footer**: Minimal, professional design with clear sections, copyright information, and brand presence

## Typography
- **Arabic font**: Preserve 'Droid Arabic Kufi' / 'Noto Kufi Arabic' for Arabic content - maintains authentic Moroccan aesthetic
- **Latin font**: Keep 'Josefin Sans' for numbers and English text to create visual contrast
- **Hierarchy**: Large bold headlines for section titles, medium weight for subheadings, regular weight for body copy; clear size scale across all screen sizes
- **Line height**: Optimized for Arabic readability (1.85 line-height maintained)

## Color Palette (Strictly enforce no subtle backgrounds)
- **Background**: Pure white #ffffff everywhere - remove all bg-cream and bg-pale instances
- **Primary brand**: #176B45 (deep forest green) for buttons, borders, and accents
- **Dark text**: #103D2B (deep charcoal) for primary text
- **Muted text**: #68736A for secondary text
- **Borders**: #E2E8DF for subtle dividers, #176B45 for highlighted elements
- **Success/CTA**: Same brand green maintained for all conversion elements
- **Hover states**: Use #f9fafb (light gray) for button hovers instead of colored backgrounds

## Technical Requirements
- **Preserve all existing functionality**: `updateHeroPricing()`, `syncAllRadios()`, `calc()`, form validation, ingredient/city rendering must all work
- **RTL support**: Maintain correct Arabic alignment, spacing, and layout direction (`dir="rtl"`)
- **Mobile-first responsiveness**: All sections must work perfectly on mobile, tablet, and desktop
- **No new dependencies**: Keep using Tailwind CSS and Vanilla JS; don't add any external libraries
- **Performance**: Fast loading images, optimized asset sizes, smooth scrolling
- **Accessibility**: Proper focus states, ARIA labels, form validation accessibility

## Image Requirements
- Preserve existing product photography; ensure all image paths are correct and load properly
- Maintain large product images in hero section for visual impact
- Optimize images for fast loading without quality loss

## User Constraints (Critical)
- **NO cream backgrounds (#FBF9F4) or subtle colored/transparent backgrounds** - all backgrounds must be pure white
- **NO blurred/neon/gradient effects** - keep design clean and minimalist
- **Preserve all Arabic content and CTA labels** - don't change any user-facing text
- **Maintain pricing accuracy**: 1kg = 299 MAD, 2kg = 499 MAD, 99 MAD savings, free delivery for 2kg offers
- **Cross-section synchronization**: Radio button selections must sync across hero and order form via `syncAllRadios()`

## Output Path
Update the existing index.html file at: `c:\Users\lenovo\Downloads\fathium-modern-uiux\fathium-redesign\index.html`
Preserve the existing file structure and only modify the HTML/CSS/JS as needed to implement the modern advanced design.