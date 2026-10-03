# Plan : Landing Page Parodique « Aldini v2.4 »

> PRD source : docs/PRD.md

## Décisions architecturales

Décisions durables qui s'appliquent à toutes les phases :

- **Routes** : Single Page Application (SPA) avec ancrage fluide (`#hero`, `#specs`, `#comparatif`, `#avis`, `#compatibilite`, `#contact`).
- **Architecture technique** : HTML5 sémantique, Tailwind CSS moderne (couleurs sombres style Apple Dark Mode / OLED, effets glassmorphism), typographies soignées (Plus Jakarta Sans / Satoshi / Inter), icônes vectorielles SVG Lucide, JavaScript vanilla réactif sans dépendances lourdes pour une performance maximale (< 0.8s de chargement dans le navigateur in-app de Meta).
- **Configuration centralisée** : Objet de données dédié `ALDINI_CONFIG` permettant de modifier en 1 clic : numéro WhatsApp, compte Instagram, photos, specs techniques, avis et questions du test de compatibilité.
- **Canaux de contact** : Deep links directs vers WhatsApp (`wa.me`) et Instagram avec message d'accroche personnalisé et pré-rempli.

---

## Phase 1 : Hero Keynote & Socle Visuel Haute Définition

**User stories** : US-1

### Ce qu'on livre

Structure principale de la page avec un design sombre ultra-luxueux inspiré des keynotes Apple :
- Barre de navigation supérieure avec statut dynamique ("⚡ En stock • Disponible pour un date").
- Hero section avec badge produit "NOUVELLE VERSION 2.4", titre percutant, sous-titre d'accroche, carte visuelle centrale avec photo d'Aldini, boutons CTA immédiats ("Réserver un créneau", "Lancer le test de compatibilité").

### Critères d'acceptation

- [ ] La page s'affiche avec une esthétique premium dark mode sans aucun bug d'affichage.
- [ ] Le Hero section présente le nom d'Aldini, son statut et ses premiers arguments percutants.
- [ ] La photo d'Aldini est mise en valeur avec un cadre lumineux subtil (glow effect) et fallback automatique.

## Bloquée par

Aucune — démarrable immédiatement.

---

## Phase 2 : Fiche Technique & Grille Comparative Absurde

**User stories** : US-2, US-3

### Ce qu'on livre

- Bento Grid des spécifications techniques insolites d'Aldini (autonomie sommeil 12h, consommation kebab certifiée, système d'exploitation affectif, tolérance aux discussions existentielles).
- Tableau comparatif officiel et sans pitié : « Aldini v2.4 » face au « Prétendant standard sur Tinder » (critères : ponctualité, honnêteté, humour, compétences culinaires, fidélité).

### Critères d'acceptation

- [ ] La bento grid s'affiche parfaitement sur mobile (1 colonne) et sur desktop (grille équilibrée).
- [ ] Le tableau comparatif met en évidence les victoires écrasantes d'Aldini avec des coches vertes et des croix rouges pour la concurrence.

## Bloquée par

Phase 1

---

## Phase 3 : Preuve Sociale & Avis "Clients" Déjantés

**User stories** : US-4

### Ce qu'on livre

Section de témoignages authentiquement parodiques :
- Note globale "4.9/5 basée sur 3 avis certifiés".
- Avis de sa mère ("Un garçon très poli qui range sa chambre une fois par an").
- Avis de son banquier ("Situation financière stable tant qu'il ne découvre pas un nouveau resto").
- Avis de son meilleur pote / wingman ("Fiable, loyal, mais ne lui confiez jamais la playlist en voiture").

### Critères d'acceptation

- [ ] Cartes d'avis avec étoiles dorées, badge "Achat vérifié" et citation.
- [ ] Effets de survol élégants et lisibilité parfaite sur mobile.

## Bloquée par

Phase 1

---

## Phase 4 : Mini-Quiz d'Affinité Interactif & Conversion Directe

**User stories** : US-5, US-6

### Ce qu'on livre

- Test d'éligibilité interactif en 3 étapes avec questions à choix multiples absurdes.
- Animation de calcul de score en direct avec barre de progression.
- Résultat final : "Compatibilité calculée : 98.4% 🎉".
- Bouton d'action final déclenchant l'ouverture de WhatsApp ou Instagram avec le texte d'accroche pré-rempli.

### Critères d'acceptation

- [ ] L'utilisateur peut répondre aux 3 questions sans rechargement de page.
- [ ] Le score final s'anime de 0% à 98.4%.
- [ ] Le clic sur "Postuler / Envoyer un DM" génère le lien de contact pré-rempli.

## Bloquée par

Phase 1

---

## Phase 5 : Partage Viral & Optimisation Finale Mobile Meta Ads

**User stories** : US-7

### Ce qu'on livre

- Bouton "Partager la fiche d'Aldini" avec copie du lien dans le presse-papier et message toast de confirmation.
- Balises méta complètes (OpenGraph / Twitter Card) pour les aperçus lors du partage sur WhatsApp, Facebook et iMessage.
- Optimisation stricte pour les formats d'écran smartphone (pas de scroll horizontal, haute réactivité tactile).

### Critères d'acceptation

- [ ] La copie de l'URL fonctionne et affiche une alerte discrète temporaire.
- [ ] Le site est 100% responsive et validé sur formats mobile (375px à 430px de largeur).

## Bloquée par

Phases 1, 2, 3, 4
