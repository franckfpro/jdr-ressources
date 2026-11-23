---
id: 202611221100
aliases: [Loner d10, Loner adaptation décimale]
tags: [jdr, solo, oracle, systeme-leger, d10, fiche-reference]
source: "Loner - Core Rules 3rd Edition, Roberto Bisceglie (CC BY-SA 4.0)"
related: ["[[Loner-RPG]]", "[[Oracle-solo]]", "[[Jeu-de-role-solo]]", "[[Freeform-Universal]]"]
---

# Loner d10 — Adaptation du système

Fiche de référence : résumé du système [[Loner-RPG]] (3e édition) et adaptation
complète aux d10. Jeu de rôle solo narratif : un Protagoniste, un Oracle,
aucune statistique chiffrée en dehors de la Chance.

## 1. Principe du jeu

Jeu solo émergent et improvisé : le joueur incarne protagoniste et narrateur.
Aucune histoire prédéfinie ; on interroge l'Oracle par des questions fermées
(Oui/Non), on interprète les réponses, et les rebondissements reconfigurent le récit.

Quatre piliers :
- Portable : quelques dés et un crayon.
- Rules-light : une seule mécanique centrale (l'Oracle).
- Tag-based : tout est décrit par des mots, jamais par des chiffres.
- Émergent : le monde réagit aux actions, Goal/Motive/Nemesis naissent du jeu.

## 2. Personnage (Protagoniste)

- Nom et Concept : une phrase évocatrice (ex. « Chasseuse de primes rusée »).
- 2 Compétences : permissions narratives (ex. « Marcheuse d'ombres »).
- 1 Fragilité : faiblesse ou fardeau (ex. « Hantée par le passé »).
- 2 Équipements : spécialisés selon le cadre.
- Goal, Motive, Nemesis : à déduire du cadre et des premières scènes.
- Chance : **10** (d10), réinitialisée après chaque conflit.

Tout élément marquant (PNJ, vaisseau, malédiction, faction) est un personnage :
Concept + Compétences/Fragilité + Tags. Les entités non vivantes n'ont ni Goal,
ni Motive, ni Nemesis. Les groupes nombreux se jouent comme une entité unique
avec une seule réserve de Chance.

## 3. Tags

Trois familles : traits de personnage, détails de scène, conditions temporaires.
Un Tag pertinent accorde Avantage ou Désavantage. Jamais de bonus numérique.
- Avantage : 2d10 Chance + 1d10 Risque, garder la meilleure Chance.
- Désavantage : 2d10 Risque + 1d10 Chance, garder le pire Risque.
- Plafond : 2 dés maximum par type. Positifs et négatifs s'annulent.

## 4. Oracle (résolution d10)

Poser une question Oui/Non, lancer **1d10 Chance + 1d10 Risque** :

| Comparaison     | Résultat                                    |
| --------------- | ------------------------------------------- |
| Chance > Risque | Oui                                         |
| Risque > Chance | Non                                         |
| Égalité         | Oui, mais... +1 Compteur de rebondissements |
| Les deux <= 5   | ajouter « mais... »                         |
| Les deux >= 6   | ajouter « et... »                           |

Six issues : Oui et... / Oui / Oui mais... / Non mais... / Non / Non et...
Interprétation souple : intensité, générateur de rebondissement, ou contrôle
du rythme de la scène. Réponse incohérente : ne pas sur-interroger (3 questions
max), reformuler, sinon retenir « Oui, mais... » par défaut.

### 4.1 Table de résolution

Chance en ligne, Risque en colonne. Lire la case croisée.
C = Compteur de rebondissements.

| Risque ><br>Chance V | 1                     | 2                     | 3                     | 4                     | 5                     | 6                     | 7                     | 8                     | 9                     | 10                    |
| -------------------- | --------------------- | --------------------- | --------------------- | --------------------- | --------------------- | --------------------- | --------------------- | --------------------- | --------------------- | --------------------- |
| 1                    | **Oui, mais...** +1 C | Non, mais...          | Non, mais...          | Non, mais...          | Non, mais...          | Non                   | Non                   | Non                   | Non                   | Non                   |
| 2                    | Oui, mais...          | **Oui, mais...** +1 C | Non, mais...          | Non, mais...          | Non, mais...          | Non                   | Non                   | Non                   | Non                   | Non                   |
| 3                    | Oui, mais...          | Oui, mais...          | **Oui, mais...** +1 C | Non, mais...          | Non, mais...          | Non                   | Non                   | Non                   | Non                   | Non                   |
| 4                    | Oui, mais...          | Oui, mais...          | Oui, mais...          | **Oui, mais...** +1 C | Non, mais...          | Non                   | Non                   | Non                   | Non                   | Non                   |
| 5                    | Oui, mais...          | Oui, mais...          | Oui, mais...          | Oui, mais...          | **Oui, mais...** +1 C | Non                   | Non                   | Non                   | Non                   | Non                   |
| 6                    | Oui                   | Oui                   | Oui                   | Oui                   | Oui                   | **Oui, mais...** +1 C | Non, et...            | Non, et...            | Non, et...            | Non, et...            |
| 7                    | Oui                   | Oui                   | Oui                   | Oui                   | Oui                   | Oui, et...            | **Oui, mais...** +1 C | Non, et...            | Non, et...            | Non, et...            |
| 8                    | Oui                   | Oui                   | Oui                   | Oui                   | Oui                   | Oui, et...            | Oui, et...            | **Oui, mais...** +1 C | Non, et...            | Non, et...            |
| 9                    | Oui                   | Oui                   | Oui                   | Oui                   | Oui                   | Oui, et...            | Oui, et...            | Oui, et...            | **Oui, mais...** +1 C | Non, et...            |
| 10                   | Oui                   | Oui                   | Oui                   | Oui                   | Oui                   | Oui, et...            | Oui, et...            | Oui, et...            | Oui, et...            | **Oui, mais...** +1 C |

#### Lecture rapide

- Zone bas-gauche (deux dés <= 5) : résultats mitigés, « mais... ».
- Zone haut-droite (deux dés >= 6) : résultats amplifiés, « et... ».
- Diagonale : égalités, toujours « Oui, mais... » +1 C.
- Avantage/Désavantage : lancer le dé supplémentaire du type concerné, garder le plus haut (Chance) ou le plus bas... garder le plus haut Risque, puis lire la matrice avec ces deux valeurs.

## 5. Compteur de rebondissements

Chaque double : +1. À 3, un rebondissement survient (compteur remis à 0) :
lancer **2d10** (Sujet + Action) et interpréter dans la scène en cours.

| d10 | Sujet                   | d10 | Action               |
| --- | ----------------------- | --- | -------------------- |
| 1   | Un tiers                | 1   | Apparaît             |
| 2   | Le héros                | 2   | Change de lieu       |
| 3   | Une rencontre           | 3   | Aide le héros        |
| 4   | Un événement physique   | 4   | Gêne le héros        |
| 5   | Un événement émotionnel | 5   | Change l'objectif    |
| 6   | Un objet                | 6   | Met fin à la scène   |
| 7   | Un mensonge             | 7   | Est révélé           |
| 8   | Un allié                | 8   | Change de camp       |
| 9   | Le temps                | 9   | Manque               |
| 10  | L'ennemi                | 10  | Renforce sa position |

Variante : sur d10 les doubles tombent à 10 % (contre 16,7 % sur 2d6) ;
déclencher le rebondissement à **2** pour une tension équivalente.

## 6. Conflits

Trois niveaux, au choix :
1. Une question Oui/Non pour tout le conflit.
2. Une question par action clé (poursuites, négociations, duels cinematic).
3. Système Chance et dégâts :

| Résultat Oracle | Dégâts     |
| --------------- | ---------- |
| Oui, et...      | infliger 5 |
| Oui             | infliger 3 |
| Oui, mais...    | infliger 2 |
| Non, mais...    | subir 2    |
| Non             | subir 3    |
| Non, et...      | subir 5    |

À 0 Chance : défaite narrative (capturé, unanimement discrédité, cible perdue).
Conséquence dictée par le récit, jamais une fin automatique. L'échelle d10
(Chance 10, dégâts 2-5) conserve 3 à 5 échanges par conflit, comme l'original.

## 7. Humeur de la scène suivante

Lancer **1d10** en fin de scène :
- 1-5 : Scène dramatique (les enjeux montent).
- 6-8 : Scène calme (repos, préparation, relations).
- 9-10 : Pendant ce temps... (coupe vers un autre point de vue).

## 8. Démarrage : 5W+H en d10

Choisir un démarrage in medias res ou cadrer la mission (combinables) :

| d10 | Qui              | Quoi       | Pourquoi   | Où             | Comment               | Obstacle      |
| --- | ---------------- | ---------- | ---------- | -------------- | --------------------- | ------------- |
| 1   | Autorité         | Sauvetage  | Aider      | Une personne   | Rencontre fortuite    | Opposition    |
| 2   | Organisation     | Protection | Fortune    | Un groupe      | Vieille connaissance  | Tromperie     |
| 3   | Allié(e)         | Espionner  | Contrainte | Un trésor      | Rumeurs               | Environnement |
| 4   | Mentor           | Explorer   | Impulsion  | Un lieu        | Capture               | Déguisement   |
| 5   | Demandeur d'aide | Fuir       | Ambition   | Un McGuffin    | Mésaventure           | Temps         |
| 6   | Maître chanteur  | Poursuivre | Vengeance  | Une confession | Objet (carte, lettre) | Espace        |
| 7   | Rival            | Livrer     | Survie     | Un repaire     | Convocation           | Ressources    |
| 8   | Inconnu          | Saboter    | Honneur    | Zone interdite | Menace directe        | Trahison      |
| 9   | Institution      | Enquêter   | Curiosité  | Un véhicule    | Message crypté        | Surveillance  |
| 10  | Ennemi           | Négocier   | Devoir     | Monde inconnu  | Coïncidence           | Dilemme       |

## 9. Inspiration (questions ouvertes)

Lancer **1d10** sur chaque table (verbe et nom obligatoires, adjectif optionnel) :

| d10 | Verbes     | Adjectifs   | Noms         |
| --- | ---------- | ----------- | ------------ |
| 1   | injecter   | fréquent    | cause        |
| 2   | continuer  | défaillant  | événement    |
| 3   | développer | insidieux   | mémoire      |
| 4   | partager   | soyeux      | conversation |
| 5   | affronter  | calme       | secret       |
| 6   | détruire   | magnifique  | allié        |
| 7   | cacher     | éthéré      | arme         |
| 8   | révéler    | surprenant  | rumeur       |
| 9   | négocier   | froid       | limite       |
| 10  | échapper   | gigantesque | promesse     |

## 10. Boucle de jeu

1. Cadrer la scène : où, quoi, objectif à court terme.
2. Résultat évident : le jouer sans dé. Incertitude : question à l'Oracle.
3. Interpréter la réponse (intensité, rebondissement, rythme).
4. Gérer les Tags : Avantage/Désavantage au cas par cas.
5. Conflit : Oracle simple, actions clés, ou Chance et dégâts.
6. Fin de scene : humeur suivante (1d10). Rebondissements : compteur.

Fin d'aventure : objectif atteint ou perdu, révélation majeure, dynamique qui
ralentit. Croissance : ajouter une Compétence, un Équipement ou une Fragilité,
modifier un trait, ajouter un Nemesis ; mettre à jour PNJ, lieux et événements.

## 11. Changelog de l'adaptation d10

- d6 `->` d10 ; seuils mais/et : 1-3/4-6 `->` 1-5/6-10.
- Chance : 6 `->` 10 ; dégâts 1/2/3 `->` 2/3/5.
- Doubles plus rares : compteur à 3 conservé, variante à 2 documentée.
- Toutes les tables converties en d10 (5W+H, rebondissements, humeur, inspiration).
- Incertitude conservée : l'égalité reste « Oui, mais... » (+1 compteur).

## Sources

- [[Loner-RPG]] : système original (Recluse Engine, Harm & Luck du 6Q System,
  inspiré de Freeform Universal et Mythic).
- Licence de l'œuvre originale : CC BY-SA 4.0 ; cette adaptation est donc
  également diffusée sous CC BY-SA 4.0.
