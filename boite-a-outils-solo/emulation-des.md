---
titre: Émuler des jets de dés sans les lancer
aliases: [Jets de dés silencieux, Générateur d'aléatoire sans dés, Diceless RNG]
tags: [jeux, dés, aléatoire, rng, jdr, astuce]
créée: 2026-10-30
type: fiche-méthode
---

# Émuler des jets de dés sans les lancer

Simuler un d6, un d10 ou un d20 sans secouer de dés : sans bruit, sans perte, sans application ni service web.

## Principe général

Tout générateur uniforme de chiffres alimente n'importe quel dé, à deux conditions :

1. **Rejet** : pour un d6 à partir de chiffres de 0 à 9, conserver 1 à 6 et rejeter 0, 7, 8, 9. Un modulo direct (chiffre mod 6) serait biaisé, car les résidus 0 à 3 apparaissent deux fois et les résidus 4 et 5 une seule fois.
2. **Parité** : une source paire ou impaire uniforme double une plage. Un d10 suivi d'un pair ou impair donne un d20 exact (pair : 1 à 10, impair : 11 à 20, ou l'inverse).

Règle associée : [[Biais humain]] — une personne qui choisit « au hasard » ne le fait jamais uniformément ; tout dispositif doit donc éliminer le choix humain du point de décision (roue, tirage aveugle, instant non choisi).

## Analyse des pistes envisagées
   Méthode | Bruit | Équiprobabilité | Disponibilité | Verdict |
 | --- | --- | --- | --- | --- |
 | Plaques d'immatriculation | Nul | Bonne (dernier chiffre) | Uniquement en circulation, débit imprévisible | Source d'appoint, jamais principale |
 | Dés tenus en main | Nul immobile, élevé au secouage | Nulle immobile : aucune entropie sans secousse | Permanente | À écarter |
 | Boîte transparente | Moyen, atténuable | Bonne | Permanente | Viable avec doublure et dés souples |
 | Dice spinner | Nul | Bonne | Permanente | Recommandé (achat) |
 | Lego | Nul à faible | Bonne | Permanente | Recommandé (fabrication) |
 | Cartes numérotées (x10) | Nul | Bonne si coupe et tirage face cachée | Permanente | Fiable mais lent |
 | Plaque ronde et doigt | Nul | Mauvaise (biais humain) | Permanente | À convertir en roulette |

### Détail des pistes

- **Plaques d'immatriculation** : dernier chiffre pour un d10 (0 lu comme 10) ; pour un d6, rejeter 0, 7, 8, 9 ; pour un d20, dernier chiffre pour l'unité et avant-dernier chiffre pour la parité. Deux chiffres d'une même plaque suffisent. Limite : il faut des voitures, au moment où l'on en a besoin, et l'échantillon n'est pas contrôlé.
- **Dés tenus en main** : un dé immobile n'est pas aléatoire ; seule la secousse crée de l'entropie, au prix du bruit et du risque de chute. Variante acceptable : dés en mousse secoués dans une poche de vêtement, tissu contre tissu.
- **Boîte transparente doublée** : coller de la feutrine ou de la mousse à l'intérieur, utiliser des dés en mousse ou en bois léger, secouer sous un vêtement ou une couverture. Reste la méthode la plus proche d'un jet réel.
- **Dice spinner** : roulette à pointeur dédiée. Silencieux, rapide, uniforme. Vérifier la fluidité du roulement, un axe qui s'arrête vite introduit un biais de secteur. Variante : toupie à dés en bois (faces numérotées), quasi silencieuse sur un tissu.
- **Cartes** : dix cartes numérotées 1 à 10. Le mélange à la main est lent et malaisé ; le remplacer par une coupe : le tas posé face cachée, couper à un endroit quelconque, lire la carte du dessus. Pour un d6 : tirer, rejeter 7 à 10, remettre sous le tas. Pour un d20 : premier tirage pour la parité (1 à 5 : dizaine basse, 6 à 10 : dizaine haute), remettre la carte sous le tas, second tirage pour l'unité. Deux tirages avec remise donnent un d20 exact.
- **Plaque ronde et doigt** : le pointé humain privilégie certaines zones (haut, centre) et évite les bords. Conversion possible sans matériel : poser un crayon au centre de la plaque et le faire tourner sur lui-même comme une toupie ; le secteur désigné à l'arrêt est uniforme. Autre option : fermer les yeux, tourner la plaque d'un tiers de tour inconnu, puis pointer — insuffisant seul, car le biais du doigt demeure.

## Méthodes Lego (fabrication)

1. **Roulette à pointeur** : plateau tournant Technic (turntable 24 et 60 dents) fixé sur une plaque, tuiles ou plaques numérotées disposées en cercle autour de l'axe, flèche montée sur l'axe ; donner une impulsion du doigt. Silencieux et reconfigurable (d6, d10, d20 selon le nombre de secteurs).
2. **Pochette de tuiles** : tuiles 1x1 ou 1x2 numérotées au feutre fin ou à l'autocollant (six tuiles pour un d6, dix pour un d10, vingt pour un d20), tirage à l'aveugle dans un sac en tissu. La méthode la plus simple et la plus fidèle ; trois jeux de tuiles couvrent tous les besoins.
3. **Tour à dés insonorisée** : tour construite en briques, parois garnies de tissu ou de mousse, dés en mousse à l'intérieur. Le bruit tombe à un niveau négligeable.

## Autres solutions sans dés

- **Pièces de monnaie (méthode binaire avec rejet)** : lire les lancers comme un nombre binaire. d6 : trois lancers, valeurs 1 à 8, rejeter 7 et 8. d10 : quatre lancers, valeurs 1 à 16, rejeter 11 à 16. d20 : cinq lancers, valeurs 1 à 32, rejeter 21 à 32. Silencieux si la pièce est rattrapée dans la paume ; un matelas de tissue sous la main couvre le cas d'une chute.
- **Table de résultats pré-générée** : lors d'un moment où le bruit est permis, produire une longue série de résultats (boîte, pièces, vrai lancer) et la noter en liste numérotée. En situation contrainte, lire le résultat suivant dans l'ordre et cocher. Aucun bruit, aucun objet à manipuler, aucun biais si la liste est consommée séquentiellement sans tri. La solution la plus discrète ; la discipline consiste à ne jamais sauter de ligne.
- **Pochette de jetons** : bouchons, jetons de loto, disques en bois gravés ou marqués au feutre, un jeton par valeur. Même logique que la pochette Lego, avec du matériel de récupération.
- **Tuiles de Scrabble** : lettres A à T pour un d20 (une lettre par valeur), A à F pour un d6, A à J pour un d10 ; remettre la tuile après tirage.
- **Aiguille des secondes** : horloge analogique visible ; observer la valeur des secondes (1 à 60) à un instant non délibéré. 60 étant divisible par 6, 10 et 20, le modulo est exact, sans rejet : secondes mod 6 plus 1 pour un d6, mod 10 plus 1 pour un d10, mod 20 plus 1 pour un d20. Condition : ne pas regarder l'horloge à un moment choisi, ce qui réintroduirait un biais.
- **Pages d'un livre** : laisser tomber le livre ouvert, dernier chiffre du numéro de page pour un d10, avant-dernier chiffre pour la parité (d20). L'épaisseur de la page paire ou impaire est uniforme.
- **Somme de deux personnes** : chacune annonce un nombre entre 1 et n sans consulter l'autre ; la somme, réduite modulo n, atténue fortement le biais individuel. Deux annonceurs valent mieux qu'un, qui resterait biaisé.

## Anti-bruit et anti-perte (règles transversales)

- Dés en mousse, en bois léger ou creux ; jamais en résine dure.
- Doublure feutrine, mousse ou tissu polaire dans toute boîte de secouage.
- Secouage dans une poche de vêtement ou sous une couverture plutôt qu'en plein air.
- Contention : boîte à couvercle, plateau à rebords, sac de tirage refermable ; un cordon noué au dé évite la perte en déplacement.

## Choix recommandés
 | Besoin | Solution |
 | --- | --- |
 | Silence total et zéro matériel | Table pré-générée |
 | Silence total et matériel minimal | Pochette de tuiles ou de jetons ; pièces de monnaie |
 | Sensation proche du jet réel | Boîte doublée avec dés en mousse |
 | Rapidité et réutilisation | Dice spinner ou roulette Lego |
 | Improvisation sans préparation | Secondes d'une horloge, pages d'un livre |

## Liens

- [[Probabilité]] — rejet, modulo, parité
- [[Biais humain]] — pourquoi le choix direct est toujours non uniforme
- [[Jeux de rôle]] — contexte d'usage
- [[Obsidian]] — format de la fiche
