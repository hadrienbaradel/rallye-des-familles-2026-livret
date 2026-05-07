# Livret HTML

Le livret imprimable est généré par `scripts/generate_livret_html.py`.
L'édition actuelle produit un journal sportif A4 de `24 pages` autour du vol de la `Bannière des Champions du Massachusetts` au `TD Garden`.

## Régénérer

Depuis la racine du projet :

```bash
python3 scripts/generate_livret_html.py
```

Le fichier produit est :

```text
livret/index.html
```

## Asset principal

La Une utilise :

```text
livret/assets/td-garden-banniere-volee.png
```

Cette image représente la vitrine du Garden après la disparition de la bannière.

## Export PDF

1. Ouvrir `livret/index.html` dans Chrome ou Safari.
2. Attendre le chargement des polices et de l'image de Une.
3. Imprimer puis enregistrer en PDF.
4. Choisir `A4` si disponible.
5. Activer les arrière-plans graphiques.
6. Garder l'échelle à `100%`.
7. Désactiver les en-têtes et pieds de page du navigateur.

## Direction éditoriale

- Style : journal sportif sérieux, dense, lisible, inspiré de la presse sportive française.
- Objet central : vol de la Bannière des Champions du Massachusetts au TD Garden.
- Ton : fiction journalistique et enquête de presse, avec une direction éditoriale entièrement interne au journal.
- Ouverture : la Une, puis l'enquête et le profil du suspect avant les grandes pages sport.
- Basket : double page Spurs-Celtics avec terrain illustré et cercles numérotés.
- Volley : double page William Morgan / mintonette, sans dévoiler le lieu dans le contenu public.
- Matchs mythiques : trois pages de récits sportifs sur des affiches marquantes jouées dans le Massachusetts.
- Culture : page Tanglewood sur l'histoire du festival et du Boston Symphony Orchestra dans les Berkshires.
