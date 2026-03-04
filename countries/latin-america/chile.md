# Casos de Uso de IA para Chile
## Guía Completa: 110+ Casos de Uso Prácticos

> **Creado por Adrian Dunkley** | Experto Regional en IA | [maestrosai.com](https://maestrosai.com) | ceo@maestrosai.com
> *Uso Justo — Recurso Educativo*

---

## Chile en Cifras

| Indicador | Dato |
|-----------|------|
| Población | 19.5 millones |
| PIB | US$ 360 mil millones |
| PIB per cápita | ~US$ 18,500 (mayor en LatAm) |
| Moneda | Peso Chileno (CLP) |
| Idioma | Español |
| Capital | Santiago |
| Hubs tech | Santiago, Valparaíso, Concepción |
| Exportaciones | Cobre, litio, vino, salmón, fruta, celulosa |
| TLCs vigentes | 30+ tratados de libre comercio |
| Unicornios / escaleups | NotCo, Cornershop, Betterfly, Fintual, Caja Vecina |
| Marco IA | Política Nacional de Inteligencia Artificial (2021, actualizada 2024) |

---

## Sector 1: Minería — Cobre, Litio y Pequeña Minería

### Caso de Uso 1: Codelco — Optimización de Mina Rajo Abierto y Subterránea
**Rol**: Ingeniero de minas / Planificador de producción / Gerente de operaciones Codelco
**Herramienta de IA**: Claude

**Estructura del Prompt**:
```
Trabajo en una operación minera de cobre en [Chuquicamata/El Teniente/Andina/El Salvador/Radomiro Tomic].
Tipo de mina: [rajo abierto/subterránea/combinada]. Ley de mineral: [X% Cu].
Producción objetivo: [X toneladas métricas de cobre fino/año].
Equipamiento: [camiones 400T Komatsu/Caterpillar/perforadoras Sandvik/Atlas Copco].
Sistema de despacho: [Wenco/Dispatch/Jigsaw]. Procesamiento: [flotación/lixiviación-SX-EW].
Desafíos actuales: [leyes decrecientes/mayor profundidad/eficiencia energética/agua].

Optimiza la operación minera con IA:
- Planificación de producción: modelo de bloques, secuencia de extracción, optimización de pit (Whittle)
- Despacho de camiones con IA: algoritmos de asignación en tiempo real, reducción de tiempos muertos
- Mantenimiento predictivo: análisis de vibraciones en camiones/correas, predicción de fallas antes de parada
- Perforación y tronadura: diseño de malla óptima por tipo de roca, factor de potencia, fragmentación
- Procesamiento metalúrgico: control de planta de flotación con ML — ajuste de reactivos en tiempo real
- Gestión del agua: uso de agua de mar desalada, recirculación, cumplimiento DGA (Dirección General de Aguas)
- Energía: curva de demanda eléctrica, peak shaving, PPAs de energía solar para operación
- Seguridad: detección de fatiga con cámaras IA, zonificación de riesgos, análisis de incidentes
- Medio ambiente: monitoreo de polvo PM2.5/PM10, control de ruido, SMA (Superintendencia del Medio Ambiente)
- Reporte ESG: métricas GRI/ICMM, huella de carbono scope 1/2/3, objetivos de descarbonización Codelco
```
**Beneficios**: Reducción de costos operativos C1, mejora de recuperación metalúrgica, cumplimiento ambiental y ESG

---

### Caso de Uso 2: SQM — Litio del Salar de Atacama
**Rol**: Gerente de operaciones SQM / Ingeniero de procesos / Analista de mercado litio
**Herramienta de IA**: Claude

**Estructura del Prompt**:
```
Trabajo en el negocio de litio del Salar de Atacama (Región de Antofagasta).
Contrato: SQM-CORFO (actualizado 2018) — producción hasta 2030.
Productos: carbonato de litio (Li2CO3) / hidróxido de litio (LiOH).
Capacidad actual: [X toneladas LCE/año]. Plan de expansión: [X toneladas].
Clientes: fabricantes de baterías EV [Tesla/CATL/Panasonic/LG Energy Solution].
Precio spot litio: USD [X]/tonelada. Precio contrato largo plazo: USD [X]/tonelada.

Desarrolla estrategia integral para el negocio de litio:
- Optimización de extracción: modelos de evaporación solar, control de salmuera, climatología Atacama
- Calidad de producto: especificaciones Li2CO3 para baterías (grado battery vs técnico), control analítico
- Mercado global: ciclo de precios del litio (boom-bust), cómo estructurar contratos de largo plazo
- Relación con Estado chileno: acuerdo CORFO, royalties, metas de producción, política litio Chile 2023
- Rol CODELCO-litio: alianza estratégica anunciada, posible integración — análisis de impacto
- DLE (Direct Lithium Extraction): tecnología en piloto, ventajas vs evaporación, cronograma comercial
- Agua y comunidades: Convenio 169 OIT, comunidades atacameñas, monitoreo de acuíferos
- Diversificación productos: manufacturar cátodos en Chile — propuesta de valor para atraer inversión
- Portafolio aguas arriba: yodo, potasio, sulfato de manganeso — sinergias en el salar
- Reporte de sostenibilidad: estándares IRMA (Initiative for Responsible Mining Assurance), GRI Minería
```
**Beneficios**: Posicionamiento en cadena de valor de baterías, gestión de relaciones comunitarias, optimización de precio y volumen

---

### Caso de Uso 3: Pequeña Minería — ENAMI y Pirquineros
**Rol**: Pirquinero / Pequeño minero / Técnico ENAMI
**Herramienta de IA**: Claude

**Estructura del Prompt**:
```
Soy [pirquinero/pequeño minero] en [Región de Atacama/Coquimbo/Valparaíso].
Mineral: [oro/cobre/plata]. Método de extracción: [artesanal/semi-mecanizado].
Producción mensual: [X toneladas de mineral]. Ley estimada: [X g/t Au o X% Cu].
Relación con ENAMI: [entrego mineral a planta de ENAMI en [ciudad]].
Organización: [individual/Cooperativa Minera — CORMI].

Ayúdame a mejorar mi operación con ENAMI:
- Entrega de mineral a ENAMI: proceso de recepción, análisis de ley, liquidación de pago
- Crédito ENAMI para pequeños mineros: líneas de crédito en insumos/equipamiento, tasas
- Asistencia técnica ENAMI: servicio de asesoría técnica, análisis de mineral, proyecto de mejora
- Seguridad: SERNAGEOMIN — estándares de seguridad para pirquinería, permisos de operación
- Formalización: concesión de explotación/exploración, inscripción CBR (Conservador de Bienes Raíces)
- Ambiental: EIA simplificada para pequeña minería, manejo de relaves, cierre de faenas
- Cooperativismo: ventajas de CORMI, economías de escala, acceso a financiamiento conjunto
- Mecanización: subsidios CORFO para mecanización de pequeña minería — postulación
- Precio del metal: London Metal Exchange, ajuste ENAMI — cómo maximizar el precio de liquidación
- Diversificación: gemas semipreciosas en zona norte — lapislázuli, atacamita — mercado artesanal
```
**Beneficios**: Mayor precio de liquidación, acceso a crédito, formalización, cumplimiento SERNAGEOMIN

---

## Sector 2: Acuicultura Salmonera

### Caso de Uso 4: Salud de Peces — Caligus, SRS, ISA y Bienestar Animal SERNAPESCA
**Rol**: Médico veterinario acuícola / Gerente de sitio salmonero / Jefe de sanidad
**Herramienta de IA**: Claude

**Estructura del Prompt**:
```
Trabajo en salud de peces en centros de cultivo salmonero en [Los Lagos/Aysén/Magallanes].
Especie: [Salmón Atlántico/Trucha Arcoíris/Coho]. Biomasa: [X toneladas].
Problemas sanitarios actuales: [Caligus/SRS (Piscirickettsiosis)/ISA (Anemia Infecciosa del Salmón)/catarata].
Densidad de cultivo: [X kg/m3]. Tipo de jaula: [circular/cuadrada/semi-sumergible].
Tratamientos: [azametifos/deltametrina/antibióticos (florfenicol/oxitetraciclina)].
Programas SERNAPESCA: [Programa Sanitario Específico de Caligidosis — PSEC].

Optimiza el programa sanitario del centro:
- Monitoreo de Caligus: conteo quincenal SERNAPESCA, umbral de tratamiento, reporte en línea
- Estrategia anti-Caligus: rotación de baños medicados, SLICE (emamectina), sincronización de cosechas
- Prevención SRS: vacunación en agua dulce (Aquavac IPN/Piscirickettsia), reporte serología
- Vigilancia ISA: PCR quincenal, zona de vigilancia, protocolo de mortandad elevada SERNAPESCA
- Bienestar animal: indicadores SERNAPESCA (mortalidad/lesiones/comportamiento), registro en IFOP
- Antibióticos: uso responsable — reporte registro de tratamientos, periodos de resguardo, resistencia
- Densidad y estrés: relación densidad-mortalidad, reducción de biomasa, manejo de cosecha parcial
- Alimentación inteligente: cámaras bajo agua para optimizar alimentación, reducción de FCR
- Ambiental: normas de emisión sedimentos NCH (RAMA), evaluación de fondos marinos SERNAPESCA
- Trazabilidad: sistema SAP/Aquabyte integrado con SERNAPESCA — trazabilidad del pez al plato
```
**Beneficios**: Reducción de mortalidad, menor uso de antibióticos, cumplimiento SERNAPESCA, acceso a mercados premium (certificación ASC/BAP)

---

## Sector 3: Fruticultura y Viticultura

### Caso de Uso 5: Exportación de Fruta Fresca — Protocolo Fitosanitario SAG para EE.UU. y China
**Rol**: Exportador de fruta / Jefe de calidad / Ingeniero agrónomo SAG
**Herramienta de IA**: Claude

**Estructura del Prompt**:
```
Soy [exportador/jefe de calidad] en empresa frutícola en [O'Higgins/Maule/Biobío/Atacama/Coquimbo].
Fruta: [uva de mesa/cerezas/arándanos/paltas/kiwis/ciruelas/manzanas].
Destino: [EE.UU. (APHIS)/China (GACC)/UE (EFSA)/Corea].
Volumen: [X toneladas/temporada]. Temporada: [octubre-marzo].
Certificaciones: [GlobalGAP/PRIMUS/USDA Organic/ninguna].
Packing: [propio/maquilado]. Frío: [atmósfera controlada/frío convencional].

Gestiona la exportación de fruta fresca con protocolo SAG:
- Protocolo de trabajo SAG-APHIS (uva/cereza/arándano): tratamiento en frío certificado, temperaturas y tiempos
- Registro GACC (China): pasos para registro de packing/predio, actualización de listas, coordinación SAG-China
- Residuos de plaguicidas: LMRs por país destino (EE.UU./UE/Japón), monitoreo PERM del SAG
- Plan de manejo de plagas: lobesia botrana (polilla de la vid), mosca de la fruta — zonas cuarentenarias
- GlobalGAP: auditoría, puntos obligatorios vs recomendados, certificadora acreditada en Chile
- Logística de exportación: booking naviero, contenedor refrigerado (reefer), ETD desde San Antonio/Valparaíso
- Cámara de frío: temperatura de pulpa para despacho, control de etileno en CA, registros data logger
- Documentación: Certificado Fitosanitario SAG, lista de empaque, BL, póliza de seguro, factura comercial
- Precios y cobertura: precio en destino (CAD/FOB/CIF), liquidaciones, seguros de precio (collar options)
- Trazabilidad farm-to-fork: QR code en caja, integración con plataformas TraceOne/Sourcemap
```
**Beneficios**: Acceso a mercados de alto precio (cereza China CNY premium), reducción de rechazos en frontera, compliance fitosanitario

---

## Sector 4: Tecnología y Startups

### Caso de Uso 6: Start-Up Chile CORFO — S Factory, Seed y Scale
**Rol**: Fundador de startup / Mentora Start-Up Chile / Asesor CORFO
**Herramienta de IA**: Claude

**Estructura del Prompt**:
```
Soy fundador/a de una startup en etapa [idea/MVP/crecimiento] en [Chile/extranjero queriendo postular].
Sector: [agritech/fintech/healthtech/edtech/climatetech/marketplace].
Equipo: [X cofundadores]. Tracción actual: [usuarios/MRR/contratos pilotos].
Programa objetivo: [S Factory (pre-semilla mujeres)/Seed (USD 100K)/Scale (USD 150K+)].
Situación legal: [SpA constituida/por constituir/empresa extranjera].

Guíame en la postulación a Start-Up Chile:
- Programas disponibles: S Factory (enfoque femenino), Seed (general, USD 100K no dilutivo), Scale (escalamiento), Backbone (impacto social)
- Requisitos de elegibilidad: domicilio en Chile, equipo residente, sectores priorizados
- Formulario de postulación: cómo responder cada sección — problema, solución, mercado, equipo, tracción
- Equity: Start-Up Chile no toma equity — ventaja vs aceleradoras privadas
- Compromiso de permanencia: tiempo en Chile durante el programa, oficinas Campus Beauchef/Santiago
- Constitución SpA digital: Registro de Empresas y Sociedades (RES), costo cero, trámite online
- Financiamiento complementario: CORFO Capital Semilla, ICT (Instrumento Capital Temprano), FOGAPE digital
- Mentores y red: acceso a red de alumni, Demo Day, conexión con fondos VC latinoamericanos
- Visa tecnológica: visa de trabajo para fundadores extranjeros — proceso consulado chileno
- Post-programa: cómo mantener el estatus en Chile, acceso a nuevas convocatorias CORFO
```
**Beneficios**: USD 100K-150K sin diluir equity, red de mentores, visibilidad internacional, ecosistema Santiago

---

## Sector 5: Gobierno Digital

### Caso de Uso 7: ChileAtiende, ClaveÚnica y Ley 21.180 de Digitalización
**Rol**: Funcionario público / Jefe de servicio digital / Ciudadano
**Herramienta de IA**: Claude

**Estructura del Prompt**:
```
Trabajo en [ministerio/servicio público/municipalidad] implementando la Ley 21.180 de Transformación Digital.
Área: [trámites ciudadanos/gestión documental/interoperabilidad entre servicios].
Estado actual: [expediente electrónico/ventanilla única digital/integración ClaveÚnica].
Usuarios que atendemos: [X ciudadanos/mes]. Trámites digitalizados: [X de Y totales].
Plataformas: [Portal ChileAtiende/SIMPLE SEGPRES/Mercado Público].

Implementa la transformación digital del servicio público:
- Ley 21.180: obligaciones por tipo de servicio, plazos de implementación, excepciones
- ClaveÚnica: integración API para autenticación ciudadana, casos de uso, seguridad
- ChileAtiende: publicación de trámites en catálogo, actualización de información, canal presencial/digital
- SIMPLE (SEGPRES): plataforma de gestión documental del Estado — expediente electrónico
- Interoperabilidad: plataforma de integración PISEE — consulta de datos entre servicios sin pedir documentos
- Cero papel: eliminación de documentos físicos, firma electrónica avanzada (FEA), registro civil digital
- Accesibilidad: WCAG 2.1 para sitios web del Estado, brecha digital en adultos mayores y zonas rurales
- Datos abiertos: portal datos.gob.cl — publicación de datasets en formato abierto, licencia
- IA en servicios públicos: chatbots en ChileAtiende, automatización de respuestas SDA, moderación
- Evaluación: NPS del trámite digital, tiempo promedio de resolución, tasa de abandono digital
```
**Beneficios**: Reducción de burocracia, ahorro de tiempo ciudadano, transparencia, cumplimiento legal Ley 21.180

---

## Sector 6: Energías Renovables

### Caso de Uso 8: Solar Atacama y Hidrógeno Verde Haru Oni Magallanes
**Rol**: Desarrollador de energía renovable / Ingeniero eléctrico / Ejecutivo de proyecto H2V
**Herramienta de IA**: Claude

**Estructura del Prompt**:
```
Trabajo en desarrollo de energía renovable en Chile.
Proyecto A — Solar: [Región de Antofagasta/Atacama]. GHI: [8-9 kWh/m2/día, mayor del mundo].
Tecnología: [bifacial/tracker/perovskita]. Capacidad: [X MWp]. Contrato: [PPA/spot/empresa consumidora].
Proyecto B — Hidrógeno Verde: [Magallanes/Antofagasta]. Recurso: [viento Patagonia/solar Atacama].
Electrolizador: [PEM/alcalino]. Capacidad H2: [X toneladas/día]. Destino: [exportación Europa/uso local amoniaco].

Desarrolla el proyecto de energía renovable en Chile:
- Evaluación de recurso solar: NASA POWER, SOLARGIS, medición in situ — bankabilidad del recurso
- Permiso ambiental (DGA/CONAF/SMA): EIA o DGA para proyectos sobre 3MW, plazos, participación ciudadana
- SERNAGEOMIN: para proyectos en zona minera o con movimiento de tierras
- Contratos PPA: estructura, indexación (IPC/USD), plazo (10-20 años), off-taker crediticio
- Licitaciones CNE: licitaciones de suministro eléctrico — cómo calcular el precio de oferta competitivo
- Financiamiento: project finance BID/IFC/DEG/KfW, CORFO líneas de financiamiento ERNC
- Red eléctrica SEN: capacidad de conexión al sistema, peajes de transmisión, capacidad de evacuación
- Hidrógeno verde: estrategia nacional H2V Chile 2050 — exportación verde, certificados de origen
- Haru Oni (HIF Global): modelo de referencia en Magallanes — e-fuels (e-methanol, e-kerosene)
- Amoniaco verde: síntesis Haber-Bosch con H2V, exportación Asia-Pacífico, demanda 2030
```
**Beneficios**: Acceso a LCOE más bajo del mundo (solar Atacama), posicionamiento en mercado de H2 verde, financiamiento internacional

---

## Casos de Uso 9–113: Tabla de Referencia Rápida

| # | Sector | Caso de Uso | Rol Principal | Herramienta |
|---|--------|-------------|---------------|-------------|
| 9 | Minería oro | Minería artesanal de oro: ENAMI, uso de borax en lugar de mercurio, certificación responsable | Pirquinero / ONG ambiental | Claude |
| 10 | Minería manganeso | Manganeso Atacama: proceso de beneficio, mercado asiático, logística Antofagasta | Empresa minera / Exportador | Claude |
| 11 | Minería drones | Topografía con drones en minería: autorización DGAC, modelo 3D de rajo, volumen de stock | Topógrafo / Empresa drones | Claude |
| 12 | Minería cobre refinado | Refinería de cobre: ENAMI/Codelco, producción de cátodos LME grado A, exportación | Ingeniero metalúrgico | Claude |
| 13 | Agro hidroponía | Hidroponía en invernadero: lechuga/tomate cherry, venta directa a supermercados Santiago | Agricultor / Agrónomo | Claude |
| 14 | Agro orgánicos | Certificación orgánica SAG Chile: norma técnica, OAC (organismo de certificación acreditado) | Agricultor orgánico | Claude |
| 15 | Agro quinoa | Quinoa altiplánica: denominación de origen, exportación a Europa, comunidades aymara | Productor / INDAP | Claude |
| 16 | Agro ganadería | Ganadería ovina en Patagonia: lana premium Magallanes, exportación a Italia/España | Ganadero / Cooperativa | Claude |
| 17 | Agro apicultura | Miel de ulmo certificada: exportación a Alemania, denominación de origen, certificado SAG | Apicultor / Exportador | Claude |
| 18 | Agro pisco | Pisco chileno DO: denominación de origen Atacama/Coquimbo, exportación, diferenciación vs Perú | Pisquero / Exportador | Claude |
| 19 | Agro cerezas | Cerezas para China: protocolo GACC, manejo de frío, despacho aéreo/marítimo diciembre | Exportador de cerezas | Claude |
| 20 | Agro celulosa | Celulosa Arauco/CMPC: ciclo forestal pino/eucalipto, mercado Asia/Europa, huella carbono | Forestal / Ingeniero | Claude |
| 21 | Agro INDAP | Crédito INDAP para pequeño agricultor: largo plazo, corto plazo, bono fomento riego | Agricultor / Consultor INDAP | Claude |
| 22 | Agro CONAF | CONAF Programa Forestación: bonificación DL 701 (proyectos vigentes), recuperación suelos | Forestal / Propietario predio | Claude |
| 23 | Agro seguro | Seguro agrícola CORFO-Agroseguros: siniestro por helada/sequía/granizo, tramitación | Agricultor / Broker seguros | Claude |
| 24 | Energía eficiencia | Ley de Eficiencia Energética 20.936: grandes consumidores, SGEN, reportes anuales a SEC | Empresa industrial / AGC | Claude |
| 25 | Energía geotermia | Geotermia en Chile: concesiones CNE, proyectos Cerro Pabellón (ENEL/ENAP), tarifa | Empresa energética / CNE | Claude |
| 26 | Energía mini-hidro | Mini-hidroeléctricas en zona sur: DGA caudal ecológico, permiso SERNAGEOMIN, PMGD | Generador distribuido | Claude |
| 27 | Energía eólica | Eólica en Atacama: factor de planta mayor al 40%, curva de viento, conexión SEN norte | Desarrollador eólico | Claude |
| 28 | Energía comunidades | Energía comunitaria: cooperativas de energía solar, net metering residencial (Ley 20.936) | Cooperativa / Municipio | Claude |
| 29 | Finanzas AFP | AFP Chile: rentabilidad histórica por fondo (A-E), estrategia de multifondos, traspaso | Trabajador / Asesor previsional | Claude |
| 30 | Finanzas FIP | FIP (Fondos de Inversión Privados): estructura, ventajas tributarias para family office | Abogado / Gestor inversiones | Claude |
| 31 | Finanzas CMF | CMF (Comisión para el Mercado Financiero): regulación de valores, normas de conducta | Compliance officer / Banco | Claude |
| 32 | Finanzas Ley Fintech | Ley Fintech 21.521: open banking, proveedores de servicios financieros, CMF autorización | Fintech / Abogado regulatorio | Claude |
| 33 | Finanzas Fintual | Fondo de inversión automatizado: Fintual, Buda, ComparaOnline — estrategia ahorro/inversión | Inversionista retail | Claude |
| 34 | Finanzas seguros | Seguros en Chile: CMF, seguros de vida/salud/SOAP, comparación de pólizas, liquidación | Broker seguros / Asegurado | Claude |
| 35 | Finanzas portabilidad | Portabilidad financiera (Ley 21.236): traslado de crédito hipotecario entre bancos sin costo | Deudor hipotecario | Claude |
| 36 | Finanzas SII F22 | Declaración de renta F22 SII: créditos, dividendos, segunda categoría, devolución | Contribuyente / Contador | Claude |
| 37 | Finanzas IVA | IVA en Chile: declaración mensual F29, crédito fiscal, débito fiscal, emisión de boletas | Empresa / Contador | Claude |
| 38 | Finanzas startup | Valorización de startup chilena: método Berkus/Scorecard, DCF para pitch VC | Founder / Analista VC | Claude |
| 39 | Salud FONASA | FONASA: bonificación por tramo, Libre Elección, MLE — cómo optimizar el uso del seguro | Paciente / Profesional salud | Claude |
| 40 | Salud ISAPRE GES | ISAPRE y GES (Garantías Explícitas en Salud): 85 enfermedades garantizadas, reclamación | Afiliado ISAPRE / Abogado | Claude |
| 41 | Salud telemedicina | Telemedicina en Chile: Ley 21.541, plataformas médicas digitales, interconsulta remota | Médico / Plataforma salud | Claude |
| 42 | Salud mental | Ley de Salud Mental 21.331: derechos del paciente, internación voluntaria/involuntaria, COSAM | Psiquiatra / Trabajador social | Claude |
| 43 | Salud ISP | ISP bioequivalencia: registro sanitario de medicamentos genéricos, pruebas de equivalencia | Laboratorio farmacéutico | Claude |
| 44 | Salud FONASA dental | Dental FONASA: Plan de Salud Oral garantizado, ortodoncia, convenios municipales | Dentista / Paciente | Claude |
| 45 | Salud nutrición | Ley de Etiquetado de Alimentos (20.606): octógonos de advertencia, publicidad, restricciones | Nutricionista / Empresa alimentos | Claude |
| 46 | Educación PAES | PAES (Prueba de Acceso a la Educación Superior): preparación matemáticas/lectura/ciencias | Estudiante / Tutor | Claude |
| 47 | Educación JUNAEB | JUNAEB: beca alimentación/útiles/lentes/hospedaje — postulación y renovación | Estudiante / Apoderado | Claude |
| 48 | Educación MECESUP | MECESUP (Mejoramiento de la Calidad de la Educación Superior): proyecto de vinculación | Académico / Universidad | Claude |
| 49 | Educación gratuidad | Gratuidad universitaria: requisitos socioeconómicos, universidades acreditadas, DEMRE | Estudiante / Orientador | Claude |
| 50 | Educación INACAP | INACAP y CFT (Centros de Formación Técnica): becas técnicas, demanda laboral por carrera | Estudiante técnico | Claude |
| 51 | Educación dual | Formación dual: empresa-institución, convenio MTP (Marco de Titulación Profesional) | Empresa / OTEC | Claude |
| 52 | Educación IA | IA en el aula: uso de Claude/ChatGPT en liceos técnicos, política MINEDUC 2024 | Docente / Director escolar | Claude |
| 53 | Turismo Patagonia | Parques Patagonia: Torres del Paine/Cerro Castillo — turismo sostenible, cap de visitantes | Operador turístico / CONAF | Claude |
| 54 | Turismo San Pedro | San Pedro de Atacama: turismo astronómico, astroturismo, paquetes premium internacionales | Agencia turismo / Hotel | Claude |
| 55 | Turismo MICE | Santiago como destino MICE: CasaPiedra/Espacio Riesco, convenciones internacionales | Agencia eventos / Hotel | Claude |
| 56 | Turismo ski | Ski Chile: Valle Nevado/Portillo — mercado sudamericano e internacional, temporada junio-octubre | Resort / Operador turístico | Claude |
| 57 | Turismo agroturismo | Agroturismo en el sur de Chile: Chiloé/Región de Los Lagos, turismo de naturaleza | Productor / Agencia | Claude |
| 58 | Turismo SERNATUR | SERNATUR: registro de prestadores, calificación turística, marketing destino Chile | Operador turístico | Claude |
| 59 | Turismo cruceros | Cruceros Patagonia: Puerto Montt/Punta Arenas — logística portuaria, experiencia en tierra | Agencia receptiva / Puerto | Claude |
| 60 | Retail Falabella | Falabella e-commerce: marketplace, CMR Puntos, logística Linio/Falabella.com | Marca / Vendedor marketplace | Claude |
| 61 | Retail Mercado Libre | MercadoLibre Chile: categorías más vendidas, fulfillment, publicidad MLA | Vendedor online | Claude |
| 62 | Retail logística | Beetrack logística: routing de última milla, integración API, indicadores de entrega | Empresa logística / E-commerce | Claude |
| 63 | Retail puerto | Puerto San Antonio/Valparaíso: importación contenedores, tramitación aduana, SAP | Importador / Agente de aduana | Claude |
| 64 | Retail moderno | Supermercados Cencosud/SMU/Walmart Chile: condiciones de ingreso de productos, negociación | Proveedor PyME / Broker retail | Claude |
| 65 | Legal INAPI | Propiedad intelectual INAPI: registro de marcas nacionales, patentes de invención, diseños | Abogado / Empresa innovadora | Claude |
| 66 | Legal mediación | Centro de Arbitraje y Mediación (CAM Santiago): arbitraje comercial, cláusula arbitral | Abogado / Empresa | Claude |
| 67 | Legal SERNAC | SERNAC: denuncia de consumidor, mediación colectiva, Ley del Consumidor 19.496 | Consumidor / Empresa | Claude |
| 68 | Legal datos | Ley de Datos Personales 19.628 (nueva versión): compliance, DPO, multas, derechos ARCO | Compliance officer / Abogado | Claude |
| 69 | Legal societario | Constitución SpA digital: RES, estatutos, distribución de acciones, acuerdo de accionistas | Abogado / Fundador | Claude |
| 70 | Legal laboral | Código del Trabajo Chile: contrato, finiquito, horas extra, fuero maternal | Abogado laboral / RRHH | Claude |
| 71 | Ambiente REP | Ley REP 20.920: gestión de envases/neumáticos/aparatos electrónicos — planes de gestión | Empresa / Gestor ambiental | Claude |
| 72 | Ambiente parques | Parques nacionales CONAF: concesiones turísticas, guías de montaña, pago de entrada | CONAF / Concesionario | Claude |
| 73 | Ambiente carbono azul | Carbono azul en manglares/kelp: metodología Verra, créditos de carbono azul, Chile | ONG / Empresa pesquera | Claude |
| 74 | Ambiente economía circular | Economía circular en industria: reciclaje industrial, residuos como insumos, reporting ESG | Director ambiental / PyME | Claude |
| 75 | Ambiente agua | DGA (Dirección General de Aguas): derechos de agua, traslados, caducidades, Ley 21.435 | Abogado aguas / Agrícola | Claude |
| 76 | RRHH código trabajo | Código del Trabajo: jornada laboral 40 horas (Ley 21.561), distribución, banco de horas | RRHH / Abogado laboral | Claude |
| 77 | RRHH teletrabajo | Ley Teletrabajo 21.220: contrato especial, desconexión digital, equipamiento empresa | RRHH / Manager | Claude |
| 78 | RRHH AFP APV | APV (Ahorro Previsional Voluntario): régimen A/B, beneficio tributario, fondos disponibles | Trabajador / Asesor financiero | Claude |
| 79 | RRHH selección | Reclutamiento con IA: screening de CVs, entrevistas asistidas, bias algorítmico y ética | Recruiter / RRHH | Claude |
| 80 | RRHH expatriados | Visa de trabajo para extranjeros: PDTEG (técnicos especialistas), visa definitiva | RRHH / Trabajador extranjero | Claude |
| 81 | Cultura Fondart | Fondart (Fondo de Desarrollo Cultural): concurso de proyectos, música/artes visuales/cine | Artista / Gestor cultural | Claude |
| 82 | Cultura música | Música chilena: SCD (Sociedad Chilena del Derecho de Autor), royalties, streaming Spotify | Músico / Manager artístico | Claude |
| 83 | Cultura cine | Cine chileno: concurso CORFO-Cine Chile, coproducción internacional, plataformas streaming | Productor audiovisual | Claude |
| 84 | Cultura patrimonio | Patrimonio cultural inmaterial: UNESCO, DIBAM — planes de salvaguardia, comunidades | Gestor cultural / Municipio | Claude |
| 85 | Deporte fútbol | Fútbol chileno: estructura ANFP, licencias de estadio, derechos de televisión, marketing | Club / Directivo deportivo | Claude |
| 86 | Deporte MINDEP | MINDEP (Ministerio del Deporte): fondos concursables, infraestructura deportiva municipal | Federación / Municipio | Claude |
| 87 | Deporte alto rendimiento | Becas MINDEP para atletas de alto rendimiento: criterios, plan de entrenamiento, nutrición | Deportista / Entrenador | Claude |
| 88 | Emergencias SENAPRED | SENAPRED (ex ONEMI): plan de emergencia municipal, sistema de alerta temprana, RRSS | Municipio / Coordinador emergencia | Claude |
| 89 | Emergencias incendios | Incendios forestales: CONAF SNMF, temporada incendios, cortafuegos, drones de vigilancia | CONAF / Bomberos | Claude |
| 90 | Emergencias terremotos | Plan de emergencia ante terremotos: mapa de riesgo sísmico, protocolo empresa, SHOA tsunamis | Empresa / Municipio | Claude |
| 91 | Blockchain | Blockchain en supply chain frutícola: trazabilidad cereza-China con Ethereum/Hyperledger | AgTech / Exportador | Claude |
| 92 | Blockchain | Tokenización de activos inmobiliarios en Chile: marco CMF, inversión fraccionada digital | PropTech / Abogado | Claude |
| 93 | Robótica | Robots en packing agrícola: sistemas de visión, clasificación de fruta, ROI para temporada | AgTech / Empresa packing | Claude |
| 94 | Robótica | Automatización minera: camiones autónomos (Komatsu AHS) en Codelco — integración | Ingeniero minero / Codelco | Claude |
| 95 | Drones DGAC | Drones en Chile: DGAC autorización de vuelo, zonas restringidas, operador UAS certificado | Empresa drones / Piloto | Claude |
| 96 | Drones | Drones en viticultura: monitoreo NDVI, identificación de estrés hídrico, mapa de vigor | Viticultor / Agrónomo | Claude |
| 97 | Política IA | Política Nacional de IA Chile 2021: principios éticos, gobernanza, plan de acción 2022-2026 | Funcionario / Consultor IA | Claude |
| 98 | Política IA | IA ética en el sector público chileno: sesgos algorítmicos, transparencia, accountability | Gobierno / ONG | Claude |
| 99 | Finanzas | Bolsa de Santiago: renta variable, renta fija, fondos mutuos — estrategia de inversión | Inversionista / Corredor | Claude |
| 100 | Finanzas | Hipotecario en UF: indexación, prepago, crédito con subsidio DS 1/DS 49 MINVU | Familia / Banco | Claude |
| 101 | Salud | Medicina de precisión: genómica en Chile, proyecto Genome Chile, oncología personalizada | Médico oncólogo / Investigador | Claude |
| 102 | Educación | Ranking QS universidades chilenas: U Chile/PUC/USACH — investigación, internacionalización | Rector / Académico | Claude |
| 103 | Agro | Vino chileno: certificación Wines of Chile, mercado UK post-Brexit, puntajes especializados | Bodega / Exportador vino | Claude |
| 104 | Logística | Paso Los Libertadores: logística de exportación de fruta hacia Argentina/Brasil por tierra | Transportista / Exportador | Claude |
| 105 | Turismo | Turismo de bienestar: termas, spa rural, circuito wellness en Valparaíso/Araucanía | Operador turismo bienestar | Claude |
| 106 | Construcción | MINVU: subsidio habitacional D.S. 1 para clase media, postulación, constructora habilitada | Familia / Constructora | Claude |
| 107 | Construcción | BIM (Building Information Modeling) en proyectos MOP Chile: Estándar BIM Chile, licitación | Arquitecto / Constructora | Claude |
| 108 | Industria | CORFO: subsidio a la innovación (ITP — Instrumento Tecnológico Productivo), postulación | Empresa industrial / Consultor | Claude |
| 109 | Industria | Plan de transformación digital PyME: CORFO Digitaliza, ERP en la nube, diagnóstico digital | Dueño PyME / Consultor | Claude |
| 110 | Gobierno | Compras públicas Chile: Mercado Público (mercadopublico.cl) — licitaciones, convenio marco | Proveedor del Estado / Empresa | Claude |
| 111 | Pesca | Pesca artesanal: SERNAPESCA, cuota artesanal de merluza/jibia, CALAMAR Magallanes | Pescador artesanal / SERNAPESCA | Claude |
| 112 | Acuicultura | Mejillones y ostras: concesiones acuícolas, SERNAPESCA, mercado gourmet Europa | Acuicultor / Exportador | Claude |
| 113 | Tech | Ciberseguridad en Chile: CSIRT de Gobierno (Ley 21.663), protección de infraestructura crítica | CISO / Empresa | Claude |

---

## Recursos Clave para Chile

### Organismos y Plataformas Regulatorias
- **SII** (sii.cl): Servicio de Impuestos Internos — factura electrónica, renta, IVA, F22
- **CMF** (cmfchile.cl): Comisión para el Mercado Financiero — bancos, seguros, valores
- **SAG** (sag.gob.cl): Servicio Agrícola y Ganadero — sanidad vegetal/animal, exportación
- **SERNAPESCA** (sernapesca.cl): Regulación acuicultura, pesca, bienestar animal acuático
- **SERNAGEOMIN** (sernageomin.cl): Seguridad minera, concesiones, geología
- **DGA** (dga.cl): Derechos de agua, cuencas, Ley de Aguas 21.435
- **CONAF** (conaf.cl): Patrimonio silvestre, incendios forestales, parques nacionales
- **CORFO** (corfo.cl): Fomento productivo, Start-Up Chile, financiamiento, subsidios
- **INAPI** (inapi.cl): Registro de marcas, patentes, variedades vegetales
- **SERNAC** (sernac.cl): Defensa del consumidor, mediaciones, denuncias
- **Mercado Público** (mercadopublico.cl): Compras y licitaciones del Estado
- **CNE** (cne.cl): Comisión Nacional de Energía — tarifas, licitaciones ERNC, regulación

### Herramientas de IA Recomendadas para Chile
- **Claude** (claude.ai): Análisis regulatorio, redacción de contratos, estrategia empresarial
- **ChatGPT** (chatgpt.com): Contenido en español, automatización de procesos, atención al cliente
- **Gemini** (gemini.google.com): Google Workspace, análisis de datos, Maps para logística
- **Perplexity** (perplexity.ai): Investigación de normativa actualizada, precios de commodities

### Normativa Clave Vigente
| Norma | Descripción |
|-------|-------------|
| Ley 21.521 | Ley Fintech — open banking, proveedores servicios financieros, CMF |
| Ley 21.561 | Reducción jornada laboral a 40 horas semanales (vigente 2024-2028) |
| Ley 21.220 | Teletrabajo — contrato especial, desconexión digital |
| Ley 21.180 | Transformación Digital del Estado — Ley de Digitalización |
| Ley 21.331 | Derechos de las personas en atención de salud mental |
| Ley 20.936 | Transmisión eléctrica y net metering solar residencial |
| Ley 20.920 | REP — Responsabilidad Extendida del Productor (envases/RAEE) |
| Ley 19.496 | Ley del Consumidor (SERNAC) |
| Ley 20.848 | Marco para la inversión extranjera directa en Chile |
| Política Nacional IA | Marco de ética y gobernanza de IA (MINCIENCIA, 2021/2024) |

### Ecosistema de Startups y Fondos VC en Chile
| Organismo | Descripción |
|-----------|-------------|
| Start-Up Chile (CORFO) | Aceleradora pública, USD 100K-150K no dilutivos, red 2.500+ alumni |
| Fen Ventures | Fondo VC chileno early stage, sectores agritech/fintech/climatetech |
| ALLVP | Fondo VC LatAm con base en Chile, Series A/B |
| Austral Capital | Fondo VC chileno, inversión en startups regionales |
| IDB Lab | BID para innovación y startups en LatAm |
| Endeavor Chile | Apoyo a emprendedores de alto impacto, red global |

### Sectores Prioritarios Política Nacional de IA Chile
| Sector | Prioridad IA |
|--------|-------------|
| Minería | Optimización operativa, seguridad, medio ambiente |
| Salud | Diagnóstico, telemedicina, gestión hospitalaria |
| Agricultura | Precisión, trazabilidad, exportación |
| Educación | Personalización, acceso, calidad docente |
| Energía | Redes inteligentes, H2 verde, gestión demanda |
| Gobierno | Trámites digitales, datos abiertos, transparencia |

---

*Documento creado con fines educativos para profesionales y empresas en Chile.*
*Actualizado: 2026 | Maestros AI — maestrosai.com*
