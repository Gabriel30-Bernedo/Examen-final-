Examen Final
================
Christian Gabriel Bernedo
31/1/2022

## 11

``` r
# tc = tiempo de concentración
# L = longitud de cauce principal
# J = Pendiente media de la cuenca
L=1200
J=(190+80)/2
tc= function(L,J) {
  (0.3*(L/(J)^1/4)^0.76)
}
tc(1,1)
```

    ## [1] 0.1046058
