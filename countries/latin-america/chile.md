# Casos de Uso de IA para Chile
## Guía Completa: 110+ Casos de Uso Prácticos

> **Creado por Adrian Dunkley** | Experto Regional en IA | [maestrosai.com](https://maestrosai.com) | ceo@maestrosai.com
> *Uso Justo — Recurso Educativo*

---

## Chile en Cifras

| Indicador | Dato |
|-----------|------|
| Población | 19 millones |
| PIB | US$ 340 mil millones |
| PIB per cápita | ~US$ 17,500 |
| Moneda | Peso Chileno (CLP) |
| Idioma | Español |
| Capital | Santiago |
| Hubs tech | Santiago (Zona Apoquindo), Valparaíso, Concepción |
| Exportaciones | Cobre, litio, salmón, cerezas, vino, celulosa, harina de pescado |
| Unicornios | NotCo, Betterfly, Fintual, Buk, Houm, Altivia |
| Inversión minera | US$ 10.000M anuales en exploración y operación |

---

## Sector 1: Minería — Cobre, Litio y SERNAGEOMIN

### Caso de Uso 1: Codelco — Optimización de Operaciones de Chancado
**Rol**: Ingeniero de Procesos / Jefe de Turno / Analista de Confiabilidad
**Herramienta de IA**: Claude / ChatGPT Enterprise

**Estructura del Prompt**:
```
Soy ingeniero de procesos en una división de Codelco (ej. Chuquicamata / El Teniente / Andina / Salvador / Ministro Hales).
Circuito: chancado primario/secundario/terciario — SAG/molienda de bolas.
Mineral: pórfido cuprífero, ley media [X]% Cu, dureza Bond [X] kWh/t.
Problema actual: [baja disponibilidad de chancador / taponamiento de tolvas / variabilidad de ley / consumo energético elevado].
Producción objetivo: [X] toneladas métricas de cobre fino por día.
Instrumentación disponible: sensores de presión, torque, amperaje, densidad de pulpa, análisis granulométrico (P80).

Genera un plan de optimización que incluya:
1. Indicadores KPI críticos para chancado: disponibilidad, utilización, throughput (t/h), consumo específico (kWh/t)
2. Causa raíz del problema actual usando análisis fishbone — proceso vs equipo vs operación vs material
3. Estrategia de mantenimiento predictivo: umbrales de alerta por vibración (ISO 10816), temperatura de rodamientos
4. Protocolo de muestreo granulométrico: frecuencia, puntos de muestreo, análisis P80/P50
5. Plan de mejora de disponibilidad: MTBF, MTTR — comparación con benchmarks internacionales (AMEC, WMC)
6. Normativa SERNAGEOMIN aplicable: DS 132 (Reglamento de Seguridad Minera) — procedimientos críticos
7. Informe para la Gerencia General con indicadores financieros: costo por tonelada molida, impacto en producción anual
8. Estándares Codelco de sostenibilidad: consumo hídrico (L/t), eficiencia energética (kWh/t Cu fino)
```
**Beneficios**: Reducción de 8-15% en costo por tonelada; incremento de disponibilidad de 85% a 92%; ahorro energético equivalente a US$ 2-4M anuales por división

---

### Caso de Uso 2: Litio Atacama — SQM y Albemarle, Cumplimiento Ambiental y Optimización
**Rol**: Superintendente de Operaciones / Especialista Ambiental / Gerente de Relaciones Comunitarias
**Herramienta de IA**: Claude

**Estructura del Prompt**:
```
Trabajo en operaciones de litio en el Salar de Atacama para [SQM / Albemarle / empresa de exploración].
Proceso: extracción de salmuera — pozas de evaporación — planta de carbonato de litio (Li₂CO₃) / hidróxido de litio (LiOH).
Ley de salmuera: [X] g/L Li, [X] g/L K.
Cuotas de extracción CORFO: [X] toneladas Li contenido/año según contrato vigente.
Monitoreo ambiental: nivel freático del acuífero, flamingos (flamenco chileno, andino, de James — CONAF), vegetación halófita.
Comunidades: Atacameños (likan antai) — Consejo de Pueblos Atacameños — proceso de consulta previa (Convenio 169 OIT).

Desarrolla los siguientes documentos y estrategias:
1. Plan de monitoreo ambiental: protocolo de medición de niveles de salmuera (piezómetros), frecuencia reportes a CORFO/SMA
2. Informe de cumplimiento RCA: indicadores de la Resolución de Calificación Ambiental — formato requerido por SMA
3. Estrategia de relacionamiento con comunidades atacameñas: protocolo de consulta previa según DS 66, actas de reunión
4. Plan de eficiencia hídrica: reducción de pérdidas por evaporación, recirculación de salmuera agotada
5. Roadmap tecnológico: extracción de litio por adsorción directa (DLE) — ventajas ambientales vs proceso actual
6. Análisis de mercado: carbonato vs hidróxido de litio — precio spot LME, contratos a largo plazo con BMW/Tesla/CATL
7. Reporte de sostenibilidad ESG: métricas SASB para metales y minería — biodiversidad, agua, comunidades
8. Plan de gestión de residuos: disposición de cloruro de magnesio (MgCl₂) — normativa DS 148 residuos peligrosos
```
**Beneficios**: Reducción de riesgos regulatorios, mejora de relaciones comunitarias, aumento de 20% en eficiencia de recuperación de litio

---

### Caso de Uso 3: SERNAGEOMIN — Gestión de Seguridad Minera y Fiscalización
**Rol**: Fiscal Minero / Jefe de Seguridad / Experto en Prevención de Riesgos
**Herramienta de IA**: Claude

**Estructura del Prompt**:
```
Soy [fiscal de SERNAGEOMIN / jefe de seguridad] responsable de fiscalizar [faena minera subterránea / rajo abierto / planta de procesos] en [Región de Antofagasta / Atacama / O'Higgins / Coquimbo].
Faena: [nombre], categoría [A/B/C] según DS 132.
Personal: [X] trabajadores propios + [X] contratistas. Turno: [8/12] horas.
Accidente reciente / near miss: [descripción del evento].
Sistema de gestión: [ISO 45001 / OHSAS 18001 / sistema corporativo Codelco SIGLO XXI].

Elabora los siguientes documentos según DS 132 Reglamento de Seguridad Minera:
1. Investigación de accidente/incidente: árbol de causas (método ICAM o Tripod Beta) — formulario SERNAGEOMIN
2. Plan de acción correctiva: responsables, plazos, indicadores de cierre — formato aceptado por SERNAGEOMIN
3. PETRA (Permiso Escrito para Trabajo de Alto Riesgo): trabajos en altura, espacios confinados, energías peligrosas
4. Análisis de Riesgos de Tareas (ART): para las 10 tareas críticas de la faena
5. Plan de preparación y respuesta ante emergencias: incendio, derrumbe, escape de gases (CO, H₂S, NOx)
6. Programa de control de salud ocupacional: ruido (DS 594), polvo de sílice, vibraciones cuerpo entero
7. Indicadores de desempeño en seguridad: TRIFR, LTIFR, SIF — benchmarks industria chilena
8. Reporte trimestral SERNAGEOMIN: formato XML sistema PSIS (Portal de Seguridad e Información Sectorial)
```
**Beneficios**: Cumplimiento regulatorio completo; reducción de 40% en tiempo de elaboración de informes; disminución de multas y suspensiones

---

### Caso de Uso 4: Exploración Minera — Informes Geológicos y Due Diligence
**Rol**: Geólogo Jefe / Gerente de Exploración / Analista de Recursos
**Herramienta de IA**: Claude / Copilot

**Estructura del Prompt**:
```
Soy geólogo en proyecto de exploración de [cobre / oro / plata / litio / molibdeno] en [región de Chile].
Tipo de depósito: [pórfido cuprífero / IOCG / veta epitermal / salar].
Etapa: [prospección / exploración avanzada / pre-factibilidad].
Datos disponibles: [X] metros de sondaje, [X] muestras de roca / suelo / sedimento de quebrada.
Software: Leapfrog Geo / Datamine / Vulcan / ArcGIS.
Código de reporte: [JORC 2012 / NI 43-101 / SME Guide].

Apóyame en:
1. Informe técnico de exploración: resumen ejecutivo, geología regional, geología local, resultados de sondaje — formato SERNAGEOMIN
2. Estimación preliminar de recursos (Inferred Resources): metodología kriging ordinario vs inverso de la distancia — justificación
3. Control de calidad datos (QAQC): inserción de estándares, blancos y duplicados — análisis de sesgo con QA Charts
4. Informe de perforación para Directorio: avance mensual, costo por metro, interpretación geológica — audiencia no técnica
5. Proceso de concesiones mineras: pedimento, manifestación, mensura — plazos y costos según Código de Minería
6. Permiso de exploración SERNAGEOMIN: DGA para uso de agua en sondajes, DAA
7. Comunicado de prensa (NR): resultados de sondaje — lenguaje técnico para inversionistas TSX/NYSE
8. Modelo conceptual del depósito: hipótesis genética, vectores de mineralización, próximas áreas objetivo
```
**Beneficios**: Reducción de 50% en tiempo de elaboración de informes técnicos; cumplimiento de estándares internacionales de reporte

---

## Sector 2: Acuicultura del Salmón

### Caso de Uso 5: Salmonicultura — Gestión Sanitaria y Cumplimiento SERNAPESCA
**Rol**: Veterinario Acuícola / Jefe de Producción / Gerente Técnico
**Herramienta de IA**: Claude

**Estructura del Prompt**:
```
Soy veterinario acuícola en empresa salmonera ([Mowi / Cermaq / AquaChile / Salmones Camanchaca / Blumar]) en [Región de Los Lagos / Aysén / Magallanes].
Centro de cultivo: [nombre], código SERNAPESCA [X]. Especie: [Salmo salar / Oncorhynchus mykiss / Salvelinus alpinus].
Biomasa actual: [X] toneladas en [X] jaulas de [X] metros de diámetro.
Problema sanitario actual: [SRS (Piscirickettsia salmonis) / Caligus rogercresseyi (piojo de mar) / CMS / AGD / BKD].
Plan sanitario vigente: [X] tratamientos autorizados en el período.

Desarrolla plan de manejo sanitario integral:
1. Diagnóstico diferencial: síntomas, lesiones macroscópicas, diagnóstico molecular PCR — protocolo de muestreo SERNAPESCA
2. Protocolo de tratamiento: dosis, duración, tiempo de retiro — medicamentos registrados SAG (antibióticos: florfenicol, oxitetraciclina)
3. Gestión de Caligus: monitoreo quincenal — umbral de tratamiento (3 hembras ovígeras/pez) — baños de agua dulce / H₂O₂ / emamectina
4. Informe SERNAPESCA: formulario de mortalidades (MAS), registro de tratamientos (Sistema Acuícola)
5. Plan de manejo ambiental: sedimento bajo jaulas — Norma Ambiental DS 320 (límite de sulfuros)
6. Bienestar animal: Five Domains — indicadores de bienestar — estándares ASC (Aquaculture Stewardship Council)
7. Programa de vacunación: PD/SRS — protocolo de aplicación intraperitoneal — trazabilidad por lote de smolts
8. Certificación ASC y GlobalG.A.P.: requisitos, auditorías, acciones correctivas — mercados Europa/EE.UU.
```
**Beneficios**: Reducción de mortalidades en 25-35%; cumplimiento total SERNAPESCA; acceso a mercados premium con certificación

---

## Sector 3: Exportación de Frutas — Cerezas, Arándanos y Uvas

### Caso de Uso 6: Exportación de Cerezas — Temporada y Logística con China
**Rol**: Gerente de Exportaciones / Trader / Encargado de Postcosecha
**Herramienta de IA**: Claude / ChatGPT

**Estructura del Prompt**:
```
Soy exportador de cerezas chilenas con temporada [noviembre-enero]. Variedades: [Regina / Lapins / Sweetheart / Bing / Santina].
Producción: [X] toneladas de cerezas frescas. Calidad: Cat. 1 (calibre >28mm), Cat. 2 (24-28mm).
Destino principal: China (85% de exportaciones chilenas de cereza).
Transporte: [marítimo Shanghai/Qingdao/Tianjin — 22-24 días / aéreo — 30 horas].
Cadena de frío: pre-frío en packing, contenedores CA (atmósfera controlada: 5% CO₂, 2% O₂), T° -0.5°C a +0.5°C.
Entidad reguladora: SAG — Protocolo Fitosanitario bilateral Chile-China (plagas cuarentenarias: Ceratitis capitata).

Crea plan de exportación para la temporada:
1. Calendario de embarques: ventanas óptimas por variedad — correlación con precios en mercado chino (Enero es temporada alta)
2. Protocolo SAG: certificado fitosanitario, declaración de plaguicidas (residuos LMR — MRL en China), inspección de campo
3. Gestión de cadena de frío: especificaciones técnicas CA — monitoreo remoto de temperatura en contenedor (data loggers)
4. Análisis de precios en China: plataforma JD.com / WeChat — precio por caja 5kg en RMB — conversión y margen bruto
5. Documentación de exportación: Packing List, Commercial Invoice, Bill of Lading, Phytosanitary Certificate, Certificado de Origen TLC Chile-China
6. Protocolo de reclamaciones: daños en destino — evidencia fotográfica, seguro de carga, proceso de claim con importador
7. Estrategia de diversificación: mercados alternativos (India, Vietnam, Tailandia) — requisitos de acceso fitosanitario
8. Análisis de temporada: comparación precio FOB Valparaíso vs año anterior — impacto de tipo de cambio CLP/USD
```
**Beneficios**: Optimización de ventanas de embarque, reducción de pérdidas postcosecha de 8% a 3%, mejora de márgenes FOB en 15%

---

## Sector 4: Startups y Ecosistema de Innovación

### Caso de Uso 7: Start-Up Chile y CORFO — Postulación a Fondos de Emprendimiento
**Rol**: Emprendedor / Fundador de Startup / Jefe de Proyecto
**Herramienta de IA**: Claude

**Estructura del Prompt**:
```
Soy fundador de una startup [deeptech / agritech / fintech / healthtech / cleantech] en Chile.
Empresa: [nombre]. Etapa: [idea / MVP / tracción / escala].
Equipo: [X] cofundadores — background [técnico / comercial / científico].
Tracción actual: [X] usuarios / [X] clientes / MRR US$ [X] / cartas de intención.
Problema que resuelve: [descripción en 2 líneas].
Fondo al que postulo: [Build — hasta $20M CLP / Scale — hasta $60M CLP / Ignite — investigadores / Growth — startups globales].

Ayúdame a estructurar mi postulación a Start-Up Chile / CORFO:
1. Pitch deck de 10 slides: problema, solución, mercado (TAM/SAM/SOM), modelo de negocio, tracción, equipo, competencia, roadmap, uso de fondos, cierre
2. Formulario de postulación CORFO: "descripción del problema" (max 200 palabras) — lenguaje evaluado por comité
3. Modelo financiero básico: proyecciones a 3 años — supuestos conservadores / base / optimista — métricas SaaS si aplica
4. Estrategia de propiedad intelectual: patente INAPI, secreto industrial, copyright — qué proteger y cuándo
5. Plan de uso de fondos CORFO: categorías elegibles (personal, viajes, marketing, desarrollo), rendir cuentas (facturas)
6. Carta de presentación: por qué Chile, impacto económico y social, potencial de escala regional
7. Métricas de impacto CORFO: empleos generados, exportaciones potenciales, gender equity en equipo
8. Preparación para Demo Day Start-Up Chile: elevator pitch 2 minutos, Q&A de inversores internacionales
```
**Beneficios**: Tasa de aprobación 3x mayor con postulaciones bien estructuradas; acceso a red global de mentores y co-working en Santiago

---

## Sector 5: Energías Renovables — Solar Atacama e Hidrógeno Verde

### Caso de Uso 8: Hidrógeno Verde — Proyectos y Financiamiento en Chile
**Rol**: Gerente de Proyectos / Ingeniero de Energía / Especialista en Financiamiento Verde
**Herramienta de IA**: Claude

**Estructura del Prompt**:
```
Trabajo en un proyecto de hidrógeno verde en [Región de Antofagasta / Tarapacá / Magallanes].
Tecnología: electrólisis PEM (membrana de intercambio protónico) / alcalina.
Fuente de energía: solar fotovoltaica [Atacama] / eólica [Magallanes].
Capacidad proyectada: [X] MW electrolizador — producción [X] toneladas H₂/día.
Usos finales: [amoníaco verde / metanol verde / exportación H₂ líquido / combustible minería].
Entidades: Ministerio de Energía (Estrategia Nacional de Hidrógeno Verde), CORFO (H2Chile), CNE.
Financiamiento: [CORFO / KfW / IFC / Green Climate Fund / bono verde].

Desarrolla los siguientes documentos para el proyecto:
1. Perfil de proyecto para CORFO H2Chile: descripción técnica, alineación con Estrategia Nacional H2 (meta: hub global top 3 al 2030)
2. Análisis LCOH (Levelized Cost of Hydrogen): desglose de capex (electrolizador, balance de planta, conexión eléctrica), opex (electricidad, agua, O&M)
3. Proceso de permisos SEA: Estudio de Impacto Ambiental (EIA) — línea base, impactos, medidas de mitigación
4. Plan de financiamiento: estructura project finance — equity 30% / deuda 70%, garantías CORFO
5. Análisis de mercado de exportación: Japón (NCI), Corea del Sur, Alemania (H2Global) — requisitos de certificación (IRENA, CertifHy)
6. Acuerdo de compraventa de energía (PPA): estructura, precio, indexación — con generadora solar/eólica
7. Análisis de agua: fuente (agua de mar + desalinización vs agua subterránea), consumo (9L H₂O/kg H₂), permiso DGA
8. Certificación de carbono: huella de carbono del H₂ (kg CO₂/kg H₂) — metodología GHG Protocol Scope 2
```
**Beneficios**: Acceso a financiamiento verde, reducción de 30% en tiempo de preparación del perfil de proyecto, alineación con regulación nacional

---

## Tabla de Referencia Rápida: 102+ Casos de Uso Adicionales

### Sector: Minería (Casos 9-25)

| # | Caso de Uso | Rol | Herramienta de IA |
|---|-------------|-----|-------------------|
| 9 | Gestión de proveedores (Supply Chain) Codelco — análisis de contratos y criterios ESG | Jefe de Abastecimiento | Claude |
| 10 | Modelo de planificación de mina a largo plazo — LOM Plan con restricciones ambientales | Planificador de Mina | ChatGPT Enterprise |
| 11 | Análisis de ley de corte y optimización de recuperación metalúrgica | Metalurgista | Claude |
| 12 | Gestión de relaves: construcción de dique, monitoreo de seguridad — DS 248 SERNAGEOMIN | Ingeniero Geotécnico | Claude |
| 13 | Negociación de contratos spot de cobre: precio LME + premium de refinación (TC/RC) | Trader de Metales | ChatGPT |
| 14 | Informe de cierre de faena minera: Plan de Cierre según DS 41 — pasivos ambientales | Gerente de Asuntos Corporativos | Claude |
| 15 | Digitalización de mapas geológicos históricos de SERNAGEOMIN — vectorización con IA | Geólogo SIG | Gemini / Claude Vision |
| 16 | Análisis de estabilidad de taludes con IA — monitoreo con sensores InSAR | Geotécnico | Copilot |
| 17 | Plan de gestión de agua en minería: balance hídrico, recirculación, descarga DS 90 | Especialista Ambiental | Claude |
| 18 | Estrategia de compra de energía para minería: licitación CNE, PPA solar, tarifa regulada | Gerente de Energía | Claude |
| 19 | Análisis de minerales críticos: cobalto, manganeso, tierras raras — exploración en Chile | Explorador | ChatGPT |
| 20 | Gestión de comunidades indígenas en zona minera: EIA, Convenio 169 OIT, FPIC | Relacionador Comunitario | Claude |
| 21 | Automatización de camiones en mina: análisis de ROI tecnología autónoma (Komatsu AHS) | Ingeniero de Automatización | Copilot |
| 22 | Proceso de obtención de DGA: derechos de aprovechamiento de agua para minería | Abogado Minero | Claude |
| 23 | Reporte ESG anual para empresa minera: GRI Standards, TCFD, SASB Metals & Mining | Especialista ESG | Claude |
| 24 | Modelamiento geoestadístico de recursos: variograma, kriging, validación cruzada | Geólogo de Recursos | ChatGPT |
| 25 | Plan de descarbonización minería: electrificación de flota, ERNC, objetivo net-zero 2050 | Gerente de Sustentabilidad | Claude |

### Sector: Acuicultura del Salmón (Casos 26-38)

| # | Caso de Uso | Rol | Herramienta de IA |
|---|-------------|-----|-------------------|
| 26 | Análisis oceanográfico: corrientes, oxígeno disuelto, temperatura — selección de sitio | Biólogo Marino | Claude |
| 27 | Plan de alimentación optimizado: FCR (Feed Conversion Ratio), Thermal Growth Coefficient | Nutricionista Acuícola | ChatGPT |
| 28 | Gestión de smolts: calidad del agua en hatchery, fotoperiodo, vacunación | Gerente de Smoltificación | Claude |
| 29 | Certificación BAP (Best Aquaculture Practices) para exportación a EE.UU. | Jefe de Calidad | Claude |
| 30 | Negociación de contratos de venta de salmón: spot vs forward — mercado europeo (Nasdaq Fish Pool) | Trader | ChatGPT |
| 31 | Análisis de impacto ambiental DS 320: monitoreo de sedimentos y columna de agua | Especialista Ambiental | Claude |
| 32 | Plan de contingencia por bloom de algas (marea roja — SERNAPESCA HAB alert) | Gerente de Centro | Claude |
| 33 | Trazabilidad del producto: de smolt a filete — blockchain para supermercados europeos | Jefe de TI | Copilot |
| 34 | Estrategia de eficiencia energética en packing: refrigeración, congelado IQF | Ingeniero Industrial | ChatGPT |
| 35 | Análisis de mercado: salmón chileno vs noruego — diferenciales de precio y posicionamiento | Gerente Comercial | Claude |
| 36 | Programa de bienestar animal en matanza: aturdimiento eléctrico, CO₂ — Five Freedoms | Veterinario | Claude |
| 37 | Gestión de residuos: cabezas, vísceras, lodos — conversión a harina y aceite de pescado | Gerente Operaciones | ChatGPT |
| 38 | Plan de respuesta ante inspección SERNAPESCA: checklist de cumplimiento, carpeta de documentos | Jefe de Área | Claude |

### Sector: Exportación de Frutas (Casos 39-52)

| # | Caso de Uso | Rol | Herramienta de IA |
|---|-------------|-----|-------------------|
| 39 | Plan de cultivo de arándanos: variedades para mercado norteño (USA feb-abril), gap analysis | Agrónomo | Claude |
| 40 | Protocolo SAG para uvas de mesa: tratamiento cuarentenario (frío vs fumigación) para EE.UU. | Ingeniero Agrónomo | Claude |
| 41 | Análisis de LMR (Límites Máximos de Residuos): plaguicidas autorizados por mercado destino | Especialista en Inocuidad | ChatGPT |
| 42 | Plan de riego con tecnología precisión: sensores de humedad, VPD, programación fertirriego | Agrónomo de Precisión | Claude |
| 43 | Estrategia de diferenciación orgánica: certificación USDA Organic / EU Organic — conversión | Productor Orgánico | Claude |
| 44 | Análisis de opciones de transporte: costo marítimo vs aéreo para arándanos frescos | Logística | ChatGPT |
| 45 | Estrategia de venta en China: plataformas Tmall Global / JD International — setup tienda | Gerente E-commerce | Claude |
| 46 | Plan de postcosecha: temperatura, atmósfera controlada, etileno — tabla por producto | Tecnólogo en Alimentos | Claude |
| 47 | Análisis de precios históricos de cerezas: estacionalidad, años buenos vs malos — proyección | Analista de Mercado | ChatGPT |
| 48 | Certificación GlobalG.A.P.: checklist de puntos de control, preparación para auditoría | Responsable de Calidad | Claude |
| 49 | Gestión de cuadrillas de cosecha: planificación de personal, temporeros, contrato SENCE | RRHH Agrícola | Claude |
| 50 | Plan de exportación de paltas (Hass): protocolo fitosanitario, mercados USA/Europa/China | Exportador | Claude |
| 51 | Análisis de TLC Chile-China, Chile-USA, Chile-UE: aprovechamiento de rebajas arancelarias | Comercio Exterior | ChatGPT |
| 52 | Estrategia de marca-país para fruta chilena: posicionamiento "Fruta del Fin del Mundo" | Marketing | Claude |

### Sector: Vino Chileno (Casos 53-62)

| # | Caso de Uso | Rol | Herramienta de IA |
|---|-------------|-----|-------------------|
| 53 | Estrategia de exportación de Carmenère: posicionamiento varietal único de Chile en mercados premium | Gerente Exportaciones Viña | Claude |
| 54 | Plan de comunicación de terruño: Colchagua, Maipo, Casablanca, San Antonio — storytelling para sommelier | Director de Comunicaciones | Claude |
| 55 | Análisis de mercado de vino en China: canal on-trade (restaurantes) vs e-commerce (Tmall) | Gerente Comercial | ChatGPT |
| 56 | Certificación de vino orgánico/biodinámico: SAG vinos orgánicos, CE 834/2007 | Enólogo | Claude |
| 57 | Plan de enoturismo: circuito de visitas, maridajes, experiencias VIP — Ruta del Vino | Director Turismo Viña | Claude |
| 58 | Análisis de puntuaciones Wine Spectator / Robert Parker: correlación con precio y ventas | Analista | ChatGPT |
| 59 | Plan de manejo de viñedo: control de enfermedades (botrytis, oídio) — agricultura de precisión | Enólogo de Viticultura | Claude |
| 60 | Redacción de notas de cata: descriptores de Carmenère / Sauvignon Blanc chileno en inglés/español/chino | Enólogo / Sommelier | Claude |
| 61 | Estrategia de precio: posicionamiento entre $10-$20 USD/botella en USA — análisis de retail shelf | Brand Manager | Claude |
| 62 | Plan de participación en ferias: Prowein (Düsseldorf), Vinexpo, London Wine Fair — ROI esperado | Gerente de Marketing | ChatGPT |

### Sector: Gobierno Digital y Trámites (Casos 63-75)

| # | Caso de Uso | Rol | Herramienta de IA |
|---|-------------|-----|-------------------|
| 63 | ChileAtiende: automatización de respuestas a consultas ciudadanas — chatbot multiservicio | Funcionario SEGEGOB | Claude / Botpress |
| 64 | ClaveÚnica: protocolo de recuperación de contraseña y onboarding digital — guía para adultos mayores | Equipo UX Gobierno | Claude |
| 65 | Ley 21.180 de Transformación Digital: plan de implementación en municipio / servicio público | Jefe de TI Municipal | Claude |
| 66 | Atención en COMPIN: formularios de licencias médicas, invalidez — simplificación de trámites | Funcionario COMPIN | Claude |
| 67 | Plan de gobierno abierto: datos abiertos, portal data.gob.cl — análisis y visualización | Analista de Datos | Copilot |
| 68 | Declaración de renta SII: resumen de cambios anuales, guía para PYME y personas naturales | Asesor Tributario | Claude |
| 69 | Plataforma OIRS (Oficina de Información, Reclamos y Sugerencias): análisis de demanda ciudadana | Encargado OIRS | Claude |
| 70 | Plan de contratación pública: bases de licitación Mercado Público — ChileCompra | Jefe de Compras Municipal | Claude |
| 71 | Análisis de datos del CENSO 2024: indicadores socioeconómicos por región — visualizaciones | Analista INE | Copilot |
| 72 | Estrategia de seguridad cibernética: CSIRT Gobierno — análisis de vulnerabilidades, phishing | Especialista en Ciberseguridad | Claude |
| 73 | Plan de atención a ciudadanos con discapacidad: accesibilidad web (WCAG 2.1) en portales públicos | UX Designer Gobierno | Claude |
| 74 | Política de datos personales: cumplimiento Ley 19.628 (próxima actualización a nueva ley) | DPO / Asesor Legal | Claude |
| 75 | Plan de digitalización de archivos históricos: OCR, indexación — Archivo Nacional de Chile | Archivista | Gemini / Claude |

### Sector: Finanzas, AFP y CMF (Casos 76-88)

| # | Caso de Uso | Rol | Herramienta de IA |
|---|-------------|-----|-------------------|
| 76 | AFP: análisis de rentabilidad de fondos A/B/C/D/E — comunicación a afiliados en lenguaje simple | Ejecutivo AFP | Claude |
| 77 | CMF: elaboración de informe de cumplimiento normativo — Recopilación Actualizada de Normas (RAN) | Oficial de Cumplimiento | Claude |
| 78 | Fintech Ley 21.521: proceso de registro ante CMF — requisitos técnicos y legales | Fundador Fintech | Claude |
| 79 | Modelo de scoring crediticio alternativo: datos no tradicionales (pagos de servicios, redes sociales) | Data Scientist Fintech | ChatGPT |
| 80 | Plan de inversión personal: comparación AFP vs APV (Ahorro Previsional Voluntario) — optimización tributaria | Asesor Financiero | Claude |
| 81 | Análisis de riesgo de liquidez: Basilea III — ratio LCR para banco chileno supervisado por CMF | Tesorero Banco | Claude |
| 82 | Estrategia de crédito para PYME: análisis de oferta FOGAPE, BancoEstado, garantías CORFO | Ejecutivo PYME | Claude |
| 83 | Plan anti-lavado de activos (ALA/CFT): políticas UAF — cliente corporativo de alto riesgo | Oficial AML | Claude |
| 84 | Análisis de mercado de seguros: AACH — cobertura de terremotos en Chile (obligatorio para hipotecario) | Broker de Seguros | ChatGPT |
| 85 | Modelo de valorización de empresa chilena: DCF en CLP/UF — múltiplos comparables IPSA | Analista M&A | Claude |
| 86 | Política de dividendos: empresas listadas en la Bolsa de Santiago — requisito 30% utilidades líquidas | CFO Empresa Pública | Claude |
| 87 | Plan de emisión de bono verde: requisitos CMF, marco de referencia, uso de fondos elegibles | Gerente de Finanzas | Claude |
| 88 | Análisis de criptoactivos: marco regulatorio UAF Chile 2024 — riesgo AML en exchanges | Asesor Legal Crypto | Claude |

### Sector: Energías Renovables y Medioambiente (Casos 89-100)

| # | Caso de Uso | Rol | Herramienta de IA |
|---|-------------|-----|-------------------|
| 89 | Desarrollo solar fotovoltaico Atacama: evaluación de recurso (GHI), ingeniería básica, PPA | Desarrollador Solar | Claude |
| 90 | Plan de licitación CNE de energía: oferta estratégica — precio ofertado, bloque horario, localización | Gerente Comercial Generadora | ChatGPT |
| 91 | ERNC en sistemas aislados: Aysén / Juan Fernández — hibridación solar-diésel-batería | Ingeniero Energético | Claude |
| 92 | Plan de PMGD (Pequeño Medio de Generación Distribuida): tramitación SEC, conexión a red distribución | Desarrollador PMGD | Claude |
| 93 | Análisis de huella de carbono empresarial: Scope 1, 2 y 3 — inventario GEI según ISO 14064 | Especialista Sustentabilidad | Claude |
| 94 | Estrategia net-zero para empresa chilena: ruta de descarbonización, compensaciones de carbono | Gerente de Sustentabilidad | Claude |
| 95 | Plan de gestión CONAF: reforestación con especies nativas (lenga, coigüe, araucaria) — bonos de carbono | Ingeniero Forestal | Claude |
| 96 | Sistema de monitoreo ambiental: redes de medición de calidad del aire (SEREMI de Salud) — análisis de datos | Analista Ambiental | Copilot |
| 97 | Plan de eficiencia energética en edificio: Calificación Energética (CEV) — medidas de mejora | Arquitecto / Ingeniero | Claude |
| 98 | Gestión de residuos sólidos municipales: Plan de Gestión de Residuos — Ley REP (Responsabilidad Extendida del Productor) | Encargado Municipal de Medioambiente | Claude |
| 99 | Análisis de riesgo climático TCFD: exposición de activos a sequía, incendios, inundaciones en Chile | Analista de Riesgo | Claude |
| 100 | Plan de electromovilidad para empresa: flota eléctrica, cargadores, análisis TCO vs combustión | Gerente de Flota | ChatGPT |
| 101 | Hidrógeno verde para minería: conversión de flota de camiones en mina — análisis técnico-económico | Gerente de Innovación Minera | Claude |
| 102 | Plan de desalinización solar: solución hídrica para minería del norte de Chile — huella carbono | Ingeniero de Proyectos | Claude |
| 103 | Análisis de eólico en Magallanes: recurso eólico (velocidad media >10 m/s), conectividad, H2 exportación | Desarrollador Eólico | Claude |
| 104 | Certificación ISO 14001 para empresa industrial: plan de implementación, auditoría interna | Jefe de Medioambiente | Claude |
| 105 | Plan de gestión de glaciares: normativa Ley de Glaciares (en tramitación) — impacto en minería | Glaciólogo / Abogado | Claude |
| 106 | Mercado de bonos de carbono: registro nacional de Chile, metodologías VERRA / Gold Standard | Especialista en Carbono | Claude |
| 107 | Estrategia de agrivoltaico: generación solar + agricultura en zona norte-chico | Agricultor / Desarrollador Solar | ChatGPT |
| 108 | Plan de economía circular: PNPRS Ministerio del Medio Ambiente — empresa manufacturera | Gerente de Operaciones | Claude |
| 109 | Análisis de riesgo sísmico: constructora en zona 3 (Norma NCh 433) — diseño antisísmico | Ingeniero Civil Estructural | Copilot |
| 110 | Estrategia de agua en agricultura: eficiencia de riego, DAA, Plan de Gestión de Cuencas DGA | Agricultor / Agrónomo | Claude |

---

## Herramientas de IA Recomendadas para Chile

| Herramienta | Mejor Para | Costo Aprox. |
|-------------|-----------|--------------|
| Claude (Anthropic) | Análisis regulatorio, redacción técnica, documentos legales CMF/SERNAGEOMIN/SERNAPESCA | Gratis / Pro US$20/mes |
| ChatGPT (OpenAI) | Brainstorming, análisis de mercado, correos comerciales, código Python | Gratis / Plus US$20/mes |
| GitHub Copilot | Automatización, scripting para análisis de datos mineros/energéticos | US$10/mes |
| Gemini (Google) | Análisis de documentos, integración Google Workspace (gobierno), imágenes satelitales | Gratis / Workspace |
| Microsoft Copilot | Documentos Excel/Word/PowerPoint para reportes corporativos Codelco/viñas/AFP | Microsoft 365 |
| Perplexity | Investigación rápida: precios LME, regulación CMF, normativa SAG | Gratis / Pro US$20/mes |
| Midjourney / DALL-E | Material visual: marketing de vino, frutas, enoturismo, energía solar | US$10-30/mes |
| Notion AI | Gestión de proyectos: startups CORFO, equipos de exploración minera | US$8-16/mes |

---

## Tabla de Instituciones Chilenas Clave para Prompts de IA

| Institución | Sigla | Rol |
|-------------|-------|-----|
| Servicio Nacional de Geología y Minería | SERNAGEOMIN | Regulación seguridad minera, catastro geológico |
| Servicio Nacional de Pesca y Acuicultura | SERNAPESCA | Fiscalización acuicultura y pesca |
| Servicio Agrícola y Ganadero | SAG | Certificados fitosanitarios, exportación agrícola |
| Corporación de Fomento de la Producción | CORFO | Financiamiento innovación, Start-Up Chile |
| Comisión Minera | CMH | Concesiones mineras |
| Comisión para el Mercado Financiero | CMF | Regulación bancos, seguros, AFP, fintech |
| Servicio de Impuestos Internos | SII | Tributación empresa e individual |
| Dirección General de Aguas | DGA | Derechos de agua |
| Superintendencia del Medio Ambiente | SMA | Fiscalización ambiental, RCA |
| Corporación Nacional Forestal | CONAF | Gestión forestal, áreas protegidas |
| Comisión Nacional de Energía | CNE | Licitaciones eléctricas, tarifas |
| Superintendencia de Electricidad y Combustibles | SEC | Concesiones eléctricas, instalaciones |
| Servicio de Evaluación Ambiental | SEA | Tramitación EIA y DGA |
| Instituto Nacional de Propiedad Industrial | INAPI | Patentes, marcas |
| Subsecretaría de Telecomunicaciones | SUBTEL | Regulación telecomunicaciones |

---

## Glosario Sectorial Chileno

| Término | Significado |
|---------|-------------|
| IPSA | Índice de Precio Selectivo de Acciones — bolsa de Santiago |
| UF | Unidad de Fomento — unidad indexada a inflación |
| AFP | Administradora de Fondos de Pensiones |
| APV | Ahorro Previsional Voluntario |
| FOGAPE | Fondo de Garantía para Pequeños Empresarios |
| RCA | Resolución de Calificación Ambiental |
| LTE / 5G | Cobertura telecomunicaciones SUBTEL |
| MAPE | Minería artesanal de pequeña escala |
| PPA | Power Purchase Agreement (Contrato de Compraventa de Energía) |
| TC/RC | Tratamiento Charge / Refinamiento Charge (cobre) |
| SRS | Salmonid Rickettsial Septicemia (enfermedad salmones) |
| PMGD | Pequeño Medio de Generación Distribuida |
| TLC | Tratado de Libre Comercio |
| MRR | Monthly Recurring Revenue |
| FCR | Feed Conversion Ratio (acuicultura) |

---

## SEO y Recursos Adicionales

**Palabras clave**: IA Chile minería cobre litio, inteligencia artificial salmonicultura Chile, ChatGPT exportación cerezas Chile, prompts IA CORFO Start-Up Chile, IA regulación CMF Chile, Claude SERNAGEOMIN seguridad minera, IA hidrógeno verde Atacama, herramientas IA vino Carmenère Chile

**Sectores relacionados**: Codelco digitalización, SQM tecnología, Mowi Chile IA, CORFO innovación, CNE energía renovable IA, AFP tecnología financiera Chile

**Recursos oficiales**:
- CORFO: [corfo.cl](https://www.corfo.cl)
- Start-Up Chile: [startupchile.org](https://www.startupchile.org)
- SERNAGEOMIN: [sernageomin.cl](https://www.sernageomin.cl)
- SERNAPESCA: [sernapesca.cl](https://www.sernapesca.cl)
- CMF: [cmfchile.cl](https://www.cmfchile.cl)
- CNE: [cne.cl](https://www.cne.cl)
- SAG: [sag.cl](https://www.sag.cl)

---

*Creado por **Adrian Dunkley** | [maestrosai.com](https://maestrosai.com) | ceo@maestrosai.com*
*Recurso educativo de uso libre — cite la fuente al compartir*
*Actualizado: Marzo 2026*
