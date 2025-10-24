# Humatch---Job-Board-Project-front-
*Un job board moderne pour connecter étudiants et entreprises*

---

## 📌 **Description**
**Humatch** est une plateforme de recherche d'emploi développée dans le cadre d'un projet scolaire. Elle permet aux utilisateurs de :
- **Chercher des offres d'emploi** par mots-clés, localisation ou secteur.
- **Gestion de compte utilisateur** (connexion/inscription/déconnexion).
- **Obtenir le descriptif d'une offre**.
- **Filtrer les résultats** selon des critères précis.
- **Candidater à une offre**.

Le projet utilise une architecture **full-stack** avec :
- **Frontend** : HTML5, CSS3 (vanilla), JavaScript.
- **Backend** : API REST avec **Python Flask**.
- **Base de données** : **SQL** (MySQL) avec une gestion via PHP myadmin.
- **Hébergement** : Déployé sur une **machine virtuelle** (HyperV).

---

## 🛠 **Technologies Utilisées**

| Catégorie       | Technologies                                                                 |
|-----------------|------------------------------------------------------------------------------|
| **Frontend**    | HTML5, CSS3 (Flexbox/Grid), JavaScript (DOM, Fetch API)                     |
| **Backend**     | Python 3.8+, Flask (API REST)                |
| **Base de données** | SQL (MySQL), PHP myadmin (gestion des tables)                    |
| **Outils**      | Git, GitHub, HyperV (pour la VM), Postman (tests API)            |

---

## 📂 **Structure du Projet**

```bash
humatch/
├── frontend/                  # Website Design (HTML/CSS/JS)
│   ├── fonts/                 # Stockage des fonts
│   ├── src/                   # Ressources du projet (images, logo...)
│   ├── index.html             # Page d'accueil
│   ├── apply.html             # Page de candidature
│   ├── offer.html             # Page de description de l'offre
│   ├── connexion.html         # Page d'authentification (connexion)
│   ├── inscription.html       # Page d'authentification (inscription)
│   ├── dashboard.html         # Espace utilisateur (non fonctionnel)
│   ├── styles.css             # Feuille de Style
│
├── backend/                   # API Flask
│   ├── app.py                 # Point d’entrée principal de l’application
│   ├── routes/                # Routes et endpoints API
│   ├── models/                # Modèles SQLAlchemy (ex: People, Companies)
│   ├── utils/                 # Fonctions utilitaires (authentification, JWT, etc.)
│    ├── config/               # Fichiers de configuration
│
├── Base de données MySQL/     # Scripts SQL (création et initialisation des tables)
│   ├── database/export        # export de la base de données en SQL (avec les tables)
│
├── vm/ Humatch_job            # Configuration de la machine virtuelle (Ubuntu 25.04  sur Hyper V, 8GO RAM, 65GO DD, dhcp, 
│
├── .gitignore                 # Fichiers exclus de Git
└── README.md                  # Informations du projet
