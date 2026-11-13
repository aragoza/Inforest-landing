# InForêt — page de présentation

Page de présentation du projet InForêt, mon projet de portfolio de fin de
formation à [Holberton School](https://www.holbertonschool.com/).

Le site est statique : du HTML, du CSS et des images, sans aucune
dépendance ni étape de construction.

- **Page en ligne :** https://aragoza.github.io/inforet-landing/
- **Dépôt de l'application :** https://github.com/aragoza/Inforest

## Arborescence

```
.
├── index.html
├── README.md
└── assets/
    ├── style.css
    ├── cover.png                  image de couverture
    ├── feature-carte.png
    ├── feature-actualites.png
    ├── feature-decouverte.png
    ├── feature-mail.png
    └── fonts/
        ├── fraunces-latin-var.woff2
        └── inter-latin-var.woff2
```

Les deux polices sont hébergées ici plutôt que chargées depuis Google
Fonts, comme sur l'application : aucune requête vers un service tiers,
donc aucune adresse IP de visiteur transmise. Si les fichiers sont
absents, la page retombe proprement sur les polices du système.

## Consulter la page en local

Il suffit d'ouvrir `index.html` dans un navigateur. Pour servir le dossier
sur un port local :

```bash
python3 -m http.server 8000
```

## Déploiement

La page est publiée avec GitHub Pages, depuis la branche `main`.

1. Dans le dépôt, ouvrir **Settings** puis **Pages**.
2. Sous **Source**, choisir **Deploy from a branch**.
3. Choisir la branche `main` et le dossier `/ (root)`, puis **Save**.
4. L'adresse apparaît au bout d'une minute environ.

## À compléter

- [ ] L'histoire personnelle dans la section « À propos ».
- [ ] L'adresse de l'application déployée, dans les deux boutons
      « Ouvrir l'application ».
- [ ] Les liens LinkedIn et Twitter dans la section « L'équipe ».
