# Design System — Aldini v2.4 (Luxury Tech Parody)

## Product Context
- **Quoi** : Landing page parodique haut de gamme reprenant les codes d'une Keynote Apple / High-tech pour présenter et promouvoir Aldini auprès d'un public de 24 à 35 ans via Meta Ads (Instagram & Facebook).
- **Pour qui** : Célibataires et visiteuses sensibles à l'autodérision, au second degré et aux formats créatifs viraux.
- **Espace** : Parodie publicitaire, viral dating landing page, Apple Product Launch mock.
- **Type** : Marketing / Conversion virale (prise de contact WhatsApp & Instagram).
- **Memorable thing** : « Le contraste hilarant entre la perfection visuelle d'une Keynote Apple ultra-sombre et l'absurdité totale des specs d'un homme idéal (sieste 12h, zéro ghosting, avis de la daronne). »

---

## Aesthetic Direction
- **Direction** : Luxury Tech Parody (Dark Mode Apple Keynote, Stripe High-End & Linear App)
- **Décoration** : Intentionnelle & Expressive (halos radiaux fuchsia `#d946ef` et cyan `#06b6d4`, cartes glassmorphism avec bordures subtiles semi-transparentes, micro-reflets lumineux, bento grid technologique, confettis interactifs).
- **Mood** : Élégant, ultra-léché, vivant, surprenant et hilarant dès les premières secondes.
- **Références** : Apple Keynote, Linear, Stripe Press, Arc Browser.

---

## Typography
- **Display / Hero** : `Space Grotesk` (Google Fonts, 700 / 800) — Modernité géométrique, audace futuriste, parfait pour les titres de Keynote.
- **Body / Content** : `Plus Jakarta Sans` (Google Fonts, 400 / 500 / 600) — Lisibilité mobile impeccable, rondeur humaine et contemporaine.
- **Data / Specs / Code** : `JetBrains Mono` (Google Fonts, 500 / 700) — Télémétrie, badges d'état, métriques de rapidité, scores de compatibilité.
- **Loading** : Google Fonts CDN préchargé avec `preconnect`.
- **Scale** :
  - `text-xs` : 12px (télémétrie, badges techniques)
  - `text-sm` : 14px (légendes, détails specs)
  - `text-base` : 16px (corps de texte principal)
  - `text-lg` : 18px (sous-titres de cartes)
  - `text-xl` : 20px (titres de sections secondaires)
  - `text-2xl` : 24px (titres de cartes Bento)
  - `text-3xl` : 30px (titres de rubriques)
  - `text-4xl` : clamp(28px, 4vw, 36px)
  - `text-5xl` : clamp(36px, 6vw, 56px) (Hero Title)

---

## Color
- **Approche** : Expressive sombre maîtrisée (fond OLED ultra-sombre + néons fuchsia/cyan + accents sémantiques).
- **Primary** : `#d946ef` (Fuchsia 500) — Halo principal, CTA d'action, score de compatibilité.
- **Secondary** : `#06b6d4` (Cyan 500) — Métriques techniques, badges d'accréditation, bordures actives.
- **Neutrals** :
  - `#05070c` : Dark OLED Background (fond global immersif)
  - `#0b0f19` : Surface (barre de navigation, sections alternées)
  - `#111726` : Surface Cards (cartes Bento, panneaux de quiz)
  - `#1f293d` : Dark Border (lignes de démarcation nettes et discrètes)
  - `#94a3b8` : Slate 400 (texte secondaire à haut contraste)
  - `#f8fafc` : Slate 50 (texte principal éclatant)
- **Semantic** :
  - Success : `#10b981` (Disponibilité immédiate, Green Flags)
  - Warning : `#f59e0b` (Avis certifiés 5 étoiles, badges VIP)
  - Error / Red Flag : `#f43f5e` (Prétendant ordinaire Tinder)
- **Dark mode** : Natif et permanent (OLED Friendly).

---

## Spacing
- **Base** : 8px
- **Densité** : Confortable avec respirations généreuses (padding 20px à 48px).
- **Scale** : 2xs(2px) · xs(4px) · sm(8px) · md(16px) · lg(24px) · xl(32px) · 2xl(48px) · 3xl(64px) · 4xl(96px).

---

## Layout
- **Approche** : Grid-disciplined & Creative Bento (Bento Grid responsive 1 col mobile / 3-4 cols desktop).
- **Grid** : 1 colonne fluide (360px-480px mobile) → 2 colonnes (tablette) → 3 à 4 colonnes (desktop 1024px+).
- **Max content width** : 1152px (`max-w-6xl`).
- **Border radius** : `sm: 8px`, `md: 12px`, `lg: 16px`, `xl: 20px`, `2xl: 28px`, `full: 9999px`.

---

## Motion & Interactivity
- **Approche** : Vivant & Expressif (Effets sonores Web Audio API doux, confettis Canvas, tabs photos interactifs, compteurs dynamiques de likes, jauge de kebab, quiz animé).
- **Easing** : `cubic-bezier(0.16, 1, 0.3, 1)` pour des entrées ultra-douces style iOS.
- **Durations** : micro (100ms), court (200ms), moyen (300ms), long (500ms).
- **Sons Web Audio API** : Clics pop subtils, carillon de victoire au quiz (désactivables via bouton mute).

---

## SAFE / RISKS Breakdown

### SAFE (Standards de conversion & attentes visiteurs) :
- **Formulaire / Quiz en 3 étapes claires** : Pas d'abandon, sensation de progression rapide.
- **Liens directs WhatsApp & Instagram** : Pas d'inscription compliquée, ouverture immédiate de l'application native.
- **Contraste texte/fond 100% WCAG AA** : Texte blanc éclatant et ardoise claire sur fond noir nuit (`#05070c`).

### RISKS (Ce qui rend Aldini inoubliable & viral) :
- **Parodie Keynote Apple intégrale** : Traiter un humain célibataire comme le nouvel iPhone 17 Pro Max avec des graphiques de télémétrie, des tests de collision émotionnelle et des avis d'experts.
- **Interactivité sonore & confettis** : Déclenche le sourire dès le premier clic, renforce l'immersion et l'envie de partager le lien avec ses amies.
- **Galerie 3 angles d'Aldini en direct** : Photos réelles d'Aldini (`aldini_1.jpg`, `aldini_2.jpg`, `aldini_3.jpg`) intégrées directement dans un module de visionnage haute définition avec switch d'ambiance.

---

## Decisions Log
| Date | Décision | Rationale |
|------|----------|-----------|
| 2026-10-03 | Restauration & sublimation du Premier Design Keynote Apple Dark Mode | Demande explicite de l'utilisateur ("je préfère le premier design, vivant et drôle"). Abandon du thème papier clair pour l'univers sombre néon haute conversion. |
| 2026-10-03 | Intégration native des 3 photos du dossier `photo aldini` | Résolution du problème d'images non chargées (`aldini.jpg`, `aldini_1.jpg`, `aldini_2.jpg`, `aldini_3.jpg`) avec sélecteur de looks. |
| 2026-10-03 | Ajout du moteur sonore Web Audio + animations réactives | Répondre au besoin de site "vivant et drôle" sans alourdir le chargement par des fichiers mp3 externes. |
