# Projet-Test-Logiciels
## Team members
> LGLSI2-TD2-TP4
* Mohamed Marzougui
* Mohamed Anis Jbara
* Hassen Horrich

## Content

------------------------------------------------------------------------------------------

Dans notre projet on a écrit un programme "CalculTVA" qui est une application graphique permettant de calculer la TVA et le prix total à partir d'un prix hors taxes et d'un taux de TVA sélectionné.

L'interface utilisateur est composée d'une étiquette pour le prix, d'un champ de texte pour entrer le prix,
d'une étiquette pour le taux de TVA, d'une liste déroulante pour sélectionner le taux de TVA (9%, 11% ou 19%), 
d'un bouton "Calculer" pour effectuer les calculs et d'une étiquette pour afficher les résultats.

Lorsque l'utilisateur appuie sur le bouton "Calculer", le programme récupère le prix et le taux de TVA sélectionné, calcule la TVA et le prix total en appelant les méthodes "calculTVAvalue" et "calculTotalPrice" respectivement, puis affiche les résultats formatés avec deux décimales.

En cas d'erreur de saisie, le programme affiche un message d'erreur à l'utilisateur 
dans l'étiquette des résultats.

En résumé, le programme "CalculTVA" fournit une interface utilisateur simple 
et conviviale pour effectuer des calculs de TVA et de prix total en temps réel.

------------------------------------------------------------------------------------------

# TestTVA1:

Le test 'TestTVA1' est une classe de test unitaire qui teste la fonction calculTVAvalue() de la classe 'CalculTVA'. 
Le test vérifie que la méthode calcule correctement la TVA pour un prix donné 
et un taux de TVA donné en comparant la valeur renvoyée par la méthode avec une valeur attendue.

La méthode 'assertEquals' est utilisée pour comparer les valeurs, elle prend trois paramètres: 
la valeur attendue (30 dans ce cas), la valeur retournée par la méthode calculTVAvalue 
et la précision de la comparaison (0.1 dans ce cas). 
Si la valeur retournée par la méthode diffère de la valeur attendue de plus de 0.1, 
le test échoue et une erreur est signalée.


------------------------------------------------------------------------------------------

# TestTVA2:

Ce test a pour fonctionnalité de tester la méthode calculTotalPrice() de la classe 'CalculTVA'. 
Il teste si le montant total du produit, y compris la TVA, est calculé correctement. 
Le test initialise également une instance de la classe 'CalculTVA' avant chaque test et la détruit après chaque test en utilisant les annotations @BeforeEach et @AfterEach, respectivement. 
Il mesure également la durée totale de tous les tests à l'aide des annotations @BeforeAll et @AfterAll.



------------------------------------------------------------------------------------------

En utilisant des tests tels que celui-ci, les développeurs peuvent s'assurer que chaque méthode de leur programme fonctionne correctement, ce qui réduit les erreurs et les bugs potentiels.
