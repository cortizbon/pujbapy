# PUJBApy package

Easy way to do in python what cannot be easily done in Excel. 

## Instalación

En una terminal o en Google Colab se puede escribir lo siguiente:

```bash
pip install pujbapy
```

## Importación

Se puede importar el paquete completo

```python
import pujbapy
```

También se puede importar uno o varios módulos

```python
from pujbapy import modelos
```

O, aún más fácil, se puede importar la función a utilizar de un módulo específico

```python
from pujbapy.modelos import regresion_lineal
```

## Contenido

El paquete contiene cuatro módulos:

- Intervalos
- Modelos
- Pruebas
- Visualización

En el módulo de intervalos se encuentran las siguientes funciones:

- `intervalo_medias`
- `intervalo_diferencia_medias`
- `intervalo_varianzas`

En el módulo de modelos se encuentran las siguientes funciones:

- `regresion_lineal`
- `regresion_logistica`
- `regresion_vi`

En el módulo de prueba se encuentran las siguientes funciones:

- `media_contra_valor`
- `comparar_medias`
- `comparar_varianzas`

Por último, en el módulo de visualización se pueden encontrar las siguientes funciones:

- `histograma`
- `grafico_barras`
- `grafico_dispersion`
- `grafico_caja`