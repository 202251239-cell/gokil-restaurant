# BRIEF: GOKIL Restaurant Landing Page

## About the Client
- **Name**: GOKIL RESTAURANT (also operates D'Brew Coffee)
- **Legal Entity**: PT Muria Jaya Boga (verified company, 11-50 employees)
- **Address**: Jl. AKBP Agil Kusumadya No.68, Jatikulon Krajan, Jati Kulon, Kec. Jati, Kudus, Jawa Tengah 59347
- **Type**: Family Style Fine Dining
- **Cuisine**: Indonesian, Western, Chinese food
- **Signature Dish**: Sego Kikil (best seller — name taken from the outlet itself)
- **Tagline**: "Flavours • Space • Moment"

## Operating Hours
- Monday–Friday: 11:00–21:00 WIB
- Saturday–Sunday: 11:00–22:00 WIB

## Contact
- **WhatsApp Business (Reservasi)**: 082319482812
- **Phone**: 088221738878
- **Instagram**: @gokilrestaurant
- **Linktree**: linktr.ee/Gokilrestaurant

## Facilities
- Indoor & outdoor seating
- Private rooms
- Sound system
- Karaoke
- Free WiFi
- Event space (weddings, birthday parties, corporate meetings, gatherings)
- Grab Food delivery
- Parking

## Menu Links (real, do not change)
- MENU 2026: https://drive.google.com/file/d/1oxXq6dMygP-2r2Fvua1pAmSEuHWml7kJ/view?usp=sharing
- Price List Venue & Buffet: https://drive.google.com/drive/folders/1Ka7wEd4Ij6V3NCIqbHXAXLbZJUCaLsaT?usp=sharing
- Family Style Set Menu: https://www.instagram.com/p/DZt1glYkzaY/?igsh=NGs0cDR4OHJ4ZGNl

## Social Media
- Instagram: https://www.instagram.com/gokilrestaurant/
- Facebook: https://www.facebook.com/gokilrestaurant/

## Design Requirements (CRITICAL)
Create a SINGLE `index.html` file with all CSS/JS inline (no external files except Google Fonts and Unsplash images).

### Style: LUXURY EDITORIAL (NOT AI-default)
- **Fonts**: Fraunces (serif display, italic accents) + Archivo (body) + Space Grotesk (uppercase labels/kickers) via Google Fonts
- **Palette**: Deep charcoal (#1c1917), Cream (#f5f0e8), Warm copper (#b87333), Sage green (#7a8a6e), Ink (#0f0d0b)
- **Layout**: Asymmetric hero (text left, arched photo right), numbered sections (01-04), editorial feel
- **NO**: centered hero, gold gradients, identical card grids, Inter/Poppins fonts, rounded-xl shadows, floating particles
- **YES**: grain texture overlay, thin rules, editorial pull-quotes, asymmetric layouts, marquee strip, rotating stamps

### Sections to Include
1. **Navigation**: Fixed top, dark bg, logo "GOKIL." with copper dot, links (Tentang, Menu, Ruang, Lokasi), CTA button "Reservasi" linking to WhatsApp
2. **Hero**: Asymmetric 2-column. Left: kicker "Family Style Fine Dining — Kudus", h1 "Flavours. Space. Moment." (Space in italic), subtext in Indonesian about family gathering, hours with copper left-border, two CTAs (WhatsApp reservasi + Lihat Menu 2026). Right: arched photo frame with restaurant interior from Unsplash. Scroll indicator at bottom.
3. **About (01)**: 2-column. Left: text about PT Muria Jaya Boga, three cuisines, Sego Kikil signature, 4 feature boxes with copper left-border (Tiga Masakan, Signature, Acara, Sejak 2021). Right: food photo with circular stamp overlay "Family Style Dining"
4. **Menu (02)**: Dark section. 3-column grid for Indonesian/Western/Chinese with Roman numerals (I, II, III), descriptions, tags. CTA row linking to Price List Google Drive.
5. **Events Marquee**: Copper bg, horizontal scrolling text: Wedding Reception, Birthday Party, Corporate Meeting, Family Gathering, After Wedding, Private Dining
6. **Spaces (03)**: Cream bg. Large card (Indoor) + 2 stacked small cards (Outdoor, Private Room) with hover zoom, overlay text.
7. **Facilities Strip**: Dark charcoal bg, horizontal row of 6 items with emoji icons (Sound System, Karaoke, Free WiFi, Parkir Luas, Grab Food, Event Space)
8. **Location (04)**: 2-column. Left: address, hours, WhatsApp number, PT legalitas. Right: Google Maps embed using q-format: `https://maps.google.com/maps?q=Jl.%20AKBP%20Agil%20Kusumadya%20No.68%20Kudus&t=&z=15&ie=UTF8&iwloc=&output=embed`
9. **CTA Section**: Dark bg, centered, "Sudah Siap Merasakan GOKIL?" with WhatsApp + Instagram buttons
10. **Footer**: Near-black bg, logo + address + contact links, disclaimer "⚠️ Situs konsep (demo) — bukan website resmi GOKIL Restaurant"
11. **Floating WhatsApp button**: Green (#25D366), bottom-right, links to wa.me/6282319482812
12. **Demo badge**: Fixed top-right, copper bg, "Demo" text

### WhatsApp Link Format
All WhatsApp links: `https://wa.me/6282319482812?text=Halo%20GOKIL%20Restaurant%2C%20saya%20ingin%20melakukan%20reservasi`

### Unsplash Images to Use
- Hero: `https://images.unsplash.com/photo-1517248135467-4c7edcad34c4?w=1200&q=80&auto=format` (restaurant interior)
- About: `https://images.unsplash.com/photo-1414235077428-338989a2e8c0?w=800&q=80&auto=format` (fine dining plate)
- Indoor: `https://images.unsplash.com/photo-1555396273-367ea4eb4db5?w=1000&q=80&auto=format` (restaurant dining)
- Outdoor: `https://images.unsplash.com/photo-1600093463592-8e36ae95ef56?w=800&q=80&auto=format` (outdoor dining)
- Private: `https://images.unsplash.com/photo-1596178060671-7a80dc8059ea?w=800&q=80&auto=format` (private dining room)

### Mobile Responsive
- Below 860px: single column, hamburger menu with drawer (dark overlay, no backdrop-filter blur on mobile), stacked sections
- Hero arch becomes full-width rectangle on mobile
- Menu grid stacks to single column

### JavaScript Requirements
- Sticky nav shrinks on scroll
- Reveal-on-scroll with IntersectionObserver (threshold 0.05, rootMargin '0px 0px -24px 0px')
- Safety sweep: revealAll() on load/resize/1200ms timeout (elements with rect.top < innerHeight+40 get visible class)
- Marquee animation (CSS keyframes, infinite scroll)
- Mobile drawer toggle (add/remove 'open' class and 'no-scroll' on body)
- WhatsApp button hover scale

### Copy Tone
Conversational Indonesian, warm, no marketing clichés. Example: "Bukan sekadar tempat makan. Ini adalah ruang di mana keluarga berkumpul, cerita tercipta, dan setiap suapan punya makna."

Output: Create the file as `index.html` in the current directory.
