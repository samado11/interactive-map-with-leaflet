---

date: "December 17, 2018"

---



```{r, leaflet, echo=FALSE}
library(leaflet)
mapNorcal = leaflet() %>%
 addTiles() %>%


 addMarkers (lat= 31, lng= 30, popup="alexanderia")
mapNorcal

```


```
