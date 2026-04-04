PENSUM DE ESTUDIO EN SISTEMAS NO TRIPULADOS
(UAV, UGV, UUV/ROV/AUV)

==================================================
MÓDULO 1. BASE CIENTÍFICA Y MATEMÁTICA
======================================

1.1 Matemáticas aplicadas
Subtemas:

* Álgebra lineal
* Vectores y matrices
* Cambios de base
* Rotaciones 2D y 3D
* Matrices de rotación
* Cuaterniones
* Ecuaciones diferenciales ordinarias
* Probabilidad y estadística
* Optimización básica

Objetivo:

* Recuperar la base matemática necesaria para modelado, control, navegación y estimación.

Proyecto sugerido:

* Implementar en Python rotaciones 3D, conversiones Euler/cuaterniones y simulaciones simples de sistemas dinámicos.

1.2 Física e ingeniería del movimiento
Subtemas:

* Mecánica clásica
* Cinemática
* Dinámica
* Fuerzas y momentos
* Torque
* Energía y potencia
* Inercia
* Fricción
* Vibraciones

Objetivo:

* Entender cómo se mueve un sistema físico y cómo responden estructuras y actuadores ante fuerzas reales.

Proyecto sugerido:

* Modelar el movimiento básico de un vehículo móvil y analizar fuerzas, aceleración y consumo energético.

1.3 Señales y sistemas
Subtemas:

* Sistemas de primer orden
* Sistemas de segundo orden
* Transformada de Laplace
* Fourier básico
* Muestreo
* Discretización
* Filtros
* Respuesta temporal

Objetivo:

* Entender cómo responden los sistemas y preparar el terreno para control, filtrado y procesamiento de sensores.

Proyecto sugerido:

* Simular en Python respuestas al escalón, impulso y filtros básicos aplicados a señales ruidosas.

==================================================
MÓDULO 2. PROGRAMACIÓN, ELECTRÓNICA Y EMBEBIDOS
===============================================

2.1 Programación técnica
Subtemas:

* Python
* Numpy
* Scipy
* Matplotlib
* Análisis de datos
* Simulación básica
* Organización de código

Objetivo:

* Usar Python como herramienta de análisis, simulación y prueba rápida de algoritmos.

Proyecto sugerido:

* Crear scripts para analizar logs de sensores, filtrar ruido y visualizar trayectorias.

2.2 Programación de alto desempeño
Subtemas:

* C
* C++
* Modularidad
* Funciones y clases
* Memoria
* Estructuras de datos
* CMake
* Buenas prácticas

Objetivo:

* Programar firmware y software técnico con más eficiencia y control.

Proyecto sugerido:

* Desarrollar una librería simple en C++ para manejar sensores y actuadores de un robot.

2.3 Linux y herramientas
Subtemas:

* Terminal
* Bash básico
* SSH
* Procesos
* Logs
* Redes básicas
* Docker básico
* Git y GitHub

Objetivo:

* Tener soltura en el entorno de trabajo típico de robótica moderna.

Proyecto sugerido:

* Preparar un entorno Linux de desarrollo con repositorios, scripts y flujo de trabajo versionado.

2.4 Microcontroladores y sistemas embebidos
Subtemas:

* STM32
* ESP32
* PWM
* ADC
* UART
* I2C
* SPI
* CAN
* Timers
* Interrupciones
* Watchdog

Objetivo:

* Poder leer sensores, controlar actuadores y desarrollar sistemas en tiempo real básico.

Proyecto sugerido:

* Leer IMU, encoder y sensor analógico desde un microcontrolador y transmitir telemetría.

2.5 Electrónica aplicada
Subtemas:

* Acondicionamiento de señales
* Ruido
* Protección eléctrica
* Alimentación
* Regulación
* Conversión DC-DC
* Integración de sensores
* Diagramas básicos de potencia

Objetivo:

* Comprender la capa física y diseñar conexiones robustas para hardware real.

Proyecto sugerido:

* Diseñar la alimentación y conexión de sensores, microcontrolador y actuadores de un prototipo.

==================================================
MÓDULO 3. ROBÓTICA COMÚN
========================

3.1 Transformaciones y marcos de referencia
Subtemas:

* Marcos inerciales
* Marcos corporales
* Transformaciones homogéneas
* Rotaciones
* Euler
* Cuaterniones

Objetivo:

* Entender cómo representar posición y orientación en robótica.

Proyecto sugerido:

* Implementar un visualizador de marcos de referencia y transformaciones en Python.

3.2 Modelado de sistemas dinámicos
Subtemas:

* Sistemas lineales
* Sistemas no lineales
* Linealización
* Espacio de estados
* Variables de estado

Objetivo:

* Aprender a representar matemáticamente vehículos y robots.

Proyecto sugerido:

* Modelar un sistema de velocidad o actitud y comparar modelo lineal y no lineal.

3.3 Control
Subtemas:

* PID
* Control en cascada
* Espacio de estados
* LQR
* Control digital
* Saturación
* Anti-windup
* Retardos

Objetivo:

* Diseñar controladores que estabilicen y guíen sistemas físicos reales.

Proyecto sugerido:

* Controlar velocidad y orientación de un robot o planta simulada con PID y luego comparar con LQR básico.

3.4 Estimación y fusión sensorial
Subtemas:

* Filtro complementario
* Kalman
* EKF
* Estimación de actitud
* Estimación de velocidad
* Estimación de posición
* Fusión IMU + sensores externos

Objetivo:

* Estimar estados internos del sistema a partir de sensores ruidosos.

Proyecto sugerido:

* Fusionar acelerómetro y giroscopio para estimar ángulo y luego extender a IMU + GPS en simulación.

3.5 Navegación y planeación
Subtemas:

* Waypoints
* Seguimiento de trayectoria
* A*
* RRT
* Planeación local
* Planeación global
* Evasión de obstáculos

Objetivo:

* Hacer que un vehículo no tripulado llegue a un objetivo evitando obstáculos.

Proyecto sugerido:

* Simular un rover o dron siguiendo waypoints con una ruta planeada.

3.6 Percepción
Subtemas:

* Cámaras
* LiDAR
* Sonar
* Visión básica
* Detección
* Tracking
* Percepción 3D introductoria

Objetivo:

* Incorporar percepción del entorno para navegación y autonomía.

Proyecto sugerido:

* Detectar objetos o paredes con cámara o LiDAR y representar el entorno.

3.7 Arquitectura de sistemas robóticos
Subtemas:

* Modularidad
* Buses de comunicación
* Telemetría
* Diagnóstico
* Seguridad
* Tolerancia a fallos

Objetivo:

* Aprender a integrar sistemas completos y mantenibles.

Proyecto sugerido:

* Diseñar la arquitectura de software y hardware de un UGV o UAV simple.

==================================================
MÓDULO 4. NÚCLEO COMÚN DE VEHÍCULOS NO TRIPULADOS
=================================================

4.1 Arquitectura de vehículos no tripulados
Subtemas:

* Computador principal
* Controlador de bajo nivel
* Sensores de navegación
* Comunicaciones
* Payload
* Energía

Objetivo:

* Comprender la estructura general de cualquier sistema no tripulado.

Proyecto sugerido:

* Dibujar y documentar la arquitectura funcional de un UGV, UAV o ROV.

4.2 Comunicaciones
Subtemas:

* UART
* CAN
* MAVLink
* Telemetría
* Radioenlace
* Latencia
* Pérdida de paquetes

Objetivo:

* Entender cómo se conectan internamente los módulos y cómo se comunica el vehículo con una estación externa.

Proyecto sugerido:

* Implementar telemetría básica entre microcontrolador y PC o entre controladora y estación.

4.3 Simulación
Subtemas:

* Gazebo
* Ignition
* Simulación de sensores
* SIL
* HITL

Objetivo:

* Validar algoritmos y arquitectura antes de pasar a hardware.

Proyecto sugerido:

* Simular un vehículo móvil o dron con sensores y control.

4.4 ROS 2
Subtemas:

* Nodos
* Topics
* Services
* Actions
* TF
* Integración multi-sensor
* Launch files

Objetivo:

* Dominar el ecosistema de integración robótica moderno.

Proyecto sugerido:

* Montar un sistema en ROS 2 con sensores simulados, odometría y control.

4.5 Seguridad y confiabilidad
Subtemas:

* Failsafe
* Watchdog
* Redundancia
* Gestión de fallos
* Recuperación

Objetivo:

* Diseñar sistemas más robustos y seguros.

Proyecto sugerido:

* Definir estados de fallo y recuperación para una misión simple.

==================================================
MÓDULO 5. ESPECIALIZACIÓN AÉREA
===============================

5.1 Aerodinámica básica
Subtemas:

* Lift
* Drag
* Thrust
* Estabilidad
* Perfiles
* Hélices

Objetivo:

* Entender cómo se sostienen y desplazan los vehículos aéreos.

Proyecto sugerido:

* Comparar configuraciones de hélices y estimar empuje y eficiencia.

5.2 Dinámica de vuelo
Subtemas:

* 6DOF
* Actitud
* Traslación
* Momentos
* Estabilidad

Objetivo:

* Modelar y comprender el comportamiento dinámico de un UAV.

Proyecto sugerido:

* Simular un cuadricóptero con variables de actitud y altura.

5.3 Multirrotores
Subtemas:

* Quad
* Hexa
* Octo
* Mezcla de motores
* Control de actitud
* Hover
* Maniobra

Objetivo:

* Comprender la configuración y control de multirrotores.

Proyecto sugerido:

* Crear un modelo y control básico de un cuadricóptero en simulación.

5.4 Ala fija y VTOL
Subtemas:

* Superficies de control
* Estabilidad longitudinal
* Estabilidad lateral
* Transición VTOL

Objetivo:

* Entender otras plataformas aéreas más allá del multirrotor.

Proyecto sugerido:

* Analizar conceptualmente la arquitectura de un VTOL y sus modos de operación.

5.5 Autopilotos aéreos
Subtemas:

* PX4
* ArduPilot
* Modos de vuelo
* Tuning
* Logs

Objetivo:

* Aprender a usar y entender autopilotos reales.

Proyecto sugerido:

* Configurar un dron en simulación con PX4 o ArduPilot y ejecutar una misión por waypoints.

5.6 Navegación aérea
Subtemas:

* GNSS
* Barómetro
* Magnetómetro
* Optical flow
* RTL
* Geofence

Objetivo:

* Implementar navegación aérea básica y mecanismos de seguridad.

Proyecto sugerido:

* Simular misión aérea con retorno a casa y límites geográficos.

==================================================
MÓDULO 6. ESPECIALIZACIÓN TERRESTRE
===================================

6.1 Locomoción terrestre
Subtemas:

* Diferencial
* Ackermann
* Skid-steer
* Omnidireccional
* Orugas

Objetivo:

* Conocer las configuraciones principales de movilidad terrestre.

Proyecto sugerido:

* Comparar modelos cinemáticos de distintos tipos de locomoción.

6.2 Dinámica vehicular terrestre
Subtemas:

* Tracción
* Deslizamiento
* Suspensión
* Estabilidad
* Interacción rueda-terreno

Objetivo:

* Entender las limitaciones reales de la movilidad terrestre.

Proyecto sugerido:

* Modelar deslizamiento y efecto de terreno en un rover simple.

6.3 Navegación terrestre
Subtemas:

* Odometría
* Encoder + IMU
* GPS
* LiDAR
* Visual odometry

Objetivo:

* Lograr estimación de posición y orientación en entornos terrestres.

Proyecto sugerido:

* Construir o simular un rover con odometría y navegación básica.

6.4 Planeación para UGV
Subtemas:

* Costmaps
* Seguimiento de trayectorias
* Evitación de obstáculos
* Planeación en terreno irregular

Objetivo:

* Permitir que un UGV navegue de forma útil y segura.

Proyecto sugerido:

* Simular un rover autónomo con costmaps y evitación de obstáculos.

6.5 Robustez mecánica
Subtemas:

* Chasis
* Vibración
* Impacto
* Sellado
* Autonomía energética

Objetivo:

* Diseñar plataformas terrestres más resistentes y utilizables en campo.

Proyecto sugerido:

* Diseñar en CAD una base rover con criterios de robustez.

==================================================
MÓDULO 7. ESPECIALIZACIÓN ACUÁTICA
==================================

7.1 Hidrostática e hidrodinámica
Subtemas:

* Flotabilidad
* Estabilidad
* Arrastre
* Empuje
* Maniobrabilidad

Objetivo:

* Comprender las fuerzas que dominan el entorno acuático.

Proyecto sugerido:

* Calcular empuje, flotabilidad y estabilidad de una plataforma subacuática básica.

7.2 Vehículos acuáticos
Subtemas:

* ROV
* AUV
* USV
* Thrusters
* Configuración de propulsión

Objetivo:

* Conocer las principales arquitecturas de sistemas no tripulados acuáticos.

Proyecto sugerido:

* Definir la arquitectura de un ROV básico teleoperado.

7.3 Sensores subacuáticos
Subtemas:

* Sensor de profundidad
* IMU
* Brújula
* Sonar
* Cámara subacuática
* DVL introductorio

Objetivo:

* Entender qué sensores sí son útiles bajo el agua y sus limitaciones.

Proyecto sugerido:

* Diseñar un stack sensorial para un ROV o AUV básico.

7.4 Control acuático
Subtemas:

* Control de profundidad
* Heading hold
* Control de actitud
* Control de posición relativa

Objetivo:

* Controlar el vehículo en un entorno donde la navegación es más limitada y difícil.

Proyecto sugerido:

* Simular control de profundidad y rumbo.

7.5 Navegación acuática
Subtemas:

* GNSS en superficie
* Navegación relativa bajo agua
* Dead reckoning
* Sonar-based navigation

Objetivo:

* Aprender las estrategias de navegación más realistas en medio acuático.

Proyecto sugerido:

* Diseñar una estrategia de navegación para un ROV/AUV con restricciones reales.

7.6 Diseño subacuático
Subtemas:

* Sellado
* Presión
* Corrosión
* Conectores
* Gestión térmica

Objetivo:

* Entender los retos de hardware en entornos acuáticos.

Proyecto sugerido:

* Diseñar conceptualmente un compartimiento estanco para electrónica.

==================================================
MÓDULO 8. AUTONOMÍA AVANZADA
============================

8.1 SLAM y localización avanzada
Subtemas:

* Visual SLAM
* LiDAR SLAM
* Sonar SLAM introductorio
* Fusión multi-sensor

Objetivo:

* Estimar la posición y construir mapas del entorno en escenarios más complejos.

Proyecto sugerido:

* Simular SLAM con LiDAR o cámara.

8.2 Planeación avanzada
Subtemas:

* Planeación dinámica
* Replanificación
* Navegación en entornos inciertos
* Evasión avanzada

Objetivo:

* Adaptar el comportamiento del vehículo ante cambios del entorno.

Proyecto sugerido:

* Implementar replanificación en un escenario con obstáculos móviles.

8.3 Visión e IA aplicada
Subtemas:

* Detección de objetos
* Segmentación
* Tracking
* Edge AI

Objetivo:

* Agregar percepción más inteligente a sistemas no tripulados.

Proyecto sugerido:

* Detectar y seguir un objetivo usando visión por computador.

8.4 Gestión de misión
Subtemas:

* Waypoints
* Asignación de tareas
* Monitoreo remoto
* Supervisión humana

Objetivo:

* Coordinar misión, objetivo, seguimiento y control operativo.

Proyecto sugerido:

* Diseñar una misión completa con estados, objetivos y contingencias.

==================================================
MÓDULO 9. SWARM Y SISTEMAS MULTIAGENTE
======================================

9.1 Fundamentos multiagente
Subtemas:

* Consenso
* Coordinación
* Formación
* Cobertura

Objetivo:

* Comprender el comportamiento colectivo de múltiples agentes.

Proyecto sugerido:

* Simular 3 agentes con reglas de coordinación básicas.

9.2 Comunicación distribuida
Subtemas:

* Topologías
* Sincronización
* Tolerancia a fallos
* Latencia

Objetivo:

* Entender cómo se coordinan múltiples sistemas sin control central total.

Proyecto sugerido:

* Simular intercambio de mensajes con retrasos y pérdida de datos.

9.3 Asignación de tareas
Subtemas:

* Leader-follower
* Task allocation
* Cooperación

Objetivo:

* Repartir misiones entre varios agentes.

Proyecto sugerido:

* Simular reparto de objetivos entre múltiples robots.

9.4 Control de enjambre
Subtemas:

* Flocking
* Virtual structure
* Behavior-based control

Objetivo:

* Modelar movimiento coordinado y estable de múltiples vehículos.

Proyecto sugerido:

* Simular flocking o formación en un grupo de drones o rovers.

9.5 Simulación multi-robot
Subtemas:

* ROS 2 multi-robot
* Multi-UAV
* Multi-UGV
* Escenarios mixtos

Objetivo:

* Probar comportamientos colectivos antes de ir a hardware.

Proyecto sugerido:

* Montar una simulación de 3 a 5 agentes cooperando.

==================================================
MÓDULO 10. INTEGRACIÓN DE MISIÓN REAL
=====================================

10.1 Diseño de misión
Subtemas:

* Requerimientos
* Restricciones
* Autonomía
* Payload
* Riesgo

Objetivo:

* Traducir una necesidad operativa a una misión técnica ejecutable.

Proyecto sugerido:

* Diseñar una misión de inspección o exploración con un vehículo no tripulado.

10.2 Validación y pruebas
Subtemas:

* SIL
* HITL
* Pruebas de banco
* Pruebas de campo
* Telemetría
* Análisis de logs

Objetivo:

* Validar con método antes de operar en entorno real.

Proyecto sugerido:

* Crear un protocolo de pruebas para un UGV, UAV o ROV.

10.3 Seguridad operacional
Subtemas:

* Failover
* Retorno seguro
* Pérdida de enlace
* Modos degradados

Objetivo:

* Diseñar sistemas que fallen de manera controlada y segura.

Proyecto sugerido:

* Definir comportamiento de emergencia ante pérdida de navegación o comunicación.

10.4 Proyecto final
Subtemas:

* UAV real o simulado
* UGV real o simulado
* UUV/ROV real o simulado
* Sistema híbrido cooperativo

Objetivo:

* Integrar conocimientos en un sistema funcional con criterio ingenieril.

Proyecto sugerido:

* Proyecto capstone completo con documentación, pruebas y resultados.

==================================================
SECUENCIA GENERAL RECOMENDADA
=============================

Etapa 1

* Módulo 1
* Módulo 2

Etapa 2

* Módulo 3
* Módulo 4

Etapa 3

* Módulo 6 primero
* Módulo 5 después
* Módulo 7 después

Etapa 4

* Módulo 8

Etapa 5

* Módulo 9

Etapa 6

* Módulo 10

==================================================
ORDEN RECOMENDADO DE ESPECIALIZACIÓN
====================================

1. Terrestre primero

* Más fácil de prototipar
* Más seguro
* Más barato
* Ideal para ROS 2, navegación y percepción

2. Aéreo después

* Aprovechas control, estimación y navegación
* Luego entras a autopilotos y dinámica de vuelo

3. Acuático después

* Mayor complejidad de hardware y navegación
* Ideal cuando ya tienes buena base


