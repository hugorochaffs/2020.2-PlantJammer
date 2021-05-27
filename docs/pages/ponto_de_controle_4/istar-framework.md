# <center> iStar Framework

### Histórico de Versão
|    Data    | Versão | Descrição            | Autor(es)       |
| :--------: | :----: | :------------------: | :-------------: |
| 27/05/2021 |  0.1   | Criação do documento | Leonardo Gomes |

<div align="justify">

## 1. Introdução

O _iStar Framework_ é um modelo criado com o intuito de esclarecer e detalhar dúvidas a respeito dos requistos funcionais. Esse modelo é dividido em duas partes:

#### 1.1 Strategic Dependency

O modelo SD é usado para expressar a rede de relacionamentos estratégicos intencionais entre os atores. (GRAU Gemma e HORKOFF Jennifer, 2006) Esse Modelo é um conjunto de nós e elos onde cada nó representa um ator e cada elo entre dois atores indica que um ator depende do outro para algo para que aquele possa atingir algum objetivo.

##### 1.1.1 Atores

Entidades ativas que realizam ações para atingir objetivos. O termo ator é utilizado para nos referirmos genericamente a qualquer unidade à qual dependências intencionais podem ser atribuídas. Agentes, papéis e posições são subunidades de um ator complexo, cada um dos quais é um ator em um sentido mais especializado. (GRAU Gemma e HORKOFF Jennifer, 2006)

<p align='center'>
  <img src='assets/images/sdactor.png'>
  <figcaption align='center'>
      <b>Figura 1: Representação de atores no modelo iStar</b>
      <br>
      <small>Fonte: GRAU Gemma e HORKOFF Jennifer, 2006</small>
  </figcaption>
</p>

__Papel__: Caracterização abstrata do comportamento de um ator dentro de algum contexto especializado ou domínio de atuação. Suas características são facilmente transferíveis para outros atores. As dependências associadas a uma função se aplicam independentemente do agente que desempenha a função. (GRAU Gemma e HORKOFF Jennifer, 2006)

<p align='center'>
  <img src='assets/images/sdRole.png'>
  <figcaption align='center'>
      <b>Figura 2: Representação de papel no modelo iStar</b>
      <br>
      <small>Fonte: GRAU Gemma e HORKOFF Jennifer, 2006</small>
  </figcaption>
</p>

__Agente__: Ator com manifestações físicas concretas, como um indivíduo humano. Usamos o termo agente em vez de pessoa para generalizar, de forma que ele pode ser usado para se referir tanto a humanos quanto a artificiais (agentes de hardware / software). Um agente tem dependências que se aplicam independentemente das funções que ele / ela está desempenhando. Essas características normalmente não são facilmente transferíveis para outros indivíduos, por exemplo, suas habilidades e experiências e suas limitações físicas. (GRAU Gemma e HORKOFF Jennifer, 2006)

<p align='center'>
  <img src='assets/images/sdAgent.png'>
  <figcaption align='center'>
      <b>Figura 3: Representação de agente no modelo iStar</b>
      <br>
      <small>Fonte: GRAU Gemma e HORKOFF Jennifer, 2006</small>
  </figcaption>
</p>

__Posição__: Abstração intermediária que pode ser usada entre uma função e um agente. É um conjunto de funções normalmente desempenhadas por um agente (por exemplo, atribuídas conjuntamente a esse agente). Dizemos que um agente ocupa uma posição. Diz-se que uma posição cobre uma função. (GRAU Gemma e HORKOFF Jennifer, 2006)

<p align='center'>
  <img src='assets/images/sdPosition.png'>
  <figcaption align='center'>
      <b>Figura 4: Representação de posição no modelo iStar</b>
      <br>
      <small>Fonte: GRAU Gemma e HORKOFF Jennifer, 2006</small>
  </figcaption>
</p>

##### 1.1.2 Links

Os relacionamentos entre os atores são descritos por links de associação gráfica entre os atores. Os links são divididos em 6 subcategorias como o objetivo de detalhar o relacionamento entre atores. Para saber mais sobre a definição de cada link, acesse (http://istarwiki.org/tiki-index.php?page=iStarQuickGuide#SR_Means-End_Links). 

<p align='center'>
  <img src='assets/images/sdLinks.png'>
  <figcaption align='center'>
      <b>Figura 5: Representação de link no modelo iStar do SD</b>
      <br>
      <small>Fonte: GRAU Gemma e HORKOFF Jennifer, 2006</small>
  </figcaption>
</p>

##### 1.1.3 Dependências

__Dependee__: Ator pai de outro ator como dependente de uma relação de dependência.

__Depender__: O ator dependente em um relacionamento de dependência.

__Dependum__: Elemento em torno do qual uma centros de relacionamento de dependência.

Podemos distinguir entre quatro tipos de dependências, com base no tipo de dependência: Dependência de recursos, Dependência de tarefas, Dependência de metas, Dependência de Softgoal. Para saber mais sobre a definição de cada dependência, acesse (http://istarwiki.org/tiki-index.php?page=iStarQuickGuide#SR_Means-End_Links). 

<p align='center'>
  <img src='assets/images/sdDependency.png'>
  <figcaption align='center'>
      <b>Figura 6: Representação de dependência no modelo iStar</b>
      <br>
      <small>Fonte: GRAU Gemma e HORKOFF Jennifer, 2006</small>
  </figcaption>
</p>

#### 1.2 Strategic Rationale

O modelo SR é um gráfico, com vários tipos de nós e links que trabalham juntos para fornecer uma estrutura representacional para expressar os fundamentos por trás das dependências. Os atores com o modelo SD são "abertos" para mostrar suas intenções específicas. Existem quatro tipos de nós, com base nas mesmas distinções feitas para tipos de dependência no modelo SD: objetivo, tarefa, recurso e meta flexível. Existem três classes principais de links internos ao ator iStar: links meios-fins, links de decomposição de tarefas e links de contribuição. (GRAU Gemma e HORKOFF Jennifer, 2006)

##### 1.2.1 Limite do Ator

Os limites do ator indicam os limites intencionais de um determinado ator. Todos os elementos dentro de um limite para um ator são explicitamente desejados por esse ator. Para alcançar esses elementos, muitas vezes um ator deve depender das intenções de outros atores, representados por links de dependência entre os limites do ator. Por sua vez, depende-se de um ator para satisfazer certos elementos, representados por um elo de dependência na direção oposta. (GRAU Gemma e HORKOFF Jennifer, 2006)

<p align='center'>
  <img src='assets/images/srActor.png'>
  <figcaption align='center'>
      <b>Figura 7: Representação do limite do ator no modelo iStar</b>
      <br>
      <small>Fonte: GRAU Gemma e HORKOFF Jennifer, 2006</small>
  </figcaption>
</p>

##### 1.2.2 Elementos / Nós

Os significados desses elementos são geralmente os mesmos encontrados nas dependências, com a exceção de que a satisfação dos elementos pode ser realizada internamente. Para saber mais sobre a definição dos elementos / nós, acesse (http://istarwiki.org/tiki-index.php?page=iStarQuickGuide#SR_Means-End_Links). 

<p align='center'>
  <img src='assets/images/srElement.png'>
  <figcaption align='center'>
      <b>Figura 8: Representação de elementos no modelo iStar</b>
      <br>
      <small>Fonte: GRAU Gemma e HORKOFF Jennifer, 2006</small>
  </figcaption>
</p>

##### 1.2.3 Links

##### 1.2.3.1 Links meio-fim

Esses links indicam uma relação entre um fim e um meio para alcançá-lo. O “meio” se expressa na forma de tarefa, já que a noção de tarefa incorpora como fazer algo, com o “fim” expresso como uma meta. Na notação gráfica, a ponta da seta aponta dos meios para o fim.

<p align='center'>
  <img src='assets/images/srLinkEndtoEnd.png'>
  <figcaption align='center'>
      <b>Figura 9: Representação de link meio-fim no modelo iStar</b>
      <br>
      <small>Fonte: GRAU Gemma e HORKOFF Jennifer, 2006</small>
  </figcaption>
</p>

##### 1.2.3.2 Links de decomposição

Um elemento de tarefa é vinculado a seus nós de componentes por links de decomposição. Uma tarefa pode ser decomposta em quatro tipos de elementos: uma submeta, uma subtarefa, um recurso e / ou uma meta flexível - correspondendo aos quatro tipos de elementos. A tarefa pode ser decomposta em um ou vários desses elementos. Esses elementos também podem fazer parte dos links de dependência no (s) modelo (s) de Dependência Estratégica quando o raciocínio vai além do limite de um ator.

<p align='center'>
  <img src='assets/images/srLinkDecopisition.png'>
  <figcaption align='center'>
      <b>Figura 10: Representação de link de decomposição no modelo iStar</b>
      <br>
      <small>Fonte: GRAU Gemma e HORKOFF Jennifer, 2006</small>
  </figcaption>
</p>

##### 1.2.3.3 Links de contribuição

Os links de contribuição são divididos 9 subcategorias, para saber mais sobre a definição dos links de contribuição, acesse (http://istarwiki.org/tiki-index.php?page=iStarQuickGuide#SR_Means-End_Links). 

<p align='center'>
  <img src='assets/images/srLinkCont.png'>
  <figcaption align='center'>
      <b>Figura 11: Representação de link de contribuição no modelo iStar</b>
      <br>
      <small>Fonte: GRAU Gemma e HORKOFF Jennifer, 2006</small>
  </figcaption>
</p>

<p align='center'>
  <img src='assets/images/srLinkRelCont.png'>
  <figcaption align='center'>
      <b>Figura 12: Representação de link de contribuição com elementos no modelo iStar</b>
      <br>
      <small>Fonte: GRAU Gemma e HORKOFF Jennifer, 2006</small>
  </figcaption>
</p>


## 2. Objetivo

O objetivo desse documento é apresentar o SD (Strategic Dependency) e o SR (Strategic Rationale) construídos com o objetivo de modelar e dar mais visibilidade aos requisitos funcionais do projeto.

## 3. Resultados

### 3.1 Strategic Dependency

<p align='center'>
    <img src='assets/images/strategic_dependency.png'>
    <figcaption align='center'>
        <b>Figura 1: Strategic Dependency</b>
        <br>
        <small>Fonte: Autor</small>
    </figcaption>
</p>

<br><br>

### 3.2 Strategic Rationale

<p align='center'>
    <img src='assets/images/strategic_rationale.png'>
    <figcaption align='center'>
        <b>Figura 2: Strategic Rationale</b>
        <br>
        <small>Fonte: Autor</small>
    </figcaption>
</p>

<br><br>

## 4. Conclusão

Após a utilização do iStar Framework a equipe analista de requisitos foi capaz de identificar diversas maneiras de implementar e priorizar os requisitos funcionais do projeto.

## Bibliografia

1. GRAU Gemma e HORKOFF Jennifer, 2006. Disponível em: http://istarwiki.org/tiki-index.php?page=iStarQuickGuide (Último acesso em 27/05/2021).

2. GRAU Gemma e HORKOFF Jennifer, 2006. Disponível em: http://istarwiki.org/tiki-index.php?page=i%2A+Guides&structure=i%2A+Wiki+Home (Último acesso em 27/05/2021).

3. GRAU Gemma e HORKOFF Jennifer, 2006. Disponível em: http://istarwiki.org/tiki-index.php?page=Purpose&structure=i%2A+Guide (Último acesso em 27/05/2021).

4. GRAU Gemma e HORKOFF Jennifer, 2006. Disponível em: http://istarwiki.org/tiki-view_articles.php (Último acesso em 27/05/2021).


</div>
