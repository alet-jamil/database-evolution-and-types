# Historia, Evolución y Paradigmas de Almacenamiento en Bases de Datos

## 1. Título y Resumen
Reporte comparativo y mapa de evolución técnica de las bases de datos desde el modelo relacional tradicional (1970) hasta el surgimiento de bases de datos vectoriales para IA (2023+).

## 2. Contexto y Pregunta de Investigación
- **Pregunta:** ¿Cómo ha evolucionado la arquitectura de almacenamiento de datos para responder a las demandas de datos Estructurados, Semi-estructurados y No Estructurados?
- **Objetivo:** Comprender las bases conceptuales que fundamentan la elección entre motores SQL, NoSQL, NewSQL y Vectoriales en la Ingeniería en Ciencia de Datos.

## 3. Clasificación Tecnológica Analizada
- **Estructurados:** Tablas SQL, esquemas rígidos (Modelo Relacional de Codd - 1970).
- **Semi-Estructurados:** Formatos auto-descriptivos flexibles como JSON (2001), BSON (MongoDB - 2009) y sistemas columnares (BigTable - 2004).
- **No Estructurados & IA:** Ecosistemas Big Data (Hadoop/HDFS - 2006) y Bases de Datos Vectoriales para Embeddings (Pinecone, Milvus - 2023+).

## 4. Metodología
Síntesis sistemática de literatura técnica y categorización cronológica basada en características de rendimiento, esquemas y tipos de datos dominantes.

## 5. Resultados Principales (Línea del Tiempo Resumida)
| Año | Hito Tecnológico | Tipo de Dato | Característica Clave |
|---|---|---|---|
| 1970 | Modelo Relacional (SQL) | Estructurado | Normalización y Esquemas estrictos (Codd) |
| 2001 | Estándar JSON | Semi-Estructurado | Intercambio ligero en web |
| 2006 | Amazon Dynamo / Hadoop | No Estructurado | Ecosistema Big Data / HDFS |
| 2012 | NewSQL | Híbrido | Consistencia ACID + Escalabilidad Horizontal |
| 2023+ | Bases de Datos Vectoriales | No Estructurado / IA | Similitud de Embeddings para Modelos LLM/IA |

## 6. Conclusiones
La elección de la base de datos óptima no depende de la novedad del motor, sino del tipo de estructura del dato y los requerimientos de consistencia (ACID) vs. escalabilidad horizontal (BASE).

## 7. Contenido del Repositorio
- `/reports/Infografia_Evolucion_BD.pdf`: Documento visual completo.
- `README.md`: Resumen ejecutivo y tabla cronológica.

## 8. Tecnologías y Conceptos
- SQL, JSON, XML, NoSQL, NewSQL, BSON, Vector Databases, Embeddings.
