# bagnolino.fr

Site public de Bagnolino, servi par GitHub Pages. Quatre pages statiques, aucun build :

- `/` — accueil
- `/confidentialite/` — politique de confidentialité (URL déclarée dans App Store Connect)
- `/support/` — support (URL déclarée dans App Store Connect)
- `/mentions-legales/` — mentions légales (LCEN)

La DA est celle de l'app (« verre, forêt & terre », `apps/mobile/src/theme/tokens.ts`) :
tout le style est dans `style.css`. Les écrans de `img/` sont exportés de la page Figma
« 04 · App Store ». La police est servie par le site (`fonts/`), jamais par Google :
le site ne charge aucune ressource tierce, et les mentions légales l'affirment.

Le favicon « B » est provisoire, en attendant la vraie icône de l'app.
Ce qui reste à remplir est surligné en ocre (classe `a-remplir`) : `grep -rn a-remplir .`

Ce dépôt est public parce que GitHub Pages l'exige sur un compte gratuit. Le code de
l'app vit ailleurs, en privé. Un `git push` sur `main` met le site en ligne.

⚠️ Les deux URLs légales sont déclarées chez Apple : ne pas les renommer.
