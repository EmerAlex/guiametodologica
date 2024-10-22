---
layout: post
title: Documentación técnica
subtitle: Consideración con respecto a la documentación técnica.
banner:
  image: assets/images/content/7_definir_entregables_tecnicos/banner_definir_entregables_tecnicos.jpg
  opacity: 0.618
  background: "#000"
  height: "100vh"
  min_height: "38vh"
  heading_style: "font-size: 4.25em; font-weight: bold;"
  subheading_style: "color: gold"
top: 7
sidebar: []
---

## Documentación técnica.

Una vez identificado los procesos con sus respectivos patrones, se empieza con la definición técnica, para ello se divide en dos sesiones, la documentación técnica base y la documentación técnica de los patrones.

## Documentación base.

la documentación técnica base de un proyecto de software enfocado en los reembolsos o reclamos es esencial para garantizar la comprensión, mantenimiento y escalabilidad del sistema. A continuación, se presentan los componentes clave de esta documentación.

- **Requisitos del Software:** Este documento detalla las necesidades y expectativas del cliente y los usuarios finales. Incluye requisitos funcionales (qué debe hacer el sistema) y no funcionales (rendimiento, seguridad, etc.). Es fundamental para guiar el desarrollo y asegurar que el producto final cumpla con las expectativas.

- **Diseño del Sistema:** Describe la arquitectura del software, incluyendo diagramas de flujo y descripciones de componentes. Este documento proporciona una visión general de cómo se estructurará el sistema y cómo interactúan sus partes.

- **Plan de Pruebas técnicas:** Este documento detalla la estrategia de pruebas que se utilizará para verificar que el software cumple con los requisitos especificados. Incluye tipos de pruebas (unitarias, de integración, de sistema) y criterios de aceptación.

- **Manual de Usuario:** Proporcionar instrucciones sobre cómo utilizar el software. Incluir guías paso a paso, ejemplos y soluciones a problemas comunes. Es crucial para facilitar la adopción del software por parte de los usuarios finales .
Guía de Instalación: Proporciona instrucciones sobre cómo instalar y configurar el software en diferentes entornos. Es esencial para asegurar que los usuarios puedan implementar el sistema sin problemas.

## Documentación patrones.

Para la documentación de patrones como insumos se tomara el resultado final de  [ver más...](/2024/10/05/definir_patrones.html), en base a la información plasmada para cada patrón se debe de detallar de forma más técnica cada uno. Para ello se le hacen modificaciones y se debe de complementar la información asociada.

- **Proceso:** Nombre del procesos asosciado, no puede existir un patrón sin procesos.

- **Nombre:** Asigna un nombre claro y descriptivo que refleje la función del patrón. El nombre debe ser intuitivo para facilitar su identificación y uso.

- **Datos entrada:** Define la información necesaria para que el patron finalice de forma correcta, este corresponde a la conexión que va haber entre los patrone.

- **Datos salida:** Define la información generada en la ejecución del patron.


![Definición inicial del patrón](..\..\..\assets\images\content\7_definir_entregables_tecnicos\drawio\primer_paso_deficincion_entregables_tecnicos.drawio.png)
> un proceso debe tener más de dos patrones un patrón debe de tener una relación con otro, ya que son comportamientos para lograr el cumplimiento del proceso

Una vez se definen los patrones de forma técnica,  se debe establecer la relación entre ellos.


![Definición parcial 2 del patrón](..\..\..\assets\images\content\7_definir_entregables_tecnicos\drawio\segundo_paso_deficincion_entregables_tecnicos.drawio.png)
> Para de unión de los patrones se recomienda utilizar o decribir la información o datos requeridos en el seguinete patrón.

Una vez establecida las relaciones entre los patrones, lo unico que restaria es agrupar por proceso y establecer la relaciones entre los procesos.

>Un proceso puede estar relacionado con más de un proceso y se puede ejecutar de forma paralela, para ello y en base al tiempo de ejecución del proceso se diagrama las relaciones, las relaciones nos indican el orden de ejecución y que insumos debe de pasarse de un proceso a otro.

![Definición final del patrón](..\..\..\assets\images\content\7_definir_entregables_tecnicos\drawio\paso_final_deficincion_entregables_tecnicos.drawio.png)

