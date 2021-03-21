# <center> Brainstorm

### Histórico de Versão
|    Data    | Versão | Descrição            | Autor(es)       |
| :--------: | :----: | :------------------: | :-------------: |
| 27/02/2021 |  0.1   | Criação do documento | João Victor |
| 07/03/2021 |  0.2   | Refatoração do documento | João Victor |
| 11/03/2021 |  0.3   | Ajuste no título da tabela de requisitos levantados  | Leonardo Gomes |
| 11/03/2021 |  0.4   | Melhora o tópico de introdução | Durval Carvalho |
| 21/03/2021 |  1.0   | Adição de links para os [léxicos](pages/ponto_de_controle_3/lexico) | Leonardo Gomes |

<div align="justify">

## 1. Introdução

Brainstorming é uma técnica que, por meio do compartilhamento espontâneo de ideias, busca encontrar a solução para um problema ou gerar insights de criatividade. Para que seja bem-sucedido, o processo deve focar em quantidade, não em qualidade.

Assim, é importante que o brainstorming seja completamente livre de críticas. Mesmo as ideias que parecem ineficientes devem ser levadas em conta, afinal, elas podem ser o ponto de partida para a construção de pensamentos mais aprofundados.

A aplicação da técnica requer preparação e envolvimento de várias pessoas.

Inicialmente, deve ser selecionada uma dinâmica para o entrosamento dos participantes, que permita que o ambiente fique descontraído e propício à criatividade. É comum que haja algumas brincadeiras em pé ou em movimento. Mas não se deve tomar muito tempo do evento.

Para a realização de Brainstorming presenciais é necessário o uso de canetas e post-it. Porém para a realização de Brainstorming remotos, com auxílio de ferramentas computacionais é necessário que o sistema em questão seja compreendido por todos os participantes, além de garantir que todos possuam uma boa conexão de rede.

Um Brainstorming é composto por três etapas:
* Aquecimento (com a dinâmica selecionada)
* Ideação (geração de ideias)
* Encerramento (agrupamento das ideias)

Opcionalmente pode ser realizado uma última etapa onde será avaliado e votado as melhores ideias.

Vale lembrar que o Brainstorming não funciona bem em times fechados e muito formais. Nesse cenário os participantes não vão ter entrosamento necessário para se aplicar a técnica. Outro ponto importante é que se deve evitar ao máximo possível a realização de críticas e julgamentos das ideias propostas, pois isso prejudica a dinâmica.

Os grupos de Brainstorming deve ter ao máximo 8 pessoas. Quando houver mais do que 8 pessoas é recomendado a divisão em grupos menores.

A técnica de Brainstorming é muito útil quando se deseja encontrar soluções inovadoras e criativas. Também é muito útil quando se deseja desenvolver uma solução nova, que não existe ainda opções no mercado.

## 2. Metodologia
A equipe realizou uma reunião para a realização da técnica de brainstorm. Para organizar as ideias e opniões utilizamos o *Jamboard*, uma ferramenta de quadro branco digital, em que cada participante escrevia suas ideias em notas autoadesivas, e para ter um direcionamento das ideias foram levantadas as seguintes perguntas:

- Quais características o app ideal deve ter?
- Quais informações o app deve fornecer?
- Quais as tarefas o [usuário](pages/ponto_de_controle_3/lexico?id=usuário) precisa realizar no app?
- Quais informações o App deve fornecer sobre as [receitas](pages/ponto_de_controle_3/lexico?id=receita)?

Participaram do Brainstorm:

- João Victor
- Hugo Rocha
- Durval Carvalho
- Victor Jorge


## 3. Objetivo
O objetivo desse documento é registrar ideias e requisitos elicitados com o uso da técnica de brainstorm.


## 4. Brainstorm

### 4.1 Resultados
<p align='center'>
    <img src='assets/images/brainstorm1.png'>
    <figcaption align='center'>
        <b>Figura 1: Ideias levantadas sobre características ideais que o app deve ter</b>
        <br>
        <small>Fonte: Autor</small>
    </figcaption>
</p>

<p align='center'>
    <img src='assets/images/brainstorm2.png'>
    <figcaption align='center'>
        <b>Figura 2: Ideias levantadas sobre informações que o app deve fornecer</b>
        <br>
        <small>Fonte: Autor</small>
    </figcaption>
</p>

<p align='center'>
    <img src='assets/images/brainstorm3.png'>
    <figcaption align='center'>
        <b>Figura 3: Ideias levantadas sobre tarefas que o usuário realiza no app</b>
        <br>
        <small>Fonte: Autor</small>
    </figcaption>
</p>

<p align='center'>
    <img src='assets/images/brainstorm4.png'>
    <figcaption align='center'>
        <b>Figura 4: Ideias levantadas sobre informações que o app deve fornecer sobre as receitas</b>
        <br>
        <small>Fonte: Autor</small>
    </figcaption>
</p>

### 4.2 Requisitos levantados

| ID LOCAL | Descrição | Tipo de Requisito |
| :------: | :-------: | :--------------:  |
| BST01 | As [receitas](pages/ponto_de_controle_3/lexico?id=receita) devem ter um video ensinando o preparo | Requisito Funcional|
| BST02 | As [receitas](pages/ponto_de_controle_3/lexico?id=receita) devem ter [passo a passo](pages/ponto_de_controle_3/lexico?id=passo) do preparo | Requisito Funcional|
| BST03 | Deve ser exibido o custo estimado da [receita](pages/ponto_de_controle_3/lexico?id=receita) | Requisito Funcional|
| BST04 | Ter a opção de exibir [ingredientes](pages/ponto_de_controle_3/lexico?id=ingrediente) que possam melhorar a [receita](pages/ponto_de_controle_3/lexico?id=receita) | Requisito Funcional|
| BST05 | Ter a opção de exibir [ingredientes](pages/ponto_de_controle_3/lexico?id=ingrediente) que possam substituir outro [ingrediente](pages/ponto_de_controle_3/lexico?id=ingrediente) | Requisito Funcional|
| BST06 | Deve exibir as quantidades de [ingredientes](pages/ponto_de_controle_3/lexico?id=ingrediente) de acordo com o numero de [porções](pages/ponto_de_controle_3/lexico?id=Porções) desejadas | Requisito Funcional|
| BST07 | Ter a opção de exibir [informações nutricionais](pages/ponto_de_controle_3/lexico?id=quadro-nutricional) sobre os [ingredientes](pages/ponto_de_controle_3/lexico?id=ingrediente) | Requisito Funcional|
| BST08 | Deve exibir o tempo de preparo da [receita](pages/ponto_de_controle_3/lexico?id=receita) | Requisito Funcional|
| BST09 | Ter a opção de exibir dicas sobre o preparo da [receita](pages/ponto_de_controle_3/lexico?id=receita) | Requisito Funcional|
| BST10 | Ter a opção de exibir a [avaliação da receita](pages/ponto_de_controle_3/lexico?id=avaliar-receita)visualizada | Requisito Funcional|
| BST11 | Ter a opção de exibir recomendações de [receitas bem avaliadas](pages/ponto_de_controle_3/lexico?id=avaliar-receita) | Requisito Funcional|
| BST12 | Ter a opção de exibir informações sobre o chefe que criou a [receita](pages/ponto_de_controle_3/lexico?id=receita) (Nome do chefe, onde ele trabalha, experiencia, seguidores) | Requisito Funcional|
| BST13 | Ter a opção de avaliar um chefe | Requisito Funcional|
| BST14 | Ter a opção de exibir avaliações sobre o chefe | Requisito Funcional|
| BST15 | Ter a opção de [avaliar a receita](pages/ponto_de_controle_3/lexico?id=avaliar-receita) | Requisito Funcional|
| BST16 | Ter a opção de ver a avaliação de outros [usuários](pages/ponto_de_controle_3/lexico?id=usuário) sobre a [receita](pages/ponto_de_controle_3/lexico?id=receita) | Requisito Funcional|
| BST17 | Ter a opção de criar [conta](pages/ponto_de_controle_3/lexico?id=conta) | Requisito Funcional|
| BST18 | Ter a opção de [login](pages/ponto_de_controle_3/lexico?id=fazer-login) | Requisito Funcional|
| BST19 | Ter a opção de modificar a [conta](pages/ponto_de_controle_3/lexico?id=fazer-login) (Nome, email, senha) | Requisito Funcional|
| BST20 | Ter a opção de deletar a [conta](pages/ponto_de_controle_3/lexico?id=fazer-login) | Requisito Funcional|
| BST21 | Ter a opção de modificar unidade de medida | Requisito Funcional|
| BST22 | Ter a opção de adicionar preferências culinárias | Requisito Funcional|
| BST23 | Ter a opção de modificar as preferências culinárias | Requisito Funcional|
| BST24 | Ter a opção de [compartilhar receitas](pages/ponto_de_controle_3/lexico?id=compartilhar-uma-receita) entre [usuários](pages/ponto_de_controle_3/lexico?id=usuário) | Requisito Funcional|
| BST25 | Ter a opção de adicionar [restrições alimentares](pages/ponto_de_controle_3/lexico?id=restrição-alimentar) | Requisito Funcional|
| BST26 | Ter a opção de modificar [restrições alimentares](pages/ponto_de_controle_3/lexico?id=restrição-alimentar) | Requisito Funcional|
| BST27 | Ter a opção de filtrar [receitas](pages/ponto_de_controle_3/lexico?id=receita) com base em [ingredientes](pages/ponto_de_controle_3/lexico?id=ingrediente) já disponíveis em casa | Requisito Funcional|
| BST28 | Ter a opção de buscar chefes | Requisito Funcional|
| BST29 | Ter a opção de seguir chefes | Requisito Funcional|
| BST30 | Ter a opção de programar refeições | Requisito Funcional|
| BST31 | Ter a opção de criar lista de compras com base em refeições programadas | Requisito Funcional|
| BST32 | Ter a opção de remover produtos da lista de compras | Requisito Funcional|
| BST33 | Ter a opção de cancelar refeições programadas | Requisito Funcional|
| BST34 | Ter a opção de recomendações de bebidas que combinem com a [receita](pages/ponto_de_controle_3/lexico?id=receita) | Requisito Funcional|
| BST35 | Ter a opção de recomendações de [receitas](pages/ponto_de_controle_3/lexico?id=receita) por sazonalidade  | Requisito Funcional|
| BST36 | Ter um layout responsivo para varios tamanhos de tela | Requisito Não Funcional|
| BST37 | Ter suporte a varias linguas (portugues, ingles, espanhol, frances, ...) | Requisito Funcional|
| BST38 | O [aplicativo](pages/ponto_de_controle_3/lexico?id=aplicativo) deve ser leve (não ocupar mais que 100MB) | Requisito Não Funcional|
| BST39 | O [aplicativo](pages/ponto_de_controle_3/lexico?id=aplicativo) deve ser rapido (não demorar mais que 500ms para abrir e carregar [receitas](pages/ponto_de_controle_3/lexico?id=receita) ) | Requisito Não Funcional|
| BST40 | O [aplicativo](pages/ponto_de_controle_3/lexico?id=aplicativo) deve ter uma interface agradavel | Requisito Não Funcional|
| BST41 | O [aplicativo](pages/ponto_de_controle_3/lexico?id=aplicativo) deve ter compatibilidade com diversos sitemas operacionais(Android, IOS, Windows Phone) | Requisito Não Funcional|
| BST42 | O [aplicativo](pages/ponto_de_controle_3/lexico?id=aplicativo) deve ter modo escuto e modo claro | Requisito Funcional|
| BST43 | Ter a opção de fazer um tour pelo [aplicativo](pages/ponto_de_controle_3/lexico?id=aplicativo) para entender como usa-lo | Requisito Funcional|
| BST44 | Ter a opção de exibir um histórico de [receitas](pages/ponto_de_controle_3/lexico?id=receita) geradas pelo [usuário](pages/ponto_de_controle_3/lexico?id=usuário) | Requisito Funcional|

## 5. Conclusão

Foram identificados 44 requisitos utilizando a técnica de brainstorm.

## Bibliografia

1.  Woebcken, Cayo. O que é brainstorming e as 7 melhores técnicas para a tomada de decisões inteligentes. Disponível em: https://rockcontent.com/br/blog/brainstorming/ (Último acesso em 27/02/2021).

Durante a elaboração desse documento, o seguinte documento de brainstorm serviu como referência:

- [Documento de brainstorm do projeto Waze](https://requisitos-de-software.github.io/2019.2-Waze/Brainstorm/)

</div>
