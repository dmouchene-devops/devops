 # Sommaires
 ## Section **INTRO** : Introduction intégration continue
 * Prerequis & public visé, objectif 
 * Augmenter la confiance, diminuer les régressions, gagner du temps
 * C'est quoi l'intgération continue,à quoi ca sert ? d'où ça vient? qu'est ce qu'elle apporte dans un projet de Dev? Se référer au livre blanc (ajouté au git)
 * les 7 étapes de mise en oeuvre intégration continue
 * La place des tests unitaires / intégration :
 * Livraison en continue, déploiement en continue

 ## Section **Git** avec Git 
 * Programme à mettre par Djamel
 
 ## Section **Build** avec Maven 
 * Conventions, Coordonnées
 * sections fichier POM.xml
 * Squelettes Projet maven
 * Notions de Phase, plugin, goal
 * gestion de dépendances
 * Repository local, distant
 * Multi-modules : héritage, composition
 * Profils et filtrage de ressources
 * Optimisations pom.xml : dependencyManagement, pluginManagement
 * Création de Release
 * Déploiement : distributionManagement
 * Tests unitaires avec JUnit, Mockito, TestNG
 * Automatiser tests unitaires, tests d’intégration
 * Tests fonctionnels tests Selenium WebDriver
 * Phase de test et - integation-test
 * -pre-integation-test et ‘post-interation-test »
 * Ignorer les tests
 * Couverture de code
 * Résoudre les problèmes de lenteur des tests
 * BDD avec concordion
 
 ## Section **Repository Manager** avec Nexus
 * Définition et valeur ajouté d’un >Repository d’entreprise
 * Installation Nexus
 * Roles Proxy, groups
 * Role pour bande passante
 * gestion des livraisons releases / snapshot
 * Intégration Maven / Nexus
 * balise mirror et server dans - settings.xml
 * balise distributionManagement dans - pom.xml
 * Gérer les purges
 
 ## Section **Intégration continue**, c'est quoi?
 
 
 ## Section **Intégration continue** avec Jenkins
 * Valeur ajoutée d’un serveur d’intégration continue
 * offre du marché : logiciels pour l’intégration continue
 * Installation et premier Job
 * Maître esclave : rôle des agents
 * Actions - pre-build,  - post-build
 * Afficher les résultats de test dans Jenkins
 * Intégration avec gestionaire de source ( - Git, - SVN)
 * Configuration Variables Système et Propriétés globales
 * Pipeline , JenkinsFile
 * Comparaison avec Atlassian Bamboo : Plan + Stage + Job + Task
 
 ## Section **Métriques / Qualité du code** avec Sonar : Optionnel
 * Bugs, Vulnérabilité , ‘Code smell’
 * Analyse de code via Maven : mvn sonar:sonar
 * Plugin Eclipse SonarLint
 * Comprendre le Sonar Scanner
 * Notion de ‘Dette technique’
 * Analyse résultats de Tests unitaires et Intégration
 * Profils de règle spécifique
 * Quality Gates
 
