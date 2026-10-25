# 🌲 PvE

> Téléportation aléatoire, Nether, Mob Zone, donjons et machines de ferme : tout ce qu'il faut pour farmer sans te battre contre d'autres joueurs.

## ⚡ En bref

| Activité | Ce que ça fait |
| --- | --- |
| 🎲 **Téléportation aléatoire** | Le PNJ Téléporteur du spawn t'envoie en pleine nature, en lieu sûr (délai : 5 min) |
| 🔥 **Nether** | Accessible par les portails du serveur |
| 🗡️ **Mob Zone** | Zone de farm de mobs : épée offerte, loots envoyés en réserve |
| 🏰 **Donjons** | 5 donjons solo avec boss, clé nécessaire, anneau à gagner |
| 🌾 **Machines de ferme** | Récolteur et Brûleur d'Âmes, à poser dans le claim de ta faction |

***

## 🎲 Téléportation aléatoire

Clique sur le PNJ **Téléporteur** au spawn : deux boutons apparaissent dans le chat, **[CONFIRMER]** et **[ANNULER]**. Il n'y a pas de commande pour lancer une téléportation aléatoire de n'importe où.

| Info | Valeur |
| --- | --- |
| Distance | entre 200 et 5 000 blocs du centre |
| Délai entre deux utilisations | 5 minutes |
| Monde | Overworld uniquement |
| Destination | pleine nature (hors claims), jamais en plein océan ou sur une rivière |

* Impossible de se téléporter en combat.
* Si aucun emplacement sûr n'est trouvé, tu peux réessayer : ton délai n'est pas consommé.

***

## 🔥 Nether

Le portail du Nether t'emmène au **Nether du serveur**. En revenant par le portail, tu atterris au **spawn**. Après un passage, un court délai (3 secondes) évite de repasser par erreur.

***

## 🐺 Spawn naturel des mobs

Pour garder le monde ouvert agréable, certains monstres **n'apparaissent plus naturellement dans l'Overworld** :

<details>

<summary>Voir la liste</summary>

* Zombies
* Squelettes
* Creepers
* Araignées et araignées bleues
* Endermen
* Poissons d'argent
* Slimes
* Chauves-souris

</details>

Les œufs et les spawners fonctionnent toujours. Le Nether et l'End ne sont pas concernés.

***

## 🗡️ Mob Zone

Une zone de nuit éternelle pour farmer des mobs sans risque.

### Entrer et sortir

* Clique droit sur le PNJ **Mob Zone** pour entrer.
* Ton inventaire est **mis de côté** et te sera rendu à la sortie. Tu reçois le **Dard Royal**, une épée offerte.
* Pour partir, tape `/spawn`.

### Les règles

* Les mobs sont **immobiles** et ne t'attaquent pas : tu ne subis aucun dégât et ta faim ne baisse pas.
* Les **loots** partent directement dans ta **réserve**. L'**XP** reste sur toi.
* Si tu meurs, tu ne perds ni objet ni XP.
* Tu ne peux ni poser ni casser de blocs, ni jeter ou ramasser d'objets. Le Dard Royal ne peut pas être déplacé dans un coffre.
* Seules quelques commandes marchent : `/spawn`, `/bottlexp` (mettre ton XP en bouteille, avec la compétence **Embouteilleur** ; la bouteille part dans ta réserve), `/epee` et `/reserve`.
* Certaines zones sont réservées aux grades **VIP**, **SVIP** et **Héros**, qui bénéficient aussi de **Speed II**.

### Personnaliser le Dard Royal

`/epee` (ou `/sword`) ouvre le menu des enchantements de ton épée, uniquement dans la Mob Zone.

| Enchantement | Effet | Grade |
| --- | --- | --- |
| Tranchant V | Augmente tous tes dégâts | Tous |
| Fléau des arthropodes V | Ravage araignées et poissons d'argent | Tous |
| Aura de feu II | Enflamme les mobs frappés | Tous |
| Châtiment V | Ravage zombies et squelettes | Tous |
| Butin I | Plus de butin | VIP |
| Butin II | Encore plus de butin | SVIP |
| Butin III | Butin maximal | Héros |

Par défaut, ton épée a Tranchant V.

***

## 🏰 Donjons

Cinq donjons, un boss dans chacun. Tu y vas **seul**, avec la **clé** correspondante.

### Entrer

1. Tiens la **clé** du donjon dans ta main.
2. Entre dans son **portail**.
3. Ta clé est consommée. Une courte génération (3 secondes) prépare ton instance, puis tu es téléporté.

Si tous les donjons sont occupés, tu es placé en **file d'attente** : reste en safezone. Jusqu'à 10 donjons peuvent tourner en même temps.

{% hint style="warning" %}
Si tu meurs dans le donjon, **tout ton inventaire est détruit** : seul le staff peut le rembourser. N'emporte pas d'objets que tu ne peux pas perdre.
{% endhint %}

### Pendant le combat

* Tu dois **éliminer le boss**. Des renforts arrivent quand il passe sous 2/3 puis 1/3 de ses PV.
* Aucune commande ni téléportation n'est possible, sauf `/dungeon quit`.
* Si tu te déconnectes, tu as **10 minutes** pour revenir reprendre ton donjon.
* Pour abandonner, utilise `/dungeon quit`. **La clé n'est pas remboursée.** Quitter la file d'attente rembourse ta clé.

### Les donjons

| Donjon | Rareté | Boss | PV du boss | Récompenses |
| --- | --- | --- | --- | --- |
| Forêt Ancienne | Commun | Ent Man | 250 | Anneau de Résistance, Coeur de l'Ent Man |
| Tanière de Direfang | Commun | DireFang | 220 | Anneau de Vitesse II, Coeur du DireFang |
| Trône du Roi Gobelin | Rare | Roi Gobelin | 350 | Anneau de Force I, Coeur du Roi Gobelin |
| Temple du Scorpion Royal | Rare | Scorpion Royal | 400 | Anneau de Résistance au Feu, Coeur du Scorpion Royal |
| Mausolée du Roi Squelette | Légendaire | Roi Squelette | 650 | Anneau d'Antichute, Coeur du Roi Squelette |

Les clés s'appellent « Clé de l'Ent Man », « Clé du DireFang », « Clé du Roi Gobelin », « Clé du Scorpion Royal » et « Clé du Roi Squelette ».

Les **Cœurs** des boss servent à forger les objets primordiaux à l'Enclume Primordiale : voir [Crafts](../general/crafts.md).

<details>

<summary>Voir les conseils et les renforts de chaque boss</summary>

**Forêt Ancienne : Ent Man**

* Il piétine en zone : une attaque d'environ 2 secondes, sois prêt à t'écarter.
* Ses bras peuvent te ralentir pendant 3 secondes.

**Tanière de Direfang : DireFang**

* Il frappe en zone sur 5 blocs autour de lui.
* Après certaines attaques, il peut être étourdi : c'est le moment de frapper.

**Trône du Roi Gobelin : Roi Gobelin**

* Vague 1 : 4 Gobelins Verts et 4 Guerriers Gobelins.
* Vague 2 : 3 Archers Gobelins.
* Vague 3 : 1 Chaman Gobelin et 1 Chef Gobelin.
* Le Chaman soigne les autres toutes les 10 secondes : élimine-le en priorité.

**Temple du Scorpion Royal : Scorpion Royal**

* Il empoisonne et peut s'enfouir dans le sol.
* Jusqu'à 6 Bébés Scorpions l'accompagnent.

**Mausolée du Roi Squelette : Roi Squelette**

* Vague 1 : 4 Guerriers Squelettes.
* Vague 2 : 4 Archers Squelettes.
* Vague 3 : 2 Chamans Squelettes et 2 Guerriers.
* Il invoque des renforts environ toutes les 20 secondes et peut se téléporter.
* Les Chamans soignent, les Guerriers parent.

</details>

### Récompenses

À la victoire, l'**anneau** et le **butin** sont envoyés dans ta **réserve** (bouton **[ Ouvrir ma réserve ]** dans le chat). Les anneaux se placent sur les emplacements d'anneau, qui se débloquent avec ta progression : voir [Progression](progression.md).

***

## 🌾 Machines de ferme

Deux machines automatiques, à poser **dans le claim de ta faction**.

### Règles générales

* Une faction peut poser **5 machines + 1 par tranche de 2 niveaux** de faction.
* Deux machines ne peuvent pas se chevaucher : garde de la distance entre elles.
* Elles travaillent uniquement quand **au moins un membre** de ta faction est connecté, et seulement dans les claims de ta faction.
* **Clic droit** sur la machine pour ouvrir son interface : améliorer, récupérer l'argent ou l'XP, et voir la réserve. Il faut avoir l'autorisation de ta faction pour l'ouvrir.
* Pour déplacer une machine, casse-la : tu la récupères avec son niveau. **Vide d'abord sa réserve**, son contenu est perdu à la casse.
* L'amélioration d'un palier coûte de l'argent.

Voir [Factions](factions.md) pour les niveaux et les autorisations.

### 🌽 Récolteur

Il **récolte automatiquement les cultures mûres** de sa zone : blé, carottes, pommes de terre, orge, framboises et myrtilles. Les produits vont dans sa réserve. Sa recette est dans [Crafts](../general/crafts.md).

| Palier | Zone | Hauteur | Vitesse | Réserve | Options | Coût |
| --- | --- | --- | --- | --- | --- | --- |
| 1 | 7×7 | 20 | ×1,0 | 27 | | Gratuit |
| 2 | 9×9 | 40 | ×1,4 | 27 | | 10 000 |
| 3 | 13×13 | 60 | ×1,6 | 54 | Replantation | 100 000 |
| 4 | 15×15 | 80 | ×1,8 | 54 | Replantation, vente auto | 500 000 |
| 5 | 17×17 | 100 | ×2,0 | 108 | Replantation, vente auto | 1 000 000 |

* **Replantation** : les cultures repoussent toutes seules.
* **Vente auto** (à activer dans l'interface) : les récoltes sont vendues au prix du shop. L'argent s'accumule dans la machine, jusqu'à **11 000** par jour au palier 4 et **12 500** au palier 5.

### 🔥 Brûleur d'Âmes

Il **élimine les monstres** qui passent dans sa zone, un à la fois. Il stocke une part de l'**XP** et des **loots**. Sa recette est dans [Crafts](../general/crafts.md).

| Palier | Zone | Vitesse | Réserve | XP récupérée | Loots récupérés | Coût |
| --- | --- | --- | --- | --- | --- | --- |
| 1 | 3×3 | ×1,0 | 27 | 30 % | 5 % | Gratuit |
| 2 | 5×5 | ×1,2 | 27 | 30 % | 10 % | 10 000 |
| 3 | 5×5 | ×1,4 | 27 | 40 % | 30 % | 100 000 |
| 4 | 7×7 | ×1,5 | 54 | 50 % | 40 % | 500 000 |
| 5 | 9×9 | ×1,6 | 54 | 60 % | 50 % | 1 000 000 |

Dans l'interface, **récupère** l'XP stockée pour la recevoir en niveaux.

***

## ⌨️ Commandes

| Commande | Effet | Qui peut |
| --- | --- | --- |
| `/rtp confirm` | Confirme la téléportation proposée par le PNJ Téléporteur (bouton [CONFIRMER]) | Tous |
| `/rtp cancel` | Annule la téléportation (bouton [ANNULER]) | Tous |
| `/epee` | Personnalise le Dard Royal (alias `/sword`), en Mob Zone | Tous |
| `/dungeon` | Accède à l'aide des donjons | Tous |
| `/dungeon quit` | Abandonne ton donjon (clé non remboursée) ou quitte la file d'attente | Tous |
| `/spawn` | Quitte la Mob Zone et retourne au spawn | Tous |
| `/bottlexp [niveaux]` | Met ton XP en bouteille, sans perte | Compétence « Embouteilleur » |
| `/reserve` | Ouvre ta réserve | Tous |
