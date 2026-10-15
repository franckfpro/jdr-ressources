# AGENTS.md — jdr-ressources (vault Obsidian / Zettelkasten FR)

Vault Markdown Obsidian, pas de code : pas de build, test, lint ni dépendances. Éditer les `.md` directement.

## Périmètre interdit

- Ne jamais lire, créer ni modifier `_attachments/` (images, rules, podcasts, videos — en grande partie gitignoré, voir `.gitignore`).
- Ne pas toucher `.obsidian/workspace.json` ni `.obsidian/plugins/`. `.obsidian/templates.json` pointe vers `_templates` : le laisser tel quel.

## Structure

- Notes de contenu à la racine (`oracles.md`, `alignements.md`, `table-du-destin.md`…) + dossiers : `tables-de-jets/`, `evenements/`, `construction-de-personnage/`, `boite-a-outils-solo/`.
- `_categories/` : MOCs (un fichier par catégorie : `utilitaires`, `references`, `personnages`, `evenements`, `inspirations`, `descriptions`). Corps = frontmatter + une seule ligne `[[README]]`.
- `_templates/` : modèles de fiches (`fiche-de-personnage*.md`, `tpl-template.md`). `_templates/bases/*.base` : vues Obsidian Bases (filtre `file.ext == "md"`), embarquées via `![[Base.base]]` (cf. `README.md`).
- `.obsidian/core-plugins.json` : `templates`, `properties`, `bases` activés ; `zk-prefixer`, `daily-notes` non structurants — ne pas s'en servir comme convention.

## Convention fiche (Zettelkasten)

Frontmatter obligatoire pour toute note de contenu :
```yaml
---
id: "202609051818"   # string, horodatage unique YYYYMMDDHHmm
type: permanente      # permanente | moc | reference
statut: valide
tags: [...]          # ex: solo, oracle, D20/D100/D6, personnage, utilitaire, reference, inspiration
date_creation: 2026-09-05  # YYYY-MM-DD, non quotée (MOCs : quotée "2026-09-05", conserver le style du fichier)
---
```
Nouvelle fiche : partir de `_templates/tpl-template.md` (`id: "{{date:YYYYMMDDHHmm}}"`, `date_creation: "{{date}}"`), générer un `id` réel unique, tag `placeholder` à remplacer par les vrais tags.

- Fichier : `kebab-case` français, titre H1 = nom du fichier (minuscules, ex `# oracles`), contenu en français.
- Footer obligatoire : wikilinks vers les MOCs concernés en fin de fichier, un par ligne (ex `[[utilitaires]]`, `[[references]]`, `[[personnages]]`, `[[inspirations]]`). Le nom du lien = nom du fichier dans `_categories/`, sans chemin.
- Liens internes en `[[nom-de-fiche]]` (sans chemin ni `.md`). Liens externes en Markdown classique, conservés tels quels.

## Markdown / tableaux

- Tableaux de jets : une ligne d'en-tête + séparateur, dés en en-tête (`d20`, `d100`, `1d6`), plages de résultats (`1-4`, `01 – 10`). Ne pas reformatter ni trier les tables existantes.
- Seul HTML toléré : `<br>` dans les en-têtes de `table-du-destin.md`. Sinon 100 % Markdown (gras `**`, italique `*`, listes `-`/`*`).
- `README.md` est une page d'index de liens externes + `![[Base.base]]` : y ajouter un lien plutôt que créer une note, quand c'est juste une ressource externe.
