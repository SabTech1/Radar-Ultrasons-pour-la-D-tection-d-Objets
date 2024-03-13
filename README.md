# Projet de Radar Ultrasonique avec Arduino
Ce projet utilise un capteur à ultrasons connecté à une carte Arduino pour détecter la distance des objets et afficher les informations sur un écran LCD. En fonction de la distance mesurée, différentes LEDs s'allument et un buzzer émet des sons pour avertir de la présence d'objets à proximité.

# Matériel requis
* Arduino Uno (ou autre modèle compatible)
* Capteur à ultrasons HC-SR04
* Écran LCD 16x2
* LEDs (rouge, bleu, verte)
* Buzzer actif
* Résistances
* Câbles de connexion
# Bibliothèques utilisées
1. LiquidCrystal.h : Utilisée pour contrôler l'écran LCD.
2. math.h : Utilisée pour les calculs trigonométriques pour déterminer l'angle d'observation.
# Configuration du matériel
- Connectez le capteur à ultrasons HC-SR04 aux broches appropriées de l'Arduino.
- Connectez l'écran LCD à l'Arduino.
- Connectez les LEDs et le buzzer aux broches de sortie numériques de l'Arduino.
# Fonctionnement
Le programme mesure la distance des objets à l'aide du capteur à ultrasons et calcule également l'angle d'observation. En fonction de la distance mesurée, les LEDs et le buzzer sont contrôlés pour avertir de la proximité des objets. Les informations sur la distance mesurée et l'angle d'observation sont affichées sur l'écran LCD.

# Contributions
Les contributions sont les bienvenues ! Si vous souhaitez contribuer à ce projet, n'hésitez pas à soumettre une demande d'extraction avec vos modifications.

