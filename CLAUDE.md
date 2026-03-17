# GlutIt – Design Rules

## DO
- Light, minimal, clean, modern design – shadcn aesthetic
- Neutral palette: whites, grays, one subtle warm stone/amber accent
- Good typography hierarchy, plenty of whitespace
- Font: Inter from Google Fonts
- Mobile responsive
- Light motion: scroll animations via IntersectionObserver, smooth transitions, subtle hover

## DON'T
- NO bright saturated gradients or gradient text
- NO emoji icons (use Lucide icons)
- NO "revolutionary", "game-changing" marketing copy
- NO heavy shadows or busy patterns
- NO dark mode
- NO border-radius > rounded-2xl
- NO cramped spacing or tiny fonts (< 14px)

## Stack
Single HTML file + Tailwind CSS CDN + Lucide icons CDN

## Sections
Hero + CTA, How it works (3 steps), Features, Testimonials, Footer

## Color Tokens
- Accent: stone-800 (#292524) buttons, amber-700 (#b45309) for GF badges/confidence
- Backgrounds: white / stone-50 (#fafaf9) alternating
- Text: gray-900 headings, gray-500 body, gray-400 muted
- Borders: gray-100
