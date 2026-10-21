# Monopoly entre amis

Un seul fichier (`index.html`), pas de serveur. Les navigateurs se connectent directement entre eux (PeerJS / WebRTC).

## Mettre en ligne sur GitHub Pages

1. Crée un dépôt sur github.com (ex. `monopoly`) et dépose-y `index.html`.
2. Dans le dépôt : **Settings → Pages → Source : Deploy from a branch → `main` / `(root)` → Save**.
3. Après ~1 minute, le jeu est sur `https://<ton-pseudo>.github.io/monopoly/`.

## Jouer

1. L'hôte ouvre l'adresse ci-dessus : un lien d'invitation s'affiche.
2. Il l'envoie à ses amis ; chacun ouvre le lien, tape son prénom, clique « Ajouter ce joueur ».
3. L'hôte ajoute aussi son prénom puis clique « Lancer la partie » (2 à 8 joueurs).

Plusieurs joueurs peuvent être ajoutés sur le même appareil (on se passe l'écran).
Clique sur une case du plateau pour voir sa fiche (loyers) et, si elle t'appartient, construire, vendre ou hypothéquer.

- Si l'hôte recharge sa page, la partie reprend toute seule et les invités se reconnectent.
- Si un ami se déconnecte, l'hôte peut **passer son tour** ou l'**exclure**.
- « Terminer la partie » déclare gagnant le joueur le plus riche (pratique quand il est tard).
- « Nouvelle partie » efface la partie en cours.

## Règles incluses

Dés et doubles (3 doubles = prison), achat ou **enchères**, loyers (terrains, gares, compagnies, groupe complet ×2),
maisons et hôtels (construction équilibrée), revente de maisons, **hypothèques**, **échanges** entre joueurs
(propriétés + argent), prison (amende, double ou carte « libéré de prison »), taxes, 16 cartes Chance
et 16 cartes Caisse de communauté, **dettes** (on vend/hypothèque avant de faire faillite), faillite au profit
du créancier, discussion entre joueurs.

Non inclus : limite de 32 maisons / 12 hôtels de la banque, intérêts de 10 % sur les propriétés hypothéquées échangées.
