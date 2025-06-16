# Teste Técnico – Desenvolvedor FullStack Sênior (maior ênfase em frontend)

## Objetivo do teste

Avaliar sua capacidade de liderar decisões técnicas, propor, arquitetar e implementar uma solução escalável, performática e otimizada, integrando frontend e backend.

## Prazo de entrega

Até 4 dias úteis a partir do recebimento deste teste.

O tempo estimado para resolução do teste é de 3 a 4 horas.

## Contexto simulado

Você fará parte da squad de desenvolvimento aquisição orgânica da MelhorPlano.net, responsável por garantir que nossos produtos tenham máxima visibilidade e performance em mecanismos de busca. Atualmente, os planos de internet são exibidos apenas em uma listagem. Para melhorar o ranqueamento e a experiência do usuário, queremos que cada plano tenha sua própria página de detalhe, com conteúdo dinâmico, URLs amigáveis e altamente otimizada para SEO e performance.

## Desafio principal

Crie uma experiência de página de detalhe de plano de internet, consumindo dados de uma nova API criada por você no backend, garantindo excelência em SEO e performance.

**O que esperamos:**

- Cada plano deve ter uma página de detalhe acessível por uma URL única e amigável (ex: /planos/[slug]).
- A página deve consumir dados de uma nova API a ser criada no backend (não pode ser mock/local no frontend). A persistência em banco de dados não é necessária; os dados podem ser mantidos em memória ou em arquivo no backend.
- As informações exibidas devem ser dinâmicas, vindas da API.
- O conteúdo da página deve estar disponível para leitura e indexação por bots de busca.
- As meta tags (title, description, Open Graph, etc) devem ser dinâmicas e otimizadas para SEO.
- O carregamento da página deve ser rápido, com atenção aos principais indicadores de performance (Lighthouse/Core Web Vitals).
- Documentar as decisões técnicas tomadas (via Pull Request).
- Implementação de dados estruturados (JSON-LD) para SEO.
- Pré-carregamento inteligente de páginas relacionadas.
- Testes automatizados (unitários).
- Métricas de performance e SEO apresentadas.
- Breadcrumbs otimizados para SEO.

## Entregáveis

- Código legível, seguindo princípios de modularidade, performance e boas práticas de SEO, em uma branch separada.
- Documentação clara no Pull Request, explicando as decisões técnicas, motivações, trade-offs e instruções para rodar/testar o projeto.
- Justificativa da escolha entre SSR/SSG e das estratégias de performance e SEO adotadas.
- Prints ou relatórios de métricas de performance/SEO.
- Sugestão de guidelines para adoção gradual da arquitetura no restante do projeto.
- Testes automtizados.

## Critérios de Avaliação

| Critério                        | O que esperamos                                                                          |
| ------------------------------- | ---------------------------------------------------------------------------------------- |
| Liderança técnica               | Propor e justificar decisões arquiteturais alinhadas à escalabilidade, performance e SEO |
| Arquitetura e modularidade      | Separação clara de responsabilidades, componentes reutilizáveis, API bem definida        |
| Performance e SEO               | Solução otimizada para Core Web Vitals, SEO técnico (meta tags, dados estruturados, etc) |
| Clareza e organização do código | Código limpo, legível, bem estruturado e documentado                                     |
| Boas práticas                   | Uso de padrões modernos de frontend/backend, segurança e sustentabilidade                |
| Comunicação                     | PR objetivo, explicativo, com histórico de commits claro e documentação das decisões     |
| Responsabilidade                | Não quebrar o que já funciona, testar antes de enviar, garantir experiência do usuário   |

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
