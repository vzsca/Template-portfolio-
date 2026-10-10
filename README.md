# Template de portfolio

Un portfolio personnel responsive construit avec **Jekyll** et **GitHub Pages**. Le thème sombre inspiré d'un terminal est sobre, sans dépendance JavaScript externe ni police distante.

## Démarrage rapide

1. Cliquez sur **Use this template** sur GitHub pour créer votre propre dépôt à partir de ce modèle.
2. Dans `_config.yml`, remplacez `VOTRE-PSEUDO` et `Template-portfolio-` par votre identifiant GitHub et le nom exact du dépôt.
3. Personnalisez `title`, `description`, `email` et `linkedin`.
4. Modifiez `index.html` : nom, titre, introduction, profil et liens de contact.
5. Remplacez ou supprimez le projet d'exemple dans `_projets/`.
6. Dans GitHub, ouvrez **Settings → Pages** et activez la publication depuis la branche `main`.
7. Attendez la fin du déploiement et vérifiez le site sur ordinateur et téléphone.

Pour un dépôt nommé `mon-portfolio`, le `baseurl` doit être `/mon-portfolio`. Pour un site utilisateur `VOTRE-PSEUDO.github.io`, le `baseurl` est généralement vide.

## Ajouter un projet

1. Copiez `_projets/_A-COPIER.md` vers un nouveau fichier, par exemple `2026-01-mon-projet.md`.
2. Complétez les métadonnées en haut du fichier : `title`, `date`, `cadre`, `type`, `resume` et `competences`.
3. Choisissez `type: "ecole"` pour un projet scolaire ou `type: "perso"` pour un projet personnel.
4. Rédigez le contexte, les moyens utilisés, les étapes, les résultats et le bilan.
5. Placez les captures dans `images/` et décrivez-les avec un texte alternatif.
6. Utilisez les codes de compétences définis dans `_data/competences.yml`.

La page d'accueil classe automatiquement les projets et construit le tableau de compétences à partir des fiches Markdown.

## Structure

- `index.html` — page d'accueil, profil, projets, compétences et contact
- `_projets/` — fiches projets Markdown
- `_layouts/default.html` — navigation et pied de page communs
- `_layouts/projet.html` — modèle des fiches projets
- `_data/competences.yml` — référentiel de compétences personnalisable
- `css/style.css` — palette, composants et mise en page responsive
- `images/` — images et captures
- `mentions-legales.md` — exemple de mentions légales à adapter
- `_config.yml` — configuration Jekyll et coordonnées

## Personnalisation

La palette est définie au début de `css/style.css` dans `:root`, notamment avec `--bg`, `--panel`, `--text`, `--muted` et `--green`.

Adaptez les mentions légales à votre situation et à vos services réels. Le fichier fourni est un exemple, pas un conseil juridique.

## Licence

Le code du template est publié sous licence MIT. Les textes, images et ressources ajoutés par chaque utilisateur restent sous la responsabilité de leur auteur et peuvent avoir des licences différentes.
