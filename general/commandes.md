# ⌨️ Commandes

> Toutes les commandes utiles à un joueur, rangées par thème.

{% hint style="info" %}
**Accès** : « Tous » veut dire que la commande est ouverte à tout le monde. Un grade (par exemple « Duc ou VIP ») veut dire ce grade de jeu ou un grade au-dessus, **ou** n'importe quel grade boutique : voir [Grades](grades.md). « Faction » veut dire que la commande ne marche que sur le serveur **PvP-Factions**.
{% endhint %}

## 🌐 Réseau

| Commande | Effet | Accès |
| --- | --- | --- |
| `/hub` (`/lobby`) | Te renvoie vers un hub. | Tous |
| `/classement` | Affiche le classement du serveur où tu es : voir [Classements](classements.md). | Tous |
| `/file` (`/queue`) · `/file quitter` | Affiche ta place dans la file d'attente, ou la quitte. | Tous |
| `/list` | Liste des joueurs connectés. | Tous |
| `/ping` (`/ms`) | Affiche ta latence. | Tous |
| `/aide` (`/help`) | Donne le lien vers ce wiki. | Tous |
| `/wiki` | Ouvre le wiki en jeu. | Tous |

Plus de détails : [Serveurs et hub](serveurs.md).

## 📍 Déplacements

| Commande | Effet | Accès |
| --- | --- | --- |
| `/home [nom]` | Te téléporte à un home. Sans nom, affiche la liste. | Tous · Faction |
| `/homes` | Liste tes homes (cliquables) avec « Total : n/limite ». | Tous · Faction |
| `/sethome <nom>` | Crée un home (lettres, chiffres, `-` et `_`). Ta limite dépend de ton [grade](grades.md). | Tous · Faction |
| `/delhome <nom>` | Supprime un home. | Tous · Faction |
| `/warps` (`/warp`) | Ouvre le menu des warps : un clic te téléporte. Voir [Kits et warps](../pvp-faction/kits-et-warps.md). | Tous · Faction |
| `/warp <nom>` | Te téléporte directement à un warp. | Tous · Faction |
| `/warp info <nom>` | Infos sur un warp. | Tous · Faction |
| `/spawn` | Retour au spawn. | Tous · Faction |
| `/tpa <joueur>` (`/call`) | Demande à te téléporter à un joueur. La demande expire après 10 secondes. | Tous · Faction |
| `/tpyes` (`/tpaccept`) | Accepte une demande de téléportation. | Tous · Faction |
| `/tpno` (`/tpdeny`) | Refuse une demande de téléportation. | Tous · Faction |
| `/back` (`/return`) | Retour à ta dernière position. | Chevalier ou VIP · Faction |

Dans le menu `/warps`, chaque warp est marqué **Ouvert**, **Fermé** ou **Verrouillé**. Au départ, le seul warp ouvert est **Portail**. Le warp **Shop** se débloque avec la compétence « Accès marché » : voir [Progression](../pvp-faction/progression.md).

{% hint style="warning" %}
Une téléportation demande de **rester immobile 5 secondes** (« Téléportation dans 5 secondes, ne bouge pas ! »). Bouger l'annule. Elle est impossible en combat.
{% endhint %}

## 💰 Argent

| Commande | Effet | Accès |
| --- | --- | --- |
| `/balance [joueur]` (`/bal`, `/money`) | Affiche ton solde, ou celui d'un joueur. | Tous · Faction |
| `/pay <joueur> <montant>` | Envoie de l'argent à un joueur connecté. | Tous · Faction |

Limites de `/pay` : montant entier de 1 à 100 000, 3 secondes entre deux paiements, 500 000 $ envoyés au maximum par période de 24 h, pas d'auto-paiement. Détails de l'économie : [Économie](../pvp-faction/economie.md).

## 🎒 Objets et inventaire

| Commande | Effet | Accès |
| --- | --- | --- |
| `/kits` (`/kit`) | Ouvre le menu des kits. `/kit <nom>` réclame un kit directement. | Tous · Faction |
| `/kit view <nom>` | Ouvre le menu sur ce kit, même si tu ne l'as pas (aperçu). | Tous · Faction |
| `/corbeille` (`/trash`, `/poubelle`) | Ouvre une poubelle. | Tous |
| `/craft` (`/workbench`, `/crafting`) | Ouvre un établi. | Duc ou VIP · Faction |
| `/enderchest` (`/ec`) | Ouvre ton coffre de l'Ender. | Duc ou VIP · Faction |
| `/condense` (`/compact`, `/block`) | Transforme tes lingots et gemmes en blocs. | Duc ou VIP · Faction |
| `/uncondense` (`/uncompact`, `/unblock`) | Retransforme des blocs en lingots ou gemmes. | Duc ou VIP · Faction |
| `/repair` (`/fix`) | Répare l'objet en main, puis délai selon ton grade. | Duc ou SuperVIP · Faction |
| `/feed` (`/eat`) | Remplit ta faim. | Baron ou VIP · Faction |
| `/furnace` (`/cook`, `/four`, `/cuire`) | Cuit la pile que tu tiens en main. | Seigneur ou VIP · Faction |
| `/near [rayon]` | Liste les joueurs proches. | Duc ou VIP · Faction |
| `/bottlexp [niveaux]` | Met ton XP en bouteille, sans perte. | Compétence « Embouteilleur » · Faction |

Le menu des kits est expliqué dans [Kits et warps](../pvp-faction/kits-et-warps.md). Les kits de grade et les kits métier sont détaillés dans [Grades](grades.md) et [Box](../pvp-faction/box.md).

## 💬 Chat

| Commande | Effet | Accès |
| --- | --- | --- |
| `/msg <joueur> <message>` (`/m`, `/w`, `/tell`, `/message`) | Message privé. | Tous |
| `/r <message>` (`/reply`) | Répond au dernier message privé. | Tous |
| `/ignore <joueur>` | Bloque les MP et masque le chat public d'un joueur (pas le staff). | Tous |
| `/unignore <joueur>` | Retire l'ignorance. | Tous |
| `/report <joueur>` | Ouvre le formulaire de signalement. | Tous |

Plus de détails : [Chat](chat.md) et [Règles](regles.md).

## ⚔️ Combat et vie du joueur

| Commande | Effet | Accès |
| --- | --- | --- |
| `/ct` (`/combat`, `/combatlog`, `/combattag`) | Affiche le temps de combat restant. | Tous |
| `/playtime [joueur]` | Affiche ton temps de jeu. | Tous |
| `/monture` (`/mount`) | Ouvre ton écurie. | Compétence « Écurie » · Faction |
| `/invi` | Active ou désactive ton invisibilité (pas en duel, en tournoi ni en Mob Zone). | Compétence « Cape royale » · Faction |
| `/cosmetics` (`/cosmetic`) | Ouvre tes cosmétiques. Voir [Client](client.md). | Tous |
| `/bienvenue` | Souhaite la bienvenue à un nouveau joueur. | Tous · Faction |

Les commandes de [Faction](../pvp-faction/factions.md), de la [PvP-Box](../pvpbox/index.md), du [Hardcore](../hardcore/index.md) et du [minage](../minage/index.md) sont détaillées dans leurs pages.

{% hint style="warning" %}
Quand tu es en combat (pendant 30 secondes après avoir frappé un joueur ou été frappé par un joueur, flèches comprises), ces commandes sont **désactivées** : `/hub`, `/spawn`, `/home`, `/tpa` (`/call`), `/warp`, `/ec`, `/corbeille`, `/craft` et `/repair`. Message : « Cette commande est désactivée en combat. »
{% endhint %}
