# 🤺 Duels

> Défie un joueur en 1v1 pour gagner sa mise, ou participe à un tournoi organisé par le staff.

## ⚡ En bref

* Un duel est un combat **1v1 équipé à l'identique** : même kit pour les deux joueurs.
* Chacun **mise** de l'argent ou un item. Le vainqueur remporte **les deux mises**.
* Tu passes par un PNJ : il n'y a pas de commande `/duel`.
* Les **tournois** sont lancés par le staff et se jouent en élimination directe.

## ⚔️ Les duels 1v1

### Accéder aux duels

Parle au PNJ **Duel** dans l'arène. Depuis le spawn, un autre PNJ te téléporte jusqu'à l'arène.

L'écran « Duels » affiche : « Défie un joueur en 1v1 : le vainqueur remporte les deux mises. »

### Les onglets

* **Offres disponibles (N)** : les défis lancés par d'autres joueurs. Filtre par Tout, Argent ou Item, ou cherche un pseudo avec « Rechercher un pseudo ».
* **Mes offres (N)** : tes propres défis, en deux sous-onglets « En cours » et « Terminées ».
* **CRÉER UNE OFFRE** : lance ton propre défi.
* **MES STATISTIQUES** : tes Victoires, Défaites, Ratio et Pots remportés.

{% hint style="info" %}
Un « pot » correspond à 2 fois la mise. Les duels d'item ne comptent pas dans les statistiques.
{% endhint %}

### Créer une offre

1. Choisis le type de mise : **Argent** ou **Item**. Le mode est « 1V1 Standardisé ».
2. Indique ta **mise** (au minimum 1 $).
3. Clique sur **Publier l'offre**.

| Règle | Détail |
| --- | --- |
| Mise d'argent | Prélevée dès la publication |
| Mise d'item | Déposée dans un coffre. La première case compte ; fermer le coffre vide annule l'offre |
| Durée de l'offre | 5 minutes |
| Annulation ou expiration | Ta mise t'est rendue |

Pour retirer une offre, clique sur « Annuler l'offre » (ou « Garder » pour renoncer). 

### Accepter une offre

Un message te présente le défi : « te défie en 1V1 Standardisé ».

{% tabs %}
{% tab title="Mise en argent" %}
* Tu vois « Mise à égaler » et « Pot total ».
* Clique sur **Accepter le duel** : la mise est prélevée tout de suite.
* Le duel démarre dès que l'arène est libre. Tu peux voir : « L'arène est occupée, tu es en file d'attente. »
{% endtab %}

{% tab title="Mise en item" %}
* Tu déposes d'abord l'item qui égale la mise.
* Le créateur voit alors « relève ton duel » avec « SA MISE » et « TA MISE ».
* Il choisit **Accepter le duel** ou **Refuser**. En cas de refus : « Offre refusée : chacun a récupéré son item. »
* Si personne ne répond à temps : « Délai écoulé : le serveur rendra les items. »
{% endtab %}
{% endtabs %}

Quand c'est parti : « Duel accepté ! Téléportation dans l'arène. »

### Pendant le combat

* Un décompte de **3 secondes** précède le combat.
* Vous avez le même kit. Ton inventaire habituel t'est rendu après le duel.
* Seules les commandes `/feed` et `/eat` fonctionnent. Le [shop et l'HDV](economie.md) sont fermés.
* À la fin, le gagnant est soigné et tout le monde revient à son point de départ, avec son équipement.
* Il n'y a **pas de match nul** : le duel ne s'arrête pas sur un temps écoulé.

{% hint style="success" %}
**Astuce.** Les mises d'argent sont remboursées si l'offre n'est jamais acceptée : tu ne risques rien à publier.
{% endhint %}

## 🏟️ Les arènes

Plusieurs arènes existent. Quand un duel commence, un **couvercle de verre rouge** se forme à 7 blocs de hauteur.

* L'arène se rouvre dès qu'elle est vide, ou après 2 minutes au plus.
* Si aucun adversaire n'arrive au bout d'une minute, le joueur seul est éjecté.

## 🏆 Les tournois

Un tournoi est lancé par le staff et annoncé dans le chat, avec des boutons cliquables : **[ S'inscrire ]**, **[ Créer une équipe ]**, **[ Rejoindre ]**, **[ Regarder ]** et **[ Infos ]**.

### Comment ça marche

| Point | Détail |
| --- | --- |
| Format | N contre N (ou solo), élimination directe |
| Inscriptions | 300 secondes (5 minutes) |
| Participants | 300 joueurs maximum |
| Combats | Autant de combats en même temps que d'arènes |
| Durée d'un combat | 5 minutes, puis mort subite |
| Annulation | S'il y a moins de 2 inscrits |

* **Viens sans stuff.** Le kit est fourni au combat : « Vide ton inventaire avant de t'inscrire, le kit est fourni au combat. »
* Après un décompte de 5 secondes, le combat commence.
* Si personne ne l'a emporté en 5 minutes, la **mort subite** démarre (30 secondes d'effet Wither). Puis on départage : plus de survivants, sinon plus de vie restante, sinon tirage au sort.
* Si le nombre d'équipes est impair, une équipe est « qualifiée d'office ».
* Les meilleurs reçoivent des récompenses (« Objets pour le top N ») dans ta [Réserve](economie.md) (`/reserve`).

{% hint style="warning" %}
Une fois le tournoi commencé, les inscriptions sont closes. L'HDV est fermé pendant un tournoi.
{% endhint %}

### Jouer en équipe

1. Le chef crée l'équipe : `/tournament create [nom]`. Le nom contient des lettres, chiffres, `_` ou `-` (12 caractères maximum).
2. Il invite ses coéquipiers : `/tournament invite <joueur>`.
3. Chaque invité accepte avec `/tournament join <équipe>`.
4. Pour quitter : `/tournament leave`. Si le chef part avant le début, l'équipe est dissoute.

Pour regarder sans jouer : `/tournament spec` te mène au lobby de spectateurs.

## ⌨️ Commandes

| Commande | Effet | Qui peut |
| --- | --- | --- |
| `/tournament` (`/tournoi`) | Affiche l'état du tournoi | Tous |
| `/tournament teams` (`/tournament equipes`) | Liste les équipes | Tous |
| `/tournament create [nom]` | T'inscris en solo ou crées une équipe | Tous, pendant les inscriptions |
| `/tournament invite <joueur>` | Invite un joueur dans ton équipe | Chef d'équipe |
| `/tournament join <équipe ou joueur>` | Rejoint une équipe qui t'a invité | Joueur invité |
| `/tournament leave` | Quitte l'équipe ou le tournoi | Tous, avant le début |
| `/tournament spec` (`/tournament spectate`) | Va regarder depuis le lobby | Tous |
| `/tournament help` | Affiche l'aide | Tous |

Les duels s'ouvrent par le PNJ, sans commande. Pour dépenser tes gains, va voir l'[économie](economie.md).
