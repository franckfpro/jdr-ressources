---
titre: JDR Solo x Google Street View — protocoles Street Oracle
type: méta-protocole
créé: 2026-11-03
statut: brouillon
tags:
  - jdr/solo
  - jdr/ironsworn
  - jdr/mythic-gme
  - geofiction
  - streetview
aliases:
  - Street Oracle
  - Géofiction solo
lié:
  - "[[Ironsworn]]"
  - "[[Mythic GME]]"
  - "[[Template - Scène Street Oracle]]"
---

# JDR Solo x Google Street View

## Principe

Google Street View sert de générateur d'ambiance, d'oracle visuel et de
mécanique de déplacement pour un jeu solo (Ironsworn, Mythic GME, ou tout
système à oracle). L'image concrète remplace ou complète le tirage abstrait ;
l'interprétation du lieu EST le résultat d'oracle.

## Chaîne d'outils
| Rôle           | Oui                                                                          | Note                             |
| -------------- | ---------------------------------------------------------------------------- | -------------------------------- |
| Lieu aléatoire | [MapCrunch](https://www.mapcrunch.com/) (filtres pays/zone/urbain/intérieur) | cacher la position = mode énigme |
| Lieu choisi    | Google Maps / Street View                                                    | régions, routes nommées          |
| Oracle texte   | Ironsworn (action + thème), Mythic (Fate Chart)                              | en cas d'image muette            |
| Journal        | Obsidian + modèle de scène                                                   | captures + lien de partage       |

## Protocoles

### A — Oracle spatial
1. Poser une question fermée ou ouverte au lieu d'un jet.
2. Téléporter (MapCrunch, filtres selon le contexte de fiction).
3. Choisir 3 détails visibles (enseigne, véhicule, végétation, lumière…).
4. Interpréter les détails comme la réponse. Noter, puis relancer la fiction.

### B — Randonnée (Ironsworn, Undertake a Journey)
1. Définir le départ réel et la destination sur Google Maps.
2. chaque étape du voyage = avancer dans Street View jusqu'à une intersection.
3. si intersection : lancer l'oracle de voie ; l'image arbitre.
4. Sur échec (délai/récit/coût) : introduire un détail incongru de l'image
   comme complication ; sur rencontre : quiconque apparaît plausible devient PNJ.

### C — Scénario (Mythic GME)
1. Mise en place de scène : téléporter = nouveau décor ; le chaos détermine
   modification/interruption.
2. Événement aléatoire : le thread est repris sur un détail visible.
3. Fin de scène : arrêter sur une image ambiguë, c'est le cliffhanger.

### D — Fracture temporelle
1. Fixer un lieu, ouvrir l'historique des clichés.
2. Rejouer la scène à 5 ou 10 ans d'écart ; les changements réels
   (constructions, fermetures, saisons) deviennent les événements.
3. Utilisable pour enquête, post-apo, mémoire, uchronie locale.

## Table d'interprétation (d6, par détail)
| d6  | Lecture du détail                            |
| --- | -------------------------------------------- |
| 1   | menacer — indice de danger imminent          |
| 2   | mené — piste vers le fil actif               |
| 3   | opportunité — ressource exploitable          |
| 4   | obstacle — complication immédiate            |
| 5   | indice de PNJ — quelqu'un vit/veille ici     |
| 6   | anomalie — déplacer le détail dans l'étrange |

## Boucle de session

1. Téléporter / avancer.
2. Décrire la scène en une phrase (imparfait du récit).
3. Question d'oracle (image ou dés).
4. Résoudre la fiction ; si position du personnage engagée, noter la position.
5. Journal : nouvelle note de scène (modèle lié), lien vers lieu Street View.
6. Actualiser fils et menaces (Mythic) ou jauge de progression (Ironsworn).

## Journalisation Zettelkasten

- une note de scène par lieu, jamais de doublon de résumé ;
- le lieu (URL Street View) devient une note source citée par toutes les
  scènes qui s'y déroulent ;
- fils, PNJ et lieux indexés par tags `#thread`, `#pnj`, `#lieu` ;
- requête possible : scènes d'un même lieu via liens entrants.

## Limites et garde-fous

- Couverture mondiale inégale (zones rurales et pays du Sud pauvres en vues) :
  utiliser le lieu où l'on se situe pour ce qui n'est pas exploré ;
- Vues datées : en faire une mécanique (protocole D) plutôt qu'un défaut ;
- Pas d'intérieur dans la plupart des cas : arbitrer l'oracle texte ;
- Captures à usage strictement privé (journal personnel) ;
- Prévoir des adjectifs (fins, mornes, chargés) sur les lieux vus pour aider à
  changer d'avis, et les délais réels de navigation pour éviter le temps
  d'écran sans fiction.
