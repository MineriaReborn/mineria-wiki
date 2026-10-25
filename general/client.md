# 🖥️ Launcher et client

> Mineria se joue avec son propre launcher et son propre client 1.7.10 : modules HUD, chat vocal, cosmétiques et menus maison.

## ⚡ En bref

- Tu te connectes au launcher avec ton **compte du site** [mineria.fr](https://mineria.fr), puis tu cliques sur **JOUER**.
- Le launcher installe **Java** et les fichiers du jeu tout seul : rien à installer à la main.
- **Maj droite** ouvre le menu des modules (HUD, réglages, macros).
- Le **chat vocal** de proximité marche en **push-to-talk** avec la touche **V**.
- Sur PvP-Factions, le menu **Échap** a des raccourcis par lettre vers les quêtes, l'HDV, les homes…

***

## 📥 Installer et se connecter

1. Télécharge le launcher Mineria depuis [mineria.fr](https://mineria.fr). Il existe pour **Windows** (64 bits), **macOS** (Intel et Apple Silicon) et **Linux** (AppImage).
2. Ouvre-le et connecte-toi avec ton **pseudo** et ton **mot de passe** du site. Coche « Se souvenir de moi » pour ne plus les retaper.
3. Si ton compte a la double authentification, entre les **6 chiffres** de ton application.
4. Clique sur **JOUER**. Le launcher vérifie les fichiers, télécharge ce qui manque (Java compris), puis lance le jeu : « Mineria se lance ! ».

Tu n'as pas encore de compte ? Crée-le sur [mineria.fr/user/register](https://mineria.fr/user/register), puis **valide ton email** : le launcher refuse les comptes non vérifiés.

{% hint style="info" %}
Le launcher se met à jour tout seul. Ton pseudo en jeu est celui de ton compte du site : tu n'as rien à saisir dans le jeu.
{% endhint %}

### 🏠 L'écran d'accueil

- Ton **pseudo**, ton **grade**, ton **argent** et un aperçu 3D de ton **skin** et de ta cape.
- Le nombre de **joueurs en ligne** (ou « Hors ligne »), mis à jour chaque minute.
- Les **actualités** du serveur.
- Des raccourcis vers la **boutique**, le **Discord** et les **paramètres**, et le bouton de déconnexion.

### ⚙️ Les paramètres

| Réglage | Choix | Par défaut |
| --- | --- | --- |
| Résolution | 854×480 à 2560×1440 | 1280×720 |
| Plein écran | Oui / non | Non |
| Après le lancement du jeu | Fermer le launcher ou le garder ouvert | Fermer (15 s après le lancement) |
| Mémoire allouée | De 1 à 16 Go | 1 à 2 Go |
| Activer le ReplayMod | Oui / non | Non |

Le réglage de mémoire affiche la mémoire totale et disponible de ton PC. Les réglages s'enregistrent automatiquement.

### 🛠️ Si ça ne marche pas

| Message | Que faire |
| --- | --- |
| « Pseudo ou mot de passe invalide » | Vérifie tes identifiants, ou utilise « Mot de passe oublié ? ». |
| « Ton email n'est pas vérifié. Valide-le avant de te connecter. » | Clique sur le lien reçu par email, ou renvoie-le depuis l'écran de connexion. |
| « Code invalide » | Entre le code actuel de ton application de double authentification. |
| « Ton compte est banni » | Ton compte est sanctionné : voir [Règles](regles.md). |
| « Le serveur est en maintenance. » | Patiente : les annonces sont sur le [Discord](https://discord.mineria.fr). |
| « Impossible de se connecter au service. Réessaie plus tard. » | Vérifie ta connexion internet et réessaie. |

***

## ⌨️ Les touches du client

| Touche par défaut | Action |
| --- | --- |
| **Maj droite** | Ouvre le menu des modules |
| **V** | Parler au chat vocal (push-to-talk) |
| **V** | Freelook : tourner la caméra autour de toi (module Perspective 360) |
| **Alt gauche** | « Behind You » : regarder derrière toi (module Perspective 360) |
| **R** | Toggle Sprint |
| **Maj gauche** | Toggle Sneak |
| **F3 + G** | Affiche les limites des chunks |
| Aucune | Guide des recettes, Waypoints, Cosmétiques : assigne-leur une touche dans les réglages |

{% hint style="warning" %}
Par défaut, **V** sert à la fois au chat vocal et au Freelook. Si tu actives Perspective 360, change l'une des deux touches dans les réglages.
{% endhint %}

***

## 🧩 Les modules HUD

**Maj droite** ouvre le menu des modules. Tu peux y activer chaque module, le régler, le **réinitialiser**, et le **placer** où tu veux à l'écran (avec aimantation). Tes réglages sont rangés en **profils**, et un profil peut contenir des **macros** déclenchées par une touche ou un bouton de souris.

Les modules se masquent quand tu affiches la liste des joueurs (Tab) ou l'écran F3, pour ne pas les recouvrir. Le scoreboard reste affiché.

| Module | Ce qu'il fait |
| --- | --- |
| Armor Status | Affiche l'armure équipée et sa durabilité |
| Battery | Affiche le niveau de batterie de ton ordinateur |
| Block Overlay | Personnalise le contour et le remplissage du bloc visé |
| Boss Bar | Affiche la barre de vie des boss (actif par défaut) |
| Chunk Borders | Affiche les limites des chunks autour de toi |
| Combo Counter | Affiche ton combo de coups en cours |
| Compass | Boussole qui suit la direction de ton regard |
| Coordinates | Affiche tes coordonnées |
| CPS | Affiche tes clics par seconde |
| Crosshair | Personnalise le réticule |
| FPS | Affiche tes images par seconde |
| Glint Colorizer | Change la couleur de l'effet d'enchantement |
| Hit Colorizer | Change la couleur du flash des entités touchées |
| Hit Range | Affiche la portée autour du joueur visé |
| Item Physics | Anime les objets au sol avec une physique réaliste |
| Keystrokes | Affiche tes touches de déplacement et tes clics |
| Memory Usage | Affiche la mémoire utilisée par le jeu |
| Motion Blur | Flou de mouvement sur la caméra |
| Music | Affiche la musique en cours (Spotify, Deezer, YouTube…) |
| Nick Hider | Masque ton pseudo, uniquement sur ton écran |
| Pack Overlay | Affiche tes packs de textures actifs |
| Particles Multiplier | Règle la quantité de particules |
| Perspective 360 | Fait tourner la caméra librement autour de toi |
| Ping Display | Affiche ton ping |
| Play Time | Affiche ton temps de jeu depuis la connexion |
| Potion Counter | Compte les potions de ton inventaire |
| Potion HUD | Affiche tes effets actifs |
| Reach Display | Affiche la distance de ton dernier coup |
| Scoreboard | Personnalise l'affichage du scoreboard (toujours actif) |
| Speedometer | Affiche ta vitesse |
| Time Changer | Change l'heure du monde sur ton écran seulement |
| Time Display | Affiche l'heure réelle |
| TNT Timer | Compte à rebours au-dessus des TNT amorcées |
| Toggle Sneak | Reste accroupi d'une simple pression |
| Toggle Sprint | Garde le sprint d'une simple pression |
| Vote | Te prévient quand tu peux voter (actif par défaut) |
| Voice Chat | État de ton micro et joueurs qui parlent (toujours actif) |

***

## 🎙️ Le chat vocal

- Tu parles en **maintenant V** (push-to-talk).
- Tu entends les joueurs **proches** : jusqu'à environ **30 blocs**, le son baisse avec la distance. Il faut être sur le même serveur et dans le même monde.
- La réduction de bruit et le réglage automatique du volume sont toujours actifs.
- Une icône apparaît au-dessus du joueur qui parle.

Les réglages sont dans le module **Voice Chat** (Maj droite) :

| Réglage | Valeur |
| --- | --- |
| Push To Talk | Touche pour parler (V) |
| Mic Volume | Volume de ton micro, de 0 à 200 (100 par défaut) |
| Speaker Volume | Volume des autres joueurs, de 0 à 200 (100 par défaut) |
| Microphone · Speaker | Choix du micro et de la sortie audio |
| Test Microphone | Jauge pour tester ton micro |

Sur macOS, autorise l'accès au micro quand le système te le demande.

***

## ✨ Les cosmétiques

`/cosmetics` (ou la touche « Gérer vos cosmetics ») ouvre tes cosmétiques. Tu peux **équiper** ou **déséquiper** ceux que tu possèdes. Un cosmétique verrouillé affiche « Acheter » et t'envoie sur la [boutique](https://mineria.fr/shop).

La barre « Rechercher un cosmétique... » filtre par nom, sans tenir compte des majuscules ni des accents. Survole un cosmétique pour voir sa catégorie et si tu le possèdes.

| Catégorie | Cosmétiques |
| --- | --- |
| **Chapeaux** | Masque de Baudouin IV, Bouffon, Bourreau, Casquette, Carton, Château, Cône, Couronne du Roi, Masque Mortuaire, Couronne du Diable, Chapeau de Paille, Fleurs, Halo, Cornes, Casque de Chevalier, Casque de Guerrier, Chapeau Moyai, Couronne de la Reine, Intello, Tête d'Épée, Téléviseur |
| **Ailes** | Azur, Cramoisi, Braise, Ver des Glaces, Saphir, Séraphin, Murmure Céleste, Ardoise |

Les options « Show Cosmetics » et « Show Capes » (activées par défaut) affichent ou masquent les cosmétiques et les capes sur ton écran. Les cosmétiques d'un joueur invisible ne s'affichent pas.

***

## ⎋ Le menu Échap

Le menu Échap propose **Retour au jeu**, **Options**, **Modules**, **Retour au hub** (sauf sur les hubs) et **Quitter le jeu**.

Sur **PvP-Factions**, il affiche aussi des tuiles avec ton argent, ton power, tes compteurs (quêtes, HDV, réserve) et le prochain événement. Chaque tuile a sa **lettre** : appuie dessus pour y aller directement.

| Touche | Ouvre | Commande |
| --- | --- | --- |
| Q | Quêtes | `/quest` |
| C | Compétences | `/competences` |
| V | Hôtel des ventes | `/hdv` |
| H | Mes homes | `/homes` |
| X | Spawn | `/spawn` |
| W | Warps | `/warps` |
| S | Shop (verrouillé sans la compétence « Accès marché ») | `/warp shop` |
| E | Réserve | `/reserve` |
| R | Progression | `/rankup` |
| L | Classements | `/classement` |
| P | Planning des événements | `/planning` |
| F | Home de faction (si tu as une faction) | `/f home` |
| G | Quêtes de faction (si tu as une faction) | `/f quest` |

***

## 📍 Les waypoints

Assigne une touche à « Gérer vos waypoints » pour ouvrir l'écran **Waypoints**. **Ajouter** crée un point avec un nom, des coordonnées (ta position par défaut) et une couleur ; **Suppr.** en retire. Tes waypoints sont enregistrés sur ton PC, séparément pour chaque serveur et chaque dimension. Le serveur peut aussi t'afficher des points temporaires, par exemple pour un événement.

En jeu, un waypoint apparaît comme une pastille de sa couleur entourée d'un halo, avec son nom et sa distance (par exemple « Base · 120 m »).

***

## 🎛️ Autres options

| Option | Par défaut | Effet |
| --- | --- | --- |
| Nametag Health Bar | Oui | Barre de vie sous le pseudo des joueurs |
| Transparent Nametags | Non | Pseudos semi-transparents |
| Show name in F5 | Non | Voir ton propre pseudo en vue F5 |
| Menu Animation | Non | Animation à l'ouverture des menus |
| Discord Rich Presence | Oui | Affiche Mineria dans ton statut Discord |
| Join messages | Chat | Où s'affichent les connexions (Chat, Overlay ou rien) |
| Stream mode | Non | Masque tes coordonnées affichées à l'écran |
| Left-handed mode | Non | Tenir les objets de la main gauche |
| Full Bright | Non | Luminosité maximale |
| Emoji style | Google | Style des emojis du chat (Google, Apple, Twitter, Facebook) |

Le sélecteur d'emojis et les onglets du chat sont expliqués dans [Chat](chat.md).

{% hint style="info" %}
Le **ReplayMod** (activable dans les paramètres du launcher) sert à enregistrer tes parties et à les rejouer pour faire des vidéos.
{% endhint %}

## ⌨️ Commandes

| Commande | Effet | Accès |
| --- | --- | --- |
| `/cosmetics` (`/cosmetic`) | Ouvre tes cosmétiques | Tous |
| `/vote` | Affiche si tu peux voter, ton nombre de votes du mois et le lien [mineria.fr/vote](https://mineria.fr/vote) | Tous |
