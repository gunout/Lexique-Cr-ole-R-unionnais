# 🗣️ Lexique Créole Réunionnais // Source: mi-aime-a-ou.com // Dictionnaire interactif - ( 4600 mots ) *

**Dictionnaire interactif Kréol Rényoné ↔ Français**

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/fr/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/fr/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/fr/docs/Web/JavaScript)
[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-222222?style=for-the-badge&logo=github&logoColor=white)](https://gunout.github.io/Lexique-Cr-ole-R-unionnais/)
[![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen?style=for-the-badge)](https://github.com/gunout/Lexique-Cr-ole-R-unionnais/pulls)
[![Made in La Réunion](https://img.shields.io/badge/Made%20in-La%20Réunion-0055A4?style=for-the-badge)](https://www.regionreunion.com/)

---

## 📖 À propos

**Lexique Créole Réunionnais** est une application web statique offrant un dictionnaire interactif **Kréol Rényoné ↔ Français**. Conçue dans une interface moderne au style *cyberpunk*, elle permet de rechercher, parcourir, prononcer et mettre en favori plus de **2 000 mots et expressions** du patrimoine linguistique réunionnais.

> *« La lang na pwin le zo »* — La langue n'a pas d'os.
> *(Proverbe créole : la parole a peu de valeur)*

<img width="1280" height="1024" alt="Screenshot_2025-11-18_10-56-42" src="https://github.com/user-attachments/assets/abc1836a-913a-409c-b64d-31099d4941a4" />

---

## ✨ Fonctionnalités

- 🔍 **Recherche instantanée** dans les mots créoles
- 🔤 **Navigation alphabétique** (A → Z) avec compteurs
- 🎴 **Double affichage** : grille de cartes / liste compacte
- 🔊 **Synthèse vocale** avec sélection de voix française
- ❤️ **Favoris persistants** (localStorage)
- 🎵 **Lecteur audio intégré** (playlist maloya / séga)
- 📱 **100% responsive** (mobile, tablette, desktop)
- 🌗 **Thème cyberpunk** aux couleurs du drapeau réunionnais
- ⚡ **Aucune dépendance** — HTML/CSS/JS pur

---

## 🚀 Démo en ligne

👉 **[https://gunout.github.io/Lexique-Cr-ole-R-unionnais/](https://gunout.github.io/Lexique-Cr-ole-R-unionnais/)**

---

## 🛠️ Installation locale

```bash
# Cloner le dépôt
git clone https://github.com/gunout/Lexique-Cr-ole-R-unionnais.git
cd Lexique-Cr-ole-R-unionnais

# Ouvrir directement le fichier dans le navigateur
# ou lancer un serveur local :
python3 -m http.server 8000
```

Puis ouvrir [http://localhost:8000](http://localhost:8000) dans votre navigateur.

---

## 📂 Structure du projet

```
Lexique-Cr-ole-R-unionnais/
├── index.html              # Interface principale
├── dictionnaire.js         # Base de données du lexique (~2000 entrées)
├── music/                  # Playlist audio (maloya, séga)
│   ├── maloya.mp3
│   ├── i fo viv.mp3
│   └── star shit.mp3
├── logo-creole.gif         # Logo
└── README.md
```

### Format des données (`dictionnaire.js`)

```javascript
var dictionnaire = {
  "zot": "Eux, leur, vous",
  "zourit'": "Pieuvre",
  "marmay": "Enfant",
  // ...
};
```

---

## 🧬 Sources linguistiques

Ce lexique s'appuie sur plusieurs ressources de référence :

| Source | Description |
|--------|-------------|
| [creole.org](https://www.creole.org/) | Dictionnaire créole en ligne (B. Hoareau) |
| Robert Chaudenson (1972) | *Le lexique du parler créole de La Réunion* — [HAL](https://theses.hal.science/) |
| James S. McDonald (2019) | *Le lexique du créole réunionnais d'origine malgache* — [DUMAS](https://dumas.ccsd.cnrs.fr/) |
| Éducation Nationale | Programmes et lexiques thématiques de créole réunionnais |
| Collectage oral | Expressions, proverbes et dictons populaires |

---

## 🤝 Contribution

Les contributions sont **chaleureusement bienvenues** ! Pour proposer un mot, une correction ou une amélioration :

1. **Fork** le projet
2. Créez votre branche (`git checkout -b feature/nouveau-mot`)
3. Commitez vos changements (`git commit -m 'Ajout : "kourpa" = "hameçon"'`)
4. **Push** vers la branche (`git push origin feature/nouveau-mot`)
5. Ouvrez une **Pull Request**

### Règles de contribution

- ✅ Vérifier l'orthographe créole (graphie *Lékritir 77* de préférence)
- ✅ Indiquer la source (dictionnaire, collectage, informateur)
- ✅ Éviter les doublons
- ❌ Pas de contenu haineux, discriminatoire ou hors-sujet

---

## 📜 Licence

Ce projet est distribué sous licence **MIT**. Voir le fichier [LICENSE](LICENSE) pour plus d'informations.

Le contenu linguistique (mots, définitions, proverbes) reste la propriété intellectuelle de ses auteurs et collecteurs respectifs.

---

## 🙏 Remerciements

- **B. Hoareau** pour [creole.org](https://www.creole.org/) — première ressource en ligne
- **Robert Chaudenson** pour ses travaux fondateurs sur le créole réunionnais
- **Toute la communauté créolophone** qui fait vivre *la lang mèr* 🏝️
- **Vous** qui consultez, corrigez et enrichissez ce lexique ❤️

---

## 📊 Statistiques

![GitHub repo size](https://img.shields.io/github/repo-size/gunout/Lexique-Cr-ole-R-unionnais?style=flat-square)
![GitHub last commit](https://img.shields.io/github/last-commit/gunout/Lexique-Cr-ole-R-unionnais?style=flat-square)
![GitHub commit activity](https://img.shields.io/github/commit-activity/m/gunout/Lexique-Cr-ole-R-unionnais?style=flat-square)
![GitHub stars](https://img.shields.io/github/stars/gunout/Lexique-Cr-ole-R-unionnais?style=flat-square)

---

<div align="center">

**Fait avec ❤️ à La Réunion** 🌋🏝️

*Nout' lang, nout' kiltir, nout' loryan* 🇷🇪

</div>
