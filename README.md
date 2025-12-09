Nous cherchons à prédire la polarité d’un avis (positif / négatif ) et à comparer des
approches basées sur :
• une ligne de base TF–IDF couplée à des classifieurs linéaires (Régression Logistique, SVM) ;
• un RNN (LSTM) avec embeddings (appris pendant l’entraînement ou pré-entraînés) ;
• un LSTM + attention (Bahdanau), pour améliorer la performance et l’interprétabilité (poids d’attention).
