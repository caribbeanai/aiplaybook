# Casos de Uso de IA para o Brasil
## Guia Completo: 120+ Casos de Uso Práticos

> **Criado por Adrian Dunkley** | Especialista Regional em IA | [maestrosai.com](https://maestrosai.com) | ceo@maestrosai.com
> *Uso Justo — Recurso Educacional*

---

## Brasil em Destaque

| Indicador | Dado |
|-----------|------|
| População | 215 milhões |
| PIB | US$ 2,1 trilhões (9ª maior do mundo) |
| PIB per capita | ~US$ 10.000 |
| Moeda | Real (BRL) |
| Idioma | Português |
| Capital | Brasília |
| Maior cidade | São Paulo (22 mi na RMSP) |
| Hub de IA | São Paulo — maior ecossistema tech da América Latina |
| Unicórnios | Nubank, iFood, Mercado Livre, Totvs, Creditas, Loft |
| Startups de IA | +1.400 startups ativas (2025) |

---

## 🌾 Setor 1: Agronegócio — Potência Global

O agronegócio representa ~26% do PIB brasileiro. Brasil é líder mundial em soja, carne bovina, café, açúcar, etanol, laranja e frango.

### Caso de Uso 1: Diagnóstico de Doenças em Lavouras de Soja
**Função**: Agrônomo / Produtor Rural
**Ferramenta de IA**: Claude + GPT-4 Vision

**Estrutura do Prompt**:
```
Sou produtor rural em [município, estado: MT/GO/PR/RS/MS] cultivando soja safra [ano].
Área: [X hectáreas]. Solo: [Latossolo Vermelho/Argissolo]. Precipitação: [mm nos últimos 30 dias].
Observei os seguintes sintomas nas folhas/hastes/vagens: [descrição detalhada].
Fase fenológica atual: [V3/V6/R1/R3/R5]. Última aplicação de fungicida: [produto e data].
Temperatura: [média diurna/noturna]. Inoculação: [Bradyrhizobium sim/não].

Analise os sintomas e forneça:
1. Diagnóstico provável: doença (Ferrugem Asiática/Antracnose/Mela/Mancha Alvo), praga ou deficiência
2. Nível de severidade e urgência de controle
3. Protocolo de manejo: fungicida/inseticida registrado no MAPA para soja
4. Dose, volume de calda, horário ideal de aplicação
5. Custo de controle por hectare (BRL) baseado no preço atual de insumos
6. Impacto estimado na produtividade se não tratado (sacas/hectare)
7. Medidas preventivas para próxima safra
8. Consultar EMBRAPA Soja: cultivar mais resistente para minha região
```
**Benefícios**: Redução de perdas de 15-40%, decisões mais rápidas que aguardar visita técnica

---

### Caso de Uso 2: Rastreabilidade para Exportação — EUDR e USDA
**Função**: Gerente de Exportação / Compliance
**Ferramenta de IA**: Claude

**Estrutura do Prompt**:
```
Sou exportador de [soja/carne bovina/café/açúcar/milho] da região de [estado/município].
Volume de exportação: [X toneladas/safra]. Destino: [UE/EE.UU./China/Japão].
Certificações atuais: [Rainforest Alliance/UTZ/ABR/Round Table/nenhuma].
CAR (Cadastro Ambiental Rural): [regularizado/em processo/não tem].
Problema: atender EUDR (Regulamento de Desmatamento da UE) a partir de dezembro 2024.

Crie sistema de rastreabilidade para atender EUDR:
- Due Diligence EUDR: documentação de origem de lote por talhão/fazenda — coordenadas GPS
- CAR/SCAR: como usar o Cadastro Ambiental Rural como prova de conformidade
- Auditoria da cadeia de custódia: de fazenda → armazém → porto — responsabilidades
- Análise geoespacial: como verificar se área é livre de desmatamento após 31/12/2020
- Plataforma TRACES NT (UE): declaração de diligência devida — preenchimento
- Documentação por destino: UE (EUDR), EUA (USDA/FDA), China (GACC registro)
- Template de due diligence statement para importadores europeus
- Risco de embargo: multas de até 4% do faturamento na UE para não conformidade
```
**Benefícios**: Acesso mantido ao mercado da UE, prevenção de embargo, preço premium

---

### Caso de Uso 3: Gestão de Pecuária de Corte — Feedlot e Pastagem
**Função**: Pecuarista / Veterinário / Nutricionista animal
**Ferramenta de IA**: Claude

**Estrutura do Prompt**:
```
Sou pecuarista em [estado: MT/GO/MS/MG/SP/RS] com [X cabeças de gado bovino].
Sistema: [pastagem extensiva/semi-intensivo/confinamento feedlot].
Raça predominante: [Nelore/Angus/cruzas Brahman]. Peso de entrada no confinamento: [X kg].
Peso de abate alvo: [X kg]. Dias em confinamento: [X]. Ração atual: [composição %].
Preço do arroba: R$ [valor]. Custo da ração: R$ [valor/kg de MS].

Otimize a operação pecuária:
- Formulação de dieta para feedlot: maximizar GPD (Gancho de Peso Diário) e CA (Conversão Alimentar)
- Análise de margem bruta: custo de produção da arroba vs preço de mercado (CEPEA)
- Sanidade animal: calendário de vacinação (febre aftosa, brucelose — MAPA obrigatório)
- Abate: peso ideal, maturidade, grau de acabamento — conformidade com frigoríficos
- SISBOV: rastreabilidade para exportação ao mercado europeu e outros exigentes
- Bienestar animal: práticas de bem-estar — exigência crescente de compradores globais
- Huella de carbono: como calcular e reduzir o GEE na pecuária (ABCZ protocolos)
- Análise financeira: custo de produção por arroba com diferentes cenários de preço
```
**Benefícios**: Melhora de 20-30% na margem, acesso a frigoríficos premium, sustentabilidade

---

## 💳 Setor 2: Fintech — Pix, Open Finance e LGPD

### Caso de Uso 4: Compliance com LGPD para Empresa de Tecnologia
**Função**: DPO (Encarregado de Dados) / Jurídico / CTO
**Ferramenta de IA**: Claude

**Estrutura do Prompt**:
```
Sou DPO de uma empresa de [fintech/healthtech/edtech/e-commerce] no Brasil.
Dados tratados: [CPF/dados bancários/comportamento/localização/biometria/saúde].
Volume de titulares: [X usuários]. Porte: [startup/scale-up/grande empresa].
Incidentes anteriores: [sim/não]. Notificações ANPD já realizadas: [sim/não].
Base legal principal: [consentimento/contrato/interesse legítimo/obrigação legal].

Crie programa completo de compliance LGPD:
1. ROPA (Registro de Operações de Tratamento): mapeamento de todos os fluxos de dados
2. Base legal por operação: art. 7º LGPD — justificativa para cada tratamento de dado
3. AIPD (Avaliação de Impacto à Proteção de Dados): quando é obrigatório e como fazer
4. Política de Privacidade: versão acessível — linguagem simples, atualização 2024
5. Direitos dos titulares: acesso, correção, eliminação — prazo de 15 dias úteis ANPD
6. Plano de resposta a incidentes: notificação ANPD em 72h — formulário e conteúdo
7. Treinamento de equipe: módulos por área (TI, atendimento, RH, marketing)
8. Due diligence de fornecedores: cláusulas contratuais de proteção de dados
```
**Benefícios**: Prevenção de multas ANPD (até R$ 50 mi ou 2% do faturamento anual)

---

### Caso de Uso 5: Estratégia de Produto com Open Finance Brasil
**Função**: CPO / Product Manager / Head de Dados
**Ferramenta de IA**: Claude

**Estrutura do Prompt**:
```
Somos instituição participante do Open Finance Brasil (regulado pelo Banco Central).
Fase de implementação atual: [Fase 2 dados cadastrais/Fase 3 pagamentos/Fase 4 investimentos].
Dados acessíveis via API (com consentimento do cliente): [tipos de dados].
Produto principal: [conta digital/crédito/investimento/cartão]. NPS atual: [score].
Concorrentes: [Nubank/Inter/C6/bancos tradicionais].

Desenvolva estratégia de produtos com Open Finance:
- Proposta de valor: o que oferecer ao cliente em troca do compartilhamento de dados
- Jornada de consentimento: UX que maximiza taxa de adesão (benchmark: >30%)
- Casos de uso de dados: personalização de oferta, cross-sell, prevenção de churn
- Crédito alternativo: variáveis Open Finance mais preditivas de inadimplência
- MVP: produto mínimo viável usando portabilidade de dados (Resolução BCB 32/2020)
- Métricas: taxa de consentimento, ativação, retenção 30/60/90 dias
- Roadmap: alinhado ao cronograma do Banco Central — próximas fases
- Privacidade: como usar dados sem violar LGPD — anonimização, minimização
```
**Benefícios**: Diferenciação competitiva, personalização, aumento de receita por cliente

---

### Caso de Uso 6: Prevenção de Fraudes no Pix
**Função**: Head de Risco / Analista de Segurança Financeira
**Ferramenta de IA**: Claude

**Estrutura do Prompt**:
```
Somos uma [fintech/banco/plataforma de pagamentos] com volume mensal Pix de R$ [valor].
Taxa atual de fraudes: [% das transações]. Tipos mais comuns: [golpe do falso suporte/phishing/Pix agendado].
Solução antifraude atual: [sistema legado/nenhuma/parcial]. Regulação: Resolução BCB 6/2023 (MED).

Crie estratégia antifraude completa para Pix:
- Sinais de comportamento suspeito: primeiro Pix de alto valor para conta nova, horário incomum, localização
- Regras de bloqueio automático: thresholds por perfil de risco e histórico do cliente
- Autenticação escalonada: quando acionar segundo fator (SMS/biometria/liveness)
- MED (Mecanismo Especial de Devolução): prazo 7 dias, processo de acionamento no Bacen
- Comunicação preventiva: alerta ao usuário antes de transação suspeita confirmar
- Registro de BO e notificação Bacen: quando e como dentro do prazo legal
- Treinamento atendimento: como orientar vítima de golpe — script humanizado
- KPIs: taxa de fraude, falsos positivos (bloqueios indevidos), custo por fraude
```
**Benefícios**: Redução de fraudes em 60-80%, conformidade Bacen, proteção da reputação

---

## 🏭 Setor 3: Indústria — Embraer, Automotive e Manufatura

### Caso de Uso 7: Manutenção Preditiva com IoT e IA
**Função**: Gerente de Manutenção / Engenheiro de Confiabilidade
**Ferramenta de IA**: Claude

**Estrutura do Prompt**:
```
Sou responsável pela manutenção de [planta automotiva/petroquímica/alimentos/papel] em [estado].
Equipamentos críticos: [tornos CNC/prensas/compressores/turbinas/esteiras].
Estratégia atual: [preventiva programada/corretiva]. Custo médio de parada não planejada: R$ [valor/hora].
Sensores disponíveis: [vibração/temperatura/corrente elétrica/pressão/nenhum].
ERP: [SAP/Totvs/outro].

Crie programa de manutenção preditiva com IA:
- Criticidade: matriz de criticidade por equipamento (impacto × probabilidade de falha)
- Sensores: quais instalar por tipo de equipamento e parâmetros de baseline
- Análise de anomalias: limites de alerta e alarme por variável monitorada
- Plataformas IoT + IA: recomendação por porte — pequeno (Seeq), médio (OSIsoft), grande (Aspentech)
- Integração com ERP: abertura automática de OS ao detectar anomalia
- ROI: redução de paradas não planejadas de 40-70% — cálculo para seu contexto
- Protocolo de resposta: o que fazer quando o sistema alerta antes da falha
- Capacitação: como treinar equipe de manutenção para usar dados preditivos
```
**Benefícios**: Economia de R$ 500K-5M/ano, disponibilidade de equipamentos >95%

---

## ⛽ Setor 4: Energia — Petrobras, Solar e Etanol

### Caso de Uso 8: Energia Solar — Dimensionamento e Análise Financeira
**Função**: Integrador Solar / Consultor Comercial / Cliente
**Ferramenta de IA**: Claude

**Estrutura do Prompt**:
```
Sou integrador de energia solar em [estado] — distribuidora: [nome, tarifa R$/kWh].
Cliente com consumo mensal de [X kWh]. Tipo: [residencial/comercial/agronegócio/industrial].
Modalidade: [sistema on-grid/off-grid/geração compartilhada ANEEL Res. 482/2012].
Financiamento desejado: [BNDES Procap-Solarize/banco/capital próprio].

Dimensione o sistema e faça análise financeira completa:
- Geração necessária: kWp considerando irradiância solar da cidade (CRESESB/Atlas Solar)
- Especificações: quantidade e potência de painéis + inversor (string/micro/central)
- Estimativa de geração anual: kWh/ano com perdas (sujeira, temperatura, cabeamento)
- Investimento total: R$ com instalação, string box, aterramento, padrão CELESC/CEMIG/ENEL
- Economia mensal: R$ na conta de luz + créditos de energia (sistema de compensação)
- Payback simples e payback descontado (TMA: SELIC como referência)
- TIR e VPL a 25 anos: análise completa do investimento
- Incentivos fiscais vigentes: isenção ICMS (prorrogado até 2045), PIS/COFINS isentos
- Proposta comercial: comparativo de cenários em tabela para o cliente
```
**Benefícios**: Economia de 70-95% na conta de luz, TIR de 15-25% ao ano, payback 5-8 anos

---

## 🏥 Setor 5: Saúde — SUS, TISS e Telemedicina

### Caso de Uso 9: Auditoria de Contas Médicas — TISS/TUSS
**Função**: Auditor Médico / Operadora de Plano de Saúde
**Ferramenta de IA**: Claude

**Estrutura do Prompt**:
```
Sou auditor médico em operadora de plano de saúde regulada pela ANS.
Volume mensal: [X guias, R$ valor processado]. Taxa de glosa atual: [%].
Principais motivos de glosa: [procedimento não coberto/ausência de guia/código TUSS incorreto].
TISS versão: [4.0]. Tabelas utilizadas: [TUSS/AMB/CBHPM].

Desenvolva sistema inteligente de auditoria:
- Regras automáticas por especialidade: porte anestésico, cirurgias simultâneas, compatibilidade CID-procedimento
- Auditoria prospectiva: pré-autorização — critérios de negativa com fundamentação ANS
- Detecção de padrões suspeitos: unbundling (fracionamento), upcoding, serviços não realizados
- Glosa fundamentada: modelo de comunicação técnica ao prestador com artigo da tabela
- Recurso do prestador: fluxo de análise conforme RN 506/2022 ANS (prazo 30 dias)
- Dashboard executivo: custo médio por evento, frequência de uso, taxa de glosa por prestador
- Relatórios ANS: DIOPS, FIP — campos obrigatórios e prazos de envio
- LGPD na saúde: dados sensíveis — base legal (art. 7º e 11º LGPD) para tratamento
```
**Benefícios**: Redução de pagamentos indevidos em 15-25%, conformidade ANS

---

## 🎓 Setor 6: Educação — ENEM, EAD e FUVEST

### Caso de Uso 10: Preparação para o ENEM — Plano de Estudos Personalizado
**Função**: Estudante / Professor / Coordenador Pedagógico
**Ferramenta de IA**: Claude

**Estrutura do Prompt**:
```
Sou [estudante/professor de cursinho] preparando o ENEM [ano].
Disciplina mais fraca: [Matemática/Português/Biologia/História/Química/Física].
Nota atual em simulados: [X pontos por área]. Meta: [X pontos — para entrar em qual curso/universidade].
Tempo disponível para estudo: [X horas/dia]. Modalidade: [cursinho presencial/EAD/autodidata].
Redação: [nota média atual: X]. Tema de redação praticados: [lista].

Crie plano de preparação personalizado:
- Análise das últimas 5 provas ENEM: temas mais recorrentes por área de conhecimento
- Mapa de calor: probabilidade de cada conteúdo cair no ENEM [ano] (análise histórica)
- Plano de estudos [X meses]: cronograma semanal com meta de conteúdo e revisão
- Exercícios no estilo ENEM: 10 questões por tópico com gabarito comentado (competências BNCC)
- Redação nota 1000: estrutura dissertativo-argumentativa (introdução+tese+3 argumentos+proposta)
- Gestão de tempo na prova: estratégia para cada caderno (45 questões/área em 5h30)
- Simulados: como interpretar relatório de desempenho e ajustar o plano
- Saúde mental: técnicas para controlar ansiedade de prova — respiração, sono, alimentação
```
**Benefícios**: Aumento de 100-300 pontos, aprovação em SISU/PROUNI/universidades públicas

---

## 🛒 Setor 7: E-commerce e Varejo Digital

### Caso de Uso 11: Mercado Livre Brasil — Estratégia de Seller
**Função**: Seller / Gerente de Marketplace / E-commerce Manager
**Ferramenta de IA**: Claude

**Estrutura do Prompt**:
```
Vendo [categoria] no Mercado Livre Brasil como [vendedor profissional/MercadoShops].
Faturamento mensal: R$ [valor]. SKUs ativos: [X]. Reputação: [verde/amarelo/vermelho].
Nível: [MercadoLíder/MercadoLíder Gold/MercadoLíder Platinum].
Logística: [Mercado Envios Full/Flex/própria]. Comissão média: [%].

Otimize a operação no Mercado Livre:
- Título e descrição: palavras-chave LSI para o mecanismo de busca do ML
- Fotos: padrão ML — fundo branco, dimensões, ângulos obrigatórios e adicionais
- Buy Box: como conquistar e manter a posição principal em anúncios compartilhados
- MercadoAds: campanha patrocinada — CPC, ROI, palavras-chave negativas
- Fulfillment Full: análise de viabilidade — custo de armazenamento vs velocidade de entrega
- Gestão de reviews: como solicitar, responder negativos, relatório de qualidade
- Calendário: Dia das Mães/Pais, Black Friday, Natal — antecipação de estoque e promoções
- Análise de concorrentes: ferramentas (Hive, Nubimetrics) para espionagem competitiva
```
**Benefícios**: Aumento de faturamento em 40-100%, melhora de posicionamento nos resultados

---

## 🏛️ Setor 8: Governo e Setor Público

### Caso de Uso 12: Compras Governamentais — ComprasNet e PNCP
**Função**: Pregoeiro / Gestor de Compras / Empresa Fornecedora
**Ferramenta de IA**: Claude

**Estrutura do Prompt**:
```
Sou [pregoeiro/gestor de compras] em [município/estado/órgão federal] com orçamento anual de R$ [valor].
Modalidade mais usada: [Pregão Eletrônico/Dispensa/Inexigibilidade/Concorrência].
Lei aplicável: Lei 14.133/2021 (Nova Lei de Licitações e Contratos) — em vigor.
Plataforma: [ComprasNet/BLL/PNCP (Portal Nacional de Contratações Públicas)].
Problema: [elaborar TR adequado/pesquisa de preços/fiscalização de contratos].

Otimize o processo de compras governamentais:
- Termo de Referência (TR): estrutura completa — objeto, justificativa, especificações técnicas não restritivas
- Pesquisa de preços: como usar o Painel de Preços do Governo Federal (preços.gov.br)
- Critérios de habilitação: jurídica, fiscal/trabalhista, técnica, econômico-financeira — limites Lei 14.133
- Sessão do Pregão Eletrônico: fases, lances, negociação, aceitação e habilitação
- Fiscalização de contrato: gestor e fiscal — responsabilidades, check-list mensal
- Irregularidades: como reportar ao TCU, CGU, MP — formulários e prazos
- PNCP: obrigatoriedade de publicação — o que publicar e quando
- Economicidade: cálculo do índice de economia em relação ao preço de referência
```
**Benefícios**: Redução de irregularidades, economia de 10-30% em compras, conformidade TCU

---

## 📊 Referência Rápida — 108 Casos de Uso Adicionais

| # | Caso de Uso | Setor | Ferramenta |
|---|-------------|-------|------------|
| 13 | Açúcar e etanol — otimização de usina sucroalcooleira | Agro/Energia | Claude |
| 14 | Café especial — classificação e exportação SCA | Agro | Claude |
| 15 | Café — gestão de cooperativa (Cooxupé/Minasul) | Agro | Claude |
| 16 | Açaí — processamento e cadeia fria do Pará | Agro | Claude |
| 17 | Soja — hedge no mercado futuro B3 (contratos) | Agro/Finanças | Claude |
| 18 | Seguros rurais — Proagro, seguro paramétrico | Agro/Finanças | Claude |
| 19 | Rastreabilidade bovina — SISBOV para exportação | Agro | Claude |
| 20 | Cooperativa agrícola — gestão e governança | Agro | Claude |
| 21 | Armazéns — CPR (Cédula de Produto Rural) | Agro/Finanças | Claude |
| 22 | Pix — estratégia de desconto e conversão | Fintech | Claude |
| 23 | Nubank / Itaú / Bradesco — digital banking | Fintech | Claude |
| 24 | LGPD — auditoria e relatório de conformidade | Legal | Claude |
| 25 | ANPD — notificação de incidente de segurança | Legal | Claude |
| 26 | Fintech regulatória — sandbox BCB | Fintech | Claude |
| 27 | Simples Nacional — enquadramento e planejamento | Contabilidade | Claude |
| 28 | Lucro Presumido vs Real — comparativo | Contabilidade | Claude |
| 29 | e-Social — eventos e tabelas obrigatórias | RRHH | Claude |
| 30 | MEI — microempreendedor individual — gestão | Admin | Claude |
| 31 | CNPJ — abertura digital via Portal Gov.br | Admin | Claude |
| 32 | Receita Federal — declaração de IR PF | Admin | Claude |
| 33 | NF-e — emissão e cancelamento de nota fiscal | Admin | Claude |
| 34 | SPED — escrituração digital obrigações fiscais | Contabilidade | Claude |
| 35 | Petrobras — pré-sal e estratégia de produção | Energia | Claude |
| 36 | Petrobras — transição energética e baixo carbono | Energia | Claude |
| 37 | Etanol — paridade com gasolina C e CBios | Energia | Claude |
| 38 | Eólica offshore — leilões e oportunidades | Energia | Claude |
| 39 | Biogás — resíduos agropecuários e urbanos | Energia | Claude |
| 40 | ANEEL — regulação elétrica e tarifas | Energia | Claude |
| 41 | ANP — upstream e downstream de petróleo | Energia | Claude |
| 42 | Embraer — supply chain aeroespacial | Indústria | Claude |
| 43 | Volkswagen/GM/Stellantis — auto Brasil | Indústria | Claude |
| 44 | Indústria 4.0 — digitalização de fábrica | Indústria | Claude |
| 45 | Zona Franca de Manaus — incentivos fiscais | Indústria | Claude |
| 46 | BNDES — linhas de crédito para empresas | Finanças | Claude |
| 47 | Debentures incentivadas — infraestrutura | Finanças | Claude |
| 48 | FII — fundos imobiliários B3 | Finanças | Claude |
| 49 | Tesouro Direto — estratégia de carteira | Finanças | Claude |
| 50 | Previdência privada — PGBL/VGBL | Finanças | Claude |
| 51 | Crédito rural — Pronaf/Pronamp/ABC+ | Finanças | Claude |
| 52 | SUS — gestão de fila de espera e regulação | Saúde | Claude |
| 53 | TISS — sistema de informação de saúde suplementar | Saúde | Claude |
| 54 | Telemedicina — resolução CFM 2.314/2022 | Saúde | Claude |
| 55 | Vigilância epidemiológica — dengue/arboviroses | Saúde | Claude |
| 56 | ANVISA — registro sanitário de produtos | Saúde | Claude |
| 57 | INCT — ensaios clínicos e farmacologia | Saúde | Claude |
| 58 | Medicina diagnóstica — IA em laudos por imagem | Saúde | Claude |
| 59 | FUVEST/Unicamp — preparação vestibular SP | Educação | Claude |
| 60 | EAD — criação de curso online na Hotmart | Educação | Claude |
| 61 | ENEM — redação nota 1000 — banco de temas | Educação | Claude |
| 62 | Currículo Lattes — atualização e otimização | Educação | Claude |
| 63 | FAPESP/CNPq — elaboração de projeto científico | Educação | Claude |
| 64 | Artigo científico — formatação ABNT/Vancouver | Educação | Claude |
| 65 | iFood / Rappi — restaurante e otimização | Varejo | Claude |
| 66 | Shopee Brasil — seller e estratégia de loja | Varejo | Claude |
| 67 | Amazon Brasil — FBA e marca própria | Varejo | Claude |
| 68 | E-commerce — taxa de conversão e abandono | Varejo | Claude |
| 69 | Google Ads Brasil — campanha e ROAS | Marketing | Claude |
| 70 | Meta Ads Brasil — campanha para e-commerce | Marketing | Claude |
| 71 | SEO em Português — Google Brasil | Marketing | Claude |
| 72 | Influencer marketing — contratos e NFs | Marketing | Claude |
| 73 | Porto Digital Recife — hub tech nordeste | Tech | Claude |
| 74 | Campinas/Unicamp — deep tech e pesquisa | Tech | Claude |
| 75 | Startup aceleração — Wayra/ACE/Darwin | Tech | Claude |
| 76 | Crédito de carbono — Amazônia REDD+ | Ambiental | Claude |
| 77 | Cerrado — desmatamento zero e carbono | Ambiental | Claude |
| 78 | Mangroves — carbono azul e restauração | Ambiental | Claude |
| 79 | ESG — relatório GRI/SASB para empresa | Ambiental | Claude |
| 80 | Código Florestal — APP e Reserva Legal | Ambiental | Claude |
| 81 | CLT — rescisão, 13º, FGTS — cálculo | RRHH | Claude |
| 82 | Trabalho remoto — regulamentação Brasil | RRHH | Claude |
| 83 | Terceirização — Lei 13.429/2017 | RRHH | Claude |
| 84 | NOM-35 BR — NR-17 ergonomia e saúde | RRHH | Claude |
| 85 | Incorporação imobiliária — RET | Imobiliário | Claude |
| 86 | IGPM/IPCA — reajuste de aluguéis | Imobiliário | Claude |
| 87 | Leilão imobiliário — estratégia | Imobiliário | Claude |
| 88 | Airbnb Nordeste — gestão de temporada | Imobiliário | Claude |
| 89 | Turismo — Nordeste e Pantanal ecoturismo | Turismo | Claude |
| 90 | Carnaval — gestão de eventos e camarotes | Turismo | Claude |
| 91 | Gastronomia brasileira — franquias | Gastronomia | Claude |
| 92 | Cachaça artesanal — MAPA e exportação | Alimentos | Claude |
| 93 | ANVISA RDC 429/2020 — rotulagem | Alimentos | Claude |
| 94 | Petição inicial — direito do consumidor | Jurídico | Claude |
| 95 | Recuperação judicial — plano e credores | Jurídico | Claude |
| 96 | INPI — marcas e patentes — estratégia | Jurídico | Claude |
| 97 | Lei Anticorrupção 12.846/2013 — compliance | Jurídico | Claude |
| 98 | Marco Civil da Internet — plataformas | Jurídico | Claude |
| 99 | Podcast Brasil — Spotify monetização | Mídia | Claude |
| 100 | Música brasileira — ECAD e streaming | Cultura | Claude |
| 101 | Games Brasil — estúdio indie e publishing | Tech | Claude |
| 102 | Blockchain agro — rastreabilidade de grãos | Agro/Tech | Claude |
| 103 | IA — legislação em tramitação no Congresso | Regulação | Claude |
| 104 | Minha Casa Minha Vida — eligibilidade | Social | Claude |
| 105 | CadÚnico — atualização e benefícios sociais | Social | Claude |
| 106 | CRAS/CREAS — gestão de benefícios | Social/Gov | Claude |
| 107 | Saúde mental — burnout e CLT | Saúde/RRHH | Claude |
| 108 | Fintechs ESG — crédito verde e social | Fintech | Claude |
| 109 | Exporta Fácil Correios — exportação micro | Logística | Claude |
| 110 | Drones — ANAC e uso comercial | Tech | Claude |
| 111 | Veículos elétricos — infraestrutura Brasil | Energia | Claude |
| 112 | Hidrômetro digital — saneamento 4.0 | Infraestrutura | Claude |
| 113 | 5G Brasil — Anatel e oportunidades | Tech | Claude |
| 114 | DeepSeek vs ChatGPT — escolha para PME | Tech | Claude |
| 115 | SEBRAE — acesso a programas de apoio | Negocios | Claude |
| 116 | Franquias — ABF e regulação no Brasil | Negocios | Claude |
| 117 | Microcrédito produtivo — Banco do Povo | Finanças | Claude |
| 118 | Factoring — financiamento de duplicatas | Finanças | Claude |
| 119 | Fintechs de investimento — CVM regulação | Finanças | Claude |
| 120 | Inovação aberta — corporate ventures Brasil | Tech | Claude |

---

## Ferramentas de IA para o Brasil

| Ferramenta | Para Quê | Custo | Qualidade PT-BR |
|------------|----------|-------|-----------------|
| Claude (claude.ai) | Tudo: análises, textos, código | Grátis/Pro R$90-100/mês | Excelente |
| ChatGPT | Conteúdo, brainstorming | Grátis/Plus R$100/mês | Muito bom |
| Google Gemini | Google Workspace, pesquisa | Grátis/Pro | Muito bom |
| Canva IA | Design, apresentações | Grátis/Pro R$55/mês | Bom |
| Microsoft Copilot | Office, Outlook, Teams | M365 | Bom |
| Totvs Carol | ERP com IA para PMEs | Pago | Excelente (BR) |
| RD Station IA | CRM e marketing | Pago | Excelente (BR) |

---

## Ecossistema de IA no Brasil

| Hub | Destaques | Foco |
|-----|-----------|------|
| São Paulo (Faria Lima) | Nubank, iFood, Mercado Livre, Totvs | Fintech, SaaS, B2B |
| Campinas/Unicamp | CPqD, CI&T, Unicamp Inova | Deep tech, telecom |
| Belo Horizonte | Take, Stefanini, Dasa Digital | Healthtech, CS |
| Porto Alegre | TOTVS Sul, Dell, Unisinos | ERP, manufatura |
| Recife (Porto Digital) | Vivo, Samsung, GovTech | Govtech, BPO |
| Brasília | Gov.br, SERPRO, TCU Digital | Govtech, regulação |

---

*Criado por Adrian Dunkley | MaestrosAI | maestrosai.com | ceo@maestrosai.com*
*Uso Justo — Recurso Educacional | Março 2026*
*SEO: IA para empresas Brasil | casos de uso IA Brasil | inteligência artificial agronegócio | IA Pix Open Finance LGPD | IA saúde SUS TISS | IA ENEM EAD | IA Mercado Livre e-commerce | IA startups São Paulo | Claude Brasil ChatGPT português*
