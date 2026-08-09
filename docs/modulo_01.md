# Módulo 1: Levantamento de Dados e Programa de Necessidades HVAC
### ⚠️ Versão 2.0 — Revisado com texto integral de NBR 7256:2021 e RDC 50/2002

---

## Resumo Executivo

Levantar dados para um projeto HVAC hospitalar não é "inventar" um formulário — é replicar, ambiente por ambiente, exatamente as colunas que as **Tabelas A.1 a A.7** (Anexo A, normativo, da NBR 7256:2021) já definem. Este módulo ensina você a usar a própria estrutura da norma como seu formulário de levantamento, e a identificar quando um ambiente do seu projeto real corresponde a qual linha da norma.

---

## Objetivos de Aprendizagem

Ao final deste módulo, você será capaz de:

- **Localizar**, nas 7 tabelas do Anexo A, o ambiente correspondente ao que está projetando
- **Extrair** de cada tabela os 7 parâmetros obrigatórios de projeto
- **Identificar** ambientes que a norma não cobre diretamente (e o que fazer nesses casos)
- **Aplicar** as notas de rodapé de cada tabela (elas mudam a interpretação dos valores)
- **Montar** uma matriz de rastreabilidade ligando seu levantamento de campo às tabelas oficiais

---

## Pré-requisitos

- Módulo 0 (Classificação PE/AII/AO/AA, níveis de risco 0–3, situação a controlar AgB/AgQ/AgR/TE/EQ)

---

## Seção 1: A Estrutura Real do Anexo A — Suas 7 Tabelas de Trabalho

A NBR 7256:2021 organiza os ambientes hospitalares em **sete tabelas normativas**, cada uma cobrindo um bloco funcional do hospital:

| Tabela | Bloco Funcional | Exemplos de Ambientes |
|--------|------------------|-------------------------|
| **A.1** | Unidade de atendimento imediato — Emergência e urgência | Recepção, triagem, sala de inalação, sala vermelha |
| **A.2** | Internação e unidade de queimados | Quartos PE/AII, UTI, enfermaria, UIQ |
| **A.3** | Centro cirúrgico (CC) | Corredor CC, antecâmara, sala de cirurgia, recuperação |
| **A.4** | Central de material esterilizado | Área suja, desinfecção, esterilização, armazenagem |
| **A.5** | Diagnóstico e terapia | Hemodinâmica, endoscopia, anatomia patológica, radioterapia, radiologia |
| **A.6** | Apoio técnico/apoio logístico | Farmácia, lactário, lavanderia, limpeza |
| **A.7** | Ambientes diversos | Sala de parto, banheiros, ambientes odontológicos |

**Cada tabela tem exatamente as mesmas 8 colunas.** Uma vez que você entende a estrutura, o levantamento vira um processo mecânico de "encontrar a linha certa".

---

## Seção 2: As 8 Colunas Obrigatórias (Sua Ficha de Levantamento)

Todas as tabelas do Anexo A seguem este formato — **use isto como seu formulário de campo**:

```
┌─────────────────────────────────────────────────────────────┐
│ FICHA DE LEVANTAMENTO POR AMBIENTE                           │
├─────────────────────────────────────────────────────────────┤
│ 1. Nome do Ambiente: ___________________________            │
│                                                                │
│ 2. Tipo (Tabela da norma): [ ] PE  [ ] AII  [ ] AO  [ ] AA   │
│                                                                │
│ 3. Nível de Risco: [ ] 1  [ ] 2  [ ] 3                       │
│                                                                │
│ 4. Situação a Controlar: [ ]AgB [ ]AgQ [ ]AgR [ ]TE [ ]EQ    │
│    (pode ter mais de uma, ex: AgB+AgQ)                       │
│                                                                │
│ 5. Nível de Pressão: [ ] Positiva [ ] Negativa [ ] Neutra    │
│                                                                │
│ 6. Vazão mín. ar exterior (renovações/hora): _____ h⁻¹       │
│                                                                │
│ 7. Vazão mín. ar insuflado (movimentações/hora): _____ h⁻¹   │
│                                                                │
│ 8. Exaustão total do ambiente: [ ] Sim  [ ] Não              │
│                                                                │
│ 9. Classe de filtragem do ar insuflado: __________            │
│                                                                │
│ 10. Temperatura (°C): ______ a ______                        │
│                                                                │
│ 11. Umidade Relativa: máx. _____%                            │
└─────────────────────────────────────────────────────────────┘
```

**Passo prático**: para cada ambiente do seu projeto, primeiro você tenta **encontrá-lo literalmente** em uma das 7 tabelas. Se encontrar, copia os 11 campos diretamente. Só entra em julgamento técnico próprio quando o ambiente **não** está listado (ver Seção 5).

---

## Seção 3: Exemplo Real — Preenchendo a Ficha com Dados da Tabela A.3

Vamos fazer o levantamento de um **Centro Cirúrgico** usando dados reais extraídos da Tabela A.3 da norma.

### Ambiente 1: Sala de Cirurgia

```
1. Nome: Sala de Cirurgia
2. Tipo: PE
3. Nível de Risco: 3
4. Situação a Controlar: AgB + AgQ + AgR
   (biológico, químico [gases anestésicos] e radiológico [se houver raio-X móvel])
5. Nível de Pressão: Positiva
6. Vazão mín. ar exterior: 5 renovações/hora
7. Vazão mín. ar insuflado: 25 movimentações/hora
8. Exaustão total: Não
9. Classe de filtragem: G4 + F8 + ISO 35H
10. Temperatura: 20 a 24°C
11. Umidade Relativa: máx. 60%
```

### Ambiente 2: Antecâmara (acesso à sala cirúrgica)

```
1. Nome: Antecâmara
2. Tipo: AO
3. Nível de Risco: 3
4. Situação a Controlar: AgB
5. Nível de Pressão: Positiva
6. Vazão mín. ar exterior: 5 renovações/hora
7. Vazão mín. ar insuflado: 25 movimentações/hora
8. Exaustão total: Não
9. Classe de filtragem: G4 + F8 + ISO 35H
10. Temperatura: 20 a 24°C
11. Umidade Relativa: máx. 60%
```

### Ambiente 3: Corredor/Circulação do Centro Cirúrgico

```
1. Nome: Corredor/Circulação CC
2. Tipo: AO
3. Nível de Risco: 1
4. Situação a Controlar: AgB
5. Nível de Pressão: Positiva
6. Vazão mín. ar exterior: 2 renovações/hora
7. Vazão mín. ar insuflado: 6 movimentações/hora
8. Exaustão total: Não
9. Classe de filtragem: G4 + F8
10. Temperatura: 20 a 24°C
11. Umidade Relativa: máx. 60%
```

**Observação de projeto**: repare que a **antecâmara** exige a MESMA vazão que a sala de cirurgia (5 renovações/25 movimentações) — isto não é coincidência. A norma trata a antecâmara como extensão do ambiente crítico, não como um corredor comum.

---

## Seção 4: Notas de Rodapé — A Parte Que Ninguém Lê (Mas Muda o Projeto)

As tabelas do Anexo A têm notas de rodapé que **alteram a leitura direta dos números**. Aqui estão as mais importantes, extraídas literalmente da norma:

### Nota sobre Antecâmaras e Pressão (Tabela A.3)

> <cite>"A pressão do corredor do centro cirúrgico deve ser positiva em relação aos ambientes adjacentes, desde que não sejam as salas cirúrgicas." / "A pressão da antecâmara (tipo bolha) deve ser sempre positiva em relação à sala de cirurgia como também em relação ao corredor."</cite>

**Implicação**: você não pode simplesmente somar +5 Pa em tudo. A hierarquia de pressão é: **antecâmara > sala de cirurgia > corredor** (quando com antecâmara tipo bolha).

### Nota sobre Anestesia em Sala de Cirurgia (6.2.2.3.2)

> <cite>"A anestesia pode ser administrada em uma sala de cirurgia, desde que os dispositivos adequados para administração de gases anestésicos estejam presentes no ambiente e que um sistema de extração e eliminação do excesso desses gases anestésicos esteja disponível."</cite>

**Implicação para o levantamento**: se a sala de cirurgia terá anestesia local, você **precisa** perguntar sobre sistema de extração de gases anestésicos — isso não aparece automaticamente na tabela, é um requisito condicional.

### Nota sobre Fluxo de Ar em Sala de Cirurgia

> <cite>"Em salas de cirurgia, a insuflação do ar deve ser projetada de forma a minimizar a turbulência sobre a mesa cirúrgica [...] utilizando o fluxo unidirecional, com velocidade do ar entre 0,2 m/s e 0,3 m/s."</cite>

> <cite>"O ar de retorno [...] deve ser captado por grelhas situadas nos quatro cantos da periferia do recinto [...] A maior parte do ar retirado, aproximadamente 70 %, deve ser captada por grelhas com a sua borda inferior a 20 cm acima do piso e o restante com a borda superior a 10 cm abaixo do forro."</cite>

**Implicação**: isso é informação de **projeto físico** (Módulo 7 do curso), mas precisa ser levantada AGORA, porque define se a sala tem espaço físico para 4 grelhas de retorno nos cantos.

### Nota sobre "Posto de Enfermagem" (recorrente em várias tabelas)

> <cite>"Recomenda-se que o posto de enfermagem atenda aos mesmos parâmetros do ambiente no qual este estiver inserido."</cite>

**Implicação prática**: você não vai achar "posto de enfermagem" como linha própria na maioria das tabelas — ele **herda** os parâmetros do ambiente onde está fisicamente localizado. Se o posto fica dentro da UTI, aplica-se a especificação da UTI.

### Nota sobre Faixas de Temperatura (recorrente)

> <cite>"As temperaturas indicadas são referenciais, podendo ser alteradas, dentro da faixa indicada, em função da necessidade da equipe médica."</cite>

**Implicação**: a temperatura não é rígida como pressão/filtragem — há flexibilidade dentro da faixa, sujeita a decisão clínica. Documente no levantamento se a equipe médica tem preferência específica.

---

## Seção 5: Quando o Ambiente NÃO Está na Tabela

Nem todo ambiente hospitalar tem linha própria nas 7 tabelas. A norma prevê isso explicitamente para alguns casos — veja o exemplo de Diagnóstico por Imagem (Tabela A.5, nota de rodapé):

> <cite>"Para as unidades e ambientes de Diagnósticos/Terapias que não foram citados nesta tabela, como tomografia, ultrassonografia, ressonância magnética e Pet-CT, recomenda-se utilizar os parâmetros de projeto definidos pelos fabricantes dos equipamentos, com base nas condições operacionais destes equipamentos bem como considerar as condições de conforto e saúde dos usuários."</cite>

**Protocolo para ambiente não listado**:

```
1. Verifique se existe ambiente ANÁLOGO em outra tabela
   (ex: "sala de exame" genérica aparece em A.5)

2. Se envolve equipamento médico de grande porte
   (ressonância, tomógrafo, acelerador linear):
   → Consulte especificação técnica do FABRICANTE primeiro
   → Depois aplique bom senso clínico (conforto, segurança)

3. Se envolve situação de biossegurança especial
   (ex: laboratório NB3):
   → NBR 7256 NÃO se aplica (ver Módulo 0, Seção 1)
   → Consulte normas de biocontenção específicas

4. Documente a decisão na matriz de rastreabilidade,
   citando a fonte usada (fabricante, norma análoga, etc.)
```

### Caso Especial: Ressonância Magnética

A RDC 50 (parte de laboratórios/equipamentos especiais, referenciada também em NBR 7256, item 6.5) traz um alerta específico:

> <cite>"No caso de equipamentos de ressonância magnética, que possuam descarga para a atmosfera de substâncias a baixa temperatura, como Hélio líquido a −269,0 ºC, deve ser motivo de extremo cuidado o local, a forma e a direção da descarga deste para evitar que seu jato, quando e se ocorrer, não atinja local com pessoas ou empena de edifício."</cite>

**Implicação para o levantamento**: se o projeto envolve sala de ressonância magnética, você precisa perguntar especificamente sobre o sistema de quench (descarga de emergência de hélio) e sua rota de saída — isso é um item de levantamento que não aparece em nenhuma tabela padrão.

---

## Seção 6: Matriz de Rastreabilidade — Consolidando o Levantamento

Depois de preencher a ficha de cada ambiente, consolide numa matriz única. Aqui está um exemplo real e completo para um pequeno centro cirúrgico (dados 100% extraídos da Tabela A.3):

| Ambiente | Tipo | Nível | Pressão | Renov. Ext. (h⁻¹) | Insufl. Total (h⁻¹) | Exaustão | Filtragem | Fonte |
|----------|------|-------|---------|---------------------|------------------------|----------|-----------|-------|
| Corredor/circulação CC | AO | 1 | Positiva | 2 | 6 | Não | G4+F8 | Tab. A.3 |
| Sala/área indução anestésica | AO | 1 | Neutra | 2 | 6 | Não | G4+F8 | Tab. A.3 |
| Antecâmara acesso à sala cirúrgica | AO | 3 | Positiva | 5 | 25 | Não | G4+F8+ISO35H | Tab. A.3 |
| Sala de cirurgia | PE | 3 | Positiva | 5 | 25 | Não | G4+F8+ISO35H | Tab. A.3 |
| Sala de procedimento | PE | 2 | Positiva | 3 | 15 | Não | G4+F8 | Tab. A.3 |
| Sala de apoio às cirurgias especializadas | PE | 3 | Neutra | 5 | 25 | Não | G4+F8+ISO35H | Tab. A.3 |
| Sala/área de recuperação anestésica | AO | 1 | Neutra | 2 | 6 | Não | G4+F8 | Tab. A.3 |
| Sala de guarda e preparo de anestésicos | AO | 1 | Negativa | 8 | 8 | Sim | G4+F8 | Tab. A.3 |

**Esta tabela é seu deliverable formal de levantamento.** Ela alimenta diretamente o Módulo 2 (cálculo de vazões em L/s) — você já tem os dados normativos; falta apenas multiplicar pelo volume real de cada sala do seu projeto específico.

---

## Seção 7: Checkpoint — Valide Seu Aprendizado

### Pergunta 1

**Durante o levantamento de uma clínica, você encontra uma "sala de exame de broncoscopia". Em qual tabela do Anexo A ela está, e qual é seu nível de risco e situação a controlar?**

**Resposta**: Tabela A.5 (Diagnóstico e terapia), bloco Endoscopia. **AO, nível de risco 2, situação AgB**. Pressão negativa, 2 renovações/hora ar exterior, 12 movimentações/hora insuflado, **exaustão total: Sim**, filtragem G4+F8.

### Pergunta 2

**Você está levantando dados de uma sala de ressonância magnética nova. A Tabela A.5 tem uma linha específica para "Sala de Ressonância Magnética"?**

**Resposta**: **Não.** Conforme nota de rodapé da Tabela A.5, ressonância magnética não está listada — deve-se usar os parâmetros do fabricante do equipamento. Além disso, é obrigatório levantar informação sobre o **sistema de quench** (descarga de hélio líquido a −269°C) e garantir rota de saída segura, conforme alerta específico da norma (item 6.5).

### Desafio Prático

**Monte a ficha de levantamento completa (11 campos) para "Quarto AII sem recirculação, com antecâmara" usando os dados reais da Tabela A.2 apresentados no Módulo 0.**

**Solução esperada**:

```
1. Nome: Quarto AII sem recirculação, com antecâmara
2. Tipo: AII
3. Nível de Risco: 3
4. Situação a Controlar: AgB
5. Nível de Pressão: Negativa
6. Vazão mín. ar exterior: 12 renovações/hora
7. Vazão mín. ar insuflado: 12 movimentações/hora
8. Exaustão total: Sim
9. Classe de filtragem: G4 + F8
10. Temperatura: 20 a 24°C
11. Umidade Relativa: máx. 60%

Observação adicional: por ser "sem recirculação", 100% do 
ar é ar exterior (renovação = movimentação = 12 h⁻¹). Se o 
projeto trocasse para "com recirculação", a renovação cairia 
para 2 h⁻¹, mas a filtragem subiria obrigatoriamente para 
G4+F8+ISO35H (3º estágio compensa a recirculação).
```

---

## Glossário Adicional do Módulo 1

| Termo | Definição Oficial |
|-------|---------------------|
| **Área compartimentada** | Compartimento contra incêndio — área separada horizontal/verticalmente por elementos de resistência ao fogo |
| **Área de internação** | Ambiente de atenção a pacientes internados para monitoração, avaliação, diagnóstico e tratamento |
| **Sala de procedimento** | Ambiente para procedimentos de baixa complexidade fora das áreas restritas de centro cirúrgico |
| **Procedimento invasivo** | Procedimento com penetração de pele, mucosas, espaços/cavidades estéreis, tecidos subepiteliais e sistema vascular |

---

## Referências Normativas do Módulo 1

1. **ABNT NBR 7256:2021**, Anexo A (normativo) — Parâmetros de projeto, Tabelas A.1 a A.7 (páginas 29 a 42 da norma).
2. **ABNT NBR 7256:2021**, item 6.5 — Ambientes operacionais, alerta sobre ressonância magnética.
3. **BRASIL. ANVISA — RDC 50/2002**, item 7.5 — Instalação de Climatização, remissão à NBR 7256.

---

## Próximo Módulo

No **Módulo 2: Renovação, Recirculação e Exaustão**, pegaremos exatamente estes dados de renovação/movimentação (em trocas por hora) e converteremos em **vazão real (L/s)** para o volume específico de cada sala do seu projeto — usando o mesmo processo demonstrado no Módulo 0, Seção 5, mas agora para todos os blocos funcionais.

---

**Módulo 1 Concluído ✓ (Versão 2.0 — Verificada)**

