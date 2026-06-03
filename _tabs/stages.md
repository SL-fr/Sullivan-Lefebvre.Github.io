---
layout: page
title: Stages
icon: fas fa-briefcase
order: 5
---
# Stage de 1ère année — BTS SIO SISR

## Assistant Administrateur Réseau et Système
Du 11 mai au 12 juin 2026, j’ai effectué mon stage de première année au sein du Service Informatique de la Mairie de Caudry, situé à Caudry (Nord).

La Mairie de Caudry est une **collectivité territoriale** qui gère un parc informatique complexe pour assurer la continuité des services publics de la commune. Le service informatique pilote l'ensemble des infrastructures serveurs, le réseau local et distant, ainsi que le support de proximité pour l'ensemble des agents municipaux.

Placé sous la tutelle officielle du Directeur des Systèmes d'Information (DSI), j'ai principalement été encadré au quotidien par le Responsable des Systèmes d’Information (RSI) suite au départ en congés du DSI dès le troisième jour de mon accueil. J'ai également travaillé en étroite collaboration avec le technicien informatique sur les interventions de proximité, ainsi qu'aux côtés d'une équipe d'électriciens lors de chantiers d'infrastructure réseau. Cette configuration terrain m'a permis de développer rapidement mon autonomie, de comprendre la coordination entre différents corps de métier et de découvrir des architectures d'envergure.

---

## Mes Réalisations Effectuées

Pendant mon stage, j’ai mené plusieurs missions concrètes allant du support utilisateur à l’administration d'infrastructure. Voici un aperçu des principales tâches réalisées, structurées par grands domaines d'intervention :

### 1. Audit, Cartographie et Gestion du Patrimoine
> **Compétence ciblée :** Gérer le patrimoine informatique

* **Audit de conformité d'un cluster de production :** Intervention et vérification annuelle d'un cluster Proxmox VE (PVE) majeur composé de 15 nœuds afin de contrôler la haute disponibilité.
* **Mise à jour du Schéma Directeur (Schéma A0) :** Collecte exhaustive des données physiques et logiques du réseau (nommage, ports, adressage) pour concevoir un tableur Excel technique complet, ayant servi de base à la mise à jour réglementaire de la cartographie réseau A0 de l'organisation.
* **Modélisation de l'architecture de virtualisation :** Conception, en collaboration avec le RSI, d'un schéma d'infrastructure macroscopique identifiant les points de vulnérabilité et planifiant les évolutions de stockage (Strate 1 et Strate 2, Datastores, Namespaces).

### 2. Déploiement d'Infrastructures Réseau et Système
> **Compétences ciblées :** Mettre à disposition un service | Répondre aux demandes

* **Configuration et sécurisation de commutateurs (Switching) :** Création et gestion de VLANs (méthodes individuelles et groupées via la commande `range`) sur 3 switchs distincts. Durcissement de la sécurité par le nommage et la désactivation (*shutdown*) des ports inutilisés, et test d'interconnexion à travers 2 firewalls existants.
* **Déploiement d'un sous-réseau local (LAN) :** Installation physique et logique d'un routeur, d'une imprimante réseau et de postes clients pour rendre opérationnels les services de numérisation et d'impression locaux.
* **Optimisation de la couverture sans fil :** Configuration et positionnement stratégique d'un répéteur Wi-Fi pour éliminer les zones blanches au deuxième étage de la structure.
* **Chantier d'infrastructure et câblage cuivre :** Participation active, en coordination avec le technicien informatique et les artisans électriciens, au repérage topologique, au tirage de câbles, à la pose et au raccordement de prises réseau RJ45 de A à Z sur un site de la Mairie de Caudry.

### 3. Maintenance, Support et Sécurité des Données
> **Compétences ciblées :** Gérer des sauvegardes | Répondre aux incidents

* **Expertise et diagnostic de supports de stockage (24 To) :** Diagnostic approfondi de deux disques durs de 12 To suspectés de panne à l'aide de CrystalDiskInfo (analyse S.M.A.R.T.), HD Tune (test de surface secteur par secteur) et LinuxReader (analyse de la cohérence de la partition NTFS). Identification d'une panne liée au châssis externe et non aux disques.
* **Sécurisation et Sanitisation (RGPD) :** Application des normes de sécurité par le lancement d'un effacement irréversible des données via l'algorithme *PRNG Stream* pendant 48 heures avant réutilisation des supports.
* **Administration de serveurs de sauvegarde :** Installation complète, intégration des disques de 12 To et initialisation logique de deux serveurs Proxmox Backup Server (PBS) et d'un nouvel hyperviseur Proxmox VE (PVE).
* **Support aux utilisateurs (Helpdesk) :** Résolution d'incidents matériels directement sur les postes des collaborateurs et maintenance préventive (remplacement d'ampoule de vidéoprojecteur).

### 4. Valorisation de l'Identité Professionnelle
> **Compétence ciblée :** Organiser son développement professionnel

* **Déploiement du Portfolio :** Création et hébergement de mon site professionnel via GitHub Pages et le framework Jekyll (Thème Chirpy Starter).
* **Optimisation Web et intégration d'outils :** Traduction complète de l'interface en français via l'intégration de fichiers de locales (`fr-FR.yml`), implémentation d'un formulaire de contact sécurisé connecté à l'API Formspree, intégration de mon CV téléchargeable et structuration des sections projets et compétences.

---

## Remerciements

Je tiens à remercier chaleureusement le Directeur des Systèmes d'Information (DSI) pour son accueil initial, le Responsable des Systèmes d’Information (RSI) pour sa pédagogie, ainsi que le technicien de terrain et les équipes d'électriciens pour m'avoir intégré aux chantiers, partagé leur savoir-faire et accompagné lors des interventions quotidiennes. Merci également à mes professeurs de l'Ensemble Saint-Luc pour leur suivi rigoureux durant cette première année.
