# LASMAR – Site web du laboratoire

Site officiel du **Laboratoire de Spectrométrie des Matériaux et Archéomatériaux (LASMAR)**,
Unité de Recherche Labellisée CNRST (URL-CNRST N°7), Département de Physique,
Faculté des Sciences, Université Moulay Ismaïl, Meknès.

Site trilingue (français, anglais, arabe), modes clair et sombre, adapté au téléphone.

Conçu et réalisé par **Omar Taoussi**.

## Structure

```
lasmar-site/
├── index.html   ← tout le site (HTML + CSS + JavaScript)
├── photos/      ← images de la galerie
└── README.md
```

## Modifier le contenu

Ouvrez `index.html` dans un éditeur de texte (VS Code, Notepad++…) et cherchez le bloc :

```
CONTENU DU SITE — chaque texte existe en 3 langues
```

Chaque texte s'écrit sous la forme `{fr:"…", en:"…", ar:"…"}`.

| Pour modifier… | Cherchez la liste |
|---|---|
| Informations générales | `INFO` |
| Équipes | `TEAMS` |
| Axes de recherche | `AXES` |
| Membres (professeurs, doctorants, alumni) | `MEMBERS` |
| Collaborateurs et institutions | `COLLABS`, `PARTNERS` |
| Publications | `PUBS` |
| Conférences | `CONFS` |
| Actualités | `NEWS` |
| Projets | `PROJECTS` |
| Équipements | `EQUIP` |
| Galerie | `GALLERY` |

Pour ajouter une photo : placez le fichier dans `photos/` puis écrivez
`src:"photos/nom-du-fichier.jpg"` dans la liste `GALLERY`.

## Publier avec GitHub Pages

1. **Settings → Pages**
2. **Source** : *Deploy from a branch* — **Branch** : `main` / `(root)` → **Save**
3. Le site est en ligne après 1 à 2 minutes à l'adresse
   `https://<votre-compte>.github.io/lasmar-site/`

Chaque modification envoyée sur la branche `main` met le site à jour automatiquement.

### Nom de domaine personnalisé (facultatif)

Dans **Settings → Pages → Custom domain**, saisissez le domaine (ex. `lasmar.umi.ac.ma`),
puis configurez le DNS comme indiqué par GitHub.
