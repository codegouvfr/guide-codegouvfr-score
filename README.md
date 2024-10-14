[![img](https://img.shields.io/badge/code.gouv.fr-ouvert-mediumseagreen.svg)](https://code.gouv.fr/documentation/#/publier.md)
[![img](https://img.shields.io/badge/Licence-EPL%2C%20Licence%20Ouverte-orange.svg)](https://git.sr.ht/~codegouvfr/guide-juridique-logiciel-libre/tree/master/item/LICENSES)


# Présentation

Ce dépôt contient le code pour une application web permettant de
calculer un *score* pour les dépôts de code source du secteur public.

L'application est là : <https://code.gouv.fr/guides/codegouvfr-score/>

Ce dépôt de code source est dérivé de l'application
<https://git.sr.ht/~bzg/choices>.


# Test et compilation

1.  Modifiez `config.yml`
2.  Testez votre configuration avec `clj -M:test`
3.  Compilez avec `clj -M:fig`

Vos fichiers statiques sont dans `resources/public/`


# Contribution

Les contributions au code sont les bienvenues sous forme de questions
ou de patches à envoyer à `~codegouvfr/dev@lists.sr.ht`.

Nous n'acceptons les contributions que si elles sont signées (*signed
off*) du vrai nom du contributeur. En signant ses contributions, le
contributeur accepte le [developer certificate of origin](https://developercertificate.org).

Si vous ne savez pas comment contribuer autrement qu'avec des *pull
requests*, faites votre PR, ajoutez `.patch` à l'URL de la PR,
téléchargez le patch qui s'affiche et envoyez-le en pièce jointe à la
liste `~codegouvfr/dev@lists.sr.ht`.


# Licence

2024 DINUM, Bastien Guerry, Louis Vigneras.

Le code de ce dépôt est publié sous [licence EPL 2.0](LICENSES/LICENSE.EPL-2.0.md) et les données du
dépôt sous [licence Ouverte 2.0](LICENSES/LICENSE.Etalab-2.0.txt).

