# Registre des araignées

> **Version bêta (1.0.0-beta.1), en cours d'essai.** Utilisez d'abord des données fictives et exportez souvent une sauvegarde.

Outil gratuit pour tenir le registre de spécimens d'araignées conservés en alcool et imprimer leurs étiquettes de récolte et d'identification, sur le modèle présenté par Paquin et Dupérré (2026, fig. 27-28). 

**Ouvrir l'outil :** https://marclajoie123.github.io/registre-araignees/

## Ce que fait l'outil

- Fiche de récolte avec numéro séquentiel pour relier le spécimen à ses photos
- Méthodes de récolte, période de pose des pièges, effort d'échantillonnage, protocole (CPAD, Coddington et al. 1991)
- Étiquettes de 35, 30 ou 22 mm selon le flacon (10, 4 ou 2 ml), imprimées quelques-unes à la fois sur carte 10 × 15 cm ou feuille 8½ × 11
- Suivi de la conservation (emplacement, changements d'alcool)
- Export CSV (Excel) et sauvegarde complète

## Confidentialité et sécurité

- Aucune donnée n'est envoyée : le registre est enregistré uniquement dans votre navigateur.
- Une règle de sécurité (Content-Security-Policy) intégrée au fichier bloque toute connexion sortante.
- Seule dépendance : [jsPDF 2.5.1](https://github.com/parallax/jsPDF) (licence MIT), chargée depuis cdnjs et vérifiée par son empreinte (Subresource Integrity).
- Le mode de navigation privée efface les données à la fermeture de la fenêtre : utilisez une fenêtre normale et exportez une sauvegarde régulièrement.

Tout le code est dans le fichier `index.html`, lisible sans outil particulier.

## Référence

Pierre Paquin et Nadine Dupérré, 2026. *Les araignées du Québec*, Natureweb, avec Gilles Arbour et Catherine Dubois. 340 p.

## Versions

| Version | Date | Empreinte SHA-256 de `index.html` |
|---|---|---|
| 1.0.0-beta.1 | 30 septembre 2026 | `c75a932f18f84325da791116b581f406ad71b7119b8d3ef22b971bbdfc124d27` |

## Auteur

Marc Lajoie. Outil conçu avec l'aide de Claude (Anthropic). Commentaires bienvenus dans l'onglet *Issues* de ce dépôt ou dans le groupe privé Facebook [« Les araignées du Québec »](https://www.facebook.com/groups/486277948065390).

