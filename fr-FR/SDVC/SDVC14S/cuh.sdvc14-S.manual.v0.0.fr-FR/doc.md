---
doc_id: cuh.sdvc14-S.manual.v0.0.fr-FR
doc_key: cuh.sdvc14-S.manual.v0.0
doc_type: manual
lang: fr-FR
product: sdvc14-S
source_pdf: /Users/wangle/Documents/Python开发/说明书转换/典型文档/SDVC11/20250905_66_IDP118_SDVC14-S_SMS-EN_1_04-文档发布单页版.pdf
source_sha256: aa366ff94e0fdfbd3ac8e34d3e32a2aacf33d964e2f2caad26b94afddb136c2f
title: Module de commande numérique à tension variable pour alimentateur vibrant SDVC14-S (Français)
updated_at: 2026-09-30 11:00:00
version: 0.0
---



CUH

# Module de commande numérique à tension variable pour alimentateur vibrant

![SDVC14-S 数字调压振动送料控制模块产品照片](assets/images/cuh.sdvc14-S.manual.v0.0/page-0001-vcrop-00.png)

Modèle : SDVC14-S



## Présentation générale :

![SDVC14-S overview diagram: Remote ON/OFF Control Connector, Remote Speed Control Connector, Full Wave/Half Wave Switch, Fuse, Power Output Connector, and Power Input Connector.](assets/images/cuh.sdvc14-S.manual.v0.0/page-0002-vcrop-00.png)



## Câblage :

![SDVC14-S 接线图：DC:5-24V；K1 Close: Stop，Open: Run；Potentiometer, 100K。输出接线标注 Power Output(L)、Power Output(N)、GND、Output Power Cable；输入接线标注 Power Input(N)、Power Input(L)、GND、Input Power Cable。](assets/images/cuh.sdvc14-S.manual.v0.0/page-0003-vcrop-00.png)




## Interrupteur onde complète/demi-onde :

La forme d'onde/la fréquence de sortie peut être commutée

![Full wave — Figure (1)](assets/images/cuh.sdvc14-S.manual.v0.0/page-0004-vcrop-00.png)

Si la fréquence du réseau est de 50/60Hz, la fréquence de sortie sera de 100/120Hz lorsque l'interrupteur est réglé comme indiqué sur la Figure (1)

![Half Wave — Figure (2)](assets/images/cuh.sdvc14-S.manual.v0.0/page-0004-vcrop-01.png)

Si la fréquence du réseau est de 50/60Hz, la fréquence de sortie sera de 50/60Hz lorsque l'interrupteur est réglé comme indiqué sur la Figure (2)



## Caractéristiques :

1) Régulation automatique de tension : Le circuit interne de régulation numérique de tension peut réduire la variation de vitesse d'alimentation causée par la fluctuation de la tension du réseau.

2) Démarrage progressif : Le contrôleur augmente progressivement la tension de sortie de 0 à la valeur préréglée lors de la mise sous tension afin d'éviter toute secousse soudaine.

3) Commande linéaire de tension : L'angle de rotation du potentiomètre externe est linéaire avec la tension de sortie du module de commande.

4) Connecteurs de commande de signal : Le module de commande dispose de connecteurs pour la commande marche/arrêt à distance et la commande de vitesse à distance.

5) Conception de circuit optimisée pour garantir la stabilité et une longue durée de vie.

6) Protection contre la surchauffe : Si la température interne du module de commande devient trop élevée, le module de commande arrête sa sortie pour se protéger.

7) Protection contre la surintensité : Si le courant de sortie dépasse sa valeur nominale, le module de commande arrête sa sortie pour se protéger lui-même et la charge.

8) Protection par fusible contre les courts-circuits : Si la sortie du module de commande est court-circuitée, le fusible interne fond pour protéger le module de commande et la charge.




## Spécifications :

| Élément | Plage : Min | Plage : Typique | Plage : Max | Unité | Description |
|---|---|---|---|---|---|
| Tension d'entrée | 150 | 220 | 260 | V | AC RMS |
| Plage ajustable de tension de sortie | 35 | —— | Vin-10 | V | Demi-onde |
| | 45 | —— | Vin-5 | | Onde complète |
| Temps de réponse de la régulation de tension | 0 | 0.01 | 0.02 | s | |
| Plage ajustable de courant de sortie | 0.1 | —— | 4 | A | |
| Puissance de sortie | 22 | —— | 880 | VA | |
| Fréquence de sortie | 45 | 50/60 | 65 | Hz | Demi-onde |
| | 90 | 100/120 | 130 | Hz | Onde complète |
| Forme d'onde de sortie | | Sinus découpé en phase | | | |
| Temps de démarrage progressif | 0.5 | 0.65 | 0.7 | s | |
| Température de déclenchement de la protection contre la surchauffe | 58 | 60 | 66 | ℃ | |
| Tension de commande marche/arrêt à distance | 5 | —— | 24 | V | |
| Capacité du fusible | | 6.3 | | A | |
| Température ambiante | 0 | 25 | 40 | ℃ | Sans condensation |
| Humidité ambiante | 10 | 60 | 85 | % | |

## Dimensions et poids :

Dimensions : 102(L)mm X 63(W)mm X 27(H)mm  
Poids : 92g


![CUH QR code](assets/images/cuh.sdvc14-S.manual.v0.0/page-0044-vcrop-00.png)

Nanjing CUH Science & Technology Co.,Ltd  
https://en.cuhnj.com  
Tel.:+86-25-84730411 / 84730415 / 84730416  
Fax:+86-25-84730426  
E-mail:sales@cuhnj.com  
Add.:Building 2, Xueyan Tech Park, Tuscity,  
No.9 Zhineng Rd, Jiangning, Nanjing, China



Document NO. : SDVC14SSMSEN_1.04


