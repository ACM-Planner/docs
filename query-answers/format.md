# Formato de los JSON

## JSON horario

Un arreglo con pares módulo día 
```
[
{“modulo”: <integer>, “dia”: <integer>},
etc…
]
```
## JSON curso 
También se pueden agregar la info del curso y el link al programa, si los tenis en le BD 
```
{
“sigla”: <string>,
“nombre”: <string>,
“facultad”: <string>,
“requisitos”: [[<sigla1>,<sigla2>,…], [<sigla3>,<sigla4>,…],...],
“equivalencias”: [<sigla1>,<sigla2>,…]
}
```
## JSON sección 
```
{
“numero”:<integer>,
“NRC”: <integer>, 
“profesor”: [<string1>, <string2>,...],
“horarios”:[
	{“tipo”, “<string>, “horario”: <horario>},
	{“tipo”, “<string>, “horario”: <horario>}
],
“semestre”: <string>,
“año”: <integer>
}
```
## JSON informacion_curso 
Esto es un json mixto que tiene la info del curso y de ahí un arreglo de secciones
```
{
“curso”: <curso>, 
“secciones”: [<seccion1>,<seccion2>,…]
}
```
## JSON informacion_curso[] (arreglo de varios cursos con varias secciones):
```
[<informacion_curso1>, <informacion_curso2>,…] 
```
