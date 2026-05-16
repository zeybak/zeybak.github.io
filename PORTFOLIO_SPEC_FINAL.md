# Mauro Juarez Ariño — Portfolio Spec (Final v2)

## Overview

GitHub Pages portfolio for Mauro Juarez Ariño, Senior Game Developer & Tech Lead.

**Approach:** Single-page scroll. Hero → Projects → About → Contact.
**Stack:** Static HTML + CSS + minimal JS. No build process. Single `index.html` + images folder.
**Hosting:** GitHub Pages → `zeybak.github.io`
**Repo name:** `zeybak.github.io`

---

## Design System

### Colors (matched to CV)

```
NAVY                #1A2B4A   — Headers, dark elements
TEXT_DARK           #1A2B4A   — Important text, names
TEXT_BODY           #3A4556   — Body copy
TEXT_MUTED          #7A8599   — Subtitles, metadata
BG_PRIMARY          #FFFFFF   — Main background
BG_SECONDARY        #F4F6FA   — Card backgrounds, alt sections
BG_LEFT_COLUMN      #E8EDF5   — Sidebar / panel backgrounds
ACCENT_DIVIDER      #D8DEE9   — Dividers, borders
LINK_COLOR          #1A2B4A   — Links default (underlined)
LINK_HOVER          #3A4556   — Links hover
```

### Typography

System fonts: `-apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, Arial, sans-serif`

### Layout

- Max width: 1200px (centered)
- Mobile responsive (single column on <768px)
- Project cards in **2-column grid on desktop, 1 column on mobile**
- Cards should be **MINIMALIST** (NOT huge — small images, tight typography)

---

## Navigation (Fixed Top Bar)

- Logo: `MJ.` (top-left)
- Links: `Projects` · `About` · `Contact`

Smooth scroll to anchors.

---

## Hero Section

```
              Senior Game Developer

              Mauro Juarez Ariño
              ━━━━━━━━━━━━━━━━━━━━

         [View Projects]  [Let's Connect]


   9+         10+         3         Multi-Platform
   Years      Shipped     Engines   PC · Console
   Dev        Games                 · Mobile

                  Scroll ↓
```

### Stats counter

Numbers animate from 0 to final on page load. "Multi-Platform" stays static text.

### Buttons

- **[View Projects]** → smooth scroll to #projects
- **[Let's Connect]** → smooth scroll to #contact

---

## Projects Section

### Card format (small, minimalist)

```
┌─────────────────────────────────┐
│        [PROJECT IMAGE]          │
│                                 │
│  TITLE                          │
│  1-line description.            │
│  Studio · Engine                │
│  Your Role                      │
│                                 │
│  • Highlight 1                  │
│  • Highlight 2                  │
│  • Highlight 3                  │
│                                 │
│  [See More →]                   │
└─────────────────────────────────┘
```

All "See More →" links open in **new tab** (target="_blank").

---

### Card 01 — TERATOPIA

Image: `teratopia.jpg`

```
TERATOPIA
Action-adventure with strategy and RPG elements.
Ravegan · Unity / C#
Lead / Game Developer

• Shipped across PC, PlayStation, and Xbox
• Owned gameplay, AI, shaders, and netcode optimization
• Led small team and mentored juniors
```

Link: `https://store.steampowered.com/app/1338100/Teratopia/`

---

### Card 02 — DUNGEON GUNFIGHT

Image: `dungeon_gunfight.jpg`

```
DUNGEON GUNFIGHT
Looter shooter where players raid dungeons, collect loot, 
and challenge bosses while climbing the ranks.
Stormward Studios · Roblox / Luau
Lead Developer and Producer

• Owned tech stack, design, and LiveOps
• 18M+ visits
• Built combat, loot, and multiplayer systems
```

Link: `https://www.roblox.com/games/18582044627`

---

### Card 03 — GUARDIANS OF ORION (PHASE 2)

Image: `guardians_of_orion.jpg`

```
GUARDIANS OF ORION (PHASE 2)
Co-op real-time First Person Shooter.
Dankie · Unreal Engine / C++
Sr. Game Developer

• Network architecture and multiplayer systems
• Custom Unreal Engine modifications
• Gameplay, AI, and UI work
```

Link: `https://store.steampowered.com/app/407840/Guardians_of_Orion_Phase_2/`

---

### Card 04 — GRIEFVILLE x CHUCKY

Image: `griefville_chucky.jpg`

```
GRIEFVILLE x CHUCKY
Survival horror experience built around Universal's Chucky IP.
RocketRide × ON3D × Roblox Game Fund × Universal · Roblox / Luau
Lead Game Developer @ ON3D

• Owned software architecture and CI/CD pipelines
• Led the dev team to ship a high-quality branded live game
• Built core gameplay and multiplayer systems
```

Link: `https://www.youtube.com/watch?v=zM9dbxSiI8g`

---

### Card 05 — DORFS

Image: `dorfs.jpg`

```
DORFS
Multiplayer party game.
Ravegan · Unity / C#
Lead Developer

• Built the foundational architecture, workflows, and CI/CD pipelines
• Mentored junior developers and led code reviews
• Led the technical direction of the project
```

Link: `https://store.steampowered.com/app/1707790/Dorfs_Hammers_for_Hire/`

---

### Card 06 — FRONTLINES VERSUS

Image: `frontlines_versus.jpg`

```
FRONTLINES VERSUS
Cross-platform PvP shooter.
MAXIMILLIAN × Roblox Game Fund · Roblox / Luau
Consultant

• Technical consultancy and mentoring for the team
• Delivered performance, stability, and cross-platform shipping
• Built modular AI, quality presets, FTUE, and workflow pipelines
```

Link: `https://www.roblox.com/games/123804558118054`

---

### Card 07 — KOVAAK 2.0: THE META

Image: `kovaak.jpg`

```
KOVAAK 2.0: THE META
FPS Aim Trainer.
The Meta × Ravegan · Unreal Engine / C++
Engine Tools Developer

• Built modular engine tools for Unreal
• Empowered artists and designers with custom tooling
• Improved workflows for the development team
```

Link: `https://store.steampowered.com/app/824270/KovaaKs/`

---

## About Section

### Content

```
I started making games at 13 by modding them. 15+ years later, I'm 
still doing it — except now I lead teams that ship across Unity, Unreal, 
and Roblox, from console releases to branded experiences with Universal.

I care about gameplay that feels right, code that holds up at scale, and 
teams that ship on time. When I'm not coding, I'm probably mentoring 
someone who will.

Currently leading development at Stormward Studios. Always open to 
building something great with a team that values craft.
```

### Skills (mini)

Displayed as tags / chips:

```
Unity / C#    Unreal Engine / C++    Roblox / Luau
Gameplay Programming    Multiplayer & Netcode    Live Operations
Cross-Platform Shipping    Console Porting    Optimization & Profiling
Software Architecture    CI/CD Pipelines    Technical Leadership
```

### Languages

```
Spanish (Native)   ·   English (Advanced)
```

---

## Contact Section

### Header

```
Let's Talk
```

### Content

```
Have a project in mind? Looking for a senior game developer or tech lead? 
I'd love to hear from you.
```

### Links

```
[Email Me]          → mailto:maurojuarezarino@gmail.com
[LinkedIn]          → https://www.linkedin.com/in/mjuareza/
```

---

## Footer

```
© 2026 Mauro Juarez Ariño · Senior Game Developer & Tech Lead    [Back to top ↑]
```

---

## SEO / Meta Tags

```html
<title>Mauro Juarez Ariño — Senior Game Developer & Tech Lead</title>
<meta name="description" content="Senior Game Developer with 9+ years shipping games across Unity, Unreal, and Roblox. Console releases, branded experiences, multiplayer architecture.">

<meta property="og:type" content="website">
<meta property="og:title" content="Mauro Juarez Ariño — Senior Game Developer & Tech Lead">
<meta property="og:description" content="Senior Game Developer with 9+ years shipping games across Unity, Unreal, and Roblox.">
<meta property="og:url" content="https://zeybak.github.io/">
<meta property="og:image" content="https://zeybak.github.io/og_thumbnail.png">

<meta name="twitter:card" content="summary_large_image">
<meta name="twitter:title" content="Mauro Juarez Ariño — Senior Game Developer & Tech Lead">
<meta name="twitter:description" content="Senior Game Developer with 9+ years shipping games across Unity, Unreal, and Roblox.">
<meta name="twitter:image" content="https://zeybak.github.io/og_thumbnail.png">
```

---

## Images Needed

Required for `/images/` folder:

- `teratopia.jpg` — Steam capsule or in-game shot
- `dungeon_gunfight.jpg` — Roblox thumbnail or in-game shot
- `guardians_of_orion.jpg` — Steam capsule (available from WordPress)
- `griefville_chucky.jpg` — YouTube trailer thumbnail
- `dorfs.jpg` — Steam capsule (available from WordPress)
- `frontlines_versus.jpg` — Roblox thumbnail
- `kovaak.jpg` — Steam capsule (available from WordPress)
- `og_thumbnail.png` — 1200x630 image for OG/Twitter sharing (can be a collage of your games or your name + tagline)

Many of these can be sourced from the existing WordPress site.

---

## Implementation Plan

### Step 1: Create GitHub repo

1. Create new public repo named `zeybak.github.io`
2. Enable GitHub Pages from main branch (Settings → Pages → Source: main → / (root))
3. After first push, site will be live at `https://zeybak.github.io/`

### Step 2: Pass spec to Claude Code

Open Claude Code in a new local directory and paste this prompt:

```
I'm building a GitHub Pages portfolio for myself as a senior game developer.
I have a complete spec attached as PORTFOLIO_SPEC_FINAL.md.

Requirements:
1. Single index.html file with embedded CSS + minimal JS
2. Mobile-responsive (breakpoint 768px)
3. Stats counter animation on hero (0 → final number on page load, ~1.5s duration)
4. Smooth scroll for nav links
5. Projects in a 2-column grid on desktop, 1 column on mobile
6. Cards should be minimalist (NOT huge — small images, tight typography)
7. All "See More" links open in new tab (target="_blank" rel="noopener")
8. Match the exact color palette and typography from the spec
9. Include all SEO meta tags from the spec
10. The site should feel like the existing WordPress (https://maurojuareza.wordpress.com/) 
    but more polished, with the visual style of the CV (navy header, clean typography, 
    subtle backgrounds)

Reference for inspiration (DON'T copy 1:1, but similar vibe):
- https://diego-wechselberg.github.io/

I'll provide the images separately. Use placeholder boxes with project names for now.

Focus on clean execution. Don't add features not in the spec. Don't over-engineer.
```

### Step 3: Iterate

Once Claude Code generates the first draft:
1. Open `index.html` in browser
2. Iterate visually with Claude Code (typography, spacing, colors)
3. Add real images once happy with layout
4. Push to GitHub when ready

### Step 4: Deploy

```bash
git add .
git commit -m "Initial portfolio"
git push origin main
```

Site will be live at `https://zeybak.github.io/` within a minute.

---

## Future Considerations (post-launch)

- **Custom domain**: Si en el futuro querés `maurojuareza.com`, comprás el dominio y lo apuntás a GitHub Pages. El portfolio sigue intacto.
- **Blog**: Tu WordPress tenía blog entries (UE4 tutorials, etc.). Si querés revivirlo, podés agregar una sección `/blog/` con MD files.
- **GitHub link**: Si en algún momento decidís agregar GitHub a contact, es 1 línea en el spec.
- **Más proyectos**: Si shippeás Run Or Die! o nuevos juegos, agregás cards.
