# EDU-AC-Project1-S5

Site vitrine associatif d'une ONG éducative fictive, réalisé dans le cadre de la Semaine 5 du programme d'Akieni Academy (Brazzaville).

## Membres et rôles

| Membre | Rôle | Partie codée |
|---|---|---|
| AKIANA Arsène Gloire  | Lead / Coordination | Header, nav, footer, style.css commun |
| TSIBA Gaevie | Repo Admin | Création du repo, gestion des branches/PR, page Contact / Faire un don, déploiement GitHub Pages |
| AKIANA Arsène Gloire assisté par NGASSAI Ndongo Dubien __ due à un problème avec son ordinateur  | Dev Accueil | index.html (hero + chiffres clés) |
| MOUTOU MOUKOLO Christian Dorgela | Dev Nos actions | actions.html (grille de cartes) |
| MIKOLO Rolvi | Dev Événements | evenements.html (liste des événements) |

## Liens

- Dépôt GitHub : https://github.com/loriontsiba-debug/EDU-AC-Project1-S5.git
- Site déployé (GitHub Pages) : https://loriontsiba-debug.github.io/EDU-AC-Project1-S5/

## Conflit de merge rencontré

Un conflit est survenu sur `style.css` entre les branches `feature/conflit-demo` (Lead) et `feature/actions` (Dev Nos actions), tous deux ayant modifié la section `.nos-actions` du fichier.

Résolu par AKIANA Arsène Gloire  le 9 sptembre 2026, en conservant une des deux modifications et en supprimant les marqueurs de conflit (`<<<<<<<`, `=======`, `>>>>>>>`).

![Capture du conflit de merge1](assets/image%20du%20conflit%201.png)


![Capture du conflit de merge2](assets/image%20du%20conflit%202.png)

## Contraintes techniques respectées

- [x] Sémantique HTML : `header`, `nav`, `main`, `section`, `article`, `footer`
- [x] Au moins 1 section en Flexbox (nav, chiffres clés) et 1 section en Grid (nos actions)
- [x] Responsive testé sur 3 breakpoints : mobile (~375px), tablette (~768px), desktop (~1280px)
- [x] Repo GitHub dédié, au moins 1 branche et 1 Pull Request par membre
- [x] Au moins 1 conflit de merge rencontré et documenté (voir ci-dessus)
- [x] Déploiement sur GitHub Pages

## Structure du projet

```
index.html
actions.html
evenements.html
contact.html
style.css
README.md
fichier assets
fichier images
```
