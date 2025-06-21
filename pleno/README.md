# Teste Técnico – Desenvolvedor Pleno

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

### 1. Bug Fix – Corrigir inconsistências na listagem paginada de planos com múltiplos filtros

O sistema de busca de planos permite ao usuário aplicar múltiplos filtros dinâmicos e navegar por páginas de resultados. Porém, foi identificado um comportamento inconsistente na listagem dos planos ao utilizar filtros combinados e navegar entre páginas.

**Tarefa:**

- Investigar o motivo
- Corrigir o problema
- Garantir que os planos cadastrados no backend apareçam corretamente no frontend
- Descreva brevemente no PR qual era o problema, motivo do bug e como foi realizada a correção

### 2. Nova feature – Recomendação inteligente de planos

Queremos oferecer uma experiência personalizada para nossos usuários, sugerindo os planos mais adequados de acordo com o perfil e preferências de cada um.

**Tarefa:**

- Desenvolver a feature de recomendação de planos, considerando múltiplos critérios e preferências do usuário.
- Implementar a solução tanto no backend quanto no frontend, garantindo uma experiência fluida e personalizada.
- Requisitos mínimos:
  - O usuário deve poder informar suas preferências (ex: cidade, orçamento, perfil de uso, operadora preferida).
  - O sistema deve retornar uma lista ordenada dos planos mais recomendados, destacando o mais aderente.
  - O algoritmo de recomendação deve ser facilmente extensível para novos critérios no futuro.
  - A solução deve ser bem testada com testes automatizados cobrindo os principais fluxos.
  - Código limpo, modular e de fácil manutenção.

### 3. Refactor – Modularização, clareza e testabilidade

No backend, existe uma função chamada `handleThing()`, que atualmente é responsável por realizar uma série de filtros. O código atual mistura responsabilidades, tem nome pouco descritivo e dificulta a manutenção e evolução.

**Tarefa:**

- Que a função e o serviço sejam reorganizados para refletir responsabilidades claras e bem definidas.
- Que o código seja mais fácil de entender, manter e evoluir.
- Que a solução seja facilmente testável e venha acompanhada de exemplos de testes automatizados.
- Requisitos mínimos:
  - O nome da função deve ser claro e semântico.
  - O código deve ser modular, evitando concentração de responsabilidades em um único lugar.
  - Deve haver exemplos de testes automatizados cobrindo os principais fluxos.
  - O comportamento do sistema deve ser mantido.
  - Não é necessário implementar integração com banco de dados real
  - Não é necessário implementar cache avançado

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
