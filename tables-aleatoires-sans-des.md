---
tags:
  - jdr
  - outil-mj
  - jdr-solo
  - generation-aleatoire
  - game-design
aliases:
  - Génération sans dés
  - Mécaniques aléatoires alternatives
---

# Tables aléatoires sans dés

Remplacer les dés polyédriques par d'autres supports physiques ou mentaux permet de jouer en mobilité (transport, randonnée), d'ajouter une dimension tactile différente ou de contourner l'absence de matériel spécialisé.

---

## 1. Cartes à jouer classiques (54 cartes)

Un paquet standard remplace avantageusement les dés et offre une mémoire des tirages (ce qui est tiré ne ressort pas avant le remélange).

* **Couleurs (Enseignes) comme thèmes :**
  * **Cœur :** Social, émotion, allié, soin, diplomatie.
  * **Carreau :** Richesse, commerce, savoir, objet, piège mécanique.
  * **Trèfle :** Nature, survie, voyage, obstacle physique, météo.
  * **Pique :** Conflit, danger mortel, mort, trahison, magie noire.
* **Valeurs numériques :**
  * **As à 10 :** Équivalent direct d'un `1d10`.
  * **Figures :** Valet = obstacle mineur ou agent ; Dame = complication ou influence ; Roi = menace majeure ou autorité.
  * **Jokers :** Événement imprévu, retournement de situation total ou intervention extérieure.
* **Mécanique d'épuisement :** Ne pas remélanger le paquet crée une tension croissante. Plus le paquet diminue, plus la probabilité qu'une carte précise (comme le Roi de Pique) sorte augmente.

---

## 2. Dominos (Jeu de 28 pièces)

Les dominos fonctionnent comme un générateur à double entrée (`2d6` ou `2d7` incluant le blanc), idéal pour croiser deux concepts.

* **Lecture asymétrique :** La moitié gauche détermine le **Sujet** (ex. : `0` = lieu, `1` = PNJ, `2` = faction, `3` = objet, `4` = créature, `5` = rumeur, `6` = météo) et la moitié droite détermine l'**État** (ex. : `0` = détruit/hostile, `6` = prospère/amical).
* **Les Doubles :** Un domino double (`[3|3]`, `[6|6]`) signale un événement critique, une rencontre rare ou une amplification de l'effet.
* **Chaînage narratif :** Pioche un domino et connecte-le au précédent selon les règles du jeu. Le chiffre commun représente le fil conducteur logique entre deux scènes successives.

---

## 3. Pièces de monnaie (Lancers binaires)

Le lancer de pièce (`Pile` ou `Face`) permet des résolutions rapides sans aucun matériel spécifique.

* **Échelle de probabilité (1 pièce) :**
  * **Face :** Oui / Succès / Favorable.
  * **Pile :** Non / Échec / Défavorable.
* **Matrice à 2 pièces ( nuances narratives) :**
  * `Face + Face` : **Oui, et...** (Succès critique, avantage supplémentaire).
  * `Face + Pile` : **Oui, mais...** (Succès avec un coût ou une complication).
  * `Pile + Face` : **Non, mais...** (Échec atténué, opportunité secondaire).
  * `Pile + Pile` : **Non, et...** (Échec critique, aggravation immédiate).
* **Table à 8 entrées (3 pièces) :** Chaque lancer de trois pièces produit une combinaison binaire unique (`FFF` à `PPP`), permettant d'indexer une table aléatoire classique de 1 à 8.

---

## 4. Supports textuels (Bibliomancie)

Utiliser un livre physique (roman, manuel de règles, recueil) comme générateur d'inspiration infini.

1. Formule une question ouverte (ex. : *« Que trouve-t-on dans ce coffre ? »* ou *« Quelle est la motivation du garde ? »*).
2. Ouvre le livre au hasard et pose le doigt sur la page sans regarder.
3. Lis le mot ou le fragment de phrase désigné et interprète-le métaphoriquement selon le contexte de la scène.

---

## 5. Dés mentalisés et chronomètre (Zéro matériel)

Méthodes purement cognitives ou utilisant une montre/un téléphone en mode hors-ligne.

* **Les centièmes de seconde :** Lance un chronomètre, arrête-le à l'aveugle et lis les deux derniers chiffres (`00` à `99`). Cela remplace instantanément un `1d100` (jet de pourcentage). Le dernier chiffre seul donne un `1d10`.
* **Chifoumi (Pierre-Feuille-Ciseaux) :** En solo ou face à un joueur, chaque signe représente une approche :
  * **Pierre :** Force, résistance, blocage.
  * **Feuille :** Ruse, magie, contournement.
  * **Ciseaux :** Précision, rapidité, attaque directe.
  * *Résolution :* Le MJ choisit mentalement l'approche de l'environnement ou de l'ennemi, puis tire au sort celle du destin.
* **Grille mentale :** Visualise une horloge. Regarde l'aiguille des secondes (ou les minutes sur un affichage numérique modulo 12) pour obtenir un résultat de `1` à `12` (`1d12`).

---

## Tableau comparatif des alternatives

| Support                  | Équivalent dé  | Atout principal                          | Limite                             |
| :----------------------- | :------------- | :--------------------------------------- | :--------------------------------- |
| **Cartes classiques**    | `1d13` x 4     | Mémoire des tirages, tension progressive | Nécessite de battre le paquet      |
| **Dominos**              | `2d7`          | Croisement naturel de deux variables     | Encombrant en déplacement          |
| **2 Pièces**             | `1d4` narratif | Ultra-portable, nuance directe           | Peu de granularité numérique       |
| **Livre (Bibliomancie)** | Table infinie  | Richesse lexicale et évocatrice          | Demande un effort d'interprétation |
| **Chronomètre**          | `1d100`        | Précision mathématique absolue           | Aucun support thématique           |

---

## Liens connexes
* [[Utiliser Magic The Gathering comme moteur aléatoire et oracle en JDR]]
* [[Oracles et moteurs de jeu solo]]
* [[Génération procédurale de donjons et hexagones]]