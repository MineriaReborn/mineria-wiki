# 🏆 Classements

> Compare-toi aux autres joueurs et aux autres factions.

## ⚡ En bref

Ouvre l'écran **Classements** avec `/classement`. Tu y trouves six classements et une barre de recherche (« Joueur ou faction… ») pour ouvrir la fiche de n'importe qui.

Pour aller directement à un classement : `/classement <grade|faction|chasseur|mineur|marchand|richesse>`.

Les classements se mettent à jour **toutes les 30 secondes** environ.

## 📊 Les six classements

| Classement | Tri | Précisions |
|---|---|---|
| **Seigneur & Roi** | Points (voir plus bas) | Réservé aux joueurs Seigneur ou Roi |
| **Factions** | Niveau, puis XP, puis nom | Affiche niveau, XP, membres et date de fondation |
| **Chasseurs** | Monstres tués | Les mobs de spawner, d'œuf ou d'élevage ne comptent pas (sauf en Mob Zone) |
| **Mineurs** | Blocs minés | Pierre, charbon, fer, or, diamant, émeraude, lapis, redstone et quartz ; les blocs que tu as posés toi-même ne comptent pas |
| **Marchands** | Gains de ventes au shop | Voir [Économie](economie.md) |
| **Richesse** | Solde | Ton argent |

Les joueurs à zéro n'apparaissent pas dans les classements Chasseurs, Mineurs et Marchands.

## 👑 Le classement Seigneur & Roi

Les joueurs qui atteignent les grades de Seigneur et de Roi (voir [Progression](progression.md)) s'affrontent à coups de points.

**Points = bonus de grade + activité + bonus de classement.**

### Bonus de grade

| Grade | Points |
|---|---|
| Seigneur | 1 000 |
| Roi | 10 000 |

Si tu perds ton grade, tu perds le bonus.

### Activité

Tu gagnes des points en étant présent et actif sur le serveur (pas quand tu es AFK).

| Source | Points |
|---|---|
| Présence | 50 par heure |
| En WarZone | +3 par minute |
| Dans la nature | +1 par minute |
| Dans un claim ennemi | +5 par minute |
| Victoire à un event KOTH | 500 |
| Victoire à un event Totem | 500 |
| Victoire à un event Météorite | 500 |

Voir [Événements](evenements.md).

### Bonus de classement

Ta place dans les cinq autres classements rapporte des points (pour les Factions, c'est la place de ta faction).

| Place | Points |
|---|---|
| 1er | 5 000 |
| 2e | 3 000 |
| 3e | 2 000 |
| 4e à 7e | 1 000 |
| 8e à 10e | 500 |

## 🔍 Les fiches

Clique sur un nom pour ouvrir sa fiche.

- **Fiche joueur** : faction, rang, monstres tués, blocs cassés, ventes au shop, solde. Pour un Seigneur ou un Roi : temps en rang, temps en WarZone, en nature, en claim ennemi, victoires KOTH, Totem et Météorite, et l'**activité récente**.
- **Fiche faction** : niveau, expérience, membres, claims, power, alliés, ennemis et meilleurs contributeurs (visibles par la faction et ses alliés).

## 🎁 Récompenses

Il n'y a pas de récompense directe pour les classements : les points du classement **Seigneur & Roi** servent à te comparer aux autres.

## ⌨️ Commandes

| Commande | Effet | Qui peut l'utiliser |
|---|---|---|
| `/classement` (`/classements`) | Ouvre l'écran des classements | Tous |
| `/classement <grade\|faction\|chasseur\|mineur\|marchand\|richesse>` | Ouvre un classement précis | Tous |
