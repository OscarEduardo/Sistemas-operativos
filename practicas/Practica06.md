# Objetivo
Investigar y practicar hilos

# Herramientas
gcc
git

# Conceptos
- Hilos
  - Proceso ligero
  - Solo tiene un stack y el codigo y el heap lo comparte con el proceso principal
  - Si el proceso principal muere, los hilos igual moriran.
 
- Lock
  - Mecanismo de sincronización 
  - Variable global que soporta dos operaciones
  - Ayuda para resolver el problema de la sección crítica.
  
- Semáforo
  - Mecanismo de sincronización
  - Variable global que tiene un valor inicial mayor o igual a 0. Soporta dos operaciones. 
  - Para asignar recursos.
  
- Problemas de sincronización
  - Condición de carrera. Ocurre cuando el resultado depende del orden en que se ejecutan los hilos.
  - Deadlock. Ocurre cuando dos o más hilos están esperando un recurso que no se libera nunca.
  - Productor/Consumidor. Ocurre cuando los datos se pueden sobreescribir.
 
 # URL de commit
https://github.com/OscarEduardo/Sistemas-operativos/commit/30c90759e4d043746a219831f4dfc655f1db84d8
