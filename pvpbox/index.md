# 🥊 PvP-Box

> Un mode de combat rapide : tu spawns, tu récupères ton kit, tu te bats, tu remontes au classement.

## ⚡ En bref

- Tu arrives au **spawn**, sans rien dans l'inventaire.
- Dès que tu **sors de la zone de spawn**, tu reçois automatiquement ton **kit**.
- Chaque kill te rapporte **5 points**, chaque mort t'en retire **2**.
- Si tu meurs, tu réapparais au spawn **au bout d'une seconde**.
- Un **Top 10** par points est affiché avec `/classement`.

## 🚪 Arrivée

À chaque connexion, tu es téléporté au spawn et ton inventaire est vidé. Tu n'as rien à préparer : tout se passe en jouant.

Le spawn est une zone **sûre** :

- personne ne peut te taper, et tu ne peux taper personne ;
- ton inventaire est verrouillé ;
- tu ne peux ni ramasser ni jeter d'objets.

{% hint style="info" %}
Sur le spawn, une **plaque de pression en bois** te propulse dans la direction où tu regardes. C'est le moyen le plus rapide d'entrer dans l'arène.
{% endhint %}

## 🎒 Le kit

Tu reçois ton kit **automatiquement en quittant la zone de spawn**. Le message « Vous avez récupéré votre kit. » confirme la remise.

- Le kit **remplace** ton inventaire et ton armure.
- Tu gagnes aussi l'effet **Speed II**, permanent.
- Il n'y a pas de choix de kit : tout le monde reçoit le même.
- Pas de cooldown : à chaque mort, tu repasses par le spawn et tu récupères le kit en ressortant.

{% hint style="warning" %}
Si aucun kit n'est configuré, tu es renvoyé au spawn avec le message « Aucun kit n'est configuré sur ce serveur ! ». Préviens alors un membre de l'équipe.
{% endhint %}

## ⚔️ Règles de combat

| Règle | Détail |
|---|---|
| PvP | Actif partout sauf dans la zone de spawn |
| Chute | Pas de dégâts de chute |
| Faim | Ta barre de faim reste pleine |
| Construction | Casser et poser des blocs est interdit |
| Monde | Pas de météo, pas de créatures, pas d'explosions |
| Décor | Cadres, tableaux, minecarts et bateaux sont protégés |

Tu ne peux pas ouvrir les coffres (y compris l'Ender Chest), fours, distributeurs, droppers, entonnoirs, alambics, établis, tables d'enchantement, enclumes, lits, portes, trappes et portillons.

## 💀 Kill, mort et respawn

- **Kill** : +5 points, et ta série augmente de 1.
- **Mort** : -2 points, ta série retombe à 0 et tu réapparais au spawn après 1 seconde.
- Ta série est aussi remise à 0 si tu te déconnectes.
- Tes kills et tes morts sont **conservés** d'une connexion à l'autre.

### 🍎 Pommes d'or

Certains kills te rapportent des pommes d'or, selon le **grade du joueur que tu tues** :

| Joueur tué | Pommes d'or gagnées |
| --- | --- |
| SuperVIP | 1 |
| Héros ou Partenaire | 2 |
| Autres grades | 0 |

Le message « Vous avez reçu N pomme(s) d'or pour avoir tué un joueur ! » s'affiche. Si ton inventaire est plein, la pomme tombe au sol.

Pour le détail des grades, consulte la page [Grades](../general/grades.md).

## 📊 Statistiques

Tape `/stat` pour afficher tes statistiques :

| Ligne | Signification |
|---|---|
| Kills | Nombre de joueurs éliminés |
| Deaths | Nombre de morts |
| Ratio K/D | Kills divisés par morts, arrondi à 2 décimales |
| Points totaux | Kills × 5 − morts × 2 |

Tes points apparaissent aussi dans le **chat**, sous la forme `[points]` devant ton pseudo (en vert s'ils sont positifs, en rouge sinon). Survole-les pour voir tes kills, tes morts et ton ratio.

## 🏆 Classement

Tape `/classement` pour voir le **Top 10** du serveur, trié par points.

- Format : `#1 - Nom , Kills: x, Morts: y (z PTS)`.
- Il est mis à jour toutes les **10 minutes**. Le chat annonce « Le classement a été mis à jour ! ».
- Les trois premiers reçoivent une **médaille** à côté de leur pseudo dans le chat.
- Tant qu'aucun classement n'existe, tu verras « Aucun classement n'est disponible pour le moment. »

Les classements des autres modes sont sur la page [Classements](../general/classements.md).

## 📋 Scoreboard

Le tableau de droite affiche :

| Ligne | Contenu |
|---|---|
| PvPBox | En-tête, avec « Série N » quand ta série est supérieure à 0 |
| Éliminations | Tes kills |
| Morts | Tes morts |
| Ratio | Ton ratio K/D |
| Points | Tes points |
| Meilleur joueur | Le nom du n°1 et son « Meilleur score » en pts (« Aucun » si le classement est vide) |

## ⌨️ Commandes

| Commande | Effet | Qui peut l'utiliser |
|---|---|---|
| `/stat` (aussi `/stats`, `/statistique`, `/statistic`) | Affiche tes statistiques | Tout le monde |
| `/classement` (aussi `/ranking`, `/classements`, `/rankings`) | Affiche le Top 10 par points | Tout le monde |

Retrouve toutes les commandes du serveur dans [Commandes](../general/commandes.md).
