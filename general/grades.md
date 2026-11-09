# 📛 Grades

> Ton grade de jeu se gagne en jouant, ton grade boutique s'achète, et leurs avantages se cumulent.

## ⚡ En bref

- Il existe **deux familles de grades** :
  - les **grades de jeu** (Guerrier, Chevalier, Duc, Baron, Seigneur, Roi) : tu les gagnes sur PvP-Factions avec `/rankup`, voir [Progression](../pvp-faction/progression.md) ;
  - les **grades boutique** (VIP, SuperVIP, Héros) : tu les achètes sur la boutique du site [mineria.fr](https://mineria.fr).
- Tu peux avoir **un grade de chaque famille en même temps**. Pour chaque avantage, tu profites du **meilleur des deux**.
- Les avantages s'appliquent sur le serveur **PvP-Factions**. Seules les **pommes d'or de la PvP-Box** dépendent du grade sur un autre serveur : voir [PvP-Box](../pvpbox/index.md).
- Ton **préfixe** dans le chat et dans la liste Tab est celui de ton grade le plus haut : un grade boutique passe devant un grade de jeu.

***

## 🏅 Grades de jeu

Tout le monde commence **Guerrier**. Les grades suivants se débloquent avec de l'or et des compétences, voir [Progression](../pvp-faction/progression.md).

| Avantage | Guerrier | Chevalier | Duc | Baron | Seigneur | Roi |
| --- | :---: | :---: | :---: | :---: | :---: | :---: |
| Homes | 1 | 2 | 3 | 4 | 5 | 6 |
| `/back` | ❌ | ✅ | ✅ | ✅ | ✅ | ✅ |
| `/craft` | ❌ | ❌ | ✅ | ✅ | ✅ | ✅ |
| `/ec` | ❌ | ❌ | ✅ | ✅ | ✅ | ✅ |
| `/condense` · `/uncondense` | ❌ | ❌ | ✅ | ✅ | ✅ | ✅ |
| `/feed` | ❌ | ❌ | ❌ | ✅ | ✅ | ✅ |
| `/furnace` | ❌ | ❌ | ❌ | ❌ | ✅ | ✅ |
| `/near` : rayon | ❌ | ❌ | 200 blocs | 300 blocs | 400 blocs | 600 blocs |
| `/repair` : délai | ❌ | ❌ | 24 h | 16 h | 12 h | 6 h |
| Kit | Guerrier | Chevalier | Duc | Baron | Seigneur | Roi |

Quand tu montes de grade, tu perds le kit de ton ancien grade, sauf le kit **Guerrier**, que tout le monde garde.

***

## 💎 Grades boutique

| Avantage | VIP | SuperVIP | Héros |
| --- | :---: | :---: | :---: |
| Homes | 7 | 8 | 9 |
| `/back`, `/craft`, `/ec`, `/condense`, `/uncondense`, `/feed`, `/furnace` | ✅ | ✅ | ✅ |
| `/near` : rayon | 200 blocs | 400 blocs | 600 blocs |
| `/repair` : délai | Celui de ton grade de jeu | 12 h | 6 h |
| Kit | VIP | SuperVIP | Héros |
| Mob Zone : zones réservées | VIP | VIP, SuperVIP | VIP, SuperVIP, Héros |
| Mob Zone : Vitesse II | ✅ | ✅ | ✅ |
| Mob Zone : enchantement Butin de l'épée | Butin I | Butin I et II | Butin I, II et III |

Le grade **Partenaire** donne les mêmes avantages que **Héros**.

{% hint style="info" %}
**Exemple de cumul** : un joueur **Baron** et **SuperVIP** a 8 homes (le plus grand des deux), `/near` jusqu'à 400 blocs, `/repair` toutes les 12 h, `/furnace` grâce au SuperVIP, et les kits Guerrier, Baron et SuperVIP.
{% endhint %}

La Mob Zone et le Dard Royal sont détaillés dans [PvE](../pvp-faction/pve.md). Si tu essaies d'entrer dans une zone réservée à un grade que tu n'as pas, tu es bloqué : « Zone X réservée à un grade supérieur ».

***

## 🧰 Les commandes de grade en détail

| Commande | Ce qu'elle fait |
| --- | --- |
| `/home` · `/sethome` · `/delhome` · `/homes` | Gère tes homes. La limite de ton grade s'ajoute aux homes gagnés avec les compétences **Pied-à-terre** (jusqu'à +4, voir [Progression](../pvp-faction/progression.md)). |
| `/back` (`/return`) | Te ramène à ta position précédente. |
| `/craft` (`/workbench`) | Ouvre un établi portable. |
| `/ec` (`/enderchest`) | Ouvre ton coffre de l'Ender à distance. |
| `/condense` (`/compact`, `/block`) | Transforme les lingots et gemmes de ton inventaire en blocs : fer, or, diamant, émeraude, charbon, redstone, saphir et Aria. Le surplus tombe à tes pieds si ton inventaire est plein. |
| `/uncondense` (`/uncompact`, `/unblock`) | Fait l'inverse : transforme les blocs en lingots ou minerais. |
| `/feed` (`/eat`) | Remplit ta barre de faim et ta saturation. |
| `/furnace` (`/four`, `/cuire`, `/cook`) | Cuit instantanément toute la pile que tu tiens en main (viande, poisson, minerai…). |
| `/near` | Liste les joueurs proches de toi. `/near <rayon>` réduit la zone. Délai entre deux utilisations : 60 s à 200 et 300 blocs, 45 s à 400 blocs, 30 s à 600 blocs. |
| `/repair` (`/fix`) | Répare l'objet que tu tiens en main. Tu dois ensuite attendre le délai de ton grade (« Tu peux réparer dans … »). |

En combat, `/craft`, `/ec`, `/repair` et `/home` sont désactivées.

***

## 🎒 Les kits

`/kits` (ou `/kit`) ouvre le **menu des kits** sur PvP-Factions : tu y vois tous les kits, leur état et leur contenu, et tu les récupères d'un clic. Tout est détaillé dans [Kits et warps](../pvp-faction/kits-et-warps.md). `/kit <nom>` récupère un kit directement.

- Chaque kit se récupère **une fois toutes les 24 h**.
- Il te faut assez de place : « Ton inventaire est plein, le kit X ne t'a pas été donné. »
- Les objets des kits sont **liés** : impossible de les vendre à l'[hôtel des ventes](../pvp-faction/economie.md), de les [échanger](../pvp-faction/economie.md) ou de les offrir.
- Un kit de bienvenue t'est donné à ta première connexion.

Toutes les armures sont enchantées **Protection II** et toutes les épées **Tranchant II**.

| Kit | Armure | Épée | Bonus |
| --- | --- | --- | --- |
| **Guerrier** | Fer | Fer | 32 steaks |
| **Chevalier** | Casque et bottes en diamant, plastron et jambières en fer | Diamant | 32 steaks |
| **Duc** | Diamant | Saphir | 32 steaks |
| **Baron** | Casque et bottes en saphir, plastron et jambières en diamant | Émeraude | 4 saphirs, 1 pépite d'Aria, 32 steaks |
| **Seigneur** | Saphir | Émeraude | 8 saphirs, 2 pépites d'Aria, 4 pommes d'or, 1 chope de cervoise, 32 steaks |
| **Roi** | Casque et bottes en émeraude, plastron et jambières en saphir | Émeraude | 8 saphirs, 8 pépites d'Aria, 7 pommes d'or, 2 chopes de cervoise, 32 steaks |
| **VIP** | Saphir | Émeraude | 8 saphirs, 1 pépite d'Aria, 4 pommes d'or, 1 chope de cervoise, 64 steaks |
| **SuperVIP** | Casque et bottes en émeraude, plastron et jambières en saphir | Émeraude | 8 saphirs, 2 pépites d'Aria, 8 pommes d'or, 2 chopes de cervoise, 64 steaks |
| **Héros** | Émeraude | Émeraude | 12 saphirs, 6 pépites d'Aria, 16 pommes d'or, 1 pomme de Notch, 2 chopes de cervoise, 64 steaks |

Les kits métier (mineur, pilleur, farmeur…) ne dépendent pas de ton grade : tu les gagnes dans les [box](../pvp-faction/box.md).

***

## 🛡️ Grades du staff

Ces grades sont réservés aux membres de l'équipe de modération et de développement du serveur.

* 🛡️ <mark style="color:yellow;">**Modérateur**</mark>
* 🛡️✨ <mark style="color:yellow;">**SuperModérateur**</mark>
* 🕹️ <mark style="color:red;">**Administrateur**</mark>
* ⚙️ <mark style="color:red;">**Développeur**</mark>
* 👑 <mark style="color:red;">**Fondateur**</mark>

➡️ Si tu souhaites rejoindre le staff, rends-toi sur notre Discord : [discord.mineria.fr](https://discord.mineria.fr). Tu pourras y déposer ta candidature auprès d'un responsable staff.

***

## 👥 Liste du staff

<table data-header-hidden><thead><tr><th width="100" align="center"></th><th></th></tr></thead><tbody><tr><td align="center"><img src="https://mineria.fr/api/skin-api/avatars/face/CipheR_.png" alt=""></td><td><strong>CipheR_</strong><br>👑 <mark style="color:red;">Fondateur</mark></td></tr><tr><td align="center"><img src="https://mineria.fr/api/skin-api/avatars/face/Para.png" alt=""></td><td><strong>Para</strong><br>👑 <mark style="color:red;">Fondateur</mark></td></tr><tr><td align="center"><img src="https://mineria.fr/api/skin-api/avatars/face/Ilhan.png" alt=""></td><td><strong>Ilhan</strong><br>👑 <mark style="color:red;">Fondateur</mark></td></tr><tr><td align="center"><img src="https://mineria.fr/api/skin-api/avatars/face/MrSimsim11.png" alt=""></td><td><strong>MrSimsim11</strong><br>🕹️ <mark style="color:red;">Administrateur</mark></td></tr></tbody></table>

## ⌨️ Commandes

| Commande | Effet | Qui peut l'utiliser |
| --- | --- | --- |
| `/kit` (`/kits`) | Ouvre le menu des kits | Tous |
| `/kit <nom>` | Récupère un kit (toutes les 24 h) | Selon ton grade |
| `/kit view <nom>` | Ouvre le menu sur ce kit, même si tu ne l'as pas (aperçu) | Tous |
| `/back`, `/craft`, `/ec`, `/condense`, `/uncondense`, `/feed`, `/furnace`, `/near`, `/repair` | Voir le tableau ci-dessus | Selon ton grade |
| `/rankup` | Monte de grade de jeu | Tous |
