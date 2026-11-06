---
id: "202609291959"
type: permanente
statut: valide
tags:
  - solo
  - mythic-gme
  - oracle
  - D100
  - reference
date_creation: 2026-09-29
---
# mythic-game-master-emulator

Le *Mythic Game Master Emulator* (GME) remplace le meneur de jeu traditionnel en utilisant des probabilités dynamiques et des associations d'idées pour générer une narration imprévisible. Ses mécaniques s'articulent autour de l'improvisation guidée par des questions et des scènes structurées.

## **L'Oracle [[table-du-destin]]**

* Posez une question fermée (Oui/Non) pour clarifier une situation ou la réaction d'un PNJ.

* Déterminez la probabilité d'un "Oui" (de "Presque impossible" à "Certain") en fonction du contexte.
* Lancez un d100 pour obtenir la réponse. Les résultats intègrent souvent des nuances narratives critiques comme "Oui, mais..." ou "Non, et..." pour enrichir la dynamique de la rencontre et relancer l'action.

* Les lancers générant des doubles sur les dés déclenchent des événements aléatoires inattendus.

## **Le Facteur de Chaos**

* C'est une jauge fluctuant de 1 à 9 qui mesure l'intensité dramatique de votre aventure.
* Une valeur élevée augmente vos chances d'obtenir des réponses "Oui" à l'Oracle et provoque davantage de rebondissements.
* Le Facteur de Chaos est ajusté à la fin de chaque scène : il baisse si la situation globale est sous contrôle, et augmente si elle échappe à votre personnage.

## **La Structure des Scènes**

* Concevez vos sessions de jeu via une boucle répétable qui vous guide scène par scène [[boite-a-outils-solo-1-start]]
* Définissez la situation initiale : le lieu, les dangers potentiels et les personnages présents.
* Avant de jouer, testez la scène contre le Facteur de Chaos pour vérifier si elle se déroule comme prévu, si elle est modifiée (Altérée), ou si elle est totalement remplacée (Interrompue) par un événement imprévu.
* Jouez la scène jusqu'à sa résolution logique, puis effectuez la transition vers la suivante.

### Le test de la scène attendue (Testing the Expected Scene)

Dans Mythic GME 2e, chaque nouvelle scène commence par une attente : vous déterminez la suite logique du récit (« mon personnage entre dans la taverne pour interroger l'aubergiste »). Avant de jouer cette scène, vous la testez contre le Facteur de Chaos (FC), qui représente le degré de contrôle des personnages sur l'action, commence à 5 et varie entre 1 et 9 ([RPG Pub](https://www.rpgpub.com/threads/using-the-mythic-game-master-emulator-my-way.9240/), [PDFCoffee — Mythic GME 2e](https://pdfcoffee.com/mythic-game-master-emulator-2nd-edition-tana-pigeon-2-pdf-free.html)).

La procédure exacte : lancez 1d10 et comparez au FC courant ([AnyFlip — Mythic GME 2e, p. 66-67](https://anyflip.com/xrdiw/tprp/basic/51-100)) :

| Résultat du d10                                         | Type de scène                                |
| ------------------------------------------------------- | -------------------------------------------- |
| Strictement supérieur au FC                             | Scène Attendue (elle se déroule comme prévu) |
| Inférieur ou égal au FC, chiffre impair (1, 3, 5, 7, 9) | Scène Altérée                                |
| Inférieur ou égal au FC, chiffre pair (2, 4, 6, 8)      | Scène Interrompue                            |

Conséquence pratique : au FC 5, la scène change une fois sur deux ; chaque point de FC supplémentaire augmente de 10 % la probabilité d'altération ou d'interruption. Un FC élevé traduit une perte de contrôle des personnages sur le récit ([PDFCoffee — Mythic GME 2e](https://pdfcoffee.com/mythic-game-master-emulator-2nd-edition-tana-pigeon-2-pdf-free.html)).

#### La scène Altérée

La scène commence « de la manière suivante la plus attendue », comme si Mythic avait entendu votre idée et répondait « essayons plutôt autre chose ». Deux contraintes : l'altération doit rester logique et pouvoir se produire à la place de la scène attendue ; elle peut être presque identique (un seul détail change) ou sensiblement différente ([AnyFlip — Mythic GME 2e](https://anyflip.com/xrdiw/tprp/basic/51-100)).

Si l'inspiration manque, deux outils sont prévus :

1. La table d'Ajustement de Scène (Scene Adjustment Table) : un lancer de d10 indique quel élément de la scène attendue se trouve modifié (le lieu, le personnage présent, l'ambiance, etc.).
2. Les tables de Sens (Meaning Tables) : deux mots tirés au hasard, à interpréter pour altérer la scène. L'exemple du livre illustre un lancer « Distrust / Innocent » interprété comme un sol qui trembe par intermittence, suggérant une grotte instable et des risques d'éboulement pour l'exploration à venir ([AnyFlip — Mythic GME 2e](https://anyflip.com/xrdiw/tprp/basic/51-100)).

#### La scène Interrompue

C'est le cas le plus radical : la scène attendue n'a pas lieu. Vous générez alors un Événement Aléatoire (Random Event) par la procédure standard : un lancer de d100 sur la table de Focus d'Événement (qui indique qui ou quoi est concerné : action d'un PNJ, nouveau PNJ, progression d'un fil narratif, etc.), complété par deux paires de mots issus des tables de Sens (Action et Description). L'événement devient le centre de la scène et remplace la scène attendue ([Wisps of Time](https://wispsoftime.com/content/rolling-solo-chapter-6-part-mythic-game-master-emulator/), [AnyFlip — Mythic GME 2e, Variations](https://anyflip.com/xrdiw/tprp/basic/151-200)).

Deux précisions importantes :

- La scène attendue initiale peut toujours se produire plus tard : si elle reste logique, elle devient simplement la scène attendue suivante.
- La 2e ajoute une entrée « Current Context » à la table de Focus, qui ancre l'interruption dans la situation présente du récit ([PDFCoffee — Mythic GME 2e](https://pdfcoffee.com/mythic-game-master-emulator-2nd-edition-tana-pigeon-2-pdf-free.html)).

#### Cas particuliers et marges de manœuvre

- La toute première scène d'une aventure n'est jamais testée contre le Facteur de Chaos : elle n'est pas soumise au risque d'altération ou d'interruption ([AnyFlip — Mythic GME 2e](https://anyflip.com/xrdiw/tprp/basic/151-200)).
- Le FC s'ajuste à la fin de chaque scène : il diminue de 1 si les personnages ont gagné en contrôle, il augmente de 1 dans le cas contraire ([Halfway Station](https://hws3.wordpress.com/2023/03/11/review-mythic-game-master-emulator-2nd-edition/)).
- Des événements aléatoires peuvent aussi survenir en pleine scène, indépendamment des interruptions, lorsque les Questions du Destin produisent des doubles (11, 22, 33…) inférieurs ou égaux au FC ([Matthew Santa Cruz](https://matthewsantacruz.substack.com/p/how-i-use-the-mythic-gm-emulator)).
- Conseil de l'autrice Tana Pigeon : face à une interruption sans inspiration, une option légitime consiste à conserver la scène attendue et à placer l'événement aléatoire en tête de scène, l'interruption agissant alors comme simple générateur d'événement plutôt que comme remplacement total ([r/mythic_gme](https://www.reddit.com/r/mythic_gme/comments/1fjv99u/how_to_not_get_hung_up_on_interruptaltered_scenes/)). La 2e accorde d'ailleurs davantage de pouvoir aux choix du joueur, et le test de scène peut être écarté lorsqu'il ne servirait pas le récit ([PDFCoffee — Mythic GME 2e](https://pdfcoffee.com/mythic-game-master-emulator-2nd-edition-tana-pigeon-2-pdf-free.html)).

## **Les Tables de Signification (Meaning Tables)** [[inspirations]]

* Développées par Tana Pigeon en 2003, ces tables de comparaison à deux mots permettent de répondre aux questions ouvertes.
* Générez des idées complexes en combinant des mots tirés sur des tables d100 dédiées aux Actions, aux Descriptions et aux Éléments.
* Ces associations de mots injectent de la vie et des surprises narratives dans une scène, par exemple en associant les concepts "Adorer" et "Devoir".
* Interprétez toujours les résultats en cherchant la métaphore ou l'ambiance plutôt qu'une signification strictement littérale.

## **Gestion des Listes et du Journal** [[tables-avancement]]

* Tenez à jour une liste des Personnages (PNJ) et une liste des Fils Conducteurs (intrigues en cours).
* Ces listes sont sollicitées lors des événements aléatoires pour ramener un personnage ou une quête spécifique sur le devant de la scène.
* Pour la prise de notes, votre journal n'a pas besoin d'être un texte rédigé avec soin ; des notes rapides, des mots-clés ou des phrases incomplètes conviennent très bien pour documenter l'aventure sans casser le rythme.

[[utilitaires]]
[[references]]
[[inspirations]]

