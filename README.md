# NestEvent

#  EcoSecure-dashboard

![EcoSecure Dashboard Preview](https://via.placeholder.com/1200x600/e8f5e9/2e7d32?text=EcoSecure+Dashboard+Preview)  
<img width="1865" height="545" alt="image" src="https://github.com/user-attachments/assets/5a6b1e1b-c638-468e-b7e3-3a026e14f7bb" />
<img width="1858" height="620" alt="image" src="https://github.com/user-attachments/assets/d3537b6c-bac9-47ed-aab6-65ef23d47eff" />

 **EcoSecure** est un tableau de bord React pour la surveillance en temps réel des systèmes industriels (ventilation, refroidissement, moteurs), avec visualisation de données, alertes et analytics prédictives.

---

## Fonctionnalités principales

-  **Surveillance en temps réel** : État des composants (Fans, Extracteur, Cooling)
-  **Mesures critiques** : Température intérieure/extérieure, vitesse de rotation (RPM), couple (Nm)
-  **Graphiques dynamiques** : Courbes temporelles (Chart.js) pour tendances hebdomadaires
-  **Interface admin** : Accès sécurisé, gestion des alertes, mode sombre

##  Technologies utilisées

| Couche         | Technologie                     |
|----------------|---------------------------------|
| Frontend       | React (JavaScript), Chart.js    |
| Styling        | CSS Modules + Vanilla CSS       |
| Structure      | Modularisée (`components/`, `styles/`, `assets/`) |
| Build          | Vite (rapide) ou Create React App |

##  Structure du projet
eco-secure/
├── public/
│ └── favicon.ico
├── src/
│ ├── assets/ # Icônes, logos, images
│ ├── components/ # Composants React réutilisables
│ │ ├── LoginPage.jsx
│ │ ├── Dashboard.jsx
│ │ ├── MainChart.jsx
│ │ ├── StatCard.jsx
│ │ ├── Topbar.jsx
│ │ └── ConsumptionCard.jsx
│ ├── styles/ # Feuilles de style modulaires
│ │ ├── Login.css
│ │ ├── Dashboard.css
│ │ ├── MainChart.css
│ │ ├── StatCard.css
│ │ └── Topbar.css
│ ├── App.jsx # Racine de l'application
│ ├── main.jsx # Point d'entrée
│ └── index.css # Styles globaux (reset, variables)
├── package.json
├── vite.config.js # Si utilisé avec Vite
└── README.md

---

##  Installation & Démarrage

### Prérequis
- Node.js ≥ 18.x
- npm ≥ 9.x (ou yarn/pnpm)

### Étapes

```bash
# 1. Cloner le dépôt
git clone https://github.com/votre-compte/NestEvent.git
cd frontend

# 2. Installer les dépendances
npm install

# 3. Démarrer le serveur de développement
npm run dev
# → Ouvre http://localhost:5173 (Vite) ou http://localhost:3000 (CRA)
