# Teste técnico – Desenvolvedor Júnior

## Objetivo do teste

Queremos avaliar sua capacidade de:

- Demonstrar excelente raciocínio lógico e capacidade de resolução de problemas
- Noções sólidas de estrutura de dados (arrays, objetos, listas, etc)
- Ler e entender um código existente
- Corrigir bugs
- Implementar uma nova funcionalidade
- Ter atenção a boas práticas e organização de código
- Escrever código limpo, claro e legível
- Comunicar bem o que fez (via descrição de Pull Request e histórico de commits claros e frequentes)

## Contexto simulado

Você acaba de entrar para o time de desenvolvimento do MelhorPlano.net, um comparador de planos telecom, streaming e financeiro.

No teste de hoje, você vai trabalhar em uma pequena aplicação interna que simula um sistema de consulta de planos de internet.

## Instruções do teste

### 1. Bug Fix – Corrigir problema na listagem de planos

Atualmente, quando alguém acessa a lista de planos de internet disponíveis, a página exibe uma lista vazia.

**Sua tarefa:**

- Investigar o motivo
- Corrigir o problema
- Garantir que os planos cadastrados no backend apareçam corretamente no frontend

> **Dica:** Antes de corrigir, descreva brevemente no PR qual era o problema e o motivo da falha.

### 2. Nova feature – Marcar plano como destaque

Os editores de conteúdo precisam de uma forma de destacar alguns planos para que apareçam primeiro na lista.

**Sua tarefa:**

- Criar um endpoint no backend (exemplo: `PATCH /plans/:id/highlight`) para permitir que um plano seja marcado como destaque
- No frontend, exibir um selo "Plano em Destaque" ao lado dos planos com esse status

> **Dica:** Pense na organização do código (ex: separar lógica de controller, service, etc., mesmo que de forma simples).

### 3. Pequeno refactor – Melhorar nome de uma função confusa

No backend, existe uma função chamada `handleThing()`, que na prática é responsável por buscar os planos disponíveis.

**Sua tarefa:**

- Refatore o nome dessa função para algo mais claro, semântico e alinhado a boas práticas de código limpo.

### 4. Documentação – Escreva uma boa descrição de Pull Request

Ao finalizar o teste, envie suas alterações em um Pull Request em uma branch separada com:

- Breve explicação do que foi feito
- Como você testou suas alterações
- Se encontrou alguma dificuldade ou limitação, pode mencionar

> **Dica:** Aqui vamos avaliar sua comunicação técnica objetiva e a capacidade de explicar seu raciocínio.

## Critérios de avaliação

| Critério                        | O que esperamos                                        |
| ------------------------------- | ------------------------------------------------------ |
| Entendimento do código          | Entender o fluxo de uma aplicação já montada           |
| Lógica de programação           | Resolver os problemas com soluções claras e eficientes |
| Clareza e organização de código | Nome de variáveis, funções, legibilidade e organização |
| Boas práticas                   | Aplicação funcional, testado e minimamente limpo       |
| Comunicação                     | PR objetivo, claro e direto, histórico de commits      |
| Responsabilidade                | Não quebrar o que já funciona, testar antes de enviar  |

## Tempo sugerido

De 2 a 3 horas  
(O prazo de envio será de até 2 dias úteis a partir do recebimento deste teste)

## Entrega

Este teste será feito diretamente em um repositório base de testes técnicos da MelhorPlano, que vamos compartilhar com você.

**Ao receber o teste:**

1. Faça o clone deste repositório: [https://github.com/melhorplano/melhorplano-coding-challenge](https://github.com/melhorplano/melhorplano-coding-challenge)
2. Crie uma nova branch para suas alterações (exemplo: `feature/nome-sobrenome-teste-melhorplano`).
3. Realize todas as implementações solicitadas nas instruções acima.
4. Abra um Pull Request da sua branch para a branch principal (`main`) dentro do mesmo repositório.
5. Marque o usuário `avaliadores-melhorplano` como revisor do seu PR.

> **Importante:**  
> Trate o processo como um fluxo de trabalho real. Vamos avaliar também sua organização de branch, qualidade da descrição do PR e clareza na explicação das suas decisões.

## Observação importante

Queremos avaliar o seu raciocínio lógico, pensamento crítico e capacidade real de resolução de problemas.

Sabemos que durante a implementação podem surgir dúvidas pontuais (ex: lembrar a sintaxe de um comando ou consultar uma função específica), e tudo bem buscar ajuda nesses casos. O importante é que você priorize entender o problema, ler a documentação oficial da linguagem ou framework e só depois, se realmente precisar, use ferramentas de IA como apoio.

O que queremos evitar é o uso excessivo ou automático da IA, principalmente na criação de blocos inteiros de código ou na escrita da descrição do PR, sem que você entenda o que está fazendo.

Nosso time técnico e gestor vai revisar com atenção o seu teste e temos experiência para perceber quando o código não reflete o nível de raciocínio esperado.

Se você avançar para a próxima etapa, vamos explorar o seu raciocínio durante a entrevista, revisando suas decisões técnicas no teste e abordando outros desafios. Por isso, é importante que tudo o que você entregar reflita de fato o seu conhecimento e a sua forma de pensar.
