# Módulo 2: Renovação, Recirculação e Exaustão — Balanço de Vazões
### ✅ Versão Verificada com texto integral de NBR 7256:2021

---

## Resumo Executivo

A norma fala em **renovações por hora** e **movimentações por hora** — números adimensionais que não dizem nada até você convertê-los em **vazão real (L/s ou m³/h)** para o volume específico da sua sala. Este módulo ensina exatamente essa conversão, usando as definições oficiais da norma (item 3.20 e 3.21) e dados reais das Tabelas A.1 a A.7.

---

## Objetivos de Aprendizagem

Ao final deste módulo, você será capaz de:

- **Diferenciar**, com base na definição normativa, "renovação" de "movimentação" de ar
- **Converter** trocas/hora (dado da norma) em vazão L/s (dado de projeto/equipamento)
- **Calcular** a parcela de ar recirculado quando movimentação > renovação
- **Aplicar** a regra de balanço de massa para dimensionar exaustão
- **Resolver** três casos reais extraídos diretamente das tabelas da norma

---

## Pré-requisitos

- Módulo 0 (classificação PE/AII/AO/AA, filtragem)
- Módulo 1 (ficha de levantamento de ambiente, com dados de renovação/movimentação já preenchidos)

---

## Seção 1: As Definições Exatas da Norma (Item 3.20 e 3.21)

Antes de calcular qualquer coisa, fixe as duas definições oficiais — elas são frequentemente confundidas:

> <cite>"3.20 número de movimentações de ar por hora (air changes per hour): quociente da vazão em metro cúbico por hora (m³/h) e o volume da sala em metro cúbico (m³)"</cite>

> <cite>"3.21 número de renovações de ar por hora (outside air changes per hour): quociente da vazão de ar insuflado no ambiente em metro cúbico por hora (m³/h) de ar exterior introduzido no ambiente e o volume da sala em metros cúbicos (m³)"</cite>

**Tradução prática**:

| Termo | O que conta | Inclui recirculação? |
|-------|-------------|------------------------|
| **Renovação** (outside air changes) | Só ar **vindo de fora** do prédio | ❌ Não |
| **Movimentação** (air changes) | **Todo** ar insuflado (novo + recirculado) | ✅ Sim |

**Consequência matemática direta**: movimentação ≥ renovação, sempre. Se os dois números forem iguais na tabela, significa **0% de recirculação** (100% ar exterior).

---

## Seção 2: A Fórmula de Conversão

A norma define os dois números como razão entre vazão e volume. Isso significa que, para ir de "trocas por hora" (dado da norma) para "vazão real" (dado que você precisa para especificar equipamento), a fórmula é a definição invertida:

```
Vazão (m³/h) = Nº de trocas por hora × Volume da sala (m³)
```

Para converter de m³/h para **L/s** (unidade mais usada em especificação de equipamento HVAC):

```
Vazão (L/s) = Vazão (m³/h) × 1000 ÷ 3600
            = Vazão (m³/h) ÷ 3,6
```

**Fórmula combinada (a que você vai usar o tempo todo)**:

```
Vazão (L/s) = (Volume da sala em m³ × Trocas por hora) ÷ 3,6
```

---

## Seção 3: Caso Real 1 — Sala de Cirurgia (Tabela A.3)

### Dados da Norma (já levantados no Módulo 1)

Da **Tabela A.3 — Centro cirúrgico (CC)**, linha "Sala de cirurgia":

| Parâmetro | Valor Normativo |
|-----------|-------------------|
| Tipo | PE |
| Nível de risco | 3 |
| Pressão | Positiva |
| **Vazão mínima de ar exterior** | **5 renovações/hora** |
| **Vazão mínima de ar insuflado** | **25 movimentações/hora** |
| Exaustão total do ambiente | Não |
| Filtragem | G4 + F8 + ISO 35H |

### Dados do Seu Projeto (exemplo hipotético — sala real de 40 m²)

```
Comprimento: 6,0 m
Largura: 6,7 m
Pé-direito: 3,0 m
Volume = 6,0 × 6,7 × 3,0 = 120,6 m³
```

### Cálculo Passo a Passo

**Passo 1 — Vazão total de ar insuflado (renovação + recirculação):**

```
Vazão Insuflado (L/s) = (Volume × Movimentações) ÷ 3,6
Vazão Insuflado (L/s) = (120,6 × 25) ÷ 3,6
Vazão Insuflado (L/s) = 3.015 ÷ 3,6
Vazão Insuflado (L/s) = 837,5 L/s
```

**Passo 2 — Vazão mínima de ar exterior (renovação):**

```
Vazão Renovação (L/s) = (Volume × Renovações) ÷ 3,6
Vazão Renovação (L/s) = (120,6 × 5) ÷ 3,6
Vazão Renovação (L/s) = 603 ÷ 3,6
Vazão Renovação (L/s) = 167,5 L/s
```

**Passo 3 — Parcela de ar recirculado (por diferença):**

```
Vazão Recirculação = Vazão Insuflado − Vazão Renovação
Vazão Recirculação = 837,5 − 167,5
Vazão Recirculação = 670,0 L/s
```

**Passo 4 — Percentual de recirculação (informativo, útil para conversa com cliente):**

```
% Recirculação = (670,0 ÷ 837,5) × 100 = 80%
```

### Resultado Final

```
┌──────────────────────────────────────────────────┐
│ ESPECIFICAÇÃO SALA DE CIRURGIA (40 m², 120,6 m³)  │
├──────────────────────────────────────────────────┤
│ Vazão Total Insuflada:     837,5 L/s (3.015 m³/h) │
│ Renovação (ar exterior):   167,5 L/s (20% do total)│
│ Recirculação (ar filtrado): 670,0 L/s (80% do total)│
│ Filtragem: G4 + F8 + ISO 35H (3 estágios)          │
│ Pressão: Positiva (referência corredor = 0)        │
└──────────────────────────────────────────────────┘
```

> ⚠️ **Correção em relação a versões anteriores deste curso**: a proporção de recirculação em sala de cirurgia (80% neste exemplo) é **bem maior** do que eu havia inicialmente estimado. Isso é coerente com a exigência de **25 movimentações/hora** — atingir esse volume só com ar novo (renovação) seria energeticamente inviável na maioria dos projetos; por isso a norma permite recirculação alta, desde que compensada pelo terceiro estágio de filtragem ISO 35H.

---

## Seção 4: Caso Real 2 — UTI Padrão (Tabela A.2)

### Dados da Norma

Da **Tabela A.2 — Internação**, linha "Unidades de tratamento intensivo (não limitada a UCO, UTI e UTI Neonatal)":

| Parâmetro | Valor Normativo |
|-----------|-------------------|
| Tipo | PE |
| Nível de risco | 2 |
| Pressão | Positiva |
| **Vazão mínima de ar exterior** | **2 renovações/hora** |
| **Vazão mínima de ar insuflado** | **6 movimentações/hora** |
| Exaustão total | Não |
| Filtragem | G4 + F8 |
| Temperatura | 20–24°C |
| Umidade | Máx. 60% |

### Dados do Projeto (UTI de 5 leitos, exemplo)

```
Dimensões: 15,0 m × 10,0 m × 3,0 m (pé-direito)
Volume = 15,0 × 10,0 × 3,0 = 450 m³
```

### Cálculo

**Vazão total insuflada:**

```
Vazão Insuflado = (450 × 6) ÷ 3,6 = 2.700 ÷ 3,6 = 750 L/s
```

**Vazão de renovação (ar exterior):**

```
Vazão Renovação = (450 × 2) ÷ 3,6 = 900 ÷ 3,6 = 250 L/s
```

**Vazão de recirculação:**

```
Vazão Recirculação = 750 − 250 = 500 L/s
```

**Percentual de recirculação:**

```
% = (500 ÷ 750) × 100 = 66,7%
```

### Resultado Final

```
┌──────────────────────────────────────────────────┐
│ ESPECIFICAÇÃO UTI (5 leitos, 450 m³)              │
├──────────────────────────────────────────────────┤
│ Vazão Total Insuflada:     750 L/s (2.700 m³/h)   │
│ Renovação (ar exterior):   250 L/s (33,3% do total)│
│ Recirculação:              500 L/s (66,7% do total)│
│ Filtragem: G4 + F8 (2 estágios — sem ISO 35H)      │
│ Pressão: Positiva                                  │
└──────────────────────────────────────────────────┘
```

> 📌 **Nota de projeto**: repare que a UTI padrão (nível 2) exige menos da metade da vazão total da sala de cirurgia (750 L/s vs 837,5 L/s) apesar de ter volume quase 4× maior. Isso acontece porque a UTI usa apenas **6 movimentações/hora** contra **25** da cirurgia. A intensidade de renovação de ar é uma função direta do risco infeccioso do ambiente, não do seu tamanho.

---

## Seção 5: Caso Real 3 — Isolamento AII, Comparando Com e Sem Recirculação

Este é o caso mais didático da norma porque ela mesma oferece **duas opções de projeto** para o mesmo ambiente — permitindo comparar diretamente o efeito da recirculação na vazão de renovação necessária.

### Opção A: Quarto AII SEM recirculação (Tabela A.2)

| Parâmetro | Valor |
|-----------|-------|
| Vazão mínima ar exterior | **12 renovações/hora** |
| Vazão mínima ar insuflado | **12 movimentações/hora** |
| Filtragem | G4 + F8 (2 estágios) |
| Exaustão total | Sim |

Como renovação = movimentação = 12, **100% do ar é novo, 0% recirculado**.

### Opção B: Quarto AII COM recirculação (Tabela A.2)

| Parâmetro | Valor |
|-----------|-------|
| Vazão mínima ar exterior | **2 renovações/hora** |
| Vazão mínima ar insuflado | **12 movimentações/hora** |
| Filtragem | G4 + F8 + ISO 35H (3 estágios) |
| Exaustão total | Não |

### Cálculo Comparativo (quarto de isolamento, 30 m³)

**Opção A — Sem recirculação:**

```
Vazão Total = (30 × 12) ÷ 3,6 = 100 L/s
Vazão Renovação = (30 × 12) ÷ 3,6 = 100 L/s  (100% do total)
Vazão Recirculação = 0 L/s
```

**Opção B — Com recirculação:**

```
Vazão Total = (30 × 12) ÷ 3,6 = 100 L/s   (mesma vazão total!)
Vazão Renovação = (30 × 2) ÷ 3,6 = 16,7 L/s  (16,7% do total)
Vazão Recirculação = 100 − 16,7 = 83,3 L/s
```

### Comparação Lado a Lado

```
┌────────────────────────┬──────────────────┬──────────────────┐
│                        │  A) Sem Recirc.  │  B) Com Recirc.  │
├────────────────────────┼──────────────────┼──────────────────┤
│ Vazão Total             │      100 L/s     │      100 L/s     │
│ Ar Exterior (renovação) │      100 L/s     │      16,7 L/s    │
│ Ar Recirculado          │        0 L/s     │      83,3 L/s    │
│ Filtragem               │    G4 + F8       │  G4+F8+ISO35H    │
│ Exaustão total          │       Sim        │       Não        │
│ Custo energético (AVAC) │      Alto        │      Baixo       │
└────────────────────────┴──────────────────┴──────────────────┘
```

**Trade-off técnico explícito**: a Opção B economiza 83,3% da vazão de ar exterior que precisaria ser condicionada (aquecida/resfriada/desumidificada) — economia real de energia — mas exige o terceiro estágio de filtragem (ISO 35H, eficiência ≥99,95%) como compensação de segurança, além de sistema de exaustão de expurgo mais criterioso (o ar recirculado passa a exigir tratamento antes de retornar ao ambiente).

---

## Seção 6: Balanço de Exaustão — Regra de Massa

A norma não trata exaustão como "adivinhação" — ela distingue dois tipos de saída de ar (item 3.5 e 3.6):

> <cite>"3.5 ar de exaustão: ar retirado do ambiente por meios mecânicos e rejeitado ao exterior, que não necessita de tratamento"</cite>

> <cite>"3.6 ar de expurgo: ar contaminado retirado do ambiente por meios mecânicos e rejeitado ao exterior que necessita de tratamento"</cite>

**Regra prática de balanço**: em regime permanente, o que entra tem que sair — mas a norma permite (e exige, em ambientes com pressão definida) um pequeno desequilíbrio proposital:

```
Se ambiente é POSITIVO (ex: sala de cirurgia, +5 Pa):
   Ar que entra > Ar que sai
   (o excedente "vaza" pelas frestas para o corredor,
    empurrando contaminação para fora)

Se ambiente é NEGATIVO (ex: quarto AII, −10 Pa):
   Ar que sai > Ar que entra
   (o déficit é compensado por infiltração vinda do
    corredor, "puxando" o ar contaminado para dentro,
    nunca para fora)
```

O cálculo exato desse desequilíbrio (chamado de **offset**) é o tema do **Módulo 3** — por ora, para efeito de levantamento, retenha que a exaustão de um ambiente **crítico com pressão definida nunca é exatamente igual à vazão de insuflação**.

Para a **Tabela A.2, "Quarto AII sem recirculação"**, a norma já resolve isso diretamente ao afirmar **exaustão total = Sim**, o que significa: toda a vazão insuflada (100 L/s no nosso exemplo) é também exaurida — mais o offset negativo que cria a despressurização. Isso confirma que, nesse caso, **não há dúvida de projeto**: você exausta pelo menos os 100 L/s insuflados, mais uma margem para manter a pressão negativa.

---

## Seção 7: Ferramenta Prática — Planilha de Conversão

Use este modelo para qualquer ambiente já levantado no Módulo 1:

```
═══════════════════════════════════════════════════
CONVERSÃO RENOVAÇÃO/MOVIMENTAÇÃO → VAZÃO REAL
═══════════════════════════════════════════════════

DADOS DE ENTRADA (do Módulo 1 / Tabela A.X):
├─ Ambiente: _______________________
├─ Tabela/linha de origem: __________
├─ Volume da sala (m³): _____________
├─ Renovações/hora (ar exterior): ___
└─ Movimentações/hora (total): ______

CÁLCULOS:
├─ Vazão Total (L/s) = (Volume × Movim.) ÷ 3,6
│   = (_____ × _____) ÷ 3,6 = _____ L/s
│
├─ Vazão Renovação (L/s) = (Volume × Renov.) ÷ 3,6
│   = (_____ × _____) ÷ 3,6 = _____ L/s
│
├─ Vazão Recirculação = Total − Renovação
│   = _____ − _____ = _____ L/s
│
└─ % Recirculação = (Recirc. ÷ Total) × 100
    = _____ %

VERIFICAÇÃO:
├─ Se Renovação = Movimentação → 0% recirculação (100% ar novo)
├─ Se % Recirculação > 0% → confirmar filtragem 3 estágios
   (verificar exigência de ISO 35H na tabela de origem)
└─ Exaustão total = Sim/Não (copiar da tabela — define
   estratégia do Módulo 3)
═══════════════════════════════════════════════════
```

---

## Seção 8: Checkpoint — Valide Seu Aprendizado

### Pergunta 1

**Qual a diferença exata, segundo a definição normativa (item 3.20/3.21), entre "renovação" e "movimentação" de ar?**

**Resposta**: Renovação (3.21) conta **apenas ar exterior** introduzido no ambiente ÷ volume. Movimentação (3.20) conta **todo** ar insuflado (exterior + recirculado) ÷ volume. Movimentação é sempre ≥ renovação.

### Pergunta 2 — Cálculo

**Uma sala de procedimento (Tabela A.3: PE, nível 2, 3 renovações/h, 15 movimentações/h) tem 25 m² e pé-direito de 2,8 m. Calcule vazão total, renovação e recirculação em L/s.**

**Resposta**:
```
Volume = 25 × 2,8 = 70 m³
Vazão Total = (70 × 15) ÷ 3,6 = 291,7 L/s
Vazão Renovação = (70 × 3) ÷ 3,6 = 58,3 L/s
Vazão Recirculação = 291,7 − 58,3 = 233,4 L/s
% Recirculação = 80%
```

### Desafio Prático

**Você está orçando dois cenários para um quarto de isolamento AII de 35 m³: (A) sem recirculação, (B) com recirculação. Calcule a vazão de ar exterior de cada opção e explique, em uma frase, por que a Opção B tem custo energético menor mas custo de filtragem maior.**

**Solução esperada**:
```
Opção A (12 renovações/h = 12 movimentações/h):
  Vazão Renovação = (35 × 12) ÷ 3,6 = 116,7 L/s (100% ar novo)

Opção B (2 renovações/h, 12 movimentações/h):
  Vazão Renovação = (35 × 2) ÷ 3,6 = 19,4 L/s (só 16,7% ar novo)
  Vazão Recirculação = (35×12)÷3,6 − 19,4 = 96,9 L/s

Explicação: a Opção B precisa condicionar (aquecer/resfriar/
desumidificar) apenas 19,4 L/s de ar novo contra 116,7 L/s da 
Opção A — reduzindo drasticamente o consumo de energia da UTA. 
Em compensação, os 96,9 L/s recirculados passam pelo terceiro 
estágio de filtragem ISO 35H (≥99,95% de eficiência), que a 
Opção A dispensa — daí o custo maior de filtros e sua manutenção.
```

---

## Glossário do Módulo 2

| Termo | Definição Oficial (NBR 7256:2021) |
|-------|-------------------------------------|
| **Vazão de ar** | Volume de ar por unidade de tempo (item 3.31) |
| **Ar insuflado** | Quantidade de ar suprido por meios mecânicos a um espaço (item 3.8) |
| **Ar exterior** | Ar captado na parte externa da edificação (item 3.7) |
| **Ar de retorno** | Ar retirado do ambiente que pode ser recirculado ou rejeitado (item 3.10) |

---

## Referências Normativas do Módulo 2

1. **ABNT NBR 7256:2021**, item 3.20 e 3.21 — Definições de movimentação e renovação de ar.
2. **ABNT NBR 7256:2021**, item 3.5 e 3.6 — Definições de ar de exaustão e ar de expurgo.
3. **ABNT NBR 7256:2021**, Anexo A, Tabelas A.2 e A.3 — Valores reais usados nos exemplos deste módulo.
4. **ABNT NBR 7256:2021**, item 7.1 e 7.2 — Renovação do ar e Recirculação do ar (requisitos gerais).

---

## Próximo Módulo

No **Módulo 3: Pressurização e Controle de Fluxo de Ar**, usaremos a vazão de insuflação calculada aqui como base para determinar o **offset de exaustão** necessário — a diferença exata entre entrada e saída de ar que cria e mantém a pressão diferencial (positiva ou negativa) especificada na tabela.

---

**Módulo 2 Concluído ✓ (Verificado)**

