# CV web — Ayoub Dfil
Projet SAÉ 1.04, BUT Réseaux et Télécommunications, IUT de Colmar, 2026–2027.
Site personnel de quatre pages, entièrement en HTML et CSS.

## Organisation

- `index.html` : profil, parcours synthétique, compétences et résumé anglais.
- `formations.html` : études et présentation du projet.
- `diplomes.html` : diplômes obtenus.
- `experiences.html` : ALDI, Poulaillon et service civique.
- `style.css` : feuille de style unique, commune aux quatre pages.
- `photo.png` : portrait personnel.


## Navigation et choix de réalisation

Chaque formation, diplôme et expérience de l’accueil renvoie vers sa rubrique détaillée : par exemple, `experiences.html#aldi` cible la section `id="aldi"`. Un sommaire permet de changer de rubrique sur les pages secondaires ; un lien ramène au résumé correspondant sur l’accueil.

Les compétences sont réparties en trois éléments Flexbox. Les pages secondaires utilisent une grille pour séparer les dates et les descriptions. Les classes portent des noms français liés à leur rôle, comme `presentation`, `coordonnees` et `titre-detail`.

Les vérifications portent sur les liens et les ancres, le chargement du portrait et l’absence de débordement à différentes largeurs, dont une fenêtre réduite de moitié. Le projet comprend aussi un accès direct au contenu au clavier, un focus visible et un style d’impression.


## Projet personnel : diffusion sur Twitch

Je diffuse sur [ma chaîne Twitch](https://www.twitch.tv/ayoubdark68) par passion, pour partager mes parties et échanger avec mes amis et ma communauté. J’utilise OBS Studio et deux écrans : le jeu sur l’écran principal, le chat et l’aperçu du direct sur le second.

La rubrique `formations.html#twitch` présente mon organisation, les compétences mobilisées et un exemple de session. Les deux captures personnelles, `capture-obs.png` et `bilan-twitch.png`, restent à la racine avec les autres fichiers. Elles sont affichées avec des légendes et peuvent être agrandies par un lien HTML.

Le bilan du 11 août montre 2 h 24 de diffusion, 3 spectateurs en moyenne, un maximum de 6 et 13 spectateurs uniques. Ces chiffres décrivent cette session uniquement ; ils ne constituent pas une mesure de progression de la chaîne.
