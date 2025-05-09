# Mon Roman Graphique

Ce dépôt contient la base d'un roman graphique interactif rétro geek, prêt à être publié sur GitHub Pages.

## Structure

- `index.html` : page d’accueil
- `style.css` : design rétro (vert terminal, lilas néon)
- `chapitres/` : chapitres HTML
- `images/` : images classées par chapitre

## Déploiement

Active GitHub Pages dans les settings du dépôt, branche `main`, dossier racine `/`.

Enjoy!


🪄 Étape 1 – Créer un nouveau fichier HTML
Va dans le dossier chapitres/ et crée un fichier nommé par exemple :

📄 Contenu type de chapitre2.html

```html
<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <title>Chapitre 2</title>
  <link rel="stylesheet" href="../style.css">
</head>
<body>
  <h1>Chapitre 2 : La Faille</h1>
  <img src="../images/chapitre2/img1.jpg" alt="Illustration 1" width="80%">
  <p>Un frisson traverse l’échine du héros. Le néon clignote. Une silhouette s’approche dans la brume verte...</p>

  <a class="start-button" href="chapitre3.html">→ Chapitre suivant</a>
  <br>
  <a class="start-button" href="chapitre1.html">← Retour au chapitre 1</a>
</body>
</html>
```

🖼️ Étape 2 – Ajouter les images
Crée un dossier :

```bash
images/chapitre2/

```

Ajoute-y tes fichiers image (par exemple img1.jpg, img2.jpg…).

🔗 Étape 3 – Lier les chapitres entre eux
Assure-toi que :

chapitre1.html se termine par un lien vers chapitre2.html

chapitre2.html renvoie vers chapitre3.html ou retourne vers chapitre1.html
(tu peux aussi créer un menu de navigation si tu préfères une vue globale)

