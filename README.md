
## Dataset: Student Performance

### Contexto

Este conjunto de datos se enfoca en el rendimiento estudiantil en la educación secundaria de dos escuelas portuguesas. Proporciona una visión detallada del desempeño académico de los estudiantes y su relación con una variedad de atributos demográficos, sociales y relacionados con la escuela. Los datos se recopilaron a través de informes escolares y cuestionarios.


### Columnas del dataset

1. **school**: La escuela a la que asisten los estudiantes ('GP' para Gabriel Pereira o 'MS' para Mousinho da Silveira).

2. **sex**: El género del estudiante ('F' para femenino o 'M' para masculino).

3. **age**: La edad del estudiante.

4. **address**: El tipo de dirección del estudiante ('U' para urbano o 'R' para rural).

5. **famsize**: El tamaño de la familia del estudiante ('LE3' para menos o igual a 3 o 'GT3' para más de 3).

6. **Pstatus**: El estado de convivencia de los padres ('T' para juntos o 'A' para separados).

7. **Medu**: La educación de la madre (en una escala de 0 a 4).

8. **Fedu**: La educación del padre (en una escala de 0 a 4).

9. **Mjob**: La ocupación de la madre.

10. **Fjob**: La ocupación del padre.

11. **reason**: La razón para elegir la escuela ('home' para cercanía a casa, 'reputation' para reputación, 'course' para preferencia de curso, 'other' para otras razones).

12. **guardian**: El tutor legal del estudiante.

13. **traveltime**: El tiempo de viaje desde casa a la escuela (en una escala de 1 a 4).

14. **studytime**: El tiempo semanal de estudio (en una escala de 1 a 4).

15. **failures**: El número de clases falladas (en una escala de 1 a 4).

16. **schoolsup**: Apoyo educativo extra de la escuela ('yes' o 'no').

17. **famsup**: Apoyo educativo extra de la familia ('yes' o 'no').

18. **paid**: Clases extra pagadas ('yes' o 'no').

19. **activities**: Participación en actividades extracurriculares ('yes' o 'no').

20. **nursery**: Asistencia a guardería infantil ('yes' o 'no').

21. **higher**: Aspiración de educación superior ('yes' o 'no').

22. **internet**: Acceso a Internet en casa ('yes' o 'no').

23. **romantic**: Relación romántica ('yes' o 'no').

24. **famrel**: Calidad de las relaciones familiares (en una escala de 1 a 5).

25. **freetime**: Tiempo libre después de la escuela (en una escala de 1 a 5).

26. **goout**: Frecuencia de salir con amigos (en una escala de 1 a 5).

27. **Dalc**: Consumo de alcohol en días laborables (en una escala de 1 a 5).

28. **Walc**: Consumo de alcohol en fines de semana (en una escala de 1 a 5).

29. **health**: Estado de salud (en una escala de 1 a 5).

30. **absences**: Cantidad de ausencias escolares.

31. **G1**: Calificación en el primer período.

32. **G2**: Calificación en el segundo período.

33. **G3**: Calificación final en el tercer período (atributo objetivo).

Estas columnas contienen información demográfica, académica y de comportamiento de los estudiantes que pueden ser utilizadas para realizar análisis y modelado predictivo relacionados con el rendimiento escolar.


## Modelado y Objetivos

Este conjunto de datos se ha utilizado para tareas de clasificación binaria/de cinco niveles y tareas de regresión. Un aspecto importante es que las calificaciones G3 tienen una fuerte correlación con las calificaciones G2 y G1. Esto se debe a que G3 es la calificación final del último año, mientras que G1 y G2 son calificaciones de los primeros dos períodos. Esta relación es esencial para predecir el rendimiento estudiantil.

## Uso del Conjunto de Datos

Este conjunto de datos es valioso para llevar a cabo análisis de datos, modelado predictivo y evaluación del rendimiento académico de los estudiantes. Puede ser utilizado en investigaciones educativas y análisis de factores que afectan el éxito académico de los estudiantes en la educación secundaria.

