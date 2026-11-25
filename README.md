# README — Evaluación

> **Curso:** ALGORITMO Y ESTRUCTURA DE DATOS BASADOS EN INTELIGENCIA ARTIFICIAL  
> **Código:** 4682  
> **Evaluación:** PA4  
> **Equipo:** Grupo 4  

## 1. Integrantes

| Integrante | Rol | Aporte principal |
|---|---|---|
| Geraldine Khatrina Tudela Theo | Desarrolladora | Desarrollo de la Actividad 1: Recursividad aplicada. Explicación de la recursividad y el principio divide y vencerás, implementación de un algoritmo recursivo en Java para recorrer las ubicaciones del campus e identificación del caso base, caso recursivo y condición de finalización. |
| Mijail Mendoza Chavez | Desarrollador del algoritmo de ordenamiento recursivo | Diseño e implementación del algoritmo Merge Sort en Java para ordenar los tiempos estimados de recorrido de las ubicaciones del campus. |
| Victor Manuel Fabricio Quispe Gonzales | Analista | Desarrollo de las Actividades 3 y 4: Modelado del campus mediante un grafo ponderado no dirigido, análisis de escenarios para DFS, BFS y A*, cuadro comparativo, conclusión técnica final y relación con aplicaciones básicas de IA. |
| [Nombre 4] | [Rol] | [Aporte] 

## 2. Descripción y objetivo

**Problema:**  
Una institución necesita desarrollar un módulo inteligente de orientación dentro del campus que permita organizar información sobre sus instalaciones, analizar rutas entre ubicaciones y recomendar recorridos convenientes.

**Objetivo:**  
Aplicar la recursividad mediante un algoritmo en Java que permita recorrer y mostrar las ubicaciones registradas dentro del campus, comprendiendo el funcionamiento del caso base y el caso recursivo.

**Solución desarrollada:**  
Se desarrolló un algoritmo recursivo en Java que utiliza un arreglo para almacenar diferentes ubicaciones del campus, como la entrada principal, biblioteca, cafetería y laboratorio.

Mediante la función mostrarUbicaciones, el programa recorre cada elemento del arreglo hasta llegar a la condición de finalización. De esta manera, se demuestra cómo aplicar la recursividad para procesar información sin utilizar un ciclo repetitivo.

**Aporte de la Actividad 2: Ordenamiento recursivo**

Se desarrolló un algoritmo de ordenamiento recursivo utilizando Merge Sort en Java, mediante el entorno de desarrollo IntelliJ IDEA.

El algoritmo permite organizar las ubicaciones del campus según sus tiempos estimados de recorrido, de menor a mayor. Para ello, aplica el principio de divide y vencerás, dividiendo los datos en dos partes hasta obtener elementos individuales y posteriormente combinarlos de forma ordenada.

Se utilizaron seis ubicaciones como ejemplo: Biblioteca, Laboratorio, Cafetería, Aula 101, Auditorio y Administración.

Como resultado, el programa logró ordenar correctamente los tiempos estimados de recorrido, demostrando la utilidad de la recursividad para procesar y organizar información dentro del sistema inteligente de orientación.
## 3. Cómo ejecutar o revisar

```bash
El repositorio contiene el desarrollo de las cuatro actividades de la PA4.
```

**Pasos de revisión:**
1. Ingresar al repositorio de GitHub y revisar los archivos correspondientes a cada actividad.
2. Abrir o descargar los documentos para visualizar las explicaciones, representaciones gráficas, algoritmos y justificaciones desarrolladas.
3. Revisar la sección de evidencias del README, donde se muestran las capturas y los aportes realizados por los integrantes del equipo.

> No publicar contraseñas, tokens, credenciales ni datos sensibles.

## 4. Evidencias

Agregar aquí capturas, resultados, pruebas o enlaces que demuestren el funcionamiento.

- Evidencia 1 Recursividad Aplicada:
  
Codigo:

<img width="696" height="582" alt="Evidencia1_codigo" src="https://github.com/user-attachments/assets/44535bdb-2859-42e8-9319-57e05b6c3e30" />

Ejecucion:

<img width="371" height="195" alt="Evidencia1_ejecucion" src="https://github.com/user-attachments/assets/e5c947b8-678b-4099-8bef-38177ba5f112" />

- Evidencia 2: ordenamiento recursivo
  <img width="1291" height="892" alt="one" src="https://github.com/user-attachments/assets/f65dc9b3-70f2-4c89-a5b2-846421be5806" />
<img width="1245" height="862" alt="two" src="https://github.com/user-attachments/assets/6b9a0805-8689-42e3-ab65-8c263e5d9c99" />
<img width="1257" height="747" alt="tree" src="https://github.com/user-attachments/assets/6b8c37ae-86c9-4df1-b2ae-0773c4136b2e" />
<img width="442" height="442" alt="four" src="https://github.com/user-attachments/assets/e4936f1c-7661-4ab4-8c2c-d64937dfc167" />

- Evidencia 3: 
- Evidencia 4: Cuadro comparativo (DFS, BFS, $A^*$), recomendación técnica y relación con aplicaciones de IA documentados en el informe del repositorio.

## 5. Matriz de participación

| Integrante | Desarrollo | Pruebas | Documentación | Exposición | Evidencia de participación |
|---|---|---|---|---|---|
| Geraldine Khatrina Tudela Theo | Alta | Media | Alta | Sí/No | Desarrollo de la Actividad 1, elaboración del algoritmo recursivo en Java, explicación del caso base y caso recursivo, documentación en PDF, evidencias, publicación en GitHub y estructuración del README.. |
| mijail mendoza chavez | Alta | Alta | media | Sí/No |Implementación de Merge Sort en Java, pruebas en IntelliJ IDEA y documentación de la Actividad 2: Ordenamiento recursivo  |
| Victor Manuel Fabricio Quispe Gonzales | Alta | Media | Alta | Si | Desarrollo de las Actividades 3 y 4, diagrama del grafo del campus, análisis comparativo (DFS, BFS, $A^*$) y relación con IA |
| [Nombre 4] | [Alta/Media/Baja] | [Alta/Media/Baja] | [Alta/Media/Baja] | [Sí/No] | [Commits, avances, etc.] |
| [Nombre 5] | [Alta/Media/Baja] | [Alta/Media/Baja] | [Alta/Media/Baja] | [Sí/No] | [Commits, avances, etc.] |

## 6. Video de exposición

**Video público de YouTube:** 
- [https://www.youtube.com/watch?v=nUfSCRFoHYI]

Todos los integrantes deben participar en la exposición con sus cámaras prendidas y explicar el procedimiento, la solución desarrollada y las decisiones tomadas.

## 7. Conclusiones

- La recursividad permite resolver problemas mediante funciones que se llaman a sí mismas hasta llegar a una condición de finalización. En nuestra actividad aplicamos este concepto para recorrer las ubicaciones registradas dentro del campus mediante un algoritmo en Java.
Este procedimiento nos ayudó a comprender el funcionamiento del caso base y del caso recursivo, además de demostrar cómo se puede utilizar la recursividad para procesar información de manera organizada dentro de un sistema de orientación.
- Ordenamiento recursivo:Se logró implementar correctamente el algoritmo Merge Sort en Java, aplicando el principio de divide y vencerás para ordenar los tiempos estimados de recorrido de las ubicaciones del campus. Mediante la recursividad, se dividieron los datos en grupos pequeños para posteriormente combinarlos en orden ascendente, obteniendo resultados correctos durante la ejecución en IntelliJ IDEA. Finalmente, se demuestra que Merge Sort es una alternativa eficiente para organizar la información del sistema inteligente de orientación, con una complejidad temporal de O(n log n).
---

**Última actualización:** [24/11/2026]
