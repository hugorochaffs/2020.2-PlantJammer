# <center> Técnica de Introspecção

### Histórico de Versão
|    Data    | Versão | Descrição            | Autor(es)       |
| :--------: | :----: | :------------------: | :-------------: |
| 26/03/2021 |  0.1   | Criação do documento | Durval Carvalho |

<div align="justify">

## 1. Introdução

O _NFR Framework_ é um modelo criado para ajudar a modelar requisitos não-funcionais, através de um grafo chamado de _Softgoal Interdependency Graphs_ (SIGs). Neste grafo, os requisitos podem ser analisados detalhadamente, uma vez que o SIG permite uma visão vertical das estratégias de alto nível e também dos detalhes operacionais. Esse detalhamento é viabilizado pelas decomposições das visões de alto nível, por meio de operadores lógicos (AND e OR) que possibilita a granularização até o nível operacional. (CHUNG et al., 2012).

O _NFR Framework_ utiliza o conceito de metas flexíveis. A noção no SIG para uma meta flexível é um símbolo similar ao de uma nuvem. Esse símbolo possui pequenas variações na forma, podendo representar uma operacionalização (nuvem em negrito), e também uma alegação (nuvem tracejada). (SILVA, 2019).

<p align='center'>
    <img src='assets/images/nuvens-nfr.png'>
    <figcaption align='center'>
        <b>Figura 1: Representações gráficas de Metas Flexível, Operacionalização e Alegação</b>
        <br>
        <small>Fonte: SILVA, 2019</small>
    </figcaption>
</p>

Para facilitar o entendimento das decisões tomadas, a meta flexível possui _labels_. Estas labels possibilitam compreender o grau de prioridade e de completude de uma meta flexível. Possíveis representações gráficas das labels de completude podem ser vista na figura 2.

<p align='center'>
    <img src='assets/images/completude-labels.png'>
    <figcaption align='center'>
        <b>Figura 2: Representação gráfica das labels em metas flexíveis</b>
        <br>
        <small>Fonte: SILVA, 2019</small>
    </figcaption>
</p>

Já as labels de prioridade são representadas por sinais de interrogação, sendo:
- “!”: Priorização Média.
- “!!”: Priorização Alta.

<p align='center'>
    <img src='assets/images/priorizacao-labels.png'>
    <figcaption align='center'>
        <b>Figura 2: Representação gráfica para o grau de prioridade da meta flexível</b>
        <br>
        <small>Fonte: SILVA, 2019</small>
    </figcaption>
</p>

Uma vez que as metas flexíveis são decompostas em sub metas flexíveis, é preciso indicar as relações entre as metas geradas. Essas relações são estabelecidas através de links de interdependência. Dessa forma, a completude de sub metas contribui para a satisfação de metas mais genéricas.

Como um meta flexível pode ser decomposta em várias sub metas flexíveis, é preciso definir qual o grau de contribuição de cada submeta. Dessa forma, existe uma notação simbólica para cada tipo de contribuição. Estes tipos de contribuição podem ser visualizados na Tabela 1.

<p align='center'>
    <img src='assets/images/nfr-tipos-de-contribuicoes.png'>
    <figcaption align='center'>
        <b>Tabela 1: Tipos de contribuições</b>
        <br>
        <small>Fonte: SILVA, 2019</small>
    </figcaption>
</p>

## 2. Objetivo

O objetivo desse documento é apresentar os SIGs construídos com o objetivo de modelar e dar mais visibilidade aos requisitos não funcionais do projeto.

## 3. Resultados

<p align='center'>
    <img src='assets/images/nfr-diagram-manutenibilidade.png'>
    <figcaption align='center'>
        <b>Figura 1: NFR de manutenibilidade</b>
        <br>
        <small>Fonte: Autor</small>
    </figcaption>
</p>

<br><br>

<p align='center'>
    <img src='assets/images/nfr-diagram-portabilidade.png'>
    <figcaption align='center'>
        <b>Figura 2: NFR de Portabilidade</b>
        <br>
        <small>Fonte: Autor</small>
    </figcaption>
</p>

<br><br>

<p align='center'>
    <img src='assets/images/nfr-diagram-confiabilidade.png'>
    <figcaption align='center'>
        <b>Figura 3: NFR de Confiabilidade</b>
        <br>
        <small>Fonte: Autor</small>
    </figcaption>
</p>

<br><br>

<p align='center'>
    <img src='assets/images/nfr-diagram-usabilidade.png'>
    <figcaption align='center'>
        <b>Figura 4: NFR de Usabilidade</b>
        <br>
        <small>Fonte: Autor</small>
    </figcaption>
</p>

<br><br>

<p align='center'>
    <img src='assets/images/nfr-diagram-desempenho.png'>
    <figcaption align='center'>
        <b>Figura 5: NFR de Desempenho</b>
        <br>
        <small>Fonte: Autor</small>
    </figcaption>
</p>

<br><br>

## 4. Conclusão

Após a utilização do NFR Framework a equipe analista de requisitos foi capaz de identificar diversas maneiras de implementar e priorizar os requisitos não funcionais do projeto.

## Bibliografia

1. Reinehr, Sheila. Livro Engenharia de Requisitos, 2020.

2. [Open Access] Leite, Julio Cesar Sampaio do Prado. Livro Vivo - Engenharia de Requisitos. Disponível em: http://livrodeengenhariaderequisitos.blogspot.com/ (Último acesso em 21/03/2021).

3. SOMMERVILLE,I.;SoftwareEngineering,9.ed.,Addison-Wesley

4. CHUNG, Lawrence; NIXON, Brian. Nixon, YU, Eric; MYLOPOULOS, John. "Non-Functional Requirements in Software Engineering". Springer US, 2000.

5. SILVA, Reinaldo Antônio da. NFR4ES: Um Catálogo de Requisitos Não-Funcionais para Sistemas Embarcados. 2019


</div>