# G4 - Projeto Jogo

Documentação da primeira entrega do Grupo 4 na disciplina de **Arquitetura e Desenho de Software**, com foco em um projeto de jogo voltado à jogabilidade, usabilidade e experiência do usuário.

O projeto proposto pela equipe é uma aplicação inspirada em Tamagotchi, com estética pixel art, que combina **pet virtual**, **Pomodoro** e **tracker de hábitos**. A ideia central é relacionar as ações do usuário, como sessões de foco, ingestão de água e acompanhamento de hábitos, ao estado e à evolução de um pet virtual.

## Entrega 01

Esta entrega reúne artefatos de base para compreensão do domínio, organização das ideias iniciais e representação dos fluxos principais do sistema.

### Focos Trabalhados

| Foco | Descrição | Artefatos |
|---|---|---|
| FOCO_01 | Artefatos generalistas e NFR Framework | Mapa Mental ou Rich Picture e SIG/NFR |
| FOCO_02 | Engenharia Reversa e Modelagem BPMN | Processo de Engenharia Reversa e modelo BPMN |
| FOCO_03 | IA Generativa | Reflexões sobre uso, apoio e limitações da IA Generativa |

## Subgrupos

A equipe está organizada em três subgrupos. Cada subgrupo possui um relatório próprio, com metodologia, participantes, artefatos, decisões, versionamentos e reflexões sobre o uso de IA Generativa.

| Subgrupo | Relatório | Escopo |
|---|---|---|
| SubEquipe 01 | [Acessar relatório](docs/Base/Relatórios/1.1.1.SubEquipe_01.md) | Artefatos generalistas, NFR Framework, Engenharia Reversa, BPMN e IA Generativa |
| SubEquipe 02 | [Acessar relatório](docs/Base/Relatórios/1.1.2.SubEquipe_02.md) | Artefatos generalistas, NFR Framework, Engenharia Reversa, BPMN e IA Generativa |
| SubEquipe 03 | [Acessar relatório](docs/Base/Relatórios/1.1.3.SubEquipe_03.md) | Artefatos generalistas, NFR Framework, Engenharia Reversa, BPMN e IA Generativa |

## Integrantes Documentados

### SubEquipe 01

| Integrante | Matrícula | GitHub |
|---|---:|---|
| Arthur Mendes Borges | 241010914 | [@artmendess](https://github.com/artmendess) |
| João Vitor Mendonça Merlin | 222006848 | [@jvopBR](https://github.com/jvopBR) |
| Danilo Sarmento Barros | 222008468 | [@auslogyc](https://github.com/auslogyc) |

### SubEquipe 02

| Integrante | Matrícula | GitHub |
|---|---:|---|
| Ana Luiza Borba de Abrantes | 200014226 | [@luabrantess](https://github.com/luabrantess) |
| Enzo Lopes Ferreira | 232002000 | [@lopes061](https://github.com/lopes061) |
| Pablo Cunha de Jesus | 222014910 | [@Pabloo8](https://github.com/Pabloo8) |

### SubEquipe 03

| Integrante | Matrícula | GitHub |
|---|---:|---|
| Eduardo Ribeiro Gomes da Silva | 190027011 | [@EduardoRGS](https://github.com/EduardoRGS) |
| Gabriel Pereira da Silva | 221008641 | [@bielg7](https://github.com/bielg7) |
| Guilherme Negreiros Pereira | 232014001 | [@guin409](https://github.com/guin409) |
| Weverton Rodrigues da Costa Silva | 221022767 | [@vevetin](https://github.com/vevetin) |

## Artefatos por Subgrupo

| Subgrupo | Artefato | Objetivo | Link |
|---|---|---|---|
| SubEquipe 01 | Relatório da SubEquipe 01 | Consolidar metodologia, decisões, artefatos e versionamento da entrega | [Acessar relatório](docs/Base/Relatórios/1.1.1.SubEquipe_01.md) |
| SubEquipe 02 | Relatório da SubEquipe 02 | Consolidar metodologia, decisões, artefatos e versionamento da entrega | [Acessar relatório](docs/Base/Relatórios/1.1.2.SubEquipe_02.md) |
| SubEquipe 03 | Relatório da SubEquipe 03 | Consolidar metodologia, decisões, artefatos e versionamento da entrega | [Acessar relatório](docs/Base/Relatórios/1.1.3.SubEquipe_03.md) |
| Todas | Participações da entrega | Registrar contribuições individuais e comprobatórios de participação | [Acessar participações](docs/Base/1.2.ParticipacoesBase.md) |
| Todas | Iniciativas extras | Registrar entregas, materiais ou evidências adicionais produzidas pela equipe | [Acessar iniciativas extras](docs/Base/1.3.IniciativasExtras.md) |

## Estrutura da Documentação

```text
docs/
+-- Base/
|   +-- Relatórios/
|   |   +-- 1.1.1.SubEquipe_01.md
|   |   +-- 1.1.2.SubEquipe_02.md
|   |   +-- 1.1.3.SubEquipe_03.md
|   +-- 1.Base.md
|   +-- 1.2.ParticipacoesBase.md
|   +-- 1.3.IniciativasExtras.md
+-- Projeto/
|   +-- Projeto.md
+-- index.html
+-- README.md
+-- _sidebar.md
```

## Como Executar Localmente

A documentação utiliza [Docsify](https://docsify.js.org/) para renderizar as páginas Markdown.

Instale o Docsify CLI:

```shell
npm i docsify-cli -g
```

Execute o site localmente:

```shell
docsify serve ./docs
```

Também é possível servir a pasta `docs` com Python:

```shell
python -m http.server 3000 -d docs
```

Depois, acesse:

```text
http://localhost:3000
```

## Links Úteis

- [Página inicial da documentação](docs/README.md)
- [Projeto e temas do período](docs/Projeto/Projeto.md)
- [Desenho de Software - Base](docs/Base/1.Base.md)
- [Relatório da SubEquipe 01](docs/Base/Relatórios/1.1.1.SubEquipe_01.md)
- [Relatório da SubEquipe 02](docs/Base/Relatórios/1.1.2.SubEquipe_02.md)
- [Relatório da SubEquipe 03](docs/Base/Relatórios/1.1.3.SubEquipe_03.md)
- [Participações da entrega](docs/Base/1.2.ParticipacoesBase.md)
- [Iniciativas extras](docs/Base/1.3.IniciativasExtras.md)
- [Commits da branch docs/subequipe03](https://github.com/UnBArqDsw2026-2-Turma02/2026.2-T02-_G4_ProjetoJogo_Entrega_01/commits/docs/subequipe03/)
