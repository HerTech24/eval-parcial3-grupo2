# Evaluacion Parcial 3 - Grupo 2

## Nota sobre el Dataset

El archivo `mymoviedb.csv` contiene informacion de peliculas obtenida de TMDB a traves de Kaggle. Presenta algunas filas malformadas debido al campo `Overview` (sinopsis), el cual contiene comillas y saltos de linea que interfieren con el parseo estandar de pandas. Por esta razon, el archivo se carga utilizando los parametros `engine='python'` y `on_bad_lines='skip'`, los cuales permiten tolerar estas filas problematicas y continuar con el analisis sin perder una cantidad significativa de datos.

---

## Presentacion

Cada integrante del grupo expondra su parte en una presentacion grupal de maximo 15 minutos. La estructura de la exposicion sera la siguiente:

1. **Hernan Lippke** (3-4 minutos): presentacion del problema abordado, configuracion del repositorio GitHub, carga del dataset y explicacion del grafico de barras sobre los generos mas frecuentes.

2. **Matias Arauz** (3 minutos): descripcion del proceso de limpieza y preparacion de los datos, incluyendo los problemas identificados en el CSV y las soluciones implementadas.

3. **Sebastian Gonzalez Pino** (3 minutos): analisis del grafico de lineas que muestra la evolucion de los estrenos cinematograficos a lo largo del tiempo.

4. **Michelangelo Bandelli** (3-4 minutos): explicacion del grafico de dispersion que relaciona calificacion y popularidad, junto con la presentacion del mini dashboard que integra los tres graficos y los KPIs principales.

5. **Todos los integrantes** (1-2 minutos): cierre de la presentacion, muestra de la evidencia de uso de Git/GitHub (historial de commits y flujo de trabajo colaborativo) y conclusiones finales.

Durante la presentacion se abordaran los siguientes puntos:
- El problema analizado y su relevancia.
- El flujo de trabajo colaborativo con Git y GitHub.
- Las visualizaciones generadas y su interpretacion.
- Los hallazgos y conclusiones obtenidas del analisis.

---

## Licencia

Este proyecto es de uso academico y educativo, desarrollado en el marco de la asignatura Programacion para la Ciencia de Datos de la Escuela de Ingenieria Informatica del DUOC UC. Su contenido puede ser utilizado con fines de estudio y aprendizaje, siempre que se mencione la fuente y a los autores originales.

---

## Contacto

Para cualquier consulta, sugerencia o comentario sobre este proyecto, los interesados pueden comunicarse con:

- **Profesor:** Pablo Espinoza (docente de la asignatura)
- **Integrantes del grupo:**
  - Matias Arauz
  - Sebastian Gonzalez Pino
  - Michelangelo Bandelli
  - Hernan Lippke

Alternativamente, se puede abrir un issue en el repositorio de GitHub o contactar a traves de los canales oficiales de la institucion.