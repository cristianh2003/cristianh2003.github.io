---
layout: post
title:  "Metodologías de desarrollo de software"
date:   2026-02-18 10:00:00 -0600
categories: Metodologías de desarrollo de software
---

Las metodologías de desarrollo de software son marcos de trabajo estructurados que sistematizan la producción de software. Estas definen los procesos, artefactos y roles necesarios para gestionar el ciclo de vida del desarrollo, desde la especificación de requisitos hasta el mantenimiento, con el objetivo de optimizar la calidad del producto y la eficiencia del equipo.

Existen dos enfoques principales: las metodologías tradicionales, que priorizan la planificación exhaustiva y la documentación, y las metodologías ágiles, que se centran en la adaptabilidad y la entrega iterativa. 

Según Sommerville:[¹](#referencias) 
>"Un proceso de software (o metodología) es una serie de actividades relacionadas que conduce a la elaboración de un producto de software".

## Metodología Tradicional
Este enfoque se centra en una planificación detallada y exhaustiva al inicio del proyecto. Se asume que los requisitos pueden definirse completamente antes de comenzar la codificación. El proceso es lineal y secuencial; una fase no comienza hasta que la anterior ha finalizado.

### Tipos principales
* **Modelo en Cascada:** El nombre de cascada de esta metodología se deriva de cómo se organizan las etapas (de arriba a abajo), desarrollando las funciones en etapas diferenciadas y en estricto orden. En esta metodología se debe revisar el producto antes de cada etapa para ver si está listo para pasar a la siguiente fase.

    En el modelo en cascada las actividades el desarrollo fundamental de este modelo se derivan en las siguientes etapas: Análisis y definición de requerimientos, Diseño del sistema hardware, Implementación y prueba de unidades, Integración y prueba del sistema, Funcionamiento y mantenimiento.

    Las ventajas del modelo en cascada son que la documentación se produce en cada fase y este cuadra con otros modelos del proceso de ingeniería. La principal desventaja es su inflexibilidad en dividir el proyecto en distintas etapas.

    ![Diagrama de Cascada](/assets/img/diagrama_cascada.webp)

* **Modelo Incremental:** En esta metodología de desarrollo de software se va elaborando el producto final de manera progresiva. En cada etapa se añade una nueva funcionalidad, con la finalidad de ver resultados de una forma más rápida en comparación con el modelo en cascada.

    Una de las características de este modelo de desarrollo es que el software se
    puede empezar a utilizar incluso antes de que se complete totalmente y, en
    general, es mucho más flexible que las demás metodologías.

    En otras palabras el modelo de desarrollo incremental es la duración de vida de desarrollo software, el mismo descompone un proyecto en una serie de incrementos, los cuales suministran una porción de la funcionalidad respecto de la totalidad de los requisitos del proyecto. 
    
    Los requisitos tienen asignada una prioridad y son entregados según el orden de prioridad en el incremento
    correspondiente.

    ![Diagrama de modelo incremental](/assets/img/incremental.png) 

* **Prototipo:** La metodología de desarrollo de software prototipo, se fundamenta en la elaboración de un prototipo que se construye rápidamente, para que el cliente o usuario lo pruebe y proporcione su feedback, lo que permite detectar y arreglar lo que está mal, e introducir requerimientos que puedan presentarse, este modelo se fundamenta en el método de ensayo y error para entender las especificidades del producto.

    En este modelo de proceso, el sistema se implementa parcialmente antes o durante la fase de análisis, lo que permite a los clientes ver el producto en las primeras etapas de su ciclo de vida. El proceso comienza con la entrevista a los clientes y el desarrollo del modelo de alto nivel incompleto.

    Es un enfoque iterativo que crea versiones preliminares funcionales (prototipos) para validar requisitos con el cliente antes del desarrollo final. Permite visualizar la interfaz y funcionalidades, reduciendo riesgos, costos y mejorando la comprensión del sistema. Es ideal cuando los requisitos no están claros.[²](#referencias)

    ![Diagrama de Prototipo](/assets/img/prototipo.png) 

* **Espiral:** El nombre de esta metodología se debe a su funcionamiento, ya que las etapas se procesan en forma de espiral. Cuanto más cerca del centro se está, más avanzado está el proyecto.

    Esta metodología se caracteriza por combinar dos modelos, el incremental y el
    prototipo, que agrega la idea de análisis de riesgo. La misma se divide en cuatro
    etapas: planificación, análisis de riesgo, desarrollo de prototipo y evaluación del cliente.

    Otra característica del desarrollo en espiral es la minimización de los riesgos en
    el desarrollo de software. Estos riesgos se enfrentan al enfoque incremental,
    realizando primero prototipos, que luego pasan por las fases de desarrollo de
    software.

    El desarrollo o modelo en espiral es un enfoque de desarrollo de software que
    puede ser considerado como una respuesta a los inconvenientes del desarrollo
    en cascada. El modelo en espiral explica las etapas de vida de un software por
    medio de espirales, que se repiten hasta entregar el producto terminado.

    El desarrollo en espiral es universal y se combina con otros métodos de
    desarrollo clásicos y ágiles, es por ello que también se le llama modelo o
    desarrollo de segundo orden.

    ![Diagrama de Espiral](/assets/img/espiral.png)

* **Desarrollo Rapido de Aplicaciones:** En español Modelo de Desarrollo Rápido de Aplicaciones (DRAI), y por sus siglas en inglés RAD, (Rapid Application Development) y es un procedimiento ágil de desarrollo de software, el cual da prioridad a las entregas y repeticiones rápidas de prototipos. Cabe destacar que las repeticiones rápidas reducen el periodo de desarrollo y agilizan la entrega.

    Este modelo se caracteriza por sus equipos compuestos por alrededor de seis
    personas, incluyendo desarrolladores y usuarios de tiempo completo del sistema
    así como aquellas personas involucradas con los requisitos.

    Cuando se toma la decisión  de adoptar la metodología DRA, se debe tener en
    cuenta las ventajas y desventajas de su uso y saber por qué utilizar RAD.

    La idea es adaptarse rápidamente a los problemas, oportunidades y actualizaciones, al mismo tiempo que se pueden tomar decisiones basadas en datos y basar el diseño y desarrollo de la solución tanto en los requisitos como en el conocimiento adquirido en procesos anteriores o en curso.

    Sin embargo, con el paso de los años, esta metodología y su concepto cambiaron (y continúan haciéndolo). Lo cual es comprensible, considerando el mero hecho de que se trata de adaptaciones, flexibilidad y cambios de acuerdo con los proyectos, las personas, la tecnología y el tiempo.[³](#referencias)

    ![Diagrama de Desarrollo Rapido de Aplicaciones](/assets/img/espiral.png)

## Ventajas y Desventajas de las Metodologías Tradicionales
### Ventajas:
- **Previsibilidad:** Los plazos, costos y alcance se definen al inicio.
- **Documentación:** Genera un registro exhaustivo del sistema, facilitando el mantenimiento futuro por terceros.
- **Disciplina:** Ideal para proyectos críticos (ej. software médico o aeroespacial) donde el error es inadmisible.

### Desventajas:
- **Rigidez:** Poca tolerancia a cambios en los requisitos una vez iniciado el desarrollo.
- **Entrega tardía de valor:** El cliente solo ve el producto funcional al final del ciclo de vida.
- **Riesgo de "Análisis-Parálisis":** Se puede invertir demasiado tiempo en la planificación sin escribir código.


### Referencias
1. Sommerville, I. (2011). Software Engineering (9th ed.). Addison-Wesley.
2. Modelo de prototipos - EcuRed. (2026). Ecured.cu. https://www.ecured.cu/Modelo_de_prototipos
3. Infragistics. (2022, September 6). ¿Qué es el desarrollo rápido de aplicaciones (modelo RAD)? App Builder. https://www.appbuilder.dev/es/blog/rapid-application-development

‌