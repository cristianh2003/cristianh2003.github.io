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

    Es un enfoque iterativo que crea versiones preliminares funcionales (prototipos) para validar requisitos con el cliente antes del desarrollo final. Permite visualizar la interfaz y funcionalidades, reduciendo riesgos, costos y mejorando la comprensión del sistema. Es ideal cuando los requisitos no están claros.[$^4$](#referencias)

    ![Diagrama de Prototipo](/assets/img/prototipo.png) 


### Referencias
- [^1]Sommerville, I. (2011). Software Engineering (9th ed.). Addison-Wesley.
- [^4] Modelo de prototipos - EcuRed. (2026). Ecured.cu. https://www.ecured.cu/Modelo_de_prototipos

‌