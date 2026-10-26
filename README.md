# Tout Doux

Ma routine du matin, tout en douceur : des tâches à cocher, Mochi le chat, une carte bonus chaque jour, des séries, des jokers et des cadeaux à débloquer.

## Contenu du dossier

| Fichier | Rôle |
|---|---|
| `index.html` | L'appli complète (page, style et code) |
| `manifest.webmanifest` | Nom, couleurs et icônes pour l'installer sur l'écran d'accueil |
| `sw.js` | Mode hors ligne : l'appli s'ouvre même sans connexion |
| `icons/` | Icônes de l'appli |
| `.nojekyll` | Dit à GitHub Pages de publier les fichiers tels quels |

## Mettre l'appli en ligne avec GitHub Pages

1. Sur github.com, crée un nouveau dépôt, par exemple `tout-doux`.
2. Dans le dépôt, clique sur **Add file → Upload files** et glisse **tout le contenu** du dossier (pas le dossier lui-même) : `index.html`, `manifest.webmanifest`, `sw.js`, `.nojekyll`, `README.md` et le dossier `icons`. Valide avec **Commit changes**.
   Le fichier `.nojekyll` est masqué sur Mac. Dans le Finder, `Cmd + Maj + .` affiche les fichiers masqués.
3. Va dans **Settings → Pages**. Sous **Build and deployment**, choisis **Deploy from a branch**, puis la branche `main` et le dossier `/ (root)`. Clique sur **Save**.
4. Après une à deux minutes, l'adresse apparaît en haut de la page **Pages**, du type `https://ton-pseudo.github.io/tout-doux/`.

Avec un compte GitHub gratuit, GitHub Pages fonctionne seulement avec un dépôt public. Le code est alors visible, mais tes données ne le sont jamais : elles restent dans le navigateur de ton téléphone.

## L'installer sur ton téléphone

- **iPhone (Safari)** : ouvre l'adresse, touche le bouton Partager, puis **Sur l'écran d'accueil**.
- **Android (Chrome)** : ouvre l'adresse, menu ⋮, puis **Installer l'application** ou **Ajouter à l'écran d'accueil**.

Tout Doux s'ouvre alors comme une vraie appli, en plein écran, même hors ligne.

## Tes données

- Tout est enregistré dans le navigateur de l'appareil. Rien n'est envoyé sur internet.
- Chaque appareil a ses propres données. Pour passer d'un appareil à l'autre, utilise **Exporter une copie**, puis **Importer une copie** sur l'autre appareil (section « Mes données », en bas de l'appli).
- Effacer les données du navigateur ou désinstaller l'appli efface aussi ta progression. Exporte une copie de temps en temps.

## Mettre à jour l'appli

1. Remplace `index.html` (ou les autres fichiers) dans le dépôt GitHub.
2. Dans `sw.js`, augmente le numéro de version : `tout-doux-v1` devient `tout-doux-v2`.
3. Ferme puis rouvre l'appli sur ton téléphone, deux fois si besoin. Tes données ne sont pas touchées.
