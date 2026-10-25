# 💬 Chat

> Discuter, répondre en privé, ignorer, signaler : tout ce qu'il faut savoir sur le chat de Mineria.

## ⚡ En bref

* Le chat est organisé en **onglets** (canaux).
* `/msg` pour les messages privés, `/ignore` pour ne plus voir quelqu'un.
* Sous les messages, des boutons cliquables te permettent de signaler (⚠) ou d'ignorer (🔕).
* Un bouton 😀 ouvre le sélecteur d'emojis.

***

## 🗂️ Les canaux en onglets

| Onglet | Contenu |
| --- | --- |
| **Général** | Le chat public et les messages système. |
| **Faction** | Le chat de ta faction. |
| **Allié** | Le chat avec tes alliés. |
| **Trêve** | Le chat avec les factions en trêve. |

Les onglets Faction, Allié et Trêve apparaissent seulement quand la relation est **mutuelle**. Les commandes de chat de faction (`/ff`, `/fa`, `/ft`, `/fp`) restent utilisables.

Les canaux sont strictement séparés : un message de faction n'apparaît jamais dans le Général. Une pastille indique les messages non lus (jusqu'à « 99+ »). Les messages répétés sont regroupés avec un compteur `(xN)`.

{% hint style="info" %}
Une commande tapée dans un autre onglet que **Général** est bloquée : reviens sur Général pour la lancer.
{% endhint %}

À ta connexion, le chat des dernières 24 h est rechargé.

***

## ✉️ Messages privés

* `/msg <joueur> <message>` envoie un message privé.
* `/r <message>` répond à la dernière personne qui t'a écrit.

***

## 🔕 Ignorer quelqu'un

`/ignore <joueur>` bloque ses MP **et** masque son chat public. `/unignore <joueur>` annule.

{% hint style="warning" %}
Tu ne peux pas ignorer un membre du staff (« Tu ne peux pas ignorer un membre du staff. »).
{% endhint %}

***

## 🖱️ Les boutons du chat

Sous les messages des autres joueurs, deux boutons cliquables :

| Bouton | Effet |
| --- | --- |
| ⚠ | Prépare `/report <joueur>` pour le signaler. Voir [Règles](regles.md). |
| 🔕 | Prépare `/ignore <joueur>`. |

Sur un message privé, un ⚠ en début de ligne permet de déposer une plainte pour ce message.

***

## 😀 Emojis

Le bouton 😀 de la barre de saisie ouvre le **sélecteur d'emojis**. Tu peux chercher en français ou en anglais, et tes emojis récents sont gardés.

***

## 🧹 Filtre d'insultes

Les messages contenant des insultes sont **masqués** : dans le chat public, les MP et les chats de faction, d'alliance et de trêve. Tu es prévenu quand ton message est bloqué, et le staff peut le consulter.

***

## 📢 Annonces automatiques

Des annonces passent régulièrement dans le chat. Par défaut, elles te rappellent de **voter**, de rejoindre le **Discord** et de visiter la **boutique**. Elles peuvent varier d'un serveur à l'autre.

***

## 👋 Bienvenue

Quand un nouveau joueur arrive pour la première fois sur un serveur, le chat annonce « Bienvenue à <pseudo> ! ». Sur Faction, tu peux aussi lui souhaiter la bienvenue avec `/bienvenue`.

***

## 📋 Liste des joueurs (tab)

La touche Tab affiche les joueurs connectés, triés par grade, avec le préfixe de chacun. Voir [Grades](grades.md).

## ⌨️ Commandes

| Commande | Effet | Grade |
| --- | --- | --- |
| `/msg <joueur> <message>` | Message privé (`/m`, `/w`, `/tell`). | Tous |
| `/r <message>` | Répond au dernier MP. | Tous |
| `/ignore <joueur>` | Ignore un joueur. | Tous |
| `/unignore <joueur>` | Arrête d'ignorer. | Tous |
| `/report <joueur>` | Signale un joueur. | Tous |
| `/ff`, `/fa`, `/ft`, `/fp` | Chats de faction, alliance, trêve. Voir [Factions](../pvp-faction/factions.md). | Faction |
