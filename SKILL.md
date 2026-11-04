---
name: awsm-proj-plan
description: "Use when starting or replanning a project with multiple deliverables or a personal routine: clarifies scope through guided questions, plans in verifiable tasks, suggests skills and connectors per context, and structures documentation. Use ao iniciar ou replanejar um projeto com várias entregas ou uma rotina de gestão: esclarece o escopo com perguntas guiadas, planeja em tarefas verificáveis, sugere skills e connectors por contexto e estrutura a documentação."
---

# Planejar projeto (awsm-proj-plan)

Use esta skill quando o projeto tiver escopo amplo, várias entregas, uma rotina a ser organizada ou documentação que vai crescer. Para tarefas pontuais, não use.

## Passo 0: identificar o tipo de projeto

Classifique o projeto como software/ferramenta, conteúdo/série, biblioteca de design, pesquisa/aprendizado, pessoal/rotina ou outro. Se não estiver claro, pergunte uma vez. O tipo define as variações dos Passos 3 e 4.

## Passo 1: explorar e esclarecer antes de planejar (obrigatório)

Antes de qualquer pergunta, liste de três a cinco caminhos possíveis para chegar ao resultado. Nesse momento, não descarte nenhum: o objetivo é ampliar as opções.

Depois, faça as perguntas em rodadas de no máximo três, nesta ordem:
1. Resultado: o que precisa existir ao final, e para quem? Qual dos caminhos listados se aproxima mais?
2. Limites: prazo, tempo ou dinheiro disponíveis, e ferramentas já em uso.
3. Entregas: quais são, em que ordem, e como saber que cada uma está pronta.
4. Suposições: o que está sendo assumido como verdade. Liste cada uma e peça que o usuário confirme ou descarte.
5. Riscos: o que tem mais chance de dar errado, e o que seria feito nesse caso.

Apresente as perguntas como múltipla escolha sempre que possível. Depois de cada rodada, resuma o que entendeu e peça confirmação. Se uma suposição parecer fraca, aponte-a uma vez, com um exemplo concreto. Não avance enquanto objetivo, restrições, entregas e critério de "pronto" não estiverem confirmados.

## Passo 2: escopo e tarefas

Escreva:
- Objetivo em uma frase.
- Entregas, cada uma com critério de pronto.
- Fora de escopo, explicitamente.
- Riscos e decisões pendentes, com o que aconteceria se a escolha fosse errada.
- Tarefas de cada entrega, no formato `- [ ] Tarefa → Verificar: como conferir`. Cada tarefa tem um resultado claro e um critério observável de conclusão.

Regras para as tarefas:
- Máximo de 10 tarefas por plano. Se passar disso, divida em planos por entrega.
- A verificação final da entrega fica sempre por último.
- Adapte o tamanho ao trabalho real, de modo que cada tarefa caiba em uma sessão de trabalho.

Se a ideia tiver um risco, erro ou escolha ruim, aponte antes de seguir.

## Passo 3: skills, connectors e ordem de uso

Para cada contexto do projeto (cada tipo de entrega ou etapa), faça duas verificações:

1. Skills: confira as skills realmente carregadas nesta sessão (não suponha a lista) e indique as que servem àquele contexto.
2. Connectors: se a etapa envolver apps do usuário (Notion, Figma, Google Drive, Gmail, Calendar etc.), verifique se há connector conectado que faça o trabalho. Se não houver, procure no registro de connectors e sugira o que ajudaria, sem forçar a instalação.

Para cada item sugerido informe: quando usar, em qual fase, e qual é a entrada e a saída. O Passo 1 vem sempre na primeira posição. A verificação final entra sempre na última fase. Não invente skills nem connectors que não existam.

Variações por tipo:
- Software/ferramenta: inclua versionamento no escopo do projeto, numerando as versões em vX.X.X (use a skill version-vx-x-x, se estiver disponível), e ajuste a verificação ao tamanho da mudança (pequena, média ou grande).
- Conteúdo/série: inclua calendário, formatos e revisão antes de publicar.
- Biblioteca de design: inclua convenções de nomes, componentes e exportação.
- Pesquisa/aprendizado: inclua perguntas de pesquisa, fontes e registro de descobertas.
- Pessoal/rotina: inclua diagnóstico da rotina atual, blocos de tempo com prioridades e uma revisão periódica (por exemplo, semanal) para ajustar o plano.

## Passo 4: documentação

Antes de criar qualquer documento, verifique o plano contra a documentação que o projeto já tem: liste os documentos existentes, leia-os e aponte conflitos ou termos divergentes com o plano. Se o projeto não tiver documentação, proponha uma base inicial.

Depois, defina um único local para toda a documentação do projeto (por exemplo, uma página no Notion ou uma pasta do projeto). Atualize o que já existe em vez de duplicar. Estrutura sugerida:
- Visão geral e objetivo.
- Escopo e entregas.
- Tarefas, com o status atual de cada uma.
- Decisões tomadas, com data e motivo.
- Versões, se o projeto tiver versionamento.
- Skills e connectors escolhidos, com a fase de uso.
- Referências.

Documente decisões e o que for necessário para retomar o projeto depois, não cada passo de execução. Marque as tarefas concluídas conforme o trabalho avança.

## Passo 5: entrega

Apresente o plano completo e aguarde o OK antes de criar ou alterar qualquer arquivo existente. Ao final, diga em uma linha o que foi definido e onde está a documentação, sem recapitular os passos.

## Regras gerais

- Responda no mesmo idioma dos últimos chats do usuário. Se houver um equilíbrio de uso (até 60/40 entre dois idiomas), pergunte qual idioma ele prefere antes de responder.
- Explique termos técnicos em uma frase entre parênteses.
- Use seções curtas; aprofunde só quando pedido.
