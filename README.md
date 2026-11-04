# awsm-proj-plan

Skill para o Claude planejar projetos com várias entregas ou uma rotina de gestão, do esclarecimento do escopo até a documentação.

## O que ela faz

1. Identifica o tipo do projeto: software/ferramenta, conteúdo/série, biblioteca de design, pesquisa/aprendizado, pessoal/rotina ou outro.
2. Antes de planejar, lista caminhos possíveis para o resultado e depois faz perguntas guiadas, em rodadas curtas, para escolher entre eles e confirmar objetivo, limites, entregas, suposições e riscos.
3. Escreve o escopo e quebra cada entrega em tarefas verificáveis, com no máximo 10 tarefas por plano.
4. Sugere skills e connectors para cada etapa, conferindo o que está realmente disponível na sessão.
5. Verifica a documentação existente antes de criar algo novo e organiza tudo em um único local.
6. Só altera arquivos existentes depois da sua aprovação.

Não depende de outras skills para funcionar. O questionamento é feito pela própria skill.

## Instalação

**Opção 1: copiar a pasta**

Copie a pasta `awsm-proj-plan` para o diretório de skills do Claude Code:

```
~/.claude/skills/awsm-proj-plan/
```

Depois, reinicie a sessão para a skill ser carregada.

**Opção 2: enviar pela interface**

Envie a pasta (ou um zip dela) pela tela de skills do Claude, como uma skill personalizada.

## Uso

Peça um planejamento de projeto com várias entregas ou de uma rotina, por exemplo:

> Quero planejar a produção de uma série de quadrinhos com 6 capítulos.

ou

> Preciso organizar minha rotina de estudos e trabalho para o próximo trimestre.

A skill também é acionada pelos gatilhos em português e em inglês definidos na descrição.

## Skills relacionadas (opcionais)

- **versionamento-vx-x-x**: usada pelo tipo software/ferramenta para numerar as versões em vX.X.X. Se não estiver instalada, a skill segue sem ela.

## Idioma

A skill responde no mesmo idioma dos últimos chats do usuário. Se o uso estiver equilibrado (até 60/40 entre dois idiomas), ela pergunta qual idioma prefere antes de responder.

## Licença

Defina a licença antes de publicar.
