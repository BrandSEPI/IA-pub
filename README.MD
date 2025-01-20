# Travel Order Resolver

## Description

Travel Order Resolver est un projet qui utilise le traitement du langage naturel (NLP) pour traiter des commandes de voyage formulées en français. Le programme prend en entrée des ordres de voyage sous forme de texte ou de voix, et produit un itinéraire approprié en identifiant les départs et les destinations.

## Fonctionnalités

- **Traitement du Langage Naturel (NLP)** : Identification des commandes de voyage, extraction des villes de départ et d'arrivée.
- **Reconnaissance Vocale** (optionnelle) : Convertit la voix en texte (STT) pour traiter les commandes vocales (en utilisant [VOSK](https://alphacephei.com/vosk/)).
- **Optimisation de Trajet** : Trouve le meilleur chemin dans un graphe pour les connexions de train.

## Installation

1. Clonez le dépôt :

   ```bash
   git clone <url_du_dépôt>
   cd Travel-Order-Resolver

   ```

2. Créez et activez un environnement virtuel :

   ```bash
    python -m venv env
    .\env\Scripts\activate  # Sur Windows
    source env/bin/activate  # Sur macOS/Linux
   ```

3. Installez les dépendances :

   ```bash
   pip install -r requirements.txt
   ```

## Utilisation

    python directTranslate.py
