# Installer l'Assistant 4/4/48 sur ton téléphone

Même principe que pour ton app Coach Basket : on héberge sur GitHub Pages, puis on l'ajoute à l'écran d'accueil.

## 1. Mettre en ligne (5 minutes)

1. Va sur github.com → **New repository** → nomme-le par exemple `assistant-448` → Create.
2. Clique **uploading an existing file** et glisse les 5 fichiers :
   `index.html`, `manifest.webmanifest`, `sw.js`, `icon-192.png`, `icon-512.png`
3. **Commit changes**.
4. Dans le repo : **Settings → Pages → Branch : main → Save**.
5. Après 1-2 minutes, ton app est en ligne à l'adresse :
   `https://TON-PSEUDO.github.io/assistant-448/`

## 2. Installer sur le téléphone

- **Android (Chrome)** : ouvre l'adresse → menu ⋮ → **Ajouter à l'écran d'accueil** (ou "Installer l'application").
- **iPhone (Safari)** : ouvre l'adresse → bouton Partager → **Sur l'écran d'accueil**.

L'app s'ouvre alors en plein écran, avec son icône 4/4/48, comme une vraie application.

## 3. La clé API (une seule fois)

Hébergée hors de Claude, l'app a besoin d'une clé API Anthropic pour faire tourner l'assistant :

1. Va sur **console.anthropic.com** → API Keys → Create Key.
2. Dans l'app, touche l'engrenage ⚙ en haut à droite → colle la clé → Enregistrer.

La clé reste stockée **uniquement dans ton téléphone** (jamais dans le code sur GitHub, jamais visible par les visiteurs). Chaque utilisation consomme du crédit API — quelques centimes par mail généré, la recherche web coûte un peu plus.

⚠️ Si tu rends le repo public, aucun souci : la clé n'y figure pas. Ne la partage juste avec personne.

## Mise à jour

Pour modifier l'app plus tard : demande-moi la nouvelle version du fichier `index.html`, remplace-le dans le repo, et c'est tout.
