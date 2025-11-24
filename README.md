<p align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=980AC9&height=120&section=header"/>
</p>

# API 3º Semestre BD

# Proficio - Mapeamento de Competências

## Sobre a plataforma
O projeto consiste no desenvolvimento de uma plataforma de mapeamento de competências, funcionando como um “LinkedIn interno” da empresa. Nela, cada colaborador poderá criar e manter um perfil profissional com suas competências técnicas, soft skills, certificações, experiências e outras informações relevantes. Os gestores terão a possibilidade de complementar esses perfis com tags e avaliações, o que facilitará a identificação de talentos de forma objetiva. A plataforma permitirá realizar buscas por habilidades específicas, apoiar a organização de equipes, avaliar departamentos e visualizar a distribuição de competências dentro da empresa, tornando-se uma ferramenta estratégica para a gestão de pessoas e desenvolvimento profissional.

## [📚 Guia de Instalação - *Proficio*](https://github.com/Concord-API/API-3/blob/sprint-3/documentacao/guia_instal.md)

### 🗓️ Cronograma do Projeto
| Sprint | Período | Objetivo Principal | Documentação |
|-------|-----------------------------|--------------------|--------------------|
| [**Sprint 1**](https://github.com/Concord-API/API-3/tree/sprint-1) | 08/09/2025 → 28/09/2025 | Construção da base da aplicação e funcionalidades essenciais. | [Docs. Sprint 1](https://github.com/Concord-API/API-3/tree/sprint-1/documentacao) |
| [**Sprint 2**](https://github.com/Concord-API/API-3/tree/sprint-2) | 06/10/2025 → 26/10/2025 | Desenvolvimento das features centrais e refinamento do fluxo. | [Docs. Sprint 2](https://github.com/Concord-API/API-3/tree/sprint-2/documentacao)|
| [**Sprint 3**](https://github.com/Concord-API/API-3/tree/sprint-3) | 03/11/2025 → 23/11/2025 | Conclusão dos épicos, testes e estabilização do sistema. | [Docs. Sprint 3](https://github.com/Concord-API/API-3/tree/sprint-3/documentacao) |

---

<details>
  <summary><strong>🟪 Product Backlog</strong></summary>

  <br>

> O objetivo do backlog é organizar, priorizar e tornar visível o trabalho que deve ser feito, garantindo que a equipe foque no que gera mais valor para o cliente e 
para o produto.

| Rank | Prioridade | User Story | Estimativa | Sprint |
| --- | --- | --- | --- | --- |
| 1 | Alta | [**Como diretor**, quero visualizar e consultar um dashboard de cada equipe **para identificar rapidamente habilidades disponíveis e avaliar a distribuição dos talentos.**](https://github.com/Concord-API/API-3/issues/8) | 8 | Sprint 1 |
| 2 | Alta | [**Como colaborador**, quero visualizar meu perfil e cadastrar minhas skills **para registrar minhas competências, certificações e experiências**.](https://github.com/Concord-API/API-3/issues/9) | 8 | Sprint 1 |
| 3 | Média | [**Como usuário**, quero ter acesso a uma tela (mesmo que não funcional) de cadastro de usuário **para validação de nível de acesso - diretor, gestor e colaborador**.](https://github.com/Concord-API/API-3/issues/10) | 3 | Sprint 1 |
| 4 | Alta | [**Como usuário**, quero ter acesso restrito às minhas informações **para garantir segurança e privacidade de acordo com meu nível de acesso**.](https://github.com/Concord-API/API-3/issues/20) | 5 | Sprint 2 |
| 5 | Alta | [**Como diretor**, quero cadastrar gestores **para organizar a relação de lideranças e equipes**.](https://github.com/Concord-API/API-3/issues/21) | 3 | Sprint 2 |
| 6 | Alta | [**Como diretor**, quero cadastrar colaboradores **para manter atualizado o quadro de profissionais da empresa**.](https://github.com/Concord-API/API-3/issues/22) | 3 | Sprint 2 |
| 7 | Alta | [**Como diretor**, quero cadastrar equipes **para vincular colaboradores e gestores em grupos de trabalho**.](https://github.com/Concord-API/API-3/issues/23) | 3 | Sprint 2 |
| 8 | Alta | [**Como diretor**, quero cadastrar setores **para estruturar melhor a divisão organizacional**.](https://github.com/Concord-API/API-3/issues/24) | 3 | Sprint 2 |
| 9 | Alta | [**Como diretor**, quero acessar um dashboard funcional **para analisar métricas em tempo real das equipes**.](https://github.com/Concord-API/API-3/issues/25) | 8 | Sprint 2 |
| 10 | Média | [**Como diretor**, quero avaliar colaboradores **para identificar talentos e oportunidades de desenvolvimento**.](https://github.com/Concord-API/API-3/issues/56) | 3 | Sprint 3 |
| 11 | Média | [**Como colaborador**, quero avaliar minhas próprias competências **para acompanhar meu progresso e desenvolvimento profissional**.](https://github.com/Concord-API/API-3/issues/55) | 3 | Sprint 3 |
| 12 | Baixa | [**Como usuário**, quero realizar login no sistema **para acessar funcionalidades de acordo com meu perfil de acesso e ter segurança dos meus dados com autenticações**.](https://github.com/Concord-API/API-3/issues/57) | 5 | Sprint 3 |
| 13 | Média | [**Como usuário**, quero poder cadastrar skills - mesmo que não registradas no sistema, **para atualizar automaticamente indicadores relacionados**.](https://github.com/Concord-API/API-3/issues/58) | 5 | Sprint 3 |
| 14 | Baixa | [**Como colaborador**, quero poder liderar um *squad* dentro de uma equipe **para gerenciar projetos específicos e facilitar a organização interna**.](https://github.com/Concord-API/API-3/issues/64) | 8 | Sprint 3 |
| 15 | Alta | [**Como diretor**, quero poder distinguir o nível de proficiência de uma skill por um número, além de poder distinguir por cores **para facilitar identificação do nível de proficiência de cada habilidade**.](https://github.com/Concord-API/API-3/issues/65) | 3 | Sprint 3 |
| 16 | Alta | [**Como diretor**, quero visualizar colaboradores por filtro de competências **para listar e analisar os profissionais que possuem determinada habilidade**.](https://github.com/Concord-API/API-3/issues/66) | 5 | Sprint 3 |


</details>


<details open>
  <summary><strong>🧩 Estratégia de branches e padrões de commits</strong></summary>

  <br>
  
### 🌿 Estrutura de Branches
  - **main**: Branch principal e estável do projeto. Recebe merges apenas ao final de cada sprint, após revisão e aprovação.  
  - **sprintX** (ex: sprint1, sprint2, sprint3): Cada sprint possui sua própria branch base, onde são integradas todas as funcionalidades desenvolvidas durante aquele ciclo.  
  - **task-número/feature-com-traço-se-tiver-espaco**: Para cada nova funcionalidade ou correção, é criada uma branch específica a partir da branch da sprint em andamento.  
    Exemplo: `task-23/crud-cargo`

  Após a conclusão e revisão da funcionalidade, é feito um *Pull Request (PR)* para a branch da sprint correspondente.  
  Quando o merge é aprovado, a branch da funcionalidade é deletada para manter o repositório limpo.  
  Ao final da sprint, a branch sprintX é integrada à main através de um *Pull Request* final.  
  A branch da sprint é mantida como histórico do desenvolvimento daquela iteração.

  **obs:** Para as branches de documentação é usada a estrutura `docs/...`

  ---

  ### 📊 Padrões de Commits
  Cada commit deve ser pequeno, descritivo e objetivo, seguindo o padrão de convenção semântica:
- feat: descrição da nova funcionalidade
- fix: correção de bug ou comportamento inesperador
- factor: melhoria de código sem alterar comportamento
- docs: atualização de documentação
- chore: tarefas de configuração, build ou manutenção

Exemplo: `feat: adicionar suporte para cargos e melhorias no formulário de criação de colaboradores, incluindo seleção de gênero e avatar`

O número de commits é usado como indicador de contribuição individual e progresso da sprint, permitindo rastrear o fluxo de trabalho no repositório

</details>




<details>
<summary><strong>🧱 Tasks</strong></summary>

  <br>

## Estrutura e organização das tasks

### o GitHub Projects foi a ferramenta escolhida para alocação de tarefas
**As tasks do projeto seguem uma organização hierárquica baseada na numeração.**
### Épicos (tasks principais)
Tasks representadas por números inteiros seguidos de .0 (ex.: 20.0, 23.0) indicam funcionalidades amplas ou macroentregas.
Esses épicos agrupam um conjunto de subtarefas relacionadas.
### Subtarefas (tasks derivadas)
Tasks que não terminam em .0 (ex.: 23.1, 20.2) representam partes específicas do épico correspondente.
Elas detalham e subdividem a entrega em atividades menores.
</details>

---

### Tecnologias utilizadas
<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=java,ts,js,css,html,git,github,docker,spring,idea,vscode,mysql,tailwind" />
  </a>
</p>

---

### Sobre nós
A Concord é uma equipe do 3º semestre comprometida com a criação de soluções tecnológicas que unem inovação, eficiência e impacto. Nosso propósito é transformar desafios em oportunidades por meio da aplicação de metodologias ágeis, pensamento crítico e criatividade.

Contamos com um time multidisciplinar, engajado e colaborativo, que valoriza o aprendizado contínuo e a troca de experiências para evoluir em cada projeto. Buscamos excelência em nossas entregas, priorizando qualidade, escalabilidade e visão prática.

Acreditamos que a força da nossa equipe está na união entre a dedicação, a curiosidade e a capacidade de encontrar soluções inteligentes, consolidando a Concord como um grupo em constante evolução, pronto para enfrentar desafios e gerar resultados de alto valor.

---

### 🎯 Nossa Missão e Visão

<u>Missão:</u>
Aplicar conhecimento e criatividade para desenvolver soluções tecnológicas inovadoras, que não apenas impulsionem a eficiência, mas também fortaleçam o aprendizado, a colaboração e o impacto positivo em empresas e comunidades.

<u>Visão:</u>
Consolidar-se como uma equipe de referência em tecnologia e inovação acadêmica, reconhecida pela capacidade de transformar ideias em projetos de qualidade, com resultados escaláveis e relevantes para o mercado e para a sociedade.

---
### Quem somos?

| Integrante                 | Função |
|:--------------------------:|:------------------------:|
 Vinicius P. de Pádua       | Product Owner            |
 João Vitor Andrade         | Scrum Master             |
 João Vitor Baranov         | Developer                |
 Victor Nogueira            | Developer                |
 Richard Leonardo Cordeiro  | Developer                |
 Isaac Oliveira             | Developer                |
