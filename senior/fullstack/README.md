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
| Responsabilidade                | Não quebrar o que já funciona, testar antes de enviar                                    |

## Entrega

Ao receber e finalizar o teste, siga um dos fluxos abaixo:

### Opção 1

1. Faça um fork deste repositório: [https://github.com/melhorplano-labs/melhorplano-coding-challenge](https://github.com/melhorplano-labs/melhorplano-coding-challenge)
2. Clone o seu fork na sua máquina local.
3. Crie uma nova branch para suas alterações (exemplo: `feature/nome-sobrenome-teste-nome-da-vaga`).
4. Implemente as tarefas solicitadas.
5. Faça o push da sua branch para o seu fork no GitHub.
6. Abra um **Pull Request** da sua branch para a branch `main` do seu fork.
7. Envie o link do **Pull Request** para `avaliadores.tech@melhorplano.net`.

### Opção 2

Como alternativa, caso prefira usar um repositório privado:

1.  Suba o código-base do desafio para um novo repositório **privado** no seu GitHub.
2.  Crie uma nova branch para desenvolver sua solução.
3.  Ao finalizar, abra um **Pull Request** no seu repositório privado.
4.  Adicione os usuários `renan.bessa@melhorplano.net` e `erick.machado@melhorplano.net` como colaboradores do repositório.
5.  Envie o link do **Pull Request** para `avaliadores.tech@melhorplano.net`.

## Observação importante - Uso de IA

Queremos avaliar sua forma de resolver problemas. Use a documentação e a IA como apoio para dúvidas pontuais, mas evite que a ferramenta crie blocos de código ou descrições no seu lugar.

Sua entrega deve refletir sua forma de pensar, pois discutiremos suas decisões técnicas em uma próxima etapa.

> Este é um teste individual. Por favor, não peça ajuda a outras pessoas durante a execução.
