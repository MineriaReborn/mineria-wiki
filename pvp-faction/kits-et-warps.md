# 🧰 Kits et warps

> Récupère ton équipement et voyage entre les zones du serveur grâce à deux menus.

## ⚡ En bref

- `/kits` ouvre le **menu des kits** : tu vois tous les kits, leur état et leur contenu, et tu les récupères d'un clic.
- `/warps` ouvre le **menu des warps** : un clic sur une carte te téléporte.
- Ces deux menus existent sur **PvP-Factions**.
- Tu peux aussi taper `/kit <nom>` ou `/warp <nom>` pour aller droit au but.

***

## 🎒 Le menu des kits

Ouvre-le avec `/kits` (ou `/kit`). La liste des kits est à gauche, le détail du kit choisi est à droite. En haut, une phrase résume la situation, par exemple « 5 kits · 2 prêts à récupérer ».

### Les filtres

Trois onglets, avec le nombre de kits dans chacun :

| Onglet | Ce qu'il montre |
|---|---|
| **Tous** | Tous les kits |
| **Disponibles** | Les kits que tu peux récupérer maintenant |
| **Verrouillés** | Les kits que tu ne possèdes pas encore |

Les kits disponibles sont listés en premier.

### L'état de chaque kit

| État | Ce que ça veut dire |
|---|---|
| **Disponible** | Tu peux le récupérer |
| **En recharge** | Le temps restant avant de pouvoir le reprendre s'affiche (par exemple « Dans 3 h 12 min ») |
| **Épuisé** | Tu as utilisé toutes tes récupérations : le menu indique tes utilisations (par exemple « 1 / 1 ») |
| **Verrouillé** | Un cadenas : tu ne possèdes pas ce kit |

### Le détail d'un kit

Clique sur un kit pour voir :

- sa **recharge** : le temps à attendre entre deux récupérations, qui démarre quand tu le prends ;
- ses **utilisations** : « Illimitées », ou le nombre de fois que tu l'as pris sur le total autorisé ;
- les **cases nécessaires** face à tes **cases libres** : il te faut assez de place dans ton inventaire pour que le kit arrive en entier ;
- son **contenu complet** : passe la souris sur un objet pour voir son détail.

### Prévisualiser un kit que tu n'as pas

Tu peux ouvrir le détail d'un kit **verrouillé** : un bandeau « Aperçu » te rappelle que tu vois le contenu sans posséder le kit. Pour l'obtenir, le menu te dit : « Obtiens ce kit avec un grade ou dans une box. »

- Les kits de grade s'obtiennent en montant de [grade](../general/grades.md).
- Les kits métier se gagnent dans les [box](box.md).

### Récupérer un kit

1. Choisis un kit **Disponible**.
2. Vérifie que tu as assez de cases libres.
3. Clique sur **Récupérer le kit** : les objets arrivent directement dans ton inventaire.

Une notification te confirme le résultat (« Kit reçu ») ou t'explique ce qui bloque : kit verrouillé, en recharge, épuisé ou inventaire plein. Quand le bouton est grisé, il indique la raison (« Inventaire plein », « En recharge », « Épuisé » ou « Verrouillé »). Si tu cliques trop vite, le jeu te demande d'attendre quelques secondes.

{% hint style="info" %}
Les objets des kits sont **liés** : impossible de les vendre à l'hôtel des ventes, de les échanger ou de les offrir. Voir [Grades](../general/grades.md).
{% endhint %}

***

## 🌐 Le menu des warps

Ouvre-le avec `/warps` (ou `/warp`), ou avec la touche **W** dans le menu Échap : voir [Launcher et client](../general/client.md).

Chaque warp est une **carte** avec son icône, son nom et sa description. En haut, une phrase résume le nombre de destinations et celles qui te sont accessibles.

### L'état de chaque warp

| État | Ce que ça veut dire |
|---|---|
| **Ouvert** | Tu peux t'y téléporter |
| **Fermé** | Le warp est fermé pour le moment : il rouvrira plus tard |
| **Verrouillé** | Tu n'y as pas encore accès |

Passe la souris sur une carte **fermée** ou **verrouillée** pour lire l'explication. Les warps ouverts sont listés en premier.

### Te téléporter

**Clique sur une carte ouverte** : tu es téléporté après le délai de téléportation habituel, **5 secondes sans bouger**. Si tu bouges, la téléportation est annulée. Elle est aussi impossible en combat.

{% hint style="info" %}
Au départ, le seul warp ouvert est **Portail**. Le warp **Shop** se débloque avec la compétence « Accès marché » : voir [Progression](progression.md).
{% endhint %}

***

## ⌨️ Commandes

| Commande | Effet | Accès |
| --- | --- | --- |
| `/kits` (`/kit`) | Ouvre le menu des kits | Tous |
| `/kit <nom>` | Récupère directement un kit, sans ouvrir le menu | Selon ton grade ou tes box |
| `/kit view <nom>` | Ouvre le menu des kits sur ce kit, même si tu ne le possèdes pas | Tous |
| `/warps` (`/warp`) | Ouvre le menu des warps | Tous |
| `/warp <nom>` | Te téléporte directement à un warp, après le délai habituel | Tous, si le warp t'est ouvert |
| `/warp info <nom>` | Affiche la description et l'état d'un warp | Tous |

Voir aussi [Commandes](../general/commandes.md) et [Box](box.md).
