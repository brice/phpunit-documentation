## Comment construire la documentation

Pour compiler la documentation en français, les pré-requis sont les suivants :

- Apache Ant
- PHP 5 (avec les extensions DOM, PRCE, SPL et Tokenizer)
- Ruby
- xsltproc

Pour compiler la documentation en français :

    cd build
    ant build-fr-6.1

Attention, la documentation est en cours de traduction (cf. tableau ci dessous)


## Contributions attendues

 * Traduire les fichiers encore en anglais
 * Mettre à jour les fichiers existants
 * Partir à la chasse aux typos et aux fautes d'orthographes, de grammaire et de syntaxes
 * Détecter le franglais et les anglicismes
 * Revue de pair sur les PR


## Plan

| Fichier                           | Etat      | Contributeurs  | Nb ligne revues/Total    |
| --------------------------------- | :-------: | :------------: | :----------------------: |
| annotations.xml                   | En cours  | @brice         | 30/511                   |
| assertions.xml                    | NOK       |                |                          |
| bibliography.xml                  | NOK       |                |                          |
| book.xml                          | NOK       |                |                          |
| code-coverage-analysis.xml        | En cours  | @brice         |                          |
| configuration.xml                 | NOK       |                |                          |
| copyright.xml                     | NOK       |                |                          |
| database.xml                      | NOK       |                |                          |
| extending-phpunit.xml             | NOK       |                |                          |
| fixtures.xml                      | NOK       |                |                          |
| incomplete-and-skipped-tests.xml  | NOK       |                |                          |
| index.xml                         | NOK       |                |                          |
| installation.xml                  | En cours  | @brice         |                          |
| logging.xml                       | NOK       |                |                          |
| organizing-tests.xml              | NOK       |                |                          |
| other-uses-for-tests.xml          | NOK       |                |                          |
| risky-tests.xml                   | NOK       |                |                          |
| test-doubles.xml                  | En cours  | @brice         | 172/1045                 |
| testing-practices.xml             | NOK       |                |                          |
| textui.xml                        | OK        | @gbprod        |                          |
| writing-tests-for-phpunit.xml     | NOK       |                |                          |


## Guide de traduction

Dans ce fichier sont recensées les règles de traductions utilisées de manière à garantir la cohérence d'ensemble.
Sont notamment visés les termes techniques.

actual:			constatée (valeur)
array:			traduit par tableau sauf quand on fait explicitement référence à PHP
assertion:		traduit par asssertion, plus parlant que affirmation
composable:		composable (rien trouvé de mieux)
expected:		attendue (valeur)
framework:		framework
isolated:		indépendant (isolé est ambigu, étanche un peu moins...)
notice:			remarque
return:			retourne plutôt que renvoie
requirements:	pré-requis
extension:		extensions
code coverage:	couverture de code
appendix:       annexe
fixture:        fixture (pas trouvé mieux en français)

verbe ing: 	traduits par l'infinitif dans les titres: testing => tester

## Historique du projet de traduction

14/02/2017 : Je relance le projet de traduction de la doc de PHPUnit afin de permettre à des francophones de mieux appréhender ce produit. La dernière version française complète est lié à la version 4.3 de phpunit. C'est cette version qui est dupliquée dans les répertoires 4.4 à 6.0. La traduction commence à la version 6.1 avec un travail en cours de récupération des fichiers manquants et mise à jour des fichiers existant.

03/03/2017 : J'ai ajouté un tableau d'avancement ppur mesurer le travail à fournir pour arriver au bout des traductions.
