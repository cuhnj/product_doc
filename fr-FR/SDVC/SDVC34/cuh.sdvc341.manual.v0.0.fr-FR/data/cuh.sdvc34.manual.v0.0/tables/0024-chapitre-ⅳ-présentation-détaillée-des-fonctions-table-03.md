<!-- publish-data-sidecar: section=24 heading='4.4.1.5 Mode principal' role=generic source_md=doc.md -->

| Signal de contrôle à distance | Signal de contrôle à distance | Tension de sortie/Vitesse d'alimentation |
|---|---|---|
| Panel |  | La tension de sortie et la vitesse d'alimentation ne sont pas contrôlées par le signal de contrôle à distance |
| 20mA | <2mA | Lorsque le mode tension est Manuel, tension de sortie = 0<br>Lorsque le mode tension est Auto, vitesse d'alimentation = 0<br>L'écran LCD affiche l'information d'erreur « Sous-tension de la commande à distance » |
|  | 2mA~4mA | Tension de sortie = 0, vitesse d'alimentation = 0 |
|  | 4mA~20mA | Contrôlé proportionnellement par le signal de contrôle à distance (0%~100%)<br>Lorsque le mode tension est Manuel, tension de sortie = (courant d'entrée - 4mA)/16 × tension de sortie max.<br>Lorsque le mode tension est Auto, vitesse d'alimentation = (courant d'entrée - 4mA)/16 × vitesse d'alimentation max. |
| 1~5V | Moins de 0.5V | Tension de sortie = 0, vitesse d'alimentation = 0<br>L'écran LCD affiche l'information d'erreur « Sous-tension de la commande à distance » |
|  | 0.5V~1V | Tension de sortie = 0, vitesse d'alimentation = 0 |
|  | 1V~5V | Contrôlé proportionnellement par le signal de contrôle à distance (0%~100%)<br>Lorsque le mode tension est Manuel, tension de sortie = (tension d'entrée - 1V)/4 × tension de sortie max.<br>Lorsque le mode tension est Auto, vitesse d'alimentation = (tension d'entrée - 1V)/4 × vitesse d'alimentation max. |
| 0~5V | 0V~5V | Contrôlé proportionnellement par le signal de contrôle à distance (0%~100%)<br>Lorsque le mode tension est Manuel, tension de sortie = tension d'entrée/5 × tension de sortie max.<br>Lorsque le mode tension est Auto, vitesse d'alimentation = tension d'entrée/5 × vitesse d'alimentation max. |
| 0~10V | 0V~10V | Contrôlé proportionnellement par le signal de contrôle à distance (0%~100%)<br>Lorsque le mode tension est Manuel, tension de sortie = tension d'entrée/10 × tension de sortie max.<br>Lorsque le mode tension est Auto, vitesse d'alimentation = tension d'entrée/10 × vitesse d'alimentation max. |
| DigSym | Digital Sync | La tension du signal de contrôle à distance est la tension d'entrée de contrôle à distance d'un appareil spécifié sur le bus (spécifié via les paramètres de synchronisation de contrôle à distance)<br>Contrôlé proportionnellement par le signal de tension d'entrée de contrôle à distance d'un appareil spécifié sur le bus, avec une plage de tension de 0% à 100%.<br>Lorsque le mode tension est Manuel, tension de sortie = tension d'entrée/10 × tension de sortie max.<br>Lorsque le mode tension est Auto, vitesse d'alimentation = tension d'entrée/10 × vitesse d'alimentation max. |
