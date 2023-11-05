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
 Não será obrigatorio criar uma conta apenas se achar necessario, com a criacao de conta recebera mais informações por e-mail, como jogos que serão lançados, e pré instalação

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

Um emulador para jogos de Android envolve desafios complexos, como emulação de arquitetura de ARM, GPU, suporte de APIs de Android, integração de controles e sensores. Otimização de desempenho e escalabilidade. Manter o emulador atualizado e compatível com versões recentes do Android, além de lidar com questões legais e concorrências, também são considerações cruciais.   

## Viabilidade Econômica

Emulador para jogos de depende de diversos fatora, incluindo o custos de desenvolvimentos, modelo de receita, demanda de mercado, concorrências e custos operacionais. Para avaliá-la, é crucial analisar a relação entre receitas potenciais e despesas, considerando projeções financeiras realistas e estratégias para atrair e reter usuários 


## Viabilidade Organizacional

um emulador de Android para jogos envolve a avaliação da capacidade da equipe e da estrutura organizacional para desenvolver, manter e comercializar o emulador com sucesso. Isso inclui considerações sobre a competência técnica da equipe, os recursos disponíveis, a gestão de projetos e a coordenação interna.

[ [INÍCIO](#BreakGame) ]

# Metodologia Adotada no Desenvolvimento
# METODOLOGIA ESPIRAL: 

Usamos a metodologia espiral, pois esta metodologia visa entregar melhorias, com casa progressão passando pelas mesmas fases, também se concentra em obter feedback do cliente e poder acomodar mudanças nos requisitos. Sendo uma metodologia útil para projetos maiores.   

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
|RNF-006 | cadastro | usuario casdatra uma conta se achar necessario. |



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



![image](https://github.com/lilaDP/projeto-fundamentos/assets/127409405/3e0aed42-5ca0-4c43-a3d9-0e00fffc346d)

[ [INÍCIO](#fibonacci-management-system) 
## Descrição / Especificação dos Casos de Uso
|UC-01 - Cadastrar Usuario|           
|:---|
|**Descrição/Objetivo:** Permite a inclusão de novos usuarios no Sistema|
|**Atores: Administrador**|
|**Pré-condições:** Não possui|
|**Pós-condições:** Será apresentada uma mensagem confirmando a realização do cadastro|
|**FLUXO PRINCIPAL / BÁSICO:**|
|1. O usuário seleciona a opção cadastrar|
|2. Os dados do usuario são inseridos|
|3. O usuário clica em salvar|
|4. É apresentada uma mensagem confirmando a realização do cadastro|
|**FLUXOS ALTERNATIVOS / EXCESSÕES:** |
|**A1: Campo obrigatório não preenchido** |
|1. Uma mensagem será mostrada informando para o usuario que o e-mail invalido|
|2. Uma mensagem será mostrada pedindo ao usuario para informa o e-mail novamente |


## Matriz de Rastreabilidade


| REQUISITO |UC-01|UC-02|UC-03|UC-04|UC-05|UC-06|UC-07|UC-08|UC-09| UC-10|     
|:---|:---|:---|:---|:---|:---|:---|:---|:---|:---|:---|
|RF-001|X| | | | | | | | | |
|RF-002| |X| |X| | | | | | |

[ [INÍCIO](#fibonacci-management-system) ]

# Diagrama de Classes
![image](https://github.com/lilaDP/projeto-fundamentos/assets/127409405/eb940c31-2a86-4791-95be-bf43117c26e4)


[ [INÍCIO](#fibonacci-management-system) ]

# Diagrama de Sequências

[ [INÍCIO](#fibonacci-management-system) ]

# Diagrama de Atividades

![image](https://github.com/lilaDP/projeto-fundamentos/assets/127409405/dc81744d-bd3b-49c1-a0af-b0aae0331d18)


# REFERÊNCIAS

Esta subseção apresenta as referências aos documentos que utilizamos no auxílio à construção deste documento.
* [UML](https://www.omg.org/spec/UML/2.5/About-UML/)
* [Práticas para Especificação de Requisitos IEEE-830](https://ieeexplore.ieee.org/document/720574)
