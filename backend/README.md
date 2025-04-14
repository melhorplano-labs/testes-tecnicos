# Teste Técnico – Desenvolvedor Backend

**Tempo estimado de conclusão**: até 3 horas  
**Entrega**: publique o repositório como privado no GitHub e adicione renan.bessa@melhorplano.net e henrique@melhorplano.net como colaboradores.

---

## Contexto

A MelhorPlano.net é um dos maiores comparadores de planos de internet, celular e TV do Brasil. Por trás da experiência do usuário, temos uma operação robusta B2B que envolve integrações com parceiros, emissão de faturas e geração de NFs via backoffice.

Seu desafio é simular um cenário interno do nosso sistema de **emissão de faturas**, garantindo que os dados estejam organizados, validados e prontos para processamento.

---

## Desafio

### Cenário:

Você precisa construir uma **API para processar e emitir faturas de parceiros**. A cada ciclo de cobrança, o sistema recebe uma lista de cobranças pendentes que devem ser agrupadas por parceiro, somadas e ordenadas por valor total.

---

### 1. Endpoint `POST /charges`

Esse endpoint deve receber **uma lista de cobranças** no seguinte formato:

```json
{
  "chargeId": "c123",
  "partnerId": "net-01",
  "amount": 199.9,
  "reference": "2024-01",
  "timestamp": "2024-01-15T10:00:00Z"
}
```

#### Regras:

- Cada `chargeId` deve ser único (não aceitar duplicados).
- Armazenar as cobranças **em memória**.
- As cobranças devem poder ser agrupadas futuramente por `partnerId`.

---

### 2. Endpoint `GET /invoices`

Esse endpoint deve:

- Gerar uma **lista de faturas por parceiro**, com a soma total de cobranças pendentes por `partnerId`.
- Retornar a lista de faturas ordenada pelo **maior valor total primeiro**.
- Exemplo de retorno:

```json
[
  {
    "partnerId": "net-01",
    "total": 1200.50,
    "charges": [ ... ]
  },
  {
    "partnerId": "claro-12",
    "total": 950.00,
    "charges": [ ... ]
  }
]
```

- Após gerar a fatura, as cobranças envolvidas devem ser **removidas da memória** (simulando "faturadas").

---

## Requisitos obrigatórios

- Usar **Node.js com TypeScript**.
- Armazenamento apenas em memória (não usar banco de dados).
- Escrever pelo menos **3 testes automatizados** cobrindo os principais fluxos.
- Criar um `README.md` com instruções claras para rodar e testar a aplicação localmente.
- Criar um `DECISIONS.md` explicando:
  - Como garantiu idempotência (`chargeId` único).
  - Como agrupou e ordenou os dados de forma eficiente.
  - Qual estrutura de dados utilizou e por quê.
  - O que faria diferente se isso fosse parte de um sistema real de emissão de faturas/NFs.

---

## Avaliação

- Clareza e estrutura do código.
- Aplicação funcional e aderente aos requisitos.
- Lógica de agregação e ordenação.
- Padrões e boas práticas de desenvolvimento.
- Testes bem escritos e organizados.
- Histórico de commits claros e frequentes.
- Qualidade da documentação (`README.md` e `DECISIONS.md`).

---

## Entrega

Após concluir o desafio, publique o repositório como privado no GitHub e adicione renan.bessa@melhorplano.net e henrique@melhorplano.net como colaboradores.

---

## Observação Final

Sabemos que ferramentas de IA podem ser úteis para consulta, mas este desafio será complementado por uma **rápida conversa técnica com o tech lead e gestor**, onde vamos explorar suas decisões e domínio do que foi implementado.  
Nosso objetivo é encontrar alguém que resolva problemas reais com clareza, lógica e visão de produto — como fazemos todos os dias aqui na MelhorPlano.net!
