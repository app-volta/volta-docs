# VOLTA — Documentação do Projeto

Repositório destinado à documentação técnica e organizacional do projeto **VOLTA**, reunindo informações sobre a arquitetura, as tecnologias utilizadas, a organização da equipe, os requisitos e as evidências de desenvolvimento.

## Objetivo

Centralizar a documentação do projeto para facilitar a consulta pelos integrantes da equipe, apoiar a validação das funcionalidades e registrar as decisões e atividades realizadas durante o desenvolvimento.

## Entregas do projeto

| Item | Entrega | Referência |
| ---- | ------- | ---------- |
| M1 | Acompanhamento e planejamento do projeto | [Jira](https://carlosvolta.atlassian.net/jira) |
| M2 | Requisitos funcionais do sistema | [requisitos-funcionais.md](docs/requisitos-funcionais.md) |
| M3 | Diagrama de casos de uso | [Imagem](docs/diagramas/png/Diagramas-volta-diagrama-casos-uso.drawio.png) · [Arquivo draw.io](docs/diagramas/uml/Diagramas-volta.drawio) · [Rastreabilidade com os requisitos](docs/requisitos-funcionais.md#5-rastreabilidade-casos-de-uso-e-requisitos) |
| M4 | Diagramas de atividades (registro de ocorrência e gestão de chamado) | [Registro de ocorrência](docs/diagramas/png/Diagramas-volta-registro-de-ocorrencia.drawio.png) · [Gestão de chamado](docs/diagramas/png/Diagramas-volta-gestao-de-chamado.drawio.png) · [Arquivo draw.io](docs/diagramas/uml/Diagramas-volta.drawio) |
| M5 | Dinâmica de trabalho e responsáveis da equipe | [dinamica-trabalho-equipe.md](docs/dinamica-trabalho-equipe.md) |
| E1 | Padrões de projeto | [padrao-de-projeto.md](docs/padrao-de-projeto.md) |
| E2 | Padrões de teste | [padroes-de-teste.md](docs/padroes-de-teste.md) · [Evidências de execução](docs/padroes-de-teste.md#10-evidências-de-execução) · [Prints](docs/prints/) |

## Outros documentos

| Documento | Referência |
| --------- | ---------- |
| Bancos de dados | [banco-de-dados.md](docs/banco-de-dados.md) |

## Organização e acompanhamento

A equipe utiliza o Jira para acompanhar as tarefas e atualizar seu andamento conforme as atividades são realizadas. O GitHub é utilizado para versionamento e colaboração por meio de repositórios e Pull Requests.

A comunicação ocorre principalmente pelo WhatsApp e também por reuniões presenciais.

O desenvolvimento é organizado em sprints, com planejamento das entregas e uma etapa final dedicada a testes, correções e revisão.

## Tecnologias e armazenamento de dados

O projeto utiliza diferentes tecnologias de armazenamento, de acordo com as necessidades de cada componente:

- **PostgreSQL:** armazenamento de dados relacionais.
- **MongoDB:** armazenamento de dados conversacionais utilizados pelo chatbot.
- **Redis:** componente utilizado pela API relacionada ao Redis.
- **Neo4j:** banco de dados em grafo utilizado em uma demonstração local de modelagem e consultas de relacionamentos.

As integrações e funcionalidades devem ser documentadas conforme sua implementação e validação efetivas.

## Evidências e validação

Quando aplicável, a documentação deve incluir evidências que demonstrem o funcionamento das funcionalidades descritas, como:

- Conexões estabelecidas com os bancos de dados.
- Registros persistidos e correspondência com os dados apresentados pela aplicação.
- Resultados de consultas e testes.
- Funcionamento das APIs e de suas integrações.
- Capturas de tela e resultados que apoiem a validação dos requisitos.

As evidências devem corresponder aos testes realmente realizados, distinguindo demonstrações locais das funcionalidades integradas ao sistema.

## Status do projeto

O projeto encontra-se em fase de conclusão e organização das entregas, com atividades de documentação, integração, testes e revisão previstas antes da entrega oficial.

## Equipe

A equipe é organizada por áreas de responsabilidade, com colaboração entre os integrantes conforme as necessidades do projeto. A distribuição inicial e as adaptações realizadas durante o desenvolvimento são detalhadas no documento de dinâmica de trabalho.

---

**VOLTA — Documentação técnica e organizacional do projeto.**
