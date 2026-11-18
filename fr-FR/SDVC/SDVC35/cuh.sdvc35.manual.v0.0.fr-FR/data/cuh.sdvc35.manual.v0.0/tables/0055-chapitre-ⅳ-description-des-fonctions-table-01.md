<!-- publish-data-sidecar: section=55 heading='Annexe E : Description des avertissements et erreurs et suggestions de dépannage' role=generic source_md=doc.md -->

| Affichage de panne | Type de panne | Suggestions de dépannage |
|---|---|---|
| 24VErr | Erreur d'alimentation interne 24V | Défaillance de l'alimentation interne 24V du contrôleur, veuillez nous contacter pour la réparation |
| 5VErr | Erreur d'alimentation interne 5V | Défaillance de l'alimentation interne 5V du contrôleur, veuillez nous contacter pour la réparation |
| <2mA Err | Le courant d'entrée du signal de commande à distance est trop faible sur le port A | Le courant d'entrée du signal de commande à distance est trop faible sur le port A ; veillez à ce qu'il soit supérieur à 2mA |
| <0.5V Err | La tension d'entrée du signal de commande à distance est trop faible sur le port A | La tension d'entrée du signal de commande à distance est trop faible sur le port A ; veillez à ce qu'elle soit supérieure à 0.5V |
| CommErr(1~5) | Erreur de communication | Veuillez nous contacter pour la réparation |
| decline | Décélération du comptage | Lorsque le nombre compté atteint la « End Count » que vous avez réglée, la tension de sortie (ou la vitesse d'alimentation) diminue |
| EEPErr | Erreur d'enregistrement des paramètres prédéfinis | Veuillez nous contacter pour la réparation |
| FrqncyHi | Fréquence de référence de synchronisation trop élevée | La fréquence d'entrée du signal de synchronisation du contrôleur esclave est supérieure à 400Hz<br>Assurez-vous que la fréquence du signal de synchronisation est comprise entre 25 Hz et 400 Hz |
| FrqncyLo | Fréquence de référence de synchronisation trop faible | La fréquence d'entrée du signal de synchronisation du contrôleur esclave est inférieure à 25Hz<br>Assurez-vous que la fréquence du signal de synchronisation est comprise entre 25 Hz et 400 Hz |
| OverHot | Surchauffe | La température interne du contrôleur dépasse 65 ℃<br>Assurez-vous que le contrôleur fonctionne dans un environnement bien ventilé |
| OverLoad | Surcharge du capteur de vibration | Le capteur de vibration a détecté une accélération dépassant sa valeur d'amplitude absolue |
| OvrCurrt | Surintensité | Le courant de sortie du contrôleur dépasse 3A |
| OvrVoltg | Surtension | La tension de sortie du contrôleur dépasse 260V<br>Assurez-vous que la plage de tension d'entrée est comprise entre 85V et 260V |
| PortDErr | Erreur du port D | L'écart de tension de sortie du port D dépasse 3V<br>Assurez-vous que la puissance de charge du port D ne dépasse pas 4.8W |
| PortPErr | Erreur du port P | L'écart de tension de sortie du port P dépasse 3V<br>Assurez-vous que la puissance de charge du port P ne dépasse pas 4.8W |
| Saturate | Saturation de sortie | Lorsque la tension de sortie du contrôleur est supérieure à la tension d'entrée, le contrôleur entre en état de saturation |
| Save | Enregistrement des paramètres prédéfinis | Après l'opération de recherche automatique de la fréquence de résonance, les paramètres associés sont enregistrés avec succès |
| SenorErr | Défaut du capteur de vibration | Le signal du capteur de vibration est anormal, veuillez nous contacter pour la réparation |
| SenTypEr | Erreur de type de capteur de vibration | Le type de capteur de vibration raccordé au contrôleur ne correspond pas au paramètre « type de capteur de vibration » réglé dans le contrôleur |
| Short | Court-circuit | La sortie du contrôleur est en court-circuit ; assurez-vous que la borne de sortie n'est pas court-circuitée |
| SynchErr | Erreur de signal de synchronisation | Le fil de signal de synchronisation n'est pas raccordé au contrôleur esclave<br>Assurez-vous que le fil de signal de synchronisation est correctement raccordé au contrôleur |
| UndrVolt | Sous-tension | La tension d'entrée du contrôleur est inférieure à 85V.<br>Assurez-vous que la plage de tension d'entrée est comprise entre 85V et 260V |
| UpgradeSlv | Mise à jour du firmware | Le firmware est en cours de mise à jour ; le contrôleur revient à la normale après la mise à jour |
