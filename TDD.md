# Le TDD (Test-Driven-Development)

(à modifier) Process de développement d'applications où l'on écrit les tests avant tout. Tests qui seront ensuite validés au fur et à mesure du développement. On comprend facilement l'avantage d'une telle démarche :
* on évite de découvrir des bugs à la fin du développement (on parle de 'mise en prod', pour production)
* l'application est rapidement opérationnelle dès que les tests sont tous validés



**Travis** </br>
Outil de tests automatiques (intégration continue), proche des tests unitaires car teste à chaque commit/push...

>* *Intégration Continue* (IC) nécessite que l'app soit bien testée, donc avec des bons test écrits au début (avec un bon "code coverage")

>* *Code coverage* = le  % de l'app qui est testé.</br>
Par ex si c’est 20% qui est testé, on a 80% de chance d’avoir des erreurs.

*Pour résumer :* </br>
IC demande bon code coverage => demande du TDD => demande donc du Test Unitaire car précis
