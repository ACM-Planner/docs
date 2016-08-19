# Información evento

## Planificación

| Horario        | Actividad            | Lugar         | Descripción |
| ------------------------- |------------------- | ------------ |---------------------------|
| 10:00 - 10:45   | Inicio hackathon | Alvaro Campos |  Palabras incio: explicación general de la arquitecura, conformación de equipos y distribución espacial. |
| 10:45 - 11:45   | Bloque 1      |  Alvaro Campos, Sala Microsoft | Primer bloque donde los equipos desarrollaran de acuerdo a su propia organización. |
| 11:45 - 12:00 | Coffe Break      |    Alvaro Campos | Break. Se llevará comida y bebestibles dependiendo de lo que necesiten. |
| 12:00 - 13:00 | Bloque 2      |    Alvaro Campos, Sala Microsoft | Segundo bloque, se seguira desarrollando. |
| 13:00 - 14:00 | Almuerzo      |    Por Confirmar | Habrá pizza :pizza: |
| 14:00 - 15:20 | Bloque 3      |   Alvaro Campos, Sala Microsoft | Tercer bloque los equipos desarrollaran de acuerdo a lo que se lleve avanzado. |
| 15:20 - 15:40 | Coffe Break      |    Sala Microsoft | Los equipos que se encuentren en la sala Alvaro Campos, deberan cambiarse de sala.  |
| 15:40 - 17:00 | Bloque 4 | Sala Microsoft, Por Confirmar |Cuarto bloque, los equipos desarrollaran de acuerdo a lo que se lleve avanzado o pueden descansar.  |
| 17:00 - 17:15 | Coffe Break      |  Sala Microsoft | Break. |
| 17:15 - 18:30 | Bloque 5     |    Sala Microsoft, Alvaro Campos | Ultimo bloque, recopilación de lo logrado y que por lograr.|

## Teams

![alt tag](./diagrama.png)


| Team Name | Lider | Mentor |
| ---------- |---------- |---------- |
| Main-API | Adrián Soto  | Matias Junemann |
| Buscacursos (Frontend 1) | Geraldine Monsalve | Por definir |
| Planner (Frontend 2) | Jaime Castro | Oscar Estay |
| JS SDK + Buscacursos (Connector 1)| Patricio Lopez | Por definir |
| Queries| Rodrigo Gomez | Por Confirmar |
| Captura Datos (Curriculums) | Juan Reutter | Por definir |
| Deploy| Jurgen Dieter | Por definir |


## Descripción de las componentes

| Componente | Descripción |
| ------------ | -------------------------------------------------- |
| Jena + Fuseki | Almacenamiento de la información extraida del Buscacursos en formato RDF |
| Main-API (Flask) | Componente para servir a la API. Se conecta con Jena para consultar la base de datos |
| JS SDK | Funciones de Angular y router de React.js para poder ser consultado por el forntend |
| Curriculums | Almacenamientos de las mallas curriculares|
| Planner | Frontend para la planificación de una malla en particular. Se programará en React.js |
| Buscacursos | Frontend para la planificación de un horario de un semestre en particular. Se programará en React.js |

## Descripción de los Teams
| Team Name | Descripción |
| ------------ | --------------------------------------------------------------------- |
| Main API | Encargado de la componente Flask y JS SDK para la correcta forma de consultar la base de datos desde el frontend |
| Buscacursos (Frontend 1) | Se encargarán de realizar el forntend de la parte que reemplazará al Buscacursos, es decir, planificador de horario para un semestre en particular     
| Planner (Frontend 2) | Se encargarán de realizar el forntend de la parte que reemplazará al Planner, es decir, planificador de todos los ramos a tomar en la carrera por semestre |
| JS SDK + Buscacursos (Connector 1) | Se encargará de conectar la componente Buscacursos con la JS SDK |
| Captura de datos (Curriculums) | Se encargarán de ver como se almacenará las mallas y de capturar los datos necesarios |
| Deploy | Se encagarán de realizar el deploy de todas las componentes |
| Queries | Se encargarán de hacer las consultas necesarias de manera que sean lo menos costosa posibles (SPARQL) |
