---
id: "202609290457"
type: permanente
statut: valide
tags:
  - solo
  - journaling
  - numerique
  - ironsworn
date_creation: 2026-09-29
---
# ironsworn-obsidian

Obsidian est l'outil parfait pour *Ironsworn* : ses fonctionnalités natives (callouts, liens internes, modèles) permettent de structurer tes parties de manière très visuelle sans ajouter le moindre superflu rédactionnel.

Voici comment configurer ton coffre (*vault*) pour un journaling minimaliste et hyper-efficace.

## 1. Les Callouts pour isoler la mécanique

Utilise la syntaxe des **Callouts** native à Obsidian pour séparer visuellement la fiction (tes puces) des jets de dés et de la mécanique. Le texte de ton histoire reste fluide, et la mécanique est isolée dans des blocs stylisés.

```markdown
* Progression lente sous la pluie battante.
* Aperçu d'une fumée au loin : le village de Ravencroft.

> [!info] Jet : Faire face au danger (Ombre)
> **Stat :** Ombre +2 | **Dés :** 4 vs [6, 2] -> **Succès mitigé (+)**
> *Complication :* Ravitaillement -1 (torche trempée).

> [!question] Oracle : Action / Thème
> `Révéler` / `Créature` + **Match (⚡)**
> -> Embuscade d'un molosse des ombres.

```

## 2. Le Worldbuilding « 0 clics » avec les liens `[[ ]]`

Ne perds plus de temps à décrire un PNJ, un lieu ou un objet dans ton journal de scène. Contente-toi de créer un lien interne :

* Dans ton fil de texte : `> Rencontre avec [[Kaelen]], le forgeur de runes à [[Ravencroft]].`
* **L'avantage Obsidian :** En survolant le lien avec la touche `Ctrl` (ou `Cmd`), tu affiches la fiche sans quitter ta scène. Si la note n'existe pas encore, laisse le lien en violet : tu la créeras seulement si le PNJ devient récurrent.

## 3. Pistes de Progrès et Jauges en texte brut

Pour suivre tes jauges et tes serments directement dans ta note de session sans alourdir ta page, tu peux utiliser des caractères Unicode ou de simples cases à cocher Markdown.

```markdown
### Jauges actuelles
- **Santé :** `[🟩🟩🟩🟥🟥]` (3/5)
- **Esprit :** `[🟩🟩🟩🟩🟥]` (4/5)
- **Ravitaillement :** `[🟩🟩🟥🟥🟥]` (2/5)
- **Impulsion :** `+4`

### Serment : Libérer Ravencroft (Troublant)
- Progress : [x] [x] [x] [ ] [ ] [ ] [ ] [ ] [ ] [ ] (3/10)

```

## 4. L'extension dédiée : *Iron Vault*

Si tu ne l'utilises pas encore, installe le plugin communautaire **Iron Vault** (disponible directement dans les paramètres d'Obsidian > *Extensions communautaires*).

* **Ce qu'il fait :** Il intègre directement les règles, les mouvements et les tables d'oracles d'Ironsworn (et Starforged) dans Obsidian.
* **Gain de temps :** Tu peux tirer un oracle ou exécuter un mouvement d'un simple raccourci clavier ou via la palette de commandes. Le résultat s'insère automatiquement dans ton texte au format minimaliste.

## 5. La vue *Canvas* (Tableau blanc) pour la cartographie

Plutôt que d'écrire des paragraphes sur les relations entre les factions ou la géographie de ton secteur :

1. Ouvre un **Canvas** Obsidian pour ta campagne.
2. Glisse tes cartes de PNJ et de lieux sous forme de cartes visuelles.
3. Relie-les avec des flèches annotées (ex: `[[Kaelen]]` -- *Rivalité* --> `[[Thora]]`).

