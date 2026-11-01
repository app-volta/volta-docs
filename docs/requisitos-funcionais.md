# VOLTA — Levantamento de Requisitos

## 1. Objetivo

Este documento apresenta os requisitos do sistema VOLTA e os relaciona aos casos de uso do [diagrama de casos de uso](eqs/png/Diagramas-volta-diagrama-casos-uso.drawio.png). A lista segue o Jira do projeto (épico **LDRE-6 — Levantamento de Requisitos**), de onde vêm os identificadores e as chaves das tarefas.

Jira: https://carlosvolta.atlassian.net/jira

## 2. Resumo

| Tipo | Quantidade | Identificadores |
|---|---|---|
| Requisitos funcionais (RF) | 21 | RF01 a RF21 |
| Requisitos não funcionais (RNF) | 14 | RNF01 a RNF14 |
| **Total** | **35** | |

## 3. Requisitos funcionais

| ID | Chave no Jira | Requisito | Caso de uso |
|---|---|---|---|
| RF01 | LDRE-7 | Cadastro de usuário | UC01 — Cadastrar usuário |
| RF02 | LDRE-8 | Autenticação de usuário | UC02 — Autenticar usuário |
| RF03 | LDRE-9 | Registro de ocorrência | UC05 — Registrar ocorrência; UC06 — Anexar fotografia |
| RF04 | LDRE-10 | Análise da fotografia | UC07 — Analisar fotografia |
| RF05 | LDRE-11 | Análise da ocorrência | UC08 — Analisar ocorrência |
| RF06 | LDRE-12 | Permitir alteração da sugestão | UC09 — Alterar sugestão da IA |
| RF07 | LDRE-13 | Validar análise da IA | UC10 — Validar análise da IA |
| RF08 | LDRE-14 | Criar chamado | UC11 — Criar chamado |
| RF09 | LDRE-15 | Acompanhar chamado | UC12 — Acompanhar chamado |
| RF10 | LDRE-16 | Atribuição de status no chamado | UC13 — Atribuir status |
| RF11 | LDRE-17 | Consultar chamados | UC14 — Consultar chamados |
| RF12 | LDRE-18 | Recomendar cooperativas | UC16 — Recomendar cooperativas |
| RF13 | LDRE-19 | Avaliar compatibilidade | UC17 — Avaliar compatibilidade |
| RF14 | LDRE-20 | Consultar tipos de materiais | UC18 — Consultar tipos de materiais |
| RF15 | LDRE-21 | Consultar cooperativas | UC20 — Consultar cooperativas |
| RF16 | LDRE-22 | Avaliar capacidade operacional | UC19 — Avaliar capacidade operacional |
| RF17 | LDRE-23 | Encerrar chamado | UC15 — Encerrar chamado |
| RF18 | LDRE-24 | Cadastro de empresas | UC21 — Cadastrar empresa |
| RF19 | LDRE-25 | Cadastro de cooperativas | UC22 — Cadastrar cooperativa |
| RF20 | LDRE-26 | Informar disponibilidade da cooperativa | UC25 — Informar disponibilidade |
| RF21 | LDRE-27 | Gerar indicadores | UC27 — Gerar indicadores |

## 4. Requisitos não funcionais

| ID | Chave no Jira | Requisito | Caso de uso relacionado |
|---|---|---|---|
| RNF01 | LDRE-28 | Gerenciar perfil | UC03 — Gerenciar perfil |
| RNF02 | LDRE-29 | Gerenciamento de permissões | Todos (controle de acesso por perfil) |
| RNF03 | LDRE-30 | Recuperação de conta | UC04 — Recuperar conta |
| RNF04 | LDRE-31 | Identificar responsáveis pela abertura | UC05 — Registrar ocorrência |
| RNF05 | LDRE-32 | Implementar validação de campos | Todos os casos de uso com formulário |
| RNF06 | LDRE-33 | Filtragem de chamados | UC14 — Consultar chamados |
| RNF07 | LDRE-34 | Registrar histórico | UC13 — Atribuir status; UC12 — Acompanhar chamado |
| RNF08 | LDRE-35 | Visualizar informações da recomendação | UC16 — Recomendar cooperativas |
| RNF09 | LDRE-36 | Gerenciar informações da empresa | UC23 — Gerenciar empresa |
| RNF10 | LDRE-37 | Gerenciar informações da cooperativa | UC24 — Gerenciar cooperativa |
| RNF11 | LDRE-38 | Visualizar dashboard | UC28 — Visualizar dashboard |
| RNF12 | LDRE-39 | Filtrar dados de indicadores | UC28 — Visualizar dashboard |
| RNF13 | LDRE-40 | Geração de relatórios | UC29 — Gerar relatório |
| RNF14 | LDRE-41 | Notificar usuários envolvidos | UC11 — Criar chamado; UC13 — Atribuir status |

## 5. Rastreabilidade: casos de uso e requisitos

| Caso de uso | Requisito |
|---|---|
| UC01 — Cadastrar usuário | RF01 |
| UC02 — Autenticar usuário | RF02 |
| UC03 — Gerenciar perfil | RNF01 |
| UC04 — Recuperar conta | RNF03 |
| UC05 — Registrar ocorrência | RF03, RNF04 |
| UC06 — Anexar fotografia | RF03 |
| UC07 — Analisar fotografia | RF04 |
| UC08 — Analisar ocorrência | RF05 |
| UC09 — Alterar sugestão da IA | RF06 |
| UC10 — Validar análise da IA | RF07 |
| UC11 — Criar chamado | RF08, RNF14 |
| UC12 — Acompanhar chamado | RF09, RNF07 |
| UC13 — Atribuir status | RF10, RNF07, RNF14 |
| UC14 — Consultar chamados | RF11, RNF06 |
| UC15 — Encerrar chamado | RF17 |
| UC16 — Recomendar cooperativas | RF12, RNF08 |
| UC17 — Avaliar compatibilidade | RF13 |
| UC18 — Consultar tipos de materiais | RF14 |
| UC19 — Avaliar capacidade operacional | RF16 |
| UC20 — Consultar cooperativas | RF15 |
| UC21 — Cadastrar empresa | RF18 |
| UC22 — Cadastrar cooperativa | RF19 |
| UC23 — Gerenciar empresa | RNF09 |
| UC24 — Gerenciar cooperativa | RNF10 |
| UC25 — Informar disponibilidade | RF20 |
| UC26 — Consultar solicitações | Sem requisito correspondente |
| UC27 — Gerar indicadores | RF21 |
| UC28 — Visualizar dashboard | RNF11, RNF12 |
| UC29 — Gerar relatório | RNF13 |