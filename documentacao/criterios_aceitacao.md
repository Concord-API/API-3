# 📌 **Critérios de Aceitação — Organizados por Sprint**


# 🟦 **Sprint 1**

## **US 1 – Dashboard por equipe (Diretor)**  
**Prioridade: Alta — Estimativa: 8**

- O sistema deve exibir um dashboard individual para cada equipe.  
- O dashboard deve listar todos os integrantes da equipe.  
- As skills de cada integrante devem estar visíveis.  
- Deve existir visualização da distribuição de habilidades (gráfico ou lista organizada).  
- O acesso ao dashboard deve ser permitido apenas para diretores.  

---

## **US 2 – Perfil e Skills (Colaborador)**  
**Prioridade: Alta — Estimativa: 8**

- O colaborador deve acessar seu próprio perfil.  
- Deve ser possível cadastrar, editar e excluir skills.  
- Cada skill deve conter nome, nível e certificações associadas.  
- As informações devem ser salvas e exibidas ao colaborador.  
- O colaborador deve visualizar seus dados cadastrados.  

---

## **US 3 – Tela de Cadastro de Usuário (Protótipo)**  
**Prioridade: Média — Estimativa: 3**

- O sistema deve exibir uma tela de cadastro de usuário.  
- Deve conter campos: nome, e-mail, senha, nível de acesso.  
- Botões e campos podem ser não funcionais.  
- A interface deve seguir o padrão visual do sistema.  
- O fluxo de cadastro deve ser simulável, mesmo sem persistência.  

---

# 🟧 **Sprint 2**

## **US 4 – Controle de Acesso por Perfil**  
**Prioridade: Alta — Estimativa: 5**

- O sistema deve restringir acesso conforme o perfil (diretor, gestor, colaborador).  
- Cada usuário deve visualizar/editar apenas suas próprias informações, exceto permissões específicas.  
- Diretores podem acessar dashboards e relatórios.  
- Gestores podem acessar dados da própria equipe.  
- Colaboradores acessam somente seu perfil.  
- Tentativas de acesso não autorizado devem ser bloqueadas e registradas.  

---

## **US 5 – Cadastro de Gestores**  
**Prioridade: Alta — Estimativa: 3**

- O sistema deve permitir cadastrar gestores.  
- Campos obrigatórios: nome, e-mail, setor vinculado.  
- O sistema deve validar dados obrigatórios.  
- O gestor cadastrado deve aparecer na listagem.  

---

## **US 6 – Cadastro de Colaboradores**  
**Prioridade: Alta — Estimativa: 3**

- O diretor deve conseguir cadastrar colaboradores.  
- Campos obrigatórios: nome, e-mail, setor e equipe vinculados.  
- O colaborador deve aparecer na listagem.  
- Os dados devem ser armazenados com consistência no banco.  

---

## **US 7 – Cadastro de Equipes**  
**Prioridade: Alta — Estimativa: 3**

- O sistema deve permitir criar equipes.  
- Campos obrigatórios: nome da equipe e gestor responsável.  
- A equipe deve aparecer na listagem.  
- Deve ser possível vincular colaboradores à equipe.  

---

## **US 8 – Cadastro de Setores**  
**Prioridade: Alta — Estimativa: 3**

- O sistema deve permitir cadastrar setores.  
- Campos obrigatórios: nome e descrição.  
- O setor deve aparecer na listagem.  
- Deve ser possível vincular equipes ao setor.  

---

## **US 9 – Dashboard Funcional com Métricas**  
**Prioridade: Alta — Estimativa: 8**

- O dashboard deve exibir métricas atualizadas (colaboradores, skills, setores etc.).  
- Dados devem atualizar em tempo real ou próximo disso.  
- O diretor deve filtrar métricas por equipe ou setor.  
- Acesso restrito a diretores.  

---

# 🟩 **Sprint 3**

## **US 10 – Avaliação de Colaboradores (Diretor)**  
**Prioridade: Média — Estimativa: 3**

- O diretor deve acessar uma tela de avaliação.  
- Deve selecionar um colaborador e registrar avaliação.    
- Avaliações devem ser armazenadas e consultáveis.  

---

## **US 11 – Autoavaliação (Colaborador)**  
**Prioridade: Média — Estimativa: 3**

- O colaborador deve acessar a tela de autoavaliação.  
- Deve registrar nível de proficiência de suas skills.  
- A autoavaliação deve ser salva no sistema.  
- O colaborador deve visualizar seu histórico de avaliações.  

---

## **US 12 – Login com Autenticação**  
**Prioridade: Baixa — Estimativa: 5**

- O sistema deve exibir tela de login.  
- Campos obrigatórios: e-mail e senha.    
- Usuário deve ser direcionado de acordo com o perfil.      

---

## **US 13 – Cadastro de Skills Não Registradas**  
**Prioridade: Média — Estimativa: 5**

- O usuário deve poder adicionar skills não existentes no sistema.  
- Deve cadastrar nome e categoria da skill.  
- Skills criadas devem atualizar indicadores automaticamente.  

---

## **US 14 – Liderança de Squad**  
**Prioridade: Baixa — Estimativa: 8**

- O colaborador pode ser designado líder de squad.  
- Deve ser possível criar squads com colaboradores de diferentes equipes.  
- O líder deve gerenciar membros e atividades internas.  
- Squads devem aparecer vinculados às equipes.  

---

## **US 15 – Proficiência Numérica + Cores (Diretor)**  
**Prioridade: Alta — Estimativa: 3**

- O diretor deve visualizar a proficiência numérica de cada skill.  
- Cada nível deve possuir também uma representação visual por cor.  
- A escala deve ser padronizada no sistema.  

---

## **US 16 – Filtro por Competências (Diretor)**  
**Prioridade: Alta — Estimativa: 5**

- O sistema deve filtrar colaboradores por skill.  
- Deve listar colaboradores que possuem a competência escolhida.  
- Dados apresentados devem se atualizar conforme os filtros aplicados.  
