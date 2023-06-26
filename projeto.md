<img src='/img/logo.png' alt='logo da empresa' width='50px' heidth='50px'/>

# *BreakGame*

# PROJETO DE SOFTWARE

## *Stakeholders*
|NOME|CARGO|E-MAIL|
* |Dalila Elena Pelegrinello |Gerente de Projeto | dalilapelegrinello@outlook.com|
* |Emilly Lemes de Carvalho |Disgner| emilly19vha@gmail.com|

# Sumário

* [RESUMO DO PROJETO](#resumo-do-projeto)
* [INTRODUÇÃO](#introdução)
  * [PROPÓSITO DESTE DOCUMENTO](#propósito-deste-documento)
  * [ESCOPO DO PROJETO](#escopo-do-projeto)
  * [CONCEPÇÃO DO SISTEMA](#concepção-do-sistema)
  * [CONVENÇÕES, TERMOS E ABRIVEAÇÕES](#convenções-termos-e-abreviações)
* [DESCRIÇÃO GERAL](#descrição-geral)
  * [USUÁRIOS DO SISTEMA](#usuários-do-sistema)
  * [ABRANGÊNCIA E SISTEMAS SIMILARES](#abrangência-e-sistemas-similares)
  * [SUPOSIÇÕES E DEPENDÊNCIAS](#suposições-e-dependências)
* [ESTUDO DE VIABILIDADE](#estudo-de-viabilidade)
  * [VIABILIDADE TÉCNICA](#viabilidade-técnica)
  * [VIABILIDADE ECONÔMICA](#viabilidade-econômica)
  * [VIABILIDADE ORGANIZACIONAL](#viabilidade-organizacional)
* [METODOLOGIA ADOTADA NO DESENVOLVIMENTO](#metodologia-adotada-no-desenvolvimento)
* [REQUISITOS DO SOFTWARE](#requisitos-do-software)
  * [REQUISITOS FUNCIONAIS](#requisitos-funcionais)
  * [REQUISITOS NÃO FUNCIONAIS](#requisitos-não-funcionais)
* [PROTOTIPAGEM](#prototipagem)
* [DIAGRAMA DE CASOS DE USO](#diagrama-de-casos-de-uso)
  * [ESPECIFICAÇÃO DOS CASOS DE USO](#descrição--especificação-dos-casos-de-uso)
* [DIAGRAMA DE CLASSES](#diagrama-de-classes)
* [DIAGRAMA DE SEQUÊNCIAS](#diagrama-de-sequências)
* [ DIAGRAMA DE ATIVIDADES](#diagrama-de-atividades)
* [REFERÊNCIAS](#referências)


# RESUMO DO PROJETO
| ITEM | DESCRIÇÃO|
|:---|:---|
| NOME DO PROJETO | BreakGame |
| GERENTE DO PROJETO | Dalila Pelegrinello |
| PRINCIPAL OBJETIVO | Emular jogos de diferentes plataformas em computadores. |
| BENEFÍCIOS ESPERADOS |* Configuração pernalizavel;<br/>* Facilidade de uso;<br/>* 
| INÍCIO E TÉRMINO PREVISTOS | 14/03/2023 - 07/12/2023 |

[ [INÍCIO](#BreakGame) ]

# INTRODUÇÃO

## PROPÓSITO DESTE DOCUMENTO

Este documento destina-se aos clientes, engenheiros, gerentes e demais stakeholders deste projeto. O propósito deste documento é apresentar a descrição dos serviços e funções que o sistema **_BreakGame** deve prover, bem como as suas restrições de operação e propriedades gerais, a fim de ilustrar uma descrição detalhada do sistema para um auxílio durante as etapas de análise, projeto e testes. O documento especifica todos os requisitos funcionais e não funcionais do sistema e contém a prototipagem, além de diagramas UML que foram construídos levando-se em conta as funcionalidades identificadas durante a fase de concepção do sistema.

## CONCEPÇÃO DO SISTEMA

Foram usados três tipos de métodos para que pudessem ser obtidos os requisitos do sistema

°Entrevista:
. Foram feitas entrevistas com clientes, e possiveis usuários para entender o que necessário para um bom sistema.

°Consulta com especialistas:
Wagner da Silva, professor de Fundamentos em Análise de Sistemas no Instituto Federal orientou na concepção do sistema devido sua experiência em trabalhar em sistemas e ser um dos consultores da empresa;

° Prtotipação:
Apresentações de interfaces graficas feitas apartir do figma.

## CONVENÇÕES, TERMOS E ABREVIAÇÕES

Para evitar interpretações incorretas deste documento, algumas convenções e termos específicos são descritos a seguir:

* Emulador: sistema de computação equipado para emular outro sistema.


[ [INÍCIO](#BreakGame) ]

# DESCRIÇÃO GERAL

## ESCOPO DO PROJETO

### NO ESCOPO

BreakGame é um emulador de jogos que visa possuir uma coletâenas de jogos de difenrentes sistemas em apenas um sistema, tendo jogos de sistemas Android e Ios, tendo uma melhor experiencia para jogar, com configurções manipulaveis pelas usuarios, deixando assim a experiencia melhorada, havendo tipos de cofigurações diferentes para cada tipo de jogo. Atualizações facil de se manterem, não sendo necessario muito conhecimento para se conseguir usar e deixar atualizado.

### FORA DO ESCOPO

Não fazem parte do escopo do projeto:
* Modificações de jogos
* Mods para jogos 
* jogos com algum tipo de burlagem

## Usuários do sistema
|USUÁRIO|DESCRIÇÃO|
 Não será necessario se criar ou gerar uma conta, apenas baixar e usar.

## Abrangência e sistemas similares

### Abrangência:

O sistema sera uma plataforma onde apresentara jogos que diferentes plataformas se podendo escolher entre elas. A jogabilidade dos jogos não sera mexida dentro mas haverá configurações para auxiliar em uma melhor experiencia. 

Das ferramentas de planejamento podemos citar:
Diferente tipos de Configurações 

* **Configuraçao de controles:** Sera possivel personalizar controle da forma desejavel;
* 
* **Cadastrar Controle:** Sera possivel cadastrar um controle de console;
* 
* **Configuraçoes do jogos:** Podera ser comnfigurado o jogo para melhor experiencia;

### Sistemas similares:

NO cenario atual de plataforma de emuladores. existe inumetos sites que apresentam mesma proposta, entretanto, não há muitos com a proposta de criar sua porpria configuração.

No cenario de emuladores emcontranse alguns que se destacam.

* **BlueStacks:** uma plataforma na qual emula tantos jogos como aplicativos de Android e Ios.
  
* **NoxPlayer:** uma paltaforma na qual emula e Otimiza jogos, compatibilidade com controle, capacidade de alterar o build. 

## Suposições e dependências
O sistema necessita de um servidor web para sua hospedagem.

Os usuários devem utilizar um computador com a seguinte configuração mínima:

*  Windows 7 e superior;
*  4 GB de RAM (8GB recomendado);
* 5Gb de armazenamento
* Você deve ser um administrador em seu PC..

# ESTUDO DE VIABILIDADE

Uma vez definidos a necessidade para o sistema e seus requisitos de negócio, é possível compreender melhor o projeto do sistema proposto para elaborar o estudo de viabilidade com os seguintes destaques:

## Viabilidade Técnica
Os colaboradores da empresa contratante possuem bastante experiência com aplicações desta natureza, os analistas também estão familiarizados com esta área de aplicação comercial, porém o sistema utiliza uma tecnologia nova, com a qual os analistas e programadores não estão familiarizados. No que se refere ao tamanho do sistema, trata-se de um projeto de médio porte, com baixo nível de complexidade, que não será integrado a outros sistemas, limitando-se a atender a demanda da escola no que se refere à EaD, que, atualmente possui 1.000 alunos matriculados. Conclui-se que o projeto possui viabilidade técnica, em virtude dos baixos riscos identificados.

## Viabilidade Econômica

Foi realizada uma análise de custo-benefício, e, mesmo com estimativas conservadoras do retorno sobre o investimento e dos benefícios totais, este projeto é viável economicamente. Após a implantação, espera-se uma melhoria na qualidade dos serviços prestados e aumento da capacidade de vagas da unidade escolar.

## Viabilidade Organizacional

Do ponto de vista organizacional, este projeto apresenta baixo risco. Os diretores e coordenadores da instituição demonstram forte interesse no projeto. Espera-se que os professores e alunos aprovem a implantação do sistema, visto que atualmente a escola não possui uma ferramenta específica para o controle das informações, o que está provocando enormes transtornos para a instituição.


[ [INÍCIO](#BreakGame) ]

# Metodologia Adotada no Desenvolvimento


[ [INÍCIO](#BreakGame) ]

# Requisitos do Software

A especificação dos requisitos deste documento deve seguir as recomendações da norma IEEE Std-830-1998, levando em conta as recomentações do documento de [características dos requisitos](caracteristicas_requisitos.md).

## Requisitos Funcionais

A tabela a seguir contém a relação dos Requisitos Funcionais elicitados, com as colunas: identificador, nome, descrição e prioridade:

| IDENTIFICADOR | NOME | DESCRIÇÃO |
:---|:---|:---|
|RNF-001 |Disponibilidade |O sistema estara sempre disponivel quando for necessario|
|RNF-002 |Manutenção |O sistema não havera muitas complicações para se atualizar|
|RNF-003 | Usabilidade | O sistema sera facil de se usar e manter |
|RNF-004 | Atuação |O sistema sera capaz de lidar com o número necessário de usuários sem qualquer degradação no desempenho.|
|RNF-005 | Segurança |O sistema sera protegido contra acesso não autorizado. |

## Requisitos Não Funcionais
A tabela a seguir contém a relação com os Requisitos Não Funcionais identificados, contendo identificador, nome, descrição e prioridade:

| IDENTIFICADOR | NOME | DESCRIÇÃO |
|:---|:---|:---|
|RNF-001 |Mostrar Infomações | O Sistema mostrara as informações necessarias para seu uso|
|RNF-002 |Notas de Atualização |Apos atualizar, havera um pequeno texto infromando sobre tal atualição|
|RNF-003 | Configurações | O sisterma tera configuraçoes que poderam interagir|
|RNF-004 | Personalização| O sistema tera personalização de controles|
|RNF-005 | Guia de soluções | Se houver algum problema que podera ser solucionado pelo usuario o guia irá mostrar. |


[ [INÍCIO](#BreakGame) ]


# Prototipagem

[Protótipo criado no FIGMA em 2022 por estudantes](https://www.figma.com/file/6wzQARlwJn5j9aGFqWCGwk/Untitled?type=design&node-id=0-1&t=Em1dX71dEVCvL3ab-0)

* ![image](https://github.com/lilaDP/projeto-fundamentos/assets/127409405/92bcf24b-d5e2-4df2-af34-2cae3920c3b4)

* ![image](https://github.com/lilaDP/projeto-fundamentos/assets/127409405/efc5dd6d-bac7-4458-a420-04637cb5dbce)

* ![image](https://github.com/lilaDP/projeto-fundamentos/assets/127409405/754e63b6-0ac2-4dfe-a5b1-eecb0855bbb7)




[ [INÍCIO](#fibonacci-management-system) 
## Descrição / Especificação dos Casos de Uso

### UC-01 - Cadastrar Professor

|UC-01 - Cadastrar Professor|           
|:---|
|**Descrição/Objetivo:** Permite a inclusão de novos professores no Sistema|
|**Atores: Administrador**|
|**Pré-condições:** O usuário precisa estar cadastrado e logado|
|**Pós-condições:** Será apresentada uma mensagem confirmando a realização do cadastro|
|**FLUXO PRINCIPAL / BÁSICO:**|
|1. O usuário seleciona a opção cadastrar professor|
|2. Os dados do professor são inseridos|
|3. O usuário clica em salvar|
|4. Um novo ID é gerado |
|5. É apresentada uma mensagem confirmando a realização do cadastro|
|**FLUXOS ALTERNATIVOS / EXCESSÕES:** |
|**A1: Campo obrigatório não preenchido** |
|1. Uma mensagem será apresentada para o usuário, informando que existe(m) campos obrigatórios que não foram preenchidos |
|2. O cursor será posicionado no primeiro campo obrigatório que não foi preenchido |
|**A2: Data de nascimento inválida** |
|1. Uma mensagem será apresentada para o usuário, informando que a data informáda não é válida|
|2. O cursor será posicionado para o campo data|


## Matriz de Rastreabilidade


| REQUISITO |UC-01|UC-02|UC-03|UC-04|UC-05|UC-06|UC-07|UC-08|UC-09| UC-10|     
|:---|:---|:---|:---|:---|:---|:---|:---|:---|:---|:---|
|RF-001|X| | | | | | | | | |
|RF-002| |X| |X| | | | | | |

[ [INÍCIO](#fibonacci-management-system) ]

# Diagrama de Classes

[ [INÍCIO](#fibonacci-management-system) ]

# Diagrama de Sequências

[ [INÍCIO](#fibonacci-management-system) ]

# Diagrama de Atividades


# REFERÊNCIAS

Esta subseção apresenta as referências aos documentos que utilizamos no auxílio à construção deste documento.
* [UML](https://www.omg.org/spec/UML/2.5/About-UML/)
* [Práticas para Especificação de Requisitos IEEE-830](https://ieeexplore.ieee.org/document/720574)
