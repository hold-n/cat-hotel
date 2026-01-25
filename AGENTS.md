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
- **Location**: Dublin, Ireland (mentioned in header and footer)
- **Hosts**: Always mention Max & Mira as the hosts (prominent in hero section)
- **Bring your own supplies**: Make it clear (playfully) that guests must bring:
  - Litterbox + Litter (combined into one tile) - MUST BRING
  - Cat food ("The Good Stuff") - MUST BRING  
  - Scratching board - RECOMMENDED (we don't have one)
  - Toys, blankets, medications - recommended
- **Pricing**: Simple list of services, all "FREE*" where * = a bottle of wine and a funny story
- **Testimonials**: Use real cat photos, full body visible (no cropping cats), pill-shaped frames

## Cat Photos
- Show the entire cat, never crop body parts
- Use `background-size: contain` to fit full cat in frame
- Pill-shaped containers (tall rounded rectangles) work well for portrait photos
- Current guests: Cloud, Chuchu & Mia, Nanysha, Semyon, Stinky, Lumos, Steve

## Sections (in order)
1. **Hero**: 5-paw rating, welcome message, prominent Max & Mira intro, CTA
2. **Ameowities**: What the hotel offers (with humor)
3. **Reviews**: Real cats with funny reviews and photos
4. **Pricing**: Simple list of services, all free
5. **Packing List**: What to bring - critical for actual use
6. **Booking Form**: Collects info but openly admits it does nothing
7. **Footer**: Contact info, reminder about what to bring

## Technical Notes
- Single HTML file with embedded CSS
- No JavaScript frameworks needed
- SVG favicon: simple purple roof with cat ears, cream walls (minimal details for 32x32 legibility)
- Served with `busybox httpd`
- Photo lightbox: clicking/tapping cat photos opens full-size view
- Escape key closes modals and lightbox
- Page title: "Cat Hotel 🐱 by Max & Mira | Dublin"

## Cat-Specific Notes
Some cats have specific stories to incorporate in reviews:
- **Nanysha**: Stayed twice, first time for 6 months (don't joke about "moving in permanently" - owners might misread)
- **Semyon**: Visited twice (repeat guest, "definitely not attached")
- **Cloud**: Ate a plastic bag once ("Plastic Bag Connoisseur")
- **Lumos**: Tried to escape through window once ("Amateur Escape Artist")
- **Stinky**: Loves blankets and warmth (hairless cat)

## Real Hotel Details
Things that are actually true (incorporate into amenities/descriptions):
- **Bird TV**: Big window with a tree outside, lots of birds
- **Sleeping**: Bed, couch, chairs available - cats often prefer the carpet
- **Plants**: Cats eat the houseplants despite being told not to
- **Recreation**: No scratching post or laser pointer; cats chase watch reflections and have zoomies
- **Lost toys**: Mystery collection behind the couch from previous guests
- **Instagram**: Cats may appear on Max & Mira's stories
- **Attention**: Cats get lots of attention, probably more than they want
