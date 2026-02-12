# 🔬 HelioFlux Interactive Patient Journey

> **For:** Claude Code / Coding Agent  
> **Created by:** Kelly Lucas + Kip 🦉  
> **Date:** February 11, 2026  
> **Goal:** Build an emotionally compelling, scientifically accurate interactive experience that shows why early cancer detection matters

---

## 📋 TABLE OF CONTENTS

1. [The Vision](#the-vision)
2. [Core Concept](#core-concept)
3. [User Journey](#user-journey)
4. [Screens & Content](#screens--content)
5. [The Science (Accurate Data)](#the-science)
6. [Visual Design](#visual-design)
7. [Technical Spec](#technical-spec)
8. [Build Instructions](#build-instructions)

---

## 🎯 THE VISION

### The Problem
Cancer detection today requires tumors to grow to ~1 BILLION cells before they're visible on scans. By then, treatment is harder, more invasive, and less likely to succeed.

Most people don't understand this. They think "early detection" means annual mammograms. They don't realize how late "early" actually is.

### The Solution
An interactive experience that makes people FEEL the difference between:
- **Current reality:** Waiting until cancer is advanced
- **HelioFlux future:** Catching it when it's just starting

### Why Interactive?
- Static decks don't create emotional connection
- People remember experiences, not slides
- Investors see this demo'd in a pitch → unforgettable
- Website visitors engage longer → better conversion
- Patients see themselves → builds trust

---

## 💡 CORE CONCEPT

### "Two Paths, One Patient"

The user follows **Sarah, 52** — a composite patient character.

She has the same symptoms, same family history, same initial concern.

But in **Path A**, she gets traditional screening.
In **Path B**, she gets HelioFlux screening.

The user sees both journeys side by side — and watches the outcomes diverge.

### Emotional Arc

```
HOPE → ANXIETY → WAITING → [DIVERGENCE] → RELIEF vs DEVASTATION → RESOLUTION
```

**Path A ending:** Late diagnosis, aggressive treatment, uncertain outcome
**Path B ending:** Early detection, minimal intervention, back to life

---

## 🚶 USER JOURNEY

### Flow Overview

```
[INTRO] → [MEET SARAH] → [THE CONCERN] → [CHOOSE PATH]
                                              ↓
                    ┌─────────────────────────┴─────────────────────────┐
                    ↓                                                   ↓
              [PATH A: Traditional]                           [PATH B: HelioFlux]
                    ↓                                                   ↓
              [WAITING...]                                      [QUICK TEST]
                    ↓                                                   ↓
              [MORE TESTS]                                      [RESULTS]
                    ↓                                                   ↓
              [DIAGNOSIS: LATE]                              [EARLY WARNING]
                    ↓                                                   ↓
              [TREATMENT]                                    [SIMPLE INTERVENTION]
                    ↓                                                   ↓
              [OUTCOME A]                                       [OUTCOME B]
                    └─────────────────────────┬─────────────────────────┘
                                              ↓
                                    [COMPARISON SCREEN]
                                              ↓
                                    [THE TECHNOLOGY]
                                              ↓
                                    [CALL TO ACTION]
```

### Interaction Model

- **Desktop:** Click to advance, hover for details
- **Mobile:** Tap/swipe to progress
- **Time:** ~3-5 minutes total experience
- **Mode:** Self-guided or auto-play option

---

## 📱 SCREENS & CONTENT

### Screen 1: INTRO

**Visual:** Dark background, subtle light particles floating (biophotons)

**Text:**
> Every day, your cells emit light.
> 
> Tiny signals. Invisible to the eye.
> 
> But not invisible to science.

**CTA:** [Begin the Journey →]

---

### Screen 2: MEET SARAH

**Visual:** Warm, friendly illustration of Sarah (not photo-realistic, approachable style)

**Text:**
> Meet Sarah. She's 52.
> 
> Mother of two. Runs her own business.
> Hasn't missed a checkup in 15 years.
> 
> Last month, something felt different.

**Details card (expandable):**
- Family history: Mother had breast cancer at 58
- Last mammogram: 11 months ago (clear)
- Current symptom: Persistent fatigue, minor discomfort

**CTA:** [Continue →]

---

### Screen 3: THE CONCERN

**Visual:** Sarah at doctor's office

**Text:**
> Her doctor says it's probably nothing.
> 
> But recommends screening, just to be safe.
>
> Sarah has a choice.

**CTA:** [See Her Options →]

---

### Screen 4: CHOOSE PATH (Interactive Split)

**Visual:** Screen splits vertically

**Left side (muted colors):**
> **Traditional Screening**
> Mammogram, bloodwork, wait.
> The standard of care for 40 years.

**Right side (warm glow):**
> **HelioFlux Screening**
> 5-minute biophotonic scan.
> Results in real-time.

**Interaction:** User can tap either to explore, or...

**CTA:** [Watch Both Paths →] (recommended — shows both simultaneously)

---

### Screen 5A: PATH A - Traditional Screening

**Visual:** Calendar animation, pages flipping

**Timeline unfolds:**

| Week | What Happens |
|------|--------------|
| Week 1 | Mammogram scheduled for next month |
| Week 5 | Mammogram completed. "We see something. Probably benign." |
| Week 6 | Follow-up ultrasound ordered |
| Week 9 | Ultrasound shows area of concern. Biopsy recommended. |
| Week 11 | Biopsy performed. Waiting for results. |
| Week 13 | **Diagnosis: Stage 2 breast cancer** |

**Emotional beat:**
> 13 weeks of waiting.
> 13 weeks of growing.
> 13 weeks the cancer had to spread.

---

### Screen 5B: PATH B - HelioFlux Screening

**Visual:** Calm, modern clinic. Soft lighting.

**Timeline unfolds:**

| Day | What Happens |
|-----|--------------|
| Day 1 | Sarah sits for a 5-minute scan. No needles. No radiation. |
| Day 1 | Biophotonic sensors detect abnormal cellular emissions |
| Day 1 | AI analysis flags early-stage cellular changes |
| Day 2 | Doctor reviews results with Sarah |
| Day 3 | Targeted follow-up confirms: pre-cancerous cells detected |
| Week 2 | **Minimally invasive removal. No chemo needed.** |

**Emotional beat:**
> 3 days from concern to clarity.
> Caught at 8 million cells.
> Before it became cancer.

---

### Screen 6: THE COMPARISON

**Visual:** Split screen, side-by-side outcomes

**Left (Path A):**
```
Stage 2 Diagnosis
Surgery + Chemotherapy + Radiation
6 months of treatment
$150,000+ in medical costs
Ongoing monitoring for recurrence
```

**Right (Path B):**
```
Pre-cancerous Detection
Outpatient procedure
2 weeks to normal life
$5,000 total cost
Peace of mind
```

**Key stat (animated):**

> **Traditional detection:** 1,000,000,000 cells
> **HelioFlux detection:** 8,000,000 cells
> 
> **That's 125x earlier.**

---

### Screen 7: THE TECHNOLOGY

**Visual:** Elegant diagram of biophoton emission from cells

**Text:**
> Every cell in your body emits ultra-weak photons.
> 
> Healthy cells glow differently than unhealthy ones.
>
> HelioFlux reads these signals — detecting changes before tumors form.

**Expandable sections:**
- **How it works:** Ultra-weak photon emission (UPE) detection
- **The science:** Published in iScience (2025), peer-reviewed
- **The team:** Dr. Nirosha Murugan (Canada Research Chair) + Kelly Lucas
- **Non-invasive:** No blood draw. No biopsy. No radiation.

---

### Screen 8: CALL TO ACTION

**Visual:** Light, hopeful, forward-looking

**For investors:**
> Want to bring this future closer?
> [Learn About Investing →]

**For partners:**
> Interested in clinical collaboration?
> [Partner With Us →]

**For everyone:**
> Want to know when HelioFlux is available?
> [Join the Waitlist →]

**Social:**
> [Share This Experience] — Twitter, LinkedIn, Email

---

## 🔬 THE SCIENCE (Accurate Data)

### Key Numbers to Use

| Metric | Traditional | HelioFlux |
|--------|-------------|-----------|
| Detection threshold | ~1 billion cells | 5-10 million cells |
| Tumor size at detection | ~1 cm diameter | Not yet a tumor |
| Time to results | Weeks to months | Minutes to days |
| Invasiveness | Blood draws, biopsies, radiation | Non-invasive sensor |
| False positive rate | 10-15% (mammography) | TBD (clinical trials) |

### Scientific Basis

**Ultra-Weak Photon Emissions (UPEs):**
- All living cells emit photons (biophotons)
- Emission patterns differ between healthy and abnormal cells
- Detectable with sensitive photomultiplier equipment
- Research basis: 40+ years of biophotonics literature

**HelioFlux Innovation:**
- Proprietary sensor array optimized for clinical use
- AI/ML analysis of emission patterns
- Platform technology (not limited to one cancer type)

**Published Research:**
- iScience 2025 paper (peer-reviewed)
- Dr. Nirosha Murugan's lab at [University]
- Multiple wavelength detection results

### What NOT to Claim

- ❌ "FDA approved" (not yet)
- ❌ Specific accuracy percentages (pending clinical trials)
- ❌ "Cures cancer" (it detects, doesn't treat)
- ❌ Guaranteed outcomes

### Safe Language

- ✅ "Aims to detect"
- ✅ "In development"
- ✅ "Based on peer-reviewed research"
- ✅ "Potential to transform"

---

## 🎨 VISUAL DESIGN

### Color Palette

```css
/* Primary - Trust & Innovation */
--helio-blue: #0A2540;        /* Deep navy - authority */
--helio-teal: #00B4D8;        /* Bright teal - innovation */
--helio-glow: #7DF9FF;        /* Electric cyan - biophoton glow */

/* Secondary - Warmth & Hope */
--warm-white: #F8F9FA;
--soft-coral: #FF6B6B;        /* For contrast moments */
--gold-accent: #FFD700;       /* Success, hope */

/* Paths */
--path-a-muted: #6C757D;      /* Traditional - gray, clinical */
--path-b-bright: #00B4D8;     /* HelioFlux - vibrant, hopeful */

/* States */
--success: #28A745;
--warning: #FFC107;
--danger: #DC3545;
```

### Typography

```css
/* Headers - Modern, clean */
font-family: 'Inter', 'SF Pro Display', sans-serif;
font-weight: 600;

/* Body - Readable, warm */
font-family: 'Source Sans Pro', 'Helvetica Neue', sans-serif;
font-weight: 400;

/* Data/Stats - Impactful */
font-family: 'Space Grotesk', monospace;
font-weight: 700;
```

### Visual Motifs

1. **Biophotons:** Subtle floating light particles throughout
2. **Cellular patterns:** Abstract, beautiful cell structures
3. **Light beams:** Representing detection/scanning
4. **Timeline ribbons:** For journey progression
5. **Split screens:** Path A vs Path B comparison

### Animation Philosophy

- **Smooth, not flashy** — medical context requires trust
- **Purposeful motion** — every animation conveys meaning
- **Particle effects** — subtle biophoton visualization
- **Progressive reveal** — information unfolds naturally

### Illustrations vs Photos

**Use illustrations:**
- More approachable
- Avoid HIPAA concerns
- Easier to update
- Universal representation

**Style:** Modern, minimal, diverse characters, warm but professional

---

## 🔧 TECHNICAL SPEC

### Architecture

**Recommended: Single-page app with scroll/click progression**

```
Frontend:
- React or Vue 3
- Framer Motion (animations)
- GSAP (scroll-triggered animations)
- Lottie (complex animations)

Hosting:
- Vercel or Netlify (static)
- Or embed in existing HelioFlux site

Analytics:
- Track completion rate
- Track path choices
- Track CTA clicks
```

### Component Structure

```
/src
  /components
    Intro.jsx
    MeetSarah.jsx
    TheConcern.jsx
    PathChoice.jsx
    PathA/
      Timeline.jsx
      Diagnosis.jsx
      Treatment.jsx
    PathB/
      QuickTest.jsx
      Results.jsx
      Resolution.jsx
    Comparison.jsx
    Technology.jsx
    CallToAction.jsx
  /animations
    Biophotons.jsx
    CellGlow.jsx
    TimelineReveal.jsx
  /data
    content.json
    science-facts.json
  App.jsx
  index.css
```

### Responsive Breakpoints

```css
/* Mobile first */
@media (min-width: 640px) { /* Tablet */ }
@media (min-width: 1024px) { /* Desktop */ }
@media (min-width: 1280px) { /* Large desktop */ }
```

### Accessibility

- Keyboard navigation throughout
- Screen reader compatible
- Reduced motion option
- High contrast mode
- Alt text for all visuals
- Captions for any audio

### Performance

- Lazy load heavy animations
- Optimize images (WebP)
- Target Lighthouse score: 90+
- First contentful paint: <1.5s

---

## 🛠️ BUILD INSTRUCTIONS

### Step 1: Setup

```bash
npx create-vite@latest helioflux-journey --template react
cd helioflux-journey
npm install framer-motion gsap lottie-react
npm install tailwindcss postcss autoprefixer
npx tailwindcss init -p
```

### Step 2: Content First

Create `/src/data/content.json` with all text content. This makes it easy to:
- Update copy without touching code
- A/B test different messages
- Translate to other languages

### Step 3: Build Screens in Order

1. Start with static screens (no animation)
2. Add navigation flow
3. Add animations progressively
4. Add interactive elements
5. Polish and optimize

### Step 4: Test Emotional Impact

Before launch:
- Show to 5 people unfamiliar with HelioFlux
- Ask: "How did this make you feel?"
- Track: Where did they pause? What questions came up?
- Iterate based on feedback

### Step 5: Deploy

```bash
npm run build
# Deploy to Vercel
npx vercel

# Or GitHub Pages
npm install -D gh-pages
npx gh-pages -d dist
```

---

## 📊 SUCCESS METRICS

| Metric | Target |
|--------|--------|
| Completion rate | >60% reach final screen |
| Time on experience | 3-5 minutes average |
| CTA click rate | >15% |
| Share rate | >5% |
| Investor meetings booked | Track separately |

---

## 🎯 QUICK WIN VERSION

If full build is too much, here's a **MVP in 1 day:**

1. **Static comparison page** (no interaction)
2. Sarah's story as scrolling narrative
3. Key stats with simple animations
4. Single CTA at bottom

Can upgrade to full interactive version later.

---

## 📁 ADDITIONAL ASSETS NEEDED

- [ ] Sarah character illustration (or commission)
- [ ] Cell/biophoton illustrations
- [ ] HelioFlux device rendering (if available)
- [ ] Team photos (Kelly, Nirosha)
- [ ] Sound design (optional — subtle ambient)

---

*Built with 🦉 by Kip for Kelly & HelioFlux — February 2026*

*"The future of cancer detection isn't just earlier. It's gentler."*
