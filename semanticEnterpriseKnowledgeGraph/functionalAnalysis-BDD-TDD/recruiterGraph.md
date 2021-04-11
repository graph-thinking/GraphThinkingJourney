# Recruiter Graph Functional Analysis

Good video on KG in recruitment - https://www.youtube.com/watch?v=NFQycDIDocg


Context - Recruitment challenge and trainings in entreprise

* Identify good resources

* Identify potentials of each collaborator 

* Build a common target 

* Lead the collaborator towards an achieved competence

* Fidéliser the collaborator

* Valorise the collaborator

Client's problem definition 

Target 1: Faire monter en compétence le groupe, dirigé vers un objectif commun, en tenant comptant du savoir et des connaissances techniques et fonctionnelles de la somme des individualités (relier les skills à l’offre e-learning)

Target 2: Proposer un parcours de formation personnalisé pour chaque collaborateur en adéquation avec la trajectoire définie par l’entreprise

Target 3: Permettre à l’entreprise de connaitre l’ensemble des compétences maitrisées dans l’entreprise à une date donnée et être en mesure de définir les objectifs futurs ainsi que les jalons associés

Why graph thinking ?

The tool based on graphs (with standard technologies) open to a new paradigme: data connections.
L’ensemble des données relatives aux Skills, secteurs et domaines d’applications, process de formation et projets généraux de l’entreprise, sont reliées entre elles et modéliser sous forme de Graphes. 
  un middleware, pouvant se « greffer » à tout type d’environnement et Base de données: Microsoft, Oracle, SAP, Postgre… et exposé via GraphQL API, ou si necessaire via RESTful API (mais potentiel plus limité)
La migration est transparente, sans impact, et évolue en même temps que le système du client

Approach (why, how what):

Step 1 : Competence model and acquisition of each collaborator (CV parsing or other sources) 

Step 2 : Distance between each key competence (indirect competence - competence clusters) and learning path computation

Step 3 : Competence comparison - visual and quantitatively « Skills collaborateurs/Skills désirées » (« learning path »)

Step 4: Learning Path Proposal, détaillé dans le temps, selon les compétences du collaborateur, du poste occupée et des projets portés par la société (« graphe de dépendances »)

Main features:

Standardise l’ensemble de la connaissance
Matching CV avec le poste ouvert ou compétences désirés
Clustering de compétences ou profil (CV/mission, CV/CV, Mission/mission)
Synthèse des compétences les plus recherchées aujourd’hui et prédiction des tendances/jobs à venir (algorythme prédictif, web scraping, …) 
Réalisation d’un programme de formation/montée en compétences (« learning path ») en fonction des tendances ou des projets en perspectives de l’entreprise
Evaluation des compétences moyenne de la société par rapport à la compétence moyenne désiré à l’avenir: design de la courbe d’apprentissage de chaque profil de la société et prédiction des besoins en ressources supplémentaires.

Inference Engine - a global vision of all the training enterprise project :

The engine allows to define rules and to arrive to conclusion in order to 

gérer simultanément l’ensemble des projets de l’entreprise, en incluant tous les départements 
manager et optimiser l’intégralité des ressources dans le temps, 
établir un programme de formation personnalisé à chaque collaborateur, et élever ainsi votre société au rang voulu à une date fixée
mieux appréhender votre roadmap pour 2022, 2023, …

Added Value :
Performance backend: Intuitivité  et vitesse décuplées
Vision globale de l’entreprise (projection des compétences de la société dans le temps)
Allocation du budget sur le payoff (objectif quantifiable) de la boite entière selon ses objectifs sur plusieurs années , non pas uniquement  sur un secteur ou departement
Ex : championnat echec/freestyle chess mode 
  

EPICS with User Story

* Define competence and competence data model

* Establish competence distance - similarity

* Establish learning path

* E-recruiter Engine 

* https://beelance.io/
