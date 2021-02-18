# <center> Planejamento da equipe
## Histórico de versão

| Data | Versão | Descrição | Autor|
| :-: | :-: | :-: | :-: |
| 18/02/2021 | 0.1 | Criação do Documento | Leonardo Gomes |

<div align="justify">

## 1. HeatMap

Foi construído um heatmap para ter um conhecimento da disponibilidade dos integrantes para a realização de reuniões sobre o projeto. A numeração indica a quantidade de membros disponível naquele horário.

<p align='center'>
    <img src='assets/images/heatmap.png'>
    <figcaption align='center'>
        <b>Figura 2: Disponibilidade dos integrantes</b>
    </figcaption>
</p>

---

## 2. Metodologias

Todas as metodologias adotadas durante esse projeto tem relação com dois princípios fundamentais do desenvolvimento ágil de software. Esses princípios são:

```
Os indivíduos e suas interações acima de procedimentos e ferramentas
A capacidade de resposta a mudanças acima de uma plano pré-estabelecido
-- Manifesto Ágil
```

O projeto contará com várias metodologias que juntas formam o híbrido de métodos que será utilizado pela equipe. Será explicado como essas tecnologias juntas poderão ser a base de organização e peça fundamental para o projeto.

### 2.1 Scrum

O Scrum é um método que define várias atividades durante o desenvolvimento do projeto. Decidimos por utilizar o Scrum por todos os membros já estarem habituados com a metodologia. Nesse projeto utilizaremos dois artefatos do scrum: product backlog, sprint backlog. Também será utilizado alguns eventos do scrum como: sprint, sprint planning, sprint review.

#### 2.1.1 Eventos do Scrum

Os eventos são projetados especificamente para permitir a transparência da equipe. A falha em operar quaisquer eventos conforme prescrito resulta em oportunidades perdidas de inspeção e adaptação. Os eventos são usados no Scrum para criar regularidade e minimizar as reuniões desnecessárias.

**Sprint**: Eventos de duração fixa de um mês ou menos para criar consistência. Um novo Sprint começa imediatamente após a conclusão do Sprint anterior. Nosso grupo decidiu por utilizar o _timebox_ de uma semana tendo em vista a urgência de produção de resultados que o projeto necessita.

**Sprint planning**: Inicia o Sprint ao definir o trabalho a ser executado para o Sprint. Este plano é criado pelo trabalho colaborativo de toda a equipe.

**Sprint Review**: Inspecionar o resultado da sprint e determinar as adaptações futuras. A equipe apresenta os resultados de seu trabalho para os principais interessados e o progresso em direção ao objetivo do produto é discutido.

#### 2.1.2 Artefatos do scrum

Os artefatos do scrum representam trabalho e valor. Eles foram pensados para aumentar a transparência de informações da equipe. Utilizando o Kanban todos que possuem acesso aos artefatos têm a mesma base de adaptação.

Cada artefato proporciona informações sobre o progresso e como ele pode ser administrado e mensurado:

```
 - Product backlog está relacionado com os objetivos do produto
 - Sprint backlog está relacionado com os objetivos da sprint

```
**Product backlog**: Lista do que é necessário para o desenvolvimento do projeto. Essa lista se encontra como issues do nosso repositório, as issues são abstrações dos cartões de tarefas que descrevem o que deve ser feito e as limitações como tempo e pessoas alocadas.

**Sprint backlog**: Lista de tarefas definidas pela equipe do que será feito no período da sprint. Essa lista é sinalizada como milestone do nosso repositório, milestone é um conjunto de issues que são designadas para um tempo específico.

### 2.2 KANBAN

Kanban é um quadro de cartões, sendo que cada cartão representa uma atividade, onde é controlado os fluxos em que cada cartão se encontra. Esses fluxos podem ser vários, dependendo do processo em questão, mas no geral são 3 fluxos principais: "a fazer", "fazendo" e "feito".

No nosso contexto, o kanban foi dividido em 5 fluxos: project backlog, sprint backlog, in progress, review e done. No primeiro processo é onde ficam todos os cartões de tarefas mapeados até o momento. No segundo fluxo ficam as cartas de tarefa que serão realizados na sprint atual, no terceiro fluxo ficam as cartões cuja as tarefas já foram iniciadas, no fluxo review ficam as tarefas que já foram concluídas e estão esperando por revisão de terceiros, e no último fluxo ficam as tarefas que já foram revisadas e aprovadas.

---
## 3. Plano de comunicação

Com o objetivo de evitar problemas na comunicação dos membros e consequentemente gerar problemas nas entregas do projeto, foi pensando no plano de comunicação da equipe.

Oficialmente, toda a comunicação deve ser realizada por meio de duas ferramentas, o site de hospedagem de repositórios, GitHub, e o site de videoconferência Jitsi, sendo que as videosconferências realizadas devem ser documentadas e mantidas no GitHub.

As tarefas são delegadas por meio de issues e pull request, e toda comunicação deve ser feita por meio de comentários nesses dois canais.

Não oficialmente, os membros do projeto participam de um grupo de telegram, onde é realizado perguntas não pertinentes ao projeto.

É fortemente desencorajado a utilização de canais não oficiais para abordar temas pertinentes sobre o projeto. Isso porque se busca deixar documentado todas as atividades realizadas durante o desenvolvimento e comunicação por canais não oficiais que dificultam essa documentação. Outro motivo é que pelo fato do projeto ser livre, no sentido das quatro liberdades descritas na licença GPL v3.0, sendo elas:

- A liberdade de executar o projeto, para qualquer propósito
- A liberdade de estudar o projeto, e adaptá-lo para suas necessidades
- A liberdade de redistribuir cópias do projeto
- A liberdade de aperfeiçoar o programa, e liberar os seus aperfeiçoamento, de modo que toda a comunidade se beneficie.

Com isso em mente, é desejável que qualquer pessoa que se interesse pelo projeto possa acessá-lo livremente, sem autorização e inclusões em canais não oficiais.

---

## Bibliografia

- KANBAN. Disponível em https://pt.wikipedia.org/wiki/Kanban
- SCRUMGUIDE. Disponível em https://scrumguides.org/scrum-guide.html#scrum-events
- Manifesto Ágil, Disponível em: https://agilemanifesto.org/iso/ptbr/manifesto.html

Durante a elaboração desse documento, foi dois documentos de metodologia se mostraram úteis e serviram como referência, sendo eles:

- [O documento de metodologia do projeto BCE](https://interacao-humano-computador.github.io/2020.1-BCE/#/pages/ponto_de_controle_1/metodologia_do_projeto)
- [O documento de planejamento de equipe do projeto SEI](https://interacao-humano-computador.github.io/2020.1-SEI/#/./planning/team_planning)