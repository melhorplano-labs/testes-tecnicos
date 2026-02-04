# Teste técnico - Engenheiro DevOps

## Objetivo

O objetivo deste teste é avaliar conhecimentos práticos em:

- Infraestrutura como código
- Containerização
- CI/CD
- Deploy em cloud
- Observabilidade e monitoramento
- Boas práticas de segurança e automação

O resultado esperado é uma aplicação containerizada rodando na AWS, com infraestrutura provisionada via Terraform, deploy automatizado via CI/CD e métricas observáveis externamente.

**Tempo previsto**: ~3 horas 

**Observações**:
- Não esperamos perfeição ou solução enterprise. Esperamos clareza técnica, boas decisões e automação funcional.
- Uso de IA: Queremos avaliar sua forma de resolver problemas. Use a documentação e a IA como apoio para dúvidas pontuais, mas evite que a ferramenta crie blocos de código ou descrições no seu lugar.
- Você pode tomar decisões técnicas livremente dentro da stack proposta abaixo. Caso faça escolhas arquiteturais específicas, descreva brevemente no README o motivo dessas decisões

Sua entrega deve refletir sua forma de pensar, pois discutiremos suas decisões técnicas em uma próxima etapa.

## Stack

- Terraform
- Docker
- AWS
- Drone CI
- Prometheus
- Grafana
- GitHub

## Desafio

Você deverá entregar um repositório que permita:
- Provisionar infraestrutura na AWS
- Realizar deploy automatizado da aplicação
- Disponibilizar a aplicação publicamente
- Disponibilizar métricas da aplicação
- Disponibilizar dashboard de monitoramento acessível externamente

## Requisitos

### Aplicação
A aplicação deve ser simples (ex: API HTTP ou web app mínima).

Deve obrigatoriamente ter:
- Endpoint /health, onde deve retornar status 200
- Endpoint /metrics com métricas no formato Prometheus

Deve expor pelo menos:
- 1 métrica de contador (ex: total de requests)
- 1 métrica de tempo ou latência (histograma ou gauge)

A linguagem é livre, mas se fosse pra recomendar, escolheria Node.JS, pois é a stack principal da empresa

### Containerização

A aplicação deve:
- Rodar em container Docker
- Ter dockerfile funcional
- Estar publicada na AWS (ECR)

### Infraestrutura como código

Provisionar na AWS usando Terraform.
A escolha dos serviços é livre, desde que permita acesso externo à aplicação.

Exemplos possíveis (não obrigatório):
- ECS
- EC2
- Fargate
- Outro modelo equivalente

Terraform deve obrigatoriamente gerar outputs:
- URL da aplicação
- URL do Grafana

### Deploy CI/CD

Criar pipeline no Drone CI para:

- Build da aplicação
- Build da imagem Docker
- Publicação da imagem em registry
- Deploy automatizado na AWS
- Test step simples
- Terraform plan no pipeline
- Versionamento/tag da imagem

### Monitoramento e observabilidade

- Prometheus coletando métricas da aplicação
- Dashboard no Grafana exibindo métricas da aplicação
- Grafana deve ser acessível externamente com autenticação

## Entrega

Repositório github privado compartilhado com os e-mails `renan.bessa@melhorplano.net` e `luiz.eduardo@melhorplano.net` contendo:

- Código da aplicação
- Dockerfile
- Código Terraform
- Pipeline CI/CD (Drone CI)
- Configuração do Prometheus
- Configuração do Grafana
- README completo com instruções claras do projeto, como rodar e validar

## Avaliação

Os critérios abaixos serão avaliados:
- Organização e clareza da solução
- Qualidade da automação
- Boas práticas de infraestrutura e deploy
- Boas práticas de monitoramento e observabilidade
- Clareza da documentação
- Facilidade de execução e validação da solução