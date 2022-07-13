# testeLiquibase


![image](https://user-images.githubusercontent.com/92308305/178695125-0977261a-37f0-4cb4-988d-2956fa80efdb.png)

Liquibase aide des millions d'équipes à suivre, versionner et déployer les changements de schéma de base de données. Cela vous aidera à :

    Contrôler les modifications du schéma de base de données pour des versions spécifiques
    Éliminer les erreurs et les retards lors de la publication des bases de données
    Commander automatiquement des scripts pour le déploiement
    Annuler facilement les modifications
    Collaborez avec des outils que vous utilisez déjà

Ce référentiel contient le code source principal de Liquibase. Pour plus d'informations sur le produit, consultez le site Web principal du projet .
Automatisation et intégrations Liquibase

Liquibase Core fonctionne avec les bases de données suivantes : Apache Derby, CockroachDB, Firebird, H2, HSQL, Informix, InterBase, MariaDB, MSSQL, MySQL, Oracle, PostgreSQL, SQLite, Sybase Anywhere, Sybase Enterprise. Les bases de données qui nécessitent des extensions sont : Azure Cosmos DB , Cassandra , Cache , DB2i , Hibernate , Impala/Hive , MaxDB , MongoDB , Redshift , SAP HANA , SQLFire , Snowflake , Teradata , Vertica , VoltDB . Voir Tutoriels de base de données Liquibase .

Liquibase peut être intégré à Maven, Ant, Gradle, Spring Boot et à d'autres outils CI/CD. Vous pouvez utiliser Liquibase GitHub Actions, Liquibase et Jenkins avec Spinnaker, et de nombreux workflows différents.
Surveillance et visibilité en temps réel

Essayez Liquibase Hub pour obtenir des informations en temps réel sur vos déploiements, un aperçu des commandes récentes pour la base de données spécifique sur laquelle vous travaillez et un espace pour la collaboration de votre équipe.
Installer et exécuter Liquibase
Configuration requise

La configuration système requise pour Liquibase est disponible sur la Télécharger Liquibase .
Un exemple de base de données en mémoire H2 pour CLI

    Téléchargez et exécutez le programme d'installation approprié .
    Assurez-vous d'ajouter Liquibase à votre PATH.
    Copiez le fichier inclus examplesrépertoire à l'emplacement requis.
    Ouvrez votre CLI et accédez à votre examples/sqlou examples/xmlannuaire.
    Démarrez la base de données H2 incluse avec le liquibase init start-h2commande.
    Exécutez le liquibase updatecommande.
    vous le souhaitez, suivez l'invite de votre e-mail pour vous inscrire à Liquibase Hub .
    Exécutez le liquibase historycommande.
    Si vous avez saisi votre adresse e-mail, vérifiez le lien du rapport et la sortie du historycommande pour voir qu'ils correspondent.

Découvrez également comment démarrer avec Liquibase en quelques minutes ou consultez notre l'installation de Liquibase pour plus de détails.
Documentation

Visitez le documentation de Liquibase pour trouver des informations sur le fonctionnement de Liquibase. 
