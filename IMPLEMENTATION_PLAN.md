# ICG Website Mockup — Full Implementation Plan

**Inspired Creative Group Inc. — Portfolio Build & Technical Implementation**
**Date:** January 31, 2026 | **Version:** 1.0

---

## Table of Contents

1. [Executive Summary](#1-executive-summary)
2. [Portfolio Section Build](#2-portfolio-section-build)
3. [Testimonials Integration](#3-testimonials-integration)
4. [Technical Implementation](#4-technical-implementation)
5. [Content Gaps & Recommendations](#5-content-gaps--recommendations)
6. [Asset Inventory](#6-asset-inventory)
7. [Implementation Timeline](#7-implementation-timeline)

---

## 1. Executive Summary

This plan covers the full implementation of the ICG website mockup, focusing on:
- Curating 15 portfolio projects into a high-impact presentation for high-ticket clients ($15K-$50K+ projects)
- Integrating approved testimonials from the messaging framework
- Technical setup (Formspree, Vimeo embed, GitHub Pages deployment)
- Identifying content gaps and Phase 2 recommendations

### Data Sources Used
- **Live Wix site**: All 15 project pages scraped with full descriptions and image inventories
- **LinkedIn profile**: 10 recent posts from Juan Valencia showing AI production capabilities
- **Google Drive**: Approved messaging framework v2 and testimonials draft
- **Existing mockup**: `index.html` (v1) with hero, about, services, AI innovation, and contact sections

---

## 2. Portfolio Section Build

### 2A. Curated Project List (Tiered for High-Ticket Impact)

#### 🏆 TIER 1 — Hero Features (Carousel/Full-Width Cards)
These projects lead with brand recognition and measurable outcomes.

| # | Project Name | Client | Category Tags | Why It's Tier 1 |
|---|---|---|---|---|
| 02 | **Warner Brothers — Scooby Doo & Looney Tunes Game** | Warner Bros. | `Interactive` `Design` | Fortune 500 IP, global entertainment brand, demonstrates handling of strict brand standards |
| 06 | **Rogers/Chrysler — Advertorial Magazines** | Rogers + Chrysler + Ontario Tourism Board | `Design` `Print` | Triple-brand partnership, distributed in national magazines (Money Sense, Chatelaine, Maclean's, Today's Parent) |
| 05 | **The Happy Baker — Award-Winning Cookbook** | Erin Bolger / Harlequin | `Design` `Print` `Branding` | Gourmand World Cookbook Award, NYT Top 10 Cookbooks, Harlequin US distribution — concrete proof of results |
| 01 | **Nutrabolics — SuperNova Commercial** | Nutrabolics | `Video` `Audio` `Production` | Full commercial production, demonstrates end-to-end video capability |
| 11 | **Doublemint — Commercial** | Wrigley's/Mars | `Video` `Audio` `Music` | Global consumer brand (Mars Inc.), creative direction + full production — instant brand credibility |

#### 🥈 TIER 2 — Strong Secondary (Standard Cards with Detail Pages)
These show breadth and business results.

| # | Project Name | Client | Category Tags | Why It's Tier 2 |
|---|---|---|---|---|
| 04 | **Titan Development — Emerald Beach Residences** | Titan Development | `Design` `Web` `Print` `Branding` | Luxury real estate in Panama, full branding + marketing collateral |
| 12 | **Professional Rubber Sealants — Brand Launch to Acquisition** | Confidential (sold to international brand) | `Branding` `Web` `Design` | Ground-up brand creation → Home Depot distribution → acquired by international brand. Best business outcome story |
| 13 | **Nalu Retreat and Nordic Spa** | Nalu Retreat | `Design` `Web` `Social Media` `Video` | Current client, Nova Scotia favorite destination, ongoing relationship |
| 15 | **Yousician For Schools** | Yousician | `Program Management` `Education` | International scope (Helsinki), 10 schools, scalable model — shows versatility beyond design |

#### 🥉 TIER 3 — Supporting Grid (Thumbnail-Only, Click to Expand)
These round out the portfolio showing breadth.

| # | Project Name | Client | Category Tags |
|---|---|---|---|
| 14 | **Kinap Athletic Club** | Kinap Athletic Club | `Branding` `Web` `Social Media` |
| 10 | **Guitar Starz Club** | Guitar Starz Club (co-founded) | `Branding` `Education` `Events` |
| 03 | **Motorcycle Wars — Promo Video** | Web Series | `Video` `Audio` `Music` |
| 07 | **B. Teepee — B.Toys Commercial** | B.Toys | `Video` `Post-Production` |
| 08 | **You Are Driving Me Crazy — Short Film** | Short Film | `Audio` `Music` `Sound Design` |
| 09 | **DASIT — Corporate Video** | DASIT | `Audio` `Music` `Sound Design` |

### 2B. NEW: AI Production Showcase (From LinkedIn Content)

Juan's LinkedIn reveals significant AI production capabilities that should be featured prominently. These are NEW portfolio pieces not on the current site:

| Post | Description | Engagement | Category | Asset Type |
|---|---|---|---|---|
| **Nalu Retreat AI Video** | 88-second video produced with zero traditional software — "No Premiere, No After Effects, No Pro Tools" — using Claude Code agentic orchestration | 12 reactions | `AI-Enhanced` `Video` | LinkedIn video/Vimeo |
| **Boxing Day Reflection** | Full AI-produced video using Claude Agents, Kling AI 2.6 Pro, Veo 3.1, Suno AI | 13 reactions, 7 comments | `AI-Enhanced` `Video` `Music` | LinkedIn video |
| **Uncle Eddie Birthday Video** | Custom AI-generated music video demonstrating Agentic Multimedia Production Suite | 11 reactions | `AI-Enhanced` `Video` `Music` | LinkedIn video |
| **Dad's 1950s Photo Animation** | Historic photo brought to life using Claude Code agent capabilities | 10 reactions | `AI-Enhanced` `Video` | LinkedIn video |
| **Sound Effects Extraction Demo** | 36 samples extracted in under 2 minutes using Claude Agent Skills | 6 reactions, 5 comments | `AI-Enhanced` `Audio` | LinkedIn video |
| **Suno AI Music Workflow** | Professional music generation from natural language | 22 reactions, 23 comments (highest engagement) | `AI-Enhanced` `Music` | LinkedIn video |

**Recommendation:** Create an "AI Innovation Showcase" sub-section within portfolio featuring 3-4 of these, with the Nalu Retreat video as the hero (it's a real client deliverable).

### 2C. Category Tags for Filtering

```
Design        → Projects 02, 04, 05, 06, 12, 13, 14
Video         → Projects 01, 03, 07, 08, 09, 11, + AI pieces
Audio         → Projects 01, 03, 07, 08, 09, 11
Interactive   → Project 02
Branding      → Projects 04, 05, 10, 12, 13, 14
AI-Enhanced   → Nalu AI video, Boxing Day, Uncle Eddie, Dad's photo, Sound FX, Suno
```

### 2D. Recommended Portfolio Page Layout

```
┌─────────────────────────────────────────────────────┐
│  PORTFOLIO HERO                                      │
│  "From broadcast networks to video games,            │
│   from startups to Fortune 500 brands."              │
│                                                      │
│  [All] [Design] [Video] [Audio] [AI-Enhanced]        │
│  Category filter pills                               │
├─────────────────────────────────────────────────────┤
│  ┌──────────────────────────────────────────────┐   │
│  │  HERO REEL — Vimeo Embed                     │   │
│  │  https://vimeo.com/1122018207?fl=tl&fe=ec    │   │
│  └──────────────────────────────────────────────┘   │
├─────────────────────────────────────────────────────┤
│  FEATURED WORK (Tier 1 — Large Cards)                │
│  ┌─────────────┐  ┌─────────────┐                   │
│  │ Warner Bros  │  │ Rogers/     │                   │
│  │ Scooby Doo   │  │ Chrysler    │                   │
│  └─────────────┘  └─────────────┘                   │
│  ┌─────────────┐  ┌─────────────┐                   │
│  │ Happy Baker  │  │ SuperNova   │                   │
│  │ Cookbook      │  │ Commercial  │                   │
│  └─────────────┘  └─────────────┘                   │
├─────────────────────────────────────────────────────┤
│  MORE WORK (Tier 2 — Medium Cards, 3-up Grid)        │
│  ┌────────┐  ┌────────┐  ┌────────┐                 │
│  │Doublem.│  │Emerald │  │Sealants│                 │
│  ├────────┤  ├────────┤  ├────────┤                 │
│  │Nalu    │  │Yousic. │  │        │                 │
│  └────────┘  └────────┘  └────────┘                 │
├─────────────────────────────────────────────────────┤
│  AI INNOVATION SHOWCASE                              │
│  "See what's possible when 20 years meets 40 agents" │
│  ┌────────┐  ┌────────┐  ┌────────┐                 │
│  │Nalu AI │  │Boxing  │  │Suno AI │                 │
│  │Video   │  │Day     │  │Music   │                 │
│  └────────┘  └────────┘  └────────┘                 │
├─────────────────────────────────────────────────────┤
│  ADDITIONAL WORK (Tier 3 — Small Grid, 4-up)         │
│  ┌──────┐ ┌──────┐ ┌──────┐ ┌──────┐               │
│  │Kinap │ │Guitar│ │Moto  │ │B.Toys│               │
│  └──────┘ └──────┘ └──────┘ └──────┘               │
│  ┌──────┐ ┌──────┐                                  │
│  │Film  │ │DASIT │                                  │
│  └──────┘ └──────┘                                  │
└─────────────────────────────────────────────────────┘
```

### 2E. Project Detail Descriptions (Copy-Ready)

**Warner Brothers — Scooby Doo & Looney Tunes Game**
> Designed and produced assets for Warner Brothers' Scooby Doo! & Looney Tunes Cartoon Universe: Adventure — a licensed video game distributed on Steam. Working with globally recognized IP required strict adherence to brand standards across every deliverable.
> 
> *Categories: Interactive Design, Brand Compliance*

**Rogers/Chrysler — Advertorial Magazines**
> Selected by Rogers in partnership with Chrysler and the Ontario Tourism Board to create five advertorial mini-magazines. Distributed with Money Sense, Chatelaine, Today's Parent, and Maclean's magazines — reaching millions of Canadian readers.
> 
> *Services: Art direction, design, photography direction, print production & management*

**The Happy Baker — Award-Winning Cookbook**
> Created the complete branding, designed and produced the 160-page cookbook, art directed the photography, and built the press kit and website for Erin Bolger's "A Dater's Guide to Emotional Baking." The result: a GOURMAND World Cookbook Award, New York Times Top 10 Cookbooks of the Year, and distribution across the U.S. through Harlequin.
> 
> *Services: Branding, book design & production, art direction, web design, press kit*

**Nutrabolics — SuperNova Commercial**
> Produced the SuperNova commercial for Nutrabolics in association with Eizzof Entertainment. Full video production including creative direction, filming, editing, sound design, and music production.
> 
> *Services: Video production, sound design, music*

**Doublemint — Commercial**
> Creative direction and full production of a Doublemint commercial for Wrigley's — including video production, sound design, and original music production.
> 
> *Services: Creative direction, video production, sound design, music production*

**Titan Development — Emerald Beach Residences**
> Created all branding and marketing collateral for Panama's luxurious Emerald Private Beach Residences. A comprehensive project spanning art direction, web design, production, and print management.
> 
> *Services: Art direction, web design, production, print production & management*

**Professional Rubber Sealants — From Launch to Acquisition**
> Ground-up brand creation for a line of professional rubber sealants and industrial cleaners. Developed all branding, collateral, trade show displays, directed photoshoots, and designed and managed the website. The marketing success led to products being sold on The Home Depot online and ultimately acquired by an international brand.
> 
> *Services: Branding, collateral, trade show, photography, web design & management*

**Nalu Retreat and Nordic Spa**
> Ongoing collaboration shaping the brand, web, and social media presence for Nalu Retreat — quickly becoming a Nova Scotia favourite destination. Includes AI-enhanced video production using our agentic orchestration system.
> 
> *Services: Art direction, web design, social media, video editing, print*

**Yousician For Schools**
> Managed a six-month pilot program across ten Helsinki elementary schools, delivering instruments, software licenses, and hardware resources. Developed educator workshops, instructional video resources, and a scalable framework for technology-enhanced music education.
> 
> *Services: Program management, educator training, promotional materials, event production*

---

## 3. Testimonials Integration

### 3A. Approved Testimonials (From Google Drive)

**Testimonial 1 — Corporate/Brand Client** ⭐ RECOMMENDED FOR HOMEPAGE
> "We needed five advertorial magazines created simultaneously for a major multi-brand campaign. The team delivered all five on time, on brand, and the art direction elevated what could have been standard advertorials into pieces our readers actually wanted to keep. That's rare."
> 
> **— Marketing Director, National Media Partnership Campaign**
> *Context: Rogers/Chrysler/Ontario Tourism Board project*

**Testimonial 2 — Entertainment/Gaming**
> "Working with licensed IP means zero room for error — every frame has to meet brand standards. They understood that from day one and delivered work that Warner approved without major revisions. For anyone who's worked with big licensors, you know how rare that is."
> 
> **— Executive Producer, Video Game Development Studio**
> *Context: Warner Brothers Scooby Doo & Looney Tunes project*

**Testimonial 3 — Creative Entrepreneur** ⭐ STRONGEST (Real Name)
> "I came to them with a cookbook concept and left with a Gourmand World Cookbook Award and a New York Times Top 10 selection. They didn't just design a book — they created an entire brand identity, art directed the photography, and built everything from the press kit to the website. The attention to detail was exceptional."
> 
> **— Erin Bolger, Author, "A Dater's Guide to Emotional Baking" (The Happy Baker)**

**Testimonial 4 — Broadcast Network**
> "When you're producing content for multiple networks simultaneously, you need a team that understands broadcast standards cold. They delivered clean, broadcast-ready assets every time — which meant we could focus on the creative instead of the technical."
> 
> **— Post-Production Supervisor, Cable Network Programming**
> *Context: Discovery Channel, HGTV, National Geographic work*

### 3B. Display Recommendations

- **Homepage:** Show 3 testimonials in a carousel — prioritize #3 (Erin Bolger, real name), #1 (corporate scale), and #2 (Warner Bros brand recognition)
- **Testimonial #4:** Reserve for Services page or About page
- **Layout:** Card-based with quote marks, horizontal carousel or 3-column grid
- **Enhancement:** Add professional avatar placeholders (generic headshots) where real photos unavailable

---

## 4. Technical Implementation

### 4A. Formspree Contact Form Setup

The existing mockup has a qualifying contact form. For the GitHub Pages deployment:

```html
<form action="https://formspree.io/f/{FORM_ID}" method="POST">
  <input type="text" name="name" placeholder="Your Name" required>
  <input type="email" name="email" placeholder="Email" required>
  <input type="text" name="company" placeholder="Company (Optional)">
  
  <select name="service" required>
    <option value="">What are you looking for?</option>
    <option value="video">Video Production</option>
    <option value="audio">Music & Audio</option>
    <option value="design">Design & Branding</option>
    <option value="campaign">Full Campaign</option>
    <option value="ai">AI Consulting</option>
    <option value="unsure">Not Sure Yet</option>
  </select>
  
  <select name="timeline">
    <option value="">Timeline?</option>
    <option value="asap">ASAP</option>
    <option value="1-2weeks">1-2 Weeks</option>
    <option value="1month">1 Month</option>
    <option value="exploring">Just Exploring</option>
  </select>
  
  <select name="budget">
    <option value="">Budget Range?</option>
    <option value="under5k">Under $5K</option>
    <option value="5k-15k">$5K - $15K</option>
    <option value="15k-50k">$15K - $50K</option>
    <option value="50k+">$50K+</option>
    <option value="discuss">Let's Discuss</option>
  </select>
  
  <textarea name="message" placeholder="Tell us about your project"></textarea>
  <button type="submit">Schedule a Discovery Call</button>
</form>
```

**Setup Steps:**
1. Create account at https://formspree.io
2. Create new form → get form endpoint ID
3. Replace `{FORM_ID}` in form action URL
4. Configure email notifications to go to Juan's email
5. Optional: Set up auto-responder

### 4B. Vimeo Video Embed

```html
<div class="video-container" style="padding:56.25% 0 0 0;position:relative;">
  <iframe 
    src="https://player.vimeo.com/video/1122018207?h=&badge=0&autopause=0&player_id=0&app_id=58479"
    frameborder="0" 
    allow="autoplay; fullscreen; picture-in-picture; clipboard-write; encrypted-media"
    style="position:absolute;top:0;left:0;width:100%;height:100%;"
    title="ICG Showreel">
  </iframe>
</div>
<script src="https://player.vimeo.com/api/player.js"></script>
```

**Placement:** Top of Portfolio section, before featured projects grid.

### 4C. GitHub Pages Deployment

```bash
# 1. Initialize repo (already done at /Users/claudiabot/clawd/icg-mockup)
cd /Users/claudiabot/clawd/icg-mockup

# 2. Ensure .nojekyll exists (prevents Jekyll processing)
touch .nojekyll

# 3. Add CNAME if using custom domain (optional)
# echo "mockup.inspiredcreativegroupinc.com" > CNAME

# 4. Commit and push
git add -A
git commit -m "Portfolio build + implementation plan"
git push origin main

# 5. Enable GitHub Pages in repo settings:
#    Settings → Pages → Source: Deploy from branch → main → / (root)
#    Save → Site will be live at https://[username].github.io/icg-mockup/
```

**Custom Domain (Optional):**
- Add CNAME record in DNS pointing to `[username].github.io`
- Add CNAME file to repo root
- Enable "Enforce HTTPS" in GitHub Pages settings

### 4D. Location Update

Update footer and contact section:

```
Halifax, Nova Scotia · Working Globally
```

Current site says: `© 2026 Inspired Creative Group Inc.`

Updated footer should read:
```
© 2026 Inspired Creative Group Inc.
Halifax, Nova Scotia · Working Globally
```

---

## 5. Content Gaps & Recommendations

### 5A. What's Missing vs. Competitor Agencies

| Gap | Current State | Competitor Standard | Priority |
|---|---|---|---|
| **Portfolio with real names** | Generic "Project 01-15" | Named clients with results | 🔴 Critical |
| **Case studies** | None | 2-3 detailed writeups with process/results | 🟡 Phase 2 |
| **Video showreel** | None on site | Above-the-fold hero reel | 🔴 Critical (have Vimeo link) |
| **Client logos** | None | Logo bar with recognized brands | 🔴 Critical (in mockup) |
| **Testimonials** | None | 3-4 with real names where possible | 🔴 Critical (have copy) |
| **Process explanation** | None | "How We Work" section | 🟡 Phase 2 |
| **Pricing indicators** | None | Budget ranges or "Starting at" signals | 🟢 Phase 3 |
| **Blog/Insights** | None | Thought leadership content | 🟢 Phase 3 |
| **AI demo/samples** | Only on LinkedIn | Interactive demos or video walkthrough | 🟡 Phase 2 |
| **SEO meta tags** | Basic | Full schema markup, OG tags | 🟡 Phase 2 |

### 5B. Phase 2 Recommendations

1. **Case Studies (2-3 detailed):**
   - The Happy Baker → Full process story (brief → design → photography → awards)
   - Rogers/Chrysler → Scale story (5 magazines, multi-brand coordination)
   - Nalu Retreat → Modern capability story (traditional + AI production)

2. **AI Production Demo Page:**
   - Embed the Nalu AI video ("No Premiere, No After Effects, No Pro Tools")
   - Side-by-side comparisons: Traditional vs. AI-enhanced workflow
   - Timeline visualization: "88 seconds of content, produced in X hours vs. X days"

3. **Blog/Insights Section:**
   - Repurpose Juan's LinkedIn posts as blog articles
   - Topics: "How AI Changes Production Workflows", "Why Experience Still Matters in AI"
   - SEO value: target "AI video production", "AI creative agency" keywords

4. **Interactive Elements:**
   - Budget calculator: "Estimate your project"
   - Service selector quiz: "What do you need?"
   - Before/after slider for design work

### 5C. SEO Considerations

**Target Keywords:**
- Primary: "creative production agency", "AI video production"
- Secondary: "Halifax creative agency", "video production Nova Scotia"
- Long-tail: "AI-enhanced creative production", "broadcast production agency AI"
- Service-specific: "commercial video production", "brand design agency", "AI music production"

**Technical SEO:**
```html
<!-- Add to each page -->
<meta name="robots" content="index, follow">
<meta property="og:title" content="Inspired Creative Group — Production Expertise Meets AI Innovation">
<meta property="og:description" content="20+ years of award-winning creative production. 40 AI agents. Design, video, audio, and AI innovation for brands that demand excellence.">
<meta property="og:image" content="[og-image-url]">
<meta property="og:type" content="website">
<link rel="canonical" href="https://www.inspiredcreativegroupinc.com">

<!-- Schema markup -->
<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "ProfessionalService",
  "name": "Inspired Creative Group Inc.",
  "description": "Award-winning creative production agency combining 20+ years of design, video, and audio expertise with AI-powered innovation.",
  "address": {
    "@type": "PostalAddress",
    "addressLocality": "Halifax",
    "addressRegion": "Nova Scotia",
    "addressCountry": "CA"
  },
  "url": "https://www.inspiredcreativegroupinc.com",
  "sameAs": [
    "https://www.linkedin.com/in/juanvalenciaproduction/",
    "https://vimeo.com/inspiredcreativegroup"
  ]
}
</script>
```

---

## 6. Asset Inventory

### 6A. Logo & Branding

| Asset | URL | Usage |
|---|---|---|
| ICG Logo (PNG) | `https://static.wixstatic.com/media/26f8ac_b3541cd1a3124ff1b5867fe934ca0051~mv2.png` | Navigation bar, footer |
| Homepage BG/Brand Element | `https://static.wixstatic.com/media/26f8ac_268a85868c194f1f8a4f56b40946481d~mv2.png` | Homepage hero or brand element |
| Homepage Brand Element 2 | `https://static.wixstatic.com/media/26f8ac_379e5d4e7bd74f16a2f08139665ed6d7~mv2.png` | Homepage |
| Homepage Brand Element 3 | `https://static.wixstatic.com/media/26f8ac_e892585ee6c9445c8243f98b510ce001~mv2.png` | Homepage |

### 6B. Portfolio Thumbnails (from /work Page Grid)

| Project | Thumbnail Alt Text | Wix CDN Base URL |
|---|---|---|
| 01 - Nutrabolics | 02.png | `https://static.wixstatic.com/media/26f8ac_3defd92260fd42e8bba9facd5634ae2a~mv2.png` |
| 02 - Warner Bros | Screen Shot (video game) | `https://static.wixstatic.com/media/26f8ac_e092a356d22942559f92900e41954ca0~mv2.png` |
| 03 - Motorcycle Wars | Screen Shot (motorcycle) | `https://static.wixstatic.com/media/26f8ac_9c56b65160bd4d0a96ea5e8a1a28a85f~mv2.png` |
| 04 - Emerald Beach | emerald1-750x500.jpg | `https://static.wixstatic.com/media/26f8ac_4c4fa06c0f9b4714b17a0a0b09770e3d~mv2.jpg` |
| 05 - Happy Baker | hb01.jpg | `https://static.wixstatic.com/media/26f8ac_9274f592075e47fc86a3a553477ad743~mv2.jpg` |
| 06 - Rogers/Chrysler | Mag01.jpg | `https://static.wixstatic.com/media/26f8ac_5994867edbfd4b9d9966c3539fa6466f~mv2.jpg` |
| 07 - B.Toys | Screen Shot (B.Toys) | `https://static.wixstatic.com/media/26f8ac_9041c5728b32434980cacb986f1abb12~mv2.png` |
| 08 - Short Film | Screen Shot (film) | `https://static.wixstatic.com/media/26f8ac_b9a26aa43d0e422cb33508c18003ae40~mv2.png` |
| 09 - DASIT | Screen Shot (DASIT) | `https://static.wixstatic.com/media/26f8ac_cd58bfe29d6446c6930204c3a7217ae8~mv2.png` |
| 10 - Guitar Starz | gsc8.jpg | `https://static.wixstatic.com/media/26f8ac_0f62ca6a91dd42e7b2cc754f00cc3d00~mv2.jpg` |
| 11 - Doublemint | Doublemint Screen.png | `https://static.wixstatic.com/media/26f8ac_a5dead9250d0409f8058d3006b769fa2~mv2.png` |
| 12 - Sealants | group-3.jpg | `https://static.wixstatic.com/media/26f8ac_80a066618d8f4416b9cce810310c7bbd~mv2.jpg` |
| 13 - Nalu Retreat | Nalu Retreat www.jpg | `https://static.wixstatic.com/media/26f8ac_4ddf028805f14fb398b50cecb3ca78fe~mv2.jpg` |
| 14 - Kinap | FB Hiring post.jpg | `https://static.wixstatic.com/media/26f8ac_01a13186bc484755b94c1d4730829233~mv2.jpg` |
| 15 - Yousician | YSFS - screen.png | `https://static.wixstatic.com/media/26f8ac_0dc6a503562e4dbd849d6bf4f27572b8~mv2.png` |

### 6C. Project Detail Page Images (High-Res Content)

See `project-images-detailed.json` for full inventory. Summary:

| Project | Content Images | Notes |
|---|---|---|
| 01 - Nutrabolics | 1 image | Video thumbnail + embedded video |
| 02 - Warner Bros | 1 image | Game screenshot |
| 03 - Motorcycle Wars | 1 image | Video embed |
| 04 - Emerald Beach | 5 images | Brochure spreads, branding materials |
| 05 - Happy Baker | 5 images | Book covers, photography, press kit |
| 06 - Rogers/Chrysler | 2 images | Magazine spreads |
| 07 - B.Toys | 1 image | Commercial still |
| 08 - Short Film | 1 image | Film still |
| 09 - DASIT | 1 image | Video still |
| 10 - Guitar Starz | 8 images | Concert photos, branding, students |
| 11 - Doublemint | 2 images | Commercial stills |
| 12 - Sealants | 12 images | Product photos, trade show, website |
| 13 - Nalu Retreat | 7 images | Website, branding, social media |
| 14 - Kinap | 5 images | Branding, website, social media |
| 15 - Yousician | 0 images | Text-only (needs imagery from LinkedIn) |

### 6D. Team Headshots

| Person | Current Source | Notes |
|---|---|---|
| Sandy Peic | `assets/sandy.jpg` (in mockup) | Extracted from current site |
| Juan Valencia | `assets/juan.jpg` (in mockup) | Extracted from current site |

### 6E. Video Assets

| Video | Source | Usage |
|---|---|---|
| ICG Showreel | `https://vimeo.com/1122018207?fl=tl&fe=ec` | Hero reel, portfolio top |
| SuperNova Commercial | Embedded on Project 01 page (Wix video) | Project detail page |
| Nalu AI Video | LinkedIn post | AI showcase section |
| Boxing Day Video | LinkedIn post | AI showcase section |

### 6F. Image Download Script

```bash
#!/bin/bash
# Download all portfolio thumbnails
mkdir -p assets/portfolio

URLS=(
  "26f8ac_3defd92260fd42e8bba9facd5634ae2a~mv2.png|01-nutrabolics.png"
  "26f8ac_e092a356d22942559f92900e41954ca0~mv2.png|02-warner-bros.png"
  "26f8ac_9c56b65160bd4d0a96ea5e8a1a28a85f~mv2.png|03-motorcycle-wars.png"
  "26f8ac_4c4fa06c0f9b4714b17a0a0b09770e3d~mv2.jpg|04-emerald-beach.jpg"
  "26f8ac_9274f592075e47fc86a3a553477ad743~mv2.jpg|05-happy-baker.jpg"
  "26f8ac_5994867edbfd4b9d9966c3539fa6466f~mv2.jpg|06-rogers-chrysler.jpg"
  "26f8ac_9041c5728b32434980cacb986f1abb12~mv2.png|07-btoys.png"
  "26f8ac_b9a26aa43d0e422cb33508c18003ae40~mv2.png|08-short-film.png"
  "26f8ac_cd58bfe29d6446c6930204c3a7217ae8~mv2.png|09-dasit.png"
  "26f8ac_0f62ca6a91dd42e7b2cc754f00cc3d00~mv2.jpg|10-guitar-starz.jpg"
  "26f8ac_a5dead9250d0409f8058d3006b769fa2~mv2.png|11-doublemint.png"
  "26f8ac_80a066618d8f4416b9cce810310c7bbd~mv2.jpg|12-sealants.jpg"
  "26f8ac_4ddf028805f14fb398b50cecb3ca78fe~mv2.jpg|13-nalu-retreat.jpg"
  "26f8ac_01a13186bc484755b94c1d4730829233~mv2.jpg|14-kinap.jpg"
  "26f8ac_0dc6a503562e4dbd849d6bf4f27572b8~mv2.png|15-yousician.png"
)

for item in "${URLS[@]}"; do
  IFS='|' read -r src dest <<< "$item"
  echo "Downloading $dest..."
  curl -s -o "assets/portfolio/$dest" \
    "https://static.wixstatic.com/media/$src/v1/fill/w_800,h_600,al_c,q_85,enc_auto/file.jpeg"
done

echo "Done! Downloaded ${#URLS[@]} images."
```

---

## 7. Implementation Timeline

### Phase 1 — Core Build (This Sprint)

| Task | Status | Priority |
|---|---|---|
| Add Portfolio section to mockup HTML | 🔲 TODO | 🔴 Critical |
| Integrate 4 testimonials | 🔲 TODO | 🔴 Critical |
| Embed Vimeo showreel | 🔲 TODO | 🔴 Critical |
| Download & optimize all portfolio images | 🔲 TODO | 🔴 Critical |
| Set up Formspree form | 🔲 TODO | 🔴 Critical |
| Update footer with Halifax location | 🔲 TODO | 🟡 Important |
| Deploy to GitHub Pages | 🔲 TODO | 🔴 Critical |
| Add client logos (SVG) | ✅ In mockup (placeholders) | 🟡 Need real SVGs |

### Phase 2 — Content Enhancement (Next Sprint)

| Task | Priority |
|---|---|
| Write 2-3 detailed case studies | 🟡 Important |
| Create AI Innovation showcase section | 🟡 Important |
| Add SEO meta tags and schema markup | 🟡 Important |
| Create "How We Work" process section | 🟢 Nice-to-have |
| Repurpose LinkedIn posts as blog articles | 🟢 Nice-to-have |

### Phase 3 — Optimization

| Task | Priority |
|---|---|
| A/B test CTAs and form fields | 🟢 Future |
| Add analytics (Google Analytics 4) | 🟡 Important |
| Performance optimization (image lazy loading, etc.) | 🟢 Future |
| Create pricing indicators | 🟢 Future |

---

## Appendix: LinkedIn Profile Summary

**Juan Valencia** — Production Director / Co-Founder, Inspired Creative Group Inc.

**Key LinkedIn Findings:**
- **Active poster** with 10+ recent posts focused on AI production capabilities
- **Highest engagement post:** Suno AI music workflow (22 likes, 23 comments, 2 shares)
- **Best client showcase:** Nalu Retreat AI video (12 reactions) — "No Premiere, No After Effects, No Pro Tools"
- **AI tools used publicly:** Claude Code, Kling AI 2.6 Pro, Veo 3.1, Suno AI, Nano Banana Pro
- **Earlier content:** Yousician educator advocacy (2019-2020), showing music education background
- **Key narrative:** "Not AI that learned production — production professionals who built AI tools"

**Recommended LinkedIn-to-Website Pipeline:**
1. Download/re-record the Nalu Retreat AI video for website embed
2. Use the "No traditional software" narrative as AI Innovation page proof point
3. Reference the 7-agent skill creation system in the "The System" section
4. Consider embedding 2-3 LinkedIn video posts directly (or link to them)

---

*Generated January 31, 2026 — Claudia for Inspired Creative Group Inc.*
