<img src=../pictures/LOGO_PRINCIPAL_IUT_NANTES_CMJN.png alt="IUT Nantes" width="200"/>

# Cahier des charges fonctionnel - APPLICATION INTELLIGENTE DE SUIVI DE L'ASTHME CHEZ L'ADOLESCENT

## Entête
- Groupe de TD : TP4-1
- Date de démarrage : 3 avril 2024
- Version : 1.1
- Destinataire : Said EL MAMOUNI


| Nom      | Prénom   | mail                                |
|----------|----------|-------------------------------------|
| Lecomte  | Benjamin | benjamin.lecomte@etu.univ-nantes.fr |
| Lerouley | Clement  | clement.lerouley@etu.univ-nantes.fr |
| Drouhot  | Loris    | loris.drouhot@etu.univ-nantes.fr    |
| Marquis  | Clement  | clement.marquis@etu.univ-nantes.fr  |


## 1. Présentation générale du problème
Le problème du suivi de l'asthme chez l'adolescent est un problème majeur de santé publique. En effet, l'asthme est une 
maladie chronique qui touche de nombreux adolescents. Il est donc important de pouvoir suivre l'évolution de la maladie 
pour adapter le traitement en conséquence. C'est pourquoi nous avons décidé de créer une application intelligente de 
suivi de l'asthme chez l'adolescent. Cette application permettra de suivre l'évolution de la maladie et de proposer des 
traitements adaptés en fonction des symptômes. Elle permettra également de suivre l'évolution de la maladie sur le long 
terme et de prévenir les crises d'asthme. L'application sera disponible sur smartphone et tablette et sera destinée aux 
adolescents asthmatiques et à leur entourage.

### 1.1 Projet

#### 1.1.1 Finalités
Le but du projet est de développer une application qui puisse offrir un suivi du patient personnalisé grâce aux capteurs 
utilisé ainsi que l'intelligence artificielle qui permettra de faire des prédictions sur l'asthme du patient dont il est 
question. Ainsi, l'application permettra d'identifier plus rapidement et simplement le stade de sévérité d'asthme du patient, 
elle permettra également de déterminer différents profils de patient grâce à leurs capteurs ainsi qu'à leurs éventuelles 
informations personnelles récoltées. En effet d'après le numéro 25 du bulletin d'informations en économie de la santé, 
publié en février 2000 par le CREDES, il y est affirmé dans cet article que les gens ayant les revenus les moins élevés 
ont plus tendance à faire de l'asthme que les personnes aisées (8,5% dont le revenu du ménage est inférieur à 2000 francs 
par unité de consommation souffrent d'asthme contre 5% parmi les personnes les plus aisées). Les conditions de vie du 
patient peuvent avoir un réel impact sur son asthme, il est donc important de déterminer un profil de patient via les 
informations récolter grâce aux questionnaires et aux capteurs. Avec ces informations l'application sera en capacité de 
créer des tableaux de bords à destination des professionnels de santé en charge du patient. Pour ce qui est du traitement, 
si le patient oublie de prendre son traitement les capteurs le remarqueront et enverront un signal à l'application pour 
que celle-ci puisse prévenir le patient.

#### 1.1.2 Espérance de retour sur investissement
Pour ce qui est des espérances de retour sur investissement, il faut d'abord calculer le coût du projet pour ensuite 
pouvoir calculer les bénéfices de celui-ci. Dans un premier temps nous allons déterminer le coût du développement de 
l'application. Dans un second temps nous verrons le coût de maintenance de l'application.

### Tableau descriptif du coût de développement du projet mensuel

| Poste                                 | Coût développement application | Coût développement intelligence artificielle |
|---------------------------------------|--------------------------------|----------------------------------------------|
| Développeurs                          | 3 500,00 €                     | -                                            |
| Designer UX/UI                        | 2 250,00 €                     | 1 000,00 €                                   |
| Spécialiste en IA                     | -                              | 4 600,00 €                                   |
| Conseiller spécialiste en pneumologie | 3 000,00 €                     | 1 000,00 €                                   |
| Spécialiste en sécurité informatique  | 3 000,00 €                     | -                                            |
| Architecte logiciel                   | 6 500,00 €                     | 1 000,00 €                                   |
| Spécialiste assurance qualité         | 3 500,00 €                     | -                                            |
| Chef de projet                        | 4 000,00 €                     | 1 000,00 €                                   |
| Responsable RH                        | 2 500,00 €                     | -                                            |
| **Total**                             | **28 750,00 €**                | **7 600,00 €**                            <br/>   |

### Tableau descriptif du coût de maintenance mensuel pour chaque poste qui se rajoute au coût de développement lorsque le développement sera finis:

| Tâche                                 | Coût de maintenance |
|---------------------------------------|---------------------|
| Mise à jour régulières                | 1500,00 €           |
| Coûts de Serveur mensuel              | 200,00 €            |
| **Total**                             | **1 700,00 €**      |

Pour ce qui est des locaux, nous avons prévu de payer 1 346 € par mois pour avoir des locaux de 143m carré
au prix de 113€/m2/mois. Ce qui nous fait un total pour les coûts de développement de 35 853€/mois, 
nous avons estimé la durée de développement de l'application à environ 6 mois ce qui nous fait un total de
215 100€ pour les coûts de développements. L'objectif de l'application serait de compter 200 000 utilisateurs
pour un coût de 5€/mois pour l'abonnement. Si nous atteignons notre objectif dès la sortie de l'application 
(donc au bout des 6 mois de développement), pendant le premier mois de sa sortie, nous aurons 1 000 000 € pour le
premier mois brut. En termes de bénéfice on aurait alors 775 124 € de bénéfice pour le premier mois si on enlève les coûts de développement de l'application, 
le coût de maintenance du premier mois de l'application et le coût des locaux.

### Organisation Humaine de l'Équipe
*Tout les nom present ici sont fictifs toute resemblence avec le reel serait fortuite*

 - Maître d'ouvrage (MOA) : Said EL MAMOUNI
 - Chef de projet : Francesco CAPO
 - Développeurs :
   - Benjamin LECOMTE
   - Clement LEROULEY
   - Loris DROUHOT 
   - Clement MARQUIS
- Consultant Santé : Eryk LEKARZ
- Expert IA : Lian RENZAO
- Responsable Qualité : Dimitri KACHESTVO

### 1.2 Contexte
#### 1.2.1 Situation du projet par rapport aux autres projets de l’entreprise
Ce projet est le seul dans notre entreprise. Il représente une initiative majeure pour nous, car il s'agit de notre premier projet. 
De ce fait, il fait l'objet de toute notre attention et de tout notre investissement.
#### 1.2.2 Études déjà effectuées
Avant le début de ce projet, nous avons effectué une étude de marché pour comprendre les besoins d'une telle application.
Selon nos recherches, environ 5% de la population mondiale, soit environ 300 millions de personnes, souffrent d'asthme.
En France, cette maladie touche 3,5 millions de personnes, dont un tiers a moins de quinze ans, soit environs 1,2 million de personnes. De plus, le nombre d'asthmatiques a augmenté de plus de 40% chez 
les adolescents au cours des 20 dernières années, soit environs 23 200 personnes asthmatiques de plus chaque année. Cela représente 
pendant 20 ans près de 464 000 adolescents de plus. En ce qui concerne les technologies existantes pour le suivi de l'asthme, nous avons identifié 
plusieurs applications mobiles et dispositifs connectés sur le marché. Cependant, notre analyse a révélé qu'aucune solution existante 
ne propose une approche aussi complète et personnalisée que celle que nous envisageons pour notre application. Par exemple, 
certaines applications se concentrent uniquement sur le suivi des symptômes, tandis que d'autres se limitent à la gestion des médicaments.
De plus, peu d'applications intègrent des capteurs environnementaux et physiologiques pour une surveillance en temps réel de l'état de santé de 
l'utilisateur.
#### 1.2.3 Études menées sur des sujets voisins
Des études ont été menées sur des sujets étroitement liés à notre projet, notamment sur l'utilisation des technologies mobiles dans le domaine 
de la santé et sur les besoins spécifiques des adolescents asthmatiques.
#### 1.2.4 Suites prévues
Une fois le cahier des charges finalisé, il sera transmis à une autre équipe au sein de notre entreprise qui sera responsable du développement 
de l'application. Notre rôle dans ce projet se terminera avec la livraison du cahier des charges, mais nous resterons disponibles pour des 
clarifications ou des discussions supplémentaires si nécessaire.
#### 1.2.5 Nature des prestations demandées
La nature des prestations demandées pour ce projet comprend la recherche et la rédaction d'un cahier des charges détaillé pour une application
de suivi de l'asthme chez l'adolescent. Le développement d'une application mobile connecté pour suivre l'asthme chez l'adolescent.
#### 1.2.6 Parties concernées par le déroulement du projet et ses résultats (demandeurs, utilisateurs)
Les parties concernées par ce projet incluent notre équipe de projet, l'équipe de développement qui prendra en charge le développement de l'application,
les adolescents asthmatiques qui utiliseront l'application, leurs parents et les professionnels de santé qui pourront utiliser les données collectées par 
l'application pour améliorer le suivi et le traitement de leurs patients.
#### 1.2.7 Caractère confidentiel s'il y a lieu
Certains aspects de ce projet peuvent nécessiter la confidentialité, notamment les informations personnelles des utilisateurs et l'application et les détails spécifiques de la technologie utilisée pour le suivi de l'asthme. Ces informations seront traitées avec le plus grand soin pour garantir leur sécurité et leur confidentialité.
### 1.3 Énoncé du besoin 
L'application doit être capable de collecter des données relatives à l'asthme du client, dans ce cas, elle doit à la fois pouvoir se connecter à des appareils et capteurs qui feront cette tâche de collecte de données, de plus l'application doit fournir des questionnaires au client. Ces données doivent être analysées par l'application afin de fournir les informations nécessaires au patient, parent du patient et/ou professionnel de santé.
Un suivi régulier du traitement et du parcours de soin doit aussi être fourni.
Aussi, un tableau de bord destiné au professionnel de santé doit être inclus dans l'application pour suivre l'état du patient.
Enfin, un algorithme doit être mis en place pour prévoir les survenues de crises d'asthme.
### 1.4 Environnement du produit recherché
#### 1.4.1 Listes exhaustives des éléments *(personnes, équipements, matières…)* et contraintes *(e.g. environnement)*

**Personnes :**
- L'enfant asthmatique
- Ses parents
- Le médecin traitant

**Équipements :**
- Capteurs environnementaux (pollution de l'air, pollen, moisissure, température/humidité, qualité de l'air intérieur)
- Capteurs physiologiques (rythme cardiaque, rythme de respiration, taux de dioxygène dans le sang)
- Capteurs sur dispositif (spiromètre connecté, bronchodilateur)
- Capteur pour mesurer l'activité physique (smartphone, montre connectée)
- Questionnaires sur l'application pour collecter des données de vie réelle (ressenti après traitement ou après crise)

**Données à collecter :**
- Pollution de l'air 
- Pollen 
- Moisissure
- Température/humidité
- Qualité de l'air intérieur
- rythme cardiaque
- rythme de respiration 
- taux de dioxygène dans le sang
- Oxymétrie (saturation en O2 dans le sang)
- Rythme cardiaque
- Température corporelle
- Température ambiante
- Taux d’humidité
- Taux de COVs atmosphérique (concentration en COVs)
- Taux de CO2 atmosphérique (concentration en CO2)
- Taux d’O3 atmosphérique (concentration en ozone)
- ressenti après traitement ou après crise

**Contraintes :**
- Détermination du Statut de Dispositif Médical (DM)
- Conformité aux Nouveaux Règlements Européens
- Marche à Suivre pour la Commercialisation
- Cybersécurité des DM
- Respect du RGPD et Protection des Données de Santé
- Normes et Guides d’Application Européens
- Évaluation Clinique et Performance
- Engagement envers la Qualité et la Sécurité
- Respect des Règles Spécifiques au Projet
- Envoi des données sur l'espace numérique de santé

#### 1.4.2 Caractéristiques pour chaque élément de l’environnement
- Parents : Doivent être capables d'utiliser l'appli, de comprendre les valeurs des capteurs
- Enfant Asthmatique : Doit être capable d'utiliser l'appli, de comprendre les valeurs
- Médecin : Doit avoir accès aux valeurs de l'appli via mon espace santé de l'enfant
- Capteurs environnementaux : Ces capteurs sont utilisés pour mesurer divers facteurs environnementaux tels que la  
- pollution de l'air, les pollens, les moisissures, la température et l'humidité, ainsi que la qualité de l'air intérieur. Ils doivent être précis, fiables et capables de fonctionner dans diverses conditions environnementales.  
- Capteurs physiologiques : Ces capteurs sont utilisés pour mesurer des constantes physiologiques telles que le rythme cardiaque, le rythme de la respiration et le taux d'oxygène dans le sang. Ils doivent être confortables à porter, non invasifs et fournir des mesures précises et fiables.  
- Capteurs sur dispositif : Ces capteurs sont utilisés pour mesurer la prise de traitement (par exemple, un spiromètre connecté, un bronchodilatateur connecté). Ils doivent être faciles à utiliser et fournir des données précises sur l'utilisation du traitement.  
- Capteur pour mesurer l'activité physique : Ces capteurs (par exemple, un smartphone, une montre connectée) sont utilisés pour mesurer l'activité physique de l'utilisateur. Ils doivent être capables de détecter et de suivre divers types d'activités physiques avec précision.  
- Questionnaires sur l'application : Ces questionnaires sont utilisés pour collecter des données de vie réelle (par exemple, le ressenti après la prise de traitement ou après une crise). Ils doivent être faciles à comprendre et à remplir par l'utilisateur, et permettre une collecte de données précise et détaillée.

### Note de Cadrage
L'uc : Application de Suivi de l'Asthme </br>
Le projet : Développement d'une application intelligente de suivi de l'asthme chez l'adolescent

| Éléments à considérer | Description                                                                                              | Recommandations, remarques du tuteur              |
|-----------------------|----------------------------------------------------------------------------------------------------------|--------------------------------------------------|
| **Contexte**          | Problème de santé publique lié à l'asthme chez les adolescents.                                          | -                                                |
|                       | Importance de suivre l'évolution de la maladie pour adapter le traitement.                              | -                                                |
|                       | Disponibilité accrue de technologies intelligentes pour la santé.                                        | -                                                |
| **But**               | Offrir un suivi personnalisé pour les adolescents asthmatiques via une application mobile.                | -                                                |
| **Résultats attendus**| - Réduction des crises d'asthme chez les adolescents.                                                    | -                                                |
|                       | - Suivi continu et précis de l'évolution de la maladie.                                                  | -                                                |
|                       | - Propositions de traitements adaptés en fonction des symptômes.                                         | -                                                |
| **Description projet**| **Moyens matériels**: Smartphones, tablettes, capteurs de santé.                                         | -                                                |
|                       | **Acteurs**: Développeurs, Expert IA, Consultant Santé, Responsable Qualité.                             | -                                                |
|                       | **Délais**: 5 mois                                                                                       | -                                                |
|                       | **Budget**: 15 000 €                                                                                     | -                                                |
|                       | **Communication**: Hors-média, relation presse, réseaux sociaux, blog médical.                           | -                                                |
| **Contraintes**       | **Risques**: Non-conformité, retards, problèmes d'intégration, défauts logiciels, manque de compétences. | -                                                |
|                       | **Études préalables**: Analyse des besoins, étude de marché, validation par des professionnels de santé.  | -                                                |

## 2. Expression fonctionnelle du besoin


| Numéro | Fonction                                         | Critère d'appréciation                                     | Niveau de critère d'appréciation                                                                                                                                                                                                                                                                                                                                    | Flexibilité                                                | Coefficient de pondération |
|--------|--------------------------------------------------|--------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------|---------------------------|
| FP     | Suivis de l'état de Santé du jeune               | Collecte de données précises et utiles : Santé et Environnement | Pas de données : Inacceptable                                                                                                                                                                                                                                                                                                                                       | 90 % de collecte complète / 10 % de collecte partielle      | 5                         |
| FC1    | Se connecter à des appareils et capteurs         | Connexion Rapide ( <1 min ) Multi Connexion ( +3 Appareil ) | Délai de connexion : - <30 s Excellent / - >30s / <1 min Acceptable / - + 1 min Défavorable / - pas de connexion : Inacceptable                                                                                                                                                                                                                                     | 50 % de connexion excellente / 40 % de connexion acceptable / 10 % de connexion défavorable / 70 % Excellent / 20 % Acceptable / 10 % Défavorable | 4 |
| FS1    | Fournir des questionnaires au client             | Questionnaire au moment opportun Succinct <3min              | Questionnaire après la détection de prise de ventoline - <1min suivante Excellent / - < 5 min Acceptable / - + 5 min Défavorable / Questionnaire succinct : - <3 min Excellent / - <5 min Acceptable / - +5 min Défavorable / - + 8 min Innacceptable                                                                                                               | 90 % de questionnaire dans la minute suivante / 10 % après / 95 % Questionnaire succinct / 3 % Acceptable / 2 % Défavorable | 2-1 |
| FS2    | Analyse des données de l'utilisateur             | Analyse permettant de détecter la nécessité de prendre de la ventoline | Détection efficace : Excellent / Détection en accord avec patient : Acceptable / Erreur Inacceptable                                                                                                                                                                                                                                                                | 50 % détection efficace / 50 % détection en accord | 3 |
| FS3    | Prédictions des crises d'asthme de l'utilisateur | Analyse des données menant à la conclusion d'une forte probabilité de crise sous peu | Détection +5 min pre-crise : Excellent / Détection <5 min pre crise : Acceptable / Détection pendant crise : Défavorable / Aucune détection mais crise : Innacceptable                                                                                                                                                                                              | 30 % +5 min pre crise / 50 % <5 min pre crise / 20 % détection pendant crise | 3 |
| FS4    | Un tableau de bord pour patient et médecin       | Permet consultation simple des données depuis mon espace santé | Transfert 100 % données vers mon espace santé : Excellent / 90 % : Acceptable / 80 % Défavorable / <80 % Innacceptable                                                                                                                                                                                                                                              | 80 % Excellent / 15 % Acceptable / 5 % Défavorable | 2 |

### Diagramme de cas d'utilisation
<img src=../pictures/casUtilisation_appliAsthme.drawio1.png alt="Cas d'utilisation" width="920"/>

### Diagramme WBS
<img src=../pictures/wbs.png alt="WBS" width="1920"/>

### 2.1 Fonctions de service et de contrainte
#### 2.1.1 Fonctions de service principales 
Suivre l'état de Santé du jeune et Se connecter à des appareils et capteurs.

##### 2.1.1.1 Description et détail
- Suivre l'état de Santé du jeune : Cette fonction implique la collecte de données précises et utiles relatives à la 
santé et à l'environnement du jeune.

- Se connecter à des appareils et capteurs : Cette fonction assure une connexion rapide à des appareils et capteurs, 
permettant également la possibilité de se connecter à plusieurs appareils simultanément.

##### 2.1.1.2 Critères d’appréciation et les niveaux qui les caractérisent

##### (Niveaux dont l’obtention est imposée)

###### Suivre l'état de Santé du jeune :
Collecte de données précises et utiles Santé et Environnement.
Niveau imposé : Uniquement santé acceptable mais insuffisant, Uniquement environnement acceptable mais insuffisant.
Flexibilité : 90 % de collecte complète, 10 % de collecte partielle.

###### Se connecter à des appareils et capteurs :
Connexion Rapide ( <1 min ) Multi Connexion ( +3 Appareil ).
Niveau imposé : Connexion en plus ou moins 1 minute et nombre possible de connexion d'au moins 3 appareils.
Flexibilité : 50 % de connexion excellente, 40 % de connexion acceptable, 10 % de connexion défavorable.
70 % Excellent, 20 % Acceptable, 10 % Défavorable.

##### (Niveaux souhaités mais révisables)

###### Suivre l'état de Santé du jeune :
Collecte de données précises et utiles Santé et Environnement.
Niveau souhaité mais révisable : Collecte des deux données santé et environnement.

###### Se connecter à des appareils et capteurs :
Connexion Rapide ( <1 min ) Multi Connexion ( +3 Appareil ).
Niveau souhaité mais révisable : Délai de connexion inférieur à 30 secondes ou entre 1 minute et 30 secondes et nombre de connexions supérieur à 3.

#### 2.1.2 Fonctions de service complémentaires 
*(qui améliorent, facilitent ou complètent le service rendu)*
##### 2.1.2.1 Description et détail
FS1: Fournir des questionnaires au client
Description : Envoi automatique de questionnaires de suivi à l'utilisateur après la détection de l'usage de ventoline, permettant un suivi efficace de l'état de santé.

FS2: Analyse des données de l'utilisateur
Description : Système intelligent d'analyse des données respiratoires pour anticiper le besoin potentiel de médication (ventoline).

FS3: Prédictions des crises d'asthme de l'utilisateur
Description : Utilisation de modèles prédictifs pour évaluer le risque de crises d’asthme imminentes, permettant une intervention proactive.

FS4: Un tableau de bord pour patient et médecin
Description : Interface accessible permettant à l'utilisateur et au médecin de consulter les données de santé enregistrées et les analyses pertinentes.

##### 2.1.2.2 Critères d’appréciation et les niveaux qui les caractérisent 
###### FS1:
- Niveaux imposés : Réponse sous 1 minute dans 90% des cas après détection de la prise de ventoline.
- Niveaux souhaités mais révisables : Durée des questionnaires moins de 3 minutes dans 95% des cas.

###### FS2:
- Niveaux imposés : 50% de détection efficace.
- Niveaux souhaités mais révisables : Conformité de la détection avec le ressenti du patient dans 50% des cas.

###### FS3:
- Niveaux imposés : 30% des détections plus de 5 minutes avant la crise.
- Niveaux souhaités mais révisables : Détection moins de 5 minutes avant la crise dans 50% des cas.

###### FS4:
- Niveaux imposés : 80% des données transférées correctement.
- Niveaux souhaités mais révisables : Transfert de 100% des données visé, avec un minimum acceptable de 80%.
#### 2.1.3 Contraintes 
*(limitations à la liberté du concepteur-réalisateur)*
- Performance des systèmes de détection et de réponse : Les systèmes doivent être conçus pour répondre efficacement 
et rapidement selon les critères d'appréciation définis.
- Simplicité et accessibilité de l'interface utilisateur : Les interfaces pour les patients et médecins doivent être 
  intuitives et facilement accessibles pour encourager leur utilisation régulière.
- Intégration des données de santé : L'application doit pouvoir intégrer de manière fiable les données dans les 
  systèmes de santé existants pour assurer la continuité des soins.
- Respect de la vie privée et de la sécurité des données : Les données des utilisateurs doivent être traitées avec 
  les plus hauts standards de sécurité et de confidentialité.

## 3. Cadre de réponse

### Diagramme de classes métiers
<img src=../pictures/classeMetierWhite.png alt="Classes métiers" width="1080"/>

### Tableau Synthétique des Jalons du Projet
| Phase                          | Jalon                                      | Date de début   | Date de fin       | Responsable           |
|--------------------------------|--------------------------------------------|-----------------|-------------------|-----------------------|
| Planification et conception    | Cahier des charges finalisé                | 3 avril 2024    | 10 avril 2024     | Chef de Projet        |
|                                | Étude de marché complétée                  | 11 avril 2024   | 14 avril 2024     | Consultant Santé      |
|                                | Conception fonctionnelle validée           | 15 avril 2024   | 24 avril 2024     | Développeurs          |
|                                | Conception technique validée               | 25 avril 2024   | 3 mai 2024        | Expert IA             |
| Développement                  | Prototype de l’application développé       | 6 mai 2024      | 15 mai 2024       | Développeurs          |
|                                | Développement de l’intelligence artificielle terminé | 16 mai 2024 | 3 juin 2024       | Expert IA             |
|                                | Intégration des capteurs complétée         | 4 juin 2024     | 20 juin 2024      | Développeurs          |
|                                | Interface utilisateur développée           | 21 juin 2024    | 4 juillet 2024    | Développeurs          |
| Test et validation             | Tests unitaires terminés                   | 7 juillet 2024  | 14 juillet 2024   | Responsable Qualité   |
|                                | Tests d’intégration terminés               | 15 juillet 2024 | 24 juillet 2024   | Responsable Qualité   |
|                                | Tests utilisateurs terminés                | 25 juillet 2024 | 31 juillet 2024   | Responsable Qualité   |
|                                | Validation par les professionnels de santé | 1 août 2024     | 8 août 2024       | Consultant Santé      |
| Déploiement et lancement       | Préparation au déploiement complétée       | 11 août 2024    | 14 août 2024      | Chef de Projet        |
|                                | Application déployée sur les plateformes   | 15 août 2024    | 19 août 2024      | Chef de Projet        |
|                                | Lancement officiel de l’application        | 20 août 2024    | 22 août 2024      | Chef de Projet        |
| Maintenance et amélioration continue | Première mise à jour après le lancement | 25 août 2024    | 29 août 2024      | Développeurs          |
|                                | Analyse des retours utilisateurs pour les améliorations | 1 septembre 2024 | 15 septembre 2024 | Développeurs          |
|                                | Mise à jour régulière                      | 16 septembre 2024 | Aujourd'hui        | Développeurs          |

*(disclaimer : toutes ces dates ont étés genere avec ChatGPT)*

### 3.1 Fonction 1
<img src=../pictures/sequence/Diagramme_sequence_FP.png alt="Diagramme_sequence_FP" width="400"/>

### 3.1.1 Solution proposée

#### Fonction Principale : Suivi de l'état de santé du jeune
- **Description de scénarios** : Développement des fonctionnalités permettant de collecter et de suivre les données de santé et d'environnement du jeune utilisateur. Scénarios incluant la collecte de données précises, la mise à jour en temps réel et la présentation claire des informations.

#### Jalon Correspondant :
- **Développement** : Étant donné que cette fonctionnalité est principalement liée à la mise en place des mécanismes de collecte de données et de suivi, elle serait livrée à la fin de la phase de Développement, soit le 4 juillet 2024.

### 3.1.2 Niveau atteint pour chaque critère d’appréciation de cette fonction et modalités de contrôle

- **Collecte de données précises et utiles : Santé et Environnement** :
    - Contrôle : Vérification de la précision et de l'utilité des données collectées par rapport aux critères définis.
    - Niveau atteint : À vérifier à la fin de la phase de Test et validation, avec un rapport sur la précision des données collectées.

### 3.1.3 Part du prix attribué à cette fonction

- **Suivi de l'état de santé du jeune** :
    - Part du prix : À déterminer en fonction de l'importance stratégique et de la complexité de cette fonction. Dans ce cas, étant donné qu'il s'agit d'une fonction principale, elle pourrait être attribuée à une part significative du budget, par exemple 25%.


### 3.2 Fonction 2
<img src=../pictures/sequence/Diagramme_sequence_FC1.png alt="Diagramme_sequence_FC1" width="400"/>

### 3.2.1 Solution proposée

#### Fonction Complémentaire 1 : Se connecter à des appareils et capteurs
- **Description de scénarios** : Développement des fonctionnalités permettant de se connecter rapidement à divers appareils et capteurs de santé. Scénarios incluant la connexion à plusieurs appareils en moins d'une minute, avec la capacité de gérer plus de trois connexions simultanées.

#### Jalon Correspondant :
- **Développement** : Cette fonctionnalité est liée à l'intégration et la gestion des connexions aux appareils et capteurs. Elle serait livrée à la fin de la phase de Développement, soit le 4 juillet 2024.

### 3.2.2 Niveau atteint pour chaque critère d’appréciation de cette fonction et modalités de contrôle

- **Connexion Rapide (<1 min) Multi Connexion (>3 Appareils)** :
  - Contrôle : Test de connexion à divers appareils et capteurs pour mesurer le temps de connexion et la capacité de gérer plusieurs connexions simultanées.
  - Niveau atteint : À vérifier à la fin de la phase de Test et validation, avec un rapport détaillant les temps de connexion et le nombre d'appareils connectés simultanément.

### 3.2.3 Part du prix attribué à cette fonction

- **Se connecter à des appareils et capteurs** :
  - Part du prix : Étant une fonction complémentaire mais essentielle pour l'expérience utilisateur, elle pourrait être attribuée à une part modérée du budget, par exemple 15%.

### 3.3 Fonction 3
<img src=../pictures/sequence/Diagramme_sequence_FS1.png alt="Diagramme_sequence_FS1" width="400"/>

### 3.3.1 Solution proposée

#### Fonction Secondaire 1 : Fournir des questionnaires au client
- **Description de scénarios** : Développement des fonctionnalités permettant de fournir des questionnaires succincts au moment opportun. Scénarios incluant la fourniture de questionnaires immédiatement après la détection de la prise de Ventoline, et veiller à ce que ces questionnaires soient remplis en moins de trois minutes.

#### Jalon Correspondant :
- **Développement** : Cette fonctionnalité est liée à l'interaction utilisateur et la collecte de feedback. Elle serait livrée à la fin de la phase de Développement, soit le 4 juillet 2024.

### 3.3.2 Niveau atteint pour chaque critère d’appréciation de cette fonction et modalités de contrôle

- **Questionnaire au moment opportun Succinct (<3 min)** :
  - Contrôle : Vérification du timing de l'envoi des questionnaires et du temps nécessaire pour les remplir.
  - Niveau atteint : À vérifier à la fin de la phase de Test et validation, avec un rapport sur le timing et la durée de remplissage des questionnaires.

### 3.3.3 Part du prix attribué à cette fonction

- **Fournir des questionnaires au client** :
  - Part du prix : Étant une fonction secondaire mais utile pour le suivi, elle pourrait être attribuée à une part plus faible du budget, par exemple 10%.

### 3.4 Fonction 4
<img src=../pictures/sequence/Diagramme_sequence_FS2.png alt="Diagramme_sequence_FS2" width="400"/>

### 3.4.1 Solution proposée

#### Fonction Secondaire 2 : Analyse des données de l'utilisateur
- **Description de scénarios** : Développement des fonctionnalités permettant d'analyser les données de santé de l'utilisateur pour détecter la nécessité de prendre de la Ventoline. Scénarios incluant l'analyse des données en temps réel et la fourniture de recommandations précises.

#### Jalon Correspondant :
- **Développement** : Cette fonctionnalité est principalement liée à l'analyse de données et l'algorithme de détection. Elle serait livrée à la fin de la phase de Développement, soit le 4 juillet 2024.

### 3.4.2 Niveau atteint pour chaque critère d’appréciation de cette fonction et modalités de contrôle

- **Analyse permettant de détecter la nécessité de prendre de la Ventoline** :
  - Contrôle : Évaluation de l'efficacité de la détection et comparaison avec les retours des utilisateurs.
  - Niveau atteint : À vérifier à la fin de la phase de Test et validation, avec un rapport sur l'efficacité des détections.

### 3.4.3 Part du prix attribué à cette fonction

- **Analyse des données de l'utilisateur** :
  - Part du prix : Étant une fonction secondaire mais essentielle pour la prévention, elle pourrait être attribuée à une part modérée du budget, par exemple 15%.

### 3.5 Fonction 5
<img src=../pictures/sequence/Diagramme_sequence_FS3.png alt="Diagramme_sequence_FS3" width="600"/>

### 3.5.1 Solution proposée

#### Fonction Secondaire 3 : Prédictions des crises d'asthme de l'utilisateur
- **Description de scénarios** : Développement des fonctionnalités permettant de prédire les crises d'asthme de l'utilisateur en analysant les données collectées. Scénarios incluant la prédiction de crises avec un délai suffisant pour agir.

#### Jalon Correspondant :
- **Développement** : Cette fonctionnalité est liée à la prédiction et l'analyse proactive des données de santé. Elle serait livrée à la fin de la phase de Développement, soit le 4 juillet 2024.

### 3.5.2 Niveau atteint pour chaque critère d’appréciation de cette fonction et modalités de contrôle

- **Analyse des données menant à la conclusion d'une forte probabilité de crise sous peu** :
  - Contrôle : Évaluation de la précision des prédictions et des délais d'alerte par rapport aux crises réelles.
  - Niveau atteint : À vérifier à la fin de la phase de Test et validation, avec un rapport sur la précision des prédictions et les délais d'alerte.

### 3.5.3 Part du prix attribué à cette fonction

- **Prédictions des crises d'asthme de l'utilisateur** :
  - Part du prix : Étant une fonction secondaire mais cruciale pour la prévention des crises, elle pourrait être attribuée à une part significative du budget, par exemple 20%.

### 3.6 Fonction 6
<img src=../pictures/sequence/Diagramme_sequence_FS4.png alt="Diagramme_sequence_FS4" width="400"/>

### 3.6.1 Solution proposée

#### Fonction Secondaire 4 : Un tableau de bord pour patient et médecin
- **Description de scénarios** : Développement des fonctionnalités permettant de consulter facilement les données de santé depuis un tableau de bord accessible à la fois par le patient et le médecin. Scénarios incluant le transfert complet des données vers l'espace santé et une interface utilisateur claire et intuitive.

#### Jalon Correspondant :
- **Développement** : Cette fonctionnalité est liée à la présentation et au transfert des données de santé. Elle serait livrée à la fin de la phase de Développement, soit le 4 juillet 2024.

### 3.6.2 Niveau atteint pour chaque critère d’appréciation de cette fonction et modalités de contrôle

- **Permet consultation simple des données depuis mon espace santé** :
  - Contrôle : Vérification de la complétude et de l'accessibilité des données transférées vers l'espace santé.
  - Niveau atteint : À vérifier à la fin de la phase de Test et validation, avec un rapport sur la complétude et l'accessibilité des données.

### 3.6.3 Part du prix attribué à cette fonction

- **Un tableau de bord pour patient et médecin** :
  - Part du prix : Étant une fonction secondaire mais utile pour le suivi des utilisateurs et la communication avec les médecins, elle pourrait être attribuée à une part modérée du budget, par exemple 15%.


### 3.7 Pour l’ensemble du produit
#### 3.7.1 Prix de la réalisation de la version de base

- **Cout de développement** :
  - environ 72 700 € d'après le tableau des coûts mensuels
- **Cout marketing et distribution** :
  - publicité a travers les maisons de santé et médecin, environ 10 000 € incluant 
    une campagne digitale, ainsi qu'une campagne physique dans les maisons de santé, puis éventuellement des 
    collaborations avec des associations de santé
  - pour la distribution prix hébergeur : serveur dédié (VPS) donc entre 100 et 300 € par mois en fonction de la taille,
  apple store 90 € par an et Google PLay Store 23 € unique
- **Cout de maintenance** :
  - d'après le tableau en début de rapport on compte entre 1500 et 2000€ mensuel pour la maintenance

*(disclaimer : tout ces chiffres ont étés estimés avec ChatGPT)*
#### 3.7.2 Options et variantes proposées non retenues au cahier des charges
- nous n'avons pas abandonné d'idée
#### 3.7.3 Mesures prises pour respecter les contraintes et leurs conséquences économiques
Plusieurs mesures ont été prises afin de respecter les contraintes imposés par le fait que notre application est un DM (Dispositif Médical), ainsi que leurs conséquences économiques :
- **Mesures techniques** :
  - Sécurité des données :
    - afin de respecter la législation en vigueur les données doivent être sauvegardée en local dur l'appareil et transférée uniquement vers l'espace santé du patient en étant chiffrée
    - notre application doit être hébergée par un Hébergeur Agréé Données de Santé (HADS)
    - Nous devons suivre le RGPD :
      - Consentement des utilisateurs
      - Transparence sur le type de données collectées, la raison et leur utilité
      - Droit d'accès et de rectification
    - Accès restreint et strict aux données
    - Journalisation des accès et de la modification des données
  - respect de la norme ISO 13485 s'assurant de la qualité du développement de l'application
  - respect de la norme ISO 14971 s'assurant d'une gestion des risques
    (les deux normes, ainsi que leur logique ont étés trouvées avec chatgpt)
- **Certification** :
  - notre application doit obtenir la certification CE, assurant que notre DM est conforme aux directives européennes


#### 3.7.4 Outils d’installation, de maintenance … à prévoir
  - **outil d'installation** :
    - application disponible sur les stores mobiles
  - **outils de maintenance** :
    - Systèmes de surveillance, afin de détecter d'éventuels problèmes
    - Support Technique, afin de répondre aux questions et problèmes des utilisateurs
    - Mise à jour régulière
#### 3.7.5 Décomposition en modules, sous-ensembles
  - **Module de suivi des données** : 
      - Sous-ensemble de Visualisation des Données : Graphiques et données chiffrées pour les utilisateurs et les professionnels de santé
      - Sous-ensemble de prédiction des crises par IA
  - **Module de gestion des questionnaires** :
    - Sous-ensemble pour consulter les résultats des différents questionnaires
    - Sous-ensemble pour répondre aux questionnaires quotidiens

#### 3.7.6 Perspectives d’évolution technologique :
Afin de rester à jour et de ne pas perdre des utilisateurs, la plateforme devra nécessairement être retravaillée et intégrer de nouvelles fonctionnalités.

- **Amélioration de la sécurité en utilisant la blockchain**
  - Objectif : Protéger les données de santé des utilisateurs.
  - Exemple de nouvelle fonctionnalité :
    - Utiliser la blockchain pour stocker les données médicales de manière sécurisée et éviter les piratages.
    - Utiliser des smart contracts pour gérer qui peut accéder aux données des utilisateurs.

  
- **Intégration de la réalité augmentée pour l'éducation et la formation**
  - Objectif : Utiliser la réalité augmentée pour mieux éduquer les patients sur l'asthme.
  - Exemple de nouvelle fonctionnalité :
    - Utiliser la réalité augmentée pour montrer des instructions visuelles sur l'écran pour bien utiliser l'inhalateur.
    - Utiliser la réalité augmentée pour montrer comment l'asthme affecte les poumons, afin d’aider les jeunes à comprendre leur condition un peu mieux.


- **Gamification pour éduquer tout en amusant**
  - Objectif : Rendre l'application plus amusante et motivante pour les jeunes.
  - Exemple de nouvelle fonctionnalité :
    - Défis quotidiens : Proposer des défis quotidiens liés à la gestion de l'asthme pour gagner des points et des badges.
    - Créer des niveaux où les utilisateurs débloquent de nouvelles fonctionnalités ou des contenus éducatifs en atteignant des objectifs.


- **Expansion de la plateforme sur le web**
  - Objectif : Rendre l'application accessible sur plus de plateformes.
  - Exemple de nouvelle fonctionnalité :
    - Développer une version web pour que les utilisateurs puissent se connecter et consulter leurs données depuis n'importe quel navigateur.
    - Assurer que les données et fonctionnalités soient synchronisées entre l'application mobile et la version web.
    - Si une gamification est faite, alors intégrer une cross-progression

  
- **Création d'un espace de communauté en ligne**
  - Objectif : Créer un endroit où les gens peuvent se parler, partager leurs expériences et s'entraider avec leur asthme.
  - Exemples de nouvelle fonctionnalité :
    - Forum de discussion : Un endroit pour poser des questions, donner des conseils et parler de notre expérience personnelle avec l’asthme.
    - Groupes de soutien : Des groupes où on peut se retrouver pour parler de nos défis avec l'asthme, comme le sport ou le stress.

## 4 Prévisions de fiabilité – Gestions des risques
### 4.1 Risques à la réalisation

#### FP : Suivis de l'état de Santé du jeune
<img src=../pictures/nature_risque/analyserDonneeUser.png alt="Analyser donnes user" width="600"/>

#### FC1 : Se connecter à des appareils et capteurs
<img src=../pictures/nature_risque/connecterAppareilsCapteur.png alt="Connecter appareils capteur" width="600"/>

#### FS1 : Fournir des questionnaires au client
<img src=../pictures/nature_risque/fournirQuestionnaire.png alt="Fournir questionnaire" width="600"/>

#### FS2 : Analyse des données de l'utilisateur
<img src=../pictures/nature_risque/predirCriseAsthme.png alt="Predir crise asthme" width="600"/>

#### FS3 : Prédictions des crises d'asthme de l'utilisateur
<img src=../pictures/nature_risque/suiviEtatSante.png alt="Suivi etat sante" width="600"/>

#### FS4 : Un tableau de bord pour patient et médecin
<img src=../pictures/nature_risque/tableauBord.png alt="Analyser donnes user" width="600"/>


### 4.2 Prévision des défaillances
#### Table de défaillance pour chaque fonction de service

| Fonctions                                     | Défaillances possibles                                | Causes potentielles                                         | Effets potentiels des défaillances                            | Comment détecter ces défaillances                                                |
|-----------------------------------------------|-------------------------------------------------------|-------------------------------------------------------------|---------------------------------------------------------------|----------------------------------------------------------------------------------|
| Suivi de l’état de santé du jeune             | Problème de sauvegarde des données                    | Dysfonctionnement de l'application, code mauvais            | Impossible de mettre au courant le médecin de l'état de santé | Maintenir l'application avec des mises à jour                                    |
| Se connecter à des appareils capteurs         | Impossibilité de se connecter                         | Panne d’un capteur, plus de batterie                        | Incapacité de d’analyser des données/ données invalides       | Alerter l’utilisateur si la batterie est faible                                  |
| Fournir des questionnaires au client          | Non-réception ou non-distribution des questionnaires  | Problèmes de communication, erreurs de distribution         | Données manquantes ou incomplètes pour l'analyse              | Vérification de l'envoi et réception des questionnaires                          |
| Analyser des données de l’utilisateur         | Mauvaises données analysées                           | l’id de l’utilisateur est déjà existant (limites atteintes) | Fuite de données personnelles                                 | Meilleure gestion des id, plus de caractères                                     |
|                                               | Impossible d’analyser                                 | Impossible de se connecter à la base de données             | Impossible d’envoyer un compte rendu                          | Demander une connexion internet                                                  |
| Prédire des crises d’asthme du jeune          | Mauvaise prédiction                                   | Calculs erronés                                             | Crise d’asthme non détectée                                   | Approfondir les recherches, calculs de prédictions                               |
| Renseigner un tableau de bord pour le médecin | Mauvaises données renseignées dans le tableau de bord | Code mal fait                                               | Mauvaises ordonnances, dosage etc…                            | Approfondir les cas de tests                                                     |
|                                               | Envoi au mauvais docteur                              | Mauvaise adresse renseignée                                 | Impossibilité pour le docteur de traiter l’état du jeune      | Assurer que le docteur soit présent lors du renseignement des infos dans l’appli |

### 4.3 Gestion des défaillances

### Matrices de criticité

**Se connecter à des appareils capteurs**
Impossibilité de se connecter

| Gravité/ Fréquence | Rare | Modérée | Élevée | Très élevée |
|--------------------|------|---------|--------|-------------|
| Mineure            |      |         | X      |             |
| Majeure            |      |         |        |             |
| Critique           |      |         |        |             |
| Catastrophique     |      |         |        |             |

**Fournir des questionnaires au client**
Non-réception ou non-distribution des questionnaires

| Gravité/ Fréquence | Rare | Modérée | Élevée | Très élevée |
|--------------------|------|---------|--------|-------------|
| Mineure            |      |         |        |             |
| Majeure            | X    |         |        |             |
| Critique           |      |         |        |             |
| Catastrophique     |      |         |        |             |

**Analyser des données de l’utilisateur**
Mauvaises données analysées

| Gravité/ Fréquence | Rare | Modérée | Élevée | Très élevée |
|--------------------|------|---------|--------|-------------|
| Mineure            |      |         |        |             |
| Majeure            |      |         |        |             |
| Critique           | X    |         |        |             |
| Catastrophique     |      |         |        |             |

Impossible d’analyser

| Gravité/ Fréquence | Rare | Modérée | Élevée | Très élevée |
|--------------------|------|---------|--------|-------------|
| Mineure            |      |         |        |             |
| Majeure            |      | X       |        |             |
| Critique           |      |         |        |             |
| Catastrophique     |      |         |        |             |

**Prédire des crises d’asthme du jeune**
Mauvaise prédiction

| Gravité/ Fréquence | Rare | Modérée | Élevée | Très élevée |
|--------------------|------|---------|--------|-------------|
| Mineure            |      |         |        |             |
| Majeure            |      |         |        |             |
| Critique           |      |         |        |             |
| Catastrophique     | X    |         |        |             |

Pour empêcher une mauvaise prédiction, il est nécessaire de travailler et approfondir l'algorithme responsable du calcul, 
le code doit être le plus précis possible. S'il est découvert que l'algorithme est défaillant et que des prédictions de 
crise d'asthme seront erronées, il devrait être possible d'alerter les utilisateurs de l'application via une notification. 
Si la défaillance est détectée il faudra assurément corriger les prédictions faussées, dédommager d'une certaine manière 
les victimes de l'erreur et travailler sur une correction du code.

**Renseigner un tableau de bord pour le médecin**</br>
Mauvaises données renseignées dans le tableau de bord

| Gravité/ Fréquence | Rare | Modérée | Élevée | Très élevée |
|--------------------|------|---------|--------|-------------|
| Mineure            |      |         |        |             |
| Majeure            |      |         |        |             |
| Critique           |      | X       |        |             |
| Catastrophique     |      |         |        |             |

Afin d'empêcher d'envoyer les mauvaises données à un médecin via le tableau de bord, on devra nécessairement assurer la 
fiabilité des données au moment de l'envoi, le code doit alors être capable de comparer correctement. Pour alerter que 
la défaillance est sur le point de se produire, afficher une alerte sur l'application au moment de l'envoi ou par mail 
au docteur. Encore une fois, si les mauvaises données sont envoyées, c'est un problème de programme qui traduit les données 
faussement, alors c'est encore le code qui devra être retravaillé, ainsi peut-être que des cas de tests devraient être 
ajoutés, si des données sont passées, il faudra prévenir les docteurs utilisant l'appli pour éviter des mauvaises 
prescriptions.

**Envoi au mauvais docteur**

| Gravité/ Fréquence | Rare | Modérée | Élevée | Très élevée |
|--------------------|------|---------|--------|-------------|
| Mineure            |      |         |        |             |
| Majeure            | X    |         |        |             |
| Critique           |      |         |        |             |
| Catastrophique     |      |         |        |             |

### 4.4 Identification des Risques (AMDEC)

| Risque                         | Gravité | Probabilité | Détection | Criticité | Actions préventives                  | Actions correctives                  |
|-------------------------------|---------|-------------|-----------|-----------|--------------------------------------|--------------------------------------|
| Non-conformité aux exigences  | 5       | 2           | 3         | 30        | Revue régulière des exigences        | Révision du cahier des charges       |
| Retards de développement      | 4       | 3           | 2         | 24        | Planning réaliste, suivi rigoureux   | Réévaluation des délais              |
| Problèmes d'intégration       | 3       | 4           | 2         | 24        | Tests d'intégration réguliers        | Correctifs rapides, tests supplémentaires |
| Défauts logiciels             | 4       | 2           | 3         | 24        | Tests unitaires et fonctionnels      | Correction des bugs, patchs          |
| Manque de compétences IA      | 5       | 1           | 3         | 15        | Formation, recrutement d'experts     | Support externe, formation continue  |
| Non-acceptation par les utilisateurs | 4   | 2           | 2         | 16        | Impliquer utilisateurs dès le début  | Sessions de feedback et d'adaptation |


## 5 Annexe

### Diagramme de Gantt
<img src=../pictures/Gantt.png alt="Gantt" width="1080"/>

### Plan de Communication

| Audience        | Type de communication        | Fréquence            | Responsable       |
|-----------------|------------------------------|----------------------|-------------------|
| Équipe projet   | Réunions de suivi            | Hebdomadaire         | Chef de Projet    |
| MOA             | Rapports d'avancement        | Mensuelle            | Chef de Projet    |
| Utilisateurs    | Formations, questionnaires   | Avant et après déploiement | Consultant Santé |
| Partenaires     | Mises à jour sur le projet   | Mensuelle            | Chef de Projet    |
| Développeurs    | Réunions techniques          | Hebdomadaire         | Chef de Projet    |
| Expert IA       | Séances de brainstorming     | Bi-hebdomadaire      | Chef de Projet    |

### Horaire de travail
- Benjamin Lecomte : 15 heures
- Clement Lerouley : 15 heures
- Loris Drouhot : 15 heures
- Clement Marquis : 15 heures

