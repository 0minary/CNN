

## Architecture du projet 



## Architecture du projet

/Projet_CNN/
│── /datasets/                          # Dossier contenant les datasets
│   │── /MNIST/                         # Dataset 1
│   │── /catsAndDogs/                   # Dataset 2
│── /src/                               # Code source du projet
│   │── /data_preprocessing/            # Scripts pour prétraitement des données
│   │   │── preprocess_dataset1.py
│   │   │── preprocess_dataset2.py
│   │── /models/                     # Définition des architectures CNN
│   │   │── cnn_model.py             # Implémentation du CNN
│   │   │── train.py                 # Script d'entraînement
│   │   │── evaluate.py               # Évaluation des modèles
│── /logs/                           # Fichiers de logs et résultats
│   │── training_logs/               # Logs d'entraînement
│   │── evaluation_results/          # Résultats des évaluations
│── /config/                         # Configuration et hyperparamètres
│   │── config.yaml                  # Fichier de configuration global
│── /scripts/                        # Scripts pour automatisation
│   │── train_all.sh                  # Script shell pour entraîner sur les deux datasets
│── /saved_models/                   # Modèles sauvegardés après entraînement
│── requirements.txt                  # Dépendances Python du projet
│── README.md                         # Documentation du projet
│── .gitignore                        # Fichiers à exclure du versionnement

