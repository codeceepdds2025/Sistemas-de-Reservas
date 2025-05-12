💻 Sistema Exemplo: Sistema de Reservas de Salas e Recursos
Aplicação web para agendar o uso de salas (reunião, aula, laboratório) e recursos (projetor, notebooks), com login, regras de conflito, relatórios e painel administrativo.

🧩 Etapa 1: Concepção e Levantamento de Requisitos
🎯 Objetivo: Compreender a necessidade dos usuários e mapear os requisitos do sistema.

📚 Disciplinas envolvidas: Engenharia de Software, Interação Humano-Computador.

🧠 Conhecimentos necessários:

Tipos de requisitos (funcionais e não funcionais)

Técnicas de elicitação: entrevistas, observação, brainstorming

Personas, jornada do usuário

🛠 Ferramentas/métodos:

Miro, Lucidchart, Google Forms

Canvas de Produto, Histórias de Usuário, Casos de Uso

📦 Entregas:

Documento de requisitos (SRS)

Lista de funcionalidades priorizadas (backlog inicial)

Personas e mapas de empatia

✅ Boas práticas:

Envolver stakeholders reais

Validar com protótipos de baixa fidelidade

Criar critérios de aceitação claros

🧩 Etapa 2: Análise e Modelagem de Sistema
🎯 Objetivo: Estruturar como o sistema se comporta e interage com os usuários e outros sistemas.

📚 Disciplinas envolvidas: Análise de Sistemas, Modelagem de Software.

🧠 Conhecimentos necessários:

Diagramas UML: casos de uso, sequência, estados

DFDs (nível 0 e 1), escopo funcional

🛠 Ferramentas/métodos:

StarUML, Draw.io, Lucidchart

📦 Entregas:

Casos de uso

Diagrama de contexto e fluxos de dados

Regras de negócio documentadas

✅ Boas práticas:

Manter escopo controlado

Revisar diagramas com equipe

Documentar exceções e fluxos alternativos

🧩 Etapa 3: Modelagem de Dados
🎯 Objetivo: Projetar como os dados serão estruturados e armazenados no sistema.

📚 Disciplinas envolvidas: Banco de Dados Relacional.

🧠 Conhecimentos necessários:

Notação DER (Chen ou UML)

Normalização até a 3FN

Álgebra Relacional e SQL

🛠 Ferramentas/métodos:

MySQL Workbench, dbdiagram.io, PostgreSQL

📦 Entregas:

DER lógico e físico

Scripts SQL de criação de tabelas (DDL) e relacionamentos

✅ Boas práticas:

Usar chaves estrangeiras para integridade

Documentar cada entidade e atributo

Separar dados sensíveis (login) do domínio (reservas)

🧩 Etapa 4: Arquitetura e Projeto de Software
🎯 Objetivo: Estruturar a organização interna do sistema (camadas, responsabilidades).

📚 Disciplinas envolvidas: Arquitetura de Software, Padrões de Projeto.

🧠 Conhecimentos necessários:

MVC, Clean Architecture, camadas

Design Patterns (Factory, Singleton, Observer)

🛠 Ferramentas/métodos:

Diagrama de classes, serviços REST

Frameworks (Django, FastAPI, React)

📦 Entregas:

Documento de arquitetura

Diagrama de classes e pacotes

✅ Boas práticas:

Separação clara entre lógica, dados e apresentação

Injeção de dependência

Reutilização de componentes

🧩 Etapa 5: Planejamento e Metodologia de Desenvolvimento
🎯 Objetivo: Definir como a equipe trabalhará para entregar valor iterativamente.

📚 Disciplinas envolvidas: Gestão Ágil de Projetos, Engenharia de Requisitos.

🧠 Conhecimentos necessários:

Scrum, Kanban, XP

Gestão de backlog, burndown, velocity

🛠 Ferramentas/métodos:

Trello, GitHub Projects, Jira

Planning poker, MoSCoW

📦 Entregas:

Sprints definidas

Roadmap de entregas

✅ Boas práticas:

Reuniões diárias curtas (daily)

Revisão de sprint com stakeholders

Ajustes constantes no backlog

🧩 Etapa 6: Implementação
🎯 Objetivo: Codificar o sistema de acordo com os requisitos e arquitetura definida.

📚 Disciplinas envolvidas: Programação, Estrutura de Dados, POO.

🧠 Conhecimentos necessários:

Lógica de programação, orientação a objetos

Desenvolvimento frontend e backend

Integração com banco de dados

🛠 Ferramentas/métodos:

Frontend: React, Bootstrap, HTML/CSS

Backend: FastAPI, Django, Flask

Banco: PostgreSQL

📦 Entregas:

Código-fonte versionado

Interface funcional do sistema

✅ Boas práticas:

Código limpo (Clean Code)

Commits atômicos

Reaproveitamento de componentes

🧩 Etapa 7: Testes de Software
🎯 Objetivo: Garantir que o sistema funciona corretamente e sem regressões.

📚 Disciplinas envolvidas: Qualidade de Software.

🧠 Conhecimentos necessários:

Testes unitários, de integração, aceitação

TDD e BDD

🛠 Ferramentas/métodos:

Pytest, Jest, Postman, Selenium

📦 Entregas:

Scripts de testes

Relatórios de cobertura e falhas

✅ Boas práticas:

Automação de testes

Testes antes de deploy

Integração com CI/CD

🧩 Etapa 8: Controle de Versão
🎯 Objetivo: Organizar o histórico e colaboração no código.

📚 Disciplinas envolvidas: Ferramentas de Desenvolvimento Colaborativo.

🧠 Conhecimentos necessários:

Git básico e avançado

Resolução de conflitos

🛠 Ferramentas/métodos:

Git, GitHub/GitLab, Gitflow

📦 Entregas:

Repositório organizado

Branches para features, hotfixes

✅ Boas práticas:

Commits descritivos

Pull Requests revisados

Tags para versões

🧩 Etapa 9: Deploy e DevOps
🎯 Objetivo: Disponibilizar o sistema em ambiente de produção.

📚 Disciplinas envolvidas: Infraestrutura, DevOps.

🧠 Conhecimentos necessários:

Docker, CI/CD, hospedagem

🛠 Ferramentas/métodos:

Docker Compose, GitHub Actions, Railway, Nginx

📦 Entregas:

Imagem Docker, arquivo docker-compose.yml

Pipeline CI/CD

✅ Boas práticas:

Deploy automatizado

Rollback em caso de erro

Backup e monitoramento

🧩 Etapa 10: Segurança
🎯 Objetivo: Proteger dados e garantir acesso seguro.

📚 Disciplinas envolvidas: Segurança da Informação.

🧠 Conhecimentos necessários:

Hashing, autenticação, injeção

🛠 Ferramentas/métodos:

JWT, OAuth2, bcrypt

Helmet.js, CSRF tokens

📦 Entregas:

Mecanismos de login seguro

Logs e controle de acesso

✅ Boas práticas:

Validação do lado do servidor

Sanitização de inputs

Políticas de senha forte

🧩 Etapa 11: Documentação
🎯 Objetivo: Facilitar entendimento, manutenção e uso do sistema.

📚 Disciplinas envolvidas: Comunicação Técnica.

🧠 Conhecimentos necessários:

Markdown, Swagger, diagramação

🛠 Ferramentas/métodos:

README.md, OpenAPI/Swagger, Wiki

📦 Entregas:

Manual do usuário

Documentação técnica e de API

✅ Boas práticas:

Atualizar conforme mudanças

Linguagem simples

Incluir exemplos práticos

🧩 Etapa 12: Manutenção, Feedback e Iteração
🎯 Objetivo: Corrigir, evoluir e adaptar o sistema ao uso real.

📚 Disciplinas envolvidas: Engenharia de Software, UX, Análise de Métricas.

🧠 Conhecimentos necessários:

Refatoração, métricas, logs, feedback

🛠 Ferramentas/métodos:

Sentry, Google Analytics, Hotjar

Formulários de feedback, entrevistas

📦 Entregas:

Versões atualizadas

Logs e métricas de uso

✅ Boas práticas:

Release notes

Gestão de incidentes

Coleta contínua de sugestões
