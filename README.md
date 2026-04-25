# ventaScop
application de collecte et d'analyse de donnees de ventes

 Présentation générale

**VentaScope** est une application web monopage (HTML/CSS/JavaScript) dédiée à la **collecte, la gestion et l'analyse descriptive des données commerciales**. Elle s'adresse aux entreprises, commercants et étudiants souhaitant centraliser leurs transactions de ventes et en extraire des statistiques utiles.

---

 Modules de l'application

# Module 1 — Saisie des données
Formulaire structuré permettant d'enregistrer chaque transaction avec les champs suivants :
- Date de vente, Nom du vendeur, Produit/Service
- Catégorie (Électronique, Informatique, Services, etc.)
- Quantité et Prix unitaire (calcul automatique du montant total)
- Région parmi les **10 régions du Cameroun**
- Canal de vente (Boutique, En ligne, Téléphone, Partenaire)
- Statut (Complétée, En attente, Annulée)
- Client et Remarques

# Module 2 — Gestion des données
- Tableau interactif de toutes les transactions enregistrées
- **Recherche en temps réel** par vendeur, produit, région ou statut
- **Pagination** (10 enregistrements par page)
- Suppression individuelle de chaque enregistrement
- **Export CSV** et **Export JSON** des données

# Module 3 — Analyse descriptive
- **4 indicateurs clés** : nombre total de ventes, chiffre d'affaires, vente moyenne, vente maximale
- **5 graphiques automatiques** :
  - Répartition des ventes par catégorie (diagramme en anneau)
  - Chiffre d'affaires par région (histogramme)
  - Évolution du CA dans le temps (courbe)
  - Répartition par canal de vente (camembert)
  - Distribution des statuts (barres)
- **Tableau de statistiques descriptives** complet : effectif N, minimum, maximum, somme, moyenne, médiane, écart-type, Q1 et Q3



# Caractéristiques techniques

- **Technologie** : HTML5, CSS3, JavaScript
- **Stockage** : localStorage du navigateur (aucune base de données externe)
- **Responsive** : navigation mobile adaptée avec barre inférieure
- **Aucune installation** requise — fonctionne directement dans le navigateur
- **Données de démonstration** préchargées au premier lancement


# Qualités de l'application

  Critère et Détail 

 1 Créativité :Interface sombre moderne, typographie distinctive, animations fluides |
 2 Robustesse  :Validation des champs obligatoires, gestion des erreurs, données persistantes |
 3 Efficacité  :Analyse instantanée, export en 1 clic, navigation intuitive |
 4 Secteur :Commerce / Ventes — contexte camerounais (régions, FCFA) |

---

# Réalisée dans le cadre de

> **INF 232 — EC2 : Analyse de données**
> TP : Application de collecte et analyse descriptive des données
> Étudiant : **Nkoum Belinga Felix Berenger** de matricule**24g2871**
