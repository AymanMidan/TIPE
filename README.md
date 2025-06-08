# README - Modélisation Aérodynamique des Balles de Football

## Auteur
**Ayman Midan**  
N° SCEI : 45451  

## Contexte
Ce travail explore l'influence de la conception des balles de football sur leurs trajectoires, en combinant des approches théoriques, numériques (CFD) et expérimentales. L'objectif est d'optimiser les performances aérodynamiques des balles en étudiant les forces en jeu (traînée, portance, effet Magnus) et les caractéristiques des couches limites.

---

## Structure du Projet

### 1. Introduction
Présentation des enjeux liés à l'aérodynamique des balles de sport et des objectifs de l'étude.

### 2. Étude Théorique et Simulation Numérique
- **Forces en jeu** : Poids, traînée, portance, et effet Magnus.
- **Modélisation mathématique** :  
  - Équations du mouvement (Newton) avec résolution analytique et numérique (Runge-Kutta).  
  - Coefficients aérodynamiques (\(C_D\), \(Re\), \(Sp\)) et leur impact.  
- **Simulation CFD** : Comparaison de deux balles (32 panneaux cousus vs 14 panneaux thermosoudés) à l'aide d'ANSYS Fluent.

### 3. Étude Approfondie de l'Aérodynamique
- **Couches limites** : Transition laminaire-turbulent et son effet sur la traînée.  
- **Effet Magnus** : Déviation des trajectoires due à la rotation, illustrée par le principe de Bernoulli.  

### 4. Expérimentation
- **Protocole** : Frappes de ballons dans des conditions contrôlées (vitesse, angle, pression).  
- **Résultats** : Mesures de temps de vol et déviations, comparant des ballons avec coutures profondes vs superficielles.  

### 5. Conclusions
- **Simulations CFD** : La balle à 14 panneaux (Teamgeist) montre une traînée réduite de 6% et une meilleure stabilité.  
- **Expérience** : Les ballons à coutures moins profondes (Ballon 1) offrent des trajectoires plus stables et précises.  
- **Synthèse** : L'équilibre entre réduction de traînée et stabilité est crucial pour la conception optimale.  

---

## Annexes
- **Codes Python** : Implémentation de la méthode de Runge-Kutta pour la résolution numérique.  
- **Visualisations** : Graphiques des coefficients de traînée et Magnus en fonction des paramètres adimensionnels.  

---

## Outils Utilisés
- **Logiciels** : ANSYS Fluent (CFD), Python (simulations numériques).  
- **Méthodes** : Analyse dimensionnelle, théorème de Bernoulli, modélisation des couches limites.  

---

## Résultats Clés
- La transition turbulente réduit la traînée au-delà d'un nombre de Reynolds critique (\(Re \approx 3.85 \times 10^5\)).  
- L'effet Magnus est maximisé pour des paramètres de rotation (\(Sp\)) entre 0.2 et 0.4.  
- Les coutures augmentent la traînée mais améliorent la stabilité de la trajectoire.  

---

## Perspectives
- Étendre l'étude à d'autres designs de balles (e.g., surfaces texturées).  
- Intégrer des effets environnementaux (vent, humidité).  

---

## Références
- Principes de mécanique des fluides (Bernoulli, Reynolds).  
- Données expérimentales et simulations CFD comparatives.  

---

**Contact** : aymanmidan2005@gmail.com  
**Date** : 06/2024  
