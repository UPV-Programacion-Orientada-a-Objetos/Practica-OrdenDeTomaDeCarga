# Práctica 2.
## Orden de Carga

Se deberá generar una librería en java capaz de analizar un conjunto de directorios (uno o muchos) que contendrán un conjunto de archivos, los cuales contienen la lista de calificaciones de alumnos. La librería deberá ser capaz de generar la lista del orden de toma de carga de los alumnos. Se deberán tomar en cuenta las siguientes restricciones:

  1.- Cada carpeta o directorio contiene las calificaciones de un grupo, el cual puede contener 1 o más archivos correspondientes a una materia de ese grupo.
  2.- Cada archivo contiene la lista de calificaciones por unidad de una materia determinada. La cantidad de unidades puede ser 2 y hasta 5 unidades.
  3.- Se debe tomar en cuenta que un alumno puede aparecer en distintos grupos (directorios), pero no es necesario que aparezca en todas las materias del grupo (archivos de un mismo directorio).
  4.- Las calificaciones por unidad se guardan en enteros positivos mayores iguales a 60. Donde una calificación de unidad menor a 70 es una calificación reprobatoria, dando como resultado al alumno reprobado en toda la materia.
  5.- Cada materia (archivo) esta identificado con el código de materia, mas no por su nombre.
  6.- Los archivos no contienen cabeceras.

Para la prioridad de la toma de carga se deberán tomar en cuenta las siguientes restricciones.

1.- Los alumnos de ordenan de forma decreciente al promedio general del alumno.
2.- Los alumnos con una materia reprobada van después de todos los alumnos con cero materias reprobadas, alumnos con dos reprobadas van después de todos los alumnos con una materia reprobada, y así sucesivamente. 
3.- Cuando dos alumnos tengan el mismo promedio, con el mismo número de materias reprobadas se desempatará por el número de materias cursadas.
4.- Para el promedio general sólo se toma en cuenta 2 decimales.

## ENTREGABLES
Se deberá entregar lo siguiente:

  1.- Proyecto en maven.
  2.- Código fuente en el repositorio correspondiente a esta actividad.
  3.- Se deberá entregar un reporte en PDF con lo siguiente:
    a) Diagrama de clases y diccionario de clases.
    b) Pruebas de escritorio.


## SUGERENCIAS

Se siguiere estudiar los siguientes temas:
  
  1.- Generación de JAR mediante maven.
  2.- Algoritmos de ordenamiento
