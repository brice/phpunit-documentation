Historique du projet de traduction
===================

14/02/2017 : Je relance le projet de traduction de la doc de PHPUnit afin de permettre à des francophones de mieux appréhender ce produit.


Comment construire la documentation
===================================

Pour compiler la documentation en français, les pré-requis sont les suivants :

- Apache Ant
- PHP 5 (avec les extensions DOM, PRCE, SPL et Tokenizer)
- Ruby
- xsltproc

Pour compiler la documentation en français :

    cd build
    ant build-fr-6.1

Attention, la documentation est en cours de traduction (cf. tableau ci dessous)


Plan
===================

| Fichier                           | Etat      | Contributeur  |
| --------------------------------- | :-------: | :-----------: |
| annotations.xml                   | En cours  |               |
| assertions.xml                    | NOK       |               |
| bibliography.xml                  | NOK       |               |
| book.xml                          | NOK       |               |
| code-coverage-analysis.xml        | NOK       |               |
| configuration.xml                 | NOK       |               |
| copyright.xml                     | NOK       |               |
| database.xml                      | NOK       |               |
| extending-phpunit.xml             | NOK       |               |
| fixtures.xml                      | NOK       |               |
| incomplete-and-skipped-tests.xml  | NOK       |               |
| index.xml                         | NOK       |               |
| installation.xml                  | En cours  |               |
| logging.xml                       | NOK       |               |
| organizing-tests.xml              | NOK       |               |
| other-uses-for-tests.xml          | NOK       |               |
| risky-tests.xml                   | NOK       |               |
| test-doubles.xml                  | NOK       |               |
| testing-practices.xml             | NOK       |               |
| textui.xml                        | NOK       |               |
| writing-tests-for-phpunit.xml     | NOK       |               |


Guide de traduction
===================

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

verbe ing: 	traduits par l'infinitif dans les titres: testing => tester

