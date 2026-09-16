# ENNUSTUSED1 Website Clone

A pixel-perfect, fully self-contained clone of [ennustused1.com](https://ennustused1.com/) with all animations, interactions, assets, and subpages.

## Features & Animations Included

1. **Announcement Bar**:
   - Lime highlight badge, link with animated arrow, and dismissible close button.
2. **Floating Pill Navigation**:
   - Glassmorphic backdrop blur (`backdrop-filter: blur(12px)`), logo brand SVG, and lime gradient CTA button.
3. **Hero Section**:
   - High-resolution stadium background, Phudu display typography, glowing lime ambient backlight, and hero hand mockup.
4. **Rating Band**:
   - Lime mesh background with frosted glass rating card, 4.8 star rating, and overlapping customer avatar stack (+130k badge).
5. **Infinite League Marquee**:
   - Smooth horizontal endless loop with fade masks on left/right.
   - Grayscale to full color transition on hover (`filter: grayscale(100%)` -> `grayscale(0)`).
   - Pauses on hover.
6. **Asymmetrical Bento Features**:
   - 2-column bento cards with gradient mesh and scroll-triggered reveal animations.
7. **3-Step Sticky Stacking Cards**:
   - Cards stack on top of each other as you scroll (`position: sticky; top: 90px`).
   - Giant gradient watermark step numbers (`01`, `02`, `03`).
   - Pure CSS iPhone mockups with metallic chassis, dynamic island, volume buttons, and dynamically injected iOS status bars.
   - Floating 3D sports shapes (`shape-ball.webp`, `shape-bolt.webp`).
8. **Yesterday's Slip Promo**:
   - Tilted betting slip with ambient lime glow.
   - Dynamically calculated yesterday's date formatted in Estonian.
9. **Proof Wall & Interactive Lightbox**:
   - Continuous horizontal scrolling marquee of real winning tickets.
   - Alternating tilts and zoom-on-hover.
   - Clicking any screenshot opens an interactive full-screen lightbox with smooth scale animation, backdrop blur, ESC key dismiss, and close button.
10. **Dual-Direction Customer Review Marquees**:
    - Two rows running in opposite directions with 24 verified reviews and 5-star ratings.
11. **FAQ Accordion**:
    - Animated '+' rotating to 'x' on toggle with giant background watermark '?'.
12. **CTA Banner**:
    - Lime mesh radial gradient banner with tilted iPhone mockup displaying daily betting tips.
13. **Multi-Step Onboarding Funnel (`/alusta/`)**:
    - Full interactive questionnaire with slide-in/slide-out animations (`enterRight`, `exitLeft`, `enterLeft`, `exitRight`).
    - Dynamic progress bar, card selection with pulse animation, animated loading sequence with multi-stage progress bars, and custom results summary.
14. **Dedicated Subpages**:
    - `/statistika/`: Statistics and betting history.
    - `/kogemused/`: Customer experiences and proof screenshots.
    - `/privaatsus/`: Privacy policy.
    - `/tingimused/`: Terms of service.
    - `/kontakt/`: Contact page.

## How to Run

### Option 1: Direct File Opening
Double-click `index.html` in Windows Explorer to open it directly in your browser. All assets are locally stored and use relative paths.

### Option 2: Local HTTP Server
Run in PowerShell inside this directory:
```powershell
python -m http.server 8080
```
Then open:
[http://localhost:8080](http://localhost:8080)
