# Objetivos del arquitecto

Skateholders -> partes interesadas


## Un arquitecto debería tener habilidades en:

- Dominio de arquitectura de software, [metodología de componentes](http://marich.blogspot.es/1459441356/metodologia-basada-en-componentes/) y su interacción.
  - [pdf de metodologia basada en componentes](https://www.fing.edu.uy/inco/lab/dotnet/material/relacionado/vp03.pdf)
- Conocimiento de las tecnologías de comunicación disponibles.
- Estándares y normas a aplicar en la construcción de software de la tecnología a su cargo.
- Conocimiento en programación avanzados en varios lenguajes, arquitecturas y paradigmas.
- Manejo de herramientas para la gestión de requerimientos y ambientes de desarrollo.
- Lecto-comprensión y elementos de redacción en inglés.
- Conocimiento avanzado de Bases de Datos (tanto en la rama de programación como administración).
- Conocimiento avanzado de comunicación entre aplicaciones: SOA, Servicios Web (SOAP, REST), protocolos y lenguajes de comunicación (XML, JSON).
- Conocimientos de Ingeniería del Software.
- Prácticas de Testing y Refactoring.
- Conocimiento de metodologías de análisis como UML u otras.
- Conocimiento de metodologías ágiles como SCRUM u otras.
- Conocimiento de herramientas de control de versiones como GIT u otras.
- Conocimientos de patrones de software empresarial.
- [Conceptos extraídos de detalle-de-arquitecto-de-software-3](http://www.cessi.org.ar/perfilesit/detalle-de-arquitecto-de-software-3)

## Objetivos del arquitecto.

El arquitecto tiene varias partes interesadas “stakeholders” el cual tiene que conectar esto requerimientos de cada stakeholders con la implementación del sistema.

### Stakeholders involucrados con diferentes requerimientos:

- **Cliente**: Entrega a tiempo y que no rebase el presupuesto.
- **Manager**: Comunicación clara entre los equipos que participan en el desarrollo del sistema
- **Dev**: Que el desarrollo llevado acabo sea fácil de implementar y mantener
- **Usuario**: Disponibilidad del producto.
- **QA**: Fácil de probar.

### El arquitecto de software debe gestionar los siguientes puntos para cada Stakeholder:

- Encontrar los riegos más altas que afecten en el desarrollo del sistema (**Cliente**)
- Modularización y flexibilidad del sistema que se está desarrollando (**Manager**)
- Modularidad, mantenibilidad y capacidad de cambio del software (**Dev**)
- Desisdir estrategias para la disponibilidad del sistema (**Usuario**)
- Que el sistema pueda ser modularizado y cada una destas partes pueda ser probado de forma fácil (**QA**).

La unión de estos requerimientos (funcionales / no funcionales) va a llevar al arquitecto a tomar decisiones que impactan directamente en el desarrollo del software.


## MODULARIZACION

Los programas pueden escribirse en módulos, los que permiten que un problema general pueda descomponerse en una serie de subproblemas independientes (Divide y vencerás). Se puede repartir la tarea entre varias personas, y concentrarse en la resolución de cada subproblema.

Cuando una tarea debe realizarse más de una vez en un mismo programa,** la modularización evita la programación redundante**, ya que una vez definida la tarea como un módulo independiente, puede ser invocada desde cualquier parte del código; se aprecia también una menor longitud del programa.
Otra ventaja de importancia es la claridad que resulta de la descomposición de un programa en módulos concisos e independientes, representando cada uno de estos una parte bien definida del problema en su conjunto, permitiendo escribir y depurar el código más fácil. Su estructura lógica es más clara, lo cual es sumamente útil si el programa es largo y complicado.


