# Módulo 1: Levantamento de Dados e Programa de Necessidades HVAC

## Resumo Executivo

Antes de desenhar qualquer sistema HVAC, você precisa **ouvir a instituição** e traduzir necessidades médicas, operacionais e arquitetônicas em especificações técnicas. Este módulo ensina o processo sistemático de coleta de informações, criação de matriz de requisitos e rastreabilidade, garantindo que nenhum detalhe escape antes do projeto começar.

---

## Objetivos de Aprendizagem

Ao final deste módulo, você será capaz de:

- **Coletar** informações completas sobre instituição, ocupação, equipamentos e sensibilidades
- **Classificar** ambientes hospitalares por tipologia (cirúrgicos, UTIs, isolamentos, etc.)
- **Identificar** requisitos especiais (fluxo laminar, pressurização, filtragem aumentada)
- **Criar** matriz de rastreabilidade (requisito → elemento HVAC)
- **Comunicar-se** efetivamente com equipes médicas, arquitetos e engenheiros
- **Documentar** programa de necessidades conforme RDC 50

---

## Pré-requisitos

- Módulo 0 (Fundamentos Regulatórios) - conceitos de classificação de ambientes
- Noções básicas de ocupação, equipamentos médicos
- Disposição de fazer "lição de casa" com hospital/instituição

---

## Seção 1: Por Que Levantamento de Dados Importa?

### O Problema: Projetos Falhando por Informação Incompleta

**Cenário Real**: Um hospital contratou projetista HVAC que não perguntou detalhes suficientes. Resultado:
- Sala cirúrgica foi projetada sem saber que havia **foco cirúrgico de 400W** = ganho térmico extra
- UTI não previu **equipamentos de precisão** que geram calor = temperatura incontrolável
- Isolamento não considerou que haveria **pacientes muito graves** = exigências de redundância ignoradas

**Custo**: Reforma pós-obra = R$ 150 mil + atraso de 3 meses.

**Lição**: **10 horas de levantamento economizam 100 horas de retrabalho.**

---

### Responsabilidade Técnica (NBR 7256 e RDC 50)

**RDC 50, Apêndice C** exige que projeto HVAC seja baseado em "programa de necessidades" definido colaborativamente com:
- Equipe médica (requisitos clínicos)
- Arquitetura (espaço disponível)
- Engenharia (viabilidade técnica)

**Sua responsabilidade** é garantir rastreabilidade: cada requisito tem origem, justificativa e elemento HVAC correspondente.

**Documentação**: Matriz de requisitos é deliverable obrigatório e auditável.

---

## Seção 2: Processo Sistemático de Levantamento

### Passo 1: Informações Gerais da Instituição

**O que perguntar:**

| Informação | Por Quê | Exemplo |
|-----------|--------|---------|
| **Nome e localização** | Clima (altitude, temperatura externa) | Hospital X, São Paulo, 750m |
| **Tamanho (leitos)** | Escala do projeto | 100, 250, 500 leitos |
| **Estágio do projeto** | Novo vs reforma | Novo construção vs reforma pós-2020 |
| **Orçamento estimado** | Determina nível de sofisticação | R$ 500k vs R$ 2M |
| **Prazos** | Impacta escolha de equipamentos | 6 meses vs 18 meses |
| **Histórico de problemas** (se reforma) | Diagnóstico de falhas passadas | "UTI com temperatura instável" |

---

### Passo 2: Tipologia de Ambientes e Ocupação

Para CADA ambiente, coletar:

#### **Informação 2.1: Identificação Básica**

```
Ambiente: Sala Cirúrgica 1
├─ Localização: Bloco Cirúrgico, Pavimento 2
├─ Área: 40 m²
├─ Pé-direito: 3.0 m
├─ Revestimentos: Piso vinílico antisséptico, paredes pintura epóxi
└─ Porta: Dupla (circulação → antecâmara → sala)
```

#### **Informação 2.2: Ocupação**

```
Ocupação Normal: 6 pessoas (cirurgião, auxiliar, anestesista, 2 técnicos, paciente)
Ocupação Máxima: 8 pessoas (ensino/treinamento)
Tempo médio de permanência: 2-4 horas
Frequência: 5-8 cirurgias/dia
```

**Por quê**: Ocupação determina geração de CO₂, calor corporal, contaminação microbiológica.

#### **Informação 2.3: Equipamentos Geradores de Calor**

```
Equipamento | Potência | Tempo Operação | Modo Ejeção
------------|----------|----------------|------------
Foco cirúrgico | 400W | Durante cirurgia | Calor radiante
Eletrocautério | 200W | Intermitente | Calor + fumaça
Monitor + registrador | 100W | Contínuo | Calor convectivo
Bomba infusora | 50W | Variável | Calor baixo
Sistema de aspiração | 150W | Intermitente | Sucção
```

**Por quê**: Define carga térmica sensível. Determina capacidade de resfriamento necessária.

---

### Passo 3: Sensibilidades e Requisitos Especiais

**Perguntas-chave:**

#### **3.1: Controle Ambiental Especial?**

- [ ] Fluxo laminar (cirurgia, UTI neonatal, transplante)?
- [ ] Umidade relativa controlada (farmácia de medicamentos instáveis)?
- [ ] Temperatura criogênica (laboratório)?
- [ ] Isolamento acústico especial?

**Exemplo**: 
```
"Sim, sala de cirurgia pediátrica requer fluxo laminar 
descendente para reduzir risco de infecção neonatal"
```

#### **3.2: Pacientes Imunocomprometidos?**

- [ ] Transplantados
- [ ] Pacientes com câncer em quimioterapia
- [ ] Prematuros extremos
- [ ] HIV+

**Impacto**: Requer pressão positiva aumentada + filtração HEPA obrigatória.

#### **3.3: Riscos Infecciosos Específicos?**

- [ ] Tuberculose (comum na instituição?)
- [ ] COVID-19
- [ ] Varicela (catapora)
- [ ] Patógenos multi-resistentes

**Impacto**: Exige isolamento respiratório com pressão negativa.

#### **3.4: Fumigação/Desinfecção Periódica?**

- [ ] Necessário?
- [ ] Frequência?
- [ ] Agentes químicos usados?

**Impacto**: Dutos devem ser estanques, selados, acessíveis para limpeza.

---

### Passo 4: Integração com Infraestrutura Existente

**Perguntas técnicas:**

```
Sistema existente (se reforma):
├─ Qual HVAC está em operação?
├─ Qual será substituído vs mantido?
├─ Conexões com sistema central?
└─ Pontos de tomada de ar exterior disponíveis?

Infraestrutura predial:
├─ Chaminés/exaustão central?
├─ Espaço disponível para sala de máquinas?
├─ Capacidade estrutural para peso de equipamentos?
└─ Espaço de dutos (forro, paredes)?

Utilidades:
├─ Alimentação elétrica disponível (trifásico)?
├─ Água/drenagem para condensado?
├─ Gás (se necessário)?
└─ Vapor (se necessário)?
```

---

## Seção 3: Matriz de Rastreabilidade (Requisito → HVAC)

Esta é a **ferramenta mais importante** do levantamento.

### Estrutura

```
ID | Fonte | Ambiente | Requisito Clínico | Elemento HVAC | Norma
---|-------|----------|-------------------|---------------|------
1  | Médico| Cirurgia | Reduzir infecção de sítio cirúrgico | Pressão +20 Pa | NBR 7256
2  | Médico| Cirurgia | Eliminar fumaça eletrocautério | Exaustão localizada | RDC 50
3  | Arqtº | Cirurgia | Espaço limite 40m² | Vazão máxima 500 L/s | Cálculo
4  | Equip| Cirurgia | Foco gera 400W | Resfriamento +5% | Carga térmica
5  | NBR  | Cirurgia | Requisito mínimo | 15 trocas/hora, G4+F7+H13 | NBR 7256
```

### Exemplo Prático Resolvido

**Ambiente: UTI Geral, 80 m² (4 leitos de 20 m² cada)**

#### **Levantamento de Dados**

```
Ocupação: 4 pacientes críticos + 8 profissionais de saúde
Equipamentos/leito:
  - Monitor cardíaco: 50W
  - Ventilador mecânico: 100W
  - Bomba infusora: 50W
  - Cama aquecida: 200W
  - Total/leito: ~400W × 4 = 1.600W

Requisitos clínicos:
  - Pacientes imunocomprometidos: SIM
  - Risco de infecção aérea: MODERADO
  - Necessidade de isolamento: ALGUNS LEITOS
  - Umidade crítica: 45-55% (equipamentos de precisão)

Infraestrutura:
  - Pé-direito: 3.0 m
  - Forro: 2.6 m (espaço de plenum disponível)
  - Sala de máquinas: 30 m² próxima
  - Tomada de ar: Fachada norte, distante 50m
```

#### **Matriz de Rastreabilidade Resultante**

| ID | Requisito | Origem | Elemento HVAC | Justificativa | Norma |
|----|-----------|--------|---------------|--------------|-------|
| U1 | Pressão positiva +6 a +12 Pa | Médico | Regulador de pressão + sensor | Proteção contra contaminação externa | NBR 7256 |
| U2 | Renovação 12 trocas/hora | NBR 7256 | UTA com vazão mínima 900 L/s | Requisito crítico | NBR 7256 Tab.X |
| U3 | Filtração F7 mínimo | NBR 7256 | 2 estágios: G4 + F7 | Remover 99% de particulados | NBR 7256 |
| U4 | Umidade 45-55% | Equipamento | Umidificador + desumidificador | Evitar condensação em equipamentos | Engenharia |
| U5 | Temperatura 20-24°C ±1°C | Médico | Termostato +/- 0.5°C | Conforto + precisão de equipamentos | Clínica |
| U6 | Redundância em crítico | RDC 50 | UTA dupla (N+1) | Se falha UTA 1, UTA 2 assume | RDC 50 Ap.C |
| U7 | Isolar leito 3 (COVID) | Médico | Damper de isolamento | Segregar fluxo de ar do leito | Improviso |
| U8 | Carga térmica +1.600W | Cálculo | Resfriamento mínimo 8 kW | Equipamentos + calor corporal | Termo |

---

## Seção 4: Ferramenta Prática - Checklist de Levantamento

Use este checklist em TODA visita à instituição:

```
═══════════════════════════════════════════════════════════
CHECKLIST DE LEVANTAMENTO HVAC
Instituição: ___________________  Data: ___________
Projetista: ____________________  Assinado: _______
═══════════════════════════════════════════════════════════

SEÇÃO 1: INFORMAÇÕES GERAIS
─────────────────────────────
[ ] Nome, endereço, localização (GPS, altitude)
[ ] Tamanho (número de leitos, blocos, pavimentos)
[ ] Tipo (hospital, clínica, UPA, pronto-socorro)
[ ] Estágio do projeto (novo, reforma, ampliação)
[ ] Orçamento estimado (R$ ou faixa)
[ ] Prazos (início, conclusão)
[ ] Contato técnico (engenheiro da instituição, diretor)
[ ] Histórico de problemas HVAC (se aplicável)

SEÇÃO 2: TIPOLOGIA DE AMBIENTES
────────────────────────────────
Para cada ambiente crítico/semi-crítico:

Ambiente: _______________________
[ ] Área (m²), pé-direito (m), volume
[ ] Localização (pavimento, proximidade)
[ ] Revestimentos (piso, paredes, teto)
[ ] Portas (simples, dupla, com antecâmara?)
[ ] Ocupação normal e máxima
[ ] Equipamentos e potência (W)
[ ] Tempo de operação (h/dia)
[ ] Sensibilidades especiais (fluxo laminar? isolamento?)

[Repetir para CADA ambiente]

SEÇÃO 3: REQUISITOS ESPECIAIS
──────────────────────────────
[ ] Fluxo laminar necessário? SIM / NÃO
[ ] Pacientes imunocomprometidos? SIM / NÃO
[ ] Risco de TB, COVID, varicela? SIM / NÃO
[ ] Fumigação periódica? SIM / NÃO
[ ] Controle de umidade crítico? SIM / NÃO
[ ] Isonomia térmica (±1°C)? SIM / NÃO
[ ] Redundância (N+1) exigida? SIM / NÃO

SEÇÃO 4: INFRAESTRUTURA
───────────────────────
[ ] Sistema HVAC existente (marca, ano, estado)
[ ] Sala de máquinas (tamanho, localização, acessibilidade)
[ ] Tomada de ar (localização, distância de exaustão, filtração)
[ ] Dutos existentes (tamanho, material, estado)
[ ] Utilidades (energia trifásica, água, gás, vapor)
[ ] Estrutura (piso radiante, forro, paredes removíveis)
[ ] Espaço de plenum (altura, uso atual)

SEÇÃO 5: INTEGRAÇÕES
────────────────────
[ ] Conhecer arquiteto do projeto
[ ] Conhecer engenheiro estrutural
[ ] Conhecer engenheiro elétrico
[ ] Conhecer médico responsável (clínica)
[ ] Conhecer engenheiro de controle/infecção
[ ] Verificar prazos com todos
[ ] Documentar conflitos potenciais

SEÇÃO 6: FOTOGRAFIA E DOCUMENTAÇÃO
───────────────────────────────────
[ ] Fotos de ambientes principais
[ ] Fotos de sala de máquinas (existente ou local)
[ ] Fotos de fachada (tomadas de ar, exaustão)
[ ] Fotos de plantas arquitetônicas (obtidas)
[ ] Documentos normativos (RDC 50 local, códigos estaduais)

SEÇÃO 7: ASSINATURA
───────────────────
Levantamento realizado: _____/_____/_______
Projetista: ____________________________
Responsável institucional: _______________
```

---

## Seção 5: Comunicação com Equipes Interdisciplinares

### Exemplo de Reunião de Kickoff (Projeto)

**Participantes**: Médico-chefe, Arquiteto, Eng. HVAC (você), Eng. Elétrico, Eng. Estrutural

**Agenda**:

```
1. Apresentação de objetivos (15 min)
   ├─ Escopo do projeto
   ├─ Prazos
   └─ Orçamento

2. Requisitos médicos (30 min)
   ├─ Médico apresenta necessidades clínicas
   ├─ Você faz perguntas técnicas
   └─ Documenta em matriz

3. Restrições arquitetônicas (20 min)
   ├─ Arquiteto apresenta layout
   ├─ Espaço disponível para HVAC
   ├─ Interferências
   └─ Você identifica conflitos

4. Infraestrutura existente (15 min)
   ├─ Elétrico: disponibilidade de carga
   ├─ Estrutural: peso máximo, espaço
   ├─ Utilities: água, gás, vapor
   └─ Definir upgrade necessário

5. Cronograma integrado (10 min)
   ├─ Arquitetura: 2 meses
   ├─ HVAC: 3 meses
   ├─ Elétrico: 2 meses
   └─ Dependências críticas

6. Próximos passos (10 min)
   └─ Cada um: entrega de dados em X semanas
```

---

## Seção 6: Criando o Programa de Necessidades (Documento Formal)

### Estrutura (conforme RDC 50)

**Título**: Programa de Necessidades HVAC - [Instituição]

**Seção 1: Introdução**
```
Este programa de necessidades define os requisitos técnicos, clínicos 
e operacionais para o projeto de sistema HVAC em [Instituição].
Baseia-se em NBR 7256:2021 e RDC 50/2002.
```

**Seção 2: Ambientes Críticos**

Para cada ambiente:
```
AMBIENTE: Sala Cirúrgica
─────────────────────────
Classificação: CRÍTICA (conforme NBR 7256)
Risco infeccioso: Alto (ferida aberta)
Ocupação: 6 pessoas + equipamentos
Origem dos requisitos: Médico + NBR 7256

Requisitos de HVAC:
├─ Renovação: 15 trocas/h (NBR 7256)
├─ Recirculação: até 50% (NBR 7256)
├─ Pressão: +20 Pa (positiva)
├─ Filtração: G4 + F7 + H13
├─ Temperatura: 20-24°C
├─ Umidade: 45-55%
├─ Fluxo laminar: Sim (descendente)
└─ Redundância: N+1 (obrigatória)

Justificativa:
- Pressão positiva: evita entrada de ar contaminado
- Filtração em 3 estágios: remove 99.99% de patógenos
- Fluxo laminar: cria barreira de ar limpo sobre incisão
- Redundância: se falha, backup garante segurança
```

**Seção 3: Matriz de Rastreabilidade Consolidada**

Tabela contendo todos os requisitos (como Seção 3 deste módulo).

**Seção 4: Restrições e Oportunidades**

```
Restrições:
- Espaço de sala de máquinas limitado a 25 m²
- Tomada de ar: 60 m de distância (ductagem longa)
- Orçamento: máximo R$ 800 mil

Oportunidades:
- Reforma integrada com estrutura = melhor espaço
- Possibilidade de energia solar (fachada norte)
- Possibilidade de reuso de água de condensado (paisagismo)
```

---

## Seção 7: Checkpoint - Valide Seu Aprendizado

### Pergunta 1: Matriz de Rastreabilidade

**Você está fazendo levantamento em pequeno hospital. Médico diz:**

"Precisamos isolar um paciente com tuberculose. Qual deve ser o requisito de HVAC e qual a origem?"

**Opções**:
- A) Pressão +20 Pa, origem: arquitetura
- B) Pressão -15 Pa, origem: NBR 7256 + clínica ✓
- C) Umidade 30%, origem: norma internacional
- D) Fluxo laminar, origem: médico

**Resposta**: **B**

**Explicação**: Isolamento respiratório (TB) requer pressão NEGATIVA para proteger ambiente externo contra contaminação. NBR 7256 especifica -12 a -25 Pa. Origem é dupla: clínica (necessidade médica) + norma (especificação técnica).

---

### Pergunta 2: Identificação de Equipamentos

**Durante levantamento, você entra em UTI e vê:**
- 4 monitores cardíacos
- 4 ventiladores mecânicos
- 4 bombas infusoras
- 2 refrigeradores (medicamentos)
- 1 televisor

**Qual informação é CRÍTICA para cálculo de carga térmica?**

**Opções**:
- A) Televisor (conforto)
- B) Monitores + ventiladores + bombas (potência contínua) ✓
- C) Refrigeradores (potência intermitente)
- D) Apenas ocupação humana

**Resposta**: **B**

**Explicação**: Carga térmica SENSÍVEL (aquecimento) vem de equipamentos operando CONTINUAMENTE. Ventiladores mecânicos (100W/unidade = 400W total) + monitores (50W = 200W) + bombas (50W = 200W) = 800W contínuos. Refrigeradores são intermitentes. Televisor é negligenciável. Soma com calor corporal (6 pessoas × 100W = 600W) para carga total ~1.400W.

---

### Desafio Prático: Criar Matriz Simplificada

**Cenário**: Você está refazendo levantamento de CLÍNICA OFTALMOLÓGICA (10 consultórios + 1 sala de cirurgia a laser).

**Dados que você coletou**:
- Sala cirurgia laser: 20 m², cirurgião + técnico (2 pessoas), laser 500W, temperatura crítica
- Consultórios: 10 × 12 m², oftalmologista + paciente (2 pessoas), apenas lâmpadas (50W)
- Recepção: 30 m², 3 funcionários

**Sua Tarefa**: 
1. Classificar cada ambiente (crítico/semi/não-crítico)
2. Criar matriz com 3 requisitos por ambiente

**Solução Esperada**:

```
AMBIENTE: Sala Cirurgia Laser
Classificação: CRÍTICA
Requisitos:

ID1 | Temperatura 20-22°C rigorosa | Origem: Equipamento (laser sensível) | Elemento: Termostato ±0.5°C
ID2 | Resfriamento extra 500W | Origem: Cálculo (laser) | Elemento: UTA +3kW capacidade
ID3 | Filtração G4+F7 | Origem: NBR 7256 semi-crítica + especial | Elemento: 2 estágios filtro

AMBIENTE: Consultórios (10x)
Classificação: NÃO-CRÍTICA
Requisitos:

ID1 | Conforto térmico 22-26°C | Origem: Clínica | Elemento: Ar-condicionado split
ID2 | Renovação mínima 4 trocas/h | Origem: NBR 7256 não-crítica | Elemento: Renovação 50 L/s
ID3 | Filtração G3+G4 | Origem: NBR 7256 | Elemento: 1 estágio filtro

AMBIENTE: Recepção
Classificação: NÃO-CRÍTICA
Requisitos:

ID1 | Conforto 22-26°C | Origem: Clínica | Elemento: Ar-condicionado split
ID2 | Renovação 3 trocas/h | Origem: NBR 7256 | Elemento: Renovação 30 L/s
ID3 | Sem filtração especial | Origem: NBR 7256 | Elemento: Filtro padrão G3
```

---

## Glossário Técnico

| Termo | Definição | Aplicação |
|-------|-----------|-----------|
| **Levantamento** | Coleta sistemática de informações sobre instituição e requisitos | Fase 1 do projeto |
| **Programa de Necessidades** | Documento formal com requisitos técnicos e clínicos | Deliverable para RDC 50 |
| **Matriz de Rastreabilidade** | Tabela que conecta requisito → origem → elemento HVAC | Garantir rastreamento |
| **Requisito Clínico** | Exigência médica (ex: pressão negativa para TB) | Vem de médico/epidemiologia |
| **Requisito Normativo** | Exigência de norma (ex: 15 trocas/h cirurgia) | Vem de NBR 7256/RDC 50 |
| **Carga Térmica Sensível** | Calor que altera temperatura (equipamentos, pessoas) | Determina potência de resfriamento |
| **Carga Térmica Latente** | Calor que altera umidade (respiração, transpiração) | Determina desumidificação |
| **N+1 Redundância** | Sistema duplo: se um falha, outro assume | Áreas críticas |
| **Damper** | Válvula que controla fluxo de ar em dutos | Pressurização/isolamento |
| **Plenum** | Espaço entre forro e laje (passa ar de retorno) | Economia de dutos |

---

## Integração com Próximos Módulos

**Módulo 0** estabeleceu "por quê".  
**Módulo 1** (este) estabeleceu "o quê" (requisitos).  
**Módulo 2** começará com "como" (cálculos de vazão baseado nos requisitos daqui).

**Fluxo lógico**:
```
Módulo 1: Requisitos coletados
    ↓
Módulo 2: Calcula vazão usando esses requisitos
    ↓
Módulo 3: Calcula pressão usando esses requisitos
    ↓
... E assim por diante
```

---

## Referências Normativas do Módulo 1

1. **BRASIL. ANVISA - RDC 50/2002** - Apêndice C (Climatização) - Define processo colaborativo de levantamento e define "programa de necessidades" como requisito.

2. **ABNT NBR 7256:2021** - Seção 4 (Classificação de Ambientes) - Tipologia de ambientes que você vai classificar.

3. **ABNT NBR 9050:2020** - Acessibilidade - Quando levantar dados, considerar acessibilidade de sala de máquinas.

---

## Próximo Módulo

No **Módulo 2: Renovação, Recirculação e Exaustão**, você usará os requisitos coletados aqui para **calcular vazão de ar** necessária para cada ambiente.

---

**Módulo 1 Concluído ✓**

*Você aprendeu a "ouvir" a instituição e traduzir necessidades em especificações mensuráveis. Este é o superpoder do projetista: não é só conhecer normas, é fazer as perguntas certas.*

