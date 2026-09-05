# ✦ Housewarming Invitation

### Akbar Ali & Nabla

A premium, mobile-first digital invitation created for the housewarming ceremony at **Chakkipparamban House**.

---

## 🌐 Live Invitation

### [Open the Invitation →](https://muneeb-pt.github.io/Invitation-Website/)

**Event**

> 06 September 2026  
> 4 PM — 8 PM  
> Pandikkad, Velluvangad

---

## ✨ Experience

This isn't designed as a traditional static invitation.

It is a cinematic mobile-first invitation experience featuring:

- ✦ Premium luxury editorial design
- ◇ 3D perspective interactions
- ◇ Touch-responsive card movement
- ◇ Multi-directional scroll animations
- ◇ Depth-based entrance animations
- ◇ 3D rotation transitions
- ◇ Back-to-front scaling
- ◇ Left / right / diagonal reveals
- ◇ Blur-to-focus transitions
- ◇ Animated golden particles
- ◇ Rotating decorative orbits
- ◇ Cinematic opening loader
- ◇ Scroll progress indicator
- ◇ Live countdown
- ◇ Google Maps directions
- ◇ Responsive mobile layout
- ◇ Desktop enhancement
- ◇ Safe-area support for modern phones
- ◇ Reduced-motion accessibility support
- ◇ Open Graph social preview

---

## 💌 Invitation

> **YOU ARE WARMLY INVITED TO OUR**
>
> # HOUSEWARMING
> ### Ceremony
>
> **AT OUR NEW HOME**
>
> **Chakkipparamban House**
>
> **WITH LOVE**
>
> **Akbar Ali & Nabla**
>
> **06 SEPTEMBER 2026**
>
> **4 PM TO 8 PM**
>
> **PANDIKKAD, VELLUVANGAD**
>
> Your presence will make our day even more special.
>
> **PLEASE GRACE US WITH YOUR PRESENCE**

---

## 🎬 Motion System

The invitation uses several different motion states instead of one generic fade animation.

### From Left

Cards enter from outside the viewport while rotating in 3D.

```text
←───────────────┐
                │
                │  CARD
                │

From Right

                ┌───────────────→
                │
             CARD
                │

From Back

Elements begin deep inside the 3D scene and grow toward the visitor.

        ·
      ·   ·
    [ CARD ]

Rotation

Cards combine:

- translate
- rotateX
- rotateY
- rotateZ
- scale
- blur

to create a cinematic entrance.

Stagger

Individual cards intentionally enter at different moments rather than moving simultaneously.

---

📱 Mobile First

The website is specifically designed around phone screens.

The layout uses:

- "100svh"
- responsive "clamp()" typography
- safe-area support
- touch interaction
- narrow-screen breakpoints
- overflow protection
- responsive cards
- mobile-friendly buttons

The invitation remains comfortable on small phones while expanding naturally on tablets and desktop screens.

---

📍 Venue

Pandikkad, Velluvangad

"Open Location in Google Maps" (https://maps.app.goo.gl/SJsyKaQeRbm8jcac9?g_st=ac)

---

🛠️ Technology

Built with:

- HTML5
- CSS3
- Vanilla JavaScript
- CSS 3D transforms
- Intersection Observer API
- Responsive Web Design
- GitHub Actions
- GitHub Pages

No frontend framework is required.

---

🚀 Deployment

The site is automatically deployed using GitHub Actions.

Every push to:

main

triggers:

Checkout
   ↓
Configure GitHub Pages
   ↓
Upload Website
   ↓
Deploy

GitHub Pages then publishes the project site.

---

🗂️ Structure

Invitation-Website/
│
├── index.html
├── og-preview.png
├── README.md
│
└── .github/
    └── workflows/
        └── pages.yml

---

🖼️ Social Preview

The website includes Open Graph metadata so supported social platforms can use:

og-preview.png

as the preview image when the invitation URL is shared.

Preview URL:

https://muneeb-pt.github.io/Invitation-Website/

---

👨‍💻 Crafted By

Muneeb PT

GitHub:

https://github.com/Muneeb-PT

LinkedIn:

https://www.linkedin.com/in/mohammed-muneeb-pt

---

❤️ Made With Love

A small digital experience for a beautiful new beginning.

Chakkipparamban House • 2026

