Teste Técnico -- Engenheiro DevOps

=================================

Objetivo

--------

Criar e entregar uma aplicação containerizada rodando na AWS, com provisionamento automatizado da infraestrutura, pipeline de CI/CD e monitoramento básico.

Stack esperada

--------------

*   Terraform

*   Drone CI

*   Docker

*   AWS

*   Prometheus e Grafana

*   GitHub

Desafio

-------

Você deverá entregar um repositório que permita provisionar a infraestrutura, realizar deploy da aplicação e visualizar o funcionamento da aplicação e das métricas de forma externa.

Requisitos

----------

### Infraestrutura como código

Provisionar na AWS, utilizando Terraform, a infraestrutura necessária para executar a aplicação containerizada.

A escolha dos serviços AWS é livre, desde que a solução permita acesso externo à aplicação.

### Container e deploy

Criar uma aplicação simples containerizada.

A aplicação deve:

*   Rodar em container Docker

*   Estar publicada na AWS

*   Ser acessível externamente (por exemplo, via Load Balancer ou endpoint público)

### CI/CD

Criar pipeline no Drone CI para:

*   Build da aplicação

*   Build da imagem Docker

*   Publicação da imagem em registry

*   Deploy da aplicação na AWS

### Monitoramento e observabilidade

Disponibilizar métricas da aplicação utilizando Prometheus.

Disponibilizar um dashboard básico no Grafana com visualização das métricas da aplicação.

O dashboard deve estar acessível externamente.

Entrega

-------

Repositório GitHub contendo:

*   Código da aplicação

*   Dockerfile

*   Código Terraform

*   Pipeline CI/CD (Drone)

*   Configuração do Prometheus

*   Configuração do Grafana

*   README com instruções completas

README deve conter

------------------

*   Como rodar a aplicação localmente

*   Como provisionar o ambiente na AWS

*   Como executar ou acionar o pipeline

*   URL pública da aplicação

*   URL pública do dashboard de métricas

*   Como validar que a solução está funcionando

Avaliação

---------

Serão avaliados principalmente:

*   Organização e clareza da solução

*   Qualidade da automação

*   Boas práticas de infraestrutura e deploy

*   Funcionamento do monitoramento e métricas

*   Clareza da documentação

*   Facilidade de execução e validação da solução

Observações

-----------

Você pode tomar decisões técnicas livremente dentro da stack proposta.

Caso faça escolhas arquiteturais específicas, descreva brevemente no README o motivo dessas decisões.

A solução deve permitir validação externa real, com aplicação e métricas acessíveis via URL pública.