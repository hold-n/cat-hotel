# Cat Hotel Website - Guiding Principles

> **Note to future agents**: Keep this file updated! When you make design decisions, add new features, or change implementation details, document them here. This file is the source of truth for how this website should look and behave.

## Purpose
A half-joke, half-real landing page for "Cat Hotel" - a cat-sitting service run by Max & Mira for friends. The site should be funny enough to share as a joke, but legitimate enough that friends might actually use it to arrange cat-sitting.

## Tone & Style
- **Cheesy and punny**: Cat puns encouraged (purrfect, meow, fur real, etc.)
- **Playful but not childish**: Humor should land with adults
- **Self-aware**: The site knows it's a bit ridiculous (e.g., form admits it does nothing)
- **Sketchy/careless aesthetic**: Handwritten fonts, dashed borders, casual feel

## Design Principles
- **Minimalistic**: No gradients, shadows, or excessive animations
- **Flat colors**: Purple, brown, red/orange color scheme
- **Simple borders**: Dashed borders for cards, solid for emphasis
- **Patrick Hand font**: For body text to maintain sketchy look
- **Fredoka font**: For headings and buttons
- **Mobile-first**: Must look good on phones

## Content Guidelines
- **Hosts**: Always mention Max & Mira as the hosts
- **Bring your own supplies**: Make it clear (playfully) that guests must bring:
  - Litterbox ("The Throne") - MUST BRING
  - Cat food ("The Good Stuff") - MUST BRING  
  - Litter - MUST BRING
  - Toys, blankets, medications - recommended
- **Pricing**: Everything is "FREE*" where * = a bottle of wine and a funny story
- **Testimonials**: Use real cat photos, full body visible (no cropping cats), pill-shaped frames

## Cat Photos
- Show the entire cat, never crop body parts
- Use `background-size: contain` to fit full cat in frame
- Pill-shaped containers (tall rounded rectangles) work well for portrait photos
- Current guests: Cloud, Chuchu & Mia, Nanysha, Semyon, Stinky, Lumos, Steve

## Sections
1. **Hero**: 5-paw rating, welcome message, hosts intro, CTA
2. **Ameowities**: What the hotel offers (with humor)
3. **Packing List**: What to bring - critical for actual use
4. **Room Types**: Joke tiers, all free
5. **Testimonials**: Real cats with funny reviews
6. **Booking Form**: Collects info but openly admits it does nothing
7. **Footer**: Contact info, reminder about what to bring

## Technical Notes
- Single HTML file with embedded CSS
- No JavaScript frameworks needed
- SVG favicon: purple house with cat ears
- Served with `busybox httpd`
- Photo lightbox: clicking/tapping cat photos opens full-size view
- Escape key closes modals and lightbox

## Cat-Specific Notes
Some cats have specific stories to incorporate in reviews:
- **Nanysha**: Stayed twice, first time for 6 months (don't joke about "moving in permanently" - owners might misread)
- **Semyon**: Visited twice (repeat guest, "definitely not attached")
- **Cloud**: Ate a plastic bag once ("Plastic Bag Connoisseur")
- **Lumos**: Tried to escape through window once ("Amateur Escape Artist")
- **Stinky**: Loves blankets and warmth (hairless cat)
