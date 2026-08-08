# Módulo 0: Fundamentos Regulatórios e Riscos Infecciosos

## Resumo Executivo

Os sistemas HVAC (aquecimento, ventilação e ar-condicionado) em Estabelecimentos Assistenciais de Saúde (EAS) não são apenas conforto: são infraestrutura de segurança que previne infecções associadas à assistência. Este módulo apresenta o "por quê" técnico e regulatório de cada decisão que você tomará como projetista, fundamentado em NBR 7256:2021 e RDC 50/2002.

---

## Objetivos de Aprendizagem

Ao final deste módulo, você será capaz de:

- **Explicar** a relação entre ventilação, qualidade do ar e infecções hospitalares
- **Classificar** ambientes hospitalares por risco infeccioso (crítico, semi-crítico, não-crítico)
- **Justificar** requisitos de renovação, pressurização e filtragem usando fundamentos regulatórios
- **Aplicar** critérios de NBR 7256 e RDC 50 em projetos reais
- **Identificar** quando coordenar com médicos, epidemiologistas ou engenheiros de controle de infecção

---

## Pré-requisitos

- Conceitos básicos de ventilação (fluxo de ar, velocidade)
- Compreensão de pressão diferencial (Pa)
- Familiaridade com tabelas e normas técnicas
- Interesse genuíno em saúde e segurança de pacientes

---

## Seção 1: Por Que HVAC Importa em Hospitais?

### O Problema: Infecções Associadas à Assistência (IAA)

Antes de qualquer cálculo, entenda o contexto clínico:

**Dado epidemiológico**: Pacientes em ambiente hospitalar têm risco de adquirir infecções por contato direto com patógenos, superfícies contaminadas, ou **ar inalado**. Estima-se que 5-15% das infecções nosocomiais têm origem aérea (tuberculose, sarampo, COVID-19, aspergilose).

**Realidade**: Você, como projetista HVAC, participa diretamente na **redução ou aumento** desse risco a cada decisão:

- Quantas trocas de ar por hora você especifica? → Define renovação de patógenos
- A sala tem pressão positiva ou negativa? → Controla para onde o ar vai
- Qual filtro você usa? → Remove partículas contaminadas ou deixa passar?

**Responsabilidade Técnica**: Uma sala de isolamento mal projetada coloca pacientes imunodeprimidos E equipe médica em risco. Isso é reconhecido legalmente em conformidade com Anotação de Responsabilidade Técnica (ART) junto ao CREA.

---

### Fundação Normativa: NBR 7256 e RDC 50

#### **NBR 7256:2021 - Sistemas de Ventilação, Climatização e Condicionamento de Ar**

**O que é**: Norma ABNT que estabelece requisitos mínimos de desempenho e segurança para sistemas HVAC em EAS. É referência técnica obrigatória.

**Onde aparece**: Toda licitação pública, contratação hospitalar, projeto aprovado por órgão regulador exige conformidade com NBR 7256.

**Seções Críticas para Este Módulo**:

| Seção | Tema | Importância |
|-------|------|------------|
| 4 | Classificação de ambientes | ⭐⭐⭐⭐⭐ CRÍTICA |
| 5 | Requisitos de renovação e recirculação | ⭐⭐⭐⭐⭐ CRÍTICA |
| 6 | Requisitos de filtragem | ⭐⭐⭐⭐⭐ CRÍTICA |
| 7 | Pressurização diferencial | ⭐⭐⭐⭐⭐ CRÍTICA |
| 8 | Controles e automação | ⭐⭐⭐⭐ Importante |
| 9 | Segurança e integridade | ⭐⭐⭐⭐ Importante |

---

#### **RDC 50/2002 - ANVISA - Regulamento Técnico para Planejamento e Construção de EAS**

**O que é**: Resolução da ANVISA (agência sanitária federal) que complementa NBR 7256 com requisitos de proteção epidemiológica.

**Autoridade**: Regulação federal, fiscalizada por ANVISA. Violações podem resultar em interdição do EAS.

**Seções Críticas**:

| Apêndice | Tema | Propósito |
|----------|------|---------|
| C | Climatização | Define renovação mínima por ambiente |
| D | Qualidade do Ar | Define filtração e contaminação máxima |

**Exemplo de Exigência RDC 50**: "Ambientes de isolamento respiratório devem manter pressão negativa de -12 a -25 Pa e renovação mínima de 12 trocas/hora, com 100% de ar exterior exaurido sem recirculação."

---

### Classificação de Ambientes Hospitalares

A NBR 7256 classifica ambientes em **3 categorias** baseadas em risco infeccioso:

#### **1. ÁREAS CRÍTICAS (Alto Risco)**

**Definição**: Ambientes onde falhas no controle de ar resultam em risco grave de infecção aérea.

**Exemplos**:
- Salas cirúrgicas (risco de infecção de sítio cirúrgico)
- UTI (pacientes imunocomprometidos)
- Isolamentos respiratórios (negativo - tuberculose, COVID)
- Isolamentos de proteção (positivo - transplante, radioterapia)
- Salas de parto e neonatologia

**Requisitos Mínimos NBR 7256** (Tabela de Renovação):

| Ambiente | Renovação Mínima | Recirculação | Pressão | Filtro Mínimo |
|----------|------------------|-------------|---------|---------------|
| Cirurgia | 15 trocas/h | até 50% | +12 a +25 Pa | F7 + H13 |
| UTI | 12 trocas/h | até 50% | +6 a +12 Pa | F7 |
| Isolamento Negativo | 12 trocas/h | 0% | -12 a -25 Pa | F7 |
| Isolamento Positivo | 12 trocas/h | até 25% | +12 a +25 Pa | F7 + H13 |
| Neonatal | 12 trocas/h | até 50% | +6 a +12 Pa | F7 |

**Por que esses números?**
- **15 trocas/hora em cirurgia**: Remove rapidamente partículas de ar (sangue, fluidos) que poderiam contaminar ferida cirúrgica aberta
- **12 trocas/hora em UTI**: Paciente instável requer frequência de renovação compatível com eliminação de patógenos
- **Pressão positiva**: Ar limpo entra → ar sujo sai, sem infiltração de zonas contaminadas

---

#### **2. ÁREAS SEMI-CRÍTICAS (Risco Moderado)**

**Definição**: Ambientes com exposição significativa a patógenos, mas com ocupação variável e menor risco que críticas.

**Exemplos**:
- Enfermarias/enfermarias de isolamento
- Salas de recuperação pós-anestesia
- Salas de curativos
- Ambulatórios especializados
- Áreas de apoio (farmácia, esterilização)

**Requisitos Mínimos NBR 7256**:

| Ambiente | Renovação | Recirculação | Pressão | Filtro |
|----------|-----------|-------------|---------|--------|
| Enfermaria | 6 trocas/h | até 50% | +2 a +6 Pa | G4 + F7 |
| Farmácia | 6 trocas/h | até 50% | Variável | G4 + F7 |
| Esterilização | 6 trocas/h | até 50% | +2 a +6 Pa | G4 + F7 |

**Critério de Design**: Menos exigentes que críticas, mas ainda precisam controlar contaminação.

---

#### **3. ÁREAS NÃO-CRÍTICAS (Risco Baixo)**

**Definição**: Ambientes sem exposição significativa a patógenos; conforto térmico é objetivo principal.

**Exemplos**:
- Corredores
- Áreas administrativas
- Salas de espera
- Vestiários
- Áreas de circulação

**Requisitos Mínimos NBR 7256**:

| Ambiente | Renovação | Recirculação | Pressão | Filtro |
|----------|-----------|-------------|---------|--------|
| Corredor | 3-4 trocas/h | até 70% | Nenhuma | G3 + G4 |
| Administrativo | 3-4 trocas/h | até 70% | Nenhuma | G3 + G4 |

**Filosofia**: Menor custo operacional, sem comprometer segurança.

---

## Seção 2: Conceitos Técnicos Fundamentais

### Conceito 1: Renovação vs Recirculação

**Renovação (Ar Exterior)**:
- Ar vindo de fora do prédio
- "Fresco", sem contaminação interna (em tese)
- Caro (resfria/aquece)
- **Necessário para**: Remover CO₂, substituir patógenos

**Recirculação (Ar Interno)**:
- Ar já dentro da sala, filtrado e reintroduzido
- Reduz custo de energia
- Filtra mas NÃO remove CO₂
- **Permitido em**: Áreas não-críticas e algumas semi-críticas

**Fórmula Básica**:
```
Vazão Total (L/s) = Vazão Renovação + Vazão Recirculação
```

**Exemplo**: Cirurgia 40 m³
- Altura: 3 m → Volume: 120 m³
- Requisito: 15 trocas/hora
- Vazão Total = (120 m³ × 15 h⁻¹) ÷ 3600 s = **50 L/s**
- Renovação mínima (100%): 50 L/s de ar novo
- Recirculação (até 50%): 0 L/s (para cirurgia é critico)

---

### Conceito 2: Pressão Diferencial

**O que é**: Diferença de pressão entre dois ambientes.

**Por que importa**: Controla para onde o ar flui.

**Física Básica**:
- Ar flui de pressão alta → pressão baixa
- Se sala cirúrgica está +20 Pa (acima de corredor) → ar sai da cirurgia para corredor
- Se isolamento está -20 Pa (abaixo de corredor) → ar entra corredor para isolamento

**Propósito**:
- **Pressão Positiva**: Protege ambiente (cirurgia, transplante) contra contaminação externa
- **Pressão Negativa**: Protege ambiente externo contra contaminação interna (tuberculose, COVID)

**Medida**: Manômetro digital, unidade: **Pascal (Pa)**

**Requisito NBR 7256**:
- Cirurgia: +12 a +25 Pa
- Isolamento negativo: -12 a -25 Pa

---

### Conceito 3: Filtragem (Eficiência de Remoção)

**Escala de Filtros** (do mais simples ao mais eficiente):

| Código | Nível | Remoção Típica | Uso |
|--------|-------|----------------|-----|
| G3 | Pré-filtro | 60% (>10 µm) | Corredor, admin |
| G4 | Pré-filtro | 85% (>10 µm) | Primeira etapa |
| F7 | Filtro fino | 95% (>1 µm) | Segunda etapa |
| F8 | Filtro fino | 98% (>0.5 µm) | Terceira etapa (raro) |
| H13 | HEPA | 99.97% (>0.3 µm) | Cirurgia, isolação |
| H14 | HEPA Ultra | 99.99% (>0.3 µm) | Laboratório P4 |

**Interpretação**:
- H13 remove 99.97% das partículas ≥ 0.3 µm
- "Deixa passar" 0.03% = **1 em 3.333 partículas**
- Vírus (0.1 µm) passam em núcleos de gotículas (1-100 µm)

**Requisito NBR 7256**:
- Cirurgia: G4 + F7 + H13 (3 estágios)
- Isolamento negativo: G4 + F7
- Administração: G3 + G4

---

## Seção 3: Exemplo Resolvido - Sala Cirúrgica Hospitalar

### Cenário

Um hospital de 200 leitos está reformando seu bloco cirúrgico. Você é designado projetista HVAC. 

**Dados**:
- Sala cirúrgica: 40 m² (6m × 6.7m × 3m pé-direito)
- Ocupação: 6 pessoas (cirurgião, auxiliar, enfermeira, dois técnicos, paciente)
- Equipamentos geradores de calor: focos cirúrgicos (400W), eletrocautério, monitor, bomba infusora
- Funciona: 8-12 horas/dia

**Tarefa**: Calcule o balanço de vazão de ar conforme NBR 7256.

### Solução Passo-a-Passo

#### **Passo 1: Determinar Volume da Sala**

```
Volume = Comprimento × Largura × Altura
Volume = 6 m × 6.7 m × 3 m = 120.6 m³
```

#### **Passo 2: Aplicar Requisito de Renovação (NBR 7256)**

Conforme Tabela de NBR 7256, sala cirúrgica requer **mínimo 15 trocas de ar por hora**.

```
Trocas/hora = 15
Frequência = 15 ÷ 3600 s = 1/240 trocas por segundo
```

#### **Passo 3: Calcular Vazão Total**

```
Vazão Total = Volume × Frequência (em s⁻¹)
Vazão Total = 120.6 m³ × (15 ÷ 3600) s⁻¹
Vazão Total = 120.6 × 0.00417
Vazão Total = 0.503 m³/s = 503 L/s

Arredondando: 500 L/s (taxa de projeto)
```

#### **Passo 4: Distribuir entre Renovação e Recirculação**

NBR 7256 permite até 50% de recirculação em cirurgia, **mas** esse é o máximo permissível. Muitos hospitais usam 100% renovação (ar novo) por segurança aumentada.

**Opção A: Máximo Permitido (50% recirculação)**
```
Renovação mínima = 50% × 500 = 250 L/s (ar novo)
Recirculação = 50% × 500 = 250 L/s (ar interno filtrado)
Total = 500 L/s ✓
```

**Opção B: Melhor Prática (100% renovação)**
```
Renovação = 500 L/s (ar novo, sempre)
Recirculação = 0 L/s
Total = 500 L/s ✓
```

**Recomendação**: Use Opção B (100% renovação). Reduz risco e justifica-se por segurança em cirurgia.

#### **Passo 5: Determinar Vazão de Exaustão**

**Princípio**: Ar que entra deve sair (balanço de massa).

```
Se Renovação = 500 L/s
E Recirculação = 0 L/s
Então Exaustão = 500 L/s
```

**Com Pressão Positiva**: Na prática, para manter +20 Pa, precisa exaurir **ligeiramente menos** que entra (offset). Isso será calculado em Módulo 3.

#### **Passo 6: Especificar Filtração**

NBR 7256 exige 3 estágios para cirurgia:
```
Entrada: G4 (85% eficiência)
   ↓
Troca intermediária: F7 (95% eficiência)
   ↓
Saída final (antes da sala): H13 (99.97% eficiência)
```

---

### Resultado Final

```
┌──────────────────────────────────────────────────┐
│ ESPECIFICAÇÃO SALA CIRÚRGICA (40 m²)             │
├──────────────────────────────────────────────────┤
│ Vazão Total:              500 L/s                │
│ Renovação (ar novo):      500 L/s (100%)         │
│ Recirculação:             0 L/s                  │
│ Exaustão:                 ~490 L/s (com offset)  │
│ Trocas de ar:             15 h⁻¹                 │
│ Pressão diferencial:      +20 Pa (positiva)      │
│ Filtração:                G4 + F7 + H13          │
│ Temperatura:              20-24°C                │
│ Umidade Relativa:         45-55%                 │
└──────────────────────────────────────────────────┘
```

---

## Seção 4: Ferramenta Prática - Checklist de Classificação de Ambiente

Use este checklist para classificar QUALQUER ambiente hospitalar:

```
PASSO 1: Qual é o ambiente?
[ ] Cirurgia/Centro Cirúrgico       → CRÍTICO
[ ] UTI/Unidade de Terapia Intensiva → CRÍTICO
[ ] Isolamento (qualquer tipo)       → CRÍTICO
[ ] Parto/Neonatal                   → CRÍTICO
[ ] Enfermaria/Quarto               → SEMI-CRÍTICO
[ ] Farmácia/Medicamentos           → SEMI-CRÍTICO
[ ] Corredor/Administrativo         → NÃO-CRÍTICO
[ ] Sala de Espera                  → NÃO-CRÍTICO

PASSO 2: Se respondeu "Não tem certeza", pergunte:
[ ] Pacientes com feridas abertas?           → Sim = CRÍTICO
[ ] Pacientes imunocomprometidos?            → Sim = CRÍTICO
[ ] Risco de transmissão aérea de patógeno?  → Sim = CRÍTICO
[ ] Medicamentos sensíveis a contaminação?   → Sim = SEMI-CRÍTICO

PASSO 3: Consulte NBR 7256 Tabela de Renovação
Ambiente Crítico?
  Sim  → Renovação ≥ 12 trocas/h, Pressão +/-, Filtro ≥ F7 + H13
  Não  → Consulte tabela correspondente
```

---

## Seção 5: Checkpoint - Valide Seu Aprendizado

### Pergunta 1: Fundamentação Normativa

**Uma sala de isolamento respiratório (tuberculose) requer pressão negativa. De qual norma vem esse requisito, e qual é o intervalo de pressão?**

**Opções**:
- A) RDC 50, -6 a -12 Pa
- B) NBR 7256, -12 a -25 Pa ✓
- C) ASHRAE 170, -20 a -30 Pa
- D) Critério exclusivamente médico, sem norma

**Resposta**: **B** (NBR 7256, -12 a -25 Pa)

**Explicação**: NBR 7256 Tabela de Ambientes estabelece que isolamentos respiratórios devem manter pressão diferencial negativa entre -12 e -25 Pa. RDC 50 complementa com requisitos de renovação mínima (12 trocas/h, 100% ar exterior exaurido).

---

### Pergunta 2: Classificação de Risco

**Classifique cada ambiente e justifique**:

1. Sala de cirurgia cardíaca
2. Corredor do bloco cirúrgico
3. Farmácia hospitalar
4. Quarto de isolamento para COVID-19

**Respostas Esperadas**:

1. **Sala Cirurgia Cardíaca = CRÍTICA**
   - Justificativa: Ferida cirúrgica aberta + risco elevado de infecção de sítio cirúrgico. NBR 7256 classifica todas as salas cirúrgicas como críticas.

2. **Corredor = NÃO-CRÍTICA**
   - Justificativa: Circulação apenas, sem paciente em risco. Requisito mínimo de 3-4 trocas/h.

3. **Farmácia = SEMI-CRÍTICA**
   - Justificativa: Medicamentos sensíveis a contaminação particulada, especialmente pós-abertura de ampolas. Requisito 6 trocas/h, filtro G4+F7.

4. **Isolamento COVID = CRÍTICA**
   - Justificativa: Transmissão aérea confirmada. Pressão negativa -12 a -25 Pa. 100% ar exterior. NBR 7256 classifica como crítica.

---

### Desafio Prático: Projeto Conceitual

**Cenário**: Você está consultando um pequeno hospital (50 leitos) que quer reformar sua Unidade de Terapia Intensiva (UTI). A UTI atual tem 6 leitos, pé-direito 3m, piso 100 m².

**Sua Tarefa**:

1. **Classifique a UTI** conforme risco infeccioso
2. **Determine o requisito mínimo de renovação** usando NBR 7256
3. **Calcule a vazão de ar total** necessária (use volume total da UTI = 300 m³)
4. **Especifique filtração mínima**
5. **Justifique cada decisão** com referência à norma

**Solução Esperada**:

```
1. CLASSIFICAÇÃO: CRÍTICA
   Justificativa: Pacientes em estado crítico, imunocomprometidos,
   risco elevado de infecção por ar.

2. RENOVAÇÃO (NBR 7256): 12 trocas/hora mínimo

3. CÁLCULO DE VAZÃO:
   Volume = 300 m³
   Trocas = 12 h⁻¹
   Vazão Total = 300 × (12 ÷ 3600) = 1 m³/s = 1.000 L/s

4. FILTRAÇÃO (NBR 7256):
   - Pré-filtro: G4
   - Filtro fino: F7
   - Filtro HEPA: Dependente (risco)

5. JUSTIFICATIVA:
   "UTI é ambiente crítico por concentração de pacientes
   imunocomprometidos. NBR 7256 Tabela XX exige 12 trocas/h.
   Filtração em 2 estágios (G4+F7) remove 99%+ de particulados.
   Pressão positiva +6 a +12 Pa protege contra infiltração."
```

---

## Glossário Técnico

| Termo | Definição | Unidade |
|-------|-----------|---------|
| **Trocas de ar** | Renovação completa do volume de ar na sala | h⁻¹ (por hora) |
| **Renovação** | Ar exterior introduzido na sala | L/s ou m³/h |
| **Recirculação** | Ar interno filtrado e reinserido | L/s ou m³/h |
| **Exaustão** | Ar removido da sala | L/s ou m³/h |
| **Pressão diferencial** | Diferença de pressão entre ambientes | Pa (Pascal) |
| **Filtro G4** | Pré-filtro grosseiro (85% eficiência) | - |
| **Filtro F7** | Filtro fino (95% eficiência) | - |
| **Filtro H13** | HEPA (99.97% eficiência) | - |
| **EAS** | Estabelecimento Assistencial de Saúde | - |
| **ART** | Anotação de Responsabilidade Técnica | - |
| **CREA** | Conselho Regional de Engenharia e Agronomia | - |

---

## Referências Normativas do Módulo 0

1. **ABNT NBR 7256:2021** - Sistemas de ventilação, climatização e condicionamento de ar — Requisitos de desempenho e segurança.

2. **BRASIL. ANVISA** - **RDC 50/2002** - Regulamento Técnico para planejamento, programação, elaboração e avaliação de projetos físicos de estabelecimentos assistenciais de saúde.

3. **ASHRAE Standard 170-2021** - Ventilation of Health Care Facilities (referência internacional complementar).

---

## Próximo Módulo

No **Módulo 1: Levantamento de Dados**, você aprenderá:
- Como coletar informações da instituição
- Criar matriz de requisitos
- Identificar ambientes especiais
- Comunicação com equipe hospitalar

---

**Módulo 0 Concluído ✓**

*Este módulo estabeleceu os fundamentos regulatórios e conceituais. Você agora entende o "por quê" de cada requisito HVAC hospitalar. Nos próximos módulos, aplicaremos esses princípios em projetos práticos.*

