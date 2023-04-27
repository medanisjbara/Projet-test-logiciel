|--------------------|---------------------------------------|------------------------------------------------|
| Nom du cas de test | Étapes de test                        | Résultat attendu                               |
|--------------------|---------------------------------------|------------------------------------------------|
| TestTVA1           |                                       |                                               |
|                    | 1.Préparer les données d'entrée :     |* La méthode de CalculTVAvalue                  |
|                    |   définir une valeur de prix et       |  retourne la valeur de TVA attendue            |
|                    |    un taux de TVA.                    |  pour chaquecombinaison de prix                |
|                    | 2.Exécuter la méthode CalculTVAvalue  |  et de taux de TVA.                            |
|                    |  en utilisant les données d'entrée    |* La méthode ne modifie pas les valeurs de prix |
|                    |  préparées.                           |  et de taux de TVA entrées.                    |
|                    | 3.Vérifier que la méthode renvoie     |* Les valeurs de sortie de la méthode sont     |
|                    |    la valeur  de TVA attendue.        |  cohérentes avec les valeurs attendues selon   |
|                    | 4.Répéter les étapes 1 à 3 pour       |  les spécifications fonctionnelles ou les     |
|                    | plusieurs combinaisons de prix        |  exigences du logiciel.                       |
|                    |  et de taux de TVA.                   |                                                |
|--------------------|---------------------------------------|------------------------------------------------|
| TestTVA2           | 1.Initialiser un objet CalculTVA      |* La méthode Assert doit vérifier                |
|                    |   en utilisant la méthode             |  que la valeur de retour de la méthode |
|                    |   initCalcTVA().                      |  calculTotalPrice() correspond à la somme du |
|                    | 2.Définir le prix et le taux de TVA   |  prix et de la TVA attendue.|
|                    |   en utilisant la méthode Arrange.    |    |
|                    | 3.Appeler la méthode                  | |
|                    |   calculTotalPrice() avec le prix     | |
|                    |   et le taux de TVA en utilisant      | |
|                    |   la méthode Act.                     | |
|                    | 4.Vérifier que la valeur de retour    | |
|                    |   de la méthode calculTotalPrice()    | |
|--------------------|---------------------------------------|------------------------------------------------|
