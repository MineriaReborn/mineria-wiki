# ⚔️ Guerre et pillage

> Tout ce qu'il faut savoir pour attaquer une faction ennemie, ou pour défendre la tienne.

## ⚡ En bref

- Une faction qui a **plus de claims que de power** est **pillable** : l'ennemi peut lui prendre ses territoires.
- Chaque soir, les **heures de guerre** doublent les pertes de power.
- Un **contrat de guerre** oppose deux factions pendant 24 h.
- La **Stèle maudite** permet d'attaquer un claim ennemi de façon organisée.

## 🔓 Quand une faction est-elle pillable ?

Dès que ses claims dépassent son [power](factions.md), le message « Attention. Votre faction est maintenant pillable. » s'affiche. Une faction ennemie peut alors **claim par-dessus** ses chunks.

Pour t'en protéger :

- Ne claim pas plus que ton power ne le permet.
- Évite les morts inutiles : chacune te coûte 2 de power.
- Les membres actifs font remonter le power (0,2 par minute en jeu).

## 🕕 Heures de guerre

Tous les jours de **18 h à 20 h** (heure de Paris), les pertes de power sont **doublées**. C'est le moment où ça chauffe le plus.

## 📜 Contrat de guerre

Le Leader d'une faction peut proposer un contrat à une faction **ennemie**.

| Règle | Détail |
|---|---|
| Durée | **24 h** |
| Effet | Les pertes de power entre les deux factions sont **doublées** et le power se régénère **2 fois plus lentement** |
| Annulation | Impossible une fois signé |
| Invitation | Expire au bout de **5 minutes** |
| Limite | Un seul contrat à la fois |
| Pendant les heures de guerre | Le contrat est suspendu |

Les factions pacifiques ne peuvent pas signer de contrat.

1. Le Leader propose : `/f contrat <faction>`.
2. L'autre Leader répond : `/f contrat accepter` ou `/f contrat refuser`.

## 🗿 La Stèle maudite

La Stèle maudite est l'arme de pillage des factions. Pour la fabriquer, il faut avoir débloqué la compétence **Stèle maudite** (grade Chevalier, voir [Progression](progression.md)). Sa recette est dans [Crafts](../general/crafts.md).

### Comment ça marche

1. Pose la stèle sur de l'**obsidienne**, dans un **claim ennemi**, avec 2 blocs libres au-dessus.
2. Elle met **25 minutes** à s'armer, puis reste active **1 heure**.
3. Pendant ce temps, elle s'use **couche par couche** sous les TNT des attaquants.
4. Si les défenseurs la détruisent avant, l'attaque échoue : la stèle est **cassable**.

{% hint style="info" %}
Au moins un défenseur doit être en ligne pour que le compte à rebours avance. Si la faction visée est restée inactive 24 h, l'attaque se déroule sans cette condition.
{% endhint %}

{% hint style="warning" %}
Tant qu'une Stèle maudite est posée sur un de tes claims, tu ne peux pas le libérer : « Impossible d'unclaim : une Stèle Maudite est posée sur l'un de vos territoires. »
{% endhint %}

## 🛡️ Règles de combat entre factions

- Pas d'attaque entre membres d'une même faction ni entre alliés.
- Le PvP est **interdit en SafeZone** et sur le territoire d'une faction pacifique.
- Le PvP est désactivé **3 secondes** après ta connexion.
- Dans un claim ennemi, `/home`, `/sethome`, `/spawn`, `/tpa`, `/tpahere` et `/tpaccept` sont bloqués.
- Personne ne peut construire dans le claim d'une faction ennemie, même hors ligne.

### Le home de pillage

À partir du **niveau 7**, ta faction peut poser un **home de pillage** dans un claim ennemi non protégé par l'anti-home : `/f sethome pillage`, puis `/f home pillage` pour y retourner pendant **30 minutes**.

## ⌨️ Commandes

| Commande | Effet | Qui peut l'utiliser |
|---|---|---|
| `/f contrat <faction>` | Propose un contrat de guerre | Leader |
| `/f contrat accepter` · `/f contrat refuser` | Répond à une proposition | Leader |
| `/f sethome pillage` | Pose un home de pillage | Faction de niveau 7 minimum |
| `/f home pillage` | Y retourne | Faction de niveau 7 minimum |
| `/f enemy <faction>` | Déclare une faction ennemie | Modérateur et plus |

Voir aussi [Factions](factions.md) pour les claims, le power et les relations.
