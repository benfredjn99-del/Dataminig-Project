# Business Understanding

## 1. Contexte général
Les accidents de la route constituent un enjeu majeur de sécurité publique à l’échelle mondiale, entraînant des pertes humaines, des blessures graves et des coûts économiques considérables. L’analyse des données d’accidents, combinée aux techniques de data mining, permet de mieux comprendre les circonstances de ces événements et d’identifier les facteurs influençant leur gravité, afin d’orienter les actions de prévention et de prise de décision.

## 2. Problématique
Malgré les mesures de sécurité existantes (limitations de vitesse, signalisation, contrôles), les accidents persistent. La question centrale est donc :

> **Quels sont les facteurs principaux qui influencent la gravité des accidents de la route ?**

## 3. Objectifs du projet

### Objectif principal
Analyser les données d’accidents pour :
- Comprendre leurs causes ;
- Identifier les facteurs déterminants de leur gravité ;
- Fournir des leviers d’action pour améliorer la sécurité routière.

### Objectifs spécifiques
- Évaluer l’impact des conditions météorologiques ;
- Analyser le rôle de la limitation de vitesse (`Speed_limit`) ;
- Comparer la gravité selon le type de route et la zone (urbaine / rurale) ;
- Étudier la relation entre le nombre de véhicules impliqués et la gravité ;
- Identifier les configurations à haut risque.

## 4. Questions métier
- Les conditions météorologiques influencent-elles la gravité ?
- La limitation de vitesse est-elle un facteur déterminant ?
- Les accidents sont-ils plus graves en zone rurale qu’en zone urbaine ?
- Le type de route (autoroute, rue, carrefour) joue-t-il un rôle ?
- Un plus grand nombre de véhicules impliqués accroît-il la gravité ?
- À quels moments (heure, jour) les accidents sont-ils les plus fréquents ?

## 5. Objectifs Data Mining
- Identifier les variables les plus explicatives (ACP) ;
- Regrouper les accidents similaires (classification non supervisée) ;
- Construire un modèle prédictif de la gravité (classification supervisée) ;
- Extraire des connaissances exploitables à partir des données.

## 6. Critères de succès
Le projet sera considéré comme réussi si :
- Les principaux facteurs de gravité sont clairement identifiés ;
- Des groupes d’accidents cohérents sont mis en évidence ;
- Un modèle prédictif performant est développé ;
- Les résultats sont interprétables et utilisables dans un cadre opérationnel.

## 7. Utilité du projet
Les livrables pourront bénéficier à :
- **Autorités publiques** : pour améliorer la sécurité routière ;
- **Services de police** : pour mieux gérer les zones à risque ;
- **Conducteurs** : pour une sensibilisation ciblée aux facteurs de danger.

## 8. Limites du projet
- La qualité des résultats dépend directement de la qualité des données disponibles ;
- Certaines variables potentiellement importantes peuvent être absentes du jeu de données ;
- Le modèle produit reste une approximation simplifiée d’une réalité complexe.