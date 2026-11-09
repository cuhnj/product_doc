<!-- publish-data-sidecar: section=41 heading='4.6.6 RS Priority' role=generic source_md=doc.md -->

| Parameter | Meaning |
|---|---|
| Same | The R port and the S port have the same priority. When there are signals on the R and S ports, the controller reports a warning of "main RS error" or "control RS error" |
| Reset | Reset priority. When there are signals on the R and S ports, the R port signal takes priority, that is, the reset signal takes priority |
| Set | Set priority. When there are signals on the R and S ports, the S port signal takes priority, that is, the set signal takes priority |
| Revers | When there are signals at the R and S ports, the current logic output result is inverted |
