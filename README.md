# Environmental Impact Analyst – Data Centers

**Open, bilingual (English/Spanish) methodology for investigating the environmental impacts of data centers, cloud and AI infrastructure.**

Developed by **Miguel Ángel Dobrich and Gabriel Farías — Amenaza Roboto**
Published: **August 2026**

**Languages:** English · Español

> **Central principle:** No important claim without verifiable evidence.
> The model is not the source: the document is the source.

---

## English

### About the project

**Environmental Impact Analyst – Data Centers** is an open and reproducible methodology for building a document-based research assistant to investigate the environmental and climate impacts of data centers, cloud infrastructure and AI infrastructure.

The project is designed for **journalists, researchers, civil-society organizations and citizens** working with large environmental records such as Environmental Impact Assessments (EIA/ESIA), permits, technical annexes, water studies, air-quality models, acoustic studies, monitoring plans and regulatory files.

Its purpose is **not** to automatically decide whether a project is environmentally “good” or “bad.” Its purpose is to make documentary evidence easier to **find, trace, compare, question and verify**.

### Read the guide

The complete guide is bilingual and contains **22 sections in Spanish and 22 sections in English**:

**[Citizen Guide to Building a GPT for Data Center Environmental Investigations / Guía ciudadana para crear un GPT que investigue el impacto ambiental de centros de datos](./Amenaza_Roboto_Guia_ciudadana_GPT_centros_de_datos.pdf)**

---

## What can it investigate?

The methodology is designed to investigate, when documentary evidence is available:

* **Water and cooling:** withdrawals, daily and annual consumption, water sources, groundwater, aquifers, reclaimed water, cooling systems, evaporation, blowdown, discharge and WUE.
* **Energy and compute:** total facility load, IT load, electricity demand, PUE, UPS systems, substations, transformers, redundancy, grid connection and grid stress.
* **Backup power:** generator count and capacity, fuel use, diesel storage, testing hours, maximum operating scenarios and emissions.
* **Air pollution:** NOx, particulate matter, SO₂, generator emissions, construction emissions and refrigerants.
* **Climate change:** direct and indirect emissions, fuels, refrigerants, identifiable Scope 1/2/3 equivalents and reduction targets.
* **Climate risks:** drought, water scarcity, extreme heat, flooding, wildfire and infrastructure vulnerability.
* **Land and biodiversity:** land occupation, habitat loss or fragmentation, protected species, ecological corridors and vegetation.
* **Communities:** noise, traffic, construction impacts, pollution, proximity to homes, cultural heritage, Indigenous peoples where applicable, and distribution of risks and benefits.
* **Cumulative impacts:** interactions with other data centers, industries, urban development, energy infrastructure and existing or planned water withdrawals.
* **Monitoring and commitments:** what will be measured, how often, against which thresholds, by whom, and what happens if limits are exceeded.

---

## Methodological principles

### Evidence traceability

Every important number, quotation or factual claim extracted from the source documents should be traceable to the most precise available location: document, section, page, table, figure or annex.

Never invent page numbers.

### Source boundary

The documents supplied for a specific investigation are the primary evidentiary corpus. Missing evidence should not be silently replaced with general knowledge or unrelated external sources.

### Investigation isolation

Treat each new project as a separate evidentiary corpus.

**New case = new documentary corpus.**

Do not automatically mix documents, figures, conclusions or notes from different projects.

### Evidence levels

| Level                     | Meaning                                                                                       |
| ------------------------- | --------------------------------------------------------------------------------------------- |
| **VERIFIED**              | Directly stated or quantitatively supported by the supplied sources.                          |
| **CALCULATED**            | Derived mathematically from verified values. Inputs, formula and assumptions must be shown.   |
| **INFERENCE**             | A reasonable interpretation of verified evidence that is not explicitly stated by the source. |
| **INSUFFICIENT EVIDENCE** | The supplied documents do not allow the claim to be established.                              |

An inference should never be presented as a verified fact.

### Human verification

AI can help navigate large documentary records, connect evidence scattered across multiple files and formulate questions for further investigation.

It does **not** turn an EIA into truth and does **not** replace scientists, engineers, environmental specialists, affected communities, regulators, journalists or lawyers.

Important findings remain provisional until a human checks them against the original documents.

---

## Recommended workflow

### 1. Build the documentary corpus

Before asking whether a data center has a major environmental impact, collect the most complete record possible.

Priority documents may include:

* EIA/ESIA;
* technical project description;
* annexes;
* water and hydrogeological studies;
* air-quality models;
* acoustic studies;
* biodiversity assessments;
* Environmental Management Plans;
* monitoring plans;
* environmental permits;
* water withdrawal or discharge authorizations;
* emissions permits;
* regulator decisions;
* subsequent project modifications.

### 2. Configure the research assistant

The guide recommends a **least-privilege approach** for document-based investigations:

* web search off by default;
* apps disabled;
* actions/APIs disabled;
* image generation not required;
* data analysis/code tools optional when needed for calculations, unit conversions, tables or charts.

Any calculation must preserve the traceability of the original values.

### 3. Use the master instructions

Section 7 of the guide contains the complete master instructions for configuring the Custom GPT, including:

* source boundaries;
* zero-trust principles;
* prompt-injection defense;
* citation discipline;
* evidence levels;
* calculation rules;
* investigative areas;
* uncertainty handling;
* monitoring analysis;
* default output structure.

### 4. Start by mapping the documents

Before extracting conclusions:

1. inventory every document;
2. identify its date, author or institution and role in the record;
3. locate the relevant sections for water, energy, generators, air emissions, refrigerants, noise, biodiversity, climate risks and monitoring;
4. only then begin substantive analysis in **VERIFY** mode.

### 5. Investigate in layers

The guide proposes moving through five layers:

1. **What exists?** — identify the infrastructure.
2. **How much?** — find quantities and magnitudes.
3. **What impact is predicted?** — identify modeled or expected impacts.
4. **How was that conclusion reached?** — inspect assumptions, models and methodology.
5. **What is missing?** — identify the evidence needed to assess unanswered questions.

### 6. Verify the result

For every important number, ask for:

* the source document;
* exact page, table or section;
* original unit;
* formula, if calculated;
* assumptions;
* whether the result is VERIFIED, CALCULATED, INFERENCE or INSUFFICIENT EVIDENCE.

Then open the original document and check it manually.

---

## Transparency

When this methodology is used in journalism, academic research, advocacy or civic participation, consider making public:

* which documents were analyzed;
* which versions were used;
* which prompts were used;
* which calculations the AI performed;
* which claims were manually checked;
* what information remained unavailable;
* what limitations affected the investigation.

**AI should make an investigation more auditable, not less.**

---

## Suggested citation

Dobrich, Miguel Ángel, & Farías, Gabriel. (2026). *Guía ciudadana para crear un GPT que investigue el impacto ambiental de centros de datos / Citizen Guide to Building a GPT for Data Center Environmental Investigations*. Amenaza Roboto.

---

# Español

## Sobre el proyecto

**Environmental Impact Analyst – Data Centers** es una metodología abierta y reproducible para construir un asistente de investigación documental orientado a investigar los impactos ambientales y climáticos de centros de datos, infraestructura de nube e infraestructura asociada a inteligencia artificial.

Está pensada para **periodistas, investigadores, organizaciones de la sociedad civil y ciudadanía** que trabajan con expedientes ambientales extensos: Evaluaciones de Impacto Ambiental (EIA/ESIA), permisos, anexos técnicos, estudios de agua, modelos de calidad del aire, estudios acústicos, planes de monitoreo y expedientes regulatorios.

Su objetivo **no** es decidir automáticamente si un proyecto es ambientalmente “bueno” o “malo”. Su función es hacer que la evidencia documental sea más fácil de **encontrar, rastrear, comparar, cuestionar y verificar**.

## Leer la guía

La guía completa es bilingüe y contiene **22 secciones en español y 22 en inglés**:

**[Guía ciudadana para crear un GPT que investigue el impacto ambiental de centros de datos / Citizen Guide to Building a GPT for Data Center Environmental Investigations](./Amenaza_Roboto_Guia_ciudadana_GPT_centros_de_datos.pdf)**

---

## ¿Qué puede investigar?

Cuando existe evidencia documental, la metodología permite analizar:

* **Agua y refrigeración:** extracción, consumo diario y anual, origen del agua, acuíferos, agua regenerada, sistemas de enfriamiento, evaporación, purgas, descargas y WUE.
* **Energía y cómputo:** carga total, carga informática, demanda eléctrica, PUE, UPS, subestaciones, transformadores, redundancia, conexión a la red y presión sobre el sistema eléctrico.
* **Energía de respaldo:** cantidad y potencia de generadores, combustibles, almacenamiento de diésel, horas de prueba, escenarios máximos de funcionamiento y emisiones.
* **Contaminación atmosférica:** NOx, material particulado, SO₂, emisiones de generadores, emisiones durante la construcción y refrigerantes.
* **Cambio climático:** emisiones directas e indirectas, combustibles, refrigerantes, equivalentes a Scope 1/2/3 cuando puedan identificarse y metas de reducción.
* **Riesgos climáticos:** sequía, escasez de agua, calor extremo, inundaciones, incendios y vulnerabilidad de la infraestructura.
* **Territorio y biodiversidad:** ocupación del suelo, pérdida o fragmentación de hábitat, especies protegidas, corredores ecológicos y vegetación.
* **Comunidad:** ruido, tránsito, obras, contaminación, cercanía a viviendas, patrimonio cultural, pueblos indígenas cuando corresponda y distribución de riesgos y beneficios.
* **Impactos acumulativos:** interacción con otros centros de datos, industrias, urbanizaciones, infraestructura energética y extracciones de agua existentes o proyectadas.
* **Monitoreo y compromisos:** qué se medirá, con qué frecuencia, contra qué umbrales, quién será responsable y qué ocurrirá si se superan los límites.

---

## Principios metodológicos

### Trazabilidad de la evidencia

Todo número, cita o afirmación factual importante extraída de los documentos debe poder rastrearse hasta la ubicación más precisa disponible: documento, sección, página, tabla, figura o anexo.

Nunca se deben inventar números de página.

### Límite de fuentes

Los documentos aportados para una investigación constituyen el corpus de evidencia principal. La falta de información no debe completarse silenciosamente con conocimiento general o fuentes externas no autorizadas.

### Aislamiento entre investigaciones

Cada proyecto debe tratarse como un corpus documental independiente.

**Caso nuevo = corpus documental nuevo.**

No deben mezclarse automáticamente documentos, cifras, conclusiones o notas de proyectos diferentes.

### Niveles de evidencia

| Nivel                     | Significado                                                                                                   |
| ------------------------- | ------------------------------------------------------------------------------------------------------------- |
| **VERIFIED**              | Está expresado directamente o respaldado cuantitativamente por las fuentes proporcionadas.                    |
| **CALCULATED**            | Se deriva matemáticamente de valores verificados. Deben mostrarse entradas, fórmula y supuestos.              |
| **INFERENCE**             | Es una interpretación razonable de evidencia verificada, pero no está expresada explícitamente por la fuente. |
| **INSUFFICIENT EVIDENCE** | Los documentos proporcionados no permiten establecer la afirmación.                                           |

Una inferencia nunca debe presentarse como un hecho verificado.

### Verificación humana

La IA puede ayudar a navegar grandes expedientes, conectar evidencia dispersa entre múltiples archivos y formular preguntas que luego puedan verificarse.

No convierte automáticamente una EIA en verdad ni sustituye a científicos, ingenieros, especialistas ambientales, comunidades afectadas, reguladores, periodistas o abogados.

Los hallazgos importantes son provisionales hasta que una persona los verifique contra los documentos originales.

---

## Flujo de trabajo recomendado

### 1. Construir el corpus documental

Antes de preguntar si un centro de datos genera un impacto ambiental importante, reúne el expediente más completo posible.

Entre los documentos prioritarios se encuentran:

* EIA/ESIA;
* descripción técnica del proyecto;
* anexos;
* estudios de agua e hidrogeología;
* modelos de calidad del aire;
* estudios acústicos;
* evaluaciones de biodiversidad;
* Plan de Gestión Ambiental;
* plan de monitoreo;
* permisos ambientales;
* autorizaciones de extracción o descarga de agua;
* permisos de emisiones;
* resoluciones del regulador;
* modificaciones posteriores del proyecto.

### 2. Configurar el asistente

La guía recomienda un enfoque de **mínimo privilegio** para investigaciones basadas en documentos:

* búsqueda web desactivada por defecto;
* apps desactivadas;
* actions/APIs desactivadas;
* generación de imágenes no necesaria;
* herramientas de análisis de datos/código opcionales para cálculos, conversiones de unidades, tablas o gráficos.

Todo cálculo debe conservar la trazabilidad de los valores originales.

### 3. Usar las instrucciones maestras

La sección 7 de la guía contiene las instrucciones completas para configurar el Custom GPT, incluyendo:

* límites de fuentes;
* principios zero-trust;
* defensa contra prompt injection;
* disciplina de citas;
* niveles de evidencia;
* reglas para cálculos;
* áreas de investigación;
* tratamiento de incertidumbre;
* análisis de monitoreo;
* estructura de respuesta por defecto.

### 4. Comenzar mapeando los documentos

Antes de extraer conclusiones:

1. inventaría todos los documentos;
2. identifica fecha, autor u organismo y función dentro del expediente;
3. localiza las secciones sobre agua, energía, generadores, emisiones atmosféricas, refrigerantes, ruido, biodiversidad, riesgos climáticos y monitoreo;
4. recién entonces comienza el análisis sustantivo en modo **VERIFY**.

### 5. Investigar por capas

La guía propone avanzar en cinco capas:

1. **¿Qué existe?** — identificar la infraestructura.
2. **¿Cuánto?** — encontrar cantidades y magnitudes.
3. **¿Qué impacto se pronostica?** — identificar impactos modelados o esperados.
4. **¿Cómo se llegó a esa conclusión?** — revisar supuestos, modelos y metodología.
5. **¿Qué falta?** — identificar la evidencia necesaria para responder preguntas todavía abiertas.

### 6. Verificar el resultado

Para cada cifra importante, pide:

* documento fuente;
* página, tabla o sección exacta;
* unidad original;
* fórmula, si se calculó;
* supuestos;
* clasificación como VERIFIED, CALCULATED, INFERENCE o INSUFFICIENT EVIDENCE.

Después abre el documento original y compruébalo manualmente.

---

## Transparencia metodológica

Cuando esta metodología se utilice en periodismo, investigación académica, activismo o participación ciudadana, considera publicar:

* qué documentos se analizaron;
* qué versiones se utilizaron;
* qué prompts se usaron;
* qué cálculos realizó la IA;
* qué afirmaciones se verificaron manualmente;
* qué información no estuvo disponible;
* qué limitaciones afectaron la investigación.

**La IA debe aumentar la posibilidad de auditar una investigación, no reducirla.**

---

## Cita sugerida

Dobrich, Miguel Ángel, & Farías, Gabriel. (2026). *Guía ciudadana para crear un GPT que investigue el impacto ambiental de centros de datos / Citizen Guide to Building a GPT for Data Center Environmental Investigations*. Amenaza Roboto.
