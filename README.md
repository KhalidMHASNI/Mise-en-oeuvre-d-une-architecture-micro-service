# Mise en oeuvre d'une architecture micro-service
1. Créer le micro service Customer-service :

![image](https://github.com/KhalidMHASNI/Mise-en-oeuvre-d-une-architecture-micro-service/assets/82038554/2d0dc2aa-66b9-4b01-94d7-961357e3dee4)

• Créer l’entité Customer<br>
![image](https://github.com/KhalidMHASNI/Mise-en-oeuvre-d-une-architecture-micro-service/assets/82038554/b682cb6b-7d3e-46e7-a95b-2efe51b0d684)

• Créer l’interface CustomerRepository basée sur Spring Data 

![image](https://github.com/KhalidMHASNI/Mise-en-oeuvre-d-une-architecture-micro-service/assets/82038554/256aeff6-e356-47c8-b96c-62ba881cec60)

• Déployer l’API Restful du micro-service en utilisant Spring Data Rest 

![image](https://github.com/KhalidMHASNI/Mise-en-oeuvre-d-une-architecture-micro-service/assets/82038554/ac2639ca-b4fc-4aa2-a5db-1981c593e9a7)

• Tester le Micro service

![image](https://github.com/KhalidMHASNI/Mise-en-oeuvre-d-une-architecture-micro-service/assets/82038554/aa7a26ea-9479-43bc-9e5b-2b60e84cdc4e)
![image](https://github.com/KhalidMHASNI/Mise-en-oeuvre-d-une-architecture-micro-service/assets/82038554/ac1c1b7f-c3a9-4edf-bfa3-ef2cec932e7c)

3. Créer le micro service Inventory-service 
      • Créer l’entité Product 
      • Créer l’interface ProductRepository basée sur Spring Data 
      • Déployer l’API Restful du micro-service en utilisant Spring Data Rest 
      • Tester le Micro service
3. Créer la Gateway service en utilisant Spring Cloud Gateway
  1. Tester la Service proxy en utilisant une configuration Statique basée
  sur le fichier application.yml
  2. Tester la Service proxy en utilisant une configuration Statique basée
  une configuration Java
4. Créer l’annuaire Registry Service basé sur NetFlix Eureka Server
5. Tester le proxy en utilisant une configuration dynamique de Gestion des
routes vers les micro services enregistrés dans l’annuaire Eureka Server
6. Créer Le service Billing-Service en utilisant Open Feign pour
communiquer avec les services Customer-service et Inventory-service
7. Créer un client Angular qui permet d’afficher une facture
