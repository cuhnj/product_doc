<!-- publish-data-sidecar: section=67 heading='7.4 Liste des paramètres' role=generic source_md=doc.md -->

| | Paramètre | Affichage | Plage de valeurs/Élément d'énumération | Défaut |
|---|---|---|---|---|
| Groupe de paramètres 4PhotoSen | Sensibilité du capteur photoélectrique intelligent | 01.PortBLimit | PNP, NPN, 1~1000 | 80 |
| Groupe de paramètres 4PhotoSen | Direction logique du port B | 02.PortBDirec | Const, Inv | Const |
| Groupe de paramètres 4PhotoSen | Retard d'enclenchement du port B | 03.PortBUpDly | 0.0~99.9 s | 0.2 |
| Groupe de paramètres 4PhotoSen | Retard de déclenchement du port B | 04.PortBDnDly | 0.0~99.9 s | 0.2 |
| Groupe de paramètres 5On&Off | Type de capteur du port C | 01.PortType | NPN, PNP, Auto1, Auto0 | Auto0 |
| Groupe de paramètres 5On&Off | Direction logique du port C | 02.PortCDirec | Const, Inv | Const |
| Groupe de paramètres 5On&Off | Retard d'enclenchement du port C | 03.PortCUpDly | 0.0~99.9 s | 0.2 |
| Groupe de paramètres 5On&Off | Retard de déclenchement du port C | 04.PortCDnDly | 0.0~99.9 s | 0.2 |
| Groupe de paramètres 6DCoutput | Source d'entrée logique du port D 1 | 01.PortDSour1 | 0, 1, PortB, -PortB, PortC, -PortC, PortD, -PortD, Main, -Main, Err, -Err | 0 |
| Groupe de paramètres 6DCoutput | Source d'entrée logique du port D 2 | 02.PortDSour2 | 0, 1, PortB, -PortB, PortC, -PortC, PortD, -PortD, Main, -Main, Err, -Err | Main |
| Groupe de paramètres 6DCoutput | Relation logique du port D | 03.PortDLogic | And, Or, Xor, RS | Or |
| Groupe de paramètres 6DCoutput | Retard d'enclenchement du port D | 04.PortDUpDly | 0.0~99.9 s | 0.0 |
| Groupe de paramètres 6DCoutput | Retard de déclenchement du port D | 05.PortDDnDly | 0.0~99.9 s | 0.0 |
| Groupe de paramètres 6DCoutput | Mode de sortie du port D | 06.PortDMode | Delay, Hold, Cycle1, Cycle2 | Delay |
| Groupe de paramètres 6DCoutput | Direction logique du port D | 07.PortDDirec | Const, Revrs, On, Off | Const |
| Groupe de paramètres 6DCoutput | Type de sortie de commande | 08.PortDType | Ou_NPN, Ou_PNP, Ou_P&P | Ou_NPN |
| Groupe de paramètres 7Save | Lire tous les paramètres depuis le groupe utilisateur | 01.ReadALLFrm | None, UsrD1, UsrD2, UsrD3 | None |
| Groupe de paramètres 7Save | Enregistrer tous les paramètres dans le groupe utilisateur | 02.SaveALLTo | None, Work, UsrD1, UsrD2, UsrD3 | None |
| Groupe de paramètres 7Save | Restauration des réglages d'usine | 03.RestorALL | None, Work | None |
| Groupe de paramètres 7Save | Identifiant de la machine locale | 04.LoadType | None, Circ, Line, Soli | None |
| Groupe de paramètres 7Save | Numéro d'identification | 05.MachineNum | None, 1~1000 | None |
| Groupe de paramètres 7Save | Mot de passe utilisateur | 06.PassWord | 0~9999 | 0 |
| Groupe de paramètres 8Monitor | Température | 01.Temperatur | -20~85 ℃ | —— |
| Groupe de paramètres 8Monitor | Courant de sortie | 02.CurrentOut | 0.0~150 mA | —— |
| Groupe de paramètres 8Monitor | Tension du signal du port A | 03.Vol_Remote | 0.0~5.0 V | —— |
| Groupe de paramètres 8Monitor | Tension du signal du port B | 04.Vol_PortB | 0~999 | —— |
| Groupe de paramètres 8Monitor | Tension du signal du port C | 05.Vol-PortC | 0.0~26.0 V | —— |
| Groupe de paramètres 8Monitor | Tension du signal du port D | 06.Vol-PortD | 0.0~26.0 V | —— |
| Groupe de paramètres 8Monitor | Tension en temps réel du port 5V | 07.Vol-5V | 0.0~6.0 V | —— |
| Groupe de paramètres 8Monitor | Tension en temps réel du port 24V | 08.Vol-24V | 0.0~26.0 V | —— |
| Groupe de paramètres 8Monitor | Version logicielle de la carte de commande | 09.Version | 0~99.99 | —— |
