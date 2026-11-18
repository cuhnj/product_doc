<!-- publish-data-sidecar: section=82 heading="7.7 Code d'avertissement" role=generic source_md=doc.md -->

| Code d'avertissement | Affichage | Signification | Méthode d'élimination |
|---|---|---|---|
| Warn01 | Saturate | Saturation de sortie | Réduisez la tension de sortie |
| Warn02 | decline | Ralentissement du comptage | État de décélération du comptage |
| Warn03 | CND | Fin de comptage | État de fin de comptage |
| Warn04 | FrqncyLo | La fréquence de sortie est trop basse | Augmentez la valeur du paramètre de décalage de fréquence |
| Warn05 | FrqncyHi | La fréquence de sortie est trop élevée | Augmentez la valeur du paramètre de décalage de fréquence |
| Warn06 | LoMAlarm | Manque de matière | Réduisez la valeur du paramètre d'alarme de manque de matière, ou ajoutez de la matière dans le plateau |
| Warn07 | PortDErr | Surintensité de sortie du port D | Réduisez la charge de commande du port de sortie |
| Warn08 | RemotLow | La tension/le courant d'entrée de contrôle à distance est trop faible | Augmentez la tension ou le courant d'entrée de contrôle à distance |
| Warn09 | MRSErr | Erreur logique RS de la sortie principale | Lorsque la logique de sortie est une bascule RS, les signaux de la source principale 1 et de la source principale 2 ne peuvent pas être valides simultanément |
| Warn10 | 24VErr | Erreur 24V | Ne connectez pas l'alimentation externe 24V au port de sortie du contrôleur |
| Warn11 | 5VErr | Erreur 5V | Ne connectez pas l'alimentation externe 5V au port de sortie du contrôleur |
| Warn12 | CtrlRSErr | Erreur logique RS de la sortie de commande | Lorsque la logique du port D est une bascule RS, les signaux de la source 1 du port D et de la source 2 du port D ne peuvent pas être valides simultanément |
| Warn13 | OverLoad | Surcharge du capteur d'accélération | Remplacez le capteur d'accélération par un modèle de plage appropriée |
| Warn14 | AcceleEr | Défaillance du capteur d'accélération | Le capteur est endommagé, remplacez-le par un neuf |
| Warn15 | EEPErr | Erreur d'enregistrement des paramètres | Vérifiez que la ligne de communication CUHBus-DS® est correctement connectée et que la mise en réseau est correctement terminée. |
