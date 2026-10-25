# 📈 Progression

> Monte en grade, débloque des compétences et équipe tes anneaux.

## ⚡ En bref

Il existe six grades de jeu : **Guerrier** (départ), **Chevalier**, **Duc**, **Baron**, **Seigneur** et **Roi**.

- Tu gagnes de l'**or** en jouant et tu le dépenses pour monter de grade (`/rankup`).
- Tu gagnes des **pièces d'argent** avec les [quêtes](quetes.md) et tu les dépenses pour débloquer des compétences (`/skill`).
- Chaque grade ouvre de nouvelles compétences et les rangs les plus hauts demandent beaucoup de compétences.

Ces grades de jeu ne sont pas les grades de la boutique : voir [Grades](../general/grades.md).

## 🥇 Le rankup

Tu gagnes **1 pièce d'or toutes les 30 minutes de jeu**. Ouvre l'écran de progression avec `/rankup`, puis valide avec `/rankup confirm`.

| Grade visé | Pièces d'or | Compétences débloquées (total) | Places |
|---|---|---|---|
| Chevalier | 30 | 6 | Illimitées |
| Duc | 50 | 14 | Illimitées |
| Baron | 70 | 20 | Illimitées |
| Seigneur | 90 | 27 | **15** |
| Roi | 100 | 0 | **5** |

L'or est **dépensé** à la promotion. Le nombre de compétences est le total de celles que tu as débloquées, tous grades confondus.

Messages que tu peux croiser :

- « Félicitations ! Tu es maintenant X ! »
- « Il te manque N pièce(s) d'or (x/y). »
- « Il te manque N compétence(s) (x/y). »
- « Les N places de X sont prises. Tu dois en tuer un pour prendre sa place ! »

### Prendre la place d'un Seigneur ou d'un Roi

Quand toutes les places d'un grade sont prises, tu peux **renverser** l'un des détenteurs :

1. Tu dois être au grade juste en dessous (Baron pour Seigneur, Seigneur pour Roi).
2. Tu dois avoir l'or et les compétences demandés.
3. Tu **tues** un détenteur du grade : tu prends sa place, tu paies l'or, et lui redescend d'un grade.

Si tu gagnes le combat sans remplir les conditions, le jeu te dit ce qu'il te manque : « Tu as vaincu un X mais il te manque N pièce(s) d'or / compétence(s) pour prendre sa place. »

Une annonce globale « X vient de devenir Y ! » prévient tout le monde.

## 🌳 L'arbre de compétences

Ouvre-le avec `/skill` (ou `/competences`). Pour débloquer une compétence, il faut :

- Être au grade de la compétence **ou plus haut**.
- Avoir assez de **pièces d'argent** (coût indiqué ci-dessous).
- Avoir débloqué sa compétence **parente**, quand elle en a une.

<details>
<summary>⚔️ Guerrier (7 compétences)</summary>

| Compétence | Effet | Coût | Parent |
|---|---|---|---|
| Pied-à-terre | +1 home | 1 | |
| Négociant | +2 emplacements à l'hôtel des ventes | 2 | Pied-à-terre |
| Tonnelier | Fabriquer le Tonneau | 2 | |
| Maître brasseur | Récolter les cervoises du Tonneau | 1 | Tonnelier |
| Artificier | Utiliser la Dynamite | 2 | |
| Forge primordiale | Utiliser l'Enclume Primordiale | 2 | |
| Embouteilleur | `/bottlexp <niveaux>` : stocke ton XP dans une bouteille sans perte | 2 | |

</details>

<details>
<summary>🛡️ Chevalier (9 compétences)</summary>

| Compétence | Effet | Coût | Parent |
|---|---|---|---|
| Négociant II | +2 emplacements à l'hôtel des ventes | 2 | |
| Stratège | +10 % d'XP sur les quêtes de faction | 2 | |
| Forgeron primordial | Fabriquer l'Enclume Primordiale | 3 | Stratège |
| Accès marché | `/warp shop` | 1 | Forgeron primordial |
| Coffre étendu I | +1 ligne à ton Ender Chest | 2 | |
| Pied-à-terre II | +1 home | 1 | Coffre étendu I |
| Écurie | `/monture` | 2 | |
| Stèle maudite | Fabriquer la Stèle maudite (voir [Guerre](guerre.md)) | 3 | Pied-à-terre II |
| Emplacement d'anneau I | Débloque le 1er emplacement d'anneau | 2 | |

</details>

<details>
<summary>🏹 Duc (5 compétences)</summary>

| Compétence | Effet | Coût | Parent |
|---|---|---|---|
| Coffre étendu II | +1 ligne à ton Ender Chest | 2 | |
| Pied-à-terre III | +1 home | 1 | Coffre étendu II |
| Cuirasse | −10 % de dégâts subis sur les coups critiques | 3 | |
| Stratège II | +10 % d'XP sur les quêtes de faction | 2 | |
| Artificier aquatique | Utiliser la Dynamite aquatique | 3 | Stratège II |

</details>

<details>
<summary>🏰 Baron (7 compétences)</summary>

| Compétence | Effet | Coût | Parent |
|---|---|---|---|
| Filon d'Aria | 0,25 % de chance d'obtenir une Pépite d'Aria en minant un minerai naturel | 3 | |
| Négociant III | +2 emplacements à l'hôtel des ventes | 2 | |
| Coffre étendu III | +1 ligne à ton Ender Chest | 2 | Négociant III |
| Frappe puissante | +5 % de dégâts infligés | 3 | Coffre étendu III |
| Érudit | +10 % d'XP gagnée avec les orbes (hors duel et tournoi) | 3 | |
| Pied-à-terre IV | +1 home | 2 | |
| Emplacement d'anneau II | Débloque le 2e emplacement d'anneau | 3 | Emplacement d'anneau I |

</details>

<details>
<summary>💎 Seigneur (5 compétences)</summary>

| Compétence | Effet | Coût | Parent |
|---|---|---|---|
| Bon négoce | +5 % sur le montant de tes ventes | 4 | |
| Foulée rapide | Vitesse II permanente | 4 | |
| Peau de braise | Résistance au feu permanente | 4 | |
| Célérité I | Précipitation I permanente avec un outil en main | 4 | |
| Emplacement d'anneau III | Débloque le 3e emplacement d'anneau | 4 | Emplacement d'anneau II |

</details>

<details>
<summary>👑 Roi (6 compétences)</summary>

| Compétence | Effet | Coût | Parent |
|---|---|---|---|
| Grand négoce | +15 % sur les ventes au shop | 5 | |
| Vigueur | Force I permanente | 5 | |
| Cape royale | `/invi` | 5 | |
| Cœur de roi | +1 cœur | 5 | Cape royale |
| Célérité II | Précipitation II permanente | 5 | |
| Célérité III | Précipitation III permanente | 6 | Célérité II |

</details>

Les coûts sont en **pièces d'argent**, que tu gagnes avec les [quêtes](quetes.md).

## 💍 Les anneaux

Les anneaux sont des bijoux qui te donnent un bonus permanent tant que tu les portes. Tu les obtiens en récompense des donjons : voir [PvE](pve.md).

| Anneau | Effet |
|---|---|
| Anneau d'Antichute | Annule les dégâts de chute |
| Anneau de Résistance au Feu | Résistance au feu |
| Anneau de Résistance | −5 % de dégâts subis (sauf vide, famine et suicide) |
| Anneau de Vitesse II | Vitesse II |
| Anneau de Force I | Force I |

### Les emplacements

Tu as **3 emplacements** d'anneau, débloqués par les compétences **Emplacement d'anneau I** (Chevalier), **II** (Baron) et **III** (Seigneur). Seuls les emplacements débloqués fonctionnent : un anneau dans une case verrouillée n'a aucun effet.

{% hint style="info" %}
Deux anneaux identiques ne cumulent pas leurs effets.
{% endhint %}

{% hint style="warning" %}
À ta mort, tes anneaux tombent comme ton armure. Fais attention à ce que tu emportes au combat !
{% endhint %}

## ⌨️ Commandes

| Commande | Effet | Qui peut l'utiliser |
|---|---|---|
| `/rankup` (`/grade`, `/rang`) | Ouvre l'écran de progression | Tous |
| `/rankup confirm` | Valide ta montée de grade | Tous |
| `/skill` (`/competences`) | Ouvre l'arbre de compétences | Tous |
| `/bottlexp <niveaux>` | Stocke ton XP dans une bouteille | Compétence Embouteilleur |
| `/warp shop` | Va au marché | Compétence Accès marché |
| `/monture` | Ouvre ton écurie | Compétence Écurie |
| `/invi` | Active ou désactive ton invisibilité | Compétence Cape royale |

Pour les classements Seigneur & Roi, voir [Classements](classements.md).
