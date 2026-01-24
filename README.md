# Telco_Customer_Prediction

## Présentation du projet
Ce projet exploite un jeu de données de plus de **7 000 clients** d'une entreprise de télécommunications. L'objectif est de répondre aux deux problématiques demandées pour le projet de ML :

1.  **Classification (Variable : `Churn`)** : Identifier les clients susceptibles de quitter l'opérateur.
2.  **Régression**:

---

## Installation et Configuration du Groupe

Pour garantir que le code fonctionne chez tout le monde et éviter les **conflits de fusion Git** sur les fichiers Notebook (.ipynb), merci de suivre rigoureusement cette procédure.

### 1. Installation des bibliothèques
Installez toutes les dépendances nécessaires (pandas, scikit-learn, etc.) en une seule fois :

```bash
pip install -r requirements.txt
```


### 2. Configuration de la protection Git (nbstripout)

**IMPORTANT** : Les fichiers Jupyter (.ipynb) créent souvent des conflits sur Git à cause des images et des temps d'exécution. Nous utilisons nbstripout pour "nettoyer" les notebooks automatiquement avant chaque envoi sur GitHub.

Lancez cette commande une seule fois dans votre terminal :

```bash
python -m nbstripout --install
```


### Membres du groupe

  - Baptiste Pretet

  - Uriel Fagninou