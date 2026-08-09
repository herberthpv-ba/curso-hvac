# Módulo 4: Filtragem em Ambientes Hospitalares
### ✅ Versão Verificada com texto integral de NBR 7256:2021

---

## Resumo Executivo

A filtragem é a barreira física que separa "ar exterior contaminado" de "ar respirável seguro para paciente crítico". Este módulo usa a classificação oficial de filtros da norma (Anexo B), a regra dos três estágios de instalação física (item 11.1), e um levantamento completo de todas as combinações de filtragem realmente usadas nas sete tabelas do Anexo A — para que você nunca precise "adivinhar" qual filtro especificar.

---

## Objetivos de Aprendizagem

Ao final deste módulo, você será capaz de:

- **Classificar** filtros usando as três escalas normativas (NBR 16101, NBR ISO 16890-1, NBR ISO 29463-1)
- **Posicionar fisicamente** os estágios de filtragem na UTA conforme a sequência exigida pela norma
- **Especificar** a combinação correta de filtros para qualquer ambiente, com base em dados reais das tabelas
- **Aplicar** os requisitos de monitoramento (manômetro diferencial) e identificação (placa de dados) obrigatórios
- **Entender** o ciclo de vida e ensaio de campo obrigatório para filtros absolutos (ISO 35H)

---

## Pré-requisitos

- Módulo 0 (classificação de ambientes e risco de infecção)
- Módulo 2 (vazão de insuflação, necessária para dimensionar cada estágio)

---

## Seção 1: As Três Escalas de Classificação (Anexo B)

A norma reconhece **três sistemas de classificação simultâneos**, porque o mercado brasileiro está em transição entre eles. Você vai encontrar as três em catálogos de fabricantes — é preciso saber ler todas.

### Sistema 1: ABNT NBR 16101 (Tabela B.1) — o mais usado nas tabelas do Anexo A

| Grupo | Classe | Critério |
|-------|--------|----------|
| Grossos | G1 | Arrestância 50 ≤ Eg < 65% |
| Grossos | G2 | Arrestância 65 ≤ Eg < 80% |
| Grossos | G3 | Arrestância 80 ≤ Eg < 90% |
| Grossos | **G4** | Arrestância ≥ 90% |
| Médios | **M5** | Eficiência 40 ≤ Ef < 60% (partículas 0,4 µm) |
| Médios | M6 | Eficiência 60 ≤ Ef < 80% |
| Finos | F7 | Eficiência 80 ≤ Ef < 90% |
| Finos | **F8** | Eficiência 90 ≤ Ef < 95% |
| Finos | F9 | Eficiência ≥ 95% |

> <cite>"Os critérios de classificação dos filtros grossos, médios e finos são apresentados na Tabela B.1 e consideram a eficiência da filtragem para o tamanho de partícula de 0,4 µm."</cite>

### Sistema 2: ABNT NBR ISO 16890-1 (Tabela B.2) — baseado em PM (Particulate Matter)

| Denominação | Requisito | Eficiência Obtida |
|-------------|-----------|---------------------|
| ISO grosso | ePM10 < 50% | Arrestância inicial |
| ISO ePM10 | ePM10 ≥ 50% | ePM10 |
| ISO ePM2,5 | ePM2,5 ≥ 50% | ePM2,5 |
| ISO ePM1 | ePM1 ≥ 50% | ePM1 |

> <cite>"Não existe relação ou equivalência direta entre as classes de efic iência definidas por estas normas [16101 e ISO 16890-1]. [...] Os filtros devem ser classificados pelos ensaios conforme os procedimentos de cada uma delas."</cite>

**Isso é importante**: a norma **proíbe explicitamente** que você converta "de cabeça" uma classificação G4/F8 em ePM equivalente. Se um fabricante só fornece dados ISO 16890-1, a Tabela B.3 (a seguir) dá uma correlação aproximada — mas apenas como referência transitória.

### Sistema 3: ABNT NBR ISO 29463-1 (Tabela B.4) — filtros de alta eficiência

| Classe | Eficiência Global | Penetração Global | Eficiência Local | Penetração Local |
|--------|---------------------|----------------------|---------------------|----------------------|
| ISO 30E | ≥ 99,90% | ≤ 0,1% | — | — |
| **ISO 35H** | **≥ 99,95%** | **≤ 0,05%** | 99,75% | ≤ 0,25% |
| ISO 40H | ≥ 99,99% | ≤ 0,01% | 99,95% | ≤ 0,05% |
| ISO 45H | ≥ 99,995% | ≤ 0,005% | 99,975% | ≤ 0,025% |

> <cite>"A eficiência indicada se refere ao tamanho de partícula de maior penetração (MPPS)."</cite>

**MPPS** (Most Penetrating Particle Size) é o tamanho de partícula mais difícil de reter — geralmente em torno de 0,3 µm. É o "pior caso" testado, por isso a eficiência declarada é conservadora.

### Correlação Aproximada (Tabela B.3 — Uso Transitório Apenas)

> <cite>"A Tabela B.3 não pode ser utilizada quando o fabricante informar a eficiência do filtro ensaiado por ambos os métodos."</cite>

| Faixa Estimada ePM2,5 | Classificação Aproximada NBR 16101 |
|--------------------------|----------------------------------------|
| 0% | Sem filtro ou ≤ G4 |
| 5 a 20% | G4 |
| 20 a 35% | M5 |
| 35 a 45% | M6 |
| 45 a 65% | F7 |
| 65 a 85% | F8 |
| 85 a 95% | F9 |

---

## Seção 2: O Requisito de Base — Item 5.2.1

> <cite>"Agentes infecciosos podem permanecer em suspensão no ar e 99,97 % dos agentes microbiológicos podem ser retidos em filtros de alta eficiência, conforme Tabela B.4. Em áreas críticas, deve-se utilizar no mínimo os filtros ISO 35H, conforme Anexo A."</cite>

**Regra fixa para memorizar**: **ISO 35H é o piso mínimo absoluto para qualquer área crítica** que exija filtro de alta eficiência. Não existe especificação abaixo disso (ex: "ISO 30E") permitida para áreas críticas — apenas ISO 35H ou superior (40H, 45H), quando alta eficiência é exigida.

---

## Seção 3: Onde Fisicamente Instalar Cada Estágio (Item 11.1.4)

Este é um dos pontos mais mal executados em obra — a norma é específica sobre a **posição física** de cada filtro dentro da UTA e da rede de dutos:

> <cite>"a) todo ar exterior deve ser filtrado por meio de caixas de filtragem dedicadas, ou pelo filtro do equipamento; b) o primeiro estágio deve ser instalado antes da serpentina, de forma a pré-filtrar todo o ar a ser tratado, tanto o ar exterior quanto o ar recirculado; c) o segundo estágio deve ser instalado no lado pressurizado a jusante do ventilador de insuflação; d) o terceiro estágio deve ser instalado no lado pressurizado do duto, o mais perto possível do ambiente tratado, preferivelmente no próprio terminal de insuflação."</cite>

### Diagrama da Sequência Física

```
AR EXTERIOR ──┐
              ├──► [1º ESTÁGIO: G4] ──► SERPENTINA (resfriamento/aquecimento)
AR RECIRC. ───┘                              │
                                              ▼
                                    [VENTILADOR DE INSUFLAÇÃO]
                                              │
                                              ▼
                                    [2º ESTÁGIO: F8] (logo após o ventilador)
                                              │
                                              ▼
                                         REDE DE DUTOS
                                              │
                                              ▼
                              [3º ESTÁGIO: ISO 35H] (no terminal, dentro da sala)
                                              │
                                              ▼
                                    AMBIENTE TRATADO
```

**Por que essa ordem importa**: o 1º estágio protege a serpentina de sujeira grosseira (evitando incrustação e perda de eficiência térmica). O 2º estágio, após o ventilador, remove partículas médias antes de percorrer os dutos. O 3º estágio, **o mais perto possível do ambiente** (idealmente no próprio difusor terminal), garante que nenhuma contaminação acumulada dentro do duto (poeira, biofilme) chegue ao paciente — é a última barreira antes do ar tocar o ambiente clínico.

### Regra da Serpentina (Item 11.2.3.1)

> <cite>"As serpentinas de resfriamento e aquecimento devem ser instaladas a montante do segundo estágio de filtragem (classe mínima M5)"</cite>

**Nota de leitura cuidadosa**: este trecho especifica "classe mínima M5" para o filtro que protege a montante da serpentina — que é, na sequência descrita acima, o **1º estágio** da UTA. Ou seja: mesmo em ambientes onde a tabela do Anexo A pede G4 como pré-filtro, a exigência técnica da serpentina propriamente dita é de no mínimo M5 nesse ponto específico — verifique sempre os dois requisitos (tabela de ambiente + proteção de serpentina) ao especificar a UTA.

---

## Seção 4: Filtros de Ar de Expurgo (Item 11.1.5) — Regra Diferente

Filtros na **exaustão** de áreas contaminadas seguem lógica oposta aos de insuflação — ficam o mais próximo possível da **origem** da contaminação, não do "fim" do percurso:

> <cite>"Os filtros de ar de expurgo provenientes de coifas de exaustão e cabines de biossegurança para manipulação de agentes infecciosos, químicos ou radioativos, bem como a exaustão de ambientes AII, devem [...] ser instalados no lado de aspiração do exaustor e o mais próximo possível da fonte de contaminação, de forma a minimizar o comprimento do trecho contaminado do duto."</cite>

**Aplicação prática**: em um quarto AII com exaustão total, o filtro (tipicamente ISO 35H em caixa "bag-in bag-out" — ver Módulo 0, glossário) deve ficar **na saída do quarto**, antes de percorrer qualquer duto — não na sala de máquinas distante.

---

## Seção 5: Monitoramento e Identificação Obrigatórios

### Manômetro Diferencial (Item 11.1.6)

> <cite>"O segundo e o terceiro estágios de filtragem devem ser monitorados individualmente, por manômetro diferencial ou outro dispositivo com essa destinação medindo a perda de pressão do ar que passa pelo filtro. O manômetro deve ser instalado permanentemente."</cite>

**Por que só 2º e 3º estágio, não o 1º?** O pré-filtro (1º estágio, geralmente G4) é trocado com alta frequência por rotina simples de manutenção — monitorar sua perda de carga individualmente tem custo-benefício baixo. Já os estágios finos e de alta eficiência (2º e 3º) são caros e sua saturação afeta diretamente a vazão entregue ao ambiente crítico — por isso exigem monitoramento permanente.

### Placa de Identificação (Item 11.1.7)

Cada estágio de filtragem deve ter placa afixada com:

> <cite>"a) nomenclatura, classe e dimensões do filtro conforme a ABNT NBR 16101; b) a eficiência de filtragem e a Norma de ensaio; c) o tipo de meio filtrante; d) a vazão de ar e a correspondente perda de carga inicial; e) a pressão diferencial máxima admissível."</cite>

**Dica de projeto**: inclua essa placa como item de especificação técnica no memorial descritivo — muitos projetistas esquecem e ela é frequentemente cobrada em vistoria de comissionamento (Módulo 9).

### Ensaio de Campo Obrigatório para Filtro Absoluto (Item 11.1.3)

> <cite>"Os filtros absolutos (ISO 35H) devem ser ensaiados em campo, conforme a ABNT NBR ISO 14644-3, quando de sua instalação, substituição e por período estabelecido pelo profissional responsável, com prazo não superior a um ano, confirmando sua estanqueidade e integridade."</cite>

**Implicação de projeto**: prever, desde a especificação, **acesso físico** para a sonda de ensaio de integridade (teste de aerossol de desafio) em todo filtro ISO 35H instalado — isso significa espaço de manutenção e pontos de amostragem antes/depois do filtro, não apenas o filtro em si.

---

## Seção 6: Combinações Reais de Filtragem — Levantamento Completo das Tabelas A.1–A.7

Ao invés de "regras gerais", aqui está o **padrão real** de especificação encontrado em toda a norma, organizado por nível de exigência:

### Nível 1 — Filtragem Simples (ambientes não-críticos / apoio)

| Combinação | Ambientes Típicos (exemplos reais da norma) |
|--------------|-------------------------------------------------|
| **G4** (único estágio) | Lavanderia — sala de recebimento, processamento, área de preparo de roupa limpa |
| **M5** (único estágio) | Internação — quarto individual (Tab. A.2); área de exercícios de fisioterapia (Tab. A.7); sala do gerador de ozônio (Tab. A.6) |

### Nível 2 — Filtragem Padrão (a mais comum na norma)

| Combinação | Ambientes Típicos |
|--------------|------------------------|
| **G4 + F8** | Corredores, enfermarias, UTI padrão (Tab. A.2), salas de exame, salas de procedimento, farmácia de dispensação, central de material esterilizado, sala de terapia com bomba de cobalto (Tab. A.5), sala de sim./terapia (Tab. A.5) |
| **G4 + M5** | Lactário — manipulação e envase, preparo e envase de fórmulas (Tab. A.6) |

### Nível 3 — Filtragem Crítica (3 estágios, com alta eficiência)

| Combinação | Ambientes Típicos |
|--------------|------------------------|
| **G4 + F8 + ISO 35H** | Sala de cirurgia (Tab. A.3), antecâmara de sala de cirurgia, sala de apoio a cirurgias especializadas, quarto PE de transplantado alogênico/TMO (Tab. A.2), quarto AII **com recirculação** (Tab. A.2), sala de nutrição parenteral com cabine biológica (Tab. A.6), sala de terapia braquiterapia invasiva (Tab. A.5) |

**Padrão claro**: o terceiro estágio (ISO 35H) só aparece quando **há recirculação em ambiente crítico** ou quando o ambiente é PE/AII de **nível de risco 3**. Ambientes de nível 2, mesmo sendo PE (como a UTI padrão), geralmente ficam em G4+F8 — dois estágios bastam quando a exigência de renovação/movimentação já é mais branda.

---

## Seção 7: Exemplo Resolvido — Especificando a UTA Completa de uma Sala de Cirurgia

Usando os dados já calculados no Módulo 2 (sala de cirurgia, 837,5 L/s de vazão total insuflada):

```
┌───────────────────────────────────────────────────────────┐
│ ESPECIFICAÇÃO DE FILTRAGEM — UTA SALA DE CIRURGIA           │
├───────────────────────────────────────────────────────────┤
│ Vazão de projeto: 837,5 L/s (3.015 m³/h)                    │
│                                                                │
│ ESTÁGIO 1 (pré-filtro, antes da serpentina):                │
│   Classe: G4                                                 │
│   Posição: entrada de ar exterior + ar recirculado           │
│   Placa de dados: obrigatória (item 11.1.7)                  │
│                                                                │
│ ESTÁGIO 2 (filtro fino, pós-ventilador):                     │
│   Classe: F8                                                 │
│   Posição: lado pressurizado, a jusante do ventilador        │
│   Monitoramento: manômetro diferencial permanente            │
│   Placa de dados: obrigatória                                │
│                                                                │
│ ESTÁGIO 3 (alta eficiência, terminal):                       │
│   Classe: ISO 35H                                             │
│   Eficiência mínima: 99,95% (global) / 99,75% (local, MPPS)  │
│   Posição: terminal de insuflação, dentro da sala             │
│   Monitoramento: manômetro diferencial permanente             │
│   Ensaio de campo: na instalação + anual (NBR ISO 14644-3)   │
│   Placa de dados: obrigatória                                │
│   Acesso para sonda de ensaio: prever no projeto físico      │
└───────────────────────────────────────────────────────────┘
```

---

## Seção 8: Checkpoint — Valide Seu Aprendizado

### Pergunta 1

**Qual é a diferença física de posicionamento entre um filtro de insuflação (3º estágio) e um filtro de ar de expurgo (exaustão de AII)?**

**Resposta**: O filtro de insuflação (3º estágio) fica **o mais perto possível do ambiente**, no terminal — última barreira antes do ar tocar o paciente. O filtro de ar de expurgo fica **o mais perto possível da fonte de contaminação**, na saída do ambiente contaminado, para minimizar o trecho de duto que carrega ar sujo (item 11.1.5).

### Pergunta 2

**Uma UTI padrão (não AII) usa filtragem G4+F8 ou G4+F8+ISO35H, segundo a Tabela A.2?**

**Resposta**: **G4 + F8** (2 estágios). O terceiro estágio ISO 35H só é exigido quando a UTI precisa isolar um paciente (configuração AII, nível de risco 3), não na configuração padrão PE de nível 2.

### Desafio Prático

**Você está especificando a UTA de um quarto AII que usará recirculação (conforme decidido no Módulo 2, Opção B). Monte a especificação de filtragem completa, incluindo o requisito de ensaio de campo.**

**Solução esperada**:

```
Classificação exigida: G4 + F8 + ISO 35H (3 estágios, por ser 
AII com recirculação, conforme Tabela A.2)

Estágio 1 (G4): antes da serpentina, protege equipamento
Estágio 2 (F8): pós-ventilador, monitorado por manômetro
Estágio 3 (ISO 35H): terminal, dentro do quarto
  - Eficiência mínima 99,95% global
  - Ensaio de campo obrigatório na instalação (NBR ISO 14644-3)
  - Reensaio periódico, prazo não superior a 1 ano
  - Prever acesso físico para sonda de ensaio de integridade
  - Placa de identificação obrigatória

Observação adicional: por ser ambiente AII (isolamento), o ar 
de expurgo/exaustão também precisa de filtro dedicado na saída 
do quarto (não confundir com o 3º estágio de insuflação — são 
filtros diferentes, um trata o ar que entra, outro trata o ar 
contaminado que sai antes de ir para o exterior).
```

---

## Glossário do Módulo 4

| Termo | Definição |
|-------|-----------|
| **Arrestância** | Medida de eficiência para filtros grossos, baseada em ensaio gravimétrico |
| **MPPS** | Most Penetrating Particle Size — tamanho de partícula de maior penetração, usado no ensaio de filtros de alta eficiência |
| **Bag-in bag-out** | Caixa de troca segura de filtro contaminado (definição oficial, item 3.15 — ver Módulo 0) |
| **Montante / jusante** | Antes / depois, na direção do fluxo de ar |

---

## Referências Normativas do Módulo 4

1. **ABNT NBR 7256:2021**, item 5.2.1 — Risco de infecção e exigência mínima de ISO 35H em áreas críticas.
2. **ABNT NBR 7256:2021**, item 11.1 (11.1.1 a 11.1.7) — Requisitos técnicos completos de filtros do ar.
3. **ABNT NBR 7256:2021**, item 11.2.3.1 — Posicionamento de serpentinas em relação à filtragem.
4. **ABNT NBR 7256:2021**, Anexo B (informativo) — Tabelas B.1 a B.4, classificação de filtros.
5. **ABNT NBR 7256:2021**, Anexo A — Tabelas A.1 a A.7, combinações de filtragem por ambiente (fonte do levantamento da Seção 6).

---

## Próximo Módulo

No **Módulo 5: Seleção de Sistemas e Equipamentos**, usaremos a vazão (Módulo 2), pressão (Módulo 3) e filtragem (este módulo) já especificadas para decidir entre sistema central, descentralizado ou híbrido — e dimensionar a redundância exigida pela norma (item 4.2).

---

**Módulo 4 Concluído ✓ (Verificado)**

