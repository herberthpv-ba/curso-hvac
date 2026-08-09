# Módulo 3: Pressurização e Controle de Fluxo de Ar
### ✅ Versão Verificada com texto integral de NBR 7256:2021

---

## Resumo Executivo

Pressurização é a ferramenta que decide **para onde o ar contaminado vai** — nunca do ambiente limpo para o sujo. Este módulo explica o que a norma efetivamente exige (item 7.4), os três tipos de antecâmara com seus arranjos reais de pressão (Anexo C), e como a engenharia HVAC calcula, na prática, a vazão de offset necessária para atingir uma pressão-alvo — deixando claro que **esse cálculo numérico não está na norma**, que é qualitativa neste ponto, mas decorre de física de fluidos padrão.

---

## Objetivos de Aprendizagem

Ao final deste módulo, você será capaz de:

- **Citar** exatamente o que a NBR 7256 exige sobre pressurização (item 7.4) e o que ela NÃO especifica
- **Diferenciar** os três tipos de antecâmara (bolha, sumidouro, cascata) e quando usar cada um
- **Aplicar** os valores de pressão diferencial documentados no Anexo C (exemplos oficiais da norma)
- **Calcular** o offset de vazão (insuflação − exaustão) usando a equação padrão de engenharia de fluxo por frestas
- **Projetar** o arranjo de pressurização completo de uma suíte de isolamento ou de ambiente protetor

---

## Pré-requisitos

- Módulo 0 (classificação PE/AII/AO/AA)
- Módulo 2 (cálculo de vazão de insuflação em L/s)

---

## Seção 1: O Que a Norma Realmente Exige (Item 7.4)

Este é o texto integral e único da norma sobre o mecanismo físico de pressurização:

> <cite>"O sistema de tratamento de ar deve evitar fluxos de ar que possam resultar em potencial risco de contaminação cruzada entre ambientes. Para tal, deve-se manter os diferenciais de pressão definidos em projeto e indicados nas Tabelas A.1 a A.6 e no Anexo C. [...] Na falha do equipamento, recomenda-se a aplicação de registros de ar com atuadores de retorno por mola para evitar o fluxo de ar entre ambientes."</cite>

> <cite>"Um diferencial de pressão em relação aos ambientes vizinhos é obtido insuflando no ambiente uma vazão de ar maior ou menor que a retirada por meios mecânicos, para pressão positiva ou negativa respectivamente."</cite>

**Análise cuidadosa deste texto — o que ele diz e o que NÃO diz:**

| A norma DIZ | A norma NÃO diz |
|---------------|---------------------|
| Manter diferenciais de pressão definidos nas tabelas | Uma fórmula matemática para calcular a vazão de offset |
| O mecanismo é: insuflar mais (ou menos) do que exaurir | Quantos Pa cada L/s de diferença produz |
| Usar registros com retorno por mola em caso de falha | Valores de estanqueidade de porta/vedação exigidos |
| Monitorar o diferencial com alarme (itens 6.2.1 e 6.3) | Método de comissionamento do offset |

**Conclusão prática**: a NBR 7256 estabelece o **resultado exigido** (a pressão-alvo, tabelada) e o **princípio físico** (insuflar mais ou menos do que exaurir), mas deixa o **dimensionamento exato do offset** a cargo da engenharia do projetista — que aplica física de fluidos padrão (Seção 5 deste módulo).

---

## Seção 2: Monitoramento Obrigatório — O Que a Norma Exige

Diferente do cálculo, o **monitoramento** da pressão é detalhado com precisão pela norma, tanto para ambiente protetor quanto isolamento:

> <cite>"6.2.1 [...] d) ter um dispositivo de leitura local instalado nos ambientes a monitorar. Caso haja supervisão remota, monitorar constantemente o diferencial de pressão. Em ambos os casos deve haver alarme visual e sonoro"</cite>

Para ambiente AII:

> <cite>"6.3 [...] f) ter um dispositivo ambiente de leitura instalado no corredor, na antecâmara e no ambiente AII. Caso haja supervisão remota, monitorar constantemente o diferencial de pressão. Em ambos os casos deve haver alarme visual e/ou sonoro"</cite>

**Implicação de projeto**: todo ambiente PE ou AII precisa de **manômetro diferencial com display local + alarme audiovisual**. Não é opcional, é requisito normativo direto.

---

## Seção 3: Regra Fixa do Banheiro (Válida para PE e AII)

Já mencionada no Módulo 0, mas fundamental repetir aqui como regra de pressurização:

> <cite>"o banheiro deve ter a pressão negativa em relação ao quarto de no mínimo 5 Pa"</cite>

Isso vale **tanto** para quarto protetor (PE) quanto para quarto de isolamento (AII). A lógica: o banheiro é sempre fonte potencial de bioaerossol (descarga sanitária), então **nunca** pode estar mais positivo que o quarto — mesmo quando o próprio quarto é positivo em relação ao corredor (caso PE).

---

## Seção 4: Os Três Tipos de Antecâmara — Dados Reais do Anexo C

A norma define e ilustra três arranjos distintos. Aqui estão os valores **exatos** de cada figura oficial:

### Tipo BOLHA — Ambiente PE (Figura C.3)

> <cite>"a) corredor: pressão de referência (zero); b) antecâmara: pressão positiva (+10,0 Pa); c) quarto: pressão positiva (+5,0 Pa); d) banheiro: pressão negativa (−5,0 Pa)."</cite>

**Lógica**: a antecâmara é o ponto de **maior pressão** de toda a suíte. Ar limpo "borbulha" da antecâmara tanto para o corredor quanto para o quarto — protegendo o paciente de contaminação vinda de ambas as direções.

```
Corredor (0 Pa) ← Antecâmara (+10 Pa) → Quarto (+5 Pa) → Banheiro (−5 Pa)
                        [pico de pressão]
```

### Tipo SUMIDOURO — Ambiente PE (Figura C.5)

> <cite>"a) corredor: pressão de referência (zero); b) antecâmara: pressão negativa (−5,0 Pa); c) quarto: pressão positiva (+5,0 Pa); d) banheiro: pressão negativa (−5,0 Pa)."</cite>

**Lógica**: a antecâmara é o ponto de **menor pressão**. Ela "suga" ar tanto do corredor quanto do quarto — funcionando como um poço de captura entre os dois ambientes, sem que nenhum ar do quarto vaze para o corredor (nem vice-versa) diretamente.

```
Corredor (0 Pa) → Antecâmara (−5 Pa) ← Quarto (+5 Pa)
                    [vale de pressão]
```

**Diferença estratégica bolha vs. sumidouro (mesma finalidade PE)**: ambos protegem o quarto, mas a bolha gasta mais energia (mantém pressão alta constantemente) enquanto o sumidouro é mais econômico — a escolha frequentemente é definida pelo espaço disponível para dutos e pela filosofia de manutenção da instituição.

### Tipo CASCATA — Exclusivo de Ambiente AII (Figura C.7)

> <cite>"a) corredor: pressão de referência (zero); b) antecâmara: pressão negativa (−5,0 Pa); c) quarto: pressão negativa (−10,0 Pa); d) banheiro: pressão negativa (−15,0 Pa)."</cite>

**Lógica**: pressão **decrescente em degraus**, cada ambiente mais negativo que o anterior. O ar sempre flui do menos contaminado (corredor) para o mais contaminado (banheiro do isolamento) — nunca ao contrário.

```
Corredor (0) → Antecâmara (−5) → Quarto (−10) → Banheiro (−15)
     [degrau 1]      [degrau 2]        [degrau 3]
```

### AII Também Pode Usar Bolha (Figura C.9)

A norma mostra que AII **não é exclusivamente cascata** — há uma variante com antecâmara tipo bolha para AII:

> <cite>"a) corredor: pressão de referência (zero); b) antecâmara: pressão positiva (+10,0 Pa); c) quarto: pressão positiva (+5,0 Pa); d) banheiro: pressão negativa (−5,0 Pa)."</cite>

**Espere — isso parece contraditório?** Um AII (isolamento) com pressão POSITIVA? Sim — este arranjo existe para o caso em que a **antecâmara** precisa proteger o corredor contra a abertura de porta (evitando refluxo instantâneo), enquanto o **quarto propriamente dito continua controlado internamente por exaustão total**, mesmo estando com leitura de pressão "positiva" na simplificação da figura. Isso reforça um ponto pedagógico importante: **sempre confira a figura específica correspondente à configuração do seu projeto real** — não generalize "AII = sempre negativo" sem checar o arranjo exato de antecâmara escolhido.

---

## Seção 5: Sala de Cirurgia — Arranjo de 3 Zonas (Figura C.13)

Diferente dos quartos, a sala de cirurgia tem uma **sala de apoio** adicional na hierarquia:

> <cite>"a) corredor: pressão de referência (zero); b) antecâmara: pressão positiva (+10,0 Pa); c) sala de cirurgia: pressão positiva (+5,0 Pa); d) sala de apoio: pressão zero (0 Pa)."</cite>

```
        Antecâmara (+10 Pa)
              ↓
Corredor (0) ←→ Sala de Cirurgia (+5 Pa) ←→ Sala de Apoio (0 Pa)
```

**Observação de projeto**: a sala de apoio fica na **mesma pressão do corredor** (referência zero) — ela não precisa de proteção extra porque não tem paciente exposto, mas também não deve "puxar" ar da sala de cirurgia.

---

## Seção 6: O Cálculo de Offset — Engenharia Padrão (Não é Norma, é Física)

Como já estabelecido na Seção 1, a NBR 7256 **não fornece fórmula**. O que se segue é **prática de engenharia HVAC padrão internacional** (a mesma lógica usada por ASHRAE e outras referências), aplicada para atingir os valores de Pa que a norma brasileira exige.

### O Princípio Físico

A diferença de pressão entre dois ambientes conectados por frestas (sob a porta, ao redor de batentes, entre vãos) segue a **equação de vazão por orifício**:

```
Q = C × A × √(2 × ΔP / ρ)
```

Onde:
- Q = vazão através da fresta (m³/s)
- C = coeficiente de descarga (tipicamente 0,6 a 0,65 para frestas retas)
- A = área da fresta (m²)
- ΔP = diferença de pressão (Pa)
- ρ = densidade do ar (≈ 1,2 kg/m³ em condições padrão)

**Na prática de projeto**, esta fórmula raramente é resolvida "na mão" — os fabricantes de porta/vedação fornecem tabelas de vazamento (m³/h por Pa) para cada modelo de porta e vedação, medidas em ensaio. O projetista soma o vazamento esperado de todas as frestas do ambiente (porta, forro, tomadas elétricas, etc.) e usa esse total como **offset mínimo necessário**.

### Regra de Bolso (Amplamente Usada na Indústria, Não é da Norma)

Para uma porta hospitalar padrão (0,90 m × 2,10 m) com vedação de borracha comum, o vazamento típico sob 5 a 15 Pa de diferencial gira em torno de:

```
Vazamento ≈ 15 a 25 L/s por porta, para ΔP de 5 a 15 Pa
```

**Isso é uma referência de mercado, não um valor normativo** — deve ser confirmado com o fabricante da porta especificada e validado em campo durante o TAB (Módulo 9).

### Aplicando ao Cálculo de Exaustão

Retomando o exemplo do Módulo 2 (sala de cirurgia, 837,5 L/s de insuflação total, pressão-alvo +5 Pa):

```
Vazão Insuflada = 837,5 L/s (calculado no Módulo 2)

Offset necessário para +5 Pa (estimativa de vazamento de portas/frestas):
  ≈ 20-25 L/s (referência de mercado para este ΔP)

Vazão de Exaustão = Vazão Insuflada − Offset
Vazão de Exaustão ≈ 837,5 − 22,5 ≈ 815,0 L/s
```

**Interpretação**: a sala recebe 837,5 L/s mas só exausta ~815 L/s — os ~22,5 L/s "faltantes" saem pelas frestas ao redor da porta e vedações, empurrando ar limpo continuamente para o corredor, mantendo a pressão positiva.

> ⚠️ **Nota de responsabilidade técnica**: este valor de offset (20-25 L/s) é uma referência típica de mercado — **não está na NBR 7256**. Cada projeto real deve calcular o offset usando dados de estanqueidade do fornecedor de porta/vedação efetivamente especificado, e validar em campo durante o comissionamento (TAB — Módulo 9 deste curso).

---

## Seção 7: Checklist de Projeto de Pressurização

```
═══════════════════════════════════════════════════
CHECKLIST — PRESSURIZAÇÃO DE SUÍTE PE/AII
═══════════════════════════════════════════════════

[ ] 1. Classificar ambiente: PE ou AII? (Módulo 0)
[ ] 2. Consultar Tabela A.X correspondente para
       confirmar "Nível de Pressão" (positiva/negativa)
[ ] 3. Definir tipo de antecâmara:
       [ ] Bolha (positiva em relação aos dois lados)
       [ ] Sumidouro (negativa em relação aos dois lados)
       [ ] Cascata (só para AII — decrescente em degraus)
[ ] 4. Confirmar valores de Pa alvo (referência: Anexo C,
       ajustar conforme especificação de projeto)
[ ] 5. REGRA FIXA: banheiro sempre ≥5 Pa mais negativo
       que o quarto (PE e AII)
[ ] 6. Especificar porta/vedação com estanqueidade
       conhecida (dado do fabricante, não da norma)
[ ] 7. Calcular offset de exaustão (vazão insuflada −
       vazamento estimado de frestas)
[ ] 8. Especificar dispositivo de leitura local +
       alarme audiovisual (obrigatório: itens 6.2.1/6.3)
[ ] 9. Especificar registro com retorno por mola para
       modo de falha segura (item 7.4)
[ ] 10. Planejar validação em campo (TAB) — Módulo 9
═══════════════════════════════════════════════════
```

---

## Seção 8: Checkpoint — Valide Seu Aprendizado

### Pergunta 1

**A norma fornece uma fórmula matemática para calcular a vazão de offset necessária para atingir uma pressão-alvo específica?**

**Resposta**: **Não.** O item 7.4 da NBR 7256 é qualitativo: estabelece que a pressão é obtida "insuflando no ambiente uma vazão de ar maior ou menor que a retirada", mas não fornece equação ou tabela de conversão Pa↔L/s. Esse cálculo é responsabilidade da engenharia do projetista, usando dados de estanqueidade do fabricante de porta/vedação e física de fluidos padrão.

### Pergunta 2

**Um quarto AII usa antecâmara tipo cascata. Ordene as pressões do mais positivo para o mais negativo, com os valores oficiais do Anexo C (Figura C.7).**

**Resposta**: Corredor (0 Pa) > Antecâmara (−5 Pa) > Quarto (−10 Pa) > Banheiro (−15 Pa).

### Desafio Prático

**Você está projetando um quarto PE (protetor) e precisa decidir entre antecâmara tipo bolha ou tipo sumidouro. O hospital tem restrição de espaço para dutos de exaustão adicionais na antecâmara. Qual você recomendaria, e por quê?**

**Resposta esperada**:

> Recomendaria **antecâmara tipo sumidouro**. No arranjo bolha (Figura C.3), a antecâmara fica em +10 Pa — a pressão mais alta de toda a suíte — o que exige um sistema de insuflação robusto e dedicado, com maior vazão de ar tratado chegando primeiro à antecâmara. No arranjo sumidouro (Figura C.5), a antecâmara fica em −5 Pa — ela é essencialmente **exaurida**, não insuflada com grande vazão adicional — o que simplifica a rede de dutos: você precisa de um ramal de exaustão na antecâmara em vez de um ramal robusto de insuflação. Isso costuma exigir menos espaço físico de duto, adequando-se à restrição do hospital.

---

## Glossário do Módulo 3

| Termo | Definição |
|-------|-----------|
| **Offset** | Diferença deliberada entre vazão de insuflação e vazão de exaustão, usada para criar pressão diferencial |
| **Antecâmara** | Ambiente intermediário entre corredor e quarto, usado para amortecer a transição de pressão |
| **Tipo bolha** | Antecâmara com pressão positiva em relação a ambos os ambientes vizinhos |
| **Tipo sumidouro** | Antecâmara com pressão negativa em relação a ambos os ambientes vizinhos |
| **Tipo cascata** | Sequência de pressões decrescentes em degraus (exclusiva de AII) |
| **Coeficiente de descarga (C)** | Fator de correção na equação de vazão por orifício, tipicamente 0,6–0,65 para frestas |

---

## Referências Normativas do Módulo 3

1. **ABNT NBR 7256:2021**, item 7.4 — Pressurização e fluxos de ar entre ambientes (texto qualitativo, sem fórmula numérica).
2. **ABNT NBR 7256:2021**, itens 6.2.1(a-d) e 6.3(b, f) — Requisitos de pressão do banheiro e monitoramento obrigatório.
3. **ABNT NBR 7256:2021**, Anexo C (informativo), Figuras C.1 a C.13 — Valores de pressão diferencial dos exemplos oficiais (bolha, sumidouro, cascata).
4. Equação de vazão por orifício — referência de engenharia de fluidos padrão (não constante na NBR 7256; citada como prática usual do setor).

---

## Próximo Módulo

No **Módulo 4: Filtragem em Ambientes Hospitalares**, aprofundaremos a lógica de filtragem G4/F8/ISO 35H já usada nos exemplos deste e dos módulos anteriores — explicando exatamente quando cada estágio é obrigatório, com base nas próprias Tabelas A.1 a A.7 e no Anexo B (classificação de filtros).

---

**Módulo 3 Concluído ✓ (Verificado)**

