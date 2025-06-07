# Teste Técnico – Desenvolvedor(a) Fullstack

## 📝 Instruções importantes

- Este teste é **confidencial** e **não deve ser compartilhado** ou divulgado publicamente.
- Você terá **até 5 dias** para completá-lo a partir do envio.
- Ao finalizar:
  - Publique o repositório como **privado** no GitHub.
  - Adicione `renan.bessa@melhorplano.net` como colaborador.
  - Responda este e-mail informando a **conclusão** do teste.

---

## 🎯 Objetivo

Avaliar sua capacidade de desenvolver uma aplicação **web fullstack simples**, incluindo:

- Montagem do ambiente
- Consumo de um CMS headless
- Criação de uma API básica
- Escrita de testes unitários

---

## 💡 Desafio

Crie uma aplicação web que:

- Liste conteúdos vindos de um **CMS headless**
- Permita a **criação de novos posts** via API própria

---

## ✅ Requisitos funcionais

- [ ] Listar posts cadastrados no CMS na página inicial
- [ ] Exibir **título**, **data de publicação** e **resumo** de cada post
- [ ] Página de **detalhes do post** com título, conteúdo e data de publicação
- [ ] Página com **formulário de cadastro** de novo post (campos: título, resumo, conteúdo)
- [ ] Implementar **pesquisa por título** dos posts
- [ ] Criar uma **API própria** para cadastrar novos posts

---

## ⚙️ Requisitos técnicos

### Backend

- Utilize **Strapi** ou **WordPress (modo headless)** como CMS
- Configure com **Docker** para subir CMS e front-end juntos
- Crie uma **API intermediária (BFF)** entre o front-end e o CMS

### Frontend

- Utilize **Astro.js** ou **Next.js**
- Linguagem: **TypeScript**
- Framework: **React** com **componentes funcionais** e **hooks**
- Gerência de estado: simples
- SEO: garanta que o conteúdo dos posts esteja renderizado no **HTML**

### Testes

- Ao menos **2 testes unitários**:
  - ✅ Um para a **API** (testar criação de post)
  - ✅ Um para um **componente de front-end** (ex: listagem de posts ou formulário)
- **Cobertura de testes ≥ 80%** é diferencial (não obrigatório)
- Adicione instruções claras de como rodar a aplicação no próprio README
- Deploy é **opcional**, mas conta como **bônus**

---

## 🔍 Critérios de avaliação

- ✅ Aplicação **funcional** e aderente aos requisitos
- ✅ Código **organizado**, modular e seguindo boas práticas
- ✅ Padrões de desenvolvimento consistentes
- ✅ Histórico de commits **claro** e **frequente**
- ✅ Testes implementados e executáveis
- ✅ Abordagem e **raciocínio** na resolução do problema

> ⚡ **Dica**: evite um único commit gigante. Prefira **commits menores** e bem descritos.

---

> O que não te desafia, não te transforma! 🚀  
> **Boa sorte!**
