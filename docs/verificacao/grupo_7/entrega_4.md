# Verificação da entrega 4 do grupo 7

## Introdução

Este documento aborda a verificação da [Entrega 4](https://requisitos-de-software.github.io/2024.1-Meu-INSS/modelagem/Agil/backlog/), intitulada "modelagem ágil". Esta entrega inclui os artefatos de [Backlog](https://requisitos-de-software.github.io/2024.1-Meu-INSS/modelagem/Agil/backlog/), [NFR Framework](https://requisitos-de-software.github.io/2024.1-Meu-INSS/modelagem/Agil/nfr2/), [Histórias de Usuário](https://requisitos-de-software.github.io/2024.1-Meu-INSS/modelagem/Agil/historia_de_usuario/) e [Rich Picture](https://requisitos-de-software.github.io/2024.1-Meu-INSS/pre-rastreabilidade/rich_picture/), elaborados pelo [grupo 7](https://requisitos-de-software.github.io/2024.1-Meu-INSS/), que está trabalhando com o aplicativo: "Meu INSS".

## Metodologia

Para realizar a análise dos documentos, utilizarei uma adaptação do método de "Inspeção" criado por Fagan no final da década de 1970. No contexto desta disciplina, a Inspeção será composta por 3 das 6 etapas propostas por Fagan. São elas:

1. **Planejamento**: Consiste em avaliar os artefatos e planejar as atividades de inspeção.
2. **Preparação**: Após a análise e compreensão dos artefatos, será elaborada uma lista de critérios (checklist) que orientará a avaliação de cada página.
3. **Inspeção**: Esta etapa envolve verificar se os artefatos atendem aos critérios estabelecidos nas checklists.

## Objetos de verificação

Nos dias que foi realizada a inspeção, 3 e 4 de junho de 2024 , os artefatos avaliados estavam nas seguintes versões demonstradas na tabela 1:

<center>

**Tabela 1**: Objetos de verificação

|                          | Versão | Data       | Descrição                                                                  | Autor(es)     | Data de revisão | Revisor(es)   |
| ------------------------ | ------ | ---------- | -------------------------------------------------------------------------- | ------------- | --------------- | ------------- |
| **Backlog**              | 1.3    | 28/05/2024 | Arrumando Hiperlinks e ajustes na tabela de backlog.                       | Johnny Lopes  | -               | -             |
| **NFR Framework 1 e 2**  | 1.9    | 02/06/2024 | Adição dos SIGs de operacionalização, afirmação e seleção de alternativas. | Vitor Feijó   | 02/06/2024      | Bianca Castro |
| **Histórias de Usuário** | 2.2    | 30/05/2024 | Adição da validação e priorização do cliente e ajustes.                    | Bianca Castro | 30/05/2024      | Amanda Campos |
| **Rich Picture**| 1.1 | 27/03/2024 | Criação do documento | Amanda Campos, Bianca Castro e Paulo Borba | 30/03/2024 | Johnny Lopes |
**Autor**: [Guilherme Westphall](https://github.com/west7)

</center>

> Observação: Haviam dois artefatos de NFR Framework, um com os cartões e outro com os grafos, considerei o mais recente para a adição na tabela 1.

## Checklists

Nesta seção, serão apresentadas a preparação dos checklists e as respectivas inspeções, onde os critérios poderão ser avaliados como "Sim", "Não" ou "Incompleto", dos artefatos listados anteriormente nas Tabelas 2, 3, 4, 5, 6, 7, 8 e 9.

### Backlog

=== "Preparação do checklist"

    <center>

    **Tabela 2**: Preparação do checklist do backlog

    | ID  | Descrição                                                                                 |
    | --- | ----------------------------------------------------------------------------------------- |
    | 01  | O artefato contém o histórico de versão padronizado?                                      |
    | 02  | Os autores e revisores estão identificados para cada artefato?                            |
    | 03  | O artefato possui um texto de introdução?                                                 |
    | 04  | As tabelas/imagens possuem fonte/autor?                                                   |
    | 05  | O artefato possui referências/bibliografia corretamente citadas?                          |
    | 06  | O artefato contém a metodologia/método utilizado?                                         |
    | 07  | Houve participação do cliente/persona na elicitação dos requisitos?                       |
    | 08  | A separação do backlog em temas, épicos e histórias de usuário está bem definida?         |
    | 09  | No backlog, está claro se uma história de usuário está implementada ou não no aplicativo? |
    | 10  | O backlog contém a rastreabilidade dos requisitos?                                        |
    | 11  | O backlog contém hyperlinks para os requisitos elicitados?                                |
    | 12  | No backlog estão descritas as prioridades das histórias de usuário?                       |
    
    **Autor**: [Guilherme Westphall](https://github.com/west7)

    </center>

=== "Inspeção"

    <center>

    **Tabela 3**: Inspeção do backlog

    | ID  | Descrição                                                                                 | Avaliação  |
    | --- | :---------------------------------------------------------------------------------------- | ---------- |
    | 01  | O artefato contém o histórico de versão padronizado?                                      | Sim        |
    | 02  | Os autores e revisores estão identificados para cada artefato?                            | Incompleto |
    | 03  | O artefato possui um texto de introdução?                                                 | Sim        |
    | 04  | As tabelas/imagens possuem fonte/autor?                                                   | Sim        |
    | 05  | O artefato possui referências/bibliografia corretamente citadas?                          | Sim        |
    | 06  | O artefato contém a metodologia/método utilizado?                                         | Sim        |
    | 07  | Houve participação do cliente/persona na elicitação dos requisitos?                       | Incompleto |
    | 08  | A separação do backlog em temas, épicos e histórias de usuário está bem definida?         | Sim        |
    | 09  | No backlog, está claro se uma história de usuário está implementada ou não no aplicativo? | Não        |
    | 10  | O backlog contém a rastreabilidade dos requisitos?                                        | Sim        |
    | 11  | O backlog contém hyperlinks para os requisitos elicitados?                                | Sim        |
    | 12  | No backlog estão descritas as prioridades das histórias de usuário?                       | Não        |

    **Autor**: [Guilherme Westphall](https://github.com/west7)

    </center>

#### Problemas encontrados

Os principais problemas encontrados no artefato [Backlog](https://requisitos-de-software.github.io/2024.1-Meu-INSS/modelagem/Agil/backlog/), foram a ausência de uma coluna "Implementado" que indicasse se uma história de usuário já estaria ou não implementada no aplicativo, a ausência de valor na coluna de "Prioridade" e a realização de algumas técnicas de elicitação sem a participação do cliente/persona, como o brainstorm, por exemplo.

### NFR Framework

=== "Preparação do checklist"

    <center>

    **Tabela 4**: Preparação do checklist do NFR Framework.

    | ID  | Descrição                                                                                                    |
    | --- | ------------------------------------------------------------------------------------------------------------ |
    | 01  | O artefato contém o histórico de versão padronizado?                                                         |
    | 02  | Os autores e revisores estão identificados para cada artefato?                                               |
    | 03  | O artefato possui um texto de introdução?                                                                    |
    | 04  | As tabelas/imagens possuem fonte/autor?                                                                      |
    | 05  | O artefato possui referências/bibliografia corretamente citadas?                                             |
    | 06  | O artefato contém a metodologia/método utilizado?                                                            |
    | 07  | Os SIGs estão padronizados entre si?                                                                         |
    | 08  | Os softgoals são refinados até o nível de operacionalização (são testáveis)?                                 |
    | 09  | A propagação de impactos foi feita?                                                                          |
    | 10  | Os cartões de especificação contém: Descrição, justificativa, conflitos, dependências e origem do requisito? |

    **Autor**: [Guilherme Westphall](https://github.com/west7)

    </center>

=== "Inspeção"

    <center>

    **Tabela 5**: Inspeção do NFR Framework

    | ID  | Descrição                                                                                                    | Avaliação  |
    | --- | ------------------------------------------------------------------------------------------------------------ | ---------- |
    | 01  | O artefato contém o histórico de versão padronizado?                                                         | Sim        |
    | 02  | Os autores e revisores estão identificados para cada artefato?                                               | Sim        |
    | 03  | O artefato possui um texto de introdução?                                                                    | Sim        |
    | 04  | As tabelas/imagens possuem fonte/autor?                                                                      | Sim        |
    | 05  | O artefato possui referências/bibliografia corretamente citadas?                                             | Sim        |
    | 06  | O artefato contém a metodologia/método utilizado?                                                            | Sim        |
    | 07  | Os SIGs estão padronizados entre si?                                                                         | Sim        |
    | 08  | Os softgoals são refinados até o nível de operacionalização (são testáveis)?                                 | Incompleto |
    | 09  | A propagação de impactos foi feita?                                                                          | Incompleto |
    | 10  | Os cartões de especificação contém: Descrição, justificativa, conflitos, dependências e origem do requisito? | Sim        |

    **Autor**: [Guilherme Westphall](https://github.com/west7)

    </center>

#### Problemas encontrados
A separação deste artefato em dois ficou bem confusa e dificulta a visualização. Ao que parece, no presente momento (04/06/2024 às 15:33), o grupo 7 ainda não finalizou a construção do artefato [NFR Framework](https://requisitos-de-software.github.io/2024.1-Meu-INSS/modelagem/Agil/nfr/). Assim, acredito que logo essas inconsistências e os critérios de ^^ID 08 e 09^^ serão corrigidos.

### Histórias de usuário

=== "Preparação do checklist"

    <center>

    **Tabela 6**: Preparação do checklist das histórias de usuário

    | ID  | Descrição                                                                                  |
    | --- | ------------------------------------------------------------------------------------------ |
    | 01  | O artefato contém o histórico de versão padronizado?                                       |
    | 02  | Os autores e revisores estão identificados para cada artefato?                             |
    | 03  | O artefato possui um texto de introdução?                                                  |
    | 04  | As tabelas/imagens possuem fonte/autor?                                                    |
    | 05  | O artefato possui referências/bibliografia corretamente citadas?                           |
    | 06  | O artefato contém a metodologia/método utilizado?                                          |
    | 07  | As histórias de usuário estão no formato: "Eu como [quem] desejo [o que] para [por que]"?  |
    | 08  | Os títulos das histórias são auto-explicativos, ou seja, resumem a história adequadamente? |
    | 09  | As histórias possuem critérios de aceitação?                                               |
    | 10  | As histórias são testáveis?                                                                |
    | 11  | As histórias estão consistentes com o backlog?                                             |
    | 12  | Houve a participação do cliente/persona na validação das histórias?                        |

    **Autor**: [Guilherme Westphall](https://github.com/west7)

    </center>

=== "Inspeção"

    <center>

    **Tabela 7**: Inspeção das histórias de usuário

    | ID  | Descrição                                                                                 | Avaliação  |
    | --- | ----------------------------------------------------------------------------------------- | ---------- |
    | 01  | O artefato contém o histórico de versão padronizado?                                      | Sim        |
    | 02  | Os autores e revisores estão identificados para cada artefato?                            | Sim        |
    | 03  | O artefato possui um texto de introdução?                                                 | Sim        |
    | 04  | As tabelas/imagens possuem fonte/autor?                                                   | Sim        |
    | 05  | O artefato possui referências/bibliografia corretamente citadas?                          | Sim        |
    | 06  | O artefato contém a metodologia/método utilizado?                                         | Sim        |
    | 07  | As histórias de usuário estão no formato: "Eu como [quem] desejo [o que] para [por que]"? | Sim        |
    | 08  | Os títulos das histórias são autoexplicativos, ou seja, resumem a história adequadamente? | Sim        |
    | 09  | As histórias possuem critérios de aceitação?                                              | Sim        |
    | 10  | As histórias são testáveis?                                                               | Incompleto |
    | 11  | As histórias estão consistentes com o backlog?                                            | Sim        |
    | 12  | Houve a participação do cliente/persona na validação das histórias?                       | Sim        |

    **Autor**: [Guilherme Westphall](https://github.com/west7)

    </center>

#### Problemas encontrados
No geral, o artefato de [Histórias de usuário](https://requisitos-de-software.github.io/2024.1-Meu-INSS/modelagem/Agil/historia_de_usuario/) está bem satisfatório. A única inconsistência encontrada foi a falta de objetividade em algumas histórias de usuário, fazendo com que elas não pudessem ser testadas adequadamente. Cito como exemplo as histórias: ^^US28, US36 e US39^^. Nessas e em outras histórias, acredito que os critérios de aceitação poderiam estar melhor descritos, de maneira que fossem testáveis. 

### Rich Picture

=== "Preparação do checklist"

    <center>

    **Tabela 8**: Preparação do checklist do Rich Picture

    | ID  | Descrição                                                                                                        |
    | --- | ---------------------------------------------------------------------------------------------------------------- |
    | 01  | O artefato contém o histórico de versão padronizado?                                                             |
    | 02  | Os autores e revisores estão identificados para cada artefato?                                                   |
    | 03  | O artefato possui um texto de introdução?                                                                        |
    | 04  | As tabelas/imagens possuem fonte/autor?                                                                          |
    | 05  | O artefato possui referências/bibliografia corretamente citadas?                                                 |
    | 06  | O artefato contém a metodologia/método utilizado?                                                                |
    | 07  | O Rich Picture está padronizado com simbologia dos Atores, Setas, Operações, Data Stores e Fronteira do Sistema? |
    | 08  | Os Atores tem legendas explicando o que representam?                                                             |
    | 09  | Toda Operação é executada por um Ator ou outra Operação?                                                         |
    | 10  | As Data Stores tem explicitamente qual tipo de dado será salvo nelas?                                            |
    | 11  | Apenas as operações estão interagindo com os Data Stores?                                                        |
    | 12  | As Setas tem legendas com a natureza do fluxo de dados?                                                          |
    | 13 | Os Atores estão fora da Fronteira do Sistema?                                                                     |
    | 14 | O Rich Picture é de fácil compreensão e descreve o sistema superficialmente?                                      |
    | 15 | As preocupações, se presentes, estão presentes em bolhas de pensamento?                                           |
    | 16 | A linguagem do Rich Picture está de simples compreensão do leitor?                                                |
    
    **Autor**: [Davi Pierre](https://github.com/DaviPierre)

    </center>

=== "Inspeção"

    <center>

    **Tabela 9**: Inspeção das histórias de usuário

    | ID  | Descrição                                                                                                        | Avaliação |
    | --- | ---------------------------------------------------------------------------------------------------------------- | --------- |
    | 01  | O artefato contém o histórico de versão padronizado?                                                             | Sim       |
    | 02  | Os autores e revisores estão identificados para cada artefato?                                                   | Sim       |
    | 03  | O artefato possui um texto de introdução?                                                                        | Sim       |
    | 04  | As tabelas/imagens possuem fonte/autor?                                                                          | Sim       |
    | 05  | O artefato possui referências/bibliografia corretamente citadas?                                                 | Sim       |
    | 06  | O artefato contém a metodologia/método utilizado?                                                                | Sim       |
    | 07  | O Rich Picture está padronizado com simbologia dos Atores, Setas, Operações, Data Stores e Fronteira do Sistema? | Não       |
    | 08  | Os Atores tem legendas explicando o que representam?                                                             | Sim       |
    | 09  | Toda Operação é executada por um Ator ou outra Operação?                                                         | Sim       |
    | 10  | As Data Stores tem explicitamente qual tipo de dado será salvo nelas?                                            | Sim       |
    | 11  | Apenas as operações estão interagindo com os Data Stores?                                                        | Não       |
    | 12  | As Setas tem legendas com a natureza do fluxo de dados?                                                          | Sim       |
    | 13 | Os Atores estão fora da Fronteira do Sistema?                                                                     | Sim       |
    | 14 | O Rich Picture é de fácil compreensão e descreve o sistema superficialmente?                                      | Sim       |
    | 15 | As preocupações, se presentes, estão presentes em bolhas de pensamento?                                           | Sim       |
    | 16 | A linguagem do Rich Picture está de simples compreensão do leitor?                                                | Sim       |
    
    **Autor**: [Davi Pierre](https://github.com/DaviPierre)

    </center>
#### Problemas encontrados
O [Rich Picture](https://requisitos-de-software.github.io/2024.1-Meu-INSS/pre-rastreabilidade/rich_picture/) teve apenas dois problemas:
07: Os Atores do [Rich Picture](https://requisitos-de-software.github.io/2024.1-Meu-INSS/pre-rastreabilidade/rich_picture/) não seguem o padrão do método, Demonstrando os Atores com imagens coloridas o invés dos boncos de palito indicado pela técnica.
11: No [Rich Picture](https://requisitos-de-software.github.io/2024.1-Meu-INSS/pre-rastreabilidade/rich_picture/) os Atores interagem com as Data Stores, algo que só poderia acontecer por meio de uma operação.



## Referência

1. MASTER2TEACH. Fagan Inspection Methodology - Benefits of Software Inspections. Disponível em: https://www.youtube.com/watch?v=v_Lz2l_XsTQ. Acesso em: 3 jun. 2024.


## Histórico de versão

| Versão | Data       | Descição                                      | Autor                                           | Revisor                                           |
| ------ | ---------- | --------------------------------------------- | ----------------------------------------------- | ------------------------------------------------- |
| 1.0    | 03/06/2024 | Criação da página                             | [Guilherme Westphall](https://github.com/west7) | [Kallyne Macedo](https://github.com/kalipassos)   |
| 1.1    | 03/06/2024 | Adiciona verificação do Backlog               | [Guilherme Westphall](https://github.com/west7) | [Kallyne Macedo](https://github.com/kalipassos)   |
| 1.2    | 04/06/2024 | Adiciona verificação do NFR Framework         | [Guilherme Westphall](https://github.com/west7) | [Lucas Martins](https://github.com/martinsglucas) |
| 1.3    | 04/06/2024 | Adiciona verificação das Histórias de usuário | [Guilherme Westphall](https://github.com/west7) | [Lucas Martins](https://github.com/martinsglucas) |
| 1.4  | 07/06/2024 | Adiciona as tabelas 8 e 9 para a verificação do Rich Picture | [Davi Pierre](https://github.com/DaviPierre) | --- |
| 1.5  | 07/06/2024 | Adiciona a verificação do Rich Picture                       | [Davi Pierre](https://github.com/DaviPierre) | --- |