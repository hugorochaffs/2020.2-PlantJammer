# <center> Verificação do Documento de Casos de Uso

### Histórico de Versão
|    Data    | Versão | Descrição            | Autor(es)       |
| :--------: | :----: | :------------------: | :-------------: |
| 28/03/2021 |  0.1   | Criação do documento | Victor Jorge  |
| 28/03/2021 |  0.2   | Revisão do documento | João Victor  |

<div align="justify">

## 1. Introdução

Os casos de uso são documentos escritos com a intenção de descrever como os usuários irão executar determinadas tarefas no sistema. Cada caso de uso é representado como uma sequência de passos simples que começam a partir dos objetivos do usuário e terminam no momento em que estes objetivos são atingidos (Usability.gov).

Segundo o texto sobre casos de uso do site [Usability](https://www.usability.gov/how-to-and-tools/methods/use-cases.html), existem itens que devem ser respeitados na elaboração do documento de casos de uso. Apesar do explícito foco em _websites_, extrapolaremos as noções fornecidas pelo texto e avaliaremos o documento de casos de uso relacionado ao aplicativo Plant Jammer. Esta avaliação, em especicífico, se baseará na seguinte tabela:

| O que os casos de uso devem incluir | O que casos de uso NÃO devem incluir                    |
| :---------------------------------: | :-----------------------------------------------------: |
| Quem está usando o _sistema_        | Aspectos específicos da linguagem de implementação      |
| O que o usuário deseja fazer        | Detalhes sobre a interface do usuário ou sobre as telas |
| Os objetivos do usuário             |                                                         |
| Os passsos envolvidos na realização de uma tarefa do usuário | |
| Como o _sistema_ deve responder à uma determinada ação | |

## 2. Metodologia

A avaliação consistirá na verificação de cada item da tabela aplicável ao contexto do diagrama.

## 3. Resultados

Nota-se a falta da especificação dos casos de uso junto do diagrama de caso de uso. Portanto, alguns itens da tabela de avaliação foram omitidos por se referirem a detalhes que são fornecidos apenas na especificação dos casos de uso. Por decisão do avaliador, o diagrama será avaliado em sua totalidade, englobando todas as tarefas em um único _check-list_ a fim de tornar os resultados da avaliação legíveis e compreensíveis. Tal decisão se baseia na percepção de que todas as tarefas cumprem igualmente os mesmos itens.

| Item | Cumprido | Justificativa |
| :--: | :------: | :-----------: |
| Exibe quem está usando o _sistema_ | Sim | Todas as tarefas partem de um usuário específico no diagrama |
| Exibe os passsos envolvidos na realização de uma tarefa do usuário | **Não** | Todas as tarefas são descritas em apenas um único passo de alto nível, desconsiderando os relacionamentos de extensão |
| NÃO exibe aspectos da linguagem de implementação | Sim | As tarefas são descritas em alto nível sem qualquer detalhe de implementação |
| NÃO fornece detalhes sobre a interface do usuário ou sobre as telas | Sim | O diagrama forncece apenas a sequência lógica das tarefas
| Especifica os casos de uso | **Não** | Existe a nessidade de se especificar em texto cada caso de uso, descrevendo quem são os atores, fluxos e condições |

## Referências

USE CASES. Em: USABILITY. Disponível em: <https://www.usability.gov/how-to-and-tools/methods/use-cases.html>. Acesso em 28 Mar. 2021.

SERRANO, Maurício; SERRANO, Milene. Requisitos - Slides Aula 013. 2º/2020. Material apresentado para a disciplina de Requisitos de Software no curso de Engenharia de Software da UnB, FGA.


</div>