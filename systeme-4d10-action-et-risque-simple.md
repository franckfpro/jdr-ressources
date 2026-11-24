---
tags:
  - jdr
  - game-design
  - mecanique-de-des
  - solo-rpg
  - ironsworn
  - loner
aliases:
  - Système 4d10 Action et Risque
  - Résolution d10 Ironsworn-Loner
created: 2026-11-23
---
# Résolution 4d10

### Étape 1 : Constitution de la réserve
Selon le positionnement fictionnel du personnage, on détermine le nombre de **dés de Risque** lancés :
* **Position normale :** Lancer **2d10 d'Action** et **1d10 de Risque**.
* **En Avantage :** Lancer **2d10 d'Action** et **2d10 de Risque**, puis **conserver uniquement le dé de Risque le plus faible**.
* **En Désavantage :** Lancer **2d10 d'Action** et **2d10 de Risque**, puis **conserver uniquement le dé de Risque le plus fort**.

### Étape 2 : Lecture du résultat principal
On compare individuellement chacun des deux **dés d'Action** au **dé de Risque** retenu :

| Condition                                                                | Résultat        | Effet narratif                                                                 |
| :----------------------------------------------------------------------- | :-------------- | :----------------------------------------------------------------------------- |
| Les **2 dés d'Action** sont **$\ge$** au dé de Risque                    | **Coup fort**   | L'action réussit pleinement, sans coût ni complication majeure.                |
| **1 seul dé d'Action** est **$\ge$** au dé de Risque *(l'autre est $<$)* | **Coup faible** | L'action réussit, mais avec un coût, un compromis ou un danger imminent.       |
| Les **2 dés d'Action** sont **$<$** au dé de Risque                      | **Échec**       | L'action échoue ou la situation tourne nettement au désavantage du personnage. |

*Si l'on souhaite rendre une tâche légèrement plus difficile, on peut décider d'un échec sur une égalité plutôt que strictement inférieur.*

### Étape 3 : Modulateurs narratifs (Doubles et Égalités)
* **Critique ("et...") :** Les **2 dés d'Action affichent le même chiffre**.
  * *Sur un Coup fort :* Succès éclatant, opportunité supplémentaire ou avantage décisif (*"Oui, et..."*).
  * *Sur un Échec :* Catastrophe, aggravation brutale de la situation (*"Non, et..."*).
* **Inattendu ("mais...") :** Au moins **un dé d'Action est égal au dé de Risque**.
  * *Sur un Coup fort :* Succès complet, **mais** un élément imprévu surgit, un détail change la donne ou un rebondissement survient (*"Oui, mais..."*).
  * *Sur un Coup faible :* Succès mitigé, **mais** la nature du rebondissement est imprévisible ou ouvre une piste inattendue.
* **Double coïncidence ("et... mais...") :** Les 3 dés retenus affichent exactement la même valeur (ex. : `7` et `7` contre un risque de `7`). C'est toujours un **Coup fort** accompagné d'un retournement majeur.
---
# Oracle

Lorsque vous cherchez à résoudre des questions, découvrir des détails, révéler des lieux, déterminer comment d'autres personnages réagissent, ou déclencher des rencontres ou des événements, vous pouvez...
- Tirer une conclusion : décidez de la réponse en vous basant sur le résultat le plus intéressant et le plus évident.
- Susciter une idée : utilisez une table d'oracle ou une autre invite aléatoire.
- Poser une question fermée : décidez des probabilités d'un "oui", et lancez les dés sur la table ci-dessous pour vérifier la réponse.
- Choisir entre deux : imaginez deux options. Considérez l'une comme "probable", et lancez les dés sur la table ci-dessous pour voir si c'est vrai. Sinon, c'est l'autre.

| Chances                | Oui Critique |  Oui  |  Non  | Non Critique |
| :--------------------- | :----------: | :---: | :---: | :----------: |
| **Certain**            |     1–18     | 19–90 | 91–98 |    99–100    |
| **Presque certain**    |     1–17     | 18–85 | 86–97 |    98–100    |
| **Très probable**      |     1–15     | 16–75 | 76–95 |    96–100    |
| **Probable**           |     1–13     | 14–65 | 66–93 |    94–100    |
| **50/50 ou Inconnu**   |     1–10     | 11–50 | 51–90 |    91–100    |
| **Improbable**         |     1–7      | 8–35  | 36–87 |    88–100    |
| **Très improbable**    |     1–5      | 6–25  | 26–85 |    86–100    |
| **Presque impossible** |     1–3      | 4–15  | 16–83 |    84–100    |
| **Impossible**         |     1–2      | 3–10  | 11–82 |    83–100    |

En cas de double, c'est un Inattendu ("mais...").

> Version simple:
Probabilités : La réponse est "oui" si vous obtenez...
- Faible chance : 10 ou moins
- Peu probable : 25 ou moins
- 50/50 : 50 ou moins
- Probable : 75 ou moins
- Presque certain : 90 ou moins
En cas de correspondance (double), imaginez un résultat extrême ou un rebondissement.

---
# Imprévu

A chaque début de session/tour, faire un jet d'oracle, en adaptant les chances à la situation. En cas de **Oui Critique**, un événement imprévu se produit. Adapter à la narration ou lancer sur le tableau ci-dessous pour inspiration:

| Jet (d100) | Type d'événement          |
| ---------- | ------------------------- |
| 1-7        | Evénement distant         |
| 8-28       | Action PNJ                |
| 29-35      | Introduire un nouveau PNJ |
| 36-45      | Avancer dans une piste    |
| 46-52      | Changer de piste          |
| 53-55      | Fermer une piste          |
| 56-67      | PJ négatif                |
| 68-75      | PJ positif                |
| 76-83      | Evénement ambigu          |
| 84-92      | PNJ positif               |
| 93-100     | PNJ négatif               |

