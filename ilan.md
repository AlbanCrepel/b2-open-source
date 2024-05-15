# Réponses de [Ilan](https://github.com/IlanOu)

## 1. Licences

<!--
Quelle licence serait appropriée si je veux une licence permissive ? 
-->
- a)
  - La licence MIT
  - La licence Apache 2.0
  - La licence BSD

<!-- 
Quelle licence serait appropriée si je veux que les projets utilisant ma solution soient obligatoirement open source eux aussi ?
-->
- b) La licence GPL

<!--
Quelles sont mes obligations si j'utilise un projet sous licence `Creative Commons Attribution 4.0 International` ?
-->
- c)
  - Obligation de créditer l'auteur original
  - Fournir un lien vers la licence
  - Indiquer si des modifications ont été apportées

<!--
Qu'appelle-t-on une licence "contagieuse" ?
-->
- d) C'est une licence qui impose que les projets dérivés soient distribués sous la même licence (ex : la licence GPL)

> Ressources :
> - https://choosealicense.com/
> - https://www.tldrlegal.com/

## 2. Solutions propriétaires vs open source

### Bruno vs Postman

<!--
Quelles raisons ont poussé beaucoup d'utilisateurs à chercher une alternative à Postman ?
-->
- a) Postman est devenu une solution payante et propriétaire avec une offre gratuite limitée

<!--
Quels sont les avantages de Bruno ?
-->
- b) Bruno est gratuit, open-source et sans limite d'utilisation (et les utilisateurs peuvent contribuer)

> Ressources :
> - https://www.usebruno.com/compare/bruno-vs-postman
> - https://star-history.com/#usebruno/bruno&Date
> - [Post Reddit 1](https://www.reddit.com/r/webdev/comments/17wqn5a/fuck_you_postman/)
> - [Post Reddit 2](https://www.reddit.com/r/webdev/comments/16tq1eh/now_that_postman_sucks_is_there_a_good_alternative/)
> - [Post Reddit 3](https://www.reddit.com/r/webdev/comments/16yxy43/what_are_people_using_instead_of_postman/)

### Twitter vs Mastodon

<!--
À votre avis, quelles raisons ont poussé beaucoup d'utilisateurs à chercher une alternative à Twitter (ou X) ?
-->
- c)
  - Le nouveau propriétaire de Twitter est Elon Musk
  - Il a licencié beaucoup d'employés
  - Il a ajouté des fonctionnalités payantes
  - La plateforme prend une tournure plus politique
  - Certains craignent pour la confidentialité de leurs données

> Ressources :
> - https://star-history.com/#mastodon/mastodon&Date

### Animejs, GSAP & rémunération

<!--
Quelles sont les différences entre Animejs et GSAP, 2 librairies utilisées pour faire des animations web ?
-->
- d) GSAP est une solution payante avec une licence propriétaire alors qu'Animejs est open source et gratuit

<!--
Pourquoi GSAP a choisi une licence moins permissive ?
-->
- e) Pour pouvoir générer des revenus

<!--
Comment les projets open source peuvent être rémunérés et donc maintenus correctement ?
-->
- f)
  - Dons
  - Sponsoring
  - Modèle freemium
  - Une licence différente pour les entreprises (personnalisé mais payant pour les entreprises)


> Ressources :
> - https://gsap.com/pricing/
> - https://gsap.com/blog/why-license
> - https://github.com/juliangarnier/anime/
> - https://strapi.io/pricing-cloud

### Le cas de Meta

<!--
Qu'est-ce qui a poussé Meta à changer la licence de React ?
-->
- g) Meta est passé à la licence MIT pour ces raisons :
  - Minimiser les risques juridiques
  - Se créer une communauté active
  - Éviter les contraintes de la licence GPL
  - Suivre les pratiques de l'industrie

> Ressources :
> - [Article Medium](https://medium.com/@raulk/if-youre-a-startup-you-should-not-use-react-reflecting-on-the-bsd-patents-license-b049d4a67dd2)

## 3. Quand ça tourne mal

### colors & faker.js

<!--
Résumer brièvement ce qui s'est passé sur ces 2 packages
-->
- a) Un développeur a contribué à ces projets en publiant des nouvelles versions instables avec du code malveillant

<!--
En quoi était-ce une faille importante ?
-->
- b) Tout les projets qui utilisaient ces packages ne fonctionnaient plus, tout s'est propagé très vite

<!--
Quelles sont les solutions pour se prémunir de ce genre de faille ?
-->
- c)
  - Il faut vérifier attentivement le code que les contributeurs partagent
  - Tester son code avant de le publier !

> Ressources :
> - https://snyk.io/blog/open-source-npm-packages-colors-faker/
> - https://www.bleepingcomputer.com/news/security/dev-corrupts-npm-libs-colors-and-faker-breaking-thousands-of-apps/
> - https://www.youtube.com/watch?v=R6S-b_k-ZKY

### XZ backdoor

<!--
À votre avis, quels sont les avantages d'avoir une faille dans une solution open source plutôt que propriétaire ?
-->
- d)
  - La communauté peut examiner le code source, identifier la faille et proposer une correction rapidement
  - Dans une solution propriétaire, la faille peut rester cachée plus longtemps

> Ressources :
> - https://www.youtube.com/watch?v=bS9em7Bg0iU
> - https://fr.wikipedia.org/wiki/Attaque_de_XZ_Utils_par_porte_d%C3%A9rob%C3%A9e

---

LICENSE: CC-BY-SA-4.0
