# Présentation

Vous trouverez dans ce document l'ensemble des éléments observable chez un membre d'une équipe agile.

# Principes généraux

Les éléments que l'on peut observer dans une équipe agile ont été regroupé par grand principe. Les voici :

-

# Cartographie des observables

Quand nous parlons d'existence d'atelier, c'est au minimum une fois par mois.


| Observables                                  | Product Owner | Manager | Déveoppeur | 
|--                                            |--             |--       |--          |
| Le manifeste agile est connue et partagé |
| Il existe des ateliers de collecte des besoins avec biz-dev-ops |
| Il existe des ateliers de priorisation du backlog |
| Il existe un backlog d'histoires utilisateurs priorisés |
| Les histoires utilisateurs sont regroupés en MVE |
| Les histoires utilisateurs décrive le quoi le pour quoi et le pour qui |
| Métrologie |
| Il existe une projection de la fin du travail |
| Le besoin est détaillé sous forme d'exemple |
| Les exemples sont executables |
| Les exemples sont coconstruit avec biz-dev-qa |
| Les fonctions sont livrés au fils du temps en production et activés par MVE |
| Le PO annime la communauté des parties prenants |
| Outils de prise de décisions |
| L'équipe réduit systématiquement le travail en cours à son strict minimum |
| Le business modèle et partagé, chacun est capable de prendre une décision et d'en informer les autres |
| La livraison est un non événement |
| Pratiques de kata au moins une fois par semaine |
| Lit sur son sujet (tech, po, etc.) au moins une fois par semaine |
| Le standar de code a été défini en équipe et est régulièrement mis à jour |
| Les outils sont standardisés et sont régulièrement challengés par l'équipe |
| Les dépendances sont gérés automatiquement |
| Les constructions sont automatiques |
| L'audit du code est automatique |
| Toutes les modifications de code sont historisé et versionnés |
| Les développements des membres de l'équipe sont très régulièrement confrontés les unes aux autres |
| Il existe une véritable stratégie de teste : TU, TA, TI, TF |
| La quantité de TU est très supérieur à la quantité de TI |

# En vrac


## Géstion de la valeur

| besoins utilisateur vs développement produit                | Business Value Burn up, MMF, Kata Slicing |
| partage de la valeur de chaque petit bout de fonctionnalité | limiter le travail en cours |

## Production du code

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
