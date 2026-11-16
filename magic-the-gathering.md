---
tags:
  - jdr
  - outil-mj
  - jdr-solo
  - generation-aleatoire
  - magic-the-gathering
aliases:
  - Oracle Magic The Gathering
  - Générateur MTG pour JDR
---

# Utiliser Magic: The Gathering comme moteur aléatoire et oracle en JDR

Les cartes *Magic: The Gathering* (MTG) constituent un outil dense et autonome pour remplacer les dés, les tables aléatoires classiques et les oracles de JDR (en solo ou en meneur de jeu). Un deck de 60 à 100 cartes offre des millions de combinaisons visuelles, numériques et thématiques.

---

## 1. Préparation du deck d'oracle

Pour optimiser la pertinence des tirages, compose un paquet dédié (environ 60 cartes) selon le ton de la campagne :
* **Ratio recommandé :** 
	* 20 Terrains (lieux et ambiances), 
	* 20 Créatures (PNJ, monstres, factions), 
	* 10 Éphémères/Rituels (événements soudains, rebondissements), 
	* 10 Artefacts/Enchantements (objets, malédictions, règles locales).
* **Filtrage thématique :** Écarte les cartes trop spécifiques à des mécaniques de tournoi ou des univers hors-sujet (ex. : cartes futuristes pour du médiéval-fantastique pur).

---

## 2. Résolution d'actions et tests (remplacer les dés)

La **Valeur de Mana** (coût converti en haut à droite de la carte) sert de générateur numérique rapide :
* **Échelle de base :** La valeur de mana va généralement de `0` à `7+`.
* **Test binaire (Oui / Non) :**
  * Coût pair = **Oui** (Succès).
  * Coût impair = **Non** (Échec).
  * Présence d'un Terrain = **Oui, mais...** ou **Non, et...** (conséquence narrative liée à la couleur du terrain).
* **Jet sous compétence :** Tire une carte. Le résultat doit être inférieur ou égal au score de compétence du personnage (sur une échelle de 1 à 6). Une carte de rareté **Mythique** ou **Rare** déclenche un succès ou un échec critique selon le contexte.

---

## 3. Interprétation des couleurs (boussole thématique)

Chaque couleur de mana oriente immédiatement la nature d'un événement, l'attitude d'un PNJ ou l'ambiance d'une scène :

| Couleur          | Thèmes et ambiances                            | Motivation d'un PNJ           | Type de danger                        |
| :--------------- | :--------------------------------------------- | :---------------------------- | :------------------------------------ |
| **Blanc (W)**    | Loi, ordre, religion, protection, tyrannie     | Devoir, justice, fanatisme    | Milice, piège sacré, jugement         |
| **Bleu (U)**     | Savoir, illusion, eau, manipulation, secret    | Curiosité, ruse, contrôle     | Énigme, magie mentale, noyade         |
| **Noir (B)**     | Mort, ambition, corruption, marais, sacrifice  | Pouvoir, survie, avidité      | Maladie, trahison, mort-vivant        |
| **Rouge (R)**    | Chaos, passion, feu, montagne, impulsion       | Colère, liberté, gloire       | Éboulement, embuscade, incendie       |
| **Vert (G)**     | Nature, instinct, croissance, forêt, tradition | Harmonie, prédation, héritage | Bête sauvage, poison, terrain hostile |
| **Incolore (C)** | Artifice, vide, relique ancienne, étrangeté    | Programmation, neutralité     | Automates, anomalie arcanique         |

---

## 4. Tables de génération par type de carte

Tire une carte face cachée et lis son type principal pour obtenir un résultat immédiat :

### Terrains : Exploration et météo
* **Plaine :** Espace dégagé, visibilité longue, patrouille ou route commerciale.
* **Île :** Point d'eau, brouillard, zone isolée, passage maritime ou rivière.
* **Marais :** Terrain difficile, miasmes, ruines englouties, visibilité réduite.
* **Montagne :** Relief escarpé, froid, grottes, point d'observation élevé.
* **Forêt :** Couvert végétal dense, pistes animales, embuscade possible.
* **Terrain non-base :** Lieu remarquable, point d'intérêt majeur ou anomalie géographique (le nom et l'illustration dictent le décor).

### Créatures : Rencontres et PNJ
* **Type de créature :** Définit l'espèce, la faction ou le métier (ex. : *Humain Soldat*, *Gobelin Éclaireur*, *Esprit*).
* **Force / Endurance :** Indique le niveau de menace physique (`1/1` = faible/civil, `3/3` = vétéran, `6/6+` = monstre majeur).
* **Capacités à mots-clés :**
  * *Vol :* En hauteur, hors de portée ou mobile.
  * *Contact mortel :* Empoisonné, assassin ou attaque létale.
  * *Initiative :* Prend l'avantage, tend une embuscade.
  * *Défense talismanique :* Protégé par une magie ou une armure lourde.
  * *Menace :* Attaque en groupe ou intimide.

### Éphémères et Rituels : Événements aléatoires
* **Éphémère :** Événement brusque, interruption immédiate, réaction d'un ennemi ou changement soudain de situation.
* **Rituel :** Événement lent, présage, conséquence à long terme ou projet d'une faction qui arrive à maturité.

### Artefacts et Enchantements : Butin et mystères
* **Artefact / Équipement :** Objet physique utilisable, relique, mécanisme ou indice matériel.
* **Enchantement / Aura :** Malédiction de zone, bénédiction divine, rumeur persistante ou loi magique locale.

---

## 5. Lecture narrative complète (méthode des 4 couches)

Lorsqu'une scène bloque ou nécessite une inspiration complète, tire une carte et lis-la de haut en bas :

1. **L'illustration :** Donne le visuel immédiat, la posture du PNJ ou l'architecture du lieu.
2. **Le titre de la carte :** Sert de mot-clé ou de nom de quête (ex. : *« Le prix de la trahison »*, *« Murmures de la nuit »*).
3. **La boîte de texte (règles) :** Traduis les mécaniques en fiction. *« Détruisez la créature ciblée »* devient un assassinat ; *« Piochez deux cartes »* devient la découverte d'un secret ou d'un indice.
4. **Le texte d'ambiance (en italique) :** Fournit une réplique toute prête pour un PNJ, une inscription gravée sur un mur ou une note trouvée sur un cadavre.

---

## Liens connexes
* [[Oracles et moteurs de jeu solo]]
* [[Génération procédurale de donjons et hexagones]]
* [[Tables aléatoires sans dés]]