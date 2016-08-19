# Formato de los JSON

## JSON horario

Un arreglo con pares módulo día y tipo
```
[
{“module”: <integer>, “day”: <char>, “type”: <string>},
etc…
]
```
## JSON curso, 
que tiene la sigla, nombre, facultad, requisitos (En formato DNF, es decir, que los requisitos es que sea necesario cumplir alguno de los set) y equivalencias.
```
{
“initial”: <string>,
“name”: <string>,
“faculty”: <string>,
“requisites”: [[<sigla1>,<sigla2>,…], [<sigla3>,<sigla4>,…],...],
“equivalences”: [<sigla1>,<sigla2>,…]
}
```
## JSON sección, 
con número de seccion, NRC, profesores, horarios que se dicta, junto con el semestre y año que se dicta
```
{
“number”:<integer>,
“NRC”: <integer>, 
“teachers”: [<string1>, <string2>,...],
“schedules”:[
	{“module”: <module>},
	{“module”: <module>}
],
“semestre”: <string>,
“año”: <integer>
}
```
## JSON informacion_curso 
Esto es un json mixto que tiene la info del curso y de ahí un arreglo de secciones
```
{
“course”: <course>, 
“sections”: [<section1>,<section2>,…]
}
```
## JSON informacion_curso[] 
(arreglo de varios cursos con varias secciones):
```
[<informacion_curso1>, <informacion_curso2>,…] 
```
