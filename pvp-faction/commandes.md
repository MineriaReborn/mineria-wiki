# ⌨️ Commandes PvP-Factions

> Toutes les commandes du mode Faction, rangées par thème.

## ⚡ En bref

- `/f` affiche l'aide des factions.
- Les commandes communes à tout Mineria (homes, warps, `/spawn`, `/tpa`, messages privés, `/report`…) sont dans [Commandes](../general/commandes.md).
- Les commandes liées à ton grade (`/craft`, `/ec`, `/repair`, `/near`…) sont dans [Grades](../general/grades.md).
- En combat, `/spawn`, `/home`, `/tpa`, `/warp`, `/ec`, `/craft` et `/repair` sont désactivées pendant 30 secondes.

***

## 🏰 Factions

| Commande | Effet | Qui peut l'utiliser |
| --- | --- | --- |
| `/f` | Affiche l'aide | Tous |
| `/f create <nom>` | Crée une faction | Tous, sans faction |
| `/f invite <joueur>` (`inv`) · `/f deinvite <joueur>` | Invite ou retire une invitation | Modérateur et plus |
| `/f join <faction>` (`accept`) | Rejoint une faction | Tous, sans faction |
| `/f leave` | Quitte la faction | Membres |
| `/f kick <joueur>` | Exclut un joueur | Modérateur et plus |
| `/f leader <joueur>` | Transfère le rôle de Leader | Leader |
| `/f promote` · `/f demote` · `/f mod` · `/f member` | Change le rôle d'un joueur | Leader |
| `/f title` | Donne un titre à un joueur | Modérateur et plus |
| `/f open` | Ouvre ou ferme la faction | Leader |
| `/f description <texte>` | Change la description | Modérateur et plus |
| `/f tag <nom>` (`rename`) | Renomme la faction | Modérateur et plus |
| `/f show [faction]` (`who`) · `/f list [page]` | Fiche et liste des factions | Tous |
| `/f map` (`/fmap`) | Affiche ou masque la carte des claims à l'écran | Tous |
| `/f claim [rayon]` · `/f autoclaim` · `/f unclaim` · `/f unclaimall` | Gère les claims | Modérateur et plus |
| `/f disband` | Dissout la faction | Leader |
| `/f perm` | Règle les permissions par rôle | Leader |
| `/f home` | Se téléporte au home | Tous les membres |
| `/f sethome` | Déplace le home | Leader |
| `/f warp [set\|del\|list\|<nom>]` | Warps de faction | Selon le niveau |
| `/f chest` | Coffre de faction | Membres, selon le niveau |
| `/f bank [deposit\|withdraw] <montant>` | Banque de faction | Dépôt : tous · retrait : Modérateur et plus |
| `/f power [joueur]` · `/f xp [joueur]` · `/f avantages` | Infos de power, d'XP et d'avantages | Tous |
| `/f ally` · `/f truce` · `/f enemy` · `/f neutral` | Relations | Modérateur et plus |
| `/ff` · `/fa` · `/ft` · `/fp` | Chats de faction, alliés, trêves, public | Tous |

Détails : [Factions](factions.md).

***

## ⚔️ Guerre et pillage

| Commande | Effet | Qui peut l'utiliser |
| --- | --- | --- |
| `/f contrat <faction>` | Propose un contrat de guerre | Leader |
| `/f contrat accepter` · `/f contrat refuser` | Répond à une proposition | Leader |
| `/f sethome pillage` | Pose un home de pillage en claim ennemi | Faction de niveau 7 minimum |
| `/f home pillage` | Y retourne | Faction de niveau 7 minimum |
| `/f antisethome` | Protège ton territoire des homes de pillage | Selon le niveau |

Détails : [Guerre et pillage](guerre.md).

***

## 📈 Progression

| Commande | Effet | Qui peut l'utiliser |
| --- | --- | --- |
| `/rankup` (`/grade`, `/rang`) | Ouvre l'écran de progression | Tous |
| `/rankup confirm` | Valide ta montée de grade | Tous |
| `/skill` (`/competences`) | Ouvre l'arbre de compétences | Tous |
| `/monture` (`/mount`) | Ouvre ton écurie | Compétence Écurie |
| `/invi` | Active ou désactive ton invisibilité (pas en duel, en tournoi ni en Mob Zone) | Compétence Cape royale |

Détails : [Progression](progression.md).

***

## 💰 Économie

| Commande | Effet | Qui peut l'utiliser |
| --- | --- | --- |
| `/balance [joueur]` (`/bal`, `/money`) | Affiche un solde | Tous |
| `/pay <joueur> <montant>` | Envoie de l'argent | Tous |
| `/warp shop` | Te téléporte à la zone Shop | Compétence Accès marché |
| `/hdv` (`/ah`, `/auction`) | Ouvre l'Hôtel des Ventes | Tous |
| `/hdv vendre` (`/hdv sell`) | Met en vente l'item en main | Tous |
| `/trade <joueur>` (`/echange`) | Propose un échange | Tous |
| `/trade accept <joueur>` · `/trade deny <joueur>` | Accepte ou refuse un échange | Tous |
| `/spawner` | Liste tes spawners | Tous |
| `/spawner send <joueur> <entité>` | Donne un de tes spawners | Tous |
| `/spawner sendfaction <entité>` | Donne un de tes spawners à ta faction | Membres de faction |
| `/f spawners` | Ouvre les spawners de ta faction | Faction de niveau 30, selon ton rôle |
| `/bottlexp [niveaux]` | Met ton XP en bouteille, sans perte | Compétence Embouteilleur |
| `/reserve` | Récupère les items livrés en [Réserve](../general/reserve.md) | Tous |

Détails : [Économie](economie.md).

***

## 🎁 Box, kits et dons

| Commande | Effet | Qui peut l'utiliser |
| --- | --- | --- |
| `/kit` | Liste les kits | Tous |
| `/kit <nom>` | Récupère un kit (toutes les 24 h) | Selon ton grade ou tes box |
| `/kit view <nom>` | Montre le contenu d'un kit | Selon ton grade ou tes box |
| `/dons send <partenaire> <message>` (`/gift`, `/don`) | Envoie un don à un partenaire | Tous |
| `/dons menu` | Récupère les dons reçus | Partenaires |
| `/dons toggle` | Active ou désactive la réception | Partenaires |
| `/dons block <pseudonyme>` | Bloque un joueur | Partenaires |

Détails : [Box](box.md) et [Grades](../general/grades.md).

***

## 🌲 PvE

| Commande | Effet | Qui peut l'utiliser |
| --- | --- | --- |
| `/rtp confirm` · `/rtp cancel` | Confirme ou annule la téléportation proposée par le PNJ Téléporteur | Tous |
| `/epee` (`/sword`) | Personnalise le Dard Royal, en Mob Zone | Tous |
| `/dungeon` | Affiche l'aide des donjons | Tous |
| `/dungeon quit` | Abandonne ton donjon (clé non remboursée) ou quitte la file d'attente | Tous |
| `/spawn` | Quitte la Mob Zone et retourne au spawn | Tous |

Détails : [PvE](pve.md).

***

## 🎉 Événements et quêtes

| Commande | Effet | Qui peut l'utiliser |
| --- | --- | --- |
| `/event` | Affiche l'aide des événements | Tous |
| `/event info` | Événement en cours, top 3, prochains événements | Tous |
| `/event top` | Top 10 de l'événement en cours | Tous |
| `/planning` (`/event planning`) | Ouvre le planning | Tous |
| `/quest` (`/quete`, `/quetes`, `/quests`) | Ouvre tes quêtes personnelles | Tous |
| `/f quest` | Ouvre les quêtes de faction | Membres d'une faction |

Détails : [Événements](evenements.md) et [Quêtes](quetes.md).

***

## 🤺 Tournois

| Commande | Effet | Qui peut l'utiliser |
| --- | --- | --- |
| `/tournament` (`/tournoi`) | Affiche l'état du tournoi | Tous |
| `/tournament teams` (`/tournament equipes`) | Liste les équipes | Tous |
| `/tournament create [nom]` | T'inscris en solo ou crées une équipe | Tous, pendant les inscriptions |
| `/tournament invite <joueur>` | Invite un joueur dans ton équipe | Chef d'équipe |
| `/tournament join <équipe ou joueur>` | Rejoint une équipe qui t'a invité | Joueur invité |
| `/tournament leave` | Quitte l'équipe ou le tournoi | Tous, avant le début |
| `/tournament spec` (`/tournament spectate`) | Va regarder depuis le lobby | Tous |
| `/tournament help` | Affiche l'aide | Tous |

Les duels 1v1 passent par le PNJ **Duel** de l'arène, sans commande : voir [Duels](duels.md).

***

## 🏆 Classements

| Commande | Effet | Qui peut l'utiliser |
| --- | --- | --- |
| `/classement` (`/classements`) | Ouvre l'écran des classements | Tous |
| `/classement <grade\|faction\|chasseur\|mineur\|marchand\|richesse>` | Ouvre un classement précis | Tous |

Détails : [Classements](classements.md).
