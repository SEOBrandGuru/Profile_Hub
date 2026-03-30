# ProfileHub — Digital Brand Profiles

> Clean, standalone digital profile pages for brands across every industry. Each profile is independently designed, fast-loading, and built to represent a brand at its best anywhere on the web.

---

## What is ProfileHub?

ProfileHub is an open collection of digital brand profile pages. The idea is simple: every brand deserves a clean, well-designed presence on the web that goes beyond a social media page or a basic link aggregator. Each profile on this platform is a fully custom-built HTML page — designed from scratch to match the brand's identity, tone, and audience.

Unlike generic link-in-bio tools, every profile here has its own unique layout, typography system, colour palette, and content structure. A luxury law firm profile looks nothing like an outdoor gear profile. A medical aesthetics clinic page has a completely different feel from a sustainability tech company. That intentionality is what makes these profiles useful and credible.

All pages are pure HTML and CSS — no frameworks, no build tools, no servers. They load instantly, work on every device, and can be hosted anywhere that serves static files.

---

## Design Philosophy

Each profile is built around three principles:

**1. Brand authenticity**
The design of each page is driven by the brand it represents. Colour choices, font pairings, layout density, and tone of voice are all matched to the brand's existing identity. A page for a fishing apparel company uses rugged typography, deep ocean tones, and editorial-style layouts. A page for a law firm uses refined serif typefaces, gold accents, and restrained spacing. Nothing is templated or copy-pasted.

**2. Content that earns its place**
Every section of every profile contains real, purposeful content — not filler. Product links go to actual product pages. Descriptions reflect what the brand actually does. Location details, service descriptions, and calls to action are all grounded in reality. This means the pages are useful to real visitors, not just to crawlers.

**3. Technical simplicity**
There is no JavaScript framework, no component library, no package manager, and no build pipeline. Each profile is a single HTML file with embedded CSS. Google Fonts are loaded via CDN. This keeps file sizes tiny, load times near-instant, and deployment trivially simple. Any hosting platform that serves static files will work — GitHub Pages, Netlify, Vercel, Cloudflare Pages, Render, Surge, Firebase Hosting, or even a basic S3 bucket.

---

## Industry Coverage

ProfileHub currently covers profiles across several distinct industries. The goal over time is to expand coverage across as many verticals as possible — each new profile adds a new design direction, a new content approach, and a new demonstration of what brand-specific web design can look like.

Current industries represented:

- Outdoor & fishing apparel
- Educational games & toys
- Legal services
- Medical aesthetics & laser clinics
- Home & luxury bedding
- Environmental technology & recycling
- Outdoor footwear & marshland gear

Each of these industries has different design conventions, different audience expectations, and different content priorities. A good profile understands those differences and reflects them in every design decision.

---

## Technical Details

All profiles are written in semantic HTML5. Headings follow a logical hierarchy for accessibility and search engine clarity. Meta titles and descriptions are set per-page to accurately describe each brand. Links use `target="_blank" rel="noopener"` for safe external linking. CSS is embedded per-file to eliminate render-blocking external stylesheets beyond Google Fonts.

Layouts are fully responsive using CSS Grid and Flexbox with `clamp()` for fluid typography scaling. No media query breakpoints are hardcoded unnecessarily — the layouts adapt gracefully across all screen widths from 320px mobile to large desktop displays.

Colour choices use CSS custom properties (`--variables`) for consistency within each file. Dark and light themes are applied per brand — some profiles use dark backgrounds with light text, others use warm neutral backgrounds. There is no enforced global theme.

Animation is kept minimal — hover transitions on interactive elements, subtle entrance effects where appropriate. No JavaScript is used for layout or interactivity. All motion is CSS-only and respects `prefers-reduced-motion` conventions.

---

## Hosting & Deployment

Every profile in this repository is ready to deploy with zero configuration. Because they are pure static HTML files, they work on any platform that can serve files over HTTP.

For platforms like GitHub Pages, the entire repository can be deployed as-is. Individual profile pages are accessible at their respective file paths under the `/profiles/` directory. The homepage (`index.html`) serves as the root of the site.

For platforms like Netlify, the repository folder can be dragged and dropped directly onto the deploy area — no settings, no build commands, no environment variables.

For Vercel and Cloudflare Pages, connecting the GitHub repository and deploying with default settings (no framework preset, no build command) is all that is required.

File sizes are intentionally kept small. The largest profile page is under 20KB uncompressed. Total repository size including all profiles and the homepage is under 100KB. This means cold-start load times on any CDN-backed platform will be well under 200ms globally.

---

## Contributing a Profile

Profiles are added on a per-brand basis. Each new profile should meet the following criteria before being included:

- The brand must have a real, publicly accessible website
- The profile design must be unique — no reuse of another profile's layout or colour scheme
- All links must point to real, functional URLs on the brand's own domain
- Meta title and description must accurately describe the brand
- The page must be responsive and render correctly on mobile
- No tracking scripts, no analytics embeds, no third-party iframes
- File must be a single self-contained HTML file placed in the `/profiles/` directory

Profile file names follow the convention `brand-name.html` in lowercase with hyphens, matching the brand's primary domain name where possible.

---

## Profiles Directory

Below is the current list of published profiles, organised by industry niche.

---

### Outdoor & Fishing Apparel

A profile for a performance fishing and outdoor apparel brand based in the United States. The page covers the brand's full product catalogue including fishing shirts, performance hoodies, hunting gear, sun protection clothing, hats, bottoms, and accessories. The design uses deep ocean tones, heavy display typography, and editorial-style card layouts to reflect the brand's rugged outdoor identity.

**Live profile:** [https://seobrandguru.github.io/Profile_Hub/profiles/dagon-fishing.html](https://seobrandguru.github.io/Profile_Hub/profiles/dagon-fishing.html)

---

### Educational Board Games

A profile for an international educational games company producing board games and card games designed for learning. Products include a faith-based trivia game, a fast-paced general knowledge card game, and a two-challenge strategy board game. The design uses bold geometric shapes, a dark navy background, and a vivid amber accent colour to convey the playful and energetic nature of the brand.

**Live profile:** [https://seobrandguru.github.io/Profile_Hub/profiles/sfm-international.html](https://seobrandguru.github.io/Profile_Hub/profiles/sfm-international.html)

---

### Legal Services

A profile for a Manchester-based law firm offering solicitor services for personal and commercial clients. The page presents the firm's practice areas, office locations, and social presence in a tone appropriate to the legal profession — authoritative, restrained, and trustworthy. The design uses dark backgrounds, refined serif typography, and warm gold accents to communicate credibility and discretion.

**Live profile:** [https://seobrandguru.github.io/Profile_Hub/profiles/blackmont-legal.html](https://seobrandguru.github.io/Profile_Hub/profiles/blackmont-legal.html)

---

### Medical Aesthetics & Laser Clinics

A profile for a medical aesthetics clinic operating in Manchester and Bolton, offering laser hair removal, dermal filler treatments, and anti-wrinkle injections. The design reflects the clinical luxury positioning of the brand — warm cream tones, a refined editorial layout, and elegant serif headings. Each treatment is presented as a card linking directly to the relevant service page on the clinic's website.

**Live profile:** [https://seobrandguru.github.io/Profile_Hub/profiles/medlaser-clinics.html](https://seobrandguru.github.io/Profile_Hub/profiles/medlaser-clinics.html)

---

### Luxury Home & Bedding

A profile for a UK luxury bedding brand selling duvets, pillows, mattress toppers, throws, bed linen, nursery bedding, cushions, and protectors. The brand offers free UK delivery and a 30-day returns policy. The page design uses a warm off-white background, classic serif typography, and a large watermark wordmark to reflect the premium and restful identity of the brand.

**Live profile:** [https://seobrandguru.github.io/Profile_Hub/profiles/rohi-bedding.html](https://seobrandguru.github.io/Profile_Hub/profiles/rohi-bedding.html)

---

### Electronic Recycling & Data Security

A profile for a UK company specialising in secure electronic recycling and certified data erasure. The company handles lost property electronics for transport operators, businesses, and local councils — providing GDPR-compliant data destruction and full certificates of destruction. The design uses a dark background with green accents and a subtle circuit-grid texture to reflect the technical and environmental nature of the service.

**Live profile:** [https://seobrandguru.github.io/Profile_Hub/profiles/ready-set-recycle.html](https://seobrandguru.github.io/Profile_Hub/profiles/ready-set-recycle.html)

---

### Outdoor Footwear & Marshland Gear

A profile for a specialist outdoor footwear brand producing anti-sink boots designed for marshland, muddy terrain, and snow. The boots use a unique sole technology that prevents the wearer from sinking into soft ground. The profile also links to the brand's YouTube channel and Instagram. The design uses a deep earthy background, heavy display typography, and a field-guide stamp aesthetic to match the rugged and utilitarian nature of the product.

**Live profile:** [https://seobrandguru.github.io/Profile_Hub/profiles/mudder-boots.html](https://seobrandguru.github.io/Profile_Hub/profiles/mudder-boots.html)

---

## Licence

All profile pages in this repository are published for demonstration and reference purposes. Brand names, logos, and trademarks referenced in profile pages belong to their respective owners. ProfileHub does not claim any affiliation with, endorsement by, or ownership of the brands featured.

HTML and CSS source code in this repository is available under the MIT licence. You are free to use, adapt, and build upon the code for your own projects with attribution.

---

_ProfileHub — Digital brand profiles, built for the web._
