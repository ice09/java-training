# Java Training 

Java Training is a series of exercises that will allow you to practice Java development. In the SEA, we will use these exercises for Dojos. You will have the possibility to automatically test the code of each exercise.

## Objectives

* Train the Java Fundamentals of the 3rd week
* Test your code
* Know how analyze errors by reading error logs and stacktraces

## Steps

* Clone this repository
* Switch to branch *dojo-sea-fundamentals*

### Setup of the project in your IDE

First step before starting the exercise: check that everything is in place to work.

In IntelliJ, you should see this project structure (in the "project" tab):

``` bash
.
├── lib
│   ├── hamcrest-core-1.3.jar
│   └── junit-4.12.jar
├── logs
├── README.md
├── src
│   ├── exercices
│   │   └── PrimitiveTraining.java
│   │   └── ...
│   └── tests
│       ├── MainTest.java
│       └── PrimitiveTrainingTest.java
│       └── ...
└── tester.sh

```

## Preparation of the Dojo

### Envoie ta solution

1. Créé un *fork* du dépôt 
1. Modifie et teste ton code avec `./tester.sh Exercice`
2. Quand ton code passe tous les tests, add/commit/push sur ton *fork*
3. Partage ton dépôt *GitHub* en solution de la quête

### Critères de validation

* Le code se compile sans erreur
* Le code passe toutes les validations attendues
* Le code respecte les conventions de Java (indentation, nommage de variable, classe, méthodes, etc...)