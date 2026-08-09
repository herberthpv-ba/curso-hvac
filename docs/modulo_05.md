# Módulo 5: Seleção de Sistemas e Equipamentos
### ✅ Versão Verificada com texto integral de NBR 7256:2021

---

## Resumo Executivo

Este módulo cobre o que a norma **exige tecnicamente** dos equipamentos (gabinetes, ventiladores, serpentinas, umidificadores, recuperadores de energia) e das salas de máquinas — e é transparente sobre o que a norma **não decide por você**: a escolha entre sistema central, descentralizado ou híbrido é julgamento de engenharia, informado pelos requisitos normativos, mas não determinado por uma tabela de decisão da NBR 7256.

---

## Objetivos de Aprendizagem

Ao final deste módulo, você será capaz de:

- **Aplicar** o princípio normativo de redundância (item 4.2) a qualquer projeto
- **Especificar** gabinetes, ventiladores e serpentinas conforme os requisitos técnicos da norma (item 11.2)
- **Decidir com fundamento** quando usar (ou não) umidificação e recuperação de energia
- **Projetar** uma sala de máquinas em conformidade com item 11.3
- **Argumentar tecnicamente** a escolha entre sistema central e descentralizado, usando os requisitos da norma como critério, não como resposta pronta

---

## Pré-requisitos

- Módulo 2 (vazão calculada), Módulo 4 (filtragem especificada)

---

## Seção 1: O Que a Norma Exige Sobre Redundância (Item 4.2)

Este é o texto integral e único da norma sobre o tema:

> <cite>"Para os estabelecimentos assistenciais de saúde (EAS), o número e a disposição das fontes de refrigeração e dos acessórios essenciais devem ser suficientes para suportar o plano de operação do estabelecimento após uma avaria ou manutenção preventiva de qualquer uma das fontes."</cite>

**Leitura cuidadosa — o que isso significa e o que não significa:**

| A norma exige | A norma NÃO especifica |
|-----------------|----------------------------|
| Capacidade de operar após falha OU manutenção preventiva de qualquer fonte | Uma proporção fixa como "N+1" ou "N+2" |
| Isso vale para "fontes de refrigeração e acessórios essenciais" | Uma lista fechada do que conta como "acessório essencial" |
| O critério é funcional: o **plano de operação** continua | Um percentual mínimo de capacidade de backup |

**Tradução para linguagem de projeto**: a indústria HVAC usa a nomenclatura "N+1" (uma unidade reserva além da necessária) para atender esse princípio, mas **esse termo não está na norma** — é a forma prática de a engenharia cumprir a exigência funcional acima. Você precisa demonstrar, com memorial de cálculo, que mesmo com uma fonte de refrigeração parada (falha ou manutenção), o hospital continua operando dentro do seu plano de operação declarado.

> Este princípio se conecta diretamente ao item 4.1.6, já mencionado implicitamente na norma:
> <cite>"As instalações de tratamento de ar devem considerar a continuidade das operações dos EAS em condições normais ou emergenciais, internas ou externas. Recomenda-se registrar as premissas e os critérios adotados em comum acordo com o contratante no desenvolvimento do projeto."</cite>

**Implicação prática**: documente, por escrito e com aprovação do contratante, qual é exatamente "o plano de operação" que a redundância precisa sustentar (ex: hospital continua com 100% dos leitos críticos operando; ou aceita redução parcial em áreas não-críticas durante falha). Essa definição formal protege tecnicamente e legalmente o projetista.

---

## Seção 2: Requisitos de Gabinetes (Item 11.2.1)

> <cite>"Os gabinetes devem ser construídos conforme recomendações da ABNT NBR 16401-3. A classe de pressão (construção) do gabinete deve ser definida de acordo com a pressão máxima do ventilador e sua estanqueidade compatível com a rede de dutos. Os painéis removíveis, os visores e a iluminação interna devem possibilitar acesso total aos componentes internos e à sua observação em operação. A tubulação de escoamento de condensados não pode ser conectada diretamente ao sistema de esgotos."</cite>

**Checklist de especificação de gabinete**:

```
[ ] Classe de pressão compatível com pressão máxima do ventilador
[ ] Estanqueidade compatível com a classe de vazamento dos dutos
[ ] Painéis removíveis para acesso total
[ ] Visores (inspeção sem abrir o gabinete)
[ ] Iluminação interna
[ ] Dreno de condensado com quebra (air gap) — NUNCA ligação direta ao esgoto
```

O item do **dreno de condensado sem ligação direta ao esgoto** é frequentemente negligenciado em obra — existe para evitar que gases/odores do sistema de esgoto retornem pela tubulação de dreno até a UTA (e daí para o ar insuflado).

---

## Seção 3: Requisitos de Ventiladores (Item 11.2.2)

> <cite>"Os ventiladores de insuflação devem ser instalados de forma a evitar que partículas geradas no mecanismo de acionamento do moto-ventilador sejam transportadas à rede de dutos. A condensação de umidade no ventilador deve ser evitada. O critério para definição da pressão dos ventiladores é de responsabilidade do projetista do sistema."</cite>

### Uma Advertência Técnica Explícita Sobre Dimensionamento

> <cite>"Não é recomendado para o dimensionamento do ventilador, o valor da soma das perdas de pressão máximas de cada estágio de filtragem. Neste caso, deve ser avaliada a necessidade de um dispositivo de controle da vazão do ventilador em decorrência da sujidade dos filtros e sua respectiva variação da perda de pressão."</cite>

**Por que isso importa**: se você somar ingenuamente a perda de carga **máxima** (filtro sujo, no limite de troca) dos 3 estágios de filtragem (Módulo 4), o ventilador fica superdimensionado — trabalhando ineficiente na maior parte da vida útil do filtro (quando ele está limpo, a perda de carga real é muito menor). A norma recomenda, em vez disso, **um controle de vazão variável** (ex: variador de frequência com sensor de pressão) que compensa o aumento de perda de carga conforme os filtros saturam — mantendo a vazão de projeto constante sem superdimensionar o motor.

**Requisito adicional de manutenção**: voluta do ventilador deve ter porta de inspeção e dreno, permitindo limpeza interna.

---

## Seção 4: Serpentinas de Resfriamento e Aquecimento (Item 11.2.3.1)

> <cite>"Os resfriadores e aquecedores aletados devem ser fabricados de acordo com a ABNT NBR 16401-3. As serpentinas de resfriamento e aquecimento devem ser instaladas a montante do segundo estágio de filtragem (classe mínima M5) e prevendo uma distância mínima entre a serpentina de resfriamento e a serpentina de aquecimento, para acesso aos serviços de limpeza e remoção de maneira a garantir pleno acesso para o procedimento de limpeza."</cite>

**Dois requisitos distintos aqui**:
1. Proteção da serpentina: filtro classe mínima M5 a montante (já discutido no Módulo 4, Seção 3)
2. **Espaçamento físico** entre a serpentina de resfriamento e a de aquecimento — suficiente para permitir limpeza e eventual remoção de qualquer uma das duas sem desmontar a outra

### Mecanismos de Redução de Micro-organismos (Item 11.2.3.2)

A norma reconhece múltiplas tecnologias, sem obrigar uma específica:

> <cite>"Outros métodos disponíveis para redução de patógenos são utilizados em instalações de climatização. Vários métodos estão acessíveis, como por exemplo, lâmpadas ultravioleta (UVc), ionização, oxidação fotocatalítica e ozônio [...] A decisão pelo método para redução de patógenos mais adequado deve ser fundamentada pela aplicação pretendida, com base em evidências de sua eficácia, viabilidade de implementação, tempo de processo, investimento e restrições. Atenção deve ser dada na escolha de um método que preserve a saúde dos ocupantes dos ambientes, bem como a integridade e as propriedades dos materiais aplicados nas instalações."</cite>

> <cite>"É fundamental que estes métodos e tecnologias de desinfecção sejam elaborados por profissional habilitado, acompanhados por documentação quanto ao seu desempenho em relação à inativação potencial de micro-organismos, sempre baseados em padrões técnicos estabelecidos por órgãos reguladores e comprovados cientificamente."</cite>

**Tradução prática**: UV-C, ionização, ozônio etc. são **complementares** à filtragem — não substituem os estágios G4/F8/ISO35H exigidos nas tabelas. Se especificar qualquer uma dessas tecnologias, você precisa documentar formalmente a evidência científica de eficácia e a responsabilidade técnica de quem projetou o sistema — não é "plug and play" de catálogo.

---

## Seção 5: Umidificadores — Quando (Não) Usar (Item 11.2.3.3)

Este é um ponto onde a norma é **deliberadamente restritiva**:

> <cite>"Em princípio, deve-se evitar o uso de umidificadores, visto que estes podem se tornar fontes de contaminação, bem como propiciar a amplificação destes micro-organismos, e somente devem ser usados por exigência técnica específica."</cite>

**Se for tecnicamente necessário** (ex: ambiente com faixa de UR muito estreita, como algumas salas de queimados — Módulo 0, UIQ 40-60%), os requisitos são rígidos:

> <cite>"Os umidificadores a água de qualquer tipo somente podem ser instalados se for comprovado o grau adequado de assepsia da água, não sendo admissível uma concentração de mais de 1.000 UFC/L." [...] "Os umidificadores do tipo de bandeja aberta aquecida não são admissíveis por permitir a permanência de água morna estagnada, potencial meio de cultura de micro-organismos, quando a umidificação é desativada." [...] "É recomendável a drenagem automática do reservatório de água dos umidificadores sempre que o dispositivo não for acionado por período superior a 24 h."</cite>

**Checklist de umidificador (quando estritamente necessário)**:

```
[ ] Confirmar que é EXIGÊNCIA TÉCNICA ESPECÍFICA (não conforto)
[ ] Materiais de elevada resistência à corrosão
[ ] Água com concentração máxima 1.000 UFC/L (comprovada)
[ ] PROIBIDO: bandeja aberta aquecida
[ ] Drenagem automática se inativo por >24h
[ ] Se vapor: sem hidrazina ou substâncias anticorrosivas nocivas
[ ] UR resultante pós-umidificação ≤ 90% (evitar condensação)
[ ] Eliminador de gotas se houver pulverização direta de água
[ ] Fechamento automático de válvulas quando ventilador desliga
```

---

## Seção 6: Recuperação de Energia — Onde é Permitida (Item 11.2.4)

> <cite>"Os sistemas de recuperação de energia devem estar localizados a montante do segundo filtro. Se forem utilizados sistemas de recuperação de energia, os sistemas não podem permitir a contaminação cruzada, entre o ar de exaustão e o de insuflação, fluxo de ar via purga, vazamento, transporte ou transferência, exceto como a seguir."</cite>

### Regra Restritiva para Ambientes AII

> <cite>"Os sistemas de expurgo de ambientes de isolamento de infecções por aerossóis não podem ser utilizados para a recuperação de energia. EXCEÇÃO: Os sistemas de exaustão que servem aos quartos AII ou combinações de salas AII/PE podem ser servidos com sistema de recuperação de energia onde os componentes de fornecimento de ar e componentes de exaustão de ar são totalmente separados por uma barreira de ar de distância adequada para evitar a contaminação cruzada."</cite>

### Regra Restritiva para Sistemas com Potencial de Vazamento

> <cite>"Os sistemas de recuperação de energia com potencial de risco de vazamento não podem ser utilizados em áreas críticas de estabelecimentos assistenciais de saúde. Somente podem ser utilizados nas áreas regidas pela ABNT NBR 16401."</cite>

**Tradução prática**: se você quer economizar energia recuperando calor do ar de exaustão de uma sala de cirurgia ou quarto AII, **precisa** de uma tecnologia com barreira de ar física (sem risco de vazamento cruzado) — trocadores de placas com barreira física, por exemplo, não roda entálpica rotativa convencional (que tem risco inerente de vazamento entre os dois fluxos). Em ambientes puramente de conforto (administrativo, regido por NBR 16401), a restrição não se aplica.

---

## Seção 7: Sala de Máquinas (Item 11.3)

> <cite>"11.3.1 As salas de máquinas devem ser acessíveis para manutenção, sem que seja necessário circular pelos ambientes de níveis de risco 2 ou 3. Recomenda-se que sua localização seja em área técnica separada." [...] "11.3.2 As salas de máquinas devem ter acabamento liso, higienizável, em cor clara. Devem ser mantidas limpas, não sendo admissível o seu uso como depósito, ou outras finalidades." [...] "11.3.4 As salas de máquinas para equipamentos não podem servir de plenum de mistura de ar exterior e de retorno, que devem ser conduzidos por dutos até a caixa de mistura do condicionador."</cite>

### Compartimentação Contra Incêndio (Item 11.3.5)

> <cite>"Salas de máquinas destinadas a abrigar unidades de tratamento de ar em contato com rota(s) de fuga [...] devem ser separadas desta(s) por barreiras resistentes a fogo e fumaça por no mínimo 1 h, quando em edificações de até três pavimentos, ou por barreiras resistentes a fogo e fumaça por no mínimo 2 h, quando em edificações mais elevadas."</cite>

**Checklist de sala de máquinas**:

```
[ ] Acesso SEM circular por ambientes nível 2 ou 3
[ ] Localização em área técnica separada (recomendado)
[ ] Acabamento liso, higienizável, cor clara
[ ] PROIBIDO uso como depósito
[ ] Componentes com acesso facilitado (limpeza + troca de filtros)
[ ] Mistura de ar exterior/retorno APENAS por dutos até caixa
    de mistura — NUNCA usando a própria sala como plenum aberto
[ ] Se em contato com rota de fuga:
    - até 3 pavimentos: barreira resistente 1h mínimo
    - mais de 3 pavimentos: barreira resistente 2h mínimo
```

---

## Seção 8: A Decisão Central vs. Descentralizado — Julgamento de Engenharia

**Transparência metodológica**: a NBR 7256 **não contém** uma seção comparando "sistema central" versus "sistema descentralizado (splits)" com critérios de decisão prontos. O que a norma faz é impor **requisitos que qualquer topologia escolhida precisa cumprir** — redundância (Seção 1), qualidade de gabinete/ventilador/serpentina (Seções 2-4), e localização de sala de máquinas (Seção 7).

A escolha entre topologias é decisão de engenharia baseada em como cada uma **atende melhor** esses requisitos dado o contexto do projeto:

| Fator | Favorece Sistema Central | Favorece Descentralizado |
|-------|-----------------------------|-------------------------------|
| Redundância (item 4.2) | Mais fácil com UTAs duplicadas compartilhadas | Cada unidade já é redundância da vizinha (falha isolada) |
| Filtragem uniforme (Módulo 4) | Controle único, mais fácil de padronizar 3 estágios | Requer replicar filtragem em cada unidade |
| Sala de máquinas (item 11.3) | Uma sala concentrada, mais fácil compartimentar | Múltiplos pontos, mais difícil padronizar acabamento/acesso |
| Flexibilidade de expansão | Mais rígido, redimensionamento é obra maior | Adicionar unidade é mais simples |
| Ambientes críticos isolados (AII) | Precisa de ramal dedicado dentro do sistema central | Naturalmente isolado por unidade própria |

**Recomendação metodológica**: documente sua decisão de topologia citando **quais requisitos específicos da norma** (redundância, filtragem, compartimentação) a escolha atende melhor no seu contexto — isso transforma uma decisão subjetiva em decisão tecnicamente justificada e defensável.

---

## Seção 9: Checkpoint — Valide Seu Aprendizado

### Pergunta 1

**A norma especifica que redundância deve seguir proporção "N+1"?**

**Resposta**: **Não diretamente.** O item 4.2 exige que o sistema suporte o "plano de operação do estabelecimento" mesmo após avaria ou manutenção preventiva de qualquer fonte — um requisito funcional, não uma proporção numérica fixa. "N+1" é a forma usual da engenharia atender esse requisito, mas o termo não está na norma.

### Pergunta 2

**Por que a norma desaconselha somar as perdas de carga máximas dos três estágios de filtro para dimensionar o ventilador?**

**Resposta**: Porque isso superdimensiona o ventilador para a condição de "filtro totalmente sujo", que é rara ao longo da vida útil do filtro. A norma recomenda avaliar um dispositivo de controle de vazão (ex: variador de frequência com sensor de pressão) que compense a perda de carga crescente sem superdimensionar o motor.

### Desafio Prático

**Um hospital quer recuperar energia do ar de exaustão de um quarto AII usando roda entálpica convencional (que tem contato físico giratório entre fluxo de exaustão e insuflação). Isso é permitido pela norma?**

**Resposta esperada**:

> Não é permitido diretamente. O item 11.2.4.1.2 proíbe sistemas de recuperação de energia **com potencial de risco de vazamento** em áreas críticas — e roda entálpica rotativa convencional tem esse risco inerente por design (contato entre os dois fluxos de ar na mesma matriz giratória). A exceção do item 11.2.4.1.1 permite recuperação em exaustão de AII **apenas** com tecnologia que garanta **separação física total** entre os fluxos (ex: trocador de placas com barreira de ar), nunca uma roda entálpica sem essa barreira.

---

## Glossário do Módulo 5

| Termo | Definição |
|-------|-----------|
| **Voluta** | Carcaça em espiral do ventilador centrífugo |
| **UFC/L** | Unidades Formadoras de Colônia por litro — medida de contaminação microbiológica de água |
| **Plenum** | Espaço/câmara usado para distribuir ou misturar ar antes de encaminhá-lo à rede de dutos |
| **Barreira de ar** | Distância/separação física projetada para impedir contaminação cruzada entre dois fluxos de ar |

---

## Referências Normativas do Módulo 5

1. **ABNT NBR 7256:2021**, item 4.2 — Redundâncias de fontes de calor e refrigeração.
2. **ABNT NBR 7256:2021**, item 4.1.6 — Continuidade das operações.
3. **ABNT NBR 7256:2021**, item 11.2 (11.2.1 a 11.2.4) — Condicionadores de ar: gabinetes, ventiladores, serpentinas, umidificadores, recuperação de energia.
4. **ABNT NBR 7256:2021**, item 11.3 — Salas de máquinas.

---

## Próximo Módulo

No **Módulo 6: Projeto Ambiente a Ambiente**, aplicaremos tudo dos Módulos 0-5 (classificação, vazão, pressão, filtragem, equipamento) em casos completos e integrados: sala cirúrgica, isolamento, UTI, farmácia — cada um do início ao fim.

---

**Módulo 5 Concluído ✓ (Verificado)**

