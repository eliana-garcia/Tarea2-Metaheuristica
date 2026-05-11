TAREA 2 - METAHEURÍSTICAS

Profesora: Leslie Pérez Cáceres

---

INTEGRANTES:

* Eliana García - 21.758.946-0
* Benjamin Leiva - RUT
* Kevin Alvarez - RUT

---

DESCRIPCIÓN:

Este proyecto implementa la metaheurística **Simulated Annealing (Recocido Simulado)** para resolver el problema **Job Shop Scheduling (JSP)**.

El objetivo es minimizar el **makespan**, es decir, el tiempo total de finalización de todos los trabajos.

---

REQUISITOS:

* Python 3.x instalado
* No se requieren librerías externas (solo librerías estándar)

---

INSTRUCCIONES DE EJECUCIÓN:

1. Descargar o clonar el repositorio
2. Abrir una terminal en la carpeta del proyecto
3. Ejecutar el siguiente comando:

   python main.py

---

ESTRUCTURA DEL PROYECTO:

* main.py
  Archivo principal que ejecuta el programa y procesa las instancias.

* simulated_annealing.py
  Contiene la implementación de la metaheurística.

* utils.py
  Funciones auxiliares:

  * lectura de instancias
  * cálculo del makespan
  * validación de soluciones

* instancias/
  Carpeta que contiene los archivos de entrada:

  * 01_facilNuevo.txt
  * 02_mediaNuevo.txt
  * 03_media_dificilNuevo.txt

---

SALIDA DEL PROGRAMA:

El programa:

* Ejecuta 10 veces el algoritmo por cada instancia
* Muestra el makespan de cada ejecución
* Calcula:

  * Media
  * Desviación estándar

---

TRABAJO COLABORATIVO (CAMBIOS EN EL CÓDIGO):

Para trabajar en equipo utilizando GitHub:

   git pull
   git add .
   git commit -m "descripción del cambio"
   git push

NOTA:

* Siempre ejecutar "git pull" antes de trabajar para evitar conflictos
* Escribir mensajes de commit claros

---

NOTAS:

* La solución obtenida es aproximada (metaheurística)
* El rendimiento depende de los parámetros del algoritmo
* El código está organizado de forma modular para facilitar su comprensión

---
