# TXT Rainbow Col

TXT Rainbow Col est une extension Visual Studio Code qui permet de colorer les colonnes de fichiers texte où les colonnes sont séparées par des points-virgules (`;`). Elle améliore la lisibilité en attribuant des couleurs différentes à chaque colonne.

## Fonctionnalités

- Coloration automatique des colonnes basées sur la séparation par `;`.
- Différentes couleurs pour chaque colonne, facilitant la lecture et l'analyse des fichiers texte structurés.
- Prise en charge des fichiers `.txt` avec des colonnes multiples, même si certaines colonnes sont vides.

## Installation et Lancement de l'Extension en Local

1. **Clonez le dépôt du projet sur votre machine locale :**
    ```bash
    git clone https://github.com/votre-repo/txt-rainbow-col.git
    ```

2. **Ouvrez le projet dans Visual Studio Code :**
    ```bash
    cd txt-rainbow-col
    code .
    ```

3. **Installez les dépendances nécessaires :**
    ```bash
    npm install
    ```

4. **Compilez le projet :**
    ```bash
    npm run compile
    ```

5. **Lancez l'extension en mode de développement :**
    - **Sur Windows/Linux** : Appuyez sur `F5` pour démarrer une nouvelle instance de Visual Studio Code avec l'extension activée.
    - **Sur macOS** : Utilisez `Fn + F5` si la touche F5 est mappée sur une fonction système.

   - Cela ouvrira une nouvelle fenêtre de Visual Studio Code avec votre extension activée.
   - Vous pouvez tester l'extension directement dans cette nouvelle instance de VS Code.

### Tester et Utiliser

1. **Ouvrir un fichier `.txt` contenant des colonnes séparées par des points-virgules (`;`) dans la nouvelle instance de VS Code.**
2. **L'extension appliquera automatiquement les couleurs à chaque colonne.**

### Raccourcis Clavier Importants

| Action                          | Windows/Linux | macOS        |
|---------------------------------|---------------|--------------|
| Ouvrir le panneau d'extensions  | `Ctrl + Shift + X` | `Cmd + Shift + X` |
| Lancer l'extension en debug     | `F5`          | `Fn + F5`    |
| Installer à partir de `.vsix`   | `Ctrl + Shift + X` puis `...` et **"Installer à partir de VSIX..."** | `Cmd + Shift + X` puis `...` et **"Installer à partir de VSIX..."** |

