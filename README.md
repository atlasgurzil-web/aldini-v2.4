# ALDINI™ v2.4 — Landing Page Parodique Officielle 🚀

Landing page haute fidélité créée pour promouvoir **Aldini** avec des campagnes Meta Ads (Instagram / Facebook) ciblées sur un public de 24 à 35 ans.

---

## 🌟 Ce qui a été développé

1. **Design Apple Keynote Dark Mode** : Esthétique soignée, typographies modernes (Space Grotesk, Plus Jakarta Sans, JetBrains Mono), reflets glassmorphism, et néons fuchsia/cyan.
2. **Hero Section Immersif** : Carte produit haute définition avec détection automatique de photo et bouton pour changer ou uploader la photo d'Aldini en 1 clic.
3. **Bento Grid des Spécifications** : Autonomie sieste 12h, protocole anti-ghosting < 3 min, gestion des dramas et module cuisine.
4. **Tableau Comparatif Implacable** : *Aldini v2.4* face au *Mec Lambda sur Tinder*.
5. **Preuve Sociale Hilarante** : Avis certifiés de sa daronne (5/5), de son banquier (4/5) et de son meilleur pote (5/5).
6. **Test d'Affinité Interactif (Quiz)** : Questionnaire en 3 étapes avec calcul de score dynamique à 98.4%, pluie de confettis et bouton WhatsApp / Instagram avec message pré-rempli.
7. **Bouton de Partage Viral** : Copie automatique du lien dans le presse-papier avec notification toast.

---

## 📸 Comment afficher ou changer la photo d'Aldini ?

Deux méthodes ultra simples :

### Méthode 1 : Directement depuis le navigateur (Le plus rapide)
1. Ouvrez `index.html` dans votre navigateur (double-clic).
2. Cliquez sur la petite icône **📸 Appareil photo** située en haut à droite de sa photo (ou sur le bouton *« Sélectionner sa photo »* si aucune photo n'est détectée).
3. Choisissez n'importe quelle photo sur votre ordinateur : elle s'affiche instantanément et est mémorisée automatiquement !

### Méthode 2 : Par fichier dans le dossier
Nommez simplement votre photo `aldini.jpg` (ou `aldini.png`, `photo.jpg`) et placez-la dans ce dossier. La page la détectera automatiquement.

---

## 📱 Comment personnaliser son WhatsApp et son Instagram ?

Ouvrez le fichier `index.html` dans votre éditeur et modifiez les lignes 450-465 dans le bloc `ALDINI_CONFIG` :

```javascript
const ALDINI_CONFIG = {
  name: "Aldini (Abdelhafid)",
  birthYear: 1988,
  age: 38, // 38 ans
  whatsappNumber: "213676080176",       // Format international WhatsApp (+213 676 08 01 76)
  instagramUsername: "baccouche_abdelhafid", // Pseudo Instagram officiel
};
```

---

## 📂 Documents de conception
- `docs/PRD.md` : Cadrage produit complet validé
- `docs/PLAN.md` : Plan d'implémentation découpé en phases
- `docs/DESIGN.md` : Spécification complète du design system
- `docs/design-preview.html` : Prévisualisation des composants et de la palette
