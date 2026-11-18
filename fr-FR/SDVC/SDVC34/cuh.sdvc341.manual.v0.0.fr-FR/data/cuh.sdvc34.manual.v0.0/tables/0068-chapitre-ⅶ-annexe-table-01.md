<!-- publish-data-sidecar: section=68 heading='7.4.8 Groupe de paramètres de communication' role=generic source_md=doc.md -->

| Fonction | Paramètre | Affichage | Plage de valeurs/Élément d'énumération | Valeur par défaut |
|---|---|---|---|---|
| P8.01 | Type de communication 485BUS | 01.485type | ASCII, RTU | RTU |
| P8.02 | Débit en bauds de la communication 485 | 02.BaudRate | 0.3, 1.2, 2.4, 9.6, 19.2, 57.6, 115.2 Kbps | 115.2 |
| P8.03 | Numéro d'identification de l'esclave de communication 485 | 03.485SlvID | 1~31 | 1 |
| P8.04 | Activation de la résistance d'adaptation du port de communication 485 | 04.Enab485R | None, Valid | None |
| P8.05 | Adresse de synchronisation numérique locale | 05.DigSynAd | 1~8 |  |
| P8.06 | Activation de la résistance d'adaptation du port de communication de synchronisation numérique | 06.EnabSynR | None, Valid | None |
| P8.07 | Adresse du signal de bus de la source d'entrée 1 de la logique du port de sortie principale | 07.BSigMID1 | 1~8 |  |
| P8.08 | Adresse du signal de bus de la source d'entrée 2 de la logique du port de sortie principale | 08.BSigMID2 | 1~8 |  |
| P8.09 | Adresse du signal de bus de la source d'entrée 1 de la logique du port D | 09.BSgD_ID1 | 1~8 |  |
| P8.10 | Adresse du signal de bus de la source d'entrée 2 de la logique du port D | 10.BSgD_ID2 | 1~8 |  |
| P8.11 | Adresse de bit du signal de bus de la source d'entrée 1 de la logique du port de sortie principale | 11.BSigM_B1 | 1~16 | 5 |
| P8.12 | Adresse de bit du signal de bus de la source d'entrée 2 de la logique du port de sortie principale | 12.BSigM_B2 | 1~16 | 6 |
| P8.13 | Adresse de bit du signal de bus de la source d'entrée 1 de la logique du port D | 13.BSigD_B1 | 1~16 | 5 |
| P8.14 | Adresse de bit du signal de bus de la source d'entrée 2 de la logique du port D | 14.BSigD_B2 | 1~16 | 6 |
| P8.15 | Signal de l'adresse de bit 1 du signal de bus local | 15.LBSig_B1 | Voir Annexe 7.4.11 | 0 |
| P8.16 | Signal de l'adresse de bit 2 du signal de bus local | 16.LBSig_B2 | Voir Annexe 7.4.11 | 1 |
| P8.17 | Signal de l'adresse de bit 3 du signal de bus local | 17.LBSig_B3 | Voir Annexe 7.4.11 | SpeedA |
| P8.18 | Signal de l'adresse de bit 4 du signal de bus local | 18.LBSig_B4 | Voir Annexe 7.4.11 | SpeedB |
| P8.19 | Signal de l'adresse de bit 5 du signal de bus local | 19.LBSig_B5 | Voir Annexe 7.4.11 | In_PtC |
| P8.20 | Signal de l'adresse de bit 6 du signal de bus local | 20.LBSig_B6 | Voir Annexe 7.4.11 | In_PtE |
| P8.21 | Signal de l'adresse de bit 7 du signal de bus local | 21.LBSig_B7 | Voir Annexe 7.4.11 | FCntSi |
| P8.22 | Signal de l'adresse de bit 8 du signal de bus local | 22.LBSig_B8 | Voir Annexe 7.4.11 | DCntSi |
| P8.23 | Signal de l'adresse de bit 9 du signal de bus local | 23.LBSig_B9 | Voir Annexe 7.4.11 | Ctr_O |
| P8.24 | Signal de l'adresse de bit 10 du signal de bus local | 24.LBSigB10 | Voir Annexe 7.4.11 | Warn |
| P8.25 | Signal de l'adresse de bit 11 du signal de bus local | 25.LBSigB11 | Voir Annexe 7.4.11 | Main |
| P8.26 | Signal de l'adresse de bit 12 du signal de bus local | 26.LBSigB12 | Voir Annexe 7.4.11 | -SpeedA |
| P8.27 | Signal de l'adresse de bit 13 du signal de bus local | 27.LBSigB13 | Voir Annexe 7.4.11 | -SpeedB |
| P8.28 | Signal de l'adresse de bit 14 du signal de bus local | 28.LBSigB14 | Voir Annexe 7.4.11 | -In_PtC |
| P8.29 | Signal de l'adresse de bit 15 du signal de bus local | 29.LBSigB15 | Voir Annexe 7.4.11 | -In_PtE |
| P8.30 | Signal de l'adresse de bit 16 du signal de bus local | 30.LBSigB16 | Voir Annexe 7.4.11 | -FCtSi |
| P8.31 | Activation de la fonction d'ajout au réseau | 31.EnNetwok | Online, Offlin, Expand, Replace |  |
| P8.32 | Numéro de l'appareil à retirer du réseau | 32.DeltDevi | 1~8 |  |
| P8.33 | Numéro de synchronisation de fréquence locale | 33.FrqncSyn | 1~8 |  |
| P8.34 | Numéro de synchronisation de la régulation de vitesse à distance locale | 34.RemotSyn | 1~8 |  |
| P8.35 | Données de contrôle à distance | 35.RemotDat | ManVol, RemVol, ManSpd, RemSpd | ManVol |
