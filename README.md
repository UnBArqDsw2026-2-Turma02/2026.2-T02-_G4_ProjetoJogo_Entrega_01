# G4 - Projeto Jogo

Documentação da primeira entrega do Grupo 4 na disciplina de **Arquitetura e Desenho de Software**, com foco em um projeto de jogo voltado à jogabilidade, usabilidade e experiência do usuário.

O projeto proposto pela equipe é uma aplicação inspirada em Tamagotchi, com estética pixel art, que combina **pet virtual**, **Pomodoro** e **tracker de hábitos**. A ideia central é relacionar as ações do usuário, como sessões de foco, ingestão de água e acompanhamento de hábitos, ao estado e à evolução de um pet virtual.

## Entrega 01

Esta entrega reúne artefatos de base para compreensão do domínio, organização das ideias iniciais e representação dos fluxos principais do sistema.

### Focos Trabalhados

| Foco | Descrição | Artefatos |
|---|---|---|
| FOCO_01 | Artefatos generalistas e NFR Framework | Mapa Mental e SIG/NFR |
| FOCO_02 | Engenharia Reversa e Modelagem BPMN | Processo de Engenharia Reversa e modelo BPMN |
| FOCO_03 | IA Generativa | Reflexões sobre uso, apoio e limitações da IA Generativa |

## SubEquipe 03

| Integrante | Matrícula | GitHub |
|---|---:|---|
| Eduardo Ribeiro Gomes da Silva | 190027011 | [@EduardoRGS](https://github.com/EduardoRGS) |
| Gabriel Pereira da Silva | 221008641 | [@bielg7](https://github.com/bielg7) |
| Guilherme Negreiros Pereira | 232014001 | [@guin409](https://github.com/guin409) |
| Weverton Rodrigues da Costa Silva | 221022767 | [@vevetin](https://github.com/vevetin) |

## Artefatos da SubEquipe 03

| Artefato | Objetivo | Link |
|---|---|---|
| Relatório da SubEquipe 03 | Consolidar metodologia, decisões, artefatos e versionamento da entrega | [Acessar relatório](docs/Base/Relatórios/1.1.3.SubEquipe_03.md) |
| Evidências da SubEquipe 03 | Registrar reuniões, atas, vídeos e comprovantes de elaboração | [Acessar evidências](docs/Base/Evidências/1.1.3.SubEquipe_03.md) |
| Participações da SubEquipe 03 | Registrar contribuições individuais da subequipe | [Acessar participações](docs/Base/Participações/1.2.3.SubEquipe_03.md) |

## Estrutura da Documentação

```text
docs/
+-- Base/
|   +-- Evidências/
|   +-- Participações/
|   +-- Relatórios/
+-- Projeto/
+-- assets/
+-- index.html
+-- README.md
+-- _sidebar.md
+-- styles.css
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
- [Relatório da SubEquipe 03](docs/Base/Relatórios/1.1.3.SubEquipe_03.md)
- [Evidências da SubEquipe 03](docs/Base/Evidências/1.1.3.SubEquipe_03.md)
- [Commits da branch docs/subequipe03](https://github.com/UnBArqDsw2026-2-Turma02/2026.2-T02-_G4_ProjetoJogo_Entrega_01/commits/docs/subequipe03/)
