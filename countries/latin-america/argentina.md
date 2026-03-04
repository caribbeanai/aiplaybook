# Casos de Uso de IA para Argentina
## Guía Completa: 110+ Casos de Uso Prácticos

> **Creado por Adrian Dunkley** | Experto Regional en IA | [maestrosai.com](https://maestrosai.com) | ceo@maestrosai.com
> *Uso Justo — Recurso Educativo*

---

## Argentina en Cifras

| Indicador | Dato |
|-----------|------|
| Población | 46 millones |
| PIB | US$ 620 mil millones |
| PIB per cápita | ~US$ 13,500 |
| Moneda | Peso Argentino (ARS) |
| Idioma | Español |
| Capital | Buenos Aires |
| Hub tech | Buenos Aires (2do en LatAm) |
| Unicornios | Mercado Libre, Globant, Auth0, Ualá, Tiendanube, Bitso |
| Exportaciones | Soja, maíz, carne vacuna, litio, vino, software |
| Desarrolladores | 115,000+ |
| Marco IA/Tech | Ley Economía del Conocimiento 27.506 |

---

## Sector 1: Agro — Pampa Húmeda y Exportaciones

### Caso de Uso 1: Siembra de Soja y Maíz — Planificación con INTA y ZARC
**Rol**: Productor agropecuario / Ingeniero agrónomo / Asesor CREA
**Herramienta de IA**: Claude

**Estructura del Prompt**:
```
Soy productor agropecuario en [partido de Buenos Aires/Santa Fe/Córdoba/Entre Ríos].
Campo: [X hectáreas]. Suelo: [serie/tipo: franco-limoso/franco-arcilloso].
Índice de productividad INTA: [X]. Zona agroecológica: [núcleo sojero/maíz].
Cultivos planificados: [soja de 1ra/soja de 2da/maíz temprano/maíz tardío].
Maquinaria: [propia/contratista]. Silos: [X toneladas capacidad].
Contratos de venta: [X toneladas a precio fijo/a fijar/MAT].
Rinde objetivo: soja [X qq/ha], maíz [X qq/ha].
Cobertura ZARC (Zoneamento Agrícola de Risco Climático): [período recomendado].

Desarrolla un plan agrícola integral:
- Ventana óptima de siembra por cultivo según INTA zona [X] y riesgo climático ZARC
- Elección de híbridos/variedades: criterios INASE, adaptación local, resistencia a enfermedades
- Nutrición de suelos: análisis foliar, reposición NPK+S, aplicación variable por ambientes
- Agricultura de precisión: mapas de rendimiento, corrección variable, drones para monitoreo
- Manejo integrado de plagas: chinche, trips, gusano cogollero — umbrales de acción INTA
- Plan de comercialización: precio disponible vs contratos MAT, cobertura con opciones MATBA-ROFEX
- Logística de cosecha: coordinación con acopiador/exportador, turnos de entrega
- Financiamiento: warrants sobre acopio, FCI agropecuarios, créditos BICE Productivo
- Documentación AFIP: liquidación de divisas BCRA, declaración jurada de ventas (DJVE)
- Estimación de márgenes brutos en ARS y USD: breakeven por cultivo
```
**Beneficios**: Optimización de rindes, mejor timing de venta, reducción de riesgo climático y financiero, compliance AFIP/BCRA

---

### Caso de Uso 2: Exportación Agropecuaria — AFIP, BCRA, SENASA
**Rol**: Exportador de granos / Corredor de cereales / Despachante de aduana
**Herramienta de IA**: Claude

**Estructura del Prompt**:
```
Soy exportador/corredor de [soja/maíz/trigo/girasol/harina de soja/aceite de soja].
Empresa: [PyME exportadora / trading internacional]. Volumen: [X toneladas/campaña].
Destino: [China/UE/Vietnam/Indonesia/Egipto]. Puerto de salida: [Rosario/Bahía Blanca/Quequén].
Situación actual: necesito gestionar el ciclo completo de exportación.

Guíame en el proceso completo de exportación de granos:
- DJVE (Declaración Jurada de Ventas al Exterior): cómo registrar, plazos, posiciones arancelarias
- Liquidación de divisas BCRA: plazos obligatorios según SEPA vigente, tipo de cambio diferencial (dólar soja)
- SENASA: habilitación de establecimientos, certificados fitosanitarios, protocolo por país destino
- Aduana AFIP: permiso de embarque, DU-E (despacho de exportación), pesos y calidades
- Retenciones a la exportación: alícuotas vigentes por producto, cómo calcular el neto a cobrar
- Financiamiento pre-embarque: pre-financiación BCRA, líneas Bapro Agro, créditos BNA Campo
- Certificaciones de origen: Mercosur, SGP, Acuerdo Mercosur-UE (cuando vigente)
- Logística portuaria: reserva de buque, armador, pólizas de seguro de carga, fumigación
- Cobros del exterior: SWIFT, cuenta bancaria validada BCRA, ingreso dentro del plazo
- Control de cambios: infracciones frecuentes, cómo evitar sanciones BCRA/AFIP
```
**Beneficios**: Cumplimiento regulatorio, optimización del tipo de cambio, acceso a financiamiento preferencial, evitar sanciones

---

### Caso de Uso 3: Feedlot — Engorde Bovino Intensivo
**Rol**: Propietario de feedlot / Veterinario / Nutricionista animal
**Herramienta de IA**: Claude

**Estructura del Prompt**:
```
Tengo un feedlot en [provincia: Buenos Aires/Córdoba/Santa Fe/Entre Ríos].
Capacidad: [X cabezas]. Categoría: [terneros/novillos/vaquillonas].
Peso de entrada: [X kg]. Peso de salida objetivo: [X kg].
Dieta actual: [maíz/silaje/expeller de girasol/DDGS/heno].
Destino: [faena local/exportación cuota Hilton/supermercado].
Habilitaciones: SENASA [número], RENSPA, habilitación municipal.

Optimiza la operación del feedlot:
- Formulación de dietas: ajuste de raciones por etapa de engorde, conversión alimenticia objetivo
- Costo de la dieta: precio de insumos al día, costo por kilo de carne producida
- Sanidad: plan vacunación (Clostridiosis/IBR/DVB/Mannheimia), tratamiento en corrales
- Bienestar animal: requerimientos SENASA para exportación, densidad por corral
- Cuota Hilton: requisitos de raza, certificación, tipificación, frigoríficos habilitados
- Exportación: habilitación frigorífico, protocolo por país destino, SENASA Ciclo II
- Análisis económico: precio del novillo gordo MAT, spread entrada-salida en USD
- Gestión ambiental: tratamiento de efluentes, distancia a poblados, habilitación provincial
- Trazabilidad bovina: SIGB SENASA, caravanas electrónicas, sistema de seguimiento
- Financiamiento: créditos BICE ganadero, warrants sobre hacienda en feedlot
```
**Beneficios**: Mejora de conversión, reducción de mortalidad, acceso a mercados premium (cuota Hilton), compliance SENASA

---

### Caso de Uso 4: Litio — Triángulo del Litio y Régimen RIGI
**Rol**: Ejecutivo minero / Abogado especialista / Asesor de inversiones
**Herramienta de IA**: Claude

**Estructura del Prompt**:
```
Trabajo en un proyecto de litio en [Salta/Jujuy/Catamarca — Triángulo del Litio].
Etapa del proyecto: [exploración/factibilidad/construcción/producción].
Modalidad: [salmuera en salar/roca dura — espodumeno].
Empresa: [junior minera/major internacional/asociación con JEMSE/CAMYEN].
Producto objetivo: [carbonato de litio/hidróxido de litio].
Capacidad objetivo: [X toneladas LCE/año]. Inversión estimada: [USD X millones].

Asesórame en el proyecto de litio en Argentina:
- Marco RIGI (Régimen de Incentivo a las Grandes Inversiones Ley 27.742): requisitos, beneficios fiscales (impuesto a las ganancias reducido, estabilidad 30 años), tramitación
- Regalías provinciales: alícuotas por provincia, negociación con gobierno provincial
- Permiso ambiental: EIA (Estudio de Impacto Ambiental), audiencia pública, Ley General del Ambiente 25.675
- Consulta previa libre e informada (CPLI): comunidades indígenas originarias, protocolo
- Tecnología de extracción: evaporación solar tradicional vs DLE (Direct Lithium Extraction) — comparativa
- Clientes estratégicos: contratos con fabricantes de baterías (CATL/Panasonic/LG Chem/Albemarle)
- Precio de mercado: contrato spot vs largo plazo — estrategia de precio
- Logística de exportación: Paso Jama/Salta a puertos chilenos o Jujuy a Buenos Aires
- Financiamiento: IFC, CAF, BID, project finance internacional, bonos verdes
- Rol del Estado: JEMSE (Jujuy), CAMYEN (Catamarca), Lithium Argentina — asociaciones público-privadas
```
**Beneficios**: Acceso a beneficios RIGI, mitigación de riesgos regulatorios y comunitarios, posicionamiento en cadena global de valor de baterías

---

## Sector 2: Tecnología y Exportación de Software

### Caso de Uso 5: Ley Economía del Conocimiento 27.506 — Compliance y Beneficios
**Rol**: CEO/CFO de empresa tech / Contador especialista / Abogado tributario
**Herramienta de IA**: Claude

**Estructura del Prompt**:
```
Soy [CEO/CFO/contador] de una empresa de [software/servicios IT/ciberseguridad/IA/biotech/diseño/auditoría].
Facturación anual: ARS [X] / USD [X]. Empleados: [X].
Porcentaje de exportación de servicios: [X%].
Situación actual: [inscripta en LEC/quiero inscribirme/renovación].
Actividades: [desarrollo de software a medida/SaaS/consultoría IT/ciberseguridad/big data].

Ayúdame a maximizar los beneficios de la Ley 27.506:
- Requisitos de inscripción: actividades calificadas, personal mínimo, exportaciones mínimas
- Bono de crédito fiscal: cálculo del bono sobre contribuciones patronales, uso para pago de impuestos nacionales
- Estabilidad fiscal: protección frente a nuevos impuestos nacionales durante vigencia
- Reducción de impuesto a las ganancias: de 35% a 15% (exportación de servicios de conocimiento)
- Dólar tech: cómo cobrar exportaciones de servicios al tipo de cambio MEP/CCL (legal)
- Nómina y estructura de personal: empleados en relación de dependencia vs monotributo vs contratos internacionales
- Auditoría de cumplimiento: indicadores de exportación, cómo documentar para SEPYME
- Renovación bienal: documentación, declaraciones juradas, indicadores de empleo calificado
- Doble imposición: convenios con EE.UU., España, Brasil para facturación internacional
- Estrategia de crecimiento: cómo escalar manteniendo los beneficios LEC con cada contratación
```
**Beneficios**: Ahorro fiscal de hasta 60% en carga tributaria, acceso a dólar diferencial, estabilidad para planificación a largo plazo

---

### Caso de Uso 6: Carrera Tech en Globant / Mercado Libre — Crecimiento Profesional
**Rol**: Desarrollador de software / Product manager / Diseñador UX
**Herramienta de IA**: Claude

**Estructura del Prompt**:
```
Soy [developer/PM/diseñador/data scientist] con [X años] de experiencia.
Stack tecnológico actual: [Java/Python/React/Node/AWS/GCP].
Empresa actual: [startup/agencia/empresa tradicional].
Meta: ingresar o crecer en Globant/Mercado Libre/Despegar/OLX/Ualá/Tiendanube.
Nivel de inglés: [básico/intermedio/avanzado].
Certificaciones: [AWS/Google/PMP/ninguna].

Diseña mi plan de desarrollo profesional tech en Argentina:
- Roadmap técnico: habilidades específicas que buscan Globant/MeLi en cada rol
- Certificaciones clave: AWS Solutions Architect, Google Cloud, Kubernetes — cómo estudiar gratis
- Portfolio en GitHub: proyectos que impresionan en entrevistas técnicas en estas empresas
- Inglés técnico: recursos específicos para entrevistas y trabajo diario (writing, meetings, demos)
- Proceso de entrevista: etapas técnicas en Globant (Studios model), MeLi (coding challenge + system design)
- Sueldo en USD: rangos actuales por nivel (Jr/Semi/Sr/Tech Lead), comparación con mercado global
- Trabajo remoto internacional: empresas europeas/norteamericanas que contratan devs argentinos
- Freelance internacional: Toptal/Upwork/Deel — cómo facturar legalmente, dólar tech
- Comunidades: eventos Buenos Aires JS, PyCon Argentina, Nerdearla — networking
- MBA tech: programas nacionales (IAE/Di Tella/UTDT) vs internacionales con beca
```
**Beneficios**: Triplicar ingresos en 18-24 meses, acceso a mercado laboral internacional, estabilidad en USD

---

## Sector 3: Vitivinicultura — Malbec Argentino

### Caso de Uso 7: Exportación de Vino Malbec a EE.UU., UE y China
**Rol**: Bodega exportadora / Exportador vitivinícola / Gerente comercial
**Herramienta de IA**: Claude

**Estructura del Prompt**:
```
Soy [propietario de bodega/gerente de exportación] en [Mendoza/San Juan/La Rioja/Neuquén/Río Negro].
Producción: [X cajas de 9L/año]. Varietales: [Malbec/Cabernet/Torrontés/Blend].
Precio promedio FOB: [USD X/caja]. Destinos actuales: [EE.UU./Brasil/UE/China].
Certificaciones: [orgánico/biodinámico/Vegan/Halal/ninguna].
Posicionamiento: [entry level <USD 10/premium USD 10-20/ultra-premium >USD 20 al consumidor].

Desarrolla estrategia de exportación vitivinícola:
- Registro TTB (EE.UU.): Certificate of Label Approval (COLA), información obligatoria, costos
- Importadores en EE.UU.: cómo seleccionar importer/distribuidor por estado (three-tier system), contrato
- Regulación UE: etiquetado vino 2023 (ingredientes, calorías obligatorios desde 2025), QR code
- Mercado China: plataformas Tmall/JD.com, registro en CIQR, relaciones con importadores chinos
- Enoturismo como marca: cómo la bodega presencial refuerza la exportación digital
- Storytelling Malbec: diferenciación de terroir (Luján de Cuyo/Valle de Uco/San Rafael), altitud, suelo
- Precio FOB a precio de góndola: cálculo de márgenes para cada canal y país destino
- Fondo Vitivinícola Mendoza: co-inversión en marketing internacional, ferias (Vinexpo/ProWein/Prowein)
- Documentación AFIP/SENASA: certificado fitosanitario, certificado de análisis, certificado de origen Mendoza
- Wine score: estrategia para obtener 90+ puntos Parker/Wine Spectator — impacto en precio y volumen
```
**Beneficios**: Acceso a mercados premium mundiales, diferenciación por terroir, precio 3-5x sobre mercado interno

---

### Caso de Uso 8: Posicionamiento Premium — Marca y Enoturismo
**Rol**: Director de marketing de bodega / Sommelier / Agencia de turismo enológico
**Herramienta de IA**: Claude

**Estructura del Prompt**:
```
Soy responsable de marketing de [bodega boutique/winery familiar/gran bodega] en Mendoza.
Capacidad de visitantes: [X personas/mes]. Precio de experiencias: [ARS/USD X].
Canales actuales: [Instagram/web/OTA/agencias receptivas].
Público objetivo: [turismo nacional/internacional/corporativo/parejas].
Meta: posicionar la bodega como destino de enoturismo premium y reforzar exportación.

Crea estrategia de marketing y enoturismo premium:
- Identidad de marca: historia de familia, terroir único, winemaker — narrativa auténtica
- Contenido digital: calendario de Instagram/TikTok para bodega, reels de vendimia, detrás de escena
- Google Business: optimización para búsquedas "wine tours Mendoza", reseñas, fotos
- Experiencias premium: wine pairing con cocina regional, cata vertical, harvest experience — precios en USD
- B2B turístico: alianzas con Hyatt/Park Hyatt Mendoza, Four Seasons, concierges de hoteles boutique
- Prensa internacional: wine journalists, bloggers especializados — invitaciones estratégicas
- Club de vinos: membresía, envíos a domicilio en Argentina, suscripción internacional (e-commerce)
- Awards: concursos internacionales (Decanter/IWSC/Buenos Aires Wine Awards), cómo postular
- Certificaciones sostenibilidad: Wines of Argentina sustentable, huella de carbono — comunicación
- ROI del enoturismo: cómo el visitante de la bodega compra 3x más que el canal supermercado
```
**Beneficios**: Aumento de precio promedio por botella, fidelización de clientes, diversificación de ingresos en USD

---

## Sector 4: Finanzas en Contexto Inflacionario

### Caso de Uso 9: Finanzas Personales — UVA, FCI, Cedears y Dólar MEP
**Rol**: Profesional independiente / Empleado / Inversor individual
**Herramienta de IA**: Claude

**Estructura del Prompt**:
```
Soy [empleado en relación de dependencia/autónomo/monotributista] en Argentina.
Ingresos mensuales: [ARS X]. Ahorros: [ARS X / USD X].
Situación: [alquiler/propietario/crédito UVA vigente].
Objetivos: proteger el poder adquisitivo, ahorrar en USD, planificar largo plazo.
Conocimiento financiero: [básico/intermedio/avanzado].
Broker/banco actual: [Balanz/IOL/PPI/BYMA/Banco X].

Diseña mi estrategia de finanzas personales en Argentina:
- Presupuesto anti-inflación: fórmula de ahorro cuando el IPC supera el 100% anual
- Instrumentos en ARS: Lecap/Boncap (letras del Tesoro), FCI Money Market, plazos fijos UVA vs tasa fija
- Dólar MEP (legal): cómo comprar paso a paso (AL30/GD30), diferencia con dólar oficial y blue
- Cedears: qué son, cuáles comprar (AAPL/MELI/TSLA/QQQ en ARS), retención de dividendos
- Inversión inmobiliaria: fideicomiso al costo, permuta de inmueble en pozo por pesos
- Crédito UVA: análisis de cuota/sueldo, cómo negociar refinanciación en contexto inflacionario
- Seguro de vida con ahorro: SEPELIO, PYME protegida — instrumentos con rendimiento
- Criptomonedas: regulación AFIP (bienes personales), declaración de holdings, stablecoins USDT/DAI
- Plan de jubilación: AFJP extintas, monotributo con jubilación, depósito convenido empresas
- Cómo hablar con tu banco: productos convenientes vs trampa — qué aceptar y rechazar
```
**Beneficios**: Preservación del capital frente a inflación, construcción de patrimonio en USD, cumplimiento fiscal

---

### Caso de Uso 10: Finanzas PyME — SGR, BCRA y Factoring Electrónico SIGNO
**Rol**: Dueño de PyME / CFO / Contador de empresa mediana
**Herramienta de IA**: Claude

**Estructura del Prompt**:
```
Soy [dueño/CFO/contador] de una PyME en Argentina con [X empleados].
Sector: [industria/comercio/servicios]. Facturación: ARS [X]/año.
Situación financiera: [buen flujo/capital de trabajo limitado/deuda bancaria alta].
Necesidad: [financiar capital de trabajo/adquirir maquinaria/exportar/expandirme].
Banco principal: [Banco X — cuenta corriente, cheques].

Estructura un plan financiero integral para mi PyME:
- Cheque de Pago Diferido: negociación en BYMA vía SGR — cómo descontar a tasa preferencial
- SGR (Sociedades de Garantía Recíproca): qué es, cómo asociarme, garantías disponibles, costo
- BCRA líneas especiales PyME: tasa subsidiada para inversión productiva, requisitos, bancos participantes
- Factoring electrónico SIGNO: ceder facturas vía plataforma SIGNO, acceso a liquidez inmediata
- Leasing financiero: BNA/Santander/BBVA — adquirir maquinaria sin descapitalizarse, tratamiento impositivo
- FOGAR (Fondo de Garantías Argentino): garantías estatales para PyMEs sin colateral propio
- Exportación: pre-financiación de exportaciones BCRA — tasa, plazos, habilitación del banco
- Plan de pagos AFIP: moratoria vigente, facilidades de pago, quita de intereses
- Presupuesto de caja en hiperinflación: rolling 90 días, cobertura de insumos, política de precios
- Reestructuración de deuda: cómo negociar con banco cuando hay iliquidez transitoria — herramientas legales
```
**Beneficios**: Acceso a financiamiento preferencial, mejora de liquidez, reducción de costo financiero

---

## Sector 5: Mercado Inmobiliario — Fideicomisos y Construcción

### Caso de Uso 11: Fideicomiso de Construcción al Costo
**Rol**: Desarrollador inmobiliario / Escribano / Inversor en pozo
**Herramienta de IA**: Claude

**Estructura del Prompt**:
```
Soy [desarrollador/inversor] en un proyecto de fideicomiso al costo en [barrio/ciudad].
Proyecto: [X unidades, X m2 totales]. Superficie por unidad: [X m2].
Precio de venta en pozo: [USD X/m2]. Costo de construcción: [USD X/m2].
Etapa: [lanzamiento/preventa/construcción/entrega].
Estructura: fideicomiso de construcción — fiduciante/fiduciario/beneficiario.

Guíame en el fideicomiso inmobiliario argentino:
- Estructura legal: fiduciante (desarrollador), fiduciario (banco/escribano), beneficiarios (compradores)
- Ventajas fiscales: el fideicomiso al costo no paga IVA en la venta si se cumplen condiciones
- Escritura de fideicomiso: cláusulas esenciales — quórum de asambleas, cuentas separadas, rendición
- Boleto de compraventa: modelo para preventas, cuotas en UVA/dólares, penalidades
- Financiamiento del fideicomiso: cuotas de preventas, crédito puente bancario, mezcla óptima
- AFIP — ITI (Impuesto a la Transferencia de Inmuebles): cuándo aplica, cómo declarar
- Bienes personales: declaración del porcentaje del fideicomiso — alícuota, valuación
- Certificación de obra: cómo documentar avance para rendición a fiduciantes
- Seguro de caución: protección para compradores ante insolvencia del desarrollador
- Normativa BCRA: cómo recibir pagos en dólares — cuentas en USD para fideicomisos
```
**Beneficios**: Estructura legal sólida, ventajas fiscales, acceso a inversores en USD, transparencia en rendición de cuentas

---

## Casos de Uso 12–110: Tabla de Referencia Rápida

| # | Sector | Caso de Uso | Rol Principal | Herramienta |
|---|--------|-------------|---------------|-------------|
| 12 | Agro precisión | Agricultura de precisión: mapas de rendimiento y prescripción variable con satélite | Agrónomo / Productor | Claude |
| 13 | Agro trigo | Planificación de trigo pan: variedades INTA, manejo de roya amarilla, exportación | Productor / Corredor | Claude |
| 14 | Agro yerba mate | Yerba mate Misiones: INYM, precios regulados, planes de mejoramiento | Yerbatero / Cooperativa | Claude |
| 15 | Agro pesca | Pesca costera Rawson/Mar del Plata: cuotas MAGYP, certificado MSC, exportación | Pesquero / Armador | Claude |
| 16 | Agro arándanos | Arándanos Tucumán/Entre Ríos: protocolo fitosanitario EE.UU./UE, cadena de frío | Productor / Exportador | Claude |
| 17 | Agro maní | Maní Córdoba: industria aceitera, exportación a China/UE, aflatoxinas control | Industrial / Exportador | Claude |
| 18 | Agro olivos | Olivicultura San Juan/La Rioja/Mendoza: aceite de oliva extra virgen premium | Olivicultor / Bodega | Claude |
| 19 | Agro fruticultura | Peras y manzanas Río Negro: CAFI, exportación Brasil/UE, postcosecha | Fruticultores / CAFI | Claude |
| 20 | Agro drones | Aplicación de fitosanitarios con drones: habilitación ANAC, mapa de vuelo, ROI | Empresa de servicios agro | Claude |
| 21 | Nearshoring | Atracción de proyectos nearshore: propuesta de valor Argentina para empresas EE.UU. | Cámara CESSI / Empresa | Claude |
| 22 | Tech startup | Constitución de startup SAS digital y búsqueda de inversión ángel en Argentina | Founder / Abogado | Claude |
| 23 | Tech LATAM | Expansión regional de SaaS argentino a México/Colombia/Chile: go-to-market | CEO / CMO startup | Claude |
| 24 | Fintech BCRA | Sandbox regulatorio BCRA para fintech: PSP/PSEC/PSP Pagos — habilitación | Founder fintech / Abogado | Claude |
| 25 | Fintech VC | Fundraising Serie A para startup argentina: pitch deck, due diligence, term sheet | CEO / CFO startup | Claude |
| 26 | Fintech Tiendanube | Tienda online en Tiendanube: catálogo, Mercado Pago, logística OCA/Andreani | Emprendedor e-commerce | Claude |
| 27 | Fintech Modo | Integración Modo y pagos QR para negocio: DEBIN, QR interoperable, conciliación | Dueño de negocio | Claude |
| 28 | Cripto AFIP | Declaración de criptomonedas en AFIP: bienes personales, ganancias, blanqueo 2024 | Inversor crypto / Contador | Claude |
| 29 | Contabilidad | Ajuste por inflación contable RT6 FACPCE: preparación de EECC reexpresados | Contador público / CFO | Claude |
| 30 | Contabilidad | Declaración jurada de ganancias personas jurídicas: formulario 713, deducciones | Contador / Asesor impositivo | Claude |
| 31 | Contabilidad | Liquidación de IVA mensual PyME: crédito fiscal, débito fiscal, regímenes especiales | Contador / Dueño PyME | Claude |
| 32 | Contabilidad | Monotributo: recategorización, actividades mixtas, factura electrónica AFIP | Profesional / Comerciante | Claude |
| 33 | Legal concurso | Concurso preventivo de acreedores: Ley 24.522, presentación al juez, acuerdo | Abogado / CEO en crisis | Claude |
| 34 | Legal INPI | Registro de marca en Argentina e internacional (Protocolo de Madrid) vía INPI | Abogado / Emprendedor | Claude |
| 35 | Legal contratos | Contrato de locación: Ley de Alquileres vigente, índice ICL, cláusulas protectoras | Abogado / Inmobiliaria | Claude |
| 36 | Legal PJN | Presentación judicial electrónica (PJN): sistema de gestión de causas, escritos | Abogado litigante | Claude |
| 37 | Legal laboral | Despido y liquidación final: Ley de Contrato de Trabajo 20.744 — cálculo indemnización | Abogado laboral / RRHH | Claude |
| 38 | Construcción | Licitación de obra pública: INVICO/IERIC, presentación de oferta, RUPE AFIP | Constructora / Estudio | Claude |
| 39 | Construcción | PROCREAR: gestión de crédito hipotecario subsidiado, etapas constructivas | Familia beneficiaria / Arq. | Claude |
| 40 | Construcción | Dirección de obra: certificaciones de avance, libro de órdenes, entregas parciales | Director de obra / Arq. | Claude |
| 41 | Construcción | Permisos municipales: visado de planos, cómputo y presupuesto, habilitación final | Arquitecto / Constructor | Claude |
| 42 | Salud PAMI | Gestión de prestaciones PAMI: prescripción, cobertura 100%, medicamentos crónicos | Médico clínico / Farmacia | Claude |
| 43 | Salud obras sociales | Auditoría médica de obra social sindical: facturación, glosas, apelaciones ante la SSS | Auditor médico / Clínica | Claude |
| 44 | Salud prepaga | Prepaga: cobertura PMO, autorizaciones de cirugías, amparo judicial por cobertura | Paciente / Abogado salud | Claude |
| 45 | Salud telemedicina | Telemedicina: regulación Ley 27.553, prescripción electrónica, receta digital | Médico / Plataforma salud | Claude |
| 46 | Salud mental | Ley de Salud Mental 26.657: internación voluntaria/involuntaria, derechos del paciente | Psiquiatra / Trabajador social | Claude |
| 47 | Salud laboratorio | Habilitación de laboratorio clínico ANMAT: GMP, control de calidad, registro productos | Director técnico / ANMAT | Claude |
| 48 | Educación UBA | Cursada en UBA CBC: materias, profesores recomendados, estrategias de aprobación | Estudiante universitario | Claude |
| 49 | Educación Progresar | Beca Progresar: requisitos, renovación, compatibilidad con trabajo part-time | Estudiante becario | Claude |
| 50 | Educación MBA | MBA en Argentina: IAE/UTDT/Di Tella — admisión, becas, ROI de la inversión | Profesional / Aspirante | Claude |
| 51 | Educación online | Plataforma de cursos online en Argentina: Xubio/Crehana/Udemy en ARS — validación | Creador de contenido edtech | Claude |
| 52 | Educación técnica | Escuela técnica INET: articulación con industria, pasantías remuneradas, certificación | Rector / Coordinador técnico | Claude |
| 53 | Turismo Bariloche | Posicionamiento de Bariloche en mercado internacional: esquí, trekking, gastronomía | Operador turístico | Claude |
| 54 | Turismo Patagonia | Turismo de aventura en Patagonia: ruta de los parques, lodge sostenible, turismo lento | Agencia / Lodge | Claude |
| 55 | Turismo Iguazú | Cataratas del Iguazú: tour operador, circuito argentino/brasileño, experiencia nocturna | Guía / Operadora | Claude |
| 56 | Turismo enoturismo | Ruta del Vino Mendoza: itinerario premium, bodegas boutique, posicionamiento global | Agencia enoturismo | Claude |
| 57 | Turismo MICE | Buenos Aires como destino de congresos: propuesta para eventos internacionales | Venue / Agencia MICE | Claude |
| 58 | Gastronomía asado | Asado argentino como marca global: clase online, kit de exportación, comunidad | Parrillero / Chef | Claude |
| 59 | Gastronomía delivery | PedidosYa: optimización de menú, fotografía, ranking de restaurante, gestión de reseñas | Restaurante / Delivery | Claude |
| 60 | Gastronomía emprendimiento | Emprendimiento gastronómico: habilitación municipal, bromatología, seguro de responsabilidad | Emprendedor gastro | Claude |
| 61 | Energía RENOVAR | Proyectos RENOVAR: parque solar/eólico, contrato CAMMESA, FODER — estructura | Desarrollador energético | Claude |
| 62 | Energía hidrógeno verde | Hidrógeno verde: producción en Vaca Muerta zona de transición, exportación a Europa | Empresa energética / IEASA | Claude |
| 63 | Energía Vaca Muerta | Gas natural Vaca Muerta: ENARGAS, Plan GasAr, gasoducto Néstor Kirchner — estructura | Petrolera / Operador | Claude |
| 64 | Energía eficiencia | Auditoría energética PyME: IECEE, diagnóstico de consumo, reducción de factura eléctrica | Ingeniero / PyME industrial | Claude |
| 65 | Energía solar domiciliaria | Instalación solar residencial: net metering, conexión EDENOR/EDESUR, subsidios | Instalador solar / Hogar | Claude |
| 66 | Minería cobre | Cobre en San Juan: CONICET mapa geológico, proyecto JOSEMARÍA/Los Azules — fases | Empresa minera / Geólogo | Claude |
| 67 | Minería oro | Minería de oro Patagonia: Yamana/Patagonia Gold — proceso de obtención de permisos | Geólogo / Inversor minero | Claude |
| 68 | RRHH LFT | Liquidación de sueldos: Ley de Contrato de Trabajo, CCT por actividad, SUNA AFIP | Liquidador de sueldos / RRHH | Claude |
| 69 | RRHH CCT | Negociación de convenio colectivo de trabajo: UOM/UOCRA/FAECYS — paritaria | Gerente RRHH / Dirigente | Claude |
| 70 | RRHH teletrabajo | Ley de Teletrabajo 21.220: equipamiento, conectividad, reversibilidad, expatriados | RRHH / Empresa tech | Claude |
| 71 | RRHH selección | Selección de personal tech en Argentina: assessment técnico, salary bands en USD | Recruiter / Manager | Claude |
| 72 | RRHH capacitación | Plan de capacitación corporativa: REPRO/FOCEA MTESS — subsidios para formación | RRHH / Gerente capacitación | Claude |
| 73 | Cultura cine | Fondo Nacional de las Artes / INCAA: concurso de proyectos, coproducción internacional | Cineasta / Productor | Claude |
| 74 | Cultura música | Mercado de la música argentina: SADAIC, CAPIF, streaming — derechos y royalties | Músico / Manager artístico | Claude |
| 75 | Cultura editorial | Editorial independiente argentina: derechos de autor, ISBN, distribución LatAm | Editor / Escritor | Claude |
| 76 | Mercado Libre | Vender en Mercado Libre Argentina: Mercado Shops, Full/Flex, reputación, anuncios | Vendedor e-commerce | Claude |
| 77 | Mercado Libre | Mercado Pago para PyME: QR, link de pago, PDV, financiamiento PyME digital | Dueño de negocio | Claude |
| 78 | Mercado Libre | MercadoLibre internacionalización: vender desde Argentina a Brasil/México/Colombia | Exportador digital | Claude |
| 79 | Exportaciones | Exporta Simple: exportación de bienes hasta USD 15.000/operación — operatoria completa | Artesano / PyME exportadora | Claude |
| 80 | Exportaciones | Drawback: recupero de aranceles de importación de insumos usados en exportación | Exportador industrial | Claude |
| 81 | Exportaciones | Exportación de servicios: contrato en inglés, cobro por PayPal/Wise/transferencia SWIFT | Freelance / Consultora | Claude |
| 82 | Exportaciones | Plan exportador PyME: AAICI, ProArgentina, ferias internacionales financiadas | Gerente comercial PyME | Claude |
| 83 | Ambiente REP | Ley de Responsabilidad Extendida del Productor (REP): envases, RAEE, neumáticos | Director ambiental / Empresa | Claude |
| 84 | Ambiente economía circular | Economía circular en producción industrial: residuos cero, simbiosis industrial | Gerente de planta / ONG | Claude |
| 85 | Ambiente aguas | Gestión de efluentes industriales: Ley 24.051 residuos peligrosos, habilitación provincial | Director ambiental | Claude |
| 86 | Ambiente certificación | Certificación ISO 14001 en empresa argentina: proceso, costos, beneficios comerciales | Consultor ambiental | Claude |
| 87 | Municipios GCBA | Trámites digitales GCBA: habilitación comercial, BAP, sistema SUTERH para PH | Comerciante / Propietario | Claude |
| 88 | Municipios | Smart city municipios del interior: app municipal, digitalización de trámites locales | Intendente / Secretario | Claude |
| 89 | Municipios | Presupuesto participativo: herramienta de consulta ciudadana digital, IA moderadora | Municipio / ONG | Claude |
| 90 | Salud nutrición | Nutrición clínica: planes alimentarios, cálculo de macros, interacción fármacos-alimentos | Nutricionista / Dietista | Claude |
| 91 | Agro tecnología | AgTech startup argentina: mercado de IoT agrícola, sensores, telemetría de campos | Fundador AgTech | Claude |
| 92 | Logística | Logística de última milla en CABA: OCA/Andreani vs startups (Zippin/Mensajeros Urbanos) | E-commerce / Logística | Claude |
| 93 | Logística | Cadena de frío en alimentos: transporte refrigerado, SENASA habilitación, monitoreo IoT | Industria alimentaria | Claude |
| 94 | Educación | Tutorías en IA para secundaria: incorporación de Claude/ChatGPT en la escuela pública | Docente / Director escolar | Claude |
| 95 | Fintech | Crowdfunding de inversión: plataformas BYMA habilitadas (Crowdium/Crowdar) — inversión | Inversor minorista / Empresa | Claude |
| 96 | Seguros | Microseguros para informales: seguros de vida/celular para monotributistas, plataformas | Broker de seguros / Fintech | Claude |
| 97 | Agro | Seguro agrícola: seguros multirriesgo La Segunda/El Comercio, índice climatológico | Productor / Broker agro | Claude |
| 98 | Industria | PyME manufacturera: reconversión productiva con automatización, créditos FONTAR MINCYT | Dueño de fábrica | Claude |
| 99 | Salud | Salud ocupacional: ART (Aseguradora de Riesgos del Trabajo) — prevención, siniestros | RRHH / Médico laboral | Claude |
| 100 | Tech | Ciberseguridad empresas argentinas: CERT.ar, ley de delitos informáticos 26.388, SOC | CISO / IT Manager | Claude |
| 101 | Agro | Industria láctea: precio de leche cruda SIGLEA, exportación polvo de leche/quesos | Tambero / Industrial lácteo | Claude |
| 102 | Finanzas | Mercado de capitales PyME: ON PyME (obligaciones negociables), BYMA, inversores | CFO PyME / Asesor financiero | Claude |
| 103 | Turismo | Cruceros Buenos Aires: puerto, itinerario Patagonia, régimen duty-free turismo | Operador náutico / Puerto | Claude |
| 104 | Educación | Universidad virtual argentina: UADE/UBA XXI/Siglo 21 — estructura de curso online | Docente universitario | Claude |
| 105 | Ambiente | Litio y ambiente: audiencias públicas, monitoreo de acuíferos, compensación comunitaria | ONG / Empresa minera | Claude |
| 106 | Industria | Economía del hidrógeno: uso del gas Vaca Muerta para H2 verde-azul, exportación | Empresa energética | Claude |
| 107 | Agro | Miel y apicultura Argentina: exportación a UE, trazabilidad, denominación de origen | Apicultor / Cooperativa | Claude |
| 108 | Tech | Inteligencia Artificial en banca argentina: scoring crediticio, chatbots, prevención fraude | Banco / Fintech | Claude |
| 109 | Cultura | Contenido cultural en español: podcasts, newsletters, YouTube — monetización regional | Creador de contenido | Claude |
| 110 | Gobierno | Modernización del Estado argentino: expediente electrónico GDE, firma digital, interoperabilidad | Funcionario público / Consultora | Claude |
| 111 | Agro | Soja no GMO y certificada: mercados premium Europa, trazabilidad blockchain, precio diferencial | Productor / Exportador | Claude |
| 112 | Tech | No-code / Low-code en PyMEs argentinas: Bubble, Make, Airtable — automatización sin desarrollador | PyME / Consultor digital | Claude |
| 113 | Finanzas | Reestructuración de deuda soberana: análisis de bonos en USD (GD30/AL30/BONAR) para inversores | Asesor financiero / Bonista | Claude |

---

## Recursos Clave para Argentina

### Organismos y Plataformas Regulatorias
- **AFIP** (afip.gob.ar): Portal fiscal, factura electrónica, DJVE, importaciones/exportaciones
- **BCRA** (bcra.gob.ar): Regulaciones cambiarias, tasas de referencia, normativa fintech
- **SENASA** (senasa.gob.ar): Certificados sanitarios y fitosanitarios, habilitación de establecimientos
- **INTA** (inta.gob.ar): Investigación agropecuaria, variedades, extensión rural
- **INPI** (inpi.gob.ar): Registro de marcas, patentes, modelos de utilidad
- **ANMAT** (anmat.gob.ar): Habilitación de medicamentos, alimentos, dispositivos médicos
- **SEPYME** (sepyme.gob.ar): Registros PyME, Ley de Economía del Conocimiento, beneficios
- **BYMA** (byma.com.ar): Bolsa de valores, ON PyME, Cedears, cheques diferidos
- **MATBA-ROFEX** (matbarofex.com.ar): Futuros y opciones agropecuarias
- **CAMMESA** (cammesa.com.ar): Mercado eléctrico mayorista, contratos de energía renovable

### Herramientas de IA Recomendadas para Argentina
- **Claude** (claude.ai): Análisis regulatorio, redacción de contratos, estrategia empresarial
- **ChatGPT** (chatgpt.com): Contenido en español, automatización, soporte al cliente
- **Gemini** (gemini.google.com): Integración Google Workspace, análisis de datos
- **Perplexity** (perplexity.ai): Investigación de normativa actualizada, precios de commodities

### Normativa Clave Vigente
| Norma | Descripción |
|-------|-------------|
| Ley 27.506 | Economía del Conocimiento (software, servicios digitales) |
| Ley 27.742 | RIGI — Régimen de Incentivo a Grandes Inversiones (minería, energía) |
| Ley 21.220 | Teletrabajo — modalidades, equipamiento, reversibilidad |
| Ley 20.744 | Ley de Contrato de Trabajo — relación laboral, indemnizaciones |
| Ley 24.522 | Concursos y Quiebras — reestructuración de deuda empresarial |
| Ley 27.499 | Ley Micaela — capacitación en género en el Estado |
| Ley 25.675 | Ley General del Ambiente — evaluación de impacto ambiental |
| RT 6 FACPCE | Ajuste por inflación contable en estados financieros |

---

*Documento creado con fines educativos para profesionales y empresas en Argentina.*
*Actualizado: 2026 | Maestros AI — maestrosai.com*
