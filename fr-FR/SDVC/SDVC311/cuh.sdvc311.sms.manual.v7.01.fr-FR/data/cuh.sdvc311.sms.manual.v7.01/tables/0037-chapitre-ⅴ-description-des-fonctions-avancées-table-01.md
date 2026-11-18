<!-- publish-data-sidecar: section=37 heading='5.9 Fonction de verrouillage par mot de passe des paramètres' role=generic source_md=doc.md -->

| Paramètre verrouillé | Indice de forme d'onde | Indice d'accélération | Limitation de la tension de sortie maximale | Opération logique des sources de signaux de la sortie principale | Seconde source de signal de la sortie principale | Première source de signal de la sortie principale | Opération logique des sources de signaux du port de contrôle D | Seconde source de signal du port de contrôle D | Première source de signal du port de contrôle D | Type de capteur du port C | Cycles de freinage/Arrêt progressif | Fréquence de sortie |
|---|---|---|---|---|---|---|---|---|---|---|---|---|
| 1 : Verrouillé | 1 | 1 | 1 | 1 | 1 | 1 | 1 | 1 | 1 | 1 | 1 | 1 |
| 0 : Déverrouillé | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 |
| Facteur de multiplication | 4 | 2 | 1 | 4 | 2 | 1 | 4 | 2 | 1 | 4 | 2 | 1 |
| Plage de la valeur du mot de passe (somme) | 0~7 (1er chiffre de la valeur du mot de passe) | | | 0~7 (2e chiffre de la valeur du mot de passe) | | | 0~7 (3e chiffre de la valeur du mot de passe) | | | 0~7 (4e chiffre de la valeur du mot de passe) | | |
| Exemple 1 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 1 |
| | 0 | | | 0 | | | 0 | | | 1\*1=1 | | |
| Exemple 2 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 0 | 0 | 1 |
| | 1\*4=4 | | | 1\*1=1 | | | 0 | | | 1\*1=1 | | |
| Exemple 3 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 1 | 1 |
| | 0 | | | 0 | | | 0 | | | 1\*4+1\*2+1\*1=7 | | |
