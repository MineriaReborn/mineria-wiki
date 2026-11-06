# ⚔️ Combat, mort et primes

> Tout ce qu'il faut savoir sur la mort, les kills, les primes et l'équipement en Hardcore.

## ⚡ En bref

- Mourir = **bannissement temporaire** (12 h par défaut) et **inventaire perdu**.
- Tuer = **+1 kill**, **Vitesse III 1 min**, la **tête** de ta victime, une **prime d'une heure** sur toi.
- Une **perle** a 10 s de cooldown, une **pomme de Notch** 2 min 30.

## 💀 La mort

Quand tu meurs :

- un **éclair** frappe et un coup de tonnerre est entendu par tous ;
- ton inventaire tombe au sol (ta Boussole traqueuse ne tombe pas) ;
- tu es **expulsé** avec le message *« Vous êtes mort ! Vous devez attendre X heures avant de pouvoir revenir. »* ;
- si tu essaies de te reconnecter trop tôt : *« Vous devez attendre X heures et Y minutes avant de pouvoir vous reconnecter. »*.

Le bannissement dure **12 heures** par défaut.

{% hint style="success" %}
**Protection de réapparition** : si tu meurs **moins de 10 minutes** après ton apparition, tu n'es **pas banni**, ta mort n'est **pas comptée** et le kill n'est **pas compté** pour le tueur. Tu réapparais avec un nouveau kit. Le tueur voit : *« Ce joueur est réapparu il y a moins de 10 minutes, ce kill ne sera pas comptabilisé. »*
{% endhint %}

## 🗡️ Le kill

Quand tu tues un joueur :

- **+1 kill** ;
- **Vitesse III pendant 1 minute** ;
- il lâche sa **tête** (*« Tête de <nom> »*) ;
- tu peux obtenir une **Émeraude magique** (**10 %** de chance, voir [La traque](traque.md)) ;
- une **prime d'une heure** est ajoutée sur ta tête.

## 💰 Les primes

Chaque kill ajoute **1 heure** de prime sur ta tête (cumulable) : *« Une prime d'une heure a été ajoutée sur ta tête ! »*

- Le temps ne diminue que si tu es **connecté** et qu'il y a **au moins 2 joueurs** en ligne.
- Si tu **tues un joueur qui a une prime**, tu gagnes **1 kill bonus**, il subit **1 mort bonus** (soit 80 points d'écart au total), un message est envoyé à tout le monde et sa prime retombe à 0.

La commande `/prime` affiche les **20 joueurs recherchés** avec leur temps restant en minutes. S'il n'y en a aucun : *« Aucun joueur recherché actuellement. »*

## ⏱️ Cooldowns

| Objet | Délai |
|---|---|
| Perle de l'Ender | 10 secondes |
| Pomme d'or enchantée (Notch) | 2 min 30 |

Messages : *« Tu dois attendre encore X avant de relancer une perle. »* et *« …avant de manger une pomme de Notch. »*. La pomme d'or normale n'a pas de cooldown.

## 🧪 Potions et enchantements

- Les potions de **Force II**, de **Dégâts instantanés II** et de **Poison II** ne peuvent pas être préparées.
- **Recul** et **Frappe** sont limités au **niveau I**.

## 🛡️ Matériaux

| Matériau | Dégâts de l'épée | Durabilité de l'épée | Points de l'armure complète |
|---|---|---|---|
| Diamant | 7 | 1561 | 18 |
| Saphir | 8 | 3000 | 20 |
| Émeraude | 9 | 2800 | 22 |
| Aria | 10 | 4100 | 23 |

Le **saphir** et l'**émeraude** se trouvent en minant. L'équipement **Aria** se trouve dans les [coffres à loot](loot.md).

## 🏆 Points et classement

Ton score se calcule ainsi :

| Action | Points |
|---|---|
| Kill | +40 |
| Mort | −40 |
| 20 minutes de connexion continue | +3 |

Le **Top 10** est actualisé chaque minute. Dans le chat, un préfixe `[score]` s'affiche devant ton nom, avec tes statistiques en infobulle ; les **3 premiers** reçoivent une médaille. Le scoreboard affiche le **meilleur joueur** et son score.

## ⌨️ Commandes

| Commande | Effet | Qui peut l'utiliser |
|---|---|---|
| `/prime` (aussi `/wanted`, `/bounty`) | Liste les 20 joueurs recherchés | Tous |
| `/classement` (aussi `/ranking`, `/leaderboard`) | Affiche le TOP 10 HARDCORE (survol : kills, morts, ratio, temps de jeu) | Tous |
| `/stats [joueur]` (aussi `/statistiques`) | Kills, morts, ratio, temps de jeu et points totaux | Tous |
| `/playtime` | Temps total, session en cours et minutes avant les +3 points | Tous |
