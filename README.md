# 1.INTRODUCTION:
## 1. Objectif du document:
##### *Ce document stratégique vise à définir de manière précise et complète les objectifs, les fonctionnalités et les exigences de notre système de gestion de bibliothèque informatisé. En concentrant nos efforts sur la création d'une solution moderne et efficace, nous aspirons à rationaliser les opérations bibliothécaires, offrir une expérience utilisateur exceptionnelle et positionner notre bibliothèque à l'avant-garde de la gestion documentaire.*
## 2. Contexte du projet:
##### *Le contexte de notre projet de gestion de bibliothèque s'inscrit dans la volonté d'optimiser et de moderniser les processus au sein de notre institution. Face à l'évolution rapide de la technologie et aux besoins croissants de nos usagers, la bibliothèque reconnaît la nécessité de passer d'un système de gestion manuelle à une plateforme informatisée. L'objectif est de garantir une gestion plus efficace de notre collection diversifiée de livres, de simplifier les opérations d'emprunt et de retour, et d'améliorer l'expérience globale des utilisateurs.*
## 3. Parties prenantes et leurs rôles:
##### 1.Clients:
 - #####    *Les clients sont les utilisateurs finaux de l'application, cherchant à emprunter des livres, faire des demandes, et interagir avec la collection de la bibliothèque.*
##### 2.Administrateur de la Bibliothèque :
  - #####   *L'administrateur est responsable de la gestion globale du système et de la supervision des opérations de la bibliothèque.*
##### 3.Développeurs et Équipe Technique :
  - #####    *L'équipe technique est chargée de concevoir, développer, et maintenir l'application.*
# 2. Présentation du projet:
## 1. Description générale du projet:
##### *L'application de gestion de bibliothèque, développée avec Angular pour le frontend et ASP.NET pour le backend, représente une avancée significative dans l'optimisation de nos opérations bibliothécaires. Cette solution moderne offre aux utilisateurs une interface conviviale pour explorer et emprunter des livres, tandis que l'administrateur dispose d'un tableau de bord complet pour gérer la collection, superviser les emprunts, et communiquer efficacement avec les utilisateurs. Avec une architecture robuste et réactive, notre application vise à améliorer l'expérience des clients tout en offrant à l'administrateur les outils nécessaires pour une gestion proactive et efficiente de la bibliothèque.*
## 2. Buts et objectifs:
- ##### *Mettre en œuvre un système automatisé pour la gestion des livres, des utilisateurs et des transactions, réduisant ainsi la dépendance aux processus manuels.*
- ##### *Simplifier le processus d'emprunt et de retour des livres pour les utilisateurs, en fournissant une interface conviviale et intuitive.*
- ##### *Établir un mécanisme de communication efficace entre l'administrateur et les utilisateurs, en particulier pour les rappels de retours en retard et la gestion des pénalités.*
- ##### *Mettre en place des mesures de sécurité robustes pour protéger les données des utilisateurs, garantissant ainsi la confidentialité et l'intégrité de l'information.*
- ##### *Implanter un système de pénalités pour les retours en retard, avec des notifications automatiques et la possibilité de bloquer temporairement les utilisateurs en cas de non-paiement.*
# 3. Contexte:
## 1. Environnement dans lequel le projet sera mis en œuvre:
##### *L'application de gestion de bibliothèque sera déployée dans un environnement technologique moderne et adaptable. Le backend, basé sur ASP.NET Core, reposera sur des serveurs performants, potentiellement hébergés en interne ou sur le cloud. Les données seront stockées dans une base de données relationnelle compatible avec ASP.NET Core.*

##### *Le frontend sera développé en Angular, offrant une expérience utilisateur intuitive. La sécurité des données sera assurée par des protocoles stricts, tandis que des services de messagerie électronique seront intégrés pour les notifications automatiques.*

##### *Le déploiement continu via Git facilitera les mises à jour, et l'évolutivité sera prise en compte pour accompagner la croissance. Des procédures de maintenance régulières et un plan de support technique garantiront la stabilité et la fiabilité de l'application. Cet environnement vise à offrir une expérience utilisateur optimale tout en respectant les normes de sécurité et de confidentialité.*
## 2. Contraintes et dépendances avec d'autres projets ou systèmes:
- ##### Délai de trois semaines :*Le projet doit être réalisé dans un délai de trois semaines, imposant une pression temporelle considérable pour la conception, le développement, les tests et le déploiement.*
- ##### Équipe Restreinte de Deux Personnes:*L'équipe de projet est composée de seulement deux membres, limitant la capacité de travail simultané et nécessitant une gestion efficace des tâches et des compétences.*
- ##### Tests et Validation Accélérés :*En raison du délai court, les phases de tests et de validation seront accélérées, nécessitant une planification minutieuse pour assurer la qualité du produit final.*
# 4. Besoin du client:
## 1. Exigences fonctionnelles:
- ##### Authentification :*L’application doit permettre aux utilisateurs de s'inscrire, de se connecter et de gérer leur compte.*
- ##### Gestion des Livres : *Ajout, suppression et mise à jour des informations des livres.*
- ##### Catégorisation :*Attribution et gestion des catégories pour organiser la collection.*
- ##### Gestion des Utilisateurs :*Approbation des nouveaux utilisateurs et consultation de la liste des inscrits.*
- ##### Emprunts et Retours :*Processus d'emprunt, enregistrement des retours, et gestion des pénalités.*
- ##### Notifications et Communication :*Envoi de notifications par e-mail et communication avec les utilisateurs.*
- ##### Gestion des Blocages Utilisateurs :*Capacité de bloquer temporairement les utilisateurs en cas de non-paiement, avec levée possible du blocage après paiement.*
## 2. Exigences non fonctionnelles:
- ##### Performances :*Temps de réponse rapide même en cas de charge élevée.*
- ##### Sécurité : *Cryptage des données et protection contre les attaques.*
- ##### Compatibilité :*Compatibilité avec les principaux navigateurs web.*
- ##### Fiabilité :*Fiabilité minimisant les temps d'arrêt imprévus.*
- ##### Disponibilité :*Accès 24/7 .*
# 5. Portée du projet:
## 1. Inclus:
- ##### *Ajout, mise à jour et suppression d'informations sur les livres.*
- ##### *Fonctionnalité de catégorisation pour une organisation efficace de la collection.*
- ##### *Approbation des nouveaux utilisateurs et consultation de la liste des inscrits.*
- ##### *Processus complet d'emprunts, de retours, et calcul des pénalités pour retards.*
- ##### *Notifications automatiques par e-mail pour les rappels de retours en retard et autres communications.*
- ##### *Blocage temporaire des utilisateurs en cas de non-paiement, avec levée possible du blocage après paiement.*
- ##### *Compatibilité avec les principaux navigateurs web (Chrome, Firefox, Safari) pour maximiser l'accessibilité.*
## 2. Exclus:
- ##### *L'intégration avec d'autres systèmes institutionnels n'est pas incluse dans cette phase du projet.*
- ##### *Des fonctionnalités avancées de gestion des utilisateurs, telles que la hiérarchie des rôles, ne sont pas comprises dans la portée initiale.*
- ##### *Un module de discussion entre utilisateurs n'est pas envisagé dans cette version.*
# 6. Contraintes:
## 1.Contrainte Temporelle :
##### *Le projet doit être développé et mis en œuvre dans un délai strict de trois semaines, imposant une pression temporelle significative sur toutes les phases du projet.*
## 2. Interopérabilité avec des Systèmes Existant :
##### *L'application doit s'interfacer de manière harmonieuse avec d'autres systèmes institutionnels existants, imposant des contraintes d'interopérabilité.*
## 3. Ressources Humaines Limitées :
##### *L'équipe de développement est composée de seulement deux membres, ce qui peut limiter la capacité de travail simultané et influencer la rapidité d'exécution des tâches.*
# 7. Critères d'acceptation:
+ ### Conditions de réussite:
- ##### *La livraison complète de l'application de gestion de bibliothèque doit être effectuée dans les trois semaines spécifiées.*
- ##### *Toutes les fonctionnalités essentielles, telles que la gestion des livres, des utilisateurs, des emprunts et retours, doivent être implémentées conformément aux spécifications.*
- ##### *L'interface utilisateur doit être intuitive, conviviale et répondre aux attentes des utilisateurs pour une expérience positive.*
- ##### *Les mesures de sécurité mises en place doivent garantir la confidentialité des données des utilisateurs et résister à d'éventuelles menaces.*
- ##### *La satisfaction des utilisateurs doit être évaluée par des retours positifs et une utilisation régulière de l'application.*
- ##### *L'architecture de l'application doit montrer sa capacité à évoluer facilement pour répondre à des besoins futurs.*
# 8. Livrables:
+ ### Produits ou résultats attendus:
- ##### *L'application complète développée, comprenant toutes les fonctionnalités spécifiées dans le cahier des charges.*
- ##### *Une documentation détaillée comprenant les manuels d'utilisation, les guides de maintenance et toute autre information pertinente.*
- ##### *Les résultats des tests de performance, confirmant la réactivité optimale de l'application.*
- ##### *Des retours d'utilisateurs et une évaluation de la satisfaction globale du public cible.*
- ##### *Un bilan du projet, comprenant des enseignements tirés, des recommandations et des perspectives pour de futures améliorations.*
# 9. Planning:
- ##### Phase de Préparation :*2jours*
- ##### Phase de Conception :*3jours*
- ##### Phase de Développement :*15jours*
- ##### Phase de Tests et Validation:*2jours*
# 10. Ressources :
## 1. Personnel :
- ##### Développeur Frontend :*BOULOUDEN Ouissal*
- ##### Développeur Backend :*CHKAIFI Zineb*
- ##### Base de Données :*BOULOUDEN Ouissal - CHKAIFI Zineb*
- ##### Testeur :*BOULOUDEN Ouissal - CHKAIFI Zineb*
## 2. Équipements :
- ##### *Ordinateurs de Développement pour chaque membre de l'équipe.*
- ##### *Serveurs pour le Développement, les Tests et la Production.*
### 3. Logiciels :
- ##### *Visual Studio Code pour Angular.*
- ##### *Visual Studio pour ASP.NET.*
- ##### *Microsoft SQL Server comme Système de Gestion de Base de Données.*
- ##### *Jira comme outil de Gestion de Projet.*
# 11. Communication:
## 1. Méthodes de communication:
##### *Réunions régulières en personne ou virtuelles, messagerie instantanée, e-mails.*
## 2. Fréquence de communication:
##### *Réunions hebdomadaires pour le suivi de l'avancement, discussions ad hoc au besoin, mises à jour quotidiennes via la messagerie instantanée.*
# 12. Gestion des risques:
## 1. Identification des risques potentiels:
- ##### *Retard dans le Développement*
- ##### *Problèmes de Compatibilité*
- ##### *Non-alignement des fonctionnalités avec les attentes des utilisateurs.*
- ##### *Vulnérabilités de sécurité non identifiées, attaques malveillantes.*
## 2. Stratégies d'atténuation:
- ##### *Planification réaliste des délais initiaux.*
- ##### *Tests approfondis sur plusieurs plates-formes dès le début du développement.*
- ##### *Implémentation d'un processus de rétroaction continue.*
- ##### *Audit régulier de la sécurité du code et des configurations.*
# 13. Conditions contractuelles :
##### *Le contrat du projet de gestion de bibliothèque s'articule autour de termes et conditions détaillés, couvrant des aspects cruciaux tels que les objectifs du projet, les délais, le budget, la propriété intellectuelle, la sécurité des données, et la gestion des changements. Des dispositions concernant les pénalités, les récompenses, la confidentialité, la résiliation du contrat, et la signature formelle des parties sont également incluses. Ces conditions contractuelles offrent une base solide pour une collaboration transparente et réussie entre les parties prenantes, assurant ainsi la conformité aux attentes et une réalisation fructueuse du projet.*
# 14. Validation :
- ### Processus de validation :
##### *Pour notre projet de gestion de bibliothèque, nous avons instauré un processus de validation du cahier des charges, axé sur des réunions approfondies avec l'équipe de développement et les parties prenantes clés. Ces sessions ont permis de clarifier les exigences et de répondre aux questions, favorisant une compréhension commune. Les commentaires des participants ont été sollicités lors de sessions formelles de rétroaction, intégrés ensuite à des révisions itératives du cahier des charges. La satisfaction de toutes les parties prenantes a été confirmée par la signature formelle des représentants autorisés, symbolisant l'acceptation mutuelle des termes du document. Ce processus rigoureux garantit une base solide pour le développement de notre application de gestion de bibliothèque, avec un alignement clair sur les objectifs du projet.*
