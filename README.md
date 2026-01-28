# 💸 App de Finanças Pessoais com Vibe Coding

Aprenda a **criar soluções com IA** de forma criativa, guiando ferramentas como o **Copilot** e o **Lovable** com uma comunicação simples e natural. O foco é desenvolver o conceito de um **App de Organização de Finanças Pessoais**, mas, acima de tudo, aprender o **jeito Vibe de programar com IA**.

## ✨ O que é Vibe Coding

**Vibe Coding** é uma forma leve e criativa de desenvolver com IA, baseada em **conversas naturais e bem estruturadas**. Você não precisa escrever código linha por linha. Em vez disso, aprende a **guiar a IA** descrevendo suas ideias de forma clara, com **intenção e contexto**. Em outras palavras:

> Você mostra a vibe da sua ideia e a IA transforma em solução (ou em um caminho para ela).

## 🎯 Desafio

Problema: Muitas pessoas não conseguem manter um controle financeiro porque os aplicativos exigem muita entrada de dados manual, e a criação de orçamentos é vista como algo tedioso. 

Precisamos de uma solução que permita **controlar as finanças por meio de uma conversa simples**, com **agentes de IA** capazes de criar **planos de economia personalizados e automatizados**. Você deve utilizar as ideias de **Vibe Coding** e **MVP (Produto Mínimo Viável)** para desenvolver o **conceito de um aplicativo** que resolva o problema citado.

> [!IMPORTANT]
> Você **não precisa construir o código**! O foco está em **usar a IA como sua parceira criativa**, transformando boas ideias e prompts em conceitos funcionais que simulam um produto real.

## 🪄 Etapas do Desafio

### 1. Saber o que Pedir é a Chave! Otimize seus Prompts!

Antes de pedir para a IA "criar um app", é importante definir com clareza o que você quer construir e por quê. Para isso, você vai criar um **PRD (Product Requirements Document)** simplificado, uma especificação que serve como _briefing_ para a IA entender sua ideia.

Um bom PRD deve descrever o problema, quem será beneficiado, as principais funcionalidades e o que você espera que a IA entregue. Use o modelo abaixo como ponto de partida e adapte conforme o seu estilo:

```txt
# Contexto
Quero criar um aplicativo de Organização de Finanças Pessoais que funcione por meio de conversas com o usuário.  
A ideia é facilitar o controle financeiro de forma simples e natural, sem formulários manuais ou planilhas complexas.

# Problema
Muitas pessoas desistem de controlar seus gastos porque os apps atuais exigem muita entrada manual e pouca personalização.  
Quero resolver isso com uma experiência de conversa e recomendações automáticas de economia.

# Público-Alvo
Pessoas que querem começar a organizar suas finanças de forma prática e sem complicação, principalmente iniciantes.

# Funcionalidades-Chave
1. Registrar gastos via chat em linguagem natural.  
2. Classificar automaticamente as transações.  
3. Definir e acompanhar metas financeiras.  
4. Receber dicas de economia do “Agente Financeiro”.  
5. Visualizar relatórios simples e personalizados.

# Entregável da IA
Gerar um plano de MVP com as principais telas, recursos necessários e um esboço de validação inicial.  
Usar tom educativo e linguagem acessível, em português.
```

Depois de preencher o modelo, use o Copilot Web para revisar e melhorar o seu prompt antes de ir ao Lovable. A ideia é lapidar o texto até que ele fique claro, direto e reflita exatamente a sua intenção.

> [!TIP]
> Pense no PRD/Prompt como “o briefing que a IA precisa para entender sua vibe”. Portanto, quanto mais claro e intencional for o texto, mais próximas do ideal serão as respostas da IA.

### 2. Explorando o Lovable na Prática

Com seu PRD pronto e revisado, é hora de colocar a IA em ação. Abra o Lovable, cole seu prompt completo e peça o plano inicial do MVP do seu aplicativo. Como o plano gratuito limita você a 5 interações por dia, seja estratégico:
- Faça perguntas diretas e construtivas, como “crie o fluxo de telas com base nas funcionalidades listadas” ou “gere uma versão resumida do plano de MVP”;
- Priorize clareza nas instruções para aproveitar ao máximo cada resposta;

Durante essa etapa, você pode orientar a IA para três entregas principais:
1. Agente Financeiro: defina o comportamento e o tom de voz de um consultor financeiro pessoal, alinhado ao público e objetivo do app.
2. Fluxo de Telas: peça à IA para gerar o fluxo conceitual de telas com base nas funcionalidades descritas no PRD, simulando a interação por conversa.
3. Plano de MVP: solicite um resumo das 5 funcionalidades principais, dos recursos necessários e um plano de validação inicial (como medir se o app cumpre seu propósito).

> [!TIP]
> Se preferir, você pode fazer tudo com o **Copilot**. O importante é exercitar a habilidade de transformar intenções em instruções claras e testar os limites da IA como parceira criativa.

### 3. Entregando o Desafio na DIO

Finalize seu projeto criando um **repositório no GitHub** (pode ser um **fork** deste).  
No README do seu repositório, inclua:

PRD refinado no Copilot

```1) Visão Geral
Aplicativo de organização financeira via chat em linguagem natural para registrar gastos, receitas e investimentos, com categorização, metas múltiplas e gráficos de evolução e alocação.
Diferencial v2.1: módulo de investimentos agora inclui “posição consolidada por ativo” (saldo atual por ativo) e evolução da carteira — sem integração externa (valores informados manualmente).

2) Problema
Usuários desistem por excesso de entrada manual, pouca personalização e dificuldade de visualizar progresso.
Investimentos, em especial, ficam confusos quando não há visão consolidada e alocação.

3) Objetivos do MVP

Registrar transações (gastos/receitas) via chat.
Categorizar automaticamente com correção.
Criar e acompanhar múltiplas metas.
Registrar investimentos via chat (compra/venda/aporte).
Manter carteira consolidada por ativo (posição atual informada/atualizada manualmente).
Exibir gráficos: evolução e alocação de gastos + investimentos.
Dicas do “Agente Financeiro” com tom educativo.


4) Escopo do Produto (MVP)
4.1 Finanças (gastos/receitas)

Registro por chat
Categorias
Relatórios simples

4.2 Metas múltiplas

Criar várias metas
Progresso e status (ativa/concluída/atrasada)
Metas por economia / teto por categoria / aporte investimento

4.3 Investimentos (MVP com carteira consolidada – opção B)
O que entra ✅

Registrar compra/aporte e venda/resgate via chat.
Criar ativos (ex.: “Tesouro Selic”, “IVVB11”, “CDB Banco X”).
Manter posição consolidada por ativo:

Quantidade (se fizer sentido) ou “saldo atual” (R$)
Valor aplicado acumulado
Valor atual (manual)
Variação (opcional) calculada a partir do valor atual vs. aplicado



O que não entra 🚫 (ainda)

Cotação automática / preço em tempo real
Sincronizar com corretora/banco
Rentabilidade oficial por benchmark
IR / eventos complexos


5) Requisitos Funcionais (Detalhados + Critérios de Aceite)
5.1 Registro de gastos/receitas via chat
Exemplos:

“Gastei 35 no almoço”
“Recebi 250 de freelance ontem”

Critérios de aceite:

Extrair valor, tipo, data (default hoje), descrição, categoria.
Confirmar em 1 frase e permitir ajuste:

“Registrei: R$ 35 em Alimentação — hoje. Quer ajustar algo?”




5.2 Metas múltiplas
Exemplos:

“Criar meta de economizar 500 até março”
“Limite de 800 em alimentação este mês”
“Quero aportar 200 por mês em investimentos”

Critérios de aceite:

Criar mais de uma meta simultânea.
Listar metas com progresso e status.
Permitir editar/encerrar meta.
Progresso atualizado automaticamente com base nas transações (quando aplicável).


5.3 Investimentos — Registro + Posição Consolidada (B)
5.3.1 Registrar compra/aporte
Exemplos:

“Aportei 200 no Tesouro Selic hoje”
“Comprei 2 cotas de IVVB11 por 600”
“Apliquei 150 em CDB Banco X”

Regras do MVP (simples e eficaz):

Se tiver quantidade e preço total, salvar quantidade.
Se não tiver quantidade, registrar como aporte em valor (R$).

Critérios de aceite:

Extrair: ativo, classe, valor, data, tipo=compra/aporte.
Atualizar posição consolidada:

aplicado_total += valor
quantidade_total (se houver)


Confirmar:

“Registrei: aporte de R$ 200 em Tesouro Selic (Renda Fixa) — hoje.”




5.3.2 Registrar venda/resgate
Exemplos:

“Vendi 1 cota de IVVB11 por 320”
“Resgatei 200 do CDB Banco X”

Critérios de aceite:

Extrair: ativo, valor, data, tipo=venda/resgate.
Atualizar posição:

aplicado_total pode diminuir (opção) ou registrar separadamente como “resgatado_total”.
saldo_atual deve refletir o que o usuário definir (ver atualização manual abaixo).


Confirmar:

“Registrei: venda/resgate de R$ 200 em CDB Banco X — hoje.”




Para evitar complexidade contábil no MVP: não precisa calcular preço médio perfeito. Basta manter “aplicado” e “resgatado” e permitir “valor atual” manual.


5.3.3 Atualizar “valor atual” / saldo por ativo (manual)
Exemplos:

“Atualize IVVB11 para 1500”
“Meu Tesouro Selic está com 2350 agora”
“Atualizar valor atual de CDB Banco X para 980”

Critérios de aceite:

Usuário consegue definir/atualizar o valor atual por ativo.
O app recalcula:

variação = valor_atual − aplicado_total + resgatado_total (se você optar por incluir resgates)
variação_% (opcional)


Deve haver um atalho na UI “Atualizar valor atual”.


5.3.4 Posição consolidada (tela de carteira)
A carteira deve mostrar por ativo:

Ativo (nome)
Classe
Aplicado total (R$)
Valor atual (R$) — informado manualmente
Variação (R$) (opcional)
% na carteira (alocação)

Critérios de aceite:

Lista ordenável (por maior valor atual, por classe, por variação).
Filtrar por classe.
Um ativo sem valor atual deve aparecer com status: “valor atual não informado”.


6) Gráficos (Atualizado)
6.1 Finanças pessoais

Evolução de gastos por período (linha/coluna)
Gastos por categoria (barra/donut)
Receitas vs gastos (colunas agrupadas)
Saldo do período (linha)

6.2 Investimentos (novo/expandido)

Alocação por classe (donut)
Alocação por ativo (barra Top N)
Evolução do total investido (aportes acumulados) (linha)
Evolução do valor atual da carteira (linha)

baseada nos “valor_atual” informados (snapshot ao longo do tempo)



Critérios de aceite (gráficos):

Acessível por aba “Dashboard” e por chat (“mostre…”).
Filtro por período: mês atual, 3 meses, 12 meses.
Export simples (opcional no MVP): “baixar imagem” ou “resumo textual”.


7) Modelo de Dados (MVP atualizado)
7.1 Transação (gasto/receita)

id
tipo: gasto | receita
valor
data
categoria
descrição

7.2 Investimento — Movimentação (novo)
Representa o “evento” (compra/venda/aporte/resgate).

id
ativo_id
tipo: aporte/compra | venda/resgate
valor (R$)
quantidade (opcional)
data
observação (opcional)

7.3 Investimento — Ativo (cadastro)

ativo_id
nome_ativo
classe (RF, Ação, ETF, Fundo, Cripto, etc.)

7.4 Investimento — Posição Consolidada (novo)

ativo_id
aplicado_total (R$)
resgatado_total (R$) (opcional mas recomendado)
quantidade_total (opcional)
valor_atual (R$) (manual)
ultima_atualizacao_valor_atual (data)

7.5 Investimento — Snapshot de carteira (para gráfico de evolução do valor atual)

snapshot_id
data
valor_total_carteira (R$)
observação (opcional)


Por que snapshots? Porque “valor atual” muda com o tempo. Sem snapshot, você só tem o valor do dia, não o histórico.


8) Telas do MVP (Componentes sugeridos)
8.1 Chat (Home)

Caixa de mensagem
Cards de atalhos:

“Registrar gasto”
“Registrar investimento”
“Minhas metas”
“Ver gráficos”



8.2 Dashboard / Gráficos

Seletor de período
Cards resumo:

Gastos do mês / Receitas / Saldo
Valor total carteira / Alocação principal


Gráficos:

Gastos por categoria (barra)
Evolução gastos (linha)
Alocação investimentos por classe (donut)
Evolução valor total da carteira (linha)



8.3 Transações

Lista + filtros + edição rápida

8.4 Metas

Lista de metas (cards com progresso)
Botão “+ Nova meta”
Detalhe da meta

8.5 Investimentos (Carteira)

Lista de ativos (cards):

Nome + classe
Aplicado total
Valor atual (manual)
% na carteira
Botão “Atualizar valor atual”


Tela “Detalhe do ativo”:

histórico de movimentações (aportes/vendas)
atualizar valor atual
ver alocação




9) Intenções de Chat (Atualizadas)
Investimentos — posição e valor atual

“Quanto eu tenho investido no total?”
“Qual minha alocação por classe?”
“Atualize IVVB11 para 1500”
“Meu Tesouro Selic está com 2350”
“Mostre gráfico da evolução da minha carteira”
“Quais são meus maiores investimentos?”

Metas múltiplas

“Criar meta de gastar no máximo 700 com alimentação”
“Criar meta de economizar 500 até março”
“Listar minhas metas”
“Como está minha meta de aportes?”


10) Regras do “Agente Financeiro” (com investimentos)
Exemplos de dicas (educativas):

“Sua alocação está 80% em renda fixa. Quer diversificar?”
“Você atualizou valores da carteira há 10 dias. Quer atualizar hoje para manter os gráficos fiéis?”
“Você está perto de atingir a meta de aporte mensal: faltam R$ 50.”


Observação: sem dar recomendação financeira “de compra/venda”, apenas insight e educação.


11) Validação Inicial (7 dias) — atualizada para investimentos B
Métricas específicas:

% usuários que cadastraram ao menos 3 ativos
% que atualizaram “valor atual” ao menos 2 vezes na semana
uso de gráficos da carteira (≥1x/semana)
clareza percebida: “Entendi minha alocação melhor?” (survey)

Critério de sucesso (exemplo):

60% criam carteira com ≥3 ativos
50% usam “atualizar valor atual”
70% afirmam que gráficos ajudaram a entender alocação

Com base neste PRD, gere um MVP com:
1) telas: Chat, Dashboard/Gráficos, Transações, Metas, Investimentos (Carteira)
2) modelo de dados: Transação, Meta, Ativo, Movimentação, Posição Consolidada, Snapshot de Carteira
3) intents do chat e parsing (valor, data, ativo, categoria, tipo compra/venda, atualização de valor atual)
4) regras de cálculo para: aplicado_total, resgatado_total, valor_total_carteira e alocação
5) componentes de UI para gráficos e filtros
6) critérios de aceite por funcionalidade
Tom: educativo, acessível, pt-BR.
Sem integrações bancárias e sem cotações automáticas no MVP.
```

- Seu **prompt final** (PRD);  
- Prints ou pequenos vídeos das interações com a IA;
https://lovable.dev/projects/e999c3bf-9939-40fd-8e88-38278f2bf281
 
<img width="1272" height="804" alt="image" src="https://github.com/user-attachments/assets/c381a85a-cb2a-42ee-9cac-8566c87eb9c8" />

 
- Um resumo do que o seu **App de Finanças Pessoais** faz;  
- Uma breve **reflexão sobre o processo**:
  - O que funcionou bem?
    O aplicativo funcionou bem para registrar os gastos do mês. Além disso, ele dá dicas para que eu possa economizar e atingir minhas metas. 
  - O que não funcionou como o esperado?
   A princípio quis inserir uma função que possibilitasse também controlar os investimentos feitos com o dinheiro da conta. Além disso, tive problemas com o aplicativo para definir os tipos de investimentos que eu poderia aderir no aplicativo.

  - O que aprendeu sobre conversar com IAs?
    A IA responde melhor quando eu dou contexto + restrições claras, por exemplo: “é MVP”, “sem integração bancária”, “tom educativo”, “quais telas”, “quais dados”.
  Aprendi que é importante fazer perguntas do tipo: “o que entra e o que não entra?” e pedir critérios de aceite, porque isso transforma uma ideia em algo construível.
  Também percebi que conversar com IA é um processo iterativo: eu preciso refinar (testar, ajustar, esclarecer) em vez de esperar que tudo fique perfeito no primeiro prompt.

> [!TIP]
> Publique seu repositório e compartilhe o link na plataforma da DIO! Sua entrega é a prova de que você domina o raciocínio de Vibe Coding, mesmo sem escrever uma única linha de código.

## 💬 Conclusão

Vibe Coding é sobre clareza, curiosidade e criatividade, não sobre perfeição técnica. O verdadeiro objetivo aqui é aprender a pensar junto com a IA, transformando ideias em conceitos reais e enxergando a tecnologia como uma extensão do seu raciocínio criativo. Cada interação é um experimento, quanto mais clara for sua intenção, mais surpreendente será o resultado.
