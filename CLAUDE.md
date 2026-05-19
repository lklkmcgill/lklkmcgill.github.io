# Profile Site — Songheng Huang

Personal profile website for DataAnnotation.tech review and general portfolio use.
Single self-contained HTML file: `index.html`. Zero build step, zero framework.

## Owner
- Name: Songheng Huang (huangsongheng)
- Location: Zhongshan, Guangdong, China
- Status: Third-year CS undergraduate
- Goal: Data annotation & AI training opportunities

## Design system (淡雅暖绿 / soft sage)
- Background: warm off-white (#faf9f6)
- Primary accent: muted sage green (#6b8e6b)
- Secondary accent: celadon (#8ba89b)
- Warm accent: muted gold (#c4a96e)
- Font: Inter (Google Fonts, weights 400–800)
- Max width: 1000px
- Border radius: 14px (large), 10px (small)
- Keep the light/airy feel — no dark mode, no bold colors

## Section structure
1. Nav (sticky, glass-morphism)
2. Hero (subtle gradient, avatar, name, tagline, badges)
3. About (info card + narrative text, 2-col grid)
4. Skills (4 categories: Programming / Languages / Tools / Strengths)
5. Education & Learning (timeline: university + self-study)
6. Projects (3 cards: campus platform, data toolkit, portfolio site)
7. Contact (email, LinkedIn, GitHub, location)
8. Footer

## Content rules
- Frame as a capable CS student, not a senior professional
- Emphasize: attention to detail, fast learning, bilingual, self-motivation
- Skills should be realistic for a junior undergrad with ambition
- Placeholder values to fill in: university name, real email, real GitHub/LinkedIn URLs
- "吹牛逼"适度 — positive framing without false claims

## Editing rules
- Always edit `index.html` directly
- No external dependencies beyond Google Fonts
- No npm, no build tools, no frameworks
- Test responsive at 480px, 768px, 1024px+
- Keep CSS variables in `:root` for easy theme tweaks
