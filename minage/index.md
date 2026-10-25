# ⛏️ Minage

> Mine sans limite d'espace : chaque bloc part dans ta réserve et te fait gagner de l'XP pour améliorer ta pioche.

## ⚡ En bref

- Tu mines, et chaque bloc récompensé part **directement dans ta [réserve](../general/reserve.md)**.
- Tu gagnes de l'**XP** à chaque bloc, donc des **niveaux**, donc des **points** à dépenser dans `/upgrade`.
- Tu récupères ta réserve sur le serveur **Faction**.
- Il y a un **plafond quotidien** de blocs récompensés.
- Garde la vue en mouvement : sans activité, les blocs ne rapportent plus rien.

## 🚪 Y aller et arriver

Le mode se joue sur les serveurs **Minage** (Mine 1 et Mine 2). À ton arrivée :

- tu es téléporté à un endroit aléatoire du monde ;
- tu reçois ta barre d'objets (voir plus bas) ;
- un message d'accueil rappelle l'essentiel : « Ta mission : mine, chaque bloc part dans ta réserve ».

Le chat est désactivé : « Le chat est désactivé sur le serveur minage. »

## 🧭 /rtp : changer de coin

Quand ton coin est épuisé, tape `/rtp` ou clique sur la perle « Téléportation » de ta barre d'objets. Tu es envoyé vers un nouveau filon, sur un sol sûr (jamais en pleine mer ni sur une rivière).

| Réglage | Valeur |
|---|---|
| Zone | De -10 000 à +10 000 blocs autour du point 0;0 |
| Cooldown | 300 secondes (5 minutes) |

Messages : « En route vers un nouveau filon ! » ou, si rien de sûr n'est trouvé, « Aucun emplacement sûr trouvé, relance /rtp. ». La téléportation d'arrivée n'a pas de cooldown.

## 🎒 Ta barre d'objets

| Emplacement | Objet | Rôle |
|---|---|---|
| 1 | Pioche | Ta pioche, qui garde ses enchantements |
| 2 | Hache | Efficacité III |
| 3 | Pelle | Efficacité III |
| 5 | Stone | 64 blocs, qui se renouvellent tout seuls |
| 7 | Perle « Téléportation » | Clic droit : `/rtp` |
| 8 | Étoile du Nether « Améliorations » | Clic droit : ouvre le menu des améliorations |
| 9 | Coffre « Réserve » | Clic droit : ouvre `/reserve` |

Tu as aussi la **vision nocturne** en permanence.

## 💎 Ce que rapportent les blocs

Chaque bloc miné rapporte **1 XP** et part dans ta réserve. Les minerais rapportent davantage d'XP :

| Minerai | XP |
|---|---|
| Charbon | 3 |
| Redstone | 4 |
| Fer | 5 |
| Lapis-lazuli | 8 |
| Or | 8 |
| Diamant | 20 |
| Émeraude | 25 |
| Saphir | 30 |

Ne rapportent **rien** (ni XP ni réserve) : lianes, torches, graines, rails, grandes plantes, buissons morts, fleurs, pots de fleurs, herbe haute, feuilles, terre et herbe. Les spawners, coffres, balises et œufs de dragon ne vont jamais dans la réserve.

{% hint style="info" %}
Les blocs que tu poses toi-même ne rapportent rien. Tu ne peux d'ailleurs poser que du Stone.
{% endhint %}

## 📈 Niveaux et points

Chaque niveau demande une quantité d'XP **à repartir de zéro** et te donne des points de compétence.

| Niveau | XP à gagner | Points gagnés |
|---|---|---|
| 1 | 100 | 2 |
| 2 | 200 | 2 |
| 3 | 300 | 2 |
| 4 | 400 | 2 |
| 5 | 600 | 2 |
| 6 | 800 | 2 |
| 7 | 1 100 | 3 |
| 8 | 1 400 | 3 |
| 9 | 1 700 | 3 |
| 10 | 2 100 | 3 |

<details><summary>Voir les niveaux 11 à 25 (3 points chacun)</summary>

| Niveau | XP à gagner |
|---|---|
| 11 | 2 500 |
| 12 | 3 000 |
| 13 | 3 500 |
| 14 | 4 000 |
| 15 | 4 600 |
| 16 | 5 200 |
| 17 | 5 900 |
| 18 | 6 600 |
| 19 | 7 300 |
| 20 | 8 100 |
| 21 | 8 900 |
| 22 | 9 800 |
| 23 | 10 700 |
| 24 | 11 600 |
| 25 | 12 600 |

</details>

À chaque niveau gagné, un message « NIVEAU N ! » s'affiche avec ta récompense et un bouton **[ Dépenser mes points ]**. Au niveau 25, tu as gagné **69 points** au total : de quoi tout acheter.

Tape `/level` pour voir ton expérience, ta barre de progression, ton « Prochain palier » et tes « Points disponibles ».

## 🛠️ /upgrade : les améliorations

`/upgrade` ouvre le menu « Améliorations » (tu peux aussi cliquer sur l'étoile de ta barre).

| Amélioration | Niveaux | Prix en points (par niveau) | Effet |
|---|---|---|---|
| Rapidité | 5 | 2, 4, 6, 8, 10 | Efficacité I à V sur ta pioche |
| Effet Haste | 2 | 4, 8 | Haste I puis Haste II, permanent |
| Effet Speed | 2 | 5, 10 | Speed I puis Speed II, permanent |
| Fortune | 3 | 2, 4, 6 | 25 %, 50 % puis 70 % de chances de bonus |

**Fortune** : quand la chance se déclenche, le minerai te donne **1 à 3 unités**. Seuls les **minerais** en profitent.

Si tu n'as pas assez de points : « Il te manque N points — gagne des niveaux en minant. »

### 🔄 Réinitialiser

Le bouton « Réinitialiser » te **rembourse tous tes points** et retire les effets, pour que tu refasses tes choix. Il a un cooldown de **48 heures** : le menu affiche « Disponible dans : ... ».

## 🚧 Plafond quotidien

Tu as droit à **3 636 blocs récompensés** par période de 24 heures. La période démarre à ton premier bloc récompensé.

Une fois le plafond atteint, tu peux continuer à miner, mais plus rien n'ira dans ta réserve ni dans ton XP. Un message t'indique l'heure de remise à zéro.

## 👀 Présence

Pour que tes blocs rapportent, tu dois être **réellement devant ton écran**. Si ta vue ne bouge plus du tout pendant que tu casses des blocs, la récompense est suspendue :

> Aucune activité détectée : tes blocs ne rapportent plus rien tant que ta vue ne bouge pas.

{% hint style="success" %}
Il suffit de bouger la souris : la récompense reprend aussitôt.
{% endhint %}

## 🛡️ Règles du serveur

- Tu es invulnérable, sans PvP, sans mobs, et la faim ne baisse pas.
- Pas de pluie, pas de ramassage ni de drop d'objets.
- Les coffres et les spawners ne sont pas utilisables.
- La lave est bloquée.

## 📋 Scoreboard

Le tableau de droite affiche :

| Ligne | Contenu |
|---|---|
| Minage | En-tête, avec « Mine N » pour ton serveur |
| Expérience | Ta jauge, par exemple « 120 / 300 », et « N XP avant le niveau X » (« Niveau maximum » à la fin) |
| Points de rang | Tes points disponibles |
| Session | Le temps passé depuis ta connexion |

## ⌨️ Commandes

| Commande | Effet | Qui peut l'utiliser |
|---|---|---|
| `/rtp` (aussi `/randomtp`, `/randomteleport`) | Téléportation aléatoire, cooldown 5 min | Tout le monde |
| `/level` (aussi `/levels`) | Affiche ton niveau, ton XP et tes points | Tout le monde |
| `/upgrade` (aussi `/boutique`, `/levelup`, `/pioche`) | Ouvre le menu des améliorations | Tout le monde |
| `/reserve` | Ouvre ta [réserve](../general/reserve.md) pour la consulter (le retrait se fait sur Faction) | Tout le monde |

Retrouve toutes les commandes dans [Commandes](../general/commandes.md).
