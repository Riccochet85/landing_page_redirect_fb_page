
# Instructions for Uploading index.html to GitHub and Deploying on Cloudflare Pages

## English

### Step 1: Create a GitHub Repository
1. Go to [GitHub](https://github.com/) and sign in to your account.
2. Click on the "+" icon in the top right corner and select "New repository".
3. Name your repository (e.g., `elrefugiodemarita`).
4. Set the repository to "Public" or "Private" as per your preference.
5. Click "Create repository".

### Step 2: Upload index.html
1. In your new repository, click on "Add file" and select "Upload files".
2. Drag and drop the `index.html` file into the upload area.
3. Scroll down and click "Commit changes".

### Step 3: Connect to Cloudflare Pages
1. Go to [Cloudflare Pages](https://pages.cloudflare.com/).
2. Click "Create a Project".
3. Connect your GitHub account and select the repository you just created.
4. For "Framework preset", choose "None".
5. Set the "Build command" to `null` (leave it empty).
6. Set the "Output directory" to `.` (a single dot, meaning root).
7. Click "Deploy Site".

### Step 4: Connect Your Domain
1. After deployment, go to your Cloudflare dashboard.
2. Select your domain `elrefugiodemarita.org`.
3. Under "Pages", link your deployed project to the domain.
4. Set it as the root domain or a subpath (like `/inicio`), depending on your preference.

---

## Français

### Étape 1 : Créer un dépôt GitHub
1. Allez sur [GitHub](https://github.com/) et connectez-vous à votre compte.
2. Cliquez sur l'icône "+" dans le coin supérieur droit et sélectionnez "Nouveau dépôt".
3. Nommez votre dépôt (par exemple, `elrefugiodemarita`).
4. Définissez le dépôt sur "Public" ou "Privé" selon votre préférence.
5. Cliquez sur "Créer un dépôt".

### Étape 2 : Télécharger index.html
1. Dans votre nouveau dépôt, cliquez sur "Ajouter un fichier" et sélectionnez "Télécharger des fichiers".
2. Faites glisser et déposez le fichier `index.html` dans la zone de téléchargement.
3. Faites défiler vers le bas et cliquez sur "Valider les modifications".

### Étape 3 : Connecter à Cloudflare Pages
1. Allez sur [Cloudflare Pages](https://pages.cloudflare.com/).
2. Cliquez sur "Créer un projet".
3. Connectez votre compte GitHub et sélectionnez le dépôt que vous venez de créer.
4. Pour "Framework preset", choisissez "None".
5. Définissez la "Commande de build" sur `null` (laissez vide).
6. Définissez le "Répertoire de sortie" sur `.` (un seul point, signifiant la racine).
7. Cliquez sur "Déployer le site".

### Étape 4 : Connecter votre domaine
1. Après le déploiement, allez sur votre tableau de bord Cloudflare.
2. Sélectionnez votre domaine `elrefugiodemarita.org`.
3. Sous "Pages", liez votre projet déployé au domaine.
4. Définissez-le comme domaine racine ou sous-chemin (comme `/inicio`), selon votre préférence.
