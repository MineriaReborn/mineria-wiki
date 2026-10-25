# 📦 Réserve

> Ta réserve met de côté les objets que tu gagnes, pour que tu les récupères quand tu veux sur Faction.

## ⚡ En bref

- C'est un **stockage personnel** : tes gains y arrivent tout seuls, sans que ton inventaire soit plein.
- Tu l'ouvres avec `/reserve`, sur Faction, Minage 1 et Minage 2.
- Tu ne peux **retirer** tes objets que sur le serveur **Faction**.
- Chaque ligne indique la **provenance** de l'objet.

## 📖 À quoi ça sert ?

Au Minage, des milliers de blocs partent directement dans ta réserve : plus besoin de t'arrêter pour vider ton inventaire. D'autres activités y déposent aussi leurs récompenses. Tu récupères tout plus tard, quand tu es prêt, sur Faction.

## 🖥️ Ouvrir et utiliser la réserve

Tape `/reserve` (ou clique sur le coffre « Réserve » de ta barre d'objets au Minage). L'écran « Ma réserve » s'ouvre.

- **Recherche** : « Rechercher un item ou une source... ».
- **Sources** : filtre par provenance (« Toutes » ou une source précise).
- **Tri** : « Triés : ajout le plus récent d'abord ».
- **Pages** : si tu as beaucoup d'entrées, elles sont réparties en pages.
- **Survol** : affiche la quantité, la source et le dernier ajout.

Pour retirer un objet, **clique dessus**. Une fenêtre s'ouvre : saisis le « Montant à retirer », puis clique sur « Retirer le montant ». Tu reçois l'objet dans ton inventaire.

{% hint style="warning" %}
Hors de Faction, l'écran affiche « Retrait impossible ici : retourne dans le monde principal ou le Nether du serveur Faction. » Tu peux regarder ta réserve, mais pas la vider.
{% endhint %}

## 📥 D'où viennent les objets ?

| Source | Ce qui arrive dans ta réserve |
|---|---|
| Minage | Chaque bloc miné |
| Mob Zone | Les objets lâchés par les mobs que tu tues |
| Donjon | Clé remboursée, anneau de victoire et récompenses |
| Hôtel des Ventes | Les objets que tu as achetés |
| Retour de vente | Tes objets invendus, retirés ou expirés |
| Échange | Les objets qui ne tenaient pas dans ton inventaire |
| Event | Récompenses de classement des events, loot surprise de l'event Farm |
| Box | Clés ou récompenses qui ne tenaient pas dans ton inventaire |
| Tournoi | Récompenses de classement |
| Bouteille d'XP | Bouteille créée en Mob Zone |

## 📏 Limites

| Limite | Valeur |
|---|---|
| Entrées par joueur | 200 |
| Quantité par entrée | 1 000 000 |

Les objets identiques de même source sont **regroupés** sur une seule entrée.

Quand tu atteins une limite, le surplus ne se perd pas : il est remis dans ton inventaire, ou jeté au sol s'il est plein. Tu vois alors « Réserve pleine (200 entrées max, 1000000 par entrée) : N remis dans ton inventaire ou au sol. »

## 🏠 Où la récupérer ?

Le retrait fonctionne **uniquement sur le serveur Faction**, dans le monde principal et le Nether. Il est refusé :

- en **combat** : « Impossible de récupérer ta réserve en combat. » ;
- pendant un **duel ou un tournoi** : « Impossible de récupérer ta réserve pendant un duel ou un tournoi. » ;
- si ton **inventaire est plein** : « Ton inventaire est plein. » ;
- ailleurs : « Récupération impossible ici. »

## ⌨️ Commandes

| Commande | Effet | Qui peut l'utiliser |
|---|---|---|
| `/reserve` (aussi `/réserve`) | Ouvre ta réserve | Tout le monde |

Pour miner et remplir ta réserve, lis la page [Minage](../minage/index.md).
