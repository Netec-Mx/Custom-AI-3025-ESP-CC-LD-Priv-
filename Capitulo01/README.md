# Guía práctica — Preparación de una propuesta inicial para un prospecto de CIBEST CAPITAL con Microsoft 365 Copilot


> Esta práctica se centra en preparar una primera conversación con un prospecto ficticio. No se deben emitir recomendaciones de inversión, seleccionar productos financieros ni inventar información del prospecto.

---

## Metadatos

| Campo | Detalle |
|---|---|
| **Duración** | **143 min** |
| **Complejidad** | Media |
| **Nivel de Bloom** | Aplicar / Analizar |
| **Tipo de actividad** | Práctica guiada integrada |
| **Licencia** | Microsoft 365 Copilot Premium, según el entorno del curso |
| **Aplicaciones** | Microsoft Copilot Chat, Word, PowerPoint, Excel, Outlook y Teams |
| **Modalidad** | Individual, paso a paso |
| **Insumos previos** | No requiere archivos preparados |
| **Datos utilizados** | Solo escenario ficticio y fuentes públicas |
| **Resultado** | Ficha de preparación, preguntas de descubrimiento, contexto público del sector, presentación, matriz de necesidades, dos borradores de correo y agenda interna |

### Distribución de tiempo

Los tiempos incluyen un margen razonable para que Copilot genere respuestas y para que el participante las revise. Si una respuesta llega más rápido, utiliza el tiempo restante para validar el contenido.

| Fase | Actividad | Tiempo total |
|---|---|---:|
| 1 | Comparar un prompt general con uno contextualizado | 15 min |
| 2 | Construir preguntas de descubrimiento | 15 min |
| 3 | Investigar contexto público del sector logístico | 18 min |
| 4 | Crear la ficha de preparación en Word | 18 min |
| 5 | Crear el material introductorio en PowerPoint | 20 min |
| 6 | Construir la matriz de necesidades en Excel | 20 min |
| 7 | Preparar el correo de bienvenida en Outlook | 12 min |
| 8 | Preparar el correo de seguimiento en Outlook | 12 min |
| 9 | Preparar la reunión interna en Teams y validar el conjunto | 13 min |
|  | **TOTAL** | **143 min** |

---

## Descripción general

Trabajarás como un ejecutivo de **CIBEST CAPITAL** que se prepara para una primera conversación con un prospecto ficticio.

Durante la práctica utilizarás Microsoft 365 Copilot para:

1. Comparar un prompt general con uno mejor contextualizado.
2. Identificar qué información todavía falta conocer del prospecto.
3. Preparar preguntas de descubrimiento.
4. Investigar información pública reciente sobre el sector logístico latinoamericano.
5. Crear una ficha de preparación en Word.
6. Crear un material introductorio breve en PowerPoint.
7. Construir una matriz de información conocida y pendiente en Excel.
8. Redactar un correo de bienvenida y un correo de seguimiento en Outlook.
9. Preparar una agenda de coordinación interna en Teams.

El objetivo no es obtener una recomendación de inversión. El objetivo es **preparar correctamente la conversación, reconocer lo que se sabe y lo que todavía debe confirmarse, y utilizar Copilot como apoyo sin permitir que invente información**.

---

## Objetivos de aprendizaje

Al finalizar la práctica podrás:

- Construir prompts con contexto, objetivo, restricciones y formato esperado.
- Identificar datos conocidos, desconocidos y supuestos que deben evitarse.
- Diseñar preguntas de descubrimiento sin responder en nombre del prospecto.
- Usar búsqueda web de Copilot para obtener contexto público reciente y revisar las fuentes utilizadas.
- Crear y refinar documentos, presentaciones, hojas de cálculo y comunicaciones con Copilot.
- Mantener coherencia entre Word, PowerPoint, Excel, Outlook y Teams.
- Diferenciar hechos, información pendiente, contexto público y propuestas de trabajo.
- Revisar críticamente el contenido generado por IA antes de utilizarlo.

---

## Escenario de la práctica

CIBEST CAPITAL se prepara para una primera conversación con el propietario de una empresa latinoamericana de logística que está explorando la posibilidad de invertir parte de su patrimonio en Estados Unidos. El prospecto tiene experiencia limitada en inversiones internacionales y, antes de evaluar alternativas concretas, quiere comprender mejor el mercado, el proceso y los factores que debería considerar. En esta etapa aún no se dispone de información financiera detallada ni de datos suficientes para definir sus necesidades de inversión, por lo que el trabajo inicial consiste en preparar adecuadamente la conversación, identificar la información que será necesario conocer y organizar los elementos que permitan dar continuidad al proceso.

---

## Prerrequisitos

### Conocimientos previos

- Manejo básico de Word, PowerPoint, Excel, Outlook y Teams.
- Concepto general de qué es Microsoft Copilot.
- Capacidad para copiar, pegar, revisar y editar contenido.

### Acceso requerido

Debes utilizar la misma cuenta organizacional durante toda la práctica y contar con:

- Microsoft Copilot Chat.
- Copilot en Word.
- Copilot en PowerPoint.
- Copilot en Excel.
- Copilot en Outlook.
- Copilot en Teams.
- OneDrive para guardar los productos generados.

> Las funciones visibles de Copilot pueden variar según la versión de la aplicación, la licencia y las políticas de la organización. La guía describe la acción que debes realizar.

---

## Preparación del entorno

La preparación se realiza **antes de iniciar el cronómetro de los 143 minutos**.

1. Inicia sesión con tu cuenta organizacional de Microsoft 365.
2. Comprueba que Copilot está disponible en Word, PowerPoint, Excel, Outlook y Teams.
3. Abre OneDrive.
4. Crea la carpeta:

```text
LAB_AI3025
```

5. Dentro de la práctica crearás estos archivos:

```text
LAB_AI3025/
├── 01_Ficha_preparacion_prospecto.docx
├── 02_Material_introductorio_prospecto.pptx
└── 03_Matriz_necesidades_prospecto.xlsx
```

Los correos se conservarán como **borradores** en Outlook y la agenda se preparará en Teams.

### Configuración recomendada de Copilot Chat

- Para las fases 1 y 2 no necesitas información web. Si tu interfaz permite desactivar la búsqueda web, puedes mantenerla desactivada.
- Para la fase 3, activa **Búsqueda web**.
- Si aparece el control **Work IQ**, puedes dejarlo desactivado durante la investigación pública para evitar mezclar el escenario con información organizacional no necesaria.
- Cuando Copilot utilice la web, revisa el botón o sección **Fuentes** de la respuesta.

---

# Desarrollo de la práctica

---

## Fase 1 — Comparar un prompt general con uno contextualizado

**Tiempo:** 15 min  
**Aplicación:** Microsoft Copilot Chat  
**Objetivo:** comprobar cómo mejora una respuesta cuando el prompt incluye contexto, objetivo, restricciones y formato.

### Paso 1. Enviar un prompt general — 4 min

Abre un chat nuevo y escribe:

> **PROMPT 1 — GENERAL**

```text
Ayúdame a preparar una primera reunión con un prospecto interesado en invertir en Estados Unidos.
```

Espera la respuesta y léela completa.

Identifica rápidamente:

- ¿Es demasiado general?
- ¿Copilot supone datos que no proporcionaste?
- ¿Habla de productos o recomendaciones demasiado pronto?
- ¿Explica qué información necesitarías obtener del prospecto?

No corrijas todavía la respuesta.

### Paso 2. Enviar un prompt contextualizado — 7 min

Para comparar de forma limpia, abre **un chat nuevo**.

> **PROMPT 2 — CONTEXTUALIZADO**

```text
Actúa como apoyo para un ejecutivo de CIBEST CAPITAL que prepara una primera conversación de descubrimiento.

Escenario disponible:
- El prospecto ficticio es propietario de una empresa latinoamericana de logística.
- Reside en Latinoamérica.
- Tiene experiencia limitada con inversiones internacionales.
- Quiere comprender el mercado y el proceso antes de evaluar invertir parte de su patrimonio en Estados Unidos.
- No ha proporcionado documentación ni información financiera detallada.

Objetivo:
Preparar la conversación inicial. No recomendar productos ni inversiones.

Necesito que organices la respuesta en cuatro bloques:
1. Información que sí conocemos.
2. Información que todavía debemos confirmar.
3. Temas que deberíamos explorar en la primera conversación.
4. Supuestos que debemos evitar.

No inventes nombre, país específico, ingresos, patrimonio, monto de inversión, horizonte, necesidades de liquidez, tolerancia al riesgo, preferencias ni respuestas del prospecto.
```

Revisa la respuesta. Si aparece algún dato inventado, elimínalo con este prompt:

> **PROMPT 3 — CONTROL DE SUPUESTOS**

```text
Revisa tu respuesta anterior y elimina cualquier dato del prospecto que no aparezca explícitamente en el escenario.

Todo dato no proporcionado debe quedar como "Pendiente de confirmar".
No completes los vacíos con estimaciones ni perfiles supuestos.
```

### Paso 3. Comparar — 4 min

Responde mentalmente o toma una nota breve:

- ¿Qué mejoró al incluir contexto?
- ¿Qué supuestos desaparecieron?
- ¿La segunda respuesta es más útil para preparar la reunión?

**Criterio de finalización:** tienes una lista clara de información conocida, pendiente y supuestos que no deben hacerse.

---

## Fase 2 — Construir preguntas de descubrimiento

**Tiempo:** 15 min  
**Aplicación:** Microsoft Copilot Chat  
**Objetivo:** identificar qué preguntas permitirían conocer mejor al prospecto sin inventar sus respuestas.

### Paso 1. Generar las preguntas — 7 min

Continúa desde la respuesta contextualizada de la fase anterior.

> **PROMPT 4 — PREGUNTAS DE DESCUBRIMIENTO**

```text
A partir únicamente del escenario validado, genera 12 preguntas de descubrimiento para una primera conversación con el prospecto.

Organízalas en seis categorías, con dos preguntas por categoría:
1. Objetivos.
2. Horizonte.
3. Experiencia previa.
4. Necesidades de liquidez.
5. Tolerancia al riesgo.
6. Expectativas.

Requisitos:
- Preguntas abiertas y fáciles de entender.
- Lenguaje adecuado para una persona con experiencia limitada en inversiones internacionales.
- No responder en nombre del prospecto.
- No asignar un perfil de riesgo.
- No solicitar contraseñas, números de cuenta ni datos sensibles.
- No recomendar productos.

Para cada pregunta explica en una frase qué información ayuda a comprender.
```

### Paso 2. Seleccionar las preguntas prioritarias — 5 min

> **PROMPT 5 — PRIORIZAR**

```text
De las 12 preguntas anteriores, selecciona seis preguntas prioritarias para una primera conversación breve: una por cada categoría.

Ordénalas de manera natural para una conversación.
Conserva las otras seis como preguntas de profundización.

No transformes ninguna pregunta en una respuesta ni inventes información del prospecto.
```

### Paso 3. Auditar las preguntas — 3 min

> **PROMPT 6 — AUDITORÍA**

```text
Revisa las 12 preguntas.

Identifica si alguna presupone ingresos, patrimonio, país, residencia fiscal, monto disponible, horizonte, liquidez, tolerancia al riesgo o preferencia de inversión.

Si alguna lo hace, reformúlala para que sea neutral.
Devuelve la lista final con las seis prioritarias claramente marcadas.
```

**Criterio de finalización:** existen 12 preguntas en seis categorías y ninguna contiene una respuesta inventada.

---

## Fase 3 — Investigar contexto público del sector logístico

**Tiempo:** 18 min  
**Aplicación:** Microsoft Copilot Chat con Búsqueda web  
**Objetivo:** obtener contexto reciente del sector sin atribuir automáticamente las tendencias a la empresa del prospecto.

### Paso 1. Activar búsqueda web — 2 min

En Copilot Chat:

1. Asegúrate de que **Búsqueda web** esté activada.
2. Si aparece **Work IQ**, puedes desactivarlo para esta fase, ya que la investigación utilizará información pública.
3. Abre un chat nuevo.

### Paso 2. Investigar — 7 min

> **PROMPT 7 — INVESTIGACIÓN DEL SECTOR**

```text
Investiga en la web información pública reciente del sector logístico en Latinoamérica que pueda ser útil para preparar una primera conversación con un empresario del sector.

Busca información publicada o actualizada durante los últimos 12 meses sobre:
- tendencias del sector;
- factores económicos relevantes;
- digitalización o cambios operativos;
- comercio, cadenas de suministro o nearshoring cuando sean pertinentes.

Presenta máximo cuatro hallazgos.
Para cada hallazgo incluye:
1. Hallazgo.
2. Alcance geográfico.
3. Fecha de la fuente.
4. Fuente y enlace.
5. Por qué podría ser útil como contexto para una conversación.
6. Una pregunta que permita comprobar si ese tema realmente afecta al prospecto.

No conocemos el país específico, tamaño, ingresos ni tipo de operación logística de la empresa.
No afirmes que una tendencia regional afecta directamente a su empresa.
No realices recomendaciones de inversión.
Prioriza fuentes originales, organismos públicos, organismos internacionales o entidades sectoriales identificables.
```

### Paso 3. Verificar dos fuentes — 5 min

Abre al menos **dos fuentes** de la respuesta.

Comprueba:

- que el enlace abre;
- quién publica la información;
- fecha de publicación;
- periodo al que se refiere el dato;
- que el texto realmente sustente el hallazgo.

Después escribe:

> **PROMPT 8 — VALIDAR FUENTES**

```text
He revisado manualmente dos de las fuentes de tu respuesta.

Reorganiza los hallazgos distinguiendo claramente:
- hechos publicados por la fuente;
- interpretación útil para preparar la conversación;
- preguntas que deberíamos hacer al prospecto.

Retira cualquier afirmación que no pueda sostenerse con una fuente identificable.
No conviertas tendencias del sector en hechos sobre la empresa del prospecto.
```

### Paso 4. Preparar el resumen que pasará a Word — 4 min

> **PROMPT 9 — CONSOLIDAR**

```text
Prepara un resumen para una ficha interna de preparación.

Incluye únicamente:
- información conocida del prospecto;
- información pendiente;
- las 12 preguntas de descubrimiento, destacando las seis prioritarias;
- hasta tres hallazgos sectoriales verificados, con fecha y fuente;
- temas que podrían abordarse en la conversación;
- supuestos que debemos evitar.

No agregues información nueva.
No redactes recomendaciones de inversión.
Distingue siempre entre hechos del prospecto y contexto público del sector.
```

Copia esta respuesta. La utilizarás en Word.

**Criterio de finalización:** tienes un resumen con máximo tres hallazgos sectoriales verificados y sus fuentes.

---

## Fase 4 — Crear la ficha de preparación en Word

**Tiempo:** 18 min  
**Aplicación:** Word con Copilot  
**Archivo:** `01_Ficha_preparacion_prospecto.docx`  
**Objetivo:** consolidar la preparación de la reunión en un documento interno claro.

### Paso 1. Crear el documento — 3 min

1. Abre Word.
2. Crea un documento en blanco.
3. Guárdalo en `LAB_AI3025` con el nombre:

```text
01_Ficha_preparacion_prospecto.docx
```

4. Abre Copilot dentro de Word.

### Paso 2. Generar la ficha — 7 min

Pega el siguiente prompt y, debajo, pega el resumen de la fase 3.

> **PROMPT 10 — FICHA DE PREPARACIÓN**

```text
Crea una ficha interna de preparación para la primera conversación con el prospecto ficticio de CIBEST CAPITAL.

Usa exclusivamente el contenido que pegaré debajo.

Estructura el documento con estas secciones:
1. Propósito de la conversación.
2. Información conocida.
3. Información por confirmar.
4. Contexto público relevante del sector.
5. Preguntas de descubrimiento por categoría.
6. Seis preguntas prioritarias.
7. Temas que podrían abordarse.
8. Aspectos que no debemos asumir.

Requisitos:
- Documento breve y fácil de consultar.
- Mantén las fechas y enlaces de las fuentes sectoriales.
- Distingue contexto público de hechos del prospecto.
- No inventes nombre, país, ingresos, patrimonio, perfil, preferencias ni respuestas.
- No recomiendes productos ni inversiones.
- Identifica el documento como material de simulación de capacitación.

CONTENIDO VALIDADO:
[PEGA AQUÍ EL RESUMEN DE LA FASE 3]
```

Revisa la propuesta antes de conservarla en el documento.

### Paso 3. Auditar la ficha — 5 min

> **PROMPT 11 — REVISIÓN DE LA FICHA**

```text
Revisa este documento como material interno de preparación.

Busca especialmente:
- datos del prospecto que no estén respaldados por el escenario;
- tendencias del sector presentadas como si fueran hechos de su empresa;
- respuestas inventadas a las preguntas de descubrimiento;
- recomendaciones de inversión;
- repeticiones o secciones difíciles de consultar.

Corrige los problemas encontrados.
Todo dato no confirmado debe quedar claramente marcado como "Pendiente de confirmar".
```

### Paso 4. Crear un resumen ejecutivo — 3 min

> **PROMPT 12 — RESUMEN EJECUTIVO**

```text
Agrega al inicio del documento un resumen ejecutivo de máximo 120 palabras.

Debe indicar:
- qué conocemos;
- qué todavía falta confirmar;
- cuál es el propósito de la primera conversación.

No agregues hechos nuevos.
```

Guarda el documento.

**Criterio de finalización:** la ficha distingue claramente información conocida, pendiente, contexto público y preguntas.

---

## Fase 5 — Crear material introductorio en PowerPoint

**Tiempo:** 20 min  
**Aplicación:** PowerPoint con Copilot  
**Archivo:** `02_Material_introductorio_prospecto.pptx`  
**Objetivo:** crear un material breve para explicar cómo se desarrollaría la conversación inicial, sin recomendar productos.

### Paso 1. Crear la presentación — 3 min

1. Abre PowerPoint.
2. Crea una presentación en blanco.
3. Guárdala en `LAB_AI3025` como:

```text
02_Material_introductorio_prospecto.pptx
```

### Paso 2. Crear la presentación desde la ficha — 9 min

Abre Copilot en PowerPoint.

Cuando esté disponible, utiliza **Crear presentación desde archivo / Referenciar archivo** y selecciona:

```text
01_Ficha_preparacion_prospecto.docx
```

Luego utiliza este prompt:

> **PROMPT 13 — PRESENTACIÓN**

```text
Crea una presentación introductoria de cinco diapositivas para el prospecto.

La presentación no debe recomendar inversiones ni productos.

Estructura:
1. Propósito de la primera conversación.
2. Cómo se desarrollará el proceso de descubrimiento.
3. Información que normalmente necesita comprender un asesor antes de evaluar alternativas: objetivos, horizonte, liquidez, experiencia, tolerancia al riesgo y expectativas.
4. Por qué esa información es importante antes de evaluar opciones.
5. Siguientes pasos posibles para continuar el análisis, sujetos a confirmación.

Audiencia:
Persona con experiencia limitada en inversiones internacionales.

Estilo:
- lenguaje sencillo;
- máximo tres ideas principales por diapositiva;
- evita tecnicismos o explícalos con palabras simples;
- no incluyas montos, rendimientos, productos, porcentajes de asignación ni perfil de riesgo;
- no conviertas tendencias del sector en datos de la empresa;
- identifica el contenido como simulación de capacitación.
```

Si tu experiencia de PowerPoint no permite referenciar el Word directamente, copia el resumen ejecutivo y las secciones principales de la ficha y pégalas después del prompt.

Espera a que PowerPoint termine de generar las diapositivas.

### Paso 3. Simplificar el lenguaje — 5 min

> **PROMPT 14 — SIMPLIFICAR**

```text
Revisa las cinco diapositivas.

Simplifica cualquier término financiero que una persona con experiencia limitada en inversiones internacionales pueda no entender.

Reduce el texto cuando sea necesario.
Mantén una idea central por diapositiva.
No agregues productos, recomendaciones, cifras ni promesas de resultados.
```

### Paso 4. Revisión visual — 3 min

Comprueba:

- exactamente cinco diapositivas;
- títulos claros;
- texto legible;
- sin cajas cortadas;
- sin gráficos que sugieran rendimientos o cifras inexistentes;
- sin recomendaciones de inversión.

Guarda la presentación.

**Criterio de finalización:** existen cinco diapositivas editables que explican el proceso inicial con lenguaje sencillo.

---

## Fase 6 — Construir la matriz de necesidades en Excel

**Tiempo:** 20 min  
**Aplicación:** Excel con Copilot  
**Archivo:** `03_Matriz_necesidades_prospecto.xlsx`  
**Objetivo:** visualizar rápidamente qué información se conoce y cuál debe confirmarse.

### Paso 1. Crear el libro — 3 min

1. Abre Excel.
2. Crea un libro en blanco.
3. Guárdalo en `LAB_AI3025` como:

```text
03_Matriz_necesidades_prospecto.xlsx
```

4. Cambia el nombre de la primera hoja a:

```text
Necesidades
```

5. Abre Copilot en Excel. Utiliza el modo que permita editar el libro cuando esté disponible.

### Paso 2. Crear la tabla — 8 min

> **PROMPT 15 — MATRIZ DE NECESIDADES**

```text
Crea en la hoja "Necesidades" una tabla de Excel llamada NecesidadesProspecto.

Debe contener una fila por cada uno de estos aspectos:
1. Contexto empresarial.
2. Objetivo.
3. Horizonte.
4. Liquidez.
5. Experiencia internacional.
6. Tolerancia al riesgo.
7. Expectativas.
8. Ubicación o residencia.
9. Recursos que consideraría invertir.

Columnas:
- Aspecto
- Informacion_conocida
- Estado
- Pregunta_pendiente
- Prioridad_de_conversacion
- Fuente

Estados permitidos:
- Confirmado
- Parcial
- Pendiente

Usa únicamente estos hechos:
- Es propietario de una empresa latinoamericana de logística.
- Reside en Latinoamérica.
- Tiene experiencia limitada con inversiones internacionales.
- Quiere comprender el mercado y el proceso antes de evaluar invertir parte de su patrimonio en Estados Unidos.
- No ha proporcionado documentación ni información financiera detallada.

Reglas:
- Escribe "No aportado" cuando el escenario no proporciona el dato.
- No inventes montos, ingresos, país, horizonte, liquidez, tolerancia al riesgo ni preferencias.
- "Experiencia limitada" no define tolerancia al riesgo.
- "Latinoamérica" no identifica un país ni residencia fiscal.
- El interés en Estados Unidos no equivale a un objetivo financiero cuantificado.
- La prioridad es una propuesta para ordenar la conversación, no una urgencia declarada por el prospecto.
```

Comprueba que la información esté en celdas editables y dentro de una tabla real de Excel.

### Paso 3. Crear una vista de pendientes — 6 min

> **PROMPT 16 — CONTROL DE PENDIENTES**

```text
Agrega a la tabla una columna llamada Requiere_confirmacion.

Crea una fórmula para que muestre:
- "Sí" cuando Estado sea Parcial o Pendiente.
- "No" cuando Estado sea Confirmado.

Aplica la fórmula a toda la tabla.

Después crea un pequeño resumen con fórmulas que muestre:
- cantidad de Confirmados;
- cantidad de Parciales;
- cantidad de Pendientes;
- total de aspectos.

No escribas conteos manuales.
No generes un puntaje de riesgo ni un perfil de inversión.
```

Verifica que:

- el total de aspectos sea **9**;
- la suma de Confirmado + Parcial + Pendiente sea **9**;
- las celdas de resumen contengan fórmulas.

Filtra temporalmente `Requiere_confirmacion = Sí` para observar la información que falta y después limpia el filtro.

### Paso 4. Auditar la tabla — 3 min

> **PROMPT 17 — AUDITORÍA DE LA MATRIZ**

```text
Audita la tabla contra los hechos del escenario.

Corrige cualquier celda que:
- invente información;
- trate un dato parcial como confirmado;
- presuponga una respuesta;
- asigne un perfil de riesgo.

Mantén los nueve aspectos.
No rellenes campos desconocidos.
```

Guarda el libro.

**Criterio de finalización:** el Excel permite ver de forma inmediata qué información está confirmada, parcial o pendiente.

---

## Fase 7 — Preparar el correo de bienvenida en Outlook

**Tiempo:** 12 min  
**Aplicación:** Outlook con Copilot  
**Objetivo:** redactar un correo previo a la primera conversación sin solicitar información sensible ni inventar datos.

En esta fase se asume únicamente que **la primera conversación ya fue acordada**. No conocemos nombre, correo, fecha ni hora.

### Paso 1. Crear el borrador — 6 min

1. Abre un correo nuevo.
2. Deja el campo **Para** vacío.
3. Abre **Borrador con Copilot / Draft with Copilot**.

> **PROMPT 18 — CORREO DE BIENVENIDA**

```text
Redacta un correo de bienvenida para una simulación de CIBEST CAPITAL.

Hechos disponibles:
- La primera conversación ya fue acordada.
- El prospecto es propietario de una empresa latinoamericana de logística.
- Reside en Latinoamérica.
- Tiene experiencia limitada con inversiones internacionales.
- Quiere comprender el mercado y el proceso antes de evaluar invertir parte de su patrimonio en Estados Unidos.

No conocemos su nombre, correo, fecha ni hora. No los inventes.

El correo debe:
- agradecer la oportunidad de conversar;
- explicar que el objetivo inicial es conocer mejor sus necesidades y explicar el proceso;
- anticipar que hablaremos de objetivos, horizonte, liquidez, experiencia, tolerancia al riesgo y expectativas;
- invitarlo a reflexionar sobre esos temas antes de la reunión;
- evitar solicitar contraseñas, números de cuenta o documentación sensible por correo.

Tono profesional, claro y cercano.
Extensión: 130 a 170 palabras.
Incluye un asunto sugerido.
No recomiendes productos ni prometas resultados.
```

Conserva el borrador generado.

### Paso 2. Refinar el mensaje — 4 min

> **PROMPT 19 — REVISAR CORREO**

```text
Revisa este correo.

Hazlo más claro y breve si es necesario.
Mantén visibles el propósito de la reunión y los temas a conversar.
No agregues fecha, hora, nombre, monto de inversión ni respuestas del prospecto.
No conviertas la invitación a reflexionar en una exigencia de entregar documentos.
```

Si Outlook ofrece **Coaching / Asesoramiento**, utilízalo para revisar tono y claridad.

### Paso 3. Guardar sin enviar — 2 min

- Usa un asunto que comience con `LAB -` para reconocerlo fácilmente.
- No agregues destinatario.
- Cierra el mensaje conservándolo en **Borradores**.

**Criterio de finalización:** existe un borrador de bienvenida y no contiene datos inventados ni solicitudes sensibles.

---

## Fase 8 — Preparar el correo de seguimiento en Outlook

**Tiempo:** 12 min  
**Aplicación:** Outlook con Copilot  
**Objetivo:** redactar un seguimiento posterior sin inventar respuestas o decisiones de inversión.

### Continuidad de la simulación

A partir de esta fase solo agregamos dos hechos:

- La primera conversación **ya ocurrió**.
- El prospecto **manifestó interés en continuar**.

No existe una minuta con respuestas detalladas. Por tanto, objetivos, horizonte, liquidez, tolerancia al riesgo, monto y preferencias continúan sin confirmar.

### Paso 1. Crear el segundo borrador — 6 min

Abre un correo nuevo y deja los destinatarios vacíos.

> **PROMPT 20 — CORREO DE SEGUIMIENTO**

```text
Redacta un correo de seguimiento para una simulación de CIBEST CAPITAL.

Hechos nuevos:
- La primera conversación con el prospecto ya ocurrió.
- El prospecto manifestó interés en continuar.

Contexto previo:
- Es propietario de una empresa latinoamericana de logística.
- Reside en Latinoamérica.
- Tiene experiencia limitada con inversiones internacionales.
- Busca comprender el proceso antes de evaluar alternativas en Estados Unidos.

No tenemos una minuta con respuestas detalladas ni decisiones de inversión.

El correo debe:
- agradecer la conversación;
- reconocer su interés en continuar;
- resumir de forma general que la conversación se centró en comprender el proceso y los temas que deberán aclararse antes de evaluar alternativas;
- mencionar como pendientes objetivos, horizonte, liquidez, experiencia, tolerancia al riesgo y expectativas;
- proponer coordinar un siguiente contacto para continuar el descubrimiento, sujeto a confirmación.

No afirmes que el prospecto confirmó cifras, preferencias, documentos, fechas o decisiones.
No recomiendes productos.
Extensión: 130 a 170 palabras.
Incluye un asunto sugerido.
```

### Paso 2. Auditar compromisos inventados — 4 min

> **PROMPT 21 — CONTROL DE ACUERDOS**

```text
Revisa el correo y busca expresiones que presenten como hechos acuerdos que no están documentados, por ejemplo:
- "según lo acordado";
- "usted indicó";
- "usted prefiere";
- "invertiremos";
- "nos reuniremos el día...";
- "nos enviará...".

Corrige cualquier afirmación de ese tipo.
Conserva como hechos únicamente que la conversación ocurrió y que el prospecto manifestó interés en continuar.
Los demás pasos deben presentarse como propuestas sujetas a confirmación.
```

### Paso 3. Guardar — 2 min

- Usa un asunto que comience con `LAB - Seguimiento`.
- Deja destinatarios vacíos.
- Guarda en **Borradores**.

**Criterio de finalización:** el seguimiento separa hechos conocidos de propuestas para continuar.

---

## Fase 9 — Preparar la reunión interna en Teams y validar el conjunto

**Tiempo:** 13 min  
**Aplicación:** Teams con Copilot  
**Objetivo:** preparar una agenda interna previa al siguiente contacto con el prospecto.

### Paso 1. Generar la agenda — 6 min

En Teams abre Copilot Chat. Crea una conversación nueva.

> **PROMPT 22 — AGENDA INTERNA**

```text
Prepara una agenda de 15 minutos para una reunión interna ficticia de CIBEST CAPITAL antes del siguiente contacto con el prospecto.

Contexto:
- La primera conversación ya ocurrió.
- El prospecto manifestó interés en continuar.
- No se proporcionaron respuestas detalladas a objetivos, horizonte, liquidez, tolerancia al riesgo, monto ni preferencias.
- Seguimos trabajando con un escenario ficticio y sin recomendaciones de inversión.

La agenda debe incluir:
1. Objetivo de la reunión interna.
2. Información que ya conocemos.
3. Información que sigue pendiente.
4. Preguntas que deben resolverse antes de evaluar alternativas.
5. Perfiles de especialistas que podría ser necesario considerar, solo como posibilidades sujetas a revisión.
6. Resultado esperado de la coordinación interna.

Distribuye los temas en bloques que sumen exactamente 15 minutos.

No inventes nombres de especialistas, participantes confirmados, requisitos legales específicos, fechas prometidas ni decisiones de inversión.
```

Revisa que los tiempos sumen 15 minutos.

### Paso 2. Auditar la agenda — 3 min

> **PROMPT 23 — AUDITORÍA DE AGENDA**

```text
Audita la agenda anterior.

Comprueba que:
- objetivos, horizonte, liquidez y tolerancia al riesgo sigan como pendientes;
- los especialistas aparezcan como perfiles que podrían considerarse y no como participantes confirmados;
- el objetivo de la reunión sea preparar el siguiente contacto y no seleccionar una inversión;
- los tiempos sumen exactamente 15 minutos.

Corrige cualquier inconsistencia.
```

### Paso 3. Crear un evento de práctica — 2 min

En **Teams > Calendario**:

1. Crea un evento de 15 minutos.
2. Título:

```text
LAB AI3025 - Coordinación interna prospecto
```

3. No agregues asistentes.
4. Pega la agenda final en la descripción.
5. Agrega al inicio:

```text
Simulación de capacitación. Sin convocatoria a terceros.
```

6. Guarda el evento.

La fecha seleccionada corresponde únicamente a tu práctica, no a un compromiso con el prospecto.

### Paso 4. Validación final del conjunto — 2 min

Verifica los siguientes resultados:

| Producto | Debe cumplir |
|---|---|
| **Word** | Conocido, pendiente y contexto público claramente separados. |
| **Preguntas** | 12 preguntas, seis categorías, seis prioritarias. |
| **Contexto sectorial** | Máximo tres hallazgos finales, con fuentes verificadas. |
| **PowerPoint** | Cinco diapositivas, lenguaje sencillo, sin productos ni recomendaciones. |
| **Excel** | Nueve aspectos, estados justificables, fórmula de confirmación y resumen. |
| **Outlook — bienvenida** | Borrador previo, sin destinatario ni datos inventados. |
| **Outlook — seguimiento** | Reunión ocurrida e interés en continuar; sin acuerdos ficticios. |
| **Teams** | Agenda interna de 15 minutos, sin asistentes externos. |

**Criterio de finalización:** todos los productos son coherentes entre sí y ninguno convierte información pendiente en un hecho.

---

# Validación y pruebas finales

Marca cada elemento antes de dar la práctica por terminada.

| # | Criterio | Estado |
|---|---|---|
| 1 | La práctica se completó dentro de los 143 minutos. | ☐ |
| 2 | No se inventó nombre, país, ingresos, patrimonio ni monto. | ☐ |
| 3 | No se asignó tolerancia al riesgo o perfil de inversión. | ☐ |
| 4 | Las preguntas de descubrimiento no incluyen respuestas inventadas. | ☐ |
| 5 | Se revisaron manualmente al menos dos fuentes web. | ☐ |
| 6 | `01_Ficha_preparacion_prospecto.docx` existe en `LAB_AI3025`. | ☐ |
| 7 | `02_Material_introductorio_prospecto.pptx` existe en `LAB_AI3025`. | ☐ |
| 8 | `03_Matriz_necesidades_prospecto.xlsx` existe en `LAB_AI3025`. | ☐ |
| 9 | El PowerPoint no contiene recomendaciones ni productos específicos. | ☐ |
| 10 | El Excel mantiene los datos desconocidos como pendientes o parciales. | ☐ |
| 11 | Los dos correos permanecen como borradores y sin destinatarios. | ☐ |
| 12 | La agenda de Teams suma 15 minutos. | ☐ |
| 13 | No se utilizaron datos reales de clientes. | ☐ |
| 14 | Todos los resultados fueron revisados por el participante antes de conservarlos. | ☐ |

---

# Solución de problemas

| Situación | Qué hacer |
|---|---|
| Copilot inventa un país, nombre, ingresos o patrimonio | Pide retirar el dato y convertirlo en `Pendiente de confirmar`. Revisa también los productos posteriores. |
| Copilot recomienda un producto o portafolio | Elimina la recomendación y recuerda que el ejercicio termina antes de evaluar alternativas específicas. |
| No aparece Búsqueda web | Revisa `Configuración > Personalización > Avanzado > Búsqueda web`. Si la organización la deshabilitó, consulta al administrador. |
| Una fuente no abre | No utilices ese hallazgo. Busca otra fuente verificable. |
| La fuente abre pero no respalda el dato | Retira el dato o vuelve a formular la búsqueda. |
| Word no conoce el contenido de Copilot Chat | Pega manualmente el resumen validado de la fase 3 en el prompt de Word. |
| PowerPoint no permite usar el Word como referencia | Pega el resumen ejecutivo y las secciones necesarias de la ficha directamente en el prompt. |
| PowerPoint crea solo un esquema | Pide explícitamente que cree las diapositivas editables y verifica las miniaturas. |
| Excel responde solo en el chat | Pide a Copilot que aplique los cambios al libro; comprueba que existan celdas y tabla real. |
| La fórmula de Excel falla | Pide a Copilot corregirla según la configuración regional del libro. No reemplaces la fórmula por valores escritos manualmente. |
| Outlook no muestra Draft with Copilot | Comprueba que la cuenta y la licencia son correctas y que el mensaje se redacta en HTML. |
| El seguimiento inventa respuestas | Conserva únicamente dos hechos nuevos: la reunión ocurrió y existe interés en continuar. |
| Teams propone especialistas concretos como confirmados | Cambia los nombres por funciones o perfiles y déjalos como posibilidades por evaluar. |

---

# Limpieza y conservación

### Conserva

- `01_Ficha_preparacion_prospecto.docx`
- `02_Material_introductorio_prospecto.pptx`
- `03_Matriz_necesidades_prospecto.xlsx`
- Los dos correos como borradores si se usarán como evidencia de la práctica.
- La agenda interna de Teams si se usará como evidencia.

### No hagas

- No envíes los correos.
- No invites personas reales a la reunión de práctica.
- No publiques en GitHub enlaces privados de OneDrive, firmas de correo o información de la organización.
- No sustituyas el escenario ficticio con datos de un cliente real.

---

# Resumen de la práctica

La práctica termina con un conjunto coherente de materiales que permite a un ejecutivo prepararse para una primera conversación sin adelantarse a decisiones de inversión.

El flujo completo es:

```text
Prompt general
   ↓
Prompt contextualizado
   ↓
Preguntas de descubrimiento
   ↓
Investigación pública del sector
   ↓
Ficha de preparación en Word
   ↓
Material introductorio en PowerPoint
   ↓
Matriz de necesidades en Excel
   ↓
Correo de bienvenida
   ↓
Correo de seguimiento
   ↓
Agenda interna en Teams
```

El criterio más importante durante todo el ejercicio es simple:

> **Copilot ayuda a organizar y redactar; el participante debe verificar, decidir y evitar que la IA convierta información desconocida en hechos.**

---

# Referencias oficiales de Microsoft

Estas referencias documentan las funciones utilizadas en la práctica. Las interfaces pueden cambiar con el tiempo.

- Microsoft Support — Draft and add content with Copilot in Word:  
  https://support.microsoft.com/es-es/word/copilot/draft-and-add-content-with-copilot-in-word

- Microsoft Support — Create a new presentation with Copilot in PowerPoint:  
  https://support.microsoft.com/en-us/powerpoint/copilot/create-a-new-presentation-with-copilot-in-powerpoint

- Microsoft Support — Add a slide from a file with Copilot in PowerPoint:  
  https://support.microsoft.com/es-es/powerpoint/copilot/add-a-slide-from-a-file-with-copilot-in-powerpoint

- Microsoft Support — Get started with Copilot in Excel:  
  https://support.microsoft.com/en-us/excel/copilot/get-started-with-copilot-in-excel

- Microsoft Support — Draft an email message with Copilot in Outlook:  
  https://support.microsoft.com/en-us/outlook/copilot-pages/draft-an-email-message-with-copilot-in-outlook

- Microsoft Support — Get email coaching with Copilot in Outlook:  
  https://support.microsoft.com/en-us/outlook/copilot-pages/get-email-coaching-with-copilot-in-outlook

- Microsoft Support — Start a conversation with Microsoft Copilot Chat in Teams:  
  https://support.microsoft.com/en-us/teams/copilot/start-a-conversation-with-microsoft-365-copilot-chat-in-teams

- Microsoft Support — Schedule a meeting in Microsoft Teams:  
  https://support.microsoft.com/en-us/teams/meetings/schedule-a-meeting-in-microsoft-teams

- Microsoft Support — How web search works in Microsoft Copilot Chat and agents:  
  https://support.microsoft.com/es-es/microsoft-365-copilot/how-web-search-works-in-microsoft-365-copilot-chat-and-agents

- Microsoft Support — What information does Copilot use to answer my prompt?:  
  https://support.microsoft.com/en-us/microsoft-365-copilot/what-information-does-copilot-use-to-answer-my-prompt