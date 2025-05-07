# Méthode de Gram-Schmid classique

1. Créez un *fork* de ce dépôt sur votre compte GitHub ;
2. clonez votre *fork* en local ;
3. créez une nouvelle branche sur votre clone local ;
4. modifiez le fichier `rapport.qmd` et ajoutez les fichiers source `.jl` nécessaires ;
5. tout le code julia doit être visible dans votre rapport ;
6. validez les questions en utilisant une ou plusieurs commandes `@test` dans un fichier `test.jl` qui sera inclus (via `{{< include >}}`) dans votre rapport ;
7. consignez vos changements à votre branche locale ;
8. n'incluez pas le PDF de votre rapport dans votre *pull request* ;
9. publiez votre branche sur votre *fork* distant ;
10. ouvrez une *pull request* proposant vos modifications à la branche `main` **de mon dépôt** (pas de votre *fork*).

Une fois ces opérations effectuées, votre rapport sera automatiquement compilé en PDF et un lien sera posté dans la *pull request*.
Votre fichier `test.jl` sera également exécuté via la commande `julia --project=rapport_env -e 'include("test.jl")'`.
Attention, `test.jl` doit contenir (ou inclure un fichier qui contient) les bonnes commandes `using ...`, mais il ne doit pas activer l'environnement.

Je ferai des commentaires dans votre *pull request* si nécessaire.
Tant que l'indicateur des tests dans la *pull request* n'indique pas que vos modifications sont correctes, que votre rapport ne compile pas, et tant que la date et l'heure limite ne sont pas dépassées, vous pouvez apporter des changements afin de corriger le tir.
À chaque changement consigné à votre branche, les modifications seront à nouveau validées.
