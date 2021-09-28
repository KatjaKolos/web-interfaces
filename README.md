[comment]: <> "LTeX: language=fr"
<!-- markdownlint-disable MD003 MD025 MD033 -->

Interfaces web pour le TAL
==========================

[![Licence : CC BY 4.0](https://licensebuttons.net/l/by/4.0/80x15.png)](https://creativecommons.org/licenses/by/4.0/)

Contenus pour le cours « Bases de données et web dynamique » du master [Plurital](http://plurital.org).


- [Site du cours](https://loicgrobol.github.io/web-interfaces/)
- [Dépôt GitHub](https://github.com/LoicGrobol/web-interfaces)

Contact : [<loic.grobol@parisnanterre.fr>](mailto:loic.grobol@parisnanterre.fr)

## Développement

Pour travailler au développement de ce cours :

1. Créer un environnement virtuel et l'activer
2. Installer les dépendances

   ```console
   pip install -U -r requirements.txt
   ```

3. Démarrer jupyter

   ```console
   jupyter notebook
   ```

   Idéalement ça devrait aussi marcher avec jupyterlab [mais ce n'est pas encore le cas pour les slides](https://github.com/damianavila/RISE/pull/381)
4. On peut alors modifier les fichiers md dans jupyter comme si c'étaient des notebooks grâce à la magie de [jupytext](https://github.com/mwouts/jupytext)

Autres éléments magiques :

- On peut ouvrir les notebooks en md sur Binder grâce au [postBuild](postBuild) qui dit de compiler
  l'extension jupytext. Par contre le build initial de l'image est assez lent. (même avec
  `--minimize=False` qui [accélère un
  peu](https://github.com/jupyterlab/jupyterlab/issues/4824#issuecomment-697188390))

## Licences

[![CC BY Licence badge](https://i.creativecommons.org/l/by/4.0/88x31.png)](http://creativecommons.org/licenses/by/4.0/)


Copyright © 2021 Loïc Grobol [\<loic.grobol@gmail.com\>](mailto:loic.grobol@gmail.com)

Sauf indication contraire, les fichiers présents dans ce dépôt sont distribués selon les termes de
la licence [Creative Commons Attribution 4.0
International](https://creativecommons.org/licenses/by/4.0/).

Un résumé simplifié de cette licence est disponible à <https://creativecommons.org/licenses/by/4.0/>.

Le texte intégral de cette licence est disponible à
<https://creativecommons.org/licenses/by/4.0/legalcode>

## Exceptions à la licence

Les fichiers suivants ne sont pas distribués selon les termes de la licence Creative Commons
Attribution 4.0 International

### CC-BY-SA

[![CC-BY-SA Licence badge](https://i.creativecommons.org/l/by-sa/2.5/88x31.png)](http://creativecommons.org/licenses/by-nc-nd/4.0/)

- Les images `internet-schema-*.png` et `simple-client-server.png` du dossier
  [`slides/lecture-06/pics`](slides/lecture-06/pics) sont issues [de la documentation web du
  MDN](https://github.com/mdn/content) sont soumises à la licence [CC-BY-SA
  2.5](https://creativecommons.org/licenses/by-sa/2.5/).