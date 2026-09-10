# PARCIAL — ANÁLISIS Y PROCESAMIENTO DE DATOS CON PANDAS

## Contexto

Una empresa de logística almacena información sobre las entregas realizadas durante el año en `entregas.csv`.

El equipo de desarrollo dejó una primera versión del sistema. Antes de ponerlo en producción se detectó que **algunos resultados no son confiables y existe una funcionalidad pendiente**.

Usted ha sido asignado para revisar y finalizar el proyecto.

## Situación

En el repositorio encontrará:

```text
main.ipynb
datos/entregas.csv
```

El Notebook contiene una primera versión del sistema.

### Su trabajo consiste en:

**Analizar el código existente, identificar y corregir los problemas que encuentre y completar el nuevo requerimiento solicitado por la empresa.**

No se indica directamente dónde se encuentran todos los problemas ni qué instrucciones debe utilizar para solucionarlos.

## Resultado esperado

El sistema final debe permitir:

- Preparar correctamente los datos para su análisis.
- Calcular correctamente el costo total de cada entrega.
- Obtener el costo total de las operaciones.
- Identificar la ciudad con mayor costo de entregas.
- Incorporar el nuevo análisis solicitado: **costo promedio de una entrega por tipo de servicio**.

Los resultados deben calcularse mediante Python y Pandas a partir de `entregas.csv`.

> **Importante:** Una línea de código puede ejecutarse sin producir un error y aun así estar haciendo algo incorrecto. Verifique la lógica y los resultados obtenidos.

## Resultados de control

Utilice los siguientes resultados para comprobar que su solución funciona correctamente:

| Resultado | Valor esperado |
|---|---:|
| Registros iniciales | **712** |
| Registros después de la limpieza | **648** |
| Costo total de operaciones | **$44.654.284** |
| Ciudad con mayor costo | **Bogotá** |

### Costo promedio por servicio

| Servicio | Costo promedio esperado |
|---|---:|
| Express | **$88.366,17** |
| Mismo Día | **$76.565,65** |
| Estándar | **$60.616,34** |
| Programada | **$52.151,28** |


> Estos valores son proporcionados únicamente como mecanismo de comprobación. Los resultados deben ser obtenidos mediante Python y Pandas, no ingresados manualmente.


> ⚠️ **ADVERTENCIA — USO DE INTELIGENCIA ARTIFICIAL**
>
> Durante el parcial está **prohibido el uso de herramientas de Inteligencia Artificial generativa o sistemas de autocompletado de código**, incluyendo, entre otros, **ChatGPT, GitHub Copilot, Gemini, Claude o herramientas similares**.
>
> Si se identifica el uso de alguna de estas herramientas durante el examen, el trabajo será considerado **copia/fraude académico y el parcial será anulado**.