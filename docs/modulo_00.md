# Módulo 0: Fundamentos Regulatórios e Riscos Infecciosos
### ⚠️ Versão 2.0 — Revisado com texto integral de NBR 7256:2021 e RDC 50/2002

---

## Resumo Executivo

Os sistemas de tratamento de ar em Estabelecimentos Assistenciais de Saúde (EAS) não são apenas conforto: são infraestrutura de segurança que reduz risco biológico. Este módulo apresenta os fundamentos regulatórios de **NBR 7256:2021** (norma técnica principal, 63 páginas, que cancela e substitui a versão de 2005) e **RDC 50/2002** (que remete diretamente à NBR 7256 para os requisitos técnicos detalhados). Você sairá sabendo classificar qualquer ambiente hospitalar e localizar exatamente onde, na norma, está cada requisito.

---

## Objetivos de Aprendizagem

Ao final deste módulo, você será capaz de:

- **Localizar** as seções corretas de NBR 7256:2021 para qualquer dúvida de projeto
- **Classificar** ambientes usando a nomenclatura oficial da norma: PE, AII, AO, AA
- **Atribuir** o nível de risco correto (0 a 3) conforme critério da norma
- **Identificar** a "situação a controlar" de cada ambiente (AgB, AgQ, AgR, TE, EQ)
- **Explicar** a relação entre RDC 50 e NBR 7256 (a primeira remete à segunda)

---

## Seção 1: A Relação Entre RDC 50 e NBR 7256

### O Que Diz a RDC 50 Sobre Climatização

Isto é crucial e frequentemente mal compreendido: **a RDC 50/2002 não traz tabelas técnicas de vazão, pressão ou filtragem**. No item **7.5 – Instalação de Climatização (IC)** da RDC 50, o texto é direto:

> <cite>"Os setores destinados à assepsia e conforto, tais como salas de cirurgias, UTI, berçário, nutrição parenteral, etc., devem atender às exigências da NBR-7256."</cite>

E para setores de conforto simples:

> <cite>"Os setores com condicionamento para fins de conforto, como salas administrativas, quartos de internação, etc., devem ser atendidos pelos parâmetros básicos de projeto definidos na norma da ABNT NBR 6401."</cite>

**Ou seja**: RDC 50 estabelece a **obrigatoriedade legal** (é uma resolução da ANVISA, com força de lei sanitária) de seguir a NBR 7256 para áreas críticas. A NBR 7256 é quem contém os números.

### O Que a RDC 50 SIM Especifica Diretamente

A RDC 50 traz requisitos próprios sobre:

- **Localização de tomadas de ar**: distância mínima de **8,00 m** de dutos de exaustão de cozinhas, sanitários, laboratórios, lavanderia, centrais de gás combustível, geradores, vácuo e estacionamento.
- **Renovação forçada**: insuflamento e exaustão do tipo forçado; retorno de ar **sempre por dutos**, sendo **vedado retorno por plenum aberto**.
- **Energia de emergência**: setores com necessidade de troca de ar constante devem ter sistema energético de backup.
- **Ruído**: conforme NB-10 (atual NBR 10152, também referenciada em NBR 7256).
- **Lavanderia**: exaustão mecânica obrigatória, independente entre área "suja" e "limpa"; coifa sobre calandras a no máximo 60 cm de altura.
- **Farmácia**: duto de exaustão de capela de manipulação de quimioterápicos deve ter filtros finos.

### Escopo da NBR 7256:2021 (Seção 1)

A norma define seu próprio escopo com precisão:

> <cite>"1.2 Esta Norma se aplica aos ambientes assistenciais de saúde com classificação de risco nível 1 ou superior [...] 1.5 Esta Norma não se aplica aos ambientes não diretamente relacionados aos serviços assistenciais, como escritórios administrativos, auditórios, bibliotecas [...] regidos pela ABNT NBR 16401 [...] 1.6 Esta Norma não se aplica aos laboratórios de segurança biológica (biocontenção)."</cite>

**Implicação prática**: se o ambiente é nível 0 (equivalente a espaço público comum), você projeta pela NBR 16401 (conforto), não pela 7256. Se é laboratório de biocontenção (NB3/NB4), a 7256 também não se aplica — consulte normas específicas de biossegurança.

---

## Seção 2: Classificação Oficial de Ambientes (Seção 3 e 6 da Norma)

A NBR 7256:2021 usa **quatro categorias nomeadas**, definidas na Seção 3 (Termos e Definições). Memorize essas siglas — elas aparecem em toda tabela da norma.

### PE — Ambiente Protetor

> <cite>"3.4 ambiente protetor PE: local utilizado por pacientes imunocomprometidos com alto risco de adquirir e desenvolver infecção, bem como salas de processo e guarda de materiais e equipamentos limpos e desinfectados"</cite>

**Lógica de projeto**: proteger o PACIENTE do ambiente. Pressão positiva.

**Exemplos na norma**: quarto de transplantado, sala cirúrgica, UTI, sala de parto, farmácia de manipulação parenteral.

### AII — Ambiente de Isolamento de Infecções por Aerossóis

> <cite>"3.2 ambiente de isolamento de infecções por aerossóis AII: local para o isolamento de pacientes com suspeita ou confirmação de infecções transmitidas por aerossóis menores que 5 µm, bem como salas de processo e guarda de materiais e equipamentos potencialmente contaminados"</cite>

**Lógica de projeto**: proteger o AMBIENTE EXTERNO do paciente. Pressão negativa.

**Exemplos**: isolamento de tuberculose, COVID-19, sarampo (aerossóis <5 µm — este limite técnico específico está na definição oficial).

### AO — Ambiente Operacional

> <cite>"3.3 ambiente operacional AO: local de processo utilizado pelos profissionais de saúde que apresenta algum tipo de risco ou contaminação do operador, ou dos insumos médicos"</cite>

**Lógica de projeto**: variável — depende do processo. Pode ser positivo, negativo ou neutro.

**Exemplos**: corredores, laboratórios, sala de necropsia, lavanderia.

### AA — Ambiente Associado

> <cite>"3.1 ambiente associado AA: local relacionado às atividades do EAS utilizado pelos profissionais de saúde, pacientes, acompanhantes e visitantes, de uso comum (objetivando a qualidade do ar interior)"</cite>

**Lógica de projeto**: conforto, qualidade do ar geral. Recepção, salas de espera de nível de risco baixo.

> A norma esclarece (6.4): <cite>"os ambientes associados são ambientes de conforto que apresentam nível de risco 1 [...] Os parâmetros de projeto devem ser definidos conforme a ABNT NBR 16401, todas as Partes."</cite>

---

## Seção 3: Classificação de Risco (5.2.2) — Níveis 0 a 3

Este é o critério que a norma usa para decidir SE ela se aplica e QUÃO rigorosa a especificação deve ser.

> <cite>"a) Nível 0, área onde o risco não excede aquele encontrado em ambientes de uso público e coletivo [Nota: esses ambientes não são contemplados por esta Norma]; b) Nível 1, área onde foi constatado baixo risco de ocorrência de agravos à saúde relacionados à qualidade do ar, porém órgãos regulamentadores [...] sugerem que o risco seja considerado; c) Nível 2, área onde existem evidências de risco [...] baseadas em estudos experimentais, clínicos ou epidemiológicos; d) Nível 3, área onde existem evidências de alto risco de ocorrência de agravos sérios à saúde [...]"</cite>

**Onde encontrar o nível de cada ambiente**: Tabelas A.1 a A.7 (Anexo A, normativo) listam, ambiente por ambiente, seu nível de risco oficial. Você não "decide" o nível — você **consulta a tabela**.

### Situação a Controlar (6.1.1)

Além do nível de risco, cada ambiente tem uma "situação a controlar" que justifica os requisitos:

> <cite>"a) AgB – agente biológico; b) AgQ – agente químico; c) AgR – agente radiológico; d) TE – terapias ou processos especiais [...]; e) EQ – condições especiais para funcionamento do equipamento"</cite>

**Por que isso importa no seu projeto**: uma sala pode ter AgB **e** AgQ simultaneamente (ex.: sala de inalação — Tabela A.1). Isso muda a estratégia de filtragem e exaustão.

---

## Seção 4: Risco de Infecção e Filtragem (5.2.1)

> <cite>"Agentes infecciosos podem permanecer em suspensão no ar e 99,97 % dos agentes microbiológicos podem ser retidos em filtros de alta eficiência, conforme Tabela B.4. Em áreas críticas, deve-se utilizar no mínimo os filtros ISO 35H, conforme Anexo A."</cite>

**Fixe este número**: **99,97%** é a eficiência associada à classe **ISO 35H** (Anexo B.1.4 / Tabela B.4), equivalente ao popularmente chamado "HEPA". A norma brasileira não usa a nomenclatura "HEPA" — usa a classificação ISO 29463-1 (ISO 30E, 35H, 40H, 45H).

### Tabela B.4 (valores reais, extraídos da norma)

| Classe | Eficiência Global | Penetração Global |
|--------|-------------------|---------------------|
| ISO 30E | ≥ 99,90% | ≤ 0,1% |
| **ISO 35H** | **≥ 99,95%** | **≤ 0,05%** |
| ISO 40H | ≥ 99,99% | ≤ 0,01% |
| ISO 45H | ≥ 99,995% | ≤ 0,005% |

### Escala Completa de Filtros (Anexo B.1.1, Tabela B.1)

| Grupo | Classe | Eficiência (partículas 0,4 µm) |
|-------|--------|----------------------------------|
| Grossos | G1–G4 | Arrestância 50% a ≥90% |
| Médios | M5, M6 | 40–60% / 60–80% |
| Finos | F7, F8, F9 | 80–90% / 90–95% / ≥95% |
| Alta eficiência | ISO 30E, 35H, 40H, 45H | ≥99,90% a ≥99,995% |

**Nota importante**: não existe classe "F7" isolada sendo usada como padrão de UTI, como eu havia afirmado incorretamente antes. A norma real especifica **G4 + F8** para UTI (ver Seção 5 abaixo) — vamos aos números reais agora.

---

## Seção 5: Exemplos Reais da Tabela A.2 (Internação) — Números Verificados

Ao invés de um "exemplo resolvido" hipotético, aqui estão **dados reais extraídos diretamente da Tabela A.2** da norma:

| Ambiente | Tipo | Nível | Pressão | Renov. Ar Ext. (h⁻¹) | Movim. Insuflado (h⁻¹) | Exaustão Total | Filtragem |
|----------|------|-------|---------|------------------------|--------------------------|-----------------|-----------|
| Quarto PE c/ antecâmara — transplantado alogênico/TMO | PE | 3 | Positiva | 2 | 12 | Não | G4+F8+ISO35H |
| Quarto PE s/ antecâmara — transplantado autólogo | PE | 2 | Positiva | 2 | 12 | Não | G4+F8 |
| Quarto AII s/ recirculação, com antecâmara | AII | 3 | Negativa | 12 | 12 | Sim | G4+F8 |
| Quarto AII **com** recirculação, com antecâmara | AII | 3 | Negativa | 2 | 12 | Não | G4+F8+ISO35H |
| Unidade de Tratamento Intensivo (UTI, UCO, UTI Neonatal) | PE | 2 | Positiva | 2 | **6** | Não | G4+F8 |
| UTI **AII** com antecâmara (isolamento em UTI) | AII | 3 | Negativa | 6 | 6 | Sim | G4+F8 |
| Internação — quarto individual | AO | 2 | Positiva | 2 | 6 | Não | **M5** |
| Enfermaria/área coletiva | AO | 2 | Positiva | 2 | 6 | Não | G4+F8 |

> **Correção crítica**: a "UTI" padrão (PE, nível 2) exige apenas **6 movimentações de ar por hora** — não 12 como eu havia dito anteriormente. As **12 movimentações** aplicam-se ao ambiente **AII com antecâmara** quando a UTI precisa isolar um paciente com infecção transmitida por aerossol.

### Como Ler Estas Colunas

- **Renovação de ar exterior (h⁻¹)**: quantas trocas do volume da sala usando SOMENTE ar vindo de fora.
- **Movimentação de ar insuflado (h⁻¹)**: quantas trocas do volume total do ar insuflado (renovação + recirculação juntas). É sempre igual ou maior que a renovação.
- **Exemplo prático**: UTI padrão — só 2 trocas/hora precisam ser ar novo; as outras 4 trocas (até completar 6) podem ser ar recirculado e filtrado.

---

## Seção 6: Pressurização — Exemplos Reais do Anexo C

O Anexo C (informativo) traz **13 figuras** com arranjos de pressurização específicos. Aqui estão os valores reais usados nos exemplos oficiais da norma (não são obrigatórios universalmente — são exemplos ilustrativos de projeto, mas amplamente usados como referência de mercado):

### Ambiente PE, sem antecâmara, com recirculação (Figura C.1)

> <cite>"Os diferenciais de pressão são os seguintes: a) corredor: pressão de referência (zero); b) quarto: pressão positiva (+5,0 Pa); c) banheiro: pressão negativa (−5,0 Pa)."</cite>

### Ambiente PE, com antecâmara tipo bolha (Figura C.3)

> <cite>"a) corredor: pressão de referência (zero); b) antecâmara: pressão positiva (+10,0 Pa); c) quarto: pressão positiva (+5,0 Pa); d) banheiro: pressão negativa (−5,0 Pa)."</cite>

### Ambiente AII, com antecâmara tipo cascata (Figura C.7) — o "efeito cascata"

> <cite>"a) corredor: pressão de referência (zero); b) antecâmara: pressão negativa (−5,0 Pa); c) quarto: pressão negativa (−10,0 Pa); d) banheiro: pressão negativa (−15,0 Pa)."</cite>

Este é o padrão clássico de isolamento: a pressão fica **cada vez mais negativa** conforme você se aproxima do foco de contaminação — corredor (0) → antecâmara (−5) → quarto (−10) → banheiro (−15). O ar sempre flui do menos contaminado para o mais contaminado.

### Regra Fixa do Banheiro (válida para PE e AII)

> <cite>"o banheiro deve ter a pressão negativa em relação ao quarto de no mínimo 5 Pa"</cite>

Isso vale tanto para PE quanto para AII — o banheiro é **sempre** o ponto de pressão mais negativa dentro da suíte, seja ela protetora ou de isolamento.

### Dois Tipos de Antecâmara — Não Confunda

| Tipo | Uso Típico | Lógica |
|------|-----------|--------|
| **Bolha** | PE (proteger paciente) ou AII quando quarto precisa ficar positivo apesar do isolamento | Pressão positiva em relação a corredor E quarto — a antecâmara "empurra" ar limpo para os dois lados |
| **Sumidouro** | PE (variante) ou AII | Pressão negativa em relação a corredor E quarto — a antecâmara "puxa" ar dos dois lados, funcionando como armadilha de ar |
| **Cascata** | Exclusivo de AII | Pressão decrescente: corredor > antecâmara > quarto > banheiro |

---

## Seção 7: Checkpoint — Valide Seu Aprendizado

### Pergunta 1

**Um quarto vai receber um paciente pós-transplante de medula óssea (imunocomprometido de alto risco). Qual classificação NBR 7256 se aplica e qual filtragem mínima?**

**Resposta**: **PE (ambiente protetor), nível de risco 3**, conforme Tabela A.2 ("Quarto (PE) com antecâmara para pacientes imunocomprometidos de alto risco/Isolamento para pacientes transplantados alogênicos e autólogos/TMO"). Filtragem mínima: **G4 + F8 + ISO 35H** (3 estágios). Renovação: 2 trocas/hora de ar exterior; 12 movimentações/hora de ar insuflado total.

### Pergunta 2

**Por que a RDC 50 não traz uma tabela própria de vazões para UTI, cirurgia etc.?**

**Resposta**: Porque a RDC 50 (item 7.5.1) **remete explicitamente** à NBR 7256 para esses ambientes: <cite>"devem atender às exigências da NBR-7256"</cite>. A RDC 50 é o marco regulatório (ANVISA, força legal); a NBR 7256 é a norma técnica com os parâmetros de projeto. Você cita as duas, mas busca os números na 7256.

### Desafio Prático

**Um pequeno hospital quer instalar isolamento respiratório para tuberculose, mas o orçamento não permite sistema sem recirculação. É permitido usar recirculação em ambiente AII? Sob quais condições?**

**Resposta esperada** (conforme item 6.3, alíneas i e j da norma):

> Sim, é permitido, com condição técnica específica. **Sem recirculação**: 100% ar exterior, mínimo 12 renovações/hora, filtragem mínima 2 estágios (G4 pré-filtro + F8). **Com recirculação**: mínimo 2 renovações/hora de ar exterior + mínimo 12 movimentações/hora total (a diferença é ar recirculado), mas a filtragem sobe para **3 estágios obrigatórios**: G4 + F8 + **ISO 35H** — o terceiro estágio de alta eficiência é a compensação técnica exigida pela norma para permitir a recirculação em ambiente de isolamento.

---

## Glossário Técnico (Termos Oficiais da Norma, Seção 3)

| Termo | Definição Oficial (NBR 7256:2021) |
|-------|-------------------------------------|
| **Ar de exaustão** | Ar retirado do ambiente por meios mecânicos e rejeitado ao exterior, que **não** necessita de tratamento |
| **Ar de expurgo** | Ar contaminado retirado do ambiente, rejeitado ao exterior, que **necessita** de tratamento |
| **Ar recirculado** | Parte do ar de retorno que volta à unidade de tratamento para ser reprocessado |
| **Movimentações de ar por hora** | Vazão (m³/h) ÷ volume da sala (m³) — inclui renovação + recirculação |
| **Renovações de ar por hora** | Vazão de ar **exterior** (m³/h) ÷ volume da sala (m³) — só ar novo |
| **Área restrita** | Espaço dentro de área semirrestrita (antecâmara/vestiário de barreira) de centro cirúrgico |
| **Fluxo de ar unidirecional** | Fluxo controlado, velocidade constante, linhas aproximadamente paralelas |
| **Caixa de troca segura (bag-in bag-out)** | Caixa de filtragem que impede contato direto entre profissional e filtro contaminado |

---

## Referências Normativas do Módulo 0 (Verificadas)

1. **ABNT NBR 7256:2021** — Tratamento de ar em estabelecimentos assistenciais de saúde (EAS) — Requisitos para projeto e execução das instalações. 3ª edição, 06.08.2021, 63 páginas. Cancela e substitui NBR 7256:2005.

2. **BRASIL. ANVISA — RDC 50/2002** — Regulamento Técnico para planejamento, programação, elaboração e avaliação de projetos físicos de estabelecimentos assistenciais de saúde. Item 7.5 (Instalação de Climatização).

3. Normas citadas pela NBR 7256 como referência complementar direta: **ABNT NBR 16401** (todas as partes — conforto), **ABNT NBR 16101** e **ABNT NBR ISO 16890-1** (classificação de filtros), **ABNT NBR ISO 29463-1** (filtros de alta eficiência), **ABNT NBR 10152** (acústica).

---

## Próximo Módulo

No **Módulo 1: Levantamento de Dados**, usaremos exatamente esta classificação (PE/AII/AO/AA + nível de risco + situação a controlar) como estrutura do formulário de levantamento — nada de categorias inventadas, apenas os campos que a própria norma exige que você preencha.

---

**Módulo 0 Concluído ✓ (Versão 2.0 — Verificada)**

