# Clase 1 – Introducción a NoSQL y sus motivaciones

### Objetivo de la clase

Comprender **por qué las bases de datos relacionales no siempre son suficientes** y qué problemas intenta resolver el paradigma NoSQL.

Al finalizar la clase, el estudiante debería poder explicar en qué contexto surge NoSQL y qué tipo de necesidades tecnológicas impulsaron su adopción.

### Repaso de bases de datos relacionales

Las bases de datos relacionales (MySQL, PostgreSQL, Oracle, SQL Server) se organizan en tablas compuestas por filas y columnas, utilizan claves primarias y foráneas para mantener relaciones entre entidades y emplean el lenguaje SQL como estándar para consultas y manipulación de datos.

Este enfoque ha permitido:

* Construir sistemas confiables, consistentes y bien organizados,
* Especialmente en entornos empresariales tradicionales como banca, sistemas académicos, gestión administrativa y comercio.

Sin embargo fueron concebidas en una época donde los volúmenes de datos eran mucho menores y las aplicaciones no requerían operar a escala global en tiempo real.

Por ello, no fueron diseñadas originalmente para afrontar escenarios como:

- Escalas masivas globales.
- Millones de escrituras por segundo.
- Datos semiestructurados o cambiantes.
- Infraestructura distribuida.
  
  *(Diagrama CAP en Mermaid → PNG)*

