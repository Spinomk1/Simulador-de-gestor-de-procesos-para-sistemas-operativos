# Simulador-de-gestor-de-procesos-para-sistemas-operativos
Proyecto integrador para la materia de Sistemas Operativos

## Descripcion
Simulador GUI de algoritmos de planificación de procesos con implementación del 
problema Productor-Consumidor usando memoria compartida y mutex.


##  Información del Curso
**Materia:** Sistemas Operativos
**Institución:** Universidad Autónoma de Tamaulipas
**Semestre:** sexto semestre del año 2025, Agosto - Diciembre 2025
**Profesor:** Muñoz Quintero Dante Adolfo 

## Integrantes
Espinosa Vázquez Cristopher 
Barahona Romero Billy Antonio 
Ponce Medina Jesus
Polanco Tijerina Jose Luis 
Gonzalez Gonzalez Oswaldo


### Funcionalidades Principales:
1. **Planificación de Procesos** 
   - SJF (Shortest Job First): Proceso más corto primero
   - Prioridad: Basado en prioridad del proceso

2. **Asignación de Recursos**
   - Gestión de CPU (1 núcleo)
   - Gestión de Memoria (4096 MB)
   - Detección de conflictos
   - Liberación automática

3. **Comunicación y Sincronización**
   - Memoria Compartida (buffer de 5 items)
   - Mutex (exclusión mutua)
   - Problema Productor-Consumidor
   - Sincronización automática

4. **Operaciones sobre Procesos**
   - Creación manual de procesos
   - Terminación normal (automática)
   - Terminación forzada (manual)
   - Bloqueo/desbloqueo de procesos

5. **Interfaz Gráfica**
   - Visualización en tiempo real
   - Cola de procesos con colores por estado
   - Panel de estadísticas
   - Log de eventos
   - Control de velocidad de simulación

## Tecnologías Utilizadas
- **Lenguaje:** Python 3.8+
- **GUI:** Tkinter
- **Conceptos de SO:** Threading, Sincronización, Mutex, Memoria Compartida