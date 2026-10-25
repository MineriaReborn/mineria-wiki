# 🌐 Serveurs et hub

> Mineria, c'est un réseau de serveurs. Tu arrives toujours au hub, puis tu choisis où jouer.

## ⚡ En bref

* Tu arrives sur un **hub**, le point de départ du réseau.
* Ta **boussole** (slot 4) ouvre le sélecteur de serveurs.
* `/hub` te ramène au hub depuis n'importe quel serveur.
* Si un serveur est complet, tu rejoins une **file d'attente** et le transfert est automatique.

***

## 🏠 Arrivée au hub

À ta toute première connexion, tu vois le message « Bienvenue sur Mineria, <pseudo>! ».

Au hub, tu ne peux pas casser ni modifier ton inventaire, et il n'y a ni pluie, ni dégâts, ni PvP. Les coffres, portes et tables restent fermés. Pas de panique : c'est fait pour que tu puisses souffler et choisir.

Tu reçois une boussole nommée **« Selection de Serveur.. ★ »** dans le slot 4. Fais un **clic droit** pour ouvrir le sélecteur.

***

## 🧭 Le sélecteur de serveurs

Le sélecteur s'appelle **« CHOISIS TON SERVEUR »**. Il liste les serveurs de jeu et, dans une section **« HUBS »**, les hubs disponibles. Chaque serveur affiche son nombre de joueurs connectés.

Clique sur un serveur à gauche pour voir ses détails à droite.

### Les états d'un serveur

| Étiquette | Ce que ça veut dire |
| --- | --- |
| **TU ES ICI** | Tu es déjà connecté sur ce serveur (« Vous êtes ici »). |
| **COMPLET** | Plus de place : tu peux rejoindre la file. |
| **EN FILE** | Tu attends déjà une place sur ce serveur. |
| **TA PLACE #n** | Ta position dans la file. |
| **MAINTENANCE** | Seuls les joueurs autorisés peuvent le rejoindre. |
| **HORS LIGNE** | Le serveur ne répond pas. Réessaie dans quelques instants. |

### Les boutons

| Bouton | Quand |
| --- | --- |
| **Rejoindre** | Le serveur est ouvert. |
| **Rejoindre la file** | Le serveur est complet. |
| **Quitter la file** | Tu es déjà dans la file. |
| **Tu es ici** | Tu es déjà sur ce serveur. |
| **En maintenance** | Le serveur est fermé aux joueurs. |
| **Hors ligne** | Le serveur est injoignable. |

***

## ⏳ La file d'attente

Quand un serveur est complet, rejoins la file : **ta place te suit sur tout le réseau**. Tu peux jouer ailleurs en attendant.

* Le détail du serveur affiche combien de joueurs attendent.
* Ta carte **« TA PLACE DANS LA FILE »** montre ta position (« sur N ») et combien de joueurs sont derrière toi.
* Le chat te rappelle ta place toutes les 2 minutes si elle a bougé. Dans les 5 premières places, tu es prévenu : « prépare-toi, le transfert est automatique ».
* Quand vient ton tour (« C'est ton tour ! »), le transfert est **automatique**, même depuis un autre serveur.
* Tu ne peux être que dans **une seule file** à la fois. Changer de file te demande confirmation (« Changer de file ? » : tu perds ta place).
* Si tu quittes la file puis reviens, tu repars en **dernière position**.
* Si tu te **déconnectes**, ta place est gardée **3 minutes** : reconnecte-toi à temps et tu la retrouves (« Tu as retrouvé ta place dans la file »).
* Si le transfert échoue, tu repasses **en tête de file**.
* Si le serveur passe en maintenance ou hors ligne, la file est en pause (« FILE EN PAUSE ») : ta place est gardée jusqu'à sa réouverture.
* Si le serveur refuse ta connexion (bannissement, liste blanche), tu sors de la file et la raison s'affiche dans le chat.

{% hint style="info" %}
La file est un « premier arrivé, premier servi » : le grade ne fait pas passer devant. Si tu es **en combat** quand vient ton tour, tu gardes ta place et le transfert se fait à la fin du combat (« Ton tour est arrivé : transfert à la fin de ton combat. »).
{% endhint %}

***

## 🔧 Maintenance

Un serveur en maintenance affiche **MAINTENANCE** dans le sélecteur. Seuls les joueurs autorisés peuvent le rejoindre. Les joueurs déjà dessus ne sont pas expulsés.

***

## 🏃 Le parcours de jump du hub

Le hub cache un parcours de saut chronométré.

1. Le **premier checkpoint** lance le chrono (« Chronomètre démarré ! ») et te donne **Speed I**.
2. Chaque checkpoint affiche « Checkpoint atteint ! » : tu réapparais ici si tu tombes.
3. Si tu tombes, tu es ramené au dernier checkpoint (« Téléportation au dernier checkpoint ! »).
4. Le **dernier checkpoint** termine le parcours (« Parcours terminé ! ») : ton temps et le record s'affichent, puis tu retournes au spawn du hub.
5. Un nouveau record du serveur est annoncé à tout le monde.

Sur le hub, `/classement` (ou `/leaderboard`) affiche le **« Classement Jump »** : les 10 meilleurs temps.

***

## 🔗 Voir aussi

* [Commandes](commandes.md)
* [Règles](regles.md)
* [Classements](classements.md)

## ⌨️ Commandes

| Commande | Effet |
| --- | --- |
| `/hub` (alias `/lobby`) | Te renvoie vers un hub. Désactivée en combat. |
| `/classement` | Sur le hub : classement du Jump (top 10). |
| `/file` (alias `/queue`) | Affiche ta place dans la file d'attente. |
| `/file quitter` | Quitte la file (tu perds ta place). |
