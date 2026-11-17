---
name: learning-module
description: Concevoir ou faire évoluer un module d’apprentissage, son découpage en épisodes, ses supports et ses passes de révision. Utiliser pour cadrer la recherche documentaire, constituer le corpus, préparer la référence pédagogique ou organiser la progression de l’apprenant. La réalisation technique des supports relève de mlunit.
---

# Modules d’apprentissage — épisodes, supports et passes

## Le modèle

Un **module** organise l’apprentissage d’un domaine pour atteindre un objectif : comprendre, appliquer des techniques, résoudre des problèmes ou préparer un examen.

Le module contient **un ou plusieurs épisodes ordonnés**. Chaque épisode couvre un sujet cohérent,
avec des savoirs et des savoir-faire. Le plan organise les concepts et leurs relations en
sous-catégories logiques, nommées avec soin ; l’ordre des épisodes construit une progression.

Un **épisode** désigne cette réalité métier : une étape dans le séquençage des choses à apprendre.
Une **unité** désigne la réalité physique dans KIAO : un dossier, son document `.mlunit.json` et
ses fichiers de contenu. Ces notions sont liées, mais ne sont pas synonymes ; le découpage en
épisodes ne prescrit pas à lui seul la répartition des fichiers en unités.

On **découpe sans planifier dans le temps**. Le plan décrit les sujets, leurs relations et leur
ordre ; ne pas y faire persister de calendrier, de dates, d’espacement entre passes ni de budget
de temps par épisode.

Les **supports** sont les documents pédagogiques d’un épisode : cours, podcasts, exercices,
tutoriels. Un épisode peut en proposer **plusieurs types**.
Le choix dépend du rôle pédagogique et de la passe demandée. Tous les
types de supports ne sont pas nécessaires à chaque épisode ni à chaque passe.

Une **passe** est un nouveau parcours du module par l’apprenant. Elle revisite ses épisodes avec
une intention et une profondeur propres. Lors de la production, pour chaque épisode et chaque
passe, identifier ce qui est déjà acquis, ce qui sera approfondi et les supports à proposer
ou enrichir.
Conserver les acquis des passes précédentes et renouveler les exemples, questions et exercices.

## Organiser les passes

Le parcours de référence comporte **cinq passes**. À partir de la deuxième, **chaque passe réactive
les acquis de la précédente**.

| Passe | Intention et niveau visé |
|---|---|
| 1 — Guide de survie | Installer rapidement les intuitions, les concepts et les savoir-faire minimaux pour s’en sortir lors d’une discussion superficielle. |
| 2 — Acquisition des bases | Installer les concepts, les intuitions et les savoir-faire de base ; viser environ les deux tiers de l’objectif. |
| 3 — Niveau de l’objectif | Installer les connaissances et les savoir-faire permettant d’atteindre l’objectif. |
| 4 — Entraînement et révisions | Consolider les acquis de la passe précédente par des rappels et des entraînements supplémentaires. |
| 5 — Approfondissement | Mêler cours et pratique pour dépasser l’objectif, afin que son atteinte soit ressentie comme facile. Viser environ 125 % de l’objectif : savoir un peu plus et aller plus loin dans la mobilisation ou la maîtrise. |

Adapter ce parcours lorsqu’une autre organisation est demandée. Les passes décrivent une
progression pédagogique, sans calendrier ni intervalle à enregistrer. Une intervention de
production cible un épisode, une passe et une sélection de supports. Approfondir une passe ne
consiste pas à recopier les supports de la précédente.

## Rôles des supports

| Support | Rôle |
|---|---|
| Podcast de vocabulaire | Préparer linguistiquement l’ensemble de l’épisode : termes du domaine et expressions avancées. |
| Podcast d’introduction | Avant l’étude formelle, activer les connaissances antérieures et le besoin de savoir, à partir d’un récit concret ou d’un problème. |
| Podcast de questions ouvertes d’introduction | Avant l’étude, faire verbaliser connaissances et raisonnements, puis apporter les éléments d’une réponse solide. |
| Cours écrit | Enseignement progressif et illustré de l’épisode. |
| Cours audio | Enseignement progressif de l’épisode, en modalité audio. |
| Exercices écrits | Application par des problèmes courts et des mini-études de cas. |
| Podcast de questions ouvertes d’entraînement | Après l’étude, mobiliser les acquis par des questions et des problèmes demandant un développement oral. |
| Tutoriel | Mise en pratique des savoirs et savoir-faire de l’épisode. |

Comment réaliser chaque support — durées, formats, règles d’écriture — relève du skill `mlunit`.

## Préparer la matière pédagogique

**Cadrage de la recherche.** Partir de l’objectif de l’apprenant et décrire les connaissances et
techniques à couvrir, les types de contenus à rechercher et les critères de qualité. Pour un
examen, inclure sa nature et son format, les concepts, des questions corrigées et des cas
pratiques. Les proportions dépendent du sujet ; celles d’un exemple ne sont pas un barème général.

**Corpus.** Réunir de quoi enseigner les concepts avec des exemples et les savoir-faire avec des
procédures, problèmes résolus et tutoriels. Prévoir la profondeur et la variété nécessaires à
l’ensemble des passes, du niveau initial jusqu’au dépassement de l’objectif prévu à la dernière
passe. Retenir des sources fiables, actuelles pour la version étudiée et cohérentes ; exploiter
les apports de plusieurs langues. Éliminer les doublons au profit du meilleur passage, le
hors-sujet et les informations dépassées.

**Plan et référence.** Réorganiser et rapprocher le corpus pour produire le plan progressif du
module et son dossier de référence. Celui-ci contient un sous-dossier autonome par épisode, nommé
**`E01-titre-de-l-episode`**, `E02-titre-de-l-episode`, etc. : `E`, le numéro de l’épisode sur deux
chiffres, un tiret et le titre en minuscules avec des tirets entre les mots.

Chaque sous-dossier rassemble toute la matière nécessaire aux passes futures, sans devoir
retourner au corpus. L’organiser par sujets, concepts, exemples, problèmes et techniques,
**sans classement ni sous-dossiers par passe**.
Si des passes sont précisées en entrée, elles donnent seulement une idée du volume, de la
profondeur et de la nature du matériel à réunir.

La référence est **découplée de la structure finale de livraison** : elle ne définit ni les
supports de chaque passe, ni leur ordre, ni les fichiers ou l’arborescence du dossier final.
Le format de référence et le format livré peuvent ainsi évoluer séparément. Un changement de
méthode pédagogique peut réutiliser la matière préparée, sans rejouer toute la recherche et
la constitution du corpus tant que cette matière reste suffisante et actuelle.