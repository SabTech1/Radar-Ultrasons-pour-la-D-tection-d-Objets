# radar-target-tracking-simulation
Ce dépôt contient un code MATLAB qui simule la planification de tâches radar pour suivre des cibles mobiles dans un environnement donné. Le code effectue les opérations suivantes :

Génération de données initiales : Des positions et des vitesses aléatoires sont générées pour un nombre spécifié de cibles.

Définition des tâches radar : Des tâches radar avec des temps d'exécution et des échéances aléatoires sont définies pour chaque cible.

Simulation du mouvement des cibles et des opérations radar : Le mouvement des cibles est simulé, et les signaux radar sont générés en fonction de leurs positions. La planification des tâches radar est effectuée à l'aide de l'algorithme EDF (Earliest Deadline First).

Évaluation des performances du système : La latence moyenne du système est calculée pour évaluer ses performances.

Visualisation des résultats : Plusieurs graphiques sont générés pour visualiser les trajectoires des cibles, la planification des tâches radar, l'histogramme des latences et la performance du système au fil du temps.

Utilisation :

Pour exécuter la simulation, assurez-vous d'avoir MATLAB installé sur votre système. Téléchargez ou clonez ce dépôt, puis exécutez le fichier principal main.m.

Remarque : Ce code est conçu à des fins éducatives et de démonstration pour illustrer la planification de tâches radar dans un contexte de suivi de cibles mobiles. Les paramètres de simulation et les algorithmes de planification peuvent être ajustés selon les besoins spécifiques du projet.
