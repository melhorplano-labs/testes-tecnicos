# Teste Técnico – Desenvolvedor Pleno

Olá! 😊
Primeiro, agradecemos demais pelo seu interesse em fazer parte do time da MelhorPlano!
Preparamos um teste técnico que simula desafios reais do nosso dia a dia, para que você possa mostrar seu jeito de pensar e codar e já sentir como seria trabalhar aqui.

## Objetivos do teste

O que vamos avaliar:

- Capacidade de resolver problemas de forma lógica
- Domínio de estruturas de dados
- Leitura, entendimento e melhoria de código já existente
- Correção de bugs de verdade
- Implementação de novas funcionalidades
- Boas práticas de desenvolvimento
- Clareza na comunicação das soluções

## Sobre o teste

- Prazo de entrega: até 4 dias úteis
- Tempo estimado: 3 a 4 horas (respeitamos seu tempo, não precisa ir além!)
- Dica: Foque na qualidade, não na quantidade. Queremos ver seu raciocínio, organização e clareza.

## Contexto

Você entrou para o time de engenharia da MelhorPlano e recebeu 3 desafios de uma aplicação interna nossa, simulando problemas reais.

## Desafios

### 1. Bug Fix – Paginação com múltiplos filtros

Nosso sistema permite que o usuário filtre e navegue por páginas de planos de internet. Porém, ao combinar múltiplos filtros e trocar de página, os resultados ficam inconsistentes.

**Sua missão:**

- Investigue a causa
- Corrija o problema
- Garanta que os planos cadastrados aparecem corretamente no frontend
- Documente qual era o bug, a causa, e como você resolveu

### 2. Nova feature – Recomendação inteligente de planos

Queremos recomendar os planos mais aderentes ao perfil e preferências do usuário.

**O que esperamos:**

- O usuário informa preferências (cidade, orçamento, perfil, operadora, etc)
- O sistema retorna uma lista ordenada dos planos mais recomendados, destacando o mais adequado
- Algoritmo extensível para novos critérios no futuro
- Foco principal no backend: entregue também um frontend simples, só para facilitar os testes e visualização da funcionalidade. Não avaliaremos design ou UX — basta ser funcional!
- Código limpo, modular e fácil de entender
- Testes automatizados principais cobrindo a lógica da recomendação
- Evite alterar a estrutura dos dados mockados

### 3. Refactor – Clareza, modularização e testabilidade

No backend temos a função `handleThing()`, cheia de responsabilidades misturadas e difícil de manter.

**Sua tarefa:**

- Reorganize a função/serviço para deixar as responsabilidades claras e bem separadas
- Torne o código mais fácil de entender, manter e testar
- Renomeie a função para um nome semântico
- Adicione exemplos de testes automatizados cobrindo os fluxos principais
- Não precisa se preocupar com integração real de banco de dados ou cache avançado

### Documentação – Descreva bem sua entrega

Explique claramente o que você fez em cada tarefa:

- Resumo por tarefa: O que foi feito, qual era o problema/motivação, como resolveu e por quê.
- Roteiro de testes: Como você testou a solução (pode ser um passo a passo ou comandos utilizados).
- Decisões técnicas e suposições: Se tomou algum caminho diferente ou precisou assumir algo, compartilhe seu raciocínio.

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

Ao receber e finalizar o teste, siga:

1. Utilize o repositório base disponível em: [https://github.com/melhorplano-labs/melhorplano-coding-challenge](https://github.com/melhorplano-labs/melhorplano-coding-challenge)

2. Clone o repositório para sua máquina local.

3. Crie um novo repositório privado na sua conta do GitHub.

4. Suba o código do desafio para esse repositório privado.

5. Implemente as tarefas solicitadas diretamente nesse seu repositório privado.

6. Ao finalizar, adicione os usuários `renan.bessa@melhorplano.net` e `erick.machado@melhorplano.net` como colaboradores do repositório.

## Observação importante - Uso de IA

Queremos avaliar sua forma de resolver problemas. Use a documentação e a IA como apoio para dúvidas pontuais, mas evite que a ferramenta crie blocos de código ou descrições no seu lugar.

Sua entrega deve refletir sua forma de pensar, pois discutiremos suas decisões técnicas em uma próxima etapa.

> Este é um teste individual. Por favor, não peça ajuda a outras pessoas durante a execução.
