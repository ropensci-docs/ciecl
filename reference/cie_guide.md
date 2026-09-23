# Guía de funciones de búsqueda CIE-10

Muestra tabla comparativa de cuándo usar cada función de búsqueda.

## Usage

``` r
cie_guide()
```

## Value

tibble con guia comparativa de funciones de busqueda

## See also

[`cie_search()`](https://docs.ropensci.org/ciecl/reference/cie_search.md),
[`cie_lookup()`](https://docs.ropensci.org/ciecl/reference/cie_lookup.md),
[`cie_short()`](https://docs.ropensci.org/ciecl/reference/cie_short.md)

Other search:
[`cie_describe()`](https://docs.ropensci.org/ciecl/reference/cie_describe.md),
[`cie_guia_busqueda()`](https://docs.ropensci.org/ciecl/reference/cie_guia_busqueda.md),
[`cie_lookup()`](https://docs.ropensci.org/ciecl/reference/cie_lookup.md),
[`cie_search()`](https://docs.ropensci.org/ciecl/reference/cie_search.md)

## Examples

``` r
cie_guide()
#> # A tibble: 8 × 3
#>   Tengo...                     `Usar funcion`                           Ejemplo 
#>   <chr>                        <chr>                                    <chr>   
#> 1 Codigo exacto (E11.0)        cie_lookup()                             "cie_lo…
#> 2 Codigo sin punto (e110)      cie_lookup()                             "cie_lo…
#> 3 Codigo con espacios (E 11.0) cie_lookup()                             "cie_lo…
#> 4 Codigo con prefijos/sufijos  cie_lookup(extract = TRUE)               "cie_lo…
#> 5 Codigo categoria (E11)       cie_lookup() o cie_lookup(expand = TRUE) "cie_lo…
#> 6 Descripcion (diabetes)       cie_search()                             "cie_se…
#> 7 Sigla medica (IAM, DM2)      cie_lookup(check_siglas = TRUE)          "cie_lo…
#> 8 No se que tengo              cie_search() con threshold bajo          "cie_se…
```
