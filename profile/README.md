![image](https://github.com/user-attachments/assets/1e90b62a-6fd2-4d01-a35b-bdcf2540bcbd)
# Twittix 


## Présentation du projet 
Twittix est un réseau social de micro-bloging révolutionnaire et totalement original. 
Les utilisateurs peuvent poster du texte, suivre des utilisateurs, intéragir avec les posts de leur feed, et envoyer des messages.

## Composition de l'équipe
### Frontend

**Gaël** : 
  - Rôles : UX/UI Designer, Développeur Frontend 
  - [twittix-front-user](https://github.com/projet-specialite-groupe-2/twittix-front-user)
  - [twittix-front-admin](https://github.com/projet-specialite-groupe-2/twittix-front-admin)
    
**Swann** : 
  - Rôles : Architecture Frontend, Développeur Frontend
  - [twittix-front-user](https://github.com/projet-specialite-groupe-2/twittix-front-user)
  - [twittix-front-admin](https://github.com/projet-specialite-groupe-2/twittix-front-admin)

**Florent** : 
  - Rôle : Développeur Frontend
  - [twittix-front-user](https://github.com/projet-specialite-groupe-2/twittix-front-user)
  - [twittix-front-admin](https://github.com/projet-specialite-groupe-2/twittix-front-admin)


### Backend

**Kevin** : 
  - Rôles : Développeur Backend (Authentification) :
  - [twittix-auth-api](https://github.com/projet-specialite-groupe-2/twittix-auth-api)

**Léo** : 
  - Rôles : Architecture Backend, Développeur Backend (Symfony)
  - [twittix-api](https://github.com/projet-specialite-groupe-2/twittix-api)

**Pierre** : 
  - Rôles : Développeur Backend, Architecture Backend (Symfony)
  - [twittix-api](https://github.com/projet-specialite-groupe-2/twittix-api)

**Killian**: 
- Rôle : Développeur Backend (Service de Recommandation)
- [twittix-recommandation-api](https://github.com/projet-specialite-groupe-2/twittix-recommandation-api)

### Infrastructure

**Théo** : 
  - Rôles:  Cloud Architect, Dev Ops
  - [twittix-infrastructure](https://github.com/projet-specialite-groupe-2/twittix-infrastructure)

**Aurélien** : 
  - Rôles : Cloud Architect, Dev Ops, Monitoring
  - [twittix-infrastructure](https://github.com/projet-specialite-groupe-2/twittix-infrastructure)

**Raphaël** : 
  - Cloud Architect, Dev Ops

### Tests / Contrôles Qualité

**Swann, Florent, Gaël** : testeurs frontend

**Kevin, Leo, Pierre, Killian** : testeurs backend

**Aurélien, Théo, Raphaël** : testeurs infrastructures


### Gestion de projet

  **Raphaël** :
   - Rôles: Product Owner, Scrum Master

## Présentation de la CI/CD

## Schéma de l'architecture micro-service
![micro-services drawio](https://github.com/user-attachments/assets/c33cc1ea-a4a4-4b18-86a5-66237666f040)



## Liste des services GCP utilisés et estimation du coût

### Backend, Service de Suggestion, Service d'Authentification, Frontend Utilisateur, Frontend Administrateur
- Service utilisé : **Cloud Run**
  - Description : **Cloud Run** permet d’exécuter des conteneurs en mode serverless. Chaque service est déployé dans un conteneur individuel, ce qui permet une gestion flexible et automatique des ressources.
  - Avantages :
    - Scalabilité automatique : Le nombre de instances de chaque service augmente ou diminue en fonction du trafic.
    - Pay-as-you-go : Nous ne payons que pour les ressources que nous utilisons, ce qui optimise les coûts.
- Estimation des coûts :
  - Le coût dépend principalement de la durée d’exécution et des ressources (CPU et mémoire) allouées à chaque conteneur.

### Base de données relationnelle (SQL)
- Service utilisé : **Cloud SQL**

### Base de données en cache (Redis)
- Service utilisé : **Memory Store for Redis**

### Surveillance et Logging
- Services utilisés : **Cloud Monitoring et Cloud Logging**
  
## "Mode d'emploi"
Tuto sur les différents utilisation de votre app  
(à faire au fil de l'eau au fur et à mesure des mise en prod)



