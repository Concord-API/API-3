# Sprint Backlog
O objetivo do backlog é organizar, priorizar e tornar visível o trabalho que deve ser feito, garantindo que a equipe foque no que gera mais valor para o cliente e para o produto.

---
### Definition of Ready (DoR) – Geral
Uma User Story é considerada **pronta para entrar na sprint** quando:  
- Está claramente descrita, com valor de negócio identificado.  
- Possui critérios de aceitação definidos e compreendidos pelo time.  
- Foi priorizada pelo Product Owner.  
- Possui estimativa de esforço realizada pelo time de desenvolvimento.  
- Dependências externas foram identificadas e não bloqueiam o início da implementação.  
- Protótipo, wireframe ou referências visuais estão disponíveis (quando aplicável).  

---

### Definition of Done (DoD) – Geral
Uma User Story é considerada **concluída** quando:  
- Funcionalidade implementada atende a todos os critérios de aceitação.  
- Código desenvolvido foi revisado por pelo menos um membro da equipe.  
- Testes unitários e funcionais realizados e aprovados.  
- Funcionalidade integrada ao repositório principal sem conflitos.  
- Documentação do sistema foi atualizada (ex.: README, guia de uso ou prints).  
- Interface segue o padrão visual definido para o projeto.  
- A entrega foi demonstrada e validada pelo Product Owner na review da sprint.
---
### Dicionário

- Rank - ordem de entrega ≠ Prioridade
- Prioridade é oque agrega mais valor
- User Story: “O que o usuário quer?” - funcionalidade a ser desenvolvida e entregue
- Estimativa: medida de esforço em escala Fibonacci (1–13)
    
    > 1 – Muito Pequeno
    > 
    > 
    > Esforço mínimo, complexidade muito baixa, quase nenhum risco. Menos de um dia.
    > 
    > *Ex: pequena alteração de texto na interface.*
    > 
    
    ---
    
    > 2 – Pequeno
    > 
    > 
    > Baixo esforço, tarefa simples, poucas dependências. ~1–2 dias.
    > 
    > *Ex: adicionar um campo simples em um formulário.*
    > 
    
    ---
    
    > 3 – Médio-Pequeno
    > 
    > 
    > Esforço moderado, não trivial, pode envolver pequenos testes ou uma dependência.
    > 
    > *Ex: ajustar uma query no banco de dados.*
    > 
    
    ---
    
    > 5 – Médio
    > 
    > 
    > Esforço perceptível, alguma complexidade, possíveis dependências. Vários dias.
    > 
    > *Ex: desenvolver uma pequena funcionalidade ou endpoint de API.*
    > 
    
    ---
    
    > 8 – Grande
    > 
    > 
    > Alto esforço, múltiplas dependências, com certeza mias de um dev. ~1 semana ou mais.
    > 
    > *Ex: integrar um serviço de terceiros.*
    > 
    
    ---
    
    > 13 – Muito Grande
    > 
    > 
    > Complexidade significativa, muitas incertezas e dependências. Pode levar semanas. Muitas vezes deve ser dividido em histórias menores.
    > 
    > *Ex: refatorar todo o sistema para suportar microsserviços.*
    > 
- Sprint: Sprint em que a funcionalidade deve ser entregue

---
| Rank | Prioridade | User Story | Estimativa | Sprint |
| --- | --- | --- | --- | --- |
| 1 | Alta | **Como diretor**, quero visualizar e consultar um dashboard de cada equipe **para identificar rapidamente habilidades disponíveis e avaliar a distribuição dos talentos**. | 8 | Sprint 1 |
| 2 | Alta | **Como colaborador**, quero visualizar meu perfil e cadastrar minhas skills **para registrar minhas competências, certificações e experiências**. | 8 | Sprint 1 |
| 3 | Média | **Como usuário**, quero ter acesso a uma tela (mesmo que não funcional) de cadastro de usuário **para validação de nível de acesso - diretor, gestor e colaborador**. | 3 | Sprint 1 |


## Critérios de Aceitação – User Stories

### US 1  
**Como diretor, quero visualizar e consultar um dashboard de cada equipe para identificar rapidamente habilidades disponíveis e avaliar a distribuição dos talentos.**

- O sistema deve exibir um dashboard por equipe.  
- O dashboard deve listar todos os integrantes da equipe.  
- As skills de cada integrante devem estar visíveis.  
- O dashboard deve apresentar a distribuição das habilidades (ex.: gráfico ou listagem organizada).  
- O acesso ao dashboard deve estar disponível somente para diretores.  

---

### US 2  
**Como colaborador, quero visualizar meu perfil e cadastrar minhas skills para registrar minhas competências, certificações e experiências.**

- O colaborador deve conseguir acessar seu perfil individual.  
- O perfil deve permitir cadastrar, editar e excluir skills.  
- Cada skill deve incluir pelo menos: nome, nível e certificações associadas.  
- As informações cadastradas devem ser salvas no sistema e exibidas ao usuário.  
- O colaborador deve conseguir visualizar suas informações já registradas.  

---

### US 3  
**Como usuário, quero ter acesso a uma tela (mesmo que não funcional) de cadastro de usuário para validação de nível de acesso - diretor, gestor e colaborador.**

- O sistema deve exibir uma tela de cadastro de usuário.  
- A tela deve conter campos básicos: nome, e-mail, senha e nível de acesso (diretor, gestor, colaborador).  
- Os botões e campos podem não ter funcionalidade real nesta versão.  
- A tela deve seguir o padrão visual do sistema.  
- Deve ser possível simular o fluxo de cadastro, mesmo sem persistência de dados.  
