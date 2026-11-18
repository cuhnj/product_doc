<!-- publish-data-sidecar: section=32 heading='4.5 Commande de vitesse à distance' role=generic source_md=doc.md -->

| Type de signal de commande à distance | Signal de commande à distance | Tension de sortie/Vitesse d'alimentation |
|---|---|---|
| Panel | | La tension de sortie et la vitesse d'alimentation ne sont pas commandées par le signal de commande à distance |
| 20mA | <2mA | Lorsque le mode de tension est manuel, tension de sortie = 0<br>Lorsque le mode de tension est automatique, vitesse d'alimentation = 0<br>L'écran LCD affiche l'information d'erreur « <2mA Err » |
| | 2mA~4 mA | Tension de sortie = 0, vitesse d'alimentation = 0 |
| | 4 mA ~20mA | commande proportionnelle par le signal de commande à distance (0%~100%)<br>Lorsque le mode de tension est manuel, tension de sortie = (courant d'entrée - 4mA)/16 × tension de sortie maximale<br>Lorsque le mode de tension est automatique, vitesse d'alimentation = (courant d'entrée - 4mA)/16 × vitesse d'alimentation maximale |
| 1~5V | <0.5V | Tension de sortie = 0, vitesse d'alimentation = 0<br>L'écran LCD affiche l'information d'erreur « <0.5V Err » |
| | 0.5V~1V | Tension de sortie = 0, vitesse d'alimentation = 0 |
| | 1V~5V | commande proportionnelle par le signal de commande à distance (0%~100%)<br>Lorsque le mode de tension est manuel, tension de sortie = (tension d'entrée 1V)/4 × tension de sortie maximale<br>Lorsque le mode de tension est manuel, tension de sortie = (tension d'entrée 1V)/4 × tension de sortie maximale |
| 0~5V | 0V~5V | commande proportionnelle par le signal de commande à distance (0%~100%)<br>Lorsque le mode de tension est manuel, tension de sortie = tension d'entrée/5 × tension de sortie maximale<br>Lorsque le mode de tension est automatique, vitesse d'alimentation = tension d'entrée/5 × vitesse d'alimentation maximale |
| 0~10V | 0V~10V | commande proportionnelle par le signal de commande à distance (0%~100%)<br>Lorsque le mode de tension est manuel, tension de sortie = tension d'entrée/10 × tension de sortie maximale<br>Lorsque le mode de tension est automatique, vitesse d'alimentation = tension d'entrée/10 × vitesse d'alimentation maximale |
| Meter (potentiomètre) | Rapport de division du potentiomètre <4% | Tension de sortie = 0, vitesse d'alimentation = 0 |
| | Rapport de division du potentiomètre 4%~96% | commande proportionnelle par le signal de commande à distance (0%~100%)<br>Lorsque le mode de tension est manuel, tension de sortie = ((rapport de division - 4%)/92%)× tension de sortie maximale<br>Lorsque le mode de tension est automatique, vitesse d'alimentation =((tension d'entrée tension interne × 4%)/tension interne × 92%) × vitesse d'alimentation maximale |
