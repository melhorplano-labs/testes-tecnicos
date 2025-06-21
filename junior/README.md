# Teste Técnico – Desenvolvedor Júnior

## Objetivos do teste

Avaliaremos sua capacidade de:

- Resolver problemas com raciocínio lógico
- Demonstrar domínio em estruturas de dados
- Ler, entender e corrigir códigos existentes
- Correção de bugs
- Implementar novas funcionalidades
- Seguir boas práticas de desenvolvimento
- Comunicar claramente o que foi feito

## Prazo de entrega

Até 4 dias úteis a partir do recebimento deste teste.

O tempo estimado para resolução do teste é de 3 a 4 horas.

## Contexto simulado

Você acaba de entrar para o time de desenvolvimento do MelhorPlano.net, um comparador de planos telecom.

Assim sendo, segue abaixo alguns desafios de uma pequena aplicação interna que simula um sistema de consulta de planos de internet.

## Desafios

### 1. Bug Fix – Corrigir problema na listagem de planos

Atualmente, quando alguém acessa a lista de planos de internet disponíveis, a página exibe uma lista vazia.

**Tarefa:**

- Investigar o motivo
- Corrigir o problema
- Garantir que os planos cadastrados no backend apareçam corretamente no frontend
- Descreva brevemente no PR qual era o problema, motivo do bug e como foi realizada a correção

### 2. Nova feature – Marcar plano como destaque

Os editores de conteúdo precisam de uma forma de destacar alguns planos para que apareçam primeiro na lista.

**Tarefa:**

- Criar um endpoint no backend (exemplo: `PATCH /plans/:id/highlight`) para permitir que um plano seja marcado como destaque
- No frontend, exibir um selo "Plano em Destaque" ao lado dos planos com esse status.

### 3. Refactor – Melhorar legibilidade e organização de uma função existente

No backend, existe uma função chamada `handleThing()`, que atualmente é responsável por realizar uma série de filtros. Além do nome e lógica confusa, quem ler essa função não tá claro qual a real responsabilidade.

**Tarefa:**

- Renomear a função para um nome mais claro e semântico, que reflita de forma objetiva o que ela faz.
- Reorganizar o corpo da função, aplicando melhorias de legibilidade e manutenibilidade como:
  - Melhorar nomes de variáveis
  - Quebrar trechos de código grandes em funções menores, se fizer sentido
  - Tornar os fluxos de decisão mais claros
  - Garantir que o comportamento da função permaneça o mesmo após o refactor.

### 4. Documentação – Escreva uma boa descrição de Pull Request

Ao finalizar o teste, envie suas alterações em um Pull Request em uma branch separada com:

- Breve explicação do que foi feito em cada tarefa com a motivação do problema e como resolveu.
- Roteiro de testes: Como você testou.

## Critérios de avaliação

| Critério                        | O que esperamos                                        |
| ------------------------------- | ------------------------------------------------------ |
| Entendimento do código          | Entender o fluxo de uma aplicação já montada           |
| Lógica de programação           | Resolver os problemas com soluções claras e eficientes |
| Clareza e organização de código | Nome de variáveis, funções, legibilidade e organização |
| Boas práticas                   | Aplicação funcional, testado e minimamente limpo       |
| Comunicação                     | PR objetivo, claro e direto, histórico de commits      |
| Responsabilidade                | Não quebrar o que já funciona, testar antes de enviar  |

## Entrega

Ao receber o teste, siga um dos fluxos abaixo:

### Opção 1: Envio pelo GitHub

1. Faça um fork deste repositório: [https://github.com/melhorplano-labs/melhorplano-coding-challenge](https://github.com/melhorplano-labs/melhorplano-coding-challenge)
2. Clone o seu fork na sua máquina local.
3. Crie uma nova branch para suas alterações (exemplo: `feature/nome-sobrenome-teste-nome-da-vaga`).
4. Implemente as tarefas solicitadas do teste enviado pelo time de R&S.
5. Faça o push da sua branch para o seu fork.
6. Abra um Pull Request da sua branch (no seu fork) para a branch principal (`main`) do repositório original (upstream).
7. Responda ao e-mail do time de R&S `recrutamento@melhorplano.net`, sinalizando que foi finalizado e o link do seu Pull Request.

### Opção 2: Envio privado (se preferir não expor em seu perfil público)

Sabemos que alguns candidatos preferem não expor publicamente sua participação em processos seletivos. Se for o seu caso, fique à vontade para escolher uma das opções abaixo:

**Envio por e-mail:**

- Envie o projeto em um arquivo `.zip` para o e-mail do time de R&S, junto com as instruções de execução.

**Repositório privado no GitHub:**

- Suba o projeto em um repositório privado no seu GitHub e adicione `engenharia@melhorplano.net` e `renan.bessa@melhorplano.net` como colaboradores para acesso.

Se optar por qualquer alternativa privada, avise o time de R&S pelo e-mail `recrutamento@melhorplano.net` para que possamos acompanhar o seu teste normalmente.

> **Importante:**
> O importante para nós é avaliar seu desafio como um todo, independente do meio de envio. Escolha a opção mais confortável para você!

## Observação importante - Uso de IA

Queremos avaliar seu raciocínio e capacidade de resolver problemas. Sabemos que dúvidas pontuais podem surgir durante a implementação (ex: sintaxe ou uso de funções), e tudo bem consultar a documentação ou, se necessário, usar IA com bom senso. O importante é priorizar entender o problema antes de buscar apoio.

O que queremos evitar é o uso excessivo da IA, principalmente na criação de blocos inteiros de código ou na descrição do PR, sem que você compreenda o que está fazendo.

Nossa equipe analisará com atenção o seu teste e temos experiência para identificar quando a solução não reflete o nível de raciocínio esperado.

Se você avançar para a próxima etapa, vamos explorar o seu raciocínio durante a entrevista, revisando suas decisões técnicas no teste. Por isso, é fundamental que sua entrega reflita de fato o seu conhecimento e a sua forma de pensar.

> Este é um teste individual. Por favor, não peça ajuda a outras pessoas durante a execução.
