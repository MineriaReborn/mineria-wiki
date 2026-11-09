# 🏰 Factions

> Fonde ta faction, protège ton territoire et fais-la grandir avec tes amis.

## ⚡ En bref

- Une faction regroupe jusqu'à **15 membres** (jusqu'à **20** en montant de niveau).
- Elle protège des **claims** : des chunks (16×16 blocs) que seuls ses membres peuvent modifier.
- Son **power** décide du nombre de claims qu'elle peut garder.
- En jouant, elle gagne de l'**XP** et monte jusqu'au **niveau 30**, en débloquant de nombreux avantages.

## 🚀 Créer ou rejoindre une faction

| Action | Commande |
|---|---|
| Créer une faction | `/f create <nom>` |
| Inviter un joueur | `/f invite <joueur>` |
| Rejoindre (sur invitation) | `/f join <faction>` |
| Quitter ta faction | `/f leave` |
| Voir la fiche d'une faction | `/f show [faction\|joueur]` |
| Voir la liste des factions | `/f list [page]` |

Le nom d'une faction fait **entre 3 et 10 caractères**.

{% hint style="warning" %}
Après avoir quitté une faction ou en avoir été exclu, tu dois attendre **24 h** avant d'en rejoindre une autre. Si tu tentes quand même, le jeu t'affiche le temps restant.
{% endhint %}

Une faction peut être **ouverte** (`/f open`, ou le réglage « Adhésion » de sa fiche) : n'importe qui peut alors la rejoindre sans invitation. Sinon, elle fonctionne **sur invitation**.

## 👑 Rôles et permissions

Il y a quatre rôles, du plus élevé au plus bas : **Leader**, **Modérateur**, **Membre** et **Recrue**.

| Rôle | Ce qu'il peut faire en plus |
|---|---|
| **Recrue** | Construire, ouvrir les coffres, utiliser portes, boutons et leviers, cultiver, déposer à la banque, utiliser `/f home` |
| **Membre** | Comme la Recrue, avec les droits que le Leader lui accorde |
| **Modérateur** | Inviter, exclure, claim et unclaim, gérer les relations, changer le nom et la description, retirer de la banque |
| **Leader** | Tout, y compris promouvoir et rétrograder, gérer les permissions, placer le home, signer les contrats de guerre |

Le Leader règle les droits de chaque rôle avec `/f perm`.

| Action | Commande |
|---|---|
| Promouvoir ou rétrograder | `/f promote <joueur>` · `/f demote <joueur>` |
| Fixer un rôle précis | `/f mod <joueur>` · `/f member <joueur>` |
| Exclure un joueur | `/f kick <joueur>` |
| Passer le rôle de Leader | `/f leader <joueur>` |
| Dissoudre la faction | `/f disband` |

## 🗺️ Territoire et claims

Un **claim** protège un chunk. Dans ton territoire :

- Personne d'autre que ta faction ne peut construire ni casser, même quand tes membres sont hors ligne.
- Le TNT ne fait pas de dégâts aux blocs quand tous les défenseurs sont hors ligne.
- Tu subis moins de dégâts avec certains niveaux de faction (voir plus bas).

| Action | Commande | Qui |
|---|---|---|
| Claim le chunk où tu es | `/f claim` | Modérateur ou Leader |
| Claim autour de toi | `/f claim <rayon>` (maximum 50) | Modérateur ou Leader |
| Claim en continu en marchant | `/f autoclaim` | Modérateur ou Leader |
| Libérer un chunk | `/f unclaim` | Modérateur ou Leader |
| Tout libérer | `/f unclaimall` | Modérateur ou Leader |
| Voir la carte des claims | `/f map` (`/fmap`) affiche ou masque le module « Carte de faction » | Tous |

**Nombre de claims maximum** : 30 au départ, jusqu'à **55** en montant de niveau.

Tu ne peux **pas** claim :

- Les zones protégées (SafeZone), la WarZone et les zones d'event.
- Un territoire allié.
- Un monde autre que le monde principal.
- Les environs de la météorite.

{% hint style="info" %}
Pour claim, il faut aussi que le nombre de claims reste **inférieur au power de ta faction** (arrondi). Si tu as du mal à claim, regarde ton power !
{% endhint %}

## ⚡ Le power

Le power mesure la solidité de ta faction.

| Règle | Valeur |
|---|---|
| Power d'un joueur | de 0 à **10** |
| Gain | **+0,2 par minute** en jeu (rien quand tu es hors ligne) |
| Perte à chaque mort | **−2** |
| Power de la faction | somme de ses membres, **plafonnée à 100** |

Tu consultes ton power avec `/f power [joueur]`.

Les morts en **SafeZone** ne coûtent pas de power. En WarZone et dans la nature, elles en coûtent. Une faction **pacifique** n'en perd pas.

{% hint style="warning" %}
Si une faction a **plus de claims que de power**, elle devient **pillable** : le message « Attention. Votre faction est maintenant pillable. » s'affiche, et une faction ennemie peut alors lui prendre des claims en les claim par-dessus. Voir [Guerre](guerre.md).
{% endhint %}

## 🤝 Relations entre factions

| Relation | Commande | Fonctionnement |
|---|---|---|
| **Alliance** | `/f ally <faction>` | Les deux factions doivent accepter : l'une envoie la demande, l'autre tape la même commande |
| **Trêve** | `/f truce <faction>` | Même principe que l'alliance |
| **Ennemi** | `/f enemy <faction>` | Se décide d'un seul côté |
| **Neutre** | `/f neutral <faction>` | Met fin à une alliance ou une trêve |

Les relations se gèrent à partir du rôle de **Modérateur**. Quand une alliance est conclue, le jeu annonce : « Votre faction est maintenant en alliance avec la faction X. »

- Tu ne peux pas attaquer un membre de ta faction ni un allié.
- Tes alliés ne peuvent pas construire sur ton territoire, et inversement.
- Les alliés se partagent un chat dédié.
- Une limite d'alliances peut s'appliquer : « Votre faction a atteint la limite d'alliance. »

## 💬 Chats de faction

| Commande | Effet |
|---|---|
| `/ff` | Chat de ta faction |
| `/fa` | Chat des alliés |
| `/ft` | Chat des trêves |
| `/fp` | Chat public |

## 🏠 Home de faction

Le home est le point de téléportation de ta faction.

- Il est posé automatiquement sur ton **premier claim**.
- Le Leader peut le déplacer avec `/f sethome`, dans ses claims, avec un délai entre deux changements : **24 h** au départ, **12 h** au niveau 10, **8 h** au niveau 20.
- Tous les membres l'utilisent avec `/f home`.
- Tu ne peux pas libérer le chunk qui contient le home : « Ce claim contient le home de votre faction. Déplacez-le avec /f sethome avant d'unclaim. »
- `/f antisethome` empêche l'ennemi de poser un home de pillage chez toi (voir niveaux).

{% hint style="info" %}
Dans un claim ennemi, certaines commandes sont bloquées : `/home`, `/sethome`, `/spawn`, `/tpa`, `/tpahere` et `/tpaccept`.
{% endhint %}

## 📈 Niveaux et XP de faction

Ta faction gagne de l'XP et monte de niveau jusqu'au **niveau 30**. Consulte-la avec `/f xp [joueur]` et la liste des avantages avec `/f avantages`.

### Comment gagner de l'XP

| Source | XP |
|---|---|
| Survivre une journée | 1 000 par jour |
| Temps de jeu | 100 par heure |
| Tuer un joueur ennemi | 200 par kill |
| Quêtes de faction | 500 / 1 000 / 2 000 par palier (voir [Quêtes](quetes.md)) |

Pour les kills : **5 kills récompensés par jour** et par joueur au maximum, uniquement en WarZone ou dans un claim ennemi, jamais contre un membre, un allié ou une trêve, et pas contre un joueur sans armure.

### Paliers

<details>
<summary>XP total nécessaire par niveau</summary>

| Niveau | XP | Niveau | XP | Niveau | XP |
|---|---|---|---|---|---|
| 1 | 0 | 11 | 42 500 | 21 | 135 000 |
| 2 | 2 000 | 12 | 49 500 | 22 | 147 000 |
| 3 | 4 500 | 13 | 57 000 | 23 | 159 500 |
| 4 | 7 500 | 14 | 65 000 | 24 | 172 500 |
| 5 | 11 000 | 15 | 73 500 | 25 | 186 000 |
| 6 | 15 000 | 16 | 82 500 | 26 | 190 000 |
| 7 | 19 500 | 17 | 92 000 | 27 | 194 000 |
| 8 | 24 500 | 18 | 102 000 | 28 | 197 000 |
| 9 | 30 000 | 19 | 112 500 | 29 | 200 000 |
| 10 | 36 000 | 20 | 123 500 | 30 | 250 000 |

</details>

### Avantages par niveau

| Avantage | Niveaux |
|---|---|
| Membres en plus | niveau 10 : +2 · niveau 21 : +2 · niveau 25 : +1 |
| Claims en plus | niveaux 2, 14, 18, 22 et 28 : +5 chacun |
| Coffre de faction (`/f chest`) | niveau 5 : 1 ligne · 11 : 2 · 15 : 3 · 20 : 4 · 24 : 5 · 26 : 6 |
| Warps de faction (`/f warp`) | niveau 12 : 1 · niveau 27 : 2 |
| Protection anti-home ennemi | niveau 3 : 1 · 9 : 4 · 17 : 9 |
| Dégâts réduits sur ton territoire | niveau 8 : −5 % · niveau 19 : −10 % |
| Taxe réduite | niveau 16 : −5 % · 23 : −10 % · 29 : −15 % |
| Cultures plus rapides | niveau 4 : +10 % · niveau 13 : +15 % |
| Délai de `/f sethome` réduit | niveau 10 : 12 h · niveau 20 : 8 h |
| Home de pillage (`/f home pillage`) | à partir du niveau 7 |
| Spawners aléatoires (`/f spawners`) | niveau 30 : 3 spawners |

## 💰 Banque et taxe

La banque de faction se gère avec `/f bank [deposit|withdraw] <montant>` : les Recrues peuvent déposer, les Modérateurs peuvent retirer.

Chaque jour, la faction paie une **taxe** :

- **50 $** par claim
- **100 $** par membre
- **5 $** par bloc d'obsidienne

Les niveaux 16, 23 et 29 la réduisent. Si la taxe n'est pas payée, la faction perd **3 claims au hasard** par jour. Garde donc ta banque approvisionnée !

## 📇 La fiche de faction

La **fiche** est l'écran qui résume une faction. Elle remplace l'ancien affichage dans le chat.

### Comment l'ouvrir

- Avec `/f show` : sans nom, tu ouvres la fiche de **ta** faction.
- Avec `/f show <faction>` ou `/f show <pseudo>` : tu cherches par **nom de faction** ou par **pseudo d'un de ses membres**.
- En cliquant sur le **tag d'une faction** dans le chat.
- Depuis l'écran des [Classements](classements.md) (bouton « Fiche complète »).
- En cliquant sur une **puce de relation** (allié, trêve, ennemi) dans une autre fiche.

### Ce que tu y vois

| Information | Détail |
|---|---|
| Identité | Blason, nom, niveau, place au classement des factions, date de fondation |
| Statut | Adhésion **ouverte** ou **sur invitation**, faction **pacifique**, contrat de guerre en cours |
| Chef et membres en ligne | Le Leader et le nombre de membres connectés |
| Description | Le texte choisi par la faction |
| Chiffres clés | Membres, claims, power (avec l'étiquette **Protégée** ou **Raidable**) et banque |
| Taxe ou activité | La **taxe quotidienne** pour ta propre faction, l'**activité** (active ou inactive) pour les autres |
| Expérience | XP, progression vers le niveau suivant, avantages débloqués et prochain avantage |
| Membres | Liste des membres avec leur rôle et leur titre |
| Relations | Alliés, trêves et ennemis, cliquables |
| Meilleurs membres | Le meilleur membre de la faction dans les classements Seigneur & Roi, Chasseurs, Mineurs, Marchands et Richesse |
| Contrat de guerre | Adversaire, temps restant, contrat actif ou en pause (voir [Guerre et pillage](guerre.md)) |

Passe la souris sur les icônes d'aide pour avoir le détail d'un chiffre.

{% hint style="info" %}
**Confidentialité** : le power, la contribution et la dernière connexion de chaque membre ne sont visibles que par la faction elle-même et ses **alliés**. La **taxe** n'est visible que par la faction. Le contrat de guerre n'est visible que par les deux factions concernées.
{% endhint %}

### Les actions de ta faction

Sur la fiche de **ta** faction, des boutons te permettent d'agir directement, **selon tes permissions de faction** (réglées par le Leader avec `/f perm`) :

| Action | Ce que ça fait | Par défaut |
|---|---|---|
| Modifier le blason | Ouvre l'atelier du blason (`/f blason`) | Leader |
| Rejoindre le home | Te téléporte au home de la faction, après le délai de téléportation habituel | Tous les membres |
| Adhésion | Passe la faction d'**ouverte** à **sur invitation**, et inversement | Leader |
| Modifier la description | Change le texte de la fiche | Modérateur et Leader |

Un bouton grisé veut dire que ton rôle ne permet pas l'action. Un court délai s'applique entre deux changements d'adhésion.

### La description

La description fait **120 caractères maximum**. Les **liens** et les **codes couleur** sont refusés (le caractère `&` n'est pas accepté). Tu peux la changer depuis la fiche ou avec `/f desc <texte>`.

## ⌨️ Commandes

| Commande | Effet | Qui peut l'utiliser |
|---|---|---|
| `/f` | Affiche l'aide | Tous |
| `/f create <nom>` | Crée une faction | Tous, sans faction |
| `/f invite <joueur>` (`inv`) · `/f deinvite <joueur>` | Invite ou retire une invitation | Modérateur et plus |
| `/f join <faction>` (`accept`) | Rejoint une faction | Tous, sans faction |
| `/f leave` | Quitte la faction | Membres |
| `/f kick <joueur>` | Exclut un joueur | Modérateur et plus |
| `/f leader <joueur>` | Transfère le rôle de Leader | Leader |
| `/f promote` · `/f demote` · `/f mod` · `/f member` | Change le rôle d'un joueur | Leader |
| `/f title` | Donne un titre à un joueur | Modérateur et plus |
| `/f open` (`close`) | Ouvre la faction à tous ou la passe sur invitation | Leader |
| `/f description <texte>` (`desc`) | Change la description (120 caractères maximum, sans lien ni code couleur) | Modérateur et plus |
| `/f blason` | Ouvre l'atelier du blason de ta faction | Selon les permissions de faction (Leader par défaut) |
| `/f tag <nom>` (`rename`) | Renomme la faction | Modérateur et plus |
| `/f show [faction\|joueur]` (`who`) | Ouvre la fiche d'une faction, trouvée par son nom ou par le pseudo d'un membre | Tous |
| `/f list [page]` | Liste des factions | Tous |
| `/f map` (`/fmap`) | Affiche ou masque la carte des claims à l'écran | Tous |
| `/f claim [rayon]` · `/f autoclaim` · `/f unclaim` · `/f unclaimall` | Gère les claims | Modérateur et plus |
| `/f disband` | Dissout la faction | Leader |
| `/f perm` | Règle les permissions par rôle | Leader |
| `/f home` | Se téléporte au home | Tous les membres |
| `/f sethome` | Déplace le home | Leader |
| `/f home pillage` · `/f sethome pillage` | Home de pillage en claim ennemi | Niveau 7 minimum |
| `/f antisethome` | Protège ton territoire des homes de pillage | Selon le niveau |
| `/f warp [set\|del\|list\|<nom>]` | Warps de faction | Selon le niveau |
| `/f chest` | Coffre de faction | Membres, selon le niveau |
| `/f bank [deposit\|withdraw] <montant>` | Banque de faction | Dépôt : tous · retrait : Modérateur et plus |
| `/f power [joueur]` · `/f xp [joueur]` · `/f avantages` | Infos de power, d'XP et d'avantages | Tous |
| `/f spawners` | Spawners de faction | Niveau 30 |
| `/f ally` · `/f truce` · `/f enemy` · `/f neutral` | Relations | Modérateur et plus |
| `/f contrat` | Contrat de guerre (voir [Guerre](guerre.md)) | Leader |
| `/f quest` | Quêtes de faction (voir [Quêtes](quetes.md)) | Membres |
| `/ff` · `/fa` · `/ft` · `/fp` | Chats de faction, alliés, trêves, public | Tous |

Pour les classements, voir [Classements](classements.md). Pour grandir en tant que joueur, voir [Progression](progression.md).
