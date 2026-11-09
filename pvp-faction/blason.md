# 🛡️ Blason de faction

> Dessine l'emblème de ta faction : il s'affiche partout où ton nom apparaît.

## ⚡ En bref

Le **blason** est un petit emblème en pixel art (une grille de 32 × 32 cases) qui représente ta faction. Ouvre l'**atelier** avec `/f blason` ou avec le bouton **Modifier le blason** de la fiche de ta faction, dessine, importe une image ou pars d'un modèle, puis valide.

- Par défaut, seul le **Leader** peut le modifier.
- Un seul changement **toutes les 24 h** par faction.
- Une faction sans blason garde son affichage habituel (initiales sur un carré de couleur).

***

## 👀 Où le blason s'affiche

| Endroit | Ce que tu vois |
|---|---|
| **Nametag** | Le blason à côté du nom de faction au-dessus des joueurs |
| **Scoreboard** | Le blason de ta faction dans l'en-tête |
| **Classements** | Le blason de chaque faction, y compris sur l'hologramme des classements |
| **Fiche faction** (`/f show`) | Le blason de la faction et celui de ses alliés et ennemis |
| **Menu Échap** | Le blason de ta faction |

Tous les joueurs voient le blason de ta faction.

***

## 🔑 Qui peut le modifier

Le droit **Changer le blason de la faction** est réservé au **Leader** par défaut. Le Leader peut l'accorder à d'autres rôles avec `/f perm` (voir [Factions](factions.md)).

Un bouton **Modifier le blason** grisé sur la fiche veut dire que ton rôle n'a pas ce droit.

***

## 🎨 L'atelier

L'atelier s'ouvre en plein écran, avec trois onglets : **Dessiner**, **Importer** et **Modèles**. Un aperçu te montre ton blason tel qu'il apparaîtra en jeu (fiche, classement, scoreboard, nametag).

### Dessiner

Peins ton blason case par case.

| Outil | Raccourci | Effet |
|---|---|---|
| **Pinceau** | `B` | Peint avec la couleur choisie |
| **Gomme** | `E` | Rend les cases transparentes (le clic droit gomme aussi) |
| **Remplir** | `G` | Remplit toute la zone de la même couleur |
| **Pipette** | `I` | Reprend la couleur d'une case |
| **Ligne** | `L` | Trace une ligne droite entre deux cases |
| **Rectangle** | `R` | Trace le contour d'un rectangle |
| **Symétrie miroir** | `M` | Chaque pixel est copié de l'autre côté de l'axe |
| **Grille** | | Affiche ou masque le quadrillage |
| **Annuler / Rétablir** | `Ctrl+Z` / `Ctrl+Y` | Revient en arrière ou refait |

Autres éléments :

- **Palette** : jusqu'à **15 couleurs**, plus la transparence. Les touches `1` à `9` choisissent vite une couleur, et le clic droit sur une couleur la retire.
- Modifier une couleur **recolore tous ses pixels**. Tu peux saisir sa valeur hexadécimale.
- **Aperçu en jeu** : bascule entre **fond sombre** et **fond clair** pour vérifier la lisibilité.
- **Réinitialiser** : repart d'une grille vide, ou revient au blason actuel de ta faction s'il existe.

### Importer

Transforme une image en blason.

1. Clique pour choisir une image, ou **glisse un fichier** dans la fenêtre (PNG, JPG ou GIF, 8 Mo maximum).
2. **Recadre** : molette pour zoomer, clic et glisser pour déplacer le cadre carré.
3. Ajuste les **réglages** :

| Réglage | Effet |
|---|---|
| **Couleurs** | Nombre de couleurs du blason (15 maximum) |
| **Tramage** | Aucun, Doux ou Fort : mélange des pixels de deux couleurs pour simuler les dégradés |
| **Contraste** | Renforce ou adoucit le contraste de l'image |
| **Fond transparent** | Retire la couleur du fond de l'image |

Dans la palette obtenue, **clique une couleur pour la rendre transparente**. Le résultat est ensuite chargé dans **Dessiner**, où tu peux le retoucher.

{% hint style="info" %}
Ton image ne quitte jamais ton PC : seul le blason 32 × 32 est envoyé au serveur.
{% endhint %}

### Modèles

Dix modèles de départ : **Royaume**, **Chevron**, **Croisade**, **Bande**, **Anneau**, **Étoile**, **Bastion**, **Croissant**, **Brasier** et **Chêne**.

Un clic sur un modèle le charge dans **Dessiner**, à retoucher. Il remplace ton dessin en cours : `Ctrl+Z` te permet de le retrouver.

***

## ✅ Enregistrer le blason

Le bouton **Enregistrer le blason** ouvre une confirmation **Appliquer ce blason ?** avec l'aperçu **avant** et **après**. Elle te rappelle que le blason sera visible par tout le serveur, que le prochain changement n'aura lieu que dans 24 h, et que c'est gratuit. Confirme avec **Appliquer le blason**, ou annule avec `Échap`.

### Délai et blocages

Chaque faction peut changer son blason **une fois toutes les 24 h**. L'atelier affiche le temps restant avant le prochain changement.

| Message | Ce que ça veut dire |
|---|---|
| Tu n'as pas la permission | Ton rôle n'a pas le droit de changer le blason : demande au Leader |
| Prochain changement dans… | Le délai de 24 h n'est pas écoulé |
| Blason verrouillé | Le blason de ta faction ne peut plus être modifié pour le moment : contacte le staff |
| Un changement est déjà en cours | Ton enregistrement précédent n'est pas terminé |
| Tu n'as plus de faction | Tu as quitté ou perdu ta faction |

***

## ⌨️ Commandes

| Commande | Effet | Accès |
|---|---|---|
| `/f blason` | Ouvre l'atelier du blason de ta faction | Selon les permissions de faction (Leader par défaut) |
| `/f perm` | Accorde ou retire le droit de changer le blason à un rôle | Leader |

Voir aussi [Factions](factions.md) et [Classements](classements.md).
