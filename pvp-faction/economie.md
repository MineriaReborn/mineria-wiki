# 💰 Économie

> Ici, tu apprends à gagner, dépenser et échanger ton argent : shop, bourse, Hôtel des Ventes, échanges entre joueurs, spawners et bouteilles d'XP.

## ⚡ En bref

* La monnaie du serveur s'affiche en `$`. Elle n'existe que sur **PvP-Factions** : `/balance` et `/pay` ne marchent pas sur les autres serveurs.
* Tu **gagnes** de l'argent en vendant au shop, à l'Hôtel des Ventes, avec la vente auto du Récolteur, en gagnant des [duels](duels.md) d'argent ou grâce aux autres joueurs (`/pay`, `/trade`).
* Tu **dépenses** ton argent au shop, à l'HDV, chez le boulanger, pour améliorer tes machines de ferme, dans la banque de ta faction ou en l'envoyant à un ami.
* Pour connaître ton solde : `/balance`.

## 🪙 Ton argent

{% tabs %}
{% tab title="Voir ton solde" %}
`/balance` (ou `/bal`, `/money`) affiche : « Ton solde : X $. ».

Tu peux aussi regarder le solde d'un joueur avec `/balance [joueur]`.
{% endtab %}

{% tab title="Envoyer de l'argent" %}
`/pay <joueur> <montant>` envoie de l'argent à un autre joueur.

| Règle | Valeur |
| --- | --- |
| Montant par envoi | de 1 à 100 000 $ (nombre entier) |
| Délai entre deux envois | 3 secondes |
| Total envoyé sur 24 h glissantes | 500 000 $ maximum |
| Destinataire | connecté, et différent de toi |

Si tu atteins le plafond, un message te le dit.

{% hint style="info" %}
Un échange (voir plus bas) où **toi seul** donnes de l'argent, sans rien recevoir, compte dans ce même plafond de 500 000 $ par 24 h. Dès que l'autre joueur met un objet ou de l'argent en face, le plafond ne s'applique plus.
{% endhint %}
{% endtab %}
{% endtabs %}

## 💸 D'où vient l'argent, où il part

| Tu gagnes de l'argent… | Tu dépenses de l'argent… |
| --- | --- |
| En vendant tes récoltes, minerais et loots au **shop** | En achetant au **shop** |
| En vendant tes objets à l'**Hôtel des Ventes** | En achetant à l'**Hôtel des Ventes** |
| Avec la **vente auto du Récolteur** (voir [PvE](pve.md)) | En améliorant ton **Récolteur** ou ton **Brûleur d'Âmes** |
| En gagnant un **duel d'argent** (voir [Duels](duels.md)) | En misant sur un duel |
| En retirant de la **banque de ta faction** (voir [Factions](factions.md)) | En déposant dans la banque de ta faction, qui paie la taxe des claims |
| Quand un joueur t'envoie de l'argent (`/pay`, `/trade`) | Chez le **boulanger** |

Les box, les quêtes et les events ne donnent pas d'argent : ils donnent des objets, de l'XP ou des pièces d'argent pour tes compétences (voir [Box](box.md), [Quêtes](quetes.md) et [Événements](evenements.md)).

## 🛒 Le shop et la bourse

Le shop te permet d'**acheter** des ressources et de **vendre** ce que tu récoltes.

### Comment y accéder

* Rends-toi dans la **zone Shop** et parle à un marchand : ils sont rangés par catégorie (« Marchand Minage », « Marchand Agriculture »…).
* Le PNJ **Bourse** ouvre directement l'onglet BOURSE.
* La compétence **Accès marché** (grade Chevalier, voir [Progression](progression.md)) débloque `/warp shop` pour t'y téléporter.

Il n'y a pas de commande pour ouvrir le shop à distance : il faut passer par les PNJ.

Les onglets de la fenêtre sont **Acheter**, **Vendre** et **BOURSE**. Un champ « Rechercher un item... » t'aide à retrouver un article. Les catégories sont : Minage, Agriculture, Loot de mobs, Blocs, Alchimie et Divers.

{% hint style="info" %}
Le shop est indisponible pendant un duel.
{% endhint %}

### Acheter

* Le prix d'achat est **fixe** : il ne bouge jamais.
* Tu choisis la quantité, tu vois le « Total estimé » et le « Solde après achat ».
* L'achat est limité par la place libre dans ton inventaire (« Pas assez de place dans ton inventaire : N au maximum. »).
* Si tu n'as pas assez d'argent : « Fonds insuffisants. »

### Vendre

* Seuls les items **non modifiés** se vendent. Un item renommé, enchanté ou modifié est refusé.
* Le bouton « Tout vendre » vend d'un coup tout ce que tu as de l'article.
* **Le prix de revente baisse quand tu vends beaucoup** du même article, jusqu'à un minimum de 10 % du prix de base. Il **remonte tout seul avec le temps** : toutes les 2 heures, l'écart avec le prix de base est réduit de moitié.
* Vendre 100 items d'un coup revient au même que les vendre un par un.
* Le prix peut changer entre le moment où tu ouvres la fenêtre et celui où tu valides. Dans ce cas : « Le prix a changé : vérifie le nouveau prix puis valide à nouveau. »

{% hint style="success" %}
**Astuce.** Plutôt que de tout vendre d'un coup, répartis tes ventes sur plusieurs articles : chacun a son propre prix, et chacun remonte tout seul.
{% endhint %}

### La bourse

L'onglet **BOURSE** montre pour chaque article son « Prix de revente » du moment et sa « Variation » (« Hausse » ou « Baisse » par rapport au prix de base). C'est ton outil pour savoir **quoi vendre maintenant**.

### Bonus de compétence

Deux compétences de l'[arbre de compétences](progression.md) augmentent tes gains de vente. Elles se cumulent.

| Compétence | Grade | Bonus sur le montant des ventes |
| --- | --- | --- |
| Bon négoce | Seigneur | +5 % |
| Grand négoce | Roi | +15 % |

### Quelques prix

Le prix de revente ci-dessous est le **maximum** (quand l'article n'a pas été revendu récemment). Un tiret signifie que l'article n'est pas vendable, ou pas achetable.

<details>

<summary>Voir la liste</summary>

**Minage**

| Article | Achat | Revente max |
| --- | --- | --- |
| Roche | 500 $ | 1,10 $ |
| Charbon | 600 $ | 13,75 $ |
| Redstone | 600 $ | 11 $ |
| Fer | — | 82,50 $ |
| Lingot d'or | — | 165 $ |
| Diamant | 5 000 $ | 330 $ |
| Émeraude | — | 880 $ |
| Aria | — | 68 750 $ |

**Agriculture**

| Article | Achat | Revente max |
| --- | --- | --- |
| Pomme de terre | 1 000 $ | 2,75 $ |
| Carotte | 1 000 $ | 11 $ |
| Blé | — | 9,90 $ |
| Cactus | 1 000 $ | 13,20 $ |
| Pastèque | 1 000 $ | 15,95 $ |
| Canne à sucre | 1 500 $ | 28,60 $ |
| Verrue du Nether | 1 500 $ | 42,35 $ |
| Citrouille | 1 000 $ | 53,35 $ |

**Loot de mobs**

| Article | Achat | Revente max |
| --- | --- | --- |
| Ficelle, Plume | — | 2,75 $ |
| Cuir | 2 500 $ | 3,30 $ |
| Os | — | 38,50 $ |
| Chair putréfiée | — | 51,15 $ |
| Steak | — | 77 $ |
| Poulet rôti | — | 108,90 $ |
| Flèche | 10 000 $ | 29,15 $ |
| Perle de l'Ender | 10 000 $ | — |
| Boule de slime | 25 000 $ | — |

**Alchimie**

| Article | Achat | Revente max |
| --- | --- | --- |
| Fiole | 70 $ | — |
| Poudre à canon | 1 500 $ | 27,50 $ |
| Boule de magma | 1 000 $ | 55 $ |
| Poudre de blaze | 1 000 $ | 55 $ |
| Bâton de blaze | 5 000 $ | 110 $ |
| Alambic | 7 500 $ | — |

**Divers**

| Article | Achat | Revente max |
| --- | --- | --- |
| TNT | 7 500 $ | — |
| Bibliothèque | 8 000 $ | — |
| Teintures | 200 $ | — |
| Fiole d'XP | — | 49,50 $ |

</details>

{% hint style="info" %}
La liste complète (blocs, bois, sable, glace, laine…) est dans la fenêtre du shop, avec les prix à jour.
{% endhint %}

## 🏛️ L'Hôtel des Ventes (HDV)

L'HDV est la place de marché entre joueurs : **tu fixes ton prix**, un autre joueur achète quand il veut, même si tu es déconnecté.

### Mettre un item en vente

1. Prends l'item en main.
2. Tape `/hdv vendre` (ou clique sur « Vendre l'item en main » dans l'HDV).
3. Choisis la quantité (« Qts : »), le prix (« Prix en $ : ») et la durée (« Expiration : N heures »).
4. Regarde « Prix en $ après taxe : », puis valide avec **Vendre**.

| Règle | Valeur |
| --- | --- |
| Durée de l'offre | de 3 à 12 heures |
| Taxe | 15 % du prix de vente, quelle que soit la durée |
| Prix maximum | 100 000 000 $ |
| Offres en même temps | 10 (certaines compétences de grade ajoutent 2 offres chacune) |

**Exemple :** tu vends à 100 $, tu reçois 85 $. Le prix doit laisser au moins 1 $ après la taxe, sinon : « Prix trop bas : après la taxe, tu ne recevrais pas 1 $. »

### Acheter

* Ouvre l'HDV avec `/hdv`, ou parle au PNJ de l'Hôtel des Ventes.
* L'onglet **Accueil** liste toutes les offres. Tu peux les trier par « Alphabétique » ou « Plus récent ».
* Chaque offre indique le **vendeur**, le prix et le temps restant (« Expire dans »).
* Tu ne peux pas acheter ta propre offre.

### Récupérer tes achats et tes gains

* L'item acheté arrive dans ta **Réserve** (`/reserve`).
* Une offre qui expire, ou que tu retires, revient aussi dans ta Réserve. Pour retirer une offre : onglet **Mes offres**, bouton Retirer, puis confirme.
* Quand ton offre se vend, l'argent est crédité **même si tu es déconnecté**. Tu reçois une notification « Hôtel des Ventes ».

{% hint style="warning" %}
L'HDV est fermé pendant un duel, un tournoi, un donjon, et pour les joueurs en mode modération. Les items « liés à ton compte » ne peuvent pas être vendus.
{% endhint %}

## 🔁 L'échange entre joueurs

L'échange te permet de donner des **items et de l'argent** à un autre joueur en toute sécurité : rien ne part tant que vous n'avez pas validé tous les deux.

### Lancer un échange

1. Place-toi à moins de 10 blocs du joueur (même monde).
2. Tape `/trade <joueur>` (ou `/echange <joueur>`).
3. Il a **30 secondes** pour répondre avec `/trade accept <joueur>` ou `/trade deny <joueur>` (ou `/echange accepter|refuser`).
4. Tu peux faire une nouvelle demande 5 secondes après la précédente.

### Dans la fenêtre « Échange avec … »

* **Propose un item** : clique dessus dans « Ton inventaire ». Reclique dessus pour le retirer. Le **stack entier** est proposé d'un coup. Seul l'inventaire principal compte, pas l'armure.
* **Propose de l'argent** : tape un montant dans le champ « Argent ». Ton « Solde » s'affiche en dessous.
* **Valide** quand l'offre te convient. Clique à nouveau pour retirer ta validation.
* Tu vois à droite l'« Offre de <joueur> », c'est-à-dire ce que tu vas recevoir, et en bas « APRÈS L'ÉCHANGE ».

### Les protections

* Toute modification annule les validations et **bloque le bouton 3 secondes**, pour t'éviter une mauvaise surprise de dernière seconde.
* Quand vous avez validé tous les deux, l'échange part après **5 secondes**. Un changement pendant le décompte l'annule.
* Il n'y a **aucune taxe**.
* Si ton inventaire est plein à l'arrivée, le surplus va dans ta Réserve. Sur le serveur Build, qui n'a pas de Réserve, l'échange est refusé si l'inventaire est plein.

{% hint style="warning" %}
L'échange est annulé automatiquement si l'un de vous s'éloigne de plus de 10 blocs, prend des dégâts, se téléporte, se déconnecte, meurt, appuie sur Échap, entre en duel ou en combat, ou passe en créatif.
{% endhint %}

## 🥖 Le boulanger

Le PNJ Boulanger te vend du pain à prix fixe.

| Offre | Prix |
| --- | --- |
| 16 pains | 32 $ (2 $ le pain) |

1. Parle au boulanger : il te propose « [16 PAIN(S) pour 32$] ».
2. Clique dans le chat pour **confirmer** ou **annuler**.
3. Tu as 30 secondes. Passé ce délai : « Demande expirée : reparle au boulanger. »

Si ton inventaire est trop plein, le surplus tombe au sol.

## 🥚 Les spawners

Un spawner fait apparaître des mobs en continu. Tu ne les **achètes pas** : tu les obtiens autrement.

### Comment en obtenir

* **Récompense de faction** : quand ta faction atteint le **niveau maximum**, elle reçoit **3 spawners** tirés au hasard parmi : Zombie, Squelette, Araignée, Araignée bleue, Creeper, Enderman, Blaze, Cochon zombie, Sorcière, Vache, Cochon, Poulet, Mouton, Cocowok. Voir [Factions](factions.md).
* **Don d'un autre joueur** : `/spawner send <joueur> <entité>`.

### Les poser et les retirer

* `/spawner` ouvre la liste de **tes** spawners. `/f spawners` ouvre ceux de ta **faction** (selon tes droits de faction).
* Clique sur un spawner de la liste, puis **tape un bloc** : il devient ce spawner.
* Pour le retirer, casse-le : il retourne dans ta liste.
* Un spawner appartient à un joueur ou à une faction. Seul son propriétaire peut le casser, sauf si tu as le droit de détruire des blocs là où il se trouve.

| Règle | Détail |
| --- | --- |
| Où | monde principal uniquement |
| Rythme | **un mob sur quatre** par rapport à un spawner de Minecraft classique (4 fois plus lent) |
| Interdit de poser sur | bedrock, obsidienne, autre spawner |

{% hint style="info" %}
Tu peux donner un spawner à ta faction avec `/spawner sendfaction <entité>`.
{% endhint %}

## 🧪 Les bouteilles d'XP

Tu veux stocker ton expérience sans la perdre ? Mets-la en bouteille.

* **Prérequis** : la compétence « Embouteilleur » (grade Guerrier). Voir [Progression](progression.md).
* **Créer** : `/bottlexp [niveaux]`. Tu obtiens une « Réserve d'XP » qui indique « Points d'XP : N » et le nombre de niveaux équivalent. Aucune perte.
* **Utiliser** : fais un clic droit avec la bouteille. Tu reçois « N points d'expérience ».
* Si ton inventaire est plein, la bouteille va dans ta Réserve (en zone de mobs) ou te le signale : « Ton inventaire est plein. »

{% hint style="warning" %}
Les distributeurs ne peuvent pas distribuer une bouteille d'XP. Et si tu as déjà trop d'XP, tu ne peux pas en reprendre d'autre : « Tu as trop d'XP pour utiliser cette bouteille. »
{% endhint %}

Le shop rachète aussi les **fioles d'XP** (voir plus haut).

## ⌨️ Commandes

| Commande | Effet | Qui peut |
| --- | --- | --- |
| `/balance [joueur]` (`/bal`, `/money`) | Affiche un solde | Tous |
| `/pay <joueur> <montant>` | Envoie de l'argent | Tous |
| `/warp shop` | Te téléporte à la zone Shop | Compétence « Accès marché » |
| `/hdv` (`/ah`, `/auction`) | Ouvre l'Hôtel des Ventes | Tous |
| `/hdv vendre` (`/hdv sell`) | Met en vente l'item en main | Tous |
| `/trade <joueur>` (`/echange`) | Propose un échange | Tous |
| `/trade accept <joueur>` | Accepte un échange | Tous |
| `/trade deny <joueur>` | Refuse un échange | Tous |
| `/spawner` | Liste tes spawners | Tous |
| `/spawner send <joueur> <entité>` | Donne un de tes spawners | Tous |
| `/spawner sendfaction <entité>` | Donne un de tes spawners à ta faction | Membres de faction |
| `/f spawners` | Ouvre les spawners de ta faction | Selon ton rôle de faction |
| `/bottlexp [niveaux]` | Met ton XP en bouteille | Compétence « Embouteilleur » |
| `/reserve` | Récupère les items livrés en Réserve | Tous |

Voir aussi [toutes les commandes](../general/commandes.md), les [grades](../general/grades.md) et les [box](box.md).
