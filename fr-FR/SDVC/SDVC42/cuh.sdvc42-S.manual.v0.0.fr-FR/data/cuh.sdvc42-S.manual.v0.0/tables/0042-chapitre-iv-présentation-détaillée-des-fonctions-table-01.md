<!-- publish-data-sidecar: section=42 heading='4.6.6 Priorité RS' role=generic source_md=doc.md -->

| Paramètre | Signification |
|---|---|
| Same | Le port R et le port S ont la même priorité. Lorsqu'il y a des signaux sur les ports R et S, le contrôleur signale un avertissement de « main RS error » ou « control RS error » |
| Reset | Priorité à la réinitialisation. Lorsqu'il y a des signaux sur les ports R et S, le signal du port R est prioritaire, c'est-à-dire que le signal de réinitialisation est prioritaire |
| Set | Priorité à l'activation. Lorsqu'il y a des signaux sur les ports R et S, le signal du port S est prioritaire, c'est-à-dire que le signal d'activation est prioritaire |
| Revers | Lorsqu'il y a des signaux sur les ports R et S, le résultat de sortie logique actuel est inversé |
