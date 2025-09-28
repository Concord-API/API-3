# Product Backlog
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
| 4 | Alta | **Como usuário**, quero ter acesso restrito às minhas informações **para garantir segurança e privacidade de acordo com meu nível de acesso**. | 5 | Sprint 2 |
| 5 | Alta | **Como diretor**, quero cadastrar gestores **para organizar a relação de lideranças e equipes**. | 3 | Sprint 2 |
| 6 | Alta | **Como diretor**, quero cadastrar colaboradores **para manter atualizado o quadro de profissionais da empresa**. | 3 | Sprint 2 |
| 7 | Alta | **Como diretor**, quero cadastrar equipes **para vincular colaboradores e gestores em grupos de trabalho**. | 3 | Sprint 2 |
| 8 | Alta | **Como diretor**, quero cadastrar setores **para estruturar melhor a divisão organizacional**. | 3 | Sprint 2 |
| 9 | Alta | **Como diretor**, quero acessar um dashboard funcional **para analisar métricas em tempo real das equipes**. | 8 | Sprint 2 |
| 10 | Média | **Como diretor**, quero avaliar colaboradores **para identificar talentos e oportunidades de desenvolvimento**. | 3 | Sprint 3 |
| 11 | Média | **Como colaborador**, quero avaliar minhas próprias competências **para acompanhar meu progresso e desenvolvimento profissional**. | 3 | Sprint 3 |
| 12 | Média | **Como diretor**, quero filtrar dashboards por métricas específicas **para facilitar a análise de dados de acordo com necessidades**. | 8 | Sprint 3 |
| 13 | Baixa | **Como usuário**, quero realizar login no sistema **para acessar funcionalidades de acordo com meu perfil de acesso e ter segurança dos meus dados com autenticações**. | 5 | Sprint 3 |
| 14 | Baixa | **Como usuário**, quero poder cadastrar skills - mesmo que não registradas no sistema, **para atualizar automaticamente indicadores relacionados**. | 5 | Sprint 3 |

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

---

### US 4  
**Como usuário, quero ter acesso restrito às minhas informações para garantir segurança e privacidade de acordo com meu nível de acesso.**

- O sistema deve restringir o acesso às informações com base no perfil (diretor, gestor, colaborador).  
- Cada usuário só deve visualizar e editar suas próprias informações, exceto quando o nível de acesso permitir.  
- Diretores devem ter acesso a dashboards e relatórios de equipes.  
- Gestores devem ter acesso apenas às informações de sua equipe.  
- Colaboradores devem ter acesso apenas ao próprio perfil.  
- Tentativas de acesso não autorizado devem ser bloqueadas e registradas.  

---

### US 5  
**Como diretor, quero cadastrar gestores para organizar a relação de lideranças e equipes.**

- O sistema deve disponibilizar formulário para cadastro de gestores.  
- Campos obrigatórios: nome, e-mail, setor vinculado.  
- O sistema deve validar dados obrigatórios antes de salvar.  
- Gestor cadastrado deve aparecer na listagem de gestores.  

---

### US 6  
**Como diretor, quero cadastrar colaboradores para manter atualizado o quadro de profissionais da empresa.**

- O sistema deve permitir o cadastro de colaboradores.  
- Campos obrigatórios: nome, e-mail, setor e equipe vinculados.  
- Colaborador cadastrado deve aparecer na listagem de colaboradores.  
- Dados devem ser armazenados no banco com consistência.  

---

### US 7  
**Como diretor, quero cadastrar equipes para vincular colaboradores e gestores em grupos de trabalho.**

- O sistema deve permitir criar novas equipes.  
- Campos obrigatórios: nome da equipe e gestor responsável.  
- A equipe cadastrada deve ficar visível na listagem de equipes.  
- O sistema deve permitir vincular colaboradores a uma equipe.  

---

### US 8  
**Como diretor, quero cadastrar setores para estruturar melhor a divisão organizacional.**

- O sistema deve permitir cadastrar setores.  
- Campos obrigatórios: nome do setor e descrição.  
- O setor cadastrado deve aparecer em listagem de setores disponíveis.  
- O sistema deve permitir vincular equipes a um setor.  

---

### US 9  
**Como diretor, quero acessar um dashboard funcional para analisar métricas em tempo real das equipes.**

- O dashboard deve exibir métricas atualizadas sobre equipes (quantidade de colaboradores, skills, setores etc.).  
- O sistema deve atualizar as métricas em tempo real ou próximo de tempo real.  
- O diretor deve conseguir filtrar e visualizar métricas por equipe ou setor.  
- O acesso ao dashboard deve ser restrito a diretores.  

---

### US 10  
**Como diretor, quero avaliar colaboradores para identificar talentos e oportunidades de desenvolvimento.**

- O diretor deve ter acesso a uma tela de avaliação de colaboradores.  
- Deve ser possível selecionar um colaborador e registrar uma avaliação.  
- A avaliação deve conter critérios como desempenho, habilidades e potencial.  
- Avaliações devem ser armazenadas e consultáveis posteriormente.  

---

### US 11  
**Como colaborador, quero avaliar minhas próprias competências para acompanhar meu progresso e desenvolvimento profissional.**

- O colaborador deve ter acesso a uma tela de autoavaliação.  
- Deve ser possível selecionar suas próprias skills e registrar uma nota/nível de proficiência.  
- A autoavaliação deve ficar registrada no sistema.  
- O colaborador deve conseguir visualizar seu histórico de avaliações.  

---

### US 12  
**Como diretor, quero filtrar dashboards por métricas específicas para facilitar a análise de dados de acordo com necessidades.**

- O dashboard deve disponibilizar filtros (ex.: por setor, equipe, skill, nível de proficiência).  
- O sistema deve exibir dados atualizados de acordo com os filtros aplicados.  
- O diretor deve conseguir limpar os filtros e voltar à visão geral.  
- O acesso a esta funcionalidade deve ser restrito a diretores.  

---

### US 13  
**Como usuário, quero realizar login no sistema para acessar funcionalidades de acordo com meu perfil de acesso e ter segurança dos meus dados com autenticações.**

- O sistema deve disponibilizar tela de login.  
- Campos obrigatórios: e-mail e senha.  
- Login deve validar credenciais contra banco de dados.  
- Após login, o sistema deve direcionar o usuário para as funcionalidades de acordo com seu perfil.  
- Tentativas inválidas devem gerar mensagem de erro.  
- Dados sensíveis devem ser protegidos (armazenamento seguro de senhas, autenticação).  

---

### US 14  
**Como usuário, quero poder cadastrar skills – mesmo que não registradas no sistema, para atualizar automaticamente indicadores relacionados.**

- O usuário deve conseguir inserir skills não previamente cadastradas no sistema.  
- O sistema deve permitir salvar a nova skill com nome e categoria definida pelo usuário.  
- Skills novas devem passar a compor indicadores e relatórios automaticamente.  
- O usuário deve conseguir editar ou excluir skills criadas por ele.  
