# 06. Balanced Scorecard (BSC)

## Propósito

El Balanced Scorecard traduce la estrategia de fidelización y retención en objetivos, indicadores y acciones que pueden revisarse periódicamente. La tabla propuesta se adapta al contenido del documento académico y transforma los plazos absolutos en horizontes relativos. **Las metas se consideran propuestas de planificación; no representan resultados obtenidos.**

## Reglas de implementación

Antes de evaluar el desempeño se recomienda:

1. Acordar la definición de cada indicador y su fórmula.
2. Definir una línea base con datos de un periodo representativo.
3. Asignar a cada KPI un dueño, fuente, periodicidad y responsable de validar calidad.
4. Establecer metas tras revisar capacidad operativa y costo; cuando se conserva una meta del informe original, se identifica como referencia pendiente de validación.
5. Revisar resultados y decisiones, no solo el valor numérico: cada desviación debe tener una hipótesis de causa y una acción.

## BSC propuesto

| Perspectiva | Objetivo estratégico | KPI y definición inicial | Meta o referencia | Iniciativas | Responsable propuesto | Horizonte relativo |
|---|---|---|---|---|---|---|
| Financiera | Proteger y aumentar ingresos recurrentes | **MRR:** suma del ingreso mensual recurrente de suscripciones activas, usando una definición estable de descuentos y servicios incluidos | El documento base aproxima el MRR a COP 30 millones. Verificar la línea base antes de fijar el objetivo de crecimiento | Revisar cohortes, renovaciones, expansión de cuentas y motivos de baja | Dirección + ventas/finanzas | Línea base en meses 0–1; revisión mensual |
| Cliente | Mejorar satisfacción y recomendación | **CSAT** (satisfacción posterior a una interacción) y **NPS** (disposición a recomendar), reportados por separado | El informe original propone NPS de 45. Validar método de encuesta, línea base y representatividad antes de adoptar el valor | Encuestas postservicio, canal de retroalimentación y cierre de acciones correctivas | Soporte + éxito del cliente | Diseño en mes 1; piloto en meses 2–3; revisión trimestral |
| Cliente | Reducir cancelación y mejorar renovación | **Churn de clientes:** clientes cancelados durante el periodo / clientes activos al inicio del periodo, con reglas explícitas para bajas y reactivaciones | Definir línea base y después fijar una reducción realista por segmento; el informe no presenta una tasa inicial verificable | Alertas de riesgo, contacto proactivo, entrevistas de salida y planes de recuperación | Éxito del cliente + ventas | Diseño en meses 0–1; piloto en meses 2–3; evaluación en meses 3–6 |
| Cliente | Ampliar presencia en sectores prioritarios | Nuevos clientes por sector, conversión de oportunidades y expansión de cuentas | El documento fuente plantea crecimiento durante un periodo de 12 meses, pero no ofrece una cifra objetivo consistente | Eventos, contenido educativo, demostraciones personalizadas y alianzas | Ventas + marketing | Plan en meses 1–3; evaluación mensual hasta el mes 12 |
| Procesos internos | Reducir fricción en soporte | Tiempo de primera respuesta y tiempo de resolución, definidos como indicadores distintos | El informe plantea reducir en cinco minutos el tiempo de respuesta. Validar unidad, línea base, horario y tipo de solicitud antes de usar como meta | Clasificación de solicitudes, base de conocimiento, protocolos y automatización de tareas de bajo riesgo | Soporte + producto | Línea base en mes 1; experimento en meses 2–3; ajuste en meses 3–6 |
| Procesos internos | Mejorar rendimiento y estabilidad del producto | Tasa de errores críticos, incidencias repetidas, disponibilidad y tiempo de carga según definición técnica | Establecer objetivos tras auditar telemetría y errores; el documento no aporta una línea base fiable | Backlog priorizado por impacto; pruebas de regresión; revisión de versión móvil | Ingeniería + calidad | Priorización en meses 0–1; ejecución continua desde mes 2 |
| Procesos internos | Evaluar analítica predictiva para ventas o riesgo de abandono | Número de predicciones válidas, precisión/recall cuando aplique, alertas útiles y acción tomada | El informe propone más de 5.000 predicciones en diez meses, pero el volumen no demuestra calidad ni impacto. Tratarlo como referencia para validar | Piloto con datos autorizados, revisión humana y comparación con una línea base | Analítica + ingeniería + privacidad | Diseño en meses 1–3; piloto en meses 3–6; evaluación en meses 6–10 |
| Aprendizaje y crecimiento | Mejorar habilidades de comunicación, escucha y empatía | Finalización de formación, evaluación de conocimientos y aplicación observada en casos de atención | El informe menciona 50 empleados en seis meses, pero debe validarse contra tamaño y composición de la plantilla | Formación híbrida, prácticas situacionales, feedback y reconocimiento | Liderazgo + gestión humana + soporte | Diagnóstico en mes 1; programa en meses 2–6 |
| Aprendizaje y crecimiento | Fomentar cultura de innovación y colaboración | Ideas presentadas, evaluadas, implementadas y beneficio demostrado | Establecer línea base y meta tras el primer ciclo, sin premiar volumen de ideas por sí solo | Buzón digital o físico, revisión mensual y comunicación de decisiones | Innovación + líderes funcionales | Diseño en meses 1–2; ciclos mensuales desde mes 3 |

## Presupuesto y viabilidad

El documento académico incluye una referencia de **COP 2.000.000** asociada a una iniciativa de la perspectiva financiera, una estimación de **COP 10.000.000** para capacitación y un rango de **COP 1.500.000–3.000.000 mensuales por cada uno de dos perfiles propuestos**. El alcance y el periodo exacto de cada rubro no están suficientemente desglosados.

No deben sumarse como si fueran un presupuesto validado. Para construir uno utilizable, especificar para cada iniciativa: concepto, cantidad, costo unitario, periodo, costo recurrente/no recurrente, impuestos o cargas laborales, proveedor, fuente de financiación y criterio de aprobación.

## Tablero mínimo de seguimiento

Se recomienda comenzar con un tablero mensual que muestre, por segmento y con fechas comparables:

- MRR y variación frente al periodo anterior;
- churn y renovación;
- CSAT/NPS con tamaño de muestra y tasa de respuesta;
- tiempo de primera respuesta y resolución;
- incidencias críticas y repetidas;
- adopción de funciones prioritarias;
- avance de capacitación y acciones de mejora cerradas.

Las cifras agregadas deben poder rastrearse hasta la fuente de datos autorizada. Los responsables de cada KPI deben anotar variaciones de definición o calidad que afecten la comparación histórica.

## Nota sobre el recuento de clientes

El documento fuente usa una estimación de **117 clientes** para el cálculo de ingreso recurrente y, en otro objetivo, menciona **más de 10.000 clientes activos**. No queda claro si la segunda referencia corresponde a usuarios, contactos, registros u otra unidad. No se pueden comparar ni usar para un objetivo hasta aclarar las definiciones.

## Cadencia de gobernanza sugerida

- **Mensual:** reunión operativa para revisar KPI, incidentes, clientes en riesgo y acciones pendientes.
- **Trimestral:** revisión estratégica del BSC, validez de supuestos, resultados de pilotos y reasignación de recursos.
- **Al cierre de cada piloto:** decisión documentada de escalar, ajustar o detener según resultado, costo y riesgos.

## Criterio de éxito

La propuesta tendrá evidencia de valor solo si las métricas acordadas mejoran frente a una línea base válida y si el cambio puede relacionarse razonablemente con las iniciativas implementadas. No se deben presentar las metas planteadas en el documento original como resultados reales.
