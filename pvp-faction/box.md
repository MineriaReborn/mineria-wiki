# 🎁 Box, cadeaux et baluchon

> Ouvre des box avec une clé pour tenter de gagner items, kits et cosmétiques, découvre les dons aux partenaires et le contenu du baluchon.

## ⚡ En bref

* Une **box** est un coffre spécial. Tu l'ouvres avec une **clé** de la même box.
* Le tirage est **pondéré** : chaque récompense a une chance affichée en pourcentage.
* Les box sont le seul moyen d'obtenir les **kits métier** (mineur, alchimiste, pilleur…).
* Le **baluchon** est un objet à usage unique qui donne un loot au hasard, réservé aux joueurs en faction.
* Les **dons** te permettent d'envoyer des items à un partenaire du serveur.

## 🎁 Les box

### Obtenir des clés

Quand tu reçois des clés, un message te prévient : « Tu as reçu xN clé(s) pour la box X. Clic droit sur la box avec une clé pour l'ouvrir. » Si ton inventaire est plein, le surplus part dans ta [Réserve](economie.md) (`/reserve`).

### Voir le contenu d'une box

Fais un **clic gauche** sur la box. La fenêtre « Récompenses possibles » liste tout ce que tu peux gagner, avec la **chance** de chaque récompense. Tu y vois aussi combien de clés tu as : « x N clé(s) » ou « Aucune clé ».

### Ouvrir une box

1. Prends une clé de la box **en main**.
2. Fais un **clic droit** sur la box. Une clé est consommée.
3. L'animation « Tirage en cours… » dure environ 7 secondes, puis « Récompense obtenue » s'affiche.
4. Un récapitulatif arrive dans le chat : la récompense, sa chance, sa rareté et où elle a été livrée.

Ta récompense t'est remise **dès le début de l'animation** : même si tu fermes la fenêtre, tu ne perds rien.

Une fois le résultat affiché, tu peux en ouvrir une autre directement depuis la fenêtre, tant que tu restes près de la box (« Rapproche-toi de la box X pour en ouvrir une autre. »).

{% hint style="info" %}
Messages que tu peux croiser : « Il te faut une clé de la box X en main. », « Tu ouvres déjà une box, patience ! », « La box X n'a aucune récompense pour le moment. »
{% endhint %}

### Les types de récompenses

| Type | Ce que tu reçois | Livraison |
| --- | --- | --- |
| Item | Un ou plusieurs objets | Dans ton inventaire, sinon dans ta Réserve, sinon au sol |
| Kit | L'accès à un kit métier, permanent ou temporaire (voir plus bas) | « Accès au kit X » ou « Accès au kit X pendant … » |
| Cosmétique | Un cosmétique débloqué | « Cosmétique débloqué » |

{% hint style="warning" %}
Si tu tombes sur un cosmétique que tu possèdes déjà, la livraison indique « Déjà possédé » et ta clé est quand même consommée.
{% endhint %}

### Les raretés

La rareté dépend de la **chance** de la récompense.

| Rareté | Chance de la récompense |
| --- | --- |
| Commun | 20 % ou plus |
| Rare | de 8 % à moins de 20 % |
| Épique | de 3 % à moins de 8 % |
| Légendaire | de 1 % à moins de 3 % |
| Mythique | moins de 1 % |

* À partir de **Légendaire**, un feu d'artifice éclate sur la box.
* Quand la chance est de **5 % ou moins**, tout le serveur est prévenu : « X vient d'obtenir Y (Z %) dans la box W ! »

## 🛠️ Les kits métier

Une récompense « Kit » te donne l'accès à un **kit métier**. Contrairement aux kits de grade (voir [Grades](../general/grades.md)), ils ne dépendent pas de ton grade : tu ne peux les obtenir que dans les box.

* L'accès est **permanent** ou **temporaire** : le récapitulatif du tirage te le dit (« Accès au kit X » ou « Accès au kit X pendant … »).
* Une fois l'accès obtenu, récupère le kit avec `/kit <nom>`, **une fois toutes les 24 h**. `/kit view <nom>` montre son contenu sans le prendre.
* Comme pour tous les kits, il te faut assez de place dans ton inventaire, et les objets reçus sont **liés** : impossible de les vendre à l'hôtel des ventes, de les échanger ou de les offrir.

Les potions des kits sont toutes des **potions jetables**.

| Kit | Commande | Contenu |
| --- | --- | --- |
| **Mineur** | `/kit mineur` | 64 charbons, 32 lingots de fer, 16 lingots d'or, 4 diamants, 8 saphirs, 8 pépites d'Aria |
| **Alchimiste** | `/kit alchimiste` | 22 potions : 12 Soin instantané II, 2 Rapidité II, 2 Régénération II, 2 Résistance au feu prolongée, 2 Anti-Chute prolongée, 2 Anti-Téléportation prolongée |
| **Pilleur** | `/kit pilleur` | 2 dynamites, 1 dynamite marine, 16 TNT, 32 redstone, 2 blocs de redstone, 2 pistons collants, 2 pistons, 16 obsidiennes, 1 briquet, 2 seaux d'eau, 2 leviers, 2 boutons en bois |
| **Farmeur** | `/kit farmeur` | 32 graines de blé, 32 graines de melon, 32 graines de citrouille, 32 myrtilles, 32 framboises, 32 graines d'orge, 32 gruits, 192 terres, 128 sables, 64 blocs d'herbe, 2 seaux d'eau, 1 houe en saphir, 32 torches, 128 poudres d'os |
| **Explorateur** | `/kit explorateur` | 48 perles de l'Ender, 2 bateaux, 4 potions de Rapidité II |
| **Enchanteur** | `/kit enchanteur` | 1 table d'enchantement, 1 enclume, 128 fioles d'XP, 16 livres |
| **Buildeur** | `/kit buildeur` | 128 obsidiennes, 32 bûches de chaque bois (chêne, sapin, bouleau, acajou, acacia, chêne noir), 64 blocs d'herbe, 64 verres, 64 pierres, 64 briques de pierre, 16 pierres lumineuses, 64 pierres de l'End |
| **Druide** | `/kit druide` | 3 alambics, 64 verrues du Nether, 32 sucres, 12 bâtons de blaze, 32 poudres de pierre lumineuse, 32 redstone, 32 poudres à canon, 32 pastèques scintillantes, 32 yeux d'araignée, 16 yeux d'araignée fermentés, 128 fioles, 1 seau d'eau |
| **Alcoolique** | `/kit alcoolique` | 12 malts, 12 gruits, 2 seaux d'eau, 3 tonneaux, 12 chopes vides, 6 chopes de cervoise, 32 pommes d'or |

## 💝 Les dons aux partenaires

Les dons te permettent d'envoyer des items à un **partenaire** du serveur (par exemple un créateur de contenu).

1. Tape `/dons send <partenaire> <message>`.
2. Dans le menu « Dépose tes items », place ce que tu veux offrir.
3. Ferme le menu pour envoyer. Tu vois « Don envoyé à X ! »

Si tu fermes le menu sans rien déposer : « Aucun objet déposé, don annulé. »

{% hint style="warning" %}
Tu ne peux pas t'envoyer un don à toi-même, ni envoyer un item lié à ton compte. Si le joueur visé n'est pas partenaire, tu vois « X n'est pas un partenaire du serveur. » Si le partenaire a désactivé la réception ou t'a bloqué, le don est refusé. Les dons peuvent aussi être désactivés temporairement : « Les dons sont actuellement désactivés. »
{% endhint %}

### Si tu es partenaire

| Commande | Effet |
| --- | --- |
| `/dons menu` | Ouvre les dons reçus. Clique sur un don pour le récupérer. |
| `/dons toggle` | Active ou désactive la réception des dons |
| `/dons block <pseudonyme>` | Bloque un joueur |

## 🎒 Le baluchon

Le baluchon est un objet à **usage unique**.

1. Prends un baluchon en main.
2. Fais un **clic droit**. Il est consommé.
3. Tu reçois un loot tiré au hasard : soit des items (« Baluchon : Nx <item> ! »), soit de l'XP pour ta faction (« Baluchon : +N XP de faction ! »).

{% hint style="warning" %}
Tu dois être dans une faction pour l'ouvrir : « Vous devez être dans une faction pour ouvrir un baluchon. » Voir [Factions](factions.md).
{% endhint %}

### Ce qu'il peut contenir

Les chances ci-dessous sont **arrondies**, regroupées par type d'objet. Chaque ligne indique les quantités possibles ; les petites quantités sont plus fréquentes que les grosses.

| Loot | Quantités possibles | Chance du groupe |
| --- | --- | --- |
| XP de faction | 10, 15 ou 20 | environ 9,6 % |
| Perle de l'Ender | 2, 4, 8 ou 16 | environ 9,3 % |
| TNT | 2, 4, 8 ou 16 | environ 9,3 % |
| Pépite d'or | 2, 4, 6 ou 8 | environ 12,7 % |
| Obsidienne | 8, 16, 32 ou 64 | environ 8,7 % |
| Lingot de fer | 2, 4, 6 ou 8 | environ 8,5 % |
| Diamant | 4, 8 ou 16 | environ 5,9 % |
| Émeraude | 2, 4 ou 8 | environ 5,9 % |
| Boule de slime | 2, 4, 8 ou 16 | environ 5,5 % |
| Chope de cervoise | 1, 8 ou 16 | environ 4,5 % |
| Saphir ou escaliers en saphir | 2, 4 ou 8 saphirs ; 1 escalier | environ 4,4 % |
| Pépite d'aria | 1, 2, 4 ou 6 | environ 4,1 % |
| Lingot d'or | 2, 4, 6 ou 8 | environ 3,2 % |
| Pomme dorée | 2 ou 4 ; 1 enchantée (très rare) | environ 2,1 % |
| Potion | 1 | environ 1,9 % |
| Fiole d'XP | 16 ou 32 | environ 1,6 % |
| Table d'enchantement ou enclume | 4 | environ 1,2 % |
| Dynamite ou dynamite marine | 1 | environ 0,9 % |
| Balise, coffre de l'Ender ou coffre en saphir | 1 | environ 0,6 % |
| Clé de donjon | 1 | environ 0,2 % |

## ⌨️ Commandes

| Commande | Effet | Qui peut |
| --- | --- | --- |
| `/dons send <partenaire> <message>` (`/gift`, `/don`) | Envoie un don à un partenaire | Tous |
| `/dons menu` | Récupère les dons reçus | Partenaires |
| `/dons toggle` | Active ou désactive la réception | Partenaires |
| `/dons block <pseudonyme>` | Bloque un joueur | Partenaires |
| `/kit <nom>` | Récupère un kit métier débloqué (toutes les 24 h) | Joueurs qui ont gagné l'accès |
| `/kit view <nom>` | Montre le contenu d'un kit | Joueurs qui ont gagné l'accès |
| `/reserve` | Récupère les items livrés en Réserve | Tous |

Les box et le baluchon s'utilisent par **clic droit**, sans commande. Pour dépenser ton argent, va voir l'[économie](economie.md).
