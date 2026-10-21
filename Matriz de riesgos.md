# MATRIZ DE RIESGOS DEL PROYECTO — SPRINT 3

**TECNOLÓGICO NACIONAL DE MÉXICO**  
**INSTITUTO TECNOLÓGICO DE TLAXIACO**

- **Carrera:** Ingeniería en Sistemas Computacionales
- **Asignatura:** Gestión de Proyectos de Software (SCG-1009)
- **Unidad:** 3. Planificación del Proyecto
- **Trabajo 3:** Matriz de Riesgos
- **Proyecto:** Sistema de Control y Comercialización de la Producción de Miel
- **Organización beneficiaria:** Unión de Productores de Miel de San Juan Ñumí, Oaxaca
- **Equipo:** Open Hub Tec – Mixteca
- **Metodología:** eduScrum

## Integrantes

- Edgar Axel Sandoval Hernández
- Adriana Hernández Martínez

---

## 1. Introducción

La gestión de riesgos es un proceso fundamental en la planificación de proyectos de software, ya que permite identificar posibles situaciones que pueden afectar el cumplimiento de los objetivos, el presupuesto, los tiempos de desarrollo y la calidad del producto final.

En el proyecto Sistema de Control y Comercialización de la Producción de Miel se busca desarrollar una herramienta informática que permita administrar la información de productores, registrar cosechas, controlar el inventario y organizar los registros de comercialización.

Debido a que la organización beneficiaria se encuentra en San Juan Ñumí, Oaxaca, es necesario considerar aspectos técnicos, sociales, operativos y financieros relacionados con las condiciones de la región Mixteca.

Asimismo, se contemplan los posibles riesgos asociados con mecanismos de financiamiento Web3, como Stellar Community Fund y Drips Protocol, analizados durante el Sprint 2. Estas alternativas se consideran posibles fuentes de apoyo y no recursos económicos confirmados, por lo que la planificación debe contemplar un escenario en el que no se obtenga financiamiento externo.

La matriz permitirá establecer medidas preventivas, asignar responsables, preparar planes de contingencia y dar seguimiento a los riesgos durante el desarrollo del proyecto mediante la metodología eduScrum.

## 2. Objetivo general

Identificar, analizar, clasificar y priorizar los riesgos que pueden presentarse durante el desarrollo del Sistema de Control y Comercialización de la Producción de Miel, estableciendo estrategias de prevención, mitigación y contingencia que favorezcan el cumplimiento de los objetivos del proyecto mediante la metodología eduScrum.

## 3. Clasificación de riesgos

Se consideran tres dimensiones principales:

**Riesgos técnicos:** relacionados con errores en el software, almacenamiento de información, integridad de los registros, controles de seguridad y funcionamiento de los módulos.

**Riesgos sociales y operativos:** relacionados con las condiciones de conectividad de San Juan Ñumí, la participación de los productores, la adaptación tecnológica y la organización del equipo.

**Riesgos financieros y Web3:** relacionados con el presupuesto, los costos de infraestructura y la posibilidad de utilizar Stellar Community Fund o Drips Protocol como mecanismos de apoyo financiero. También incluyen la complejidad de integrar blockchain y los posibles problemas de privacidad asociados con la publicación de información en redes públicas.

## 4. Metodología de evaluación

Para evaluar cada riesgo se utiliza una escala de tres niveles de probabilidad e impacto.

| Valor | Probabilidad | Impacto |
|---:|---|---|
| 1 | Baja | Bajo |
| 2 | Media | Medio |
| 3 | Alta | Alto |

La puntuación se obtiene mediante la siguiente fórmula:

**Exposición del riesgo = Probabilidad × Impacto**

### Clasificación de la exposición

| Resultado | Nivel de riesgo |
|---:|---|
| 1–2 | Bajo |
| 3–4 | Medio |
| 6–9 | Alto |

Esta escala permite establecer prioridades mediante un análisis semicuantitativo. Los valores asignados son estimaciones preliminares del equipo y no probabilidades estadísticas medidas.

## 5. Matriz de identificación y evaluación de riesgos

| ID | Riesgo identificado | Clasificación | Probabilidad | Impacto | Exposición | Nivel |
|---|---|---|---:|---:|---:|---|
| R-01 | Pérdida de registros de productores y cosechas. | Técnico | 2 | 3 | 6 | Alto |
| R-02 | Inconsistencias entre inventario y ventas. | Técnico | 3 | 3 | 9 | Alto |
| R-03 | Interrupciones de conectividad a Internet. | Social y técnico | 3 | 2 | 6 | Alto |
| R-04 | Acceso no autorizado a datos de productores. | Técnico y seguridad | 2 | 3 | 6 | Alto |
| R-05 | Dificultades de adaptación de los productores. | Social | 2 | 2 | 4 | Medio |
| R-06 | Retrasos por disponibilidad limitada del equipo. | Operativo | 2 | 2 | 4 | Medio |
| R-07 | Costos mayores a los estimados. | Financiero | 2 | 3 | 6 | Alto |
| R-08 | Captura incorrecta de cantidades y precios. | Técnico y operativo | 3 | 2 | 6 | Alto |
| R-09 | Cambios no controlados de requisitos. | Gestión | 2 | 2 | 4 | Medio |
| R-10 | No obtener financiamiento mediante Stellar Community Fund o Drips Protocol. | Financiero y Web3 | 3 | 3 | 9 | Alto |
| R-11 | Integración blockchain compleja o innecesaria. | Técnico y Web3 | 2 | 3 | 6 | Alto |
| R-12 | Exposición de información financiera en blockchain. | Ético y Web3 | 2 | 3 | 6 | Alto |

### Interpretación de resultados

Los riesgos R-02 y R-10 presentan la mayor exposición, con nueve puntos. Por ello, deben recibir atención prioritaria durante la planificación.

Los riesgos R-01, R-03, R-04, R-07, R-08, R-11 y R-12 presentan una exposición de seis puntos y requieren medidas preventivas y seguimiento.

Los riesgos R-05, R-06 y R-09 presentan una exposición de cuatro puntos, por lo que se clasifican como medios.

La clasificación representa una prioridad de atención y no significa que los riesgos necesariamente ocurrirán.

## 6. Justificación de la evaluación

| Riesgo | Justificación |
|---|---|
| R-01 | La pérdida de información puede afectar el historial de cosechas y la identificación de los productores. |
| R-02 | Los registros de ventas modifican las existencias; una actualización incorrecta puede ocasionar inventarios negativos o cantidades inconsistentes. |
| R-03 | La conectividad limitada e intermitente de la región Mixteca puede dificultar la consulta de información y el funcionamiento de servicios en línea. |
| R-04 | El sistema administrará información de productores y operaciones comerciales que requiere controles de acceso y protección. |
| R-05 | Los productores podrían tener diferentes niveles de experiencia con herramientas digitales, dificultando la adopción inicial. |
| R-06 | La disponibilidad de los dos integrantes puede verse afectada por otras obligaciones académicas y las fechas de entrega. |
| R-07 | Los gastos de infraestructura y operación todavía no están completamente confirmados. |
| R-08 | Los errores al capturar cantidades y precios pueden afectar el inventario, los reportes y el seguimiento comercial. |
| R-09 | Las modificaciones posteriores a los criterios de aceptación pueden incrementar el tiempo de desarrollo y generar retrabajo. |
| R-10 | Stellar Community Fund y Drips Protocol no representan financiamiento aprobado; depender de recursos no confirmados podría comprometer el proyecto. |
| R-11 | La incorporación de tecnologías Web3 sin un beneficio funcional claro podría elevar los costos y la complejidad técnica. |
| R-12 | La publicación de información financiera identificable en redes blockchain públicas puede afectar la privacidad de los productores. |

Las calificaciones se establecen según las consecuencias posibles de cada situación y deberán actualizarse cuando existan resultados de pruebas, incidentes documentados o nueva información.

## 7. Estrategias de respuesta y responsables

| ID | Estrategia | Responsable propuesto | Medida preventiva | Plan de contingencia |
|---|---|---|---|---|
| R-01 | Mitigar | Edgar Axel | Implementar validaciones, respaldos periódicos y pruebas de recuperación de datos. | Recuperar una copia disponible, verificar la integridad de los datos y documentar los registros afectados. |
| R-02 | Mitigar | Edgar Axel y Adriana | Realizar pruebas de movimientos de inventario, ventas, cantidades y actualización de existencias. | Suspender temporalmente las operaciones afectadas, corregir las existencias y repetir las pruebas antes de reanudar el uso normal. |
| R-03 | Mitigar | Edgar Axel | Probar el sistema con conexiones limitadas e identificar las funciones que requieren Internet. | Informar al usuario y recuperar las operaciones pendientes si la arquitectura lo permite. |
| R-04 | Mitigar | Edgar Axel | Implementar controles de acceso, permisos y medidas de protección de información. | Restringir los accesos afectados, investigar el incidente, corregir la vulnerabilidad y documentar las acciones realizadas. |
| R-05 | Mitigar | Adriana | Preparar capacitación, realizar pruebas de usabilidad y solicitar comentarios de los productores. | Simplificar la interfaz, brindar acompañamiento y repetir las pruebas con los usuarios. |
| R-06 | Mitigar | Edgar Axel y Adriana | Organizar el calendario, distribuir las tareas y revisar periódicamente los avances. | Redistribuir las actividades pendientes, establecer prioridades y reajustar las fechas mediante acuerdo. |
| R-07 | Mitigar | Edgar Axel y Adriana | Revisar periódicamente el presupuesto y distinguir los costos confirmados de los estimados. | Priorizar funcionalidades esenciales y ajustar el alcance a los recursos disponibles. |
| R-08 | Mitigar | Edgar Axel y Adriana | Validar campos, cantidades, precios y reglas de cálculo antes de registrar las operaciones. | Corregir registros inconsistentes, verificar los cálculos y repetir las pruebas funcionales. |
| R-09 | Evitar o controlar | Edgar Axel y Adriana | Definir criterios de aceptación y establecer un procedimiento para controlar cambios. | Registrar la solicitud y evaluar su impacto en tiempo y esfuerzo antes de incorporarla. |
| R-10 | Evitar la dependencia | Edgar Axel y Adriana | Elaborar un escenario sin financiamiento externo y revisar los requisitos de los programas de apoyo. | Ajustar el alcance a los recursos disponibles y continuar con las funciones esenciales del producto mínimo viable. |
| R-11 | Evitar | Edgar Axel | Evaluar si blockchain es técnicamente necesario y aporta un beneficio verificable. | Mantener el sistema administrativo independiente de blockchain hasta demostrar su necesidad y viabilidad. |
| R-12 | Mitigar | Edgar Axel y Adriana | Evitar publicar datos personales o comerciales identificables en redes públicas. | Detener nuevas publicaciones, evaluar la exposición y documentar las medidas correctivas. |

La asignación de responsables se presenta como propuesta y deberá confirmarse por los integrantes del equipo eduScrum. Ambos deberán participar en las decisiones importantes y en la revisión de los riesgos prioritarios.

## 8. Riesgos prioritarios

### 8.1. R-02. Inconsistencias entre inventario y ventas

Este riesgo alcanza una exposición de nueve puntos y se considera prioritario porque afecta directamente las funciones principales del sistema.

La auditoría del Sprint 1 identificó la necesidad de impedir ventas superiores al inventario disponible.

Por ello, deben realizarse pruebas de actualización de existencias, validaciones de cantidades y verificación de los movimientos registrados.

Las acciones prioritarias son:

1. Validar que las cantidades vendidas no superen las existencias disponibles.
2. Verificar que cada venta actualice correctamente el inventario.
3. Probar cantidades válidas, valores incorrectos y existencias insuficientes.
4. Comparar los resultados del inventario con los movimientos de venta.
5. Corregir las inconsistencias antes de aceptar la funcionalidad.

### 8.2. R-10. Ausencia de financiamiento externo

Este riesgo alcanza una exposición de nueve puntos y puede afectar la viabilidad financiera del proyecto.

El proyecto ha considerado Stellar Community Fund y Drips Protocol como posibles mecanismos de financiamiento. Sin embargo, no se dispone de evidencia de que se hayan obtenido estos recursos.

El equipo debe mantener una planeación que permita desarrollar el alcance académico mínimo sin depender de fondos externos.

Las acciones prioritarias son:

1. Revisar los requisitos de elegibilidad y las condiciones de cada alternativa.
2. Distinguir entre financiamiento solicitado, aprobado y efectivamente recibido.
3. Identificar los costos indispensables para el desarrollo y mantenimiento.
4. Preparar un escenario de viabilidad sin financiamiento externo.
5. Ajustar el alcance si los recursos disponibles no permiten realizar todas las funcionalidades propuestas.

### 8.3. R-03. Conectividad limitada

Debido a las condiciones de conectividad que pueden presentarse en la región Mixteca, se recomienda realizar pruebas con conexiones intermitentes y verificar qué funcionalidades requieren Internet.

Las acciones prioritarias son:

1. Identificar las operaciones que necesitan conexión.
2. Medir el comportamiento del sistema con conexiones lentas.
3. Evitar la pérdida de información cuando una operación no pueda completarse.
4. Evaluar alternativas de almacenamiento local solo si son técnicamente viables.
5. Documentar las limitaciones y comunicar a los usuarios qué funciones están disponibles sin conexión.

El funcionamiento offline solamente podrá considerarse implementado cuando existan las funcionalidades y las pruebas correspondientes.

### 8.4. R-04 y R-12. Protección y privacidad de la información

Ambos riesgos presentan una exposición de seis puntos y requieren medidas preventivas.

El sistema puede administrar información de productores, cosechas, cantidades y operaciones comerciales. Por esta razón, es necesario evitar el acceso no autorizado y la publicación de información identificable en redes blockchain públicas.

Las acciones prioritarias son:

1. Limitar el acceso a los datos según las funciones de cada usuario.
2. Evitar almacenar información personal o comercial sensible en redes públicas.
3. Revisar los componentes que puedan afectar la seguridad.
4. Realizar pruebas de acceso y validación de permisos.
5. Documentar y atender cualquier exposición de información detectada.

## 9. Trazabilidad con los sprints anteriores

La matriz se relaciona con los productos de trabajo de los sprints anteriores para mantener la coherencia entre las necesidades identificadas, la calidad esperada y la planificación del proyecto.

| Riesgo | Sprint 1: Historias de usuario | Sprint 2: Calidad | Sprint 3: Planificación |
|---|---|---|---|
| R-01 | Registro de productores y cosechas. | Prevención de defectos y validación de datos. | Estimación de esfuerzo y pruebas de recuperación. |
| R-02 | HU-P1-003 Inventario y HU-P1-004 Ventas. | Auditoría de requisitos y criterios de aceptación. | Estimación del inventario: 38 horas. |
| R-03 | Necesidades de operación en la Mixteca. | OQ-03, conectividad limitada. | Planificación de pruebas y recursos técnicos. |
| R-04 | Información de productores. | Revisiones de calidad y seguridad. | Controles de acceso y asignación de responsables. |
| R-05 | Necesidades de los productores. | Validación de funcionalidades. | Actividades de capacitación y seguimiento. |
| R-06 | Backlog y responsabilidades. | Plan de revisiones. | Distribución propuesta de 144 horas. |
| R-07 | Alcance funcional. | Costo de la Calidad. | Estimación académica de $21,600 MXN de esfuerzo humano. |
| R-08 | HU-P1-004 Ventas. | Auditoría de criterios de aceptación. | Validaciones y pruebas de comercialización. |
| R-09 | Historias de usuario. | Auditoría de requisitos. | Seguimiento de cambios mediante eduScrum. |
| R-10 | Necesidades y viabilidad del proyecto. | Informe Stellar/Drips. | Evaluación financiera preliminar. |
| R-11 | Funcionalidades del sistema. | Análisis de estándares Web3. | Evaluación de integración técnica. |
| R-12 | Datos comerciales. | Consideraciones de privacidad. | Medidas preventivas y contingencias. |

Las cifras de 144 horas y $21,600 MXN son estimaciones propuestas en el Trabajo 2 y deberán ser confirmadas por el equipo. La estimación de 38 horas corresponde al inventario y no necesariamente al esfuerzo total del proyecto.

### 9.1. Relación con el costo de la calidad

El costo de la calidad permite analizar los recursos destinados a prevenir defectos, evaluar el funcionamiento del sistema y corregir errores detectados durante el desarrollo.

La matriz contribuye a esta evaluación al identificar riesgos que pueden generar retrabajo, como los errores de inventario, las fallas de seguridad y los problemas de captura.

Para controlar estos riesgos, Edgar Axel y Adriana deberán registrar las horas dedicadas a prevención, revisión, pruebas y corrección durante cada sprint. Al comparar los resultados con las estimaciones anteriores, será posible determinar si las acciones preventivas ayudan a reducir el esfuerzo de corrección.

Los resultados deberán documentarse con evidencias de las actividades realizadas y no solamente con estimaciones.

## 10. Seguimiento mediante GitHub Projects

Para dar seguimiento a los riesgos se utilizará el tablero:

**Sprint 3 - Planificación - Open Hub Tec – Mixteca**

**Repositorio de referencia:**

https://github.com/SistemasTecTlaxiaco/gestion-de-proyectos-de-software-tablero-group-9

Los riesgos prioritarios podrán registrarse como *Issues* relacionadas con las historias del sistema.

Cada registro deberá contar con:

- Identificador y descripción del riesgo.
- Clasificación y nivel de riesgo.
- Probabilidad, impacto y exposición.
- Responsable de seguimiento.
- Estrategia de respuesta.
- Medida preventiva y plan de contingencia.
- Evidencia de seguimiento.
- Estado de la acción preventiva o correctiva.

Los cambios se revisarán durante las reuniones de planificación, seguimiento y revisión del Sprint 3.

### 10.1. Estados de seguimiento propuestos

| Estado | Descripción |
|---|---|
| Propuesta | El riesgo ha sido identificado y está pendiente de revisión. |
| En estudio | El equipo está analizando su probabilidad, impacto y posibles respuestas. |
| Elegida | Se ha acordado una estrategia de respuesta. |
| En desarrollo | Las medidas preventivas o correctivas están en ejecución. |
| Terminada | Las acciones acordadas se han completado y existe evidencia de su cumplimiento. |
| Descartada | El equipo ha determinado, con justificación, que la propuesta no se aplicará. |

El estado de una acción no significa necesariamente que el riesgo haya desaparecido. Los riesgos residuales deberán continuar bajo seguimiento cuando exista la posibilidad de que ocurran.

## 11. Relación con el análisis de viabilidad

La matriz de riesgos complementa el documento *Objetivo SMART y Análisis de Viabilidad Multidimensional*.

### 11.1. Viabilidad técnica

Deberá comprobarse mediante pruebas funcionales, validación de registros, revisión de la arquitectura y evaluación de los recursos necesarios para ejecutar el sistema.

Los riesgos R-01, R-02, R-03, R-04, R-08 y R-11 requieren especial atención porque pueden afectar la confiabilidad, la seguridad o el funcionamiento de las funcionalidades principales.

### 11.2. Viabilidad operativa

Dependerá de la disponibilidad del equipo, la distribución de tareas, la facilidad de uso y la participación de los productores.

Los riesgos R-05, R-06 y R-09 deberán controlarse mediante capacitación, organización del trabajo, definición de criterios de aceptación y seguimiento de las actividades en eduScrum.

### 11.3. Viabilidad financiera

Requerirá confirmar los costos de infraestructura, operación y mantenimiento, además de identificar los recursos realmente disponibles.

Los riesgos R-07 y R-10 muestran la importancia de no considerar los apoyos externos como ingresos asegurados. La planificación debe incluir un escenario que permita desarrollar las funcionalidades esenciales con los recursos confirmados.

### 11.4. Dictamen preliminar

**Dictamen: SUJETO A VALIDACIÓN.**

No se considera conveniente emitir un dictamen definitivo de viabilidad hasta contar con evidencias suficientes sobre las pruebas técnicas, los recursos disponibles, las necesidades de la organización beneficiaria y los costos de operación.

La decisión de continuar deberá basarse en los resultados de la evaluación y en los acuerdos de Edgar Axel y Adriana, considerando los riesgos que permanezcan sin resolver.

## 12. Seguimiento, control y actualización de la matriz

La matriz deberá mantenerse como un documento de trabajo actualizado durante el desarrollo del proyecto.

Las actividades de seguimiento serán las siguientes:

1. **Revisión inicial:** confirmar los riesgos, su clasificación y los valores asignados.
2. **Asignación de responsables:** acordar quién dará seguimiento a cada riesgo y quién ejecutará las acciones necesarias.
3. **Ejecución de medidas preventivas:** registrar las pruebas, validaciones, respaldos y revisiones que se realicen.
4. **Seguimiento de riesgos prioritarios:** revisar especialmente los riesgos con exposición de nueve puntos.
5. **Registro de incidentes:** documentar cuándo ocurre un riesgo, sus consecuencias y las medidas aplicadas.
6. **Reevaluación:** modificar probabilidad e impacto cuando existan nuevas evidencias.
7. **Cierre de acciones:** registrar los resultados y comprobar que las medidas acordadas se hayan completado.
8. **Actualización al cierre del sprint:** revisar los riesgos residuales y proponer nuevas acciones para el siguiente ciclo de trabajo.

La revisión se realizará durante las reuniones de seguimiento del equipo eduScrum y al cierre de cada sprint. Los riesgos de mayor prioridad deberán atenderse en cuanto sean detectados.

## 13. Conclusión

La matriz de riesgos del Sistema de Control y Comercialización de la Producción de Miel permite identificar y evaluar doce situaciones que podrían afectar el desarrollo del proyecto y el cumplimiento de sus objetivos.

Entre los riesgos de mayor importancia destacan las inconsistencias de inventario, las dificultades de conectividad, la protección de información y la disponibilidad de recursos económicos.

La utilización de una escala de probabilidad e impacto permite establecer prioridades, mientras que las estrategias de respuesta y la asignación de responsables facilitan la organización del trabajo.

La relación entre las historias de usuario del Sprint 1, el Plan de Calidad del Sprint 2 y las estimaciones del Sprint 3 fortalece la coherencia de la planificación y permite dar seguimiento a los riesgos mediante eduScrum.

La participación de Edgar Axel Sandoval Hernández y Adriana Hernández Martínez permitirá distribuir las actividades de análisis, desarrollo, pruebas, documentación y seguimiento. Ambos deberán revisar los riesgos y actualizar las medidas de respuesta con base en las evidencias obtenidas.

Finalmente, el seguimiento periódico permitirá ajustar el alcance cuando sea necesario, controlar el esfuerzo de desarrollo y evitar la dependencia de financiamiento externo no confirmado, procurando que el sistema sea funcional, seguro y útil para la Unión de Productores de Miel de San Juan Ñumí, Oaxaca.

## 14. Referencias

- Equipo Open Hub Tec – Mixteca. (2026). *Plan de Calidad del proyecto, versión 1.0*. Documento de trabajo de la asignatura.
- Equipo Open Hub Tec – Mixteca. (2026). *Objetivo SMART y Análisis de Viabilidad Multidimensional*. Documento del Sprint 3.
- Equipo Open Hub Tec – Mixteca. (2026). *Informe de estándares Stellar/Drips*. Documento del Sprint 2.
- Equipo Open Hub Tec – Mixteca. (2026). *Auditoría con IA*. Documento de trabajo relacionado con las historias de usuario y los criterios de aceptación.
- Stellar Development Foundation. (s. f.). *Grants and funding*. https://stellar.org/grants-and-funding
- Drips. (s. f.). *Documentation*. https://docs.drips.network/
