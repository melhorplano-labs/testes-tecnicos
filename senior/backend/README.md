# Teste Técnico – Desenvolvedor Sênior Backend

## Objetivo do teste

Avaliar sua capacidade de liderar decisões técnicas, propor soluções escaláveis e evoluir a arquitetura de sistemas, promovendo qualidade, modularidade e visão de longo prazo.

## Prazo de entrega

Até 4 dias úteis a partir do recebimento deste teste.

O tempo estimado para resolução do teste é de 3 a 4 horas.

## Contexto simulado

Você acaba de ingressar no time de desenvolvimento do MelhorPlano.net, um comparador de planos telecom.  
Sua missão é atuar como referência técnica, promovendo padrões de arquitetura e qualidade que permitam a evolução sustentável do backend.

A aplicação atual simula um sistema de consulta de planos de internet, com dados mockados e endpoints básicos.

## Desafio principal

### Refatoração arquitetural

O backend atual possui uma estrutura tradicional de controllers, services e models, com lógica de negócio acoplada e dados mockados em memória.

Seu desafio é liderar a evolução arquitetural do sistema, refatorando um dos fluxos principais para adotar uma arquitetura mais modular, sustentável e alinhada a boas práticas de mercado (ex: arquitetura hexagonal ou Clean Architecture), promovendo separação clara de domínios, casos de uso e infraestrutura.

**O que esperamos:**

- Separação clara entre regras de negócio, casos de uso e infraestrutura.
- Código desacoplado, testável e preparado para futuras evoluções.
- Padrões e diretrizes que possam ser seguidos pelo time no restante do projeto.
- Documentação clara das decisões técnicas e motivações.

O objetivo é garantir que o backend esteja pronto para crescer de forma sustentável, facilitando a manutenção, testes e futuras integrações.

**Diferenciais:**

- Propor melhorias estratégicas na stack, sugerindo padrões para todo o backend.
- Antecipar possíveis gargalos de performance e sugerir pontos de observabilidade.
- Demonstrar visão de liderança técnica, deixando claro como a solução pode ser expandida para outros fluxos do sistema.

## Entregáveis

- Código refatorado, seguindo princípios de modularidade e boas práticas arquiteturais, em uma branch separada.
- Testes automatizados cobrindo os principais fluxos do endpoint refatorado.
- Documentação clara no Pull Request, explicando as decisões técnicas, motivações, trade-offs e roteiro de testes.
- Sugestão de guidelines para adoção gradual da arquitetura no restante do projeto.

## Critérios de avaliação

| Critério                        | O que esperamos                                                                  |
| ------------------------------- | -------------------------------------------------------------------------------- |
| Liderança técnica               | Propor e justificar padrões arquiteturais alinhados à escalabilidade e qualidade |
| Arquitetura e modularidade      | Separação clara de domínios, casos de uso, interfaces e infraestrutura           |
| Testabilidade                   | Código facilmente testável, com exemplos de testes automatizados                 |
| Clareza e organização de código | Nome de variáveis, funções, legibilidade e organização                           |
| Boas práticas                   | Código limpo, documentado e sustentável                                          |
| Comunicação                     | PR objetivo, claro e direto, histórico de commits                                |
| Responsabilidade                | Não quebrar o que já funciona, testar antes de enviar                            |

## Entrega

1. Faça o clone deste repositório: [https://github.com/melhorplano-labs/melhorplano-coding-challenge](https://github.com/melhorplano-labs/melhorplano-coding-challenge)
2. Crie uma nova branch para suas alterações (exemplo: `feature/nome-sobrenome-teste-nome-da-vaga`).
3. Implemente as tarefas solicitadas acima.
4. Abra um Pull Request da sua branch para a branch principal (`main`) dentro do mesmo repositório com descrição detalhada do desafio de qual era a motivação, o problema, como resolveu e roteiro de testes.
5. Marque `melhorplano-labs/technical-test-evaluators` como revisor do seu PR.

> **Importante:**  
> Trate o processo como um fluxo de trabalho real. Avaliaremos também sua organização de branch, qualidade da descrição do PR e clareza na explicação das suas decisões.

## Observação importante - Uso de IA

Queremos avaliar seu raciocínio e capacidade de resolver problemas. Sabemos que dúvidas pontuais podem surgir durante a implementação (ex: sintaxe ou uso de funções), e tudo bem consultar a documentação ou, se necessário, usar IA com bom senso. O importante é priorizar entender o problema antes de buscar apoio.

O que queremos evitar é o uso excessivo da IA, principalmente na criação de blocos inteiros de código ou na descrição do PR, sem que você compreenda o que está fazendo.

Nossa equipe analisará com atenção o seu teste e temos experiência para identificar quando a solução não reflete o nível de raciocínio esperado.

Se você avançar para a próxima etapa, vamos explorar o seu raciocínio durante a entrevista, revisando suas decisões técnicas no teste. Por isso, é fundamental que sua entrega reflita de fato o seu conhecimento e a sua forma de pensar.

> Este é um teste individual. Por favor, não peça ajuda a outras pessoas durante a execução.
