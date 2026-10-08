Blossom — Interactive Book & Botanical Collection
A little curiosity, a lot of plants, and a digital experience designed to bloom.

Blossom is an interactive website created around a book celebrating the diversity of plants — from tropical foliage to alpine species and desert flora. The project brings the book's identity online through playful motion, a 3D book presentation and an editorial, nature-inspired atmosphere.
Alongside the book introduction, the site includes a poster collection to explore.

Highlights

Interactive 3D book hero presented through an embedded Spline scene.
Immersive visual atmosphere with parallax backgrounds, a custom intro sequence and animated details.
Launch countdown component and a mailing-list sign-up section.
Bilingual content in French and English.
Botanical storytelling through an introduction to the book and its subject.
Poster collection pages connected to a dedicated shop section.

Tech stack

Area	Technologies
Framework	Next.js 14, React 18, TypeScript
Styling	Tailwind CSS
Interactions	Framer Motion, React Scroll Parallax
3D presentation	Spline embed
Analytics	Vercel Analytics

Getting started

```bash
git clone https://github.com/nolhancolas-ctrl/blossom_landing.git
cd blossom_landing
npm install
npm run dev
```

Open http://localhost:3000.

The 3D book presentation is loaded from an external Spline scene, so an internet connection is needed to view that element during development.

Project structure

```text
app/                  Home and shop routes
components/spline/    3D book presentation
components/sections/  Countdown, mailing list and editorial content
components/visual/    Parallax background and splash screen
components/collections/ Poster collection browsing
hooks/                Shared UI state and localization
public/               Visual assets
```

Design approach

A warm, tactile interface that feels closer to turning the pages of an illustrated book than browsing a conventional product website. Motion and depth help create a sense of discovery, while the content remains central.
---

Web design & development: Nolhan Colas · GitHub
