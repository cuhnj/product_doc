<!-- publish-data-sidecar: section=48 heading='7.3 Suggestions de dépannage et explications des erreurs' role=generic source_md=doc.md -->

| Code d'erreur | Définition (Phénomène) | Méthodes de dépannage |
|---|---|---|
| Er01A/Er01b | Court-circuit du canal A/B<br>(les deux canaux arrêtent la sortie) | ◆ Assurez-vous que la charge n'est pas en court-circuit, puis essayez de redémarrer la sortie du contrôleur en appuyant deux fois sur le bouton Marche/Arrêt de sortie ou en réalimentant le contrôleur. |
| Er02 | Surintensité combinée des canaux A/B<br>(les deux canaux suspendent la sortie, redémarrage après 2 s) | ◆ Réduisez la tension de sortie de manière appropriée, puis redémarrez la sortie. |
| Er02A/Er02b | Surintensité individuelle du canal A/B<br>(le canal en surintensité arrête la sortie, redémarrage après 2 s) | |
| Er02A./Er02b. | La surintensité individuelle du canal A/B atteint le maximum défini | |
| Er03 | Surchauffe ou refroidissement excessif<br>(les deux canaux arrêtent la sortie, récupération automatique entre -20℃~60℃) | ◆ Installez le contrôleur dans un environnement bien ventilé ou évitez le froid extrême. |
| Er041/Er042 | Sous-tension/surtension de l'alimentation<br>(les deux canaux arrêtent la sortie, récupération automatique) | ◆ Assurez-vous que la tension d'entrée est comprise entre AC 85~250Vac. |
| Er05 | Communication interne anormale<br>(les deux canaux arrêtent la sortie) | ◆ Assurez-vous qu'aucune alimentation externe n'est raccordée au port d'alimentation 24V ou contactez notre support technique. |
| Er06 | Anomalie du capteur de température<br>(les deux canaux arrêtent la sortie) | ◆ Assurez-vous que la température de fonctionnement n'est pas inférieure à -20℃ ou contactez notre support technique. |
| Er07A/Er07b | Court-circuit du port D du canal A/B<br>(la sortie de contrôle du canal A/B s'arrête, tentative de redémarrage après 2 s) | ◆ Assurez-vous que la charge du port D n'est pas en court-circuit et que le courant ne dépasse pas 350mA. |
| Er10 | Sortie d'alimentation 24V anormale<br>(coupe la sortie 24V, tentative de redémarrage après 2 s) | ◆ Assurez-vous que le port 24V n'est pas en court-circuit et que le courant ne dépasse pas 700mA. |
| Er11 | Sortie d'alimentation 5V anormale<br>(la fonction de contrôle de vitesse est temporairement désactivée, redémarrage automatique après restauration) | ◆ Assurez-vous que l'alimentation 5V du port A n'est pas en court-circuit et qu'elle n'est pas raccordée à une tension d'alimentation externe supérieure à 5V. |
| Er12 | Tension d'alimentation 24V anormale<br>(les deux canaux arrêtent la sortie, sortie de contrôle à haute impédance, récupération automatique) | ◆ Assurez-vous qu'aucune alimentation externe n'est raccordée au port d'alimentation 24V. |
