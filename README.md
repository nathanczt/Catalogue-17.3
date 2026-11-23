# Catalogue-17.3

Catalogue de matériaux et fournitures (travaux publics) : articles, fournisseurs, panier, historique des commandes et lecture automatique des devis.

## Ouvrir le catalogue

Le catalogue en ligne, avec toutes ses données, est ici :

**https://claude.ai/artifact/6xqfrACwcVtFjM8ASrS5G6**

Il s'ouvre sur n'importe quel ordinateur ou téléphone : il suffit d'être connecté au même compte Claude. Les articles, fournisseurs, commandes, devis et fiches techniques sont enregistrés en ligne avec le catalogue, pas dans ce dépôt.

Pour le donner à quelqu'un d'autre, utilisez le menu **Partager** du catalogue sur claude.ai.

## Contenu du dépôt

- `catalogue.html` : code source de la page (sauvegarde). Ouvert seul dans un navigateur, il affiche l'interface sans les données ; les données et les fonctions en ligne (enregistrement, fichiers, lecture des devis) ne marchent que dans la version publiée sur claude.ai.

## Fonctions

- Familles : Assainissement (ASS), Réseaux secs (RSE), Matériaux de remblais (REM), Maçonnerie (MAC), et ajout de nouvelles familles depuis les filtres. Références générées automatiquement (ASS-001…). Filtres par famille et par chantier.
- Fiche article : désignation commerciale et désignation perso, chantier, code GED, unité, prix HT, quantité marché, conditionnement et quantité par conditionnement, fournisseur et fabricant (liste ou saisie libre), fiche technique et devis/contrats en pièces jointes (glisser-déposer).
- Lecture automatique des devis (prix HT uniquement) et import d'un devis complet pour créer ou mettre à jour les articles, avec alerte rouge si le prix change.
- Un même fichier n'est stocké qu'une fois ; bouton « Fusionner les doublons » pour nettoyer.
- Panier personnel arrondi au conditionnement (barres, pièces), validation, export CSV.
- Historique des commandes, par commande et par article, avec quantité restante sur le marché.
- Recherche tolérante (pluriels, accents, fautes de frappe).
