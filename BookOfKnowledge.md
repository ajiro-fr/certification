# Présentation

# Principes généraux

Savoir être et savoir faire ou pratiques et principes ?

# En vrac

## Gestion des besoins

| Principes                                  | Pratiques |
|--                                          |--         |
| collecte des besoins                       | atelier de travail avec biz-dev-ops |
| affinage et priorisation de la liste       | affinage du backlog avec po / biz /dev  / ops |         
| pas de surprise en production              | Métrologie |
| rythme prévisible                          | Métrologie, burndown |
| Expression du besoins sous forme d'exemple | BDD avec dev / qa / biz |
| Délivrer toujours plus vite en continue    | feature flag |

## Géstion de la valeur

| Principes                                                   | Pratiques |
|--                                                           |--         |
| une équipe concentré sur le minimum de taches               | Existence du backlog |
| avec une bonne compréhension du pour quoi et du pour qui    | Découpage en histoire utilisateur |
| besoins utilisateur vs développement produit                | Business Value Burn up, MMF, Kata Slicing |
| partage de la valeur de chaque petit bout de fonctionnalité | limiter le travail en cours |
| chacun est capable de prioriser et d'informer de la décision| business modèle paratagé entre biz-dev-ops
| La livraison de valeur en continue est une seconde nature   | 

## Production du code

| Principes                                          | Pratiques |
|--                                                  |--         |
| Un environnement technique partagé                 | Standar de code, standar d'outils |
| intégration continue                               | automatisation des dépendances, automatisation des constructions, audit de code automatique |
| une gestion de la configuration                    | gestion de version |
| tests automatisés                                  | XUnit |
| Réduire le niveau d'insertitude des développements (chacque sprint est prévésible) | TDD, Stratégie de test, Clean code, Legacy refactoring, katas |
| L'infrastructure est partagé et géré comme du code | puppet, cloud, chef, ansible
| Les mises en Production sont des nons événements   | Déploiement continue ou en 1 clic  (Docker, capistrano, etc.)
| Tester des fonctionnalités en production est simple| A/B testing, cohorte d'utilisateurs, etc.

## Amélioration continue

| Principes                                   | Pratiques |
|--                                           |--         |
| cadre et temps consacré à l'amélioration    | retrospectives, stop the line, kata |
| le partage de connaissance est une priorité | pairing, code review, temps d'apprentissages |
| les apprentissages sont scientifiques       | kata, popcorn flow, PDCA, lean startup |
| apprendre est une seconde nature            | on observe des gens qui demande de l'aide, et au moins 20% du temps dédié à l'apprentissage

## Équipe, gestion du travail

| Principes                                                                       | Pratiques |
|--                                                                               |--         |
| Équipe concentré sur la délivrance de valeur et pas sur son niveau d'occupation |
| Équipe pluridiciplinaire                                                        |
| Nombreuses interaction avec les autres équipes                                  | Give and take matrix, ateliers avec biz-dev-ops
| Équipe capable de coconstruire l'architecture                                   | tableau blanc, daily meeting |
| Les décisions sont prisent au plus proche de l'information                      | Turn the ship around
| L'équipe est capable de s'adapter à son environnement

## Leadership

| Principes                                                 | Pratiques |
|--                                                         |--         |
| autonome / auto-organisé                                  | management visuel (tableau kanban) |
| l'équipe corrige ses erreurs                              | Droit à l'erreur sans représeail   |
| chaque membre de l'équipe développe son propre leadership | host leadership |
| Autopoiesis                                               |
