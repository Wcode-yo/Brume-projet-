# ☕ BRUME — Configurateur de Café Personnalisé

## 📌 Présentation du projet

**BRUME** est une application web interactive permettant aux clients de créer leur café idéal en personnalisant différents éléments : taille, type de lait et suppléments.

L'objectif est de proposer une expérience utilisateur moderne, intuitive et responsive, avec une visualisation du produit et un calcul du prix en temps réel.

Ce projet est réalisé dans le cadre d'une formation en développement web afin de mettre en pratique **HTML5, CSS3, JavaScript Vanilla, la manipulation du DOM et GitFlow**.

## 🎯 Objectifs du projet

- Créer une interface de personnalisation interactive.
- Permettre au client de choisir les caractéristiques de son café.
- Afficher les modifications en temps réel.
- Calculer automatiquement le prix total.
- Enregistrer la configuration dans le navigateur.
- Présenter un récapitulatif de la commande.
- Garantir une expérience adaptée aux mobiles, tablettes et ordinateurs.
- Organiser le développement à travers GitFlow et GitHub Projects.

## ✨ Fonctionnalités principales

### ☕ Page 1 — Configurateur

L'utilisateur pourra :

- Choisir la taille de son café : Small, Medium ou Large.
- Sélectionner son type de lait.
- Ajouter des suppléments : caramel, vanille, chocolat, etc.
- Visualiser son café personnalisé.
- Consulter le prix total actualisé automatiquement.
- Valider sa configuration.

### 🛒 Page 2 — Résumé de commande

Cette page permettra de :

- Récupérer les données enregistrées dans le `localStorage`.
- Afficher les options choisies par le client.
- Présenter le prix final.
- Vérifier les détails de la commande.
- Revenir au configurateur pour modifier les choix.

## 🛠️ Technologies utilisées

| Technologie | Utilisation |
|---|---|
| HTML5 | Structure sémantique des pages |
| CSS3 | Design, Flexbox et responsive |
| JavaScript Vanilla | Interactions et logique métier |
| DOM | Modification dynamique de l'interface |
| LocalStorage | Conservation de la configuration |
| Figma | Maquettage UX/UI |
| Git & GitHub | Versioning et collaboration |
| GitHub Projects | Organisation des tâches |

## 📂 Structure prévue du projet

- 📁 **assets/** — Images et icônes
- 📁 **css/** — `style.css`, `responsive.css`
- 📁 **js/** — `configurator.js`, `summary.js`
- 📄 **index.html** — Page configurateur
- 📄 **resume.html** — Page récapitulative
- 📄 **README.md** — Documentation du projet

## 🚀 Étapes de développement

### Étape 0 — Planification et organisation

- Initialisation du repository GitHub.
- Création des branches `main` et `develop`.
- Création des branches de fonctionnalités.
- Configuration du tableau Kanban sur GitHub Projects.
- Organisation des tâches et répartition du travail.
- Utilisation obligatoire des Pull Requests.

### Étape 1 — Zoning et architecture

- Création des deux pages HTML5.
- Définition du zoning de l'interface.
- Organisation des différentes sections.
- Mise en place de la structure CSS.

### Étape 2 — Design et responsive

- Création des maquettes sur Figma.
- Intégration du design.
- Mise en place des boutons et sélecteurs interactifs.
- Adaptation aux différentes tailles d'écran.
- Amélioration de l'accessibilité et de l'expérience utilisateur.

### Étape 3 — JavaScript et DOM

- Gestion des événements avec `addEventListener()`.
- Récupération des choix du client.
- Modification dynamique de l'aperçu.
- Calcul automatique du prix.
- Sauvegarde de la commande dans `localStorage`.
- Navigation vers la page récapitulative.
- Affichage des données enregistrées.

## 🌿 Workflow GitFlow

Le projet suit une organisation GitFlow.

| Branche | Rôle |
|---|---|
| `main` | Version stable du projet |
| `develop` | Intégration des fonctionnalités |
| `feature/layout-css` | Structure et mise en page |
| `feature/responsive` | Adaptation responsive |
| `feature/js-configurator` | Interactions JavaScript |
| `feature/order-summary` | Récapitulatif de commande |

**Règles de collaboration :**

- Aucun commit direct sur `main` ou `develop`.
- Chaque fonctionnalité est développée sur sa propre branche.
- Toute intégration passe par une Pull Request.
- Les modifications sont vérifiées avant leur fusion.
- La branche `main` contient uniquement les versions stables.

## 📋 Gestion des tâches — GitHub Projects

Le suivi du projet utilise un tableau Kanban composé de quatre colonnes :

| Statut | Description |
|---|---|
| To Do | Tâches à réaliser |
| In Progress | Tâches en cours |
| Review | Tâches à vérifier |
| Done | Tâches terminées |

Cette organisation permet de suivre l'avancement du projet et de faciliter la collaboration.

## 💻 Installation et exécution

1. Cloner le repository GitHub.
2. Ouvrir le dossier du projet avec Visual Studio Code.
3. Installer l'extension Live Server si nécessaire.
4. Lancer `index.html` avec Live Server.
5. Personnaliser un café et valider la sélection.
6. Consulter le récapitulatif sur `resume.html`.

Le projet ne nécessite ni backend ni base de données.

## ✅ Critères de validation

- [ ] Les deux pages sont fonctionnelles.
- [ ] L'interface est responsive.
- [ ] Les options sont sélectionnables.
- [ ] L'aperçu est mis à jour dynamiquement.
- [ ] Le prix change automatiquement.
- [ ] Les données sont sauvegardées dans `localStorage`.
- [ ] Le résumé affiche correctement la configuration.
- [ ] Le workflow GitFlow est respecté.
- [ ] Les fonctionnalités ont été testées.

## 🔮 Améliorations futures

- Ajout de nouvelles boissons.
- Ajout d'animations lors de la personnalisation.
- Historique des commandes.
- Gestion d'un panier contenant plusieurs produits.
- Intégration d'un backend et d'une base de données.

## 👨‍💻 Équipe de développement

Projet réalisé en équipe dans le cadre de la formation en développement web.

**Méthodologie :** Agile, Kanban et GitFlow.
