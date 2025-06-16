Smart Waste Detection 🚀
========================

À propos du projet
------------------

Le *Smart Waste Detection* est un système intelligent de détection et classification automatique des déchets utilisant l'intelligence artificielle, spécialement conçu pour aider les agents de maintenance de l'école à maintenir un environnement propre et sain.

Ce projet permet d'identifier automatiquement si un objet constitue un déchet et de le classer dans la catégorie de recyclage appropriée, facilitant ainsi le travail quotidien des équipes de nettoyage de l'ENSAM Meknès et contribuant à rendre notre établissement plus propre.

Grâce à des techniques avancées d'apprentissage automatique et de vision par ordinateur, notre système analyse les images d'objets en temps réel et fournit une classification précise pour optimiser le processus de tri des déchets dans l'environnement scolaire.

Équipe de développement
-----------------------

Étudiants
~~~~~~~~~

* *Youssef ES-SAAIDI* - `GitHub <https://github.com/YoussefAIDT>`_
* *Zakariae ZEMMAHI* - `GitHub <https://github.com/zakariazemmahi>`_  
* *Mohamed HAJJI* - `GitHub <https://github.com/mohamedhajji11>`_

Encadrant
~~~~~~~~~

* *MASROUR Tawfik* - - `GitHub <https://github.com/MasrourTawfik>`_

Institution
~~~~~~~~~~~

*École Nationale Supérieure d'Arts et Métiers (ENSAM) - Meknès, Maroc*

*Filière :* Génie Intelligence Artificielle et Technologies de Data - Systèmes Industriels

Fonctionnalités principales
---------------------------

.. raw:: html

   <div class="feature-grid">
     <div class="feature-card">
       <h3>🔍 Détection Intelligente</h3>
       <p>Détecte automatiquement si un objet est un déchet grâce à des algorithmes d'IA avancés</p>
     </div>
     <div class="feature-card">
       <h3>🗂 Classification Avancée</h3>
       <p>Classe précisément en 5 catégories principales de recyclage</p>
     </div>
     <div class="feature-card">
       <h3>⚡ Interface Streamlit</h3>
       <p>Interface web moderne, interactive et facile à utiliser</p>
     </div>
   </div>

Types de déchets supportés
--------------------------

Notre système reconnaît et classe les déchets selon 5 catégories principales :

.. raw:: html

   <span class="waste-type">🥤 Plastique</span>
   <span class="waste-type">🍷 Verre</span>
   <span class="waste-type">🥫 Métal</span>
   <span class="waste-type">📄 Papier</span>
   <span class="waste-type">📦 Carton</span>

Détail des catégories
~~~~~~~~~~~~~~~~~~~~~

*🥤 Plastique*
    Bouteilles, sacs plastiques, contenants alimentaires

*🍷 Verre* 
    Bouteilles en verre, bocaux, verres cassés
    
    .. note::
       Cette catégorie inclut également la porcelaine et la céramique qui suivent des processus de recyclage similaires

*🥫 Métal*
    Canettes en aluminium, boîtes de conserve, objets métalliques

*📄 Papier*
    Journaux, documents, papier d'emballage

*📦 Carton*
    Boîtes en carton, carton ondulé

Précision sur la catégorie "Verre"
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

La catégorie "Verre" englobe non seulement les objets en verre traditionnel, mais aussi :

* La porcelaine (assiettes, tasses, objets décoratifs)
* La céramique 
* La faïence

Cette classification est justifiée par le fait que ces matériaux partagent des caractéristiques similaires en termes de traitement et de recyclage, nécessitant souvent des processus de traitement thermique à haute température.

Interface Streamlit
-------------------

*Streamlit* est un framework Python open-source qui permet de créer rapidement des applications web interactives pour les projets de data science et d'apprentissage automatique.

Avantages de Streamlit pour notre projet
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

* *Simplicité* : Interface intuitive sans nécessité de connaissances en développement web
* *Interactivité* : Widgets intégrés pour l'upload d'images et l'affichage des résultats
* *Temps réel* : Mise à jour instantanée des résultats de classification
* *Déploiement facile* : Possibilité de déployer rapidement sur le cloud
* *Visualisation* : Affichage optimisé des images et des résultats de classification

Fonctionnalités de l'interface
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

L'interface permet aux utilisateurs de :

* Télécharger une image via drag & drop ou sélection de fichier
* Visualiser l'image analysée
* Obtenir instantanément le résultat de classification
* Voir le niveau de confiance de la prédiction

Documentation
-------------

.. toctree::
   :maxdepth: 2
   :caption: Sommaire

   guide_utilisation
   explication_projet
   explication_code
   chatbot

Project Structure
------------------

Voici la structure du projet `waste-detection-yolov8` :

.. code-block:: text

    waste-detection-yolov8/                     # Répertoire racine du projet
    ├── Models/                                 # Contient des notebooks liés à la vision par ordinateur
    │   ├── Application_de_comptur_vision.ipynb # Notebook de détection 
    │   └── Smart_waste_detection.ipynb         # Autre notebook d'application de détection
    ├── ModelsSauvegarde/                       # Sauvegarde des anciens modèles )
    ├── docs                                    # Répertoire de documentation (Read the Docs)
    ├── .readthedocs.yml                        # Fichier de configuration pour Read the Docs
    ├── yolov8_best.pt                          # Modèle YOLOv8 entraîné pour la détection des déchets
    ├── yolov8_waste_detect.ipynb               # Notebook principal pour tester le modèle YOLOv8
    └── README.md                               # Fichier de description du projet 

Impact environnemental
----------------------

Ce projet s'inscrit dans une démarche de développement durable en :

* Aidant les agents de maintenance de l'école dans leur travail quotidien
* Facilitant le tri sélectif automatisé dans l'environnement scolaire
* Réduisant les erreurs de classification des déchets
* Optimisant les processus de recyclage à l'ENSAM
* Contribuant à maintenir un campus plus propre et respectueux de l'environnement
* Sensibilisant la communauté étudiante à l'importance du tri des déchets

.. note::
   Projet réalisé dans le cadre de la formation en Intelligence Artificielle à l'ENSAM Meknès - 2024/2025
