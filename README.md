# 🤖 Arduino Fun Lab — LingoLab Academy

**Un laboratoire ludique d'initiation à l'électronique et à la programmation, conçu pour apprendre en s'amusant.**

Dirigé par **Dr. Chikh Mohamed Amine**
📍 LingoLab Academy — Relizane, Algérie

---

## 🎯 À propos de ce repository

Ce dépôt regroupe l'ensemble des projets pédagogiques Arduino développés dans le cadre du programme **Arduino Fun Lab** de LingoLab Academy. Chaque projet est pensé pour être réalisé avec un enfant ou un débutant complet : matériel accessible, montages progressifs, code commenté ligne par ligne, et petits défis pour aller plus loin.

L'objectif du Fun Lab n'est pas seulement de faire clignoter une LED, mais de construire une **intuition physique et logique** : comprendre ce qu'est un capteur, une sortie, une condition, une conversion de valeurs — à travers des objets concrets et amusants.

---

## 📚 Les Projets

| # | Projet | Composants clés | Fichier |
|---|---|---|---|
| 1 | 🌤️ [La Station Météo de Lumière](./station-meteo-lumiere.md) | LDR, écran LCD, potentiomètre (contraste) | `station-meteo-lumiere.md` |
| 2 | 🌙 [La Veilleuse Intelligente](./veilleuse-intelligente.md) | LDR, LED (PWM) | `veilleuse-intelligente.md` |
| 3 | 🔆 [Le Variateur d'Intensité (Dimmer)](./dimmer-variateur.md) | Potentiomètre, LED (PWM) | `dimmer-variateur.md` |
| 4 | 📊 [Le Tableau de Bord Interactif](./tableau-de-bord.md) | Potentiomètre, LED, écran LCD | `tableau-de-bord.md` |

Chaque fiche projet contient :
- 🎯 Le concept expliqué simplement
- 🧰 La liste du matériel nécessaire
- 🔌 Un schéma **breadboard** (vue physique du montage)
- 🔌 Un schéma **électrique** (câblage logique)
- 💻 Le code Arduino complet et commenté
- 💡 Des idées d'activités et de défis à faire avec l'enfant
- 🔧 Un tableau de dépannage rapide

---

## 🧭 Progression pédagogique recommandée

Les projets sont classés du plus simple au plus complet, chacun réutilisant les acquis du précédent :

```
1. Variateur d'Intensité  →  Potentiomètre + LED (le plus simple)
        ↓
2. Veilleuse Intelligente →  Capteur de lumière (LDR) + LED
        ↓
3. Station Météo de Lumière → Écran LCD + capteur de lumière
        ↓
4. Tableau de Bord Interactif → Synthèse : LCD + potentiomètre + LED
```

> 💡 Conseil pédagogique : commencer par le Variateur d'Intensité permet à l'enfant de comprendre le rôle du potentiomètre et du PWM avant d'aborder les capteurs et l'affichage LCD, qui sont introduits progressivement dans les projets suivants.

---

## 🧰 Matériel commun à tout le Fun Lab

Pour réaliser l'ensemble des projets, il est recommandé de disposer du kit de base suivant :

- 1 carte Arduino (Uno, Nano, etc.)
- 1 breadboard + câbles de prototypage (jumpers)
- 1 écran LCD 16x2 (standard ou I2C)
- 1 ou 2 potentiomètres
- 1 photorésistance (LDR)
- 1 résistance de 10 kΩ (capteur de lumière)
- 1 ou plusieurs LED (couleur au choix)
- 1 résistance de 220-330 Ω (protection LED)

Ce kit unique permet de réaliser les 4 projets sans achat supplémentaire.

---

## 🏫 À propos de LingoLab Academy

LingoLab Academy est un centre de formation basé à Relizane, en Algérie, spécialisé dans l'apprentissage des langues et des technologies. Le programme **Arduino Fun Lab** s'inscrit dans une démarche d'initiation précoce à la pensée computationnelle et à l'électronique, à travers des projets concrets, progressifs et amusants.

**Direction pédagogique :** Dr. Chikh Mohamed Amine

---

## 📄 Licence et usage

Ce contenu pédagogique est destiné à un usage éducatif au sein de LingoLab Academy et de ses partenaires. Toute réutilisation ou adaptation doit créditer LingoLab Academy et Dr. Chikh Mohamed Amine.
