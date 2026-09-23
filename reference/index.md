# Package index

## Búsqueda y Exploración

### Funciones para encontrar códigos y descripciones

- [`cie_search()`](https://docs.ropensci.org/ciecl/reference/cie_search.md)
  : Búsqueda difusa (fuzzy) de términos médicos CIE-10
- [`cie_lookup()`](https://docs.ropensci.org/ciecl/reference/cie_lookup.md)
  : Búsqueda exacta por código CIE-10
- [`cie_describe()`](https://docs.ropensci.org/ciecl/reference/cie_describe.md)
  : Obtener descripción de códigos CIE-10 (vector)
- [`cie_short()`](https://docs.ropensci.org/ciecl/reference/cie_short.md)
  : Listar siglas médicas soportadas
- [`cie_guide()`](https://docs.ropensci.org/ciecl/reference/cie_guide.md)
  : Guía de funciones de búsqueda CIE-10

## Datos y Catálogos

### Conjuntos de datos integrados

- [`cie10_cl`](https://docs.ropensci.org/ciecl/reference/cie10_cl.md) :
  Dataset CIE-10 Chile oficial MINSAL/DEIS v2018
- [`cie_table()`](https://docs.ropensci.org/ciecl/reference/cie_table.md)
  : Generar tabla HTML interactiva GT de código CIE-10

## Base de Datos SQL

### Acceso directo al catálogo integrado

- [`cie10_sql()`](https://docs.ropensci.org/ciecl/reference/cie10_sql.md)
  : Ejecutar consultas SQL sobre CIE-10 Chile
- [`cie10_clear_cache()`](https://docs.ropensci.org/ciecl/reference/cie10_clear_cache.md)
  : Limpiar caché SQLite local (forzar rebuild)
- [`cie10_disconnect()`](https://docs.ropensci.org/ciecl/reference/cie10_disconnect.md)
  : Cerrar conexión pooled SQLite

## API CIE-11

### Conexión con servidores de la OMS

- [`cie11_search()`](https://docs.ropensci.org/ciecl/reference/cie11_search.md)
  : Buscar códigos CIE-11 vía API OMS
- [`get_icd_api_key()`](https://docs.ropensci.org/ciecl/reference/get_icd_api_key.md)
  : Obtener la API key de la OMS desde el entorno

## Análisis y Comorbilidad

- [`cie_comorbid()`](https://docs.ropensci.org/ciecl/reference/cie_comorbid.md)
  : Calcular comorbilidades Charlson/Elixhauser para Chile
- [`cie_map_comorbid()`](https://docs.ropensci.org/ciecl/reference/cie_map_comorbid.md)
  : Mapeo manual de grupos de comorbilidad específicos de Chile

## Utilidades y Validación

- [`cie_norm()`](https://docs.ropensci.org/ciecl/reference/cie_norm.md)
  [`cie_normalize()`](https://docs.ropensci.org/ciecl/reference/cie_norm.md)
  : Normalizar códigos CIE-10 a formato con punto
- [`cie_expand()`](https://docs.ropensci.org/ciecl/reference/cie_expand.md)
  : Expandir código jerárquico (ej. E11 -\> E11.0-E11.9)
- [`cie_validate_vector()`](https://docs.ropensci.org/ciecl/reference/cie_validate_vector.md)
  : Validar vector de códigos CIE-10 formato
