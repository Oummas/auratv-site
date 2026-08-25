# auratv-site

Pages publiques d'AuraTV : accueil, conditions générales d'utilisation et
politique de confidentialité. Servies par GitHub Pages parce que la page
d'achat de l'application ouvre ces URL, et qu'Apple refuse un paywall dont les
liens légaux ne résolvent pas.

- `index.html` — page d'accueil
- `cgu.html` — conditions générales d'utilisation (FR)
- `confidentialite.html` — politique de confidentialité (FR)

En ligne :

- https://oummas.github.io/auratv-site/
- https://oummas.github.io/auratv-site/cgu.html
- https://oummas.github.io/auratv-site/confidentialite.html

Ce sont exactement les URL que `AuraPlus.termsURL` et `AuraPlus.privacyURL`
pointent dans `Core/Store/SubscriptionStore.swift`, côté application.

## Pourquoi un dépôt séparé

Le dépôt de l'application est privé, et GitHub Pages n'est pas disponible sur
un dépôt privé en plan gratuit. Ce dépôt-ci ne contient que du HTML statique :
il peut être public sans exposer le code de l'application.

La source de vérité reste `docs/` dans le dépôt de l'application — toute
modification part de là et se recopie ici.
