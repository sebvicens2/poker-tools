# Range Trainer — MTT 9-max

Petit outil pour construire ses ranges d'open (et limp/raise en SB) en tournoi
MTT 9-max, puis s'entraîner à les reconnaître.

- **Builder** : peins la grille 13×13 (fold / limp / raise) pour chaque
  position (UTG → BTN, SB) et chaque palier de stack (10 à 100 bb). Copie
  une range existante vers une autre case, exporte/importe en JSON.
- **Trainer** : choisis un sous-ensemble de positions/stacks, puis un quiz
  tire une main pondérée par son nombre de combos réel et te demande de
  choisir la bonne action.

Les ranges sont sauvegardées dans le `localStorage` du navigateur — pense à
exporter en JSON régulièrement pour ne rien perdre.

## Usage

En ligne : https://sebvicens2.github.io/poker-tools/

En local : ouvre `range-trainer.html` directement dans un navigateur, aucune
installation nécessaire. Le téléchargement JSON automatique (bouton
"Exporter JSON") ne fonctionne que hors de l'aperçu artifact de claude.ai —
en local ou via la page GitHub Pages ci-dessus, sur celle-ci.
