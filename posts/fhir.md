---
title: "FHIR, el nuevo miembro de la familia HL7."
date: "2020-06-03"
---

![FHIR-HL7](/images/FHIR-HL7.png "FHIR-HL7")

Durante este año hemos  seguido de cerca el desarrollo de una iniciativa que promete facilitar  la interoperabilidad entre sistemas de información del sector salud. 

Se trata de FHIR® o Fast Healthcare Interoperability Resources (Recursos Rápidos de Interoperabilidad en Salud), la nueva propuesta de especificación de estándares HL7 para el intercambio electrónico de información en salud; cuyo surgimiento obedece a las dificultades de implementación de HL7 V3, a la necesidad de transición de HL7 V2.x y los retos que suponen las nuevas tendencias como  Mobile Health y aplicaciones de telefonía móvil, Personal Health Record, intercambio de registros electrónicos de salud o historia clínica electrónica , comunicaciones en la nube y mucho más.


De acuerdo con el sitio web de Health Level Seven: “FHIR® es un marco de estándares de última generación creado por HL7.  FHIR® combina las mejores características de las líneas de producto HL7 versión 2, versión 3 y CDA®, al tiempo que aprovecha los últimos estándares web, aplicado un enfoque estricto de implementación” [Ver texto original].

¿Cómo funciona FHIR®?
Para comprender la especificación FHIR®, es necesario familiarizarse con términos como "Recursos", "Elementos Narrativos" y "Extensiones"; además de tener conocimientos previos en los conceptos de "Mensajes" y "Documentos" electrónicos empleados en las especificaciones HL7 V2.X y V3.

Adicional a lo anterior, es necesario comprender el uso de ciertos formatos como XML o JSON y especificaciones de transporte de datos (transferencia de archivos FTP/FTPS, HTTP, MLLP, Mensajería MQ, SOAP, REST).

A continuación, los pondremos en contexto con algunos de éstos términos.

![Recursos FHIR](/images/framework-2.png "Recursos FHIR")

Los recursos.
Los artefactos de interoperabilidad de FHIR® se componen a partir de un conjunto de componentes modulares llamados "Recursos", cuyo contenido ha sido diseñado para el intercambio de datos.

Estos recursos, son representaciones de conceptos empleados en el contexto de la salud (paciente, medicación, observación, etc), que funcionan como bloques de construcción que permiten componer estructuras de mensajes y/o documentos (en forma similar a los arquetipos OpenEHR).

Todos los recursos comparten las siguientes características:

Una manera común de definirlos y representarlos, cuya construcción se hace a partir de los tipos de datos que definen patrones comunes de elementos reutilizables (similar a los CMETs de HL7 V3).
Un conjunto común de metadatos.
Un elemento para facilitar la legibilidad humana.
La documentación de la especificación FHIR® para cada recurso, contiene una descripción detallada, definiciones formales de los elementos, ejemplos, mapeos (para HL7 V3 y HL7 V2.x) y perfiles.
