**Structure des dossiers**

Le dossier de définition de tâche contient la tâche à traiter    
Le dossier de code contient le code fourni, des tests et des répertoires pour votre propre code    

src / main / java / ias: interfaces et classes prédéfinies. Ne peut pas être modifié!     
src / main / java / student: dossier pour votre code      
src / main / resources: Voici les règles de style de vérification. Vous pouvez le faire automatiquement (voir Exécuter et tester)     
src / main / test / ias: tests JUnit prédéfinis pour vérifier votre code   
src / main / test / student: Ici, vous pouvez et devez créer des tests supplémentaires pour tester votre code indépendamment  
Les dossiers ias et student sont nommés dans des packages Java.   
Pour plus d'informations, voir: https://docs.oracle.com/javase/tutorial/java/package/packages.html   


**Exécuter et tester

Toutes les commandes suivantes doivent être exécutées à partir du dossier de code

./gradlew checkstyleMain - Exécute les règles de contrôle pour tous les fichiers Java dans le répertoire src / main / java

./gradlew vérification Exécute les règles Checkstyle et tous les tests JUnit

./gradlew test Exécute tous les tests JUnit

./gradlew pot - Compiler le projet - Le projet compilé peut être exécuté avec la commande java -jar build / libs / [nom_du_jar] .jar
