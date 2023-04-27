| Nom du cas de test | Étapes de test                                                                         | Résultat attendu                               |
|--------------------|----------------------------------------------------------------------------------------|------------------------------------------------|
|  TestTVA1          | 1.Préparer les données d'entrée : définir une valeur de prix et un taux de TVA.        | * La méthode de CalculTVAvalue retourne la valeur de TVA attendue pour chaquecombinaison de prix et de taux de TVA.|
|                    | 2.Exécuter la méthode CalculTVAvalue en utilisant les données d'entrée préparées.      | * La méthode ne modifie pas les valeurs de prix et de taux de TVA entrées.                           |
|                    | 3.Vérifier que la méthode renvoie la valeur  de TVA attendue.                          | * Les valeurs de sortie de la méthode sont cohérentes avec les valeurs attendues selon  les spécifications fonctionnelles ou les exigences du logiciel.   |
|                    | 4.Répéter les étapes 1 à 3 pour plusieurs combinaisons de prix et de taux de TVA.      |  
| TestTVA2           | 1.Initialiser un objet CalculTVA en utilisant la méthode initCalcTVA().                | * La méthode Assert doit vérifier que la valeur de retour de la méthode calculTotalPrice() correspond à la somme du prix et de la TVA attendue. |
|                    | 2.Définir le prix et le taux de TVA  en utilisant la méthode Arrange.  
|                    | 3.Appeler la méthode calculTotalPrice() avec le prix et le taux de TVA en utilisant la méthode Act. | |
|                    | 4.Vérifier que la valeur de retour de la méthode calculTotalPrice()                    |  |
