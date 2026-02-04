### Teste Técnico - Engenheiro DevOps

## Objetivo

O objetivo desse teste é avaliar seus conhecimentos técnicos sobre infraestrutura, práticas DevOps, automações. No mais, o objetivo final é criar e entregar uma aplicação containerizada rodando na AWS, com provisionamento automatizado da infraestrutura, pipeline de CI/CD e observabilidade e monitoramento.

## Stack

*   Terraform como infraestrutura como código
*   Drone CI como pipeline de CI/CD
*   Docker
*   AWS
*   Prometheus e Grafana
*   GitHub

## Desafio

Você deverá entregar um repositório que permita provisionar a infraestrutura, realizar deploy da aplicação e visualizar o funcionamento da aplicação e das métricas de forma externa.

## Requisitos

### Infraestrutura como código

Provisionar na AWS, utilizando Terraform, a infraestrutura necessária para executar a aplicação containerizada. A escolha dos serviços AWS é livre, desde que a solução permita acesso externo à aplicação.

### Container e deploy

## Criar uma aplicação simples containerizada.

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
*   Steps de testes

### Monitoramento e observabilidade

Disponibilizar métricas da aplicação utilizando Prometheus.
Disponibilizar um dashboard no Grafana com visualização das métricas da aplicação.
O dashboard deve estar acessível externamente.

## Entrega

Repositório GitHub contendo:

*   Código da aplicação
*   Dockerfile
*   Código Terraform
*   Pipeline CI/CD (Drone CI)
*   Configuração do Prometheus
*   Configuração do Grafana
*   README com instruções claras, completas de como rodar e validar

## README deve conter

*   Como rodar a aplicação localmente
*   Como que o ambiente da AWS é provisionado de forma automática explicando toda a infraestrutura e arquitetura
*   Como executar ou acionar o pipeline
*   URL pública da aplicação
*   URL pública do dashboard de métricas
*   Como validar que a solução está funcionando

## Avaliação

Os critérios abaixos serão avaliados:
*   Organização e clareza da solução
*   Qualidade da automação
*   Boas práticas de infraestrutura e deploy
*   Boas práticas de monitoramento e observabilidade
*   Clareza da documentação
*   Facilidade de execução e validação da solução

## Observações

Você pode tomar decisões técnicas livremente dentro da stack proposta.
Caso faça escolhas arquiteturais específicas, descreva brevemente no README o motivo dessas decisões.
A solução deve permitir validação externa, com aplicação e métricas acessíveis via URL pública.