# Quete_logs_Windows


## 1) Création vue personalisée dans l'observateur d'événements avec le nom : Surveillance DNS

![Logs Windows.png](https://github.com/Hebus79/Quete_logs_Windows/blob/main/image1.png)

## 2) Configuration avec les critères demandés 

* Niveaux à surveiller

Critique (1)

Erreur (2)

Avertissement (3)

Information (4) - Pour les démarrages/arrêts


 * Sources d'événements à inclure :

DNS-Server-Service: Pour les opérations du serveur DNS

DNS Client Events: Pour les événements côté client


 * Événements critiques (ID principaux)

2: Démarrage du serveur DNS

4: Arrêt du serveur DNS

409: Erreur de résolution de nom

501-502: Échec de chargement de zone

6001-6002: Problèmes de réplication DNS


   ![Logs Windows.png](https://github.com/Hebus79/Quete_logs_Windows/blob/main/image2.png)


## 3) Vue au format XML

 ![Logs Windows.png](https://github.com/Hebus79/Quete_logs_Windows/blob/main/image3.png)
