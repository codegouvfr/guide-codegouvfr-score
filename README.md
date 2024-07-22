
# Table of Contents

1.  [Présentation](#org3adcaf2)
2.  [Test](#org6eed6c1)
3.  [Contribution](#org4b55f34)
4.  [Licence](#orga28078e)

[![img](https://img.shields.io/badge/Licence-EPL%2C%20Licence%20Ouverte-orange.svg?style=flat-square)](https://git.sr.ht/~codegouvfr/guide-juridique-logiciel-libre/tree/master/item/LICENSES)


<a id="org3adcaf2"></a>

# Présentation

Ce dépôt contient le code pour une application web présentant le guide
*awesome* pour calculer le *awesome score* des logiciels libres du
secteur public.

L'application est là : [guide-awesome-score.code.gouv.fr](https://guide-awesome-score.code.gouv.fr).

Ce dépôt de code source est dérivé de l'appliation
<https://git.sr.ht/~bzg/choices>.


<a id="org6eed6c1"></a>

# Test

1.  Modifier `src/cljs/choices/config.cljs`
2.  Lancer `~$ lein fig:test` pour tester le format de `config/tree`
3.  Compilez avec `~$ lein fig:min`
4.  Vos fichiers statiques sont dans `resources/public/`


<a id="org4b55f34"></a>

# Contribution

Ce dépôt ne permet pas d'ouvrir des issues ou des *pull requests*.

Les contributions au code sont les bienvenues sous forme de questions
ou de patches à envoyer à `~codegouvfr/dev@lists.sr.ht`.

Nous n'acceptons les contributions que si elles sont signées (*signed
off*) du vrai nom du contributeur.  En signant ses contributions, le
contributeur accepte le [developer certificate of origin](https://developercertificate.org).


<a id="orga28078e"></a>

# Licence

2024 DINUM, Bastien Guerry, Louis Vigneras.

Le code de ce dépôt est publié sous [licence EPL 2.0](LICENSES/LICENSE.EPL-2.0.md) et les données du
dépôt sous [licence Ouverte 2.0](LICENSES/LICENSE.Etalab-2.0.txt).

