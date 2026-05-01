# 🎓 SkillBadge – Certification blockchain des compétences numériques


## 📌 Description du projet

**SkillBadge** est une plateforme de certification numérique basée sur la blockchain qui permet aux jeunes autodidactes burkinabè de prouver leurs compétences techniques auprès des recruteurs.

### Problème identifié

Au Burkina Faso :
- **15 000+** jeunes se forment au numérique chaque année via des canaux informels
- **Moins de 5%** obtiennent une certification reconnue par les employeurs
- **70%** des recruteurs IT peinent à évaluer les profils autodidactes

### Solution proposée

SkillBadge permet à des **formateurs habilités** d'émettre des **badges NFT** (standard ERC-5192 Soulbound) pour chaque compétence acquise. Les apprenants disposent d'un **portfolio public** et les recruteurs peuvent **vérifier instantanément** l'authenticité des badges.



## 🚀 Fonctionnalités principales

### 🎓 Espace Formateur
- Création de types de badges (nom, niveau, domaine, organisation)
- Attribution de badges aux apprenants
- Suggestion automatique du niveau suivant (Débutant → Intermédiaire → Expert)
- Révocation de badges
- Export des preuves blockchain

### 👤 Espace Apprenant
- Portfolio public avec adresse wallet unique
- Visualisation des badges obtenus
- Progression par domaine (barres et étapes)
- Partage du portfolio par email ou WhatsApp

### 🔍 Espace Recruteur
- Vérification par adresse wallet
- Affichage de la progression par domaine
- Détails des transactions (TX, bloc, IPFS)
- **Aucune connexion requise**



## 🛠️ Technologies utilisées

| Catégorie | Technologies |
|-----------|--------------|
| **Frontend** | HTML5, CSS3, TailwindCSS, JavaScript |
| **Stockage** | localStorage (simulation blockchain) |
| **Blockchain** | Simulation Polygon Amoy Testnet (ERC-5192) |
| **Hébergement** | Netlify |

### Simulation blockchain
Le projet simule une blockchain Polygon avec des identifiants réalistes :
- Transactions : `0x7a3f...c2e9`
- Blocs : `14800000+`
- IPFS : `QmWn...a1B2`

**Migration possible** vers une vraie blockchain en remplaçant les fonctions `randomTx()`, `randomIpfs()`, `randomBlock()` par des appels ethers.js.



## 📦 Installation et exécution locale

### Prérequis
- Navigateur web moderne (Chrome, Firefox, Edge)
- Aucun serveur requis

### Étapes d'installation

```bash
# 1. Cloner le dépôt
git clone https://github.com/votre-compte/skillbadge.git

# 2. Accéder au dossier
cd skillbadge

# 3. Ouvrir le fichier dans le navigateur
# Windows
start index.html

# Mac
open index.html

# Linux
xdg-open index.html