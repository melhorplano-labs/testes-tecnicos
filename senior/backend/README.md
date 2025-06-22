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

Ao receber o teste, siga um dos fluxos abaixo:

### Opção 1: Envio pelo GitHub

1. Faça um fork deste repositório: [https://github.com/melhorplano-labs/melhorplano-coding-challenge](https://github.com/melhorplano-labs/melhorplano-coding-challenge)
2. Clone o seu fork na sua máquina local.
3. Crie uma nova branch para suas alterações (exemplo: `feature/nome-sobrenome-teste-nome-da-vaga`).
4. Implemente as tarefas solicitadas do teste enviado pelo time de R&S.
5. Faça o push da sua branch para o seu fork (repositório no perfil do candidato).
6. Abra um Pull Request da sua branch (no seu fork) para a branch principal (`main`) do próprio fork (não do repositório original).
7. Envie o link do fork (ou branch específica) para o time de R&S pelo e-mail `recrutamento@melhorplano.net`

### Opção 2: Envio privado (se preferir não expor em seu perfil público)

Sabemos que alguns candidatos preferem não expor publicamente sua participação em processos seletivos. Se for o seu caso, fique à vontade para escolher uma das opções abaixo:

**Envio por e-mail:**

- Envie o projeto em um arquivo `.zip` para o e-mail do time de R&S `recrutamento@melhorplano.net`, junto com as instruções de execução.

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
