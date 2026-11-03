# 🔎 Audit OSINT — Analyse de la surface d'exposition de TEHTRIS

![Cybersécurité](https://img.shields.io/badge/Domaine-Cybersécurité-blue)
![OSINT](https://img.shields.io/badge/Spécialité-OSINT-green)
![Projet](https://img.shields.io/badge/Type-Projet_académique-orange)

##  Présentation du projet

Ce projet académique, réalisé dans le cadre de ma formation d'ingénieur en cybersécurité à l'EFREI Paris, porte sur l'utilisation des techniques d'Open Source Intelligence (OSINT) pour analyser l'exposition numérique d'une organisation.

L'étude prend pour cas l'entreprise française TEHTRIS, spécialisée dans les solutions de cybersécurité et de détection des menaces.

L'objectif est de comprendre comment des informations accessibles publiquement peuvent être collectées, croisées et interprétées pour identifier des risques potentiels de sécurité.

> **Cadre éthique :** cette étude repose sur des sources publiques et des méthodes de reconnaissance passive. Elle ne constitue ni un audit mandaté par TEHTRIS, ni une démonstration de vulnérabilités exploitables. Les observations sont historiques et ne décrivent pas nécessairement l'état actuel de l'infrastructure.

##  Objectifs

- Collecter des informations publiques sur l'environnement numérique de l'organisation.
- Identifier les domaines, sous-domaines, services et technologies visibles.
- Étudier les risques liés à l'exposition d'informations techniques et organisationnelles.
- Corréler les données issues de plusieurs sources OSINT.
- Réaliser une cartographie relationnelle avec Maltego.
- Proposer des recommandations visant à réduire les risques d'exposition.

##  Outils utilisés

| Outil | Utilisation |
|---|---|
| Whois Lookup | Analyse des informations d'enregistrement des domaines |
| DNSDumpster | Identification et cartographie des sous-domaines |
| Shodan | Consultation des services et bannières techniques indexés |
| Skymem | Étude de l'exposition des adresses électroniques publiques |
| RocketReach | Analyse de la visibilité organisationnelle |
| Have I Been Pwned | Étude des risques associés aux violations de données |
| Google Dorks | Recherche avancée de contenus publics indexés |
| Maltego | Corrélation et représentation graphique des informations |

##  Méthodologie

### Phase 1 — Collecte d'informations OSINT

La première phase consiste à rechercher des informations accessibles publiquement à l'aide de moteurs spécialisés.

Les recherches ont notamment porté sur :
- Les informations d'enregistrement et de résolution DNS.
- Les sous-domaines et les fournisseurs d'hébergement.
- Les services et technologies indexés par Shodan.
- L'exposition des informations organisationnelles.
- Les documents indexés par les moteurs de recherche.

### Phase 2 — Analyse et corrélation des données

Les données collectées ont été étudiées et croisées afin d'identifier les relations entre les différentes entités.

L'utilisation de Maltego a permis de représenter les liens entre :
- Domaines et sous-domaines.
- Adresses IP et fournisseurs d'hébergement.
- Services et technologies.
- Informations organisationnelles accessibles publiquement.

Cette démarche permet de passer d'une collecte de données isolées à une vision structurée de la surface d'exposition.

### Phase 3 — Analyse des risques

L'étude a permis d'examiner plusieurs catégories de risques potentiels :

**1. Exposition de services techniques**

L'observation de services accessibles depuis Internet peut révéler des informations sur les technologies employées et leurs configurations.

**2. Versions logicielles anciennes**

Certaines bannières historiques indiquaient des versions anciennes de services. Ces observations nécessitent une vérification complémentaire avant de conclure à une vulnérabilité réelle.

**3. Exposition d'informations organisationnelles**

La disponibilité publique de certaines informations professionnelles peut accroître les risques d'ingénierie sociale et de phishing ciblé.

**4. Corrélation des informations**

Le croisement de sources publiques peut révéler des relations et dépendances qui ne sont pas immédiatement visibles lorsqu'une information est étudiée seule.

##  Recommandations de sécurité

À partir des risques étudiés, plusieurs mesures générales peuvent être proposées :

- Maintenir les systèmes et logiciels à jour.
- Réduire l'exposition inutile des services accessibles depuis Internet.
- Renforcer l'authentification et le contrôle des accès.
- Surveiller régulièrement la surface d'exposition externe.
- Sensibiliser les collaborateurs aux risques de phishing et d'ingénierie sociale.
- Limiter la publication d'informations organisationnelles sensibles.
- Mettre en place une veille continue sur les vulnérabilités et les actifs exposés.

##  Compétences développées

- Open Source Intelligence (OSINT).
- Reconnaissance passive.
- Analyse de la surface d'attaque externe.
- Recherche et corrélation d'informations.
- Cartographie des infrastructures numériques.
- Identification et qualification des risques.
- Rédaction de recommandations de cybersécurité.
- Respect des principes éthiques de la recherche en sécurité.

##  Documentation

Les captures d'écran anonymisées, la cartographie et une synthèse du rapport pourront être ajoutées progressivement dans les dossiers du dépôt.

##  Avertissement

Ce dépôt présente un travail académique indépendant. Il n'est ni affilié à TEHTRIS ni approuvé par cette entreprise.

Les informations techniques mentionnées correspondent à des observations effectuées pendant le projet. Aucune conclusion sur la sécurité actuelle de TEHTRIS ne peut en être déduite sans vérification et autorisation appropriées.

Les informations personnelles et les détails techniques sensibles ne sont pas publiés.

##  Auteur

**Ezekiel BOUNDA DJIKUI**  
Étudiant ingénieur en cybersécurité — EFREI Paris  
Spécialisation : Cybersécurité, Infrastructures et Gouvernance

**Domaines d'intérêt :** audit de sécurité, gouvernance SSI, sécurité des infrastructures, renseignement sur les menaces et cyberdéfense.
