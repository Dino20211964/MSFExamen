\[!\[Open in MATLAB Online]

# Examen Modelado de sistemas Fisiologicos

## Información de la estudiante

Victor Silvano Dino Seanez \[20211964]; l20211964@tectijuana.edu.mx

Modelado de Sistemas Fisiológicos

Ingeniería Biomédica

## Docente

Dr. Paul Antonio Valle Trujillo; paul.valle@tectijuana.edu.mx

Departamento de Ingeniería Eléctrica y Electrónica, Tecnológico Nacional de México/IT Tijuana, Blvd. Alberto Limón Padilla s/n, Tijuana, C.P. 22454, B.C., México.

## Descripción de la asignatura

El modelizado de sistemas fisiológicos es una herramienta importante en Ingeniería Biomédica, permite comprender el funcionamiento del cuerpo humano, así como diseñar y evaluar terapias y dispositivos médicos; se define como el proceso de formular modelos matemáticos o computacionales que representan el comportamiento y la interacción de los sistemas biológicos y fisiológicos. Esta asignatura pretende aportar al perfil del Ingeniero Biomédico la capacidad de realizar investigación científica en el área de Biología de Sistemas con la finalidad de dirigir y participar en equipos de trabajo interdisciplinarios en contextos nacionales e internacionales, así como de proporcionar soluciones informáticas para resolver problemas en el campo de la Ingeniería Biomédica con ética profesional; lo anterior al proporcionar al estudiante bases sólidas para modelizar sistemas y diseñar controladores para la solución de problemas en las áreas de atención médica y del sector industrial médico. La construcción de analogías entre circuitos eléctricos y sistemas fisiológicos para la formulación de modelos matemáticos y el diseño de controladores mediante la experimentación in silico brindan herramientas de gran aplicación en el quehacer profesional del Ingeniero Biomédico.

La asignatura de Modelado de Sistemas Fisiológicos forma parte del plan de estudios de la carrera en Ingeniería Biomédica con la siguiente competencia general del curso: Utiliza las propiedades de los circuitos RLC para describir la dinámica de sistemas fisiológicos, obtener modelos matemáticos y aplicar el control clásico, esto con el objetivo de integrar los principios de la Ingeniería de Control, la Electrónica Analógica y las Ciencias de la Computación con la Anatomía y Fisiología del cuerpo humano para proporcionar descripciones cuantitativas y cualitativas de sistemas fisiológicos complejos con el objetivo de modelizar, analizar, controlar, ilustrar y predecir su dinámica tanto en el corto como en el largo plazo.

## Objetivos

1. (20 puntos) Dibuje el diagrama eléctrico del sistema cardiovascular, identificando cada uno de sus elementos, es decir, 
componentes, voltajes, corrientes y nodos de entrada y salida.
Valores de los componentes para el Control: R1 = 3 kΩ, L = 330 µH, R2 = 300 kΩ y C = 3.3 µF.
Valores de los componentes para el Caso: R1 = 3 kΩ, L = 330 µH, R2 = 3 kΩ y C = 330 µF
2. (30 puntos) Determine el modelo de ecuaciones integro-diferenciales y la función de transferencia del sistema.
3. (30 puntos) Utilice Simulink para construir el sistema cardiovascular descrito y obtener las respuestas del Control, el Caso y 
el sistema de control en lazo cerrado. El tiempo de simulación debe ser de 10 s.
Figura. Lienzo representativo para construir en Simulink.
4. (20 puntos) Las simulaciones solamente deben realizarse en Simulink, se debe crear un repositorio de GitHub con los 
archivos e imágenes correspondientes al Scope con las señales de cada subsistema, así como los parámetros del 
controlador, capturas de pantalla de cada subsistema. El repositorio debe tener sus archivos de README y CITATION.

## Descripción detallada del sistema

El sistema representa un modelo simplificado del sistema cardiovascular mediante un circuito RLC de segundo orden. La fuente de voltaje Ve(t)Ve(t)Ve(t) simula el impulso eléctrico generado por el nodo sinoauricular del corazón. El resistor R1R1R1 representa la resistencia vascular principal al flujo sanguíneo, mientras que el inductor LLL modela la inercia de la sangre y su oposición a cambios bruscos de flujo.
En el nodo principal se obtiene la salida Vs(t)Vs(t)Vs(t), que representa la presión o energía del sistema. A partir de este nodo se conectan dos ramas en paralelo: el resistor R2R2R2, asociado a la capacidad de respuesta y estabilidad del sistema, y el capacitor CCC, que representa la elasticidad de las arterias y el almacenamiento temporal de energía.
La interacción entre RRR, LLL y CCC produce un comportamiento dinámico de segundo orden similar al funcionamiento del corazón y la circulación sanguínea, permitiendo analizar la respuesta del sistema mediante ecuaciones diferenciales, función de transferencia y simulaciones en Simulink.

## Lista de archivos incluidos en el repositorio

1. Modelo de Simulink \[.slx].
2. Imagen con los parámetros del controlador.
3. Imágenes de las simulaciones \[.pdf y .png].
4. Análisis matemático: Función de transferencia, modelo de ecuaciones integro-diferenciales, estabilidad y error en estado estacionario.

## Referencias

\[1] P. A. Valle, Syllabus para Modelado de Sistemas Fisiológicos, Tecnológico Nacional de México / Instituto Tecnológico de Tijuana, Tijuana, B.C., México, 2025. Permalink: https://biomath.xyz/course/

\[2] M. C. Khoo, Physiological Control Systems Analysis Simulation, and Estimation, 2nd ed. Piscataway, New Jersey, USA: IEEE Press, 2018, Section 4, Page 93.

\[3] N. S. Nise, Control Systems Engineering, 8th ed. Hoboken, New Jersey, USA: John Wiley \& Sons, 2020.

