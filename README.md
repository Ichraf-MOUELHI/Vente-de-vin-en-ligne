# 🛍️ Fusion ERP & Site E-commerce - Boutique de Vin en Ligne

## 📌 Problématique

Actuellement, notre ERP (système de gestion interne) n'est **pas connecté** au site de vente en ligne. Cela crée des écarts et des inefficacités dans la gestion des ventes, du stock, et du chiffre d’affaires.

## 🎯 Objectif

Créer une **fusion des données** issues de l’ERP et de la boutique en ligne pour :
- Suivre le chiffre d’affaires par produit
- Identifier les produits performants ou problématiques
- Avoir une vision unifiée et exploitable de l’activité e-commerce
- Améliorer la prise de décision et la gestion des stocks

## 🧠 Méthodologie

### ✅ Étape 1 : Fusion des exports
- **ERP** : Références produit, prix de vente, état de stock
- **Site Web** : Nom, description, nombre de ventes
- **Fichier de liaison** : Correspondance entre `product_id` (ERP) et `SKU` (site)

### ✅ Étape 2 : Analyse des ventes
- Calcul du **chiffre d’affaires par produit**
- Total du **chiffre d’affaires en ligne**

### ✅ Étape 3 : Détection des anomalies
- Identification des **valeurs aberrantes**
- Représentation graphique des données
- Nettoyage des doublons et valeurs manquantes

## 📂 Données

Les données sont chargées depuis des fichiers CSV hébergés sur GitHub :
- `Fichier_erp.csv`
- `Fichier_web.csv`
- `fichier_liaison.csv`

## 🛠️ Technologies utilisées

- Python 3
- Pandas, NumPy
- Matplotlib, Seaborn
- SciPy

## 📊 Résultats attendus

- Tableau consolidé des ventes par produit
- Graphiques interactifs pour la visualisation
- Liste des anomalies détectées
- Insights pour améliorer la stratégie de vente en ligne

## 🚀 Lancer le projet

```bash
git clone https://github.com/votre-utilisateur/votre-repo.git
cd votre-repo
# Ouvrir le notebook avec Jupyter ou VSCode
