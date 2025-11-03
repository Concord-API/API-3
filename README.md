<p align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=980AC9&height=120&section=header"/>
</p>

## Sobre a plataforma
O projeto consiste no desenvolvimento de uma plataforma de mapeamento de competências, funcionando como um “LinkedIn interno” da empresa. Nela, cada colaborador poderá criar e manter um perfil profissional com suas competências técnicas, soft skills, certificações, experiências e outras informações relevantes. Os gestores terão a possibilidade de complementar esses perfis com tags e avaliações, o que facilitará a identificação de talentos de forma objetiva. A plataforma permitirá realizar buscas por habilidades específicas, apoiar a organização de equipes, avaliar departamentos e visualizar a distribuição de competências dentro da empresa, tornando-se uma ferramenta estratégica para a gestão de pessoas e desenvolvimento profissional.

<details>
  <summary><strong>🟧 Sprint Backlog</strong></summary>

  <br>

> O objetivo do backlog é organizar, priorizar e tornar visível o trabalho que deve ser feito, garantindo que a equipe foque no que gera mais valor para o cliente e 
para o produto.

| Rank | Prioridade | User Story | Estimativa | Sprint |
| --- | --- | --- | --- | --- |
| 10 | Média | **Como diretor**, quero avaliar as skills dos colaboradores **para identificar talentos e oportunidades de desenvolvimento**. | 3 | Sprint 3 |
| 11 | Média | **Como colaborador**, quero avaliar minhas próprias competências **para acompanhar meu progresso e desenvolvimento profissional**. | 3 | Sprint 3 |
| 12 | Baixa | **Como usuário**, quero realizar login no sistema **para acessar funcionalidades de acordo com meu perfil de acesso e ter segurança dos meus dados com autenticações**. | 5 | Sprint 3 |
| 13 | Média | **Como usuário**, quero poder cadastrar skills - mesmo que não registradas no sistema, **para atualizar automaticamente indicadores relacionados**. | 5 | Sprint 3 |
| 14 | Baixa | **Como colaborador**, quero poder liderar um *squad* dentro de uma equipe **para gerenciar projetos específicos e facilitar a organização interna**. | 8 | Sprint 3 |
| 15 | Alta | **Como diretor**, quero poder distinguir o nível de proficiência de uma skill por um número, além de poder distinguir por cores **para facilitar identificação do nível de proficiência de cada habilidade**. | 3 | Sprint 3 |
| 16 | Alta | **Como diretor**, quero visualizar colaboradores por filtro de competências **para listar e analisar os profissionais que possuem determinada habilidade**. | 5 | Sprint 3 |

</details>

<details open>
  <summary><strong>🧩 Estratégia de Branches e padrões de commits</strong></summary>

  <br>
  
### 🌿 Estrutura de Branches
  - **main**: Branch principal e estável do projeto. Recebe merges apenas ao final de cada sprint, após revisão e aprovação.  
  - **sprintX** (ex: sprint1, sprint2, sprint3): Cada sprint possui sua própria branch base, onde são integradas todas as funcionalidades desenvolvidas durante aquele ciclo.  
  - **feature/...**: Para cada nova funcionalidade ou correção, é criada uma branch específica a partir da branch da sprint em andamento.  
    Exemplo: `feature/nome-da-funcionalidade`

  Após a conclusão e revisão da funcionalidade, é feito um *Pull Request (PR)* para a branch da sprint correspondente.  
  Quando o merge é aprovado, a branch da funcionalidade é deletada para manter o repositório limpo.  
  Ao final da sprint, a branch sprintX é integrada à main através de um *Pull Request* final.  
  A branch da sprint é mantida como histórico do desenvolvimento daquela iteração.

  ---

  ### 📊 Métrica de Commits
  Cada commit deve ser pequeno, descritivo e objetivo, seguindo o padrão de convenção semântica:
feat: descrição da nova funcionalidadefix: correção de bug ou comportamento inesperadorefactor: melhoria de código sem alterar comportamentodocs: atualização de documentaçãochore: tarefas de configuração, build ou manutenção
O número de commits é usado como indicador de contribuição individual e progresso da sprint, permitindo rastrear o fluxo de trabalho no repositório

</details>


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
