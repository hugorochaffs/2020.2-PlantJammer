# <center> MoSCoW

### Histórico de Versão
|    Data    | Versão | Descrição            | Autor(es)       |
| :--------: | :----: | :------------------: | :-------------: |
| 11/03/2021 |  0.1   | Criação do documento | Leonardo Gomes |
| 11/03/2021 |  0.2   | Adição do resultado | Leonardo Gomes, Hugo Rocha e Victor Jorge |

<div align="justify">

## 1. Introdução

O MoSCoW é uma técnica de priorização utilizada para aspectos de desenvolvimento e gestão de projetos com o objetivo de determinar a importancia dos requisitos levantos para o projeto.

O termo MoSCoW é um acrônimo em inglês da primeira letra de uma das quatro classificações de priorização, são elas:

| Descrição | Classificação | 
| :- | :- |
| Prioritários/Críticos   |  **Must**  |
| Importantes   |  **Should**  |
| Desejáveis   |  **Could**  |
| Menos críticos   |  **Would / Want / Won't**  |

## 2. Objetivo

A técnica é muito simples: para cada *requisito funcional* levantado se deve se atribuir uma das quatro classificações. Nessa técnica iremos conseguir retirar uma estimativa de como devem ser planejadas as issues em *product backlog*, podendo retornar um *MVP* de maior qualidade possível.

## 3. Resultado

| ID | Descrição | Prioridade |
| :- | :- | :- |
| RF001 | O aplicativo deve deve fornecer no mínimo 100 pratos/receitas diferentes, sem contar as receitas que são criadas pelos usuários | SHOULD |
| RF002 | O aplicativo deve disponibilizar receitas simples e objetivas, que possuem um baixo grau de dificuldade | COULD |
| RF003 | O aplicativo deve ter uma sessão para listagem das receitas criadas por determinados chefs de cozinha | SHOULD |
| RF004 | O aplicativo deve ter uma sessão de edição de pratos favoritos | SHOULD |
| RF005 | Na página de cada receita, deve possuir uma área para o vídeo de alguém preparando a receitas | COULD |
| RF006 | Na página de cada receita, deve haver os passos ensinando a preparar a receita | MUST |
| RF007 | Na página de cada receita, deve haver um indicador do custo monetário estimado da receita, com base nos ingredientes necessários para o preparo | COULD |
| RF008 | Na página de cada receita, deve existir algum indicador de quais ingredientes podem ser substituídos para melhorar a receita | SHOULD |
| RF009 | Na página de cada receita, deve haver um seletor da quantidade de porções que se deseja fazer com a receita escolhida. Uma vez definido a quantidade de porções, a quantidade de ingredientes devem ser atualizadas automaticamente | MUST |
| RF010 | Na página de cada receita, deve ser exibido as informações nutricionais da refeição | SHOULD |
| RF011 | Na página de cada receita, deve ser exibido o tempo estimado de preparo da receita | MUST |
| RF012 | Na página de cada receita, na sessão de passo a passo, pode haver dicas entre os passos, sinalizado a melhor maneira de se realizar o passo | SHOULD |
| RF013 | Na página de cada receita, deve haver a opção de compartilhar uma receita | SHOULD |
| RF014 | Na página de cada receita, deve haver uma sessão de sugestões, onde será sugerido as melhores bebidas que combinam com determinada receita | COULD |
| RF015 | Toda receita deve possuir uma avaliação associada, e essa avaliação deve ser apresentada sempre que a receita for exibida | SHOULD |
| RF016 | Na página de cada receita, deve existir a opção de avaliar a receita | MUST |
| RF017 | Na página de cada receita, deve existir a opção de favoritar a receita | SHOULD |
| RF018 | Na página de cada receita, deve existir a opção de desfavoritar a receita | SHOULD |
| RF019 | Em algum lugar do APP deve ser possível ver todas as receitas que já foram favoritadas pelo usuário | SHOULD |
| RF020 | Na página de cada receita, deve existir uma sessão de avaliações, onde será exibido todas as avaliações feitas até então | SHOULD |
| RF021 | Na página de pesquisa de receitas, deve existir um filtro para exibir somente as receitas acima de um certa avaliação | SHOULD |
| RF022 | Na página de pesquisa de receitas, deve existir um filtro para selecionar o fator predominante na receita, sendo que o fator é um ingrediente que irá predominar sobre os demais | SHOULD |
| RF023 | Na página de pesquisa de receitas, deve ser possível pesquisar receitas pelo nome | MUST |
| RF024 | Caso uma receita seja de um Chef, deve existir a opção de visualizar o perfil do Chef, e nesse perfil deve exibir informações como: nome, local onde trabalha, experiência, número de seguidores, número de receitas curtidas, etc | COULD |
| RF025 | Na página de perfil de um Chef deve existir a opção de seguir o Chef | COULD |
| RF026 | Na página de perfil de um Chef deve existir a opção de deixar de seguir o Chef | COULD |
| RF027 | Na página de perfil de um Chef deve existir a opção de avaliar o Chef | COULD |
| RF028 | Na página de perfil de um Chef, deve exibir a média das avaliações e a quantidade de avaliações do chefe | COULD |
| RF029 | O aplicativo deve ter a opção de criar uma nova conta, utilizando email e senha | MUST |
| RF030 | Após criar uma nova conta utilizando email e senha, deve ser enviado um email de confirmação, com um link, para o email definido. Enquanto o link não for clicado a conta deve permanecer como "não verificada" | SHOULD |
| RF031 | O aplicativo deve ter a opção de criar uma nova conta, utilizando a conta do Google ou Facebook | SHOULD |
| RF032 | Durante o fluxo de criação de conta, deve ser apresentado os Termos e Políticas do APP, e para criar a conta o usuário deve clicar que leu e concorda | MUST |
| RF033 | O aplicativo deve ter a opção de realizar login com uma conta existente, utilizando email e senha | MUST |
| RF034 | Na tela de login, deve haver a opção de recuperar senha | MUST |
| RF035 | O aplicativo deve ter a opção de relizar login utilizando a conta do Google ou Facebook | SHOULD |
| RF036 | O aplicativo deve ter a opção de modificar o nome, email e senha da conta existente | MUST |
| RF037 | O aplicativo deve ter a opção de excluir uma conta existente | MUST |
| RF038 | O aplicativo deve ter a opção de modificar a unidade de medida escolhida (medida imperial, medida métrica) | MUST |
| RF039 | O aplicativo deve ter a opção de registrar as preferências culinárias (pizza, sopas, tortas, etc) | SHOULD |
| RF040 | O aplicativo deve ter a opção de modificar as preferências culinárias (pizza, sopas, tortas, etc) | SHOULD |
| RF041 | O aplicativo deve ter a opção de registrar as restrições alimentáres do usuário | MUST |
| RF042 | O aplicativo deve ter a opção de modificar as restrições alimentáres do usuário | MUST |
| RF043 | Na página de pesquisa de receitas, deve ser possível filtrar as receitas pelos ingredientes disponíveis | MUST |
| RF044 | A lista de resultados exibidas para o usuário deve levar em consideração as preferências culinárias do usuário | MUST |
| RF045 | Na página de pesquisa de receitas, deve ser possível filtrar as receitas pelo Chef que cadastrou a receita | COULD |
| RF046 | Na página de pesquisa de receitas, deve ser possível filtrar as receitas com base na estação do ano | COULD |
| RF047 | O aplicativo deve ter uma sessão de agendar uma refeição, desse modo o usuário poderá programar qual dia irá fazer qual receita | COULD |
| RF048 | O usuário deve poder modificar a data agendada de uma determinada refeição | COULD |
| RF049 | O usuário deve poder remover uma receita que foi agendada para uma determinada data | COULD |
| RF050 | O usuário deve poder compartilhar o planejamento de refeições agendadas de uma determinada semana ou mês | COULD |
| RF051 | Na página de refeições cadastradas deve ser possível cancelar um agendamento de refeição | COULD |
| RF052 | O aplicativo deve ter uma sessão para gerar uma lista de compras com base nas receitas que foram programadas para a semana ou para o mês | COULD |
| RF053 | Na página da lista de compras, deve ser possível remover produtos da lista de compras | COULD |
| RF054 | Na página da lista de compras, devem haver blocos de notas, para lembrar de algo | WANT |
| RF055 | Em uma determinada lista de compras, deve ser possível marcar os alimentos que já foram adquiridos | COULD |
| RF056 | Deve ser possível compartilhar uma lista de compras | COULD |
| RF057 | Na página da lista de compras, deve ser possível adicionar produtos da lista de compras | COULD |
| RF058 | Na página de configurações do aplicativo, deve ser possível de mudar a linguagem do APP (portugues, ingles, espanhol, frances, ...) | MUST |
| RF059 | Ao selecionar uma nova linguagem, a linguagem do aplicativo deve mudar para a opção selecionada | MUST |
| RF060 | Na página de configurações do aplicativo, deve ser possível escolher o tema do aplicativo (modo claro e modo escuro) | WANT |
| RF061 | Na página de configurações do aplicativo, deve ser possível apagar a conta do usuário | MUST |
| RF062 | Quando um novo usuário acessar o aplicativo pela primeira vez, o aplicativo deve iniciar com o modo Tour, onde o aplicativo irá guiar a navegação, apresentando as principais sessões do APP | MUST |
| RF063 | Na página de perfil do usuário, deve haver opção de exibir o histórico de receitas curtidas e receitas visitadas pelo usuário | SHOULD |
| RF064 | De tempos em tempos deve ser exibido um popup solicitando a avaliação do aplicativo pelo usuário, caso ainda não tenha sido avaliado | COULD |
| RF065 | Deve ser possível utilizar o aplicativo mesmo sem estar logado ou possuir uma conta. Quando o aplicativo for aberto, se não existir um usuário logado deve existir uma opção para acessar sem login | MUST |
| RF066 | Usuários que nunca tiveram uma assitura Premium devem poder experimentar a assinatura Premium durante 7 dias | COULD |
| RF067 | Os usuáros devem poder obter a assinatura Premium após a confirmação do pagamento | MUST |
| RF068 | Deve ser mostrado anúncios para usuários Freemium, e não deve ser mostrado anúncios para usuários que tiverem assinatura Premium | MUST |
| RF069 | Usuários Freemium devem ter um limite de receitas que podem ser consultadas no dia. Usuários Premium não possuem essas limitações | SHOULD |
| RF070 | Durante períodos excepcionais (promoções, datas comemorativas, pandemias, etc) deve ser liberado assinaturas Premium para todos os usuários | COULD|
| RF071 | Para usuários que acabaram de criar a conta, deve ser perguntado qual o objetivo do usuário (Comer mais vegetais, Esvaziar a geladeira, Descobrir novas receitas, Comer comidas saudáveis) | SHOULD |
| RF072 | Para usuários que acabaram de criar a conta, deve ser perguntado se o usuário possui alguma restrição alimentar (Alergias, Intolerâncias, não consumo de produtos de animais, etc) | MUST |
| RF073 | Para usuários que acabaram de criar a conta, deve ser perguntado quais são os pratos favoritos do usuário (Macarrão, Lasanhas, Saladas, etc) | MUST |
| RF074 | Para usuários que acabaram de criar a conta, deve ser perguntado qual a lingua que o APP deve ser configurado | WON'T |
| RF075 | Para usuários que acabaram de criar a conta, deve ser perguntado qual a unidade de medida (imperial, métrica) o APP deve ser configurado | WON'T |
| RF076 | Em algum lugar do APP deve ser possível ver todas as receitas que já foram favoritadas pelo usuário | SHOULD |
| RF077 | Antes de apresentar qualquer receita, deve ser perguntado ao usuário se ele tem alguma restrição alimentar | WON'T |
| RF078 | Deve existir a opção de selecionar receitas genéricas (Pizzas, omeletes, sopas, etc), onde o usuário irá receber uma receita adaptada com base nos ingredientes selecionados | COULD |
| RF079 | Na página de busca de receitas, deve ser possível definir qual será o aroma da receita desejada | COULD |
| RF080 | Antes de gerar uma receita para o usuário, deve ser exibido a lista de ingredientes selecionados e solicitado a confirmação | MUST |
| RF081 | Antes de gerar uma receita para o usuário, deve ser apresentado a roda dos sabores básicos do paladar humano (Doce, Salgado, Azedo, Amargo, Umami), onde cada ingrediente será categorizado em uma parte da roda, e será solicitado a confirmação do usuário. Nessa etapa, o usuário pode adicionar novos ingredientes de acordo com os sabores que estão faltando | COULD |
| RF082 | Antes de gerar uma receita para o usuário, deve ser apresentado um score da receita que será gerada, de acordo com os ingredientes que foram selecionados | SHOULD |
| RF083 | Antes de gerar uma receita para o usuário, caso o score seja muito baixo o APP deve intervir e perguntar se o usuário não deseja realizar determinada alteração na receita | SHOULD |
| RF084 | Após a seleção e confirmação de todas as etapas de geração de receita, deve ser apresentado a receita de acordo com os ingredientes definidos | MUST |
| RF085 | O usuário deve poder selecionar e visualizar uma receita já existente | MUST |
| RF086 | O usuário deve poder criar/cadastrar uma receita no APP | SHOULD |
| RF087 | Na receita que o usuário está executando deve haver a opção de selecionar os passos que já foram executados | SHOULD |
| RF088 | O usuário deve poder agrupar as receitas em pastas (por exemplo: pasta doces, pasta salgados, pasta "gluten free") | COULD |
| RF089 | Na página de pesquisa deve ser possível encontrar pastas criadas por outros usuários | COULD |
| RF090 | Na parte de configurações deve existir a opção de convidar/compartilhar o aplicativo com outros usuários | SHOULD |
| RF091 | O aplicativo deve possuir uma sessão de anotações, onde os usuários poderão deixar seus lembretes | WANT |
| RF092 | Na página de perfil do usuário, deve ter a opção de visualizar o quadro nutricional do usuário, com base nas receitas que o usuário preparou durante a semana e durante o mês | COULD |


## 4 Conclusão

Após a priorização de todos os requisitos funcionais foram obtidos os seguintes resultados:

|Quantidade|Classificação|
| :- | :- |
| 28 | MUST|
| 28 |SHOULD|
| 30 |COULD|
| 6  |WOULD/WANT/WON'T|

## Bibliografia

1. SERRANO, Maurício; SERRANO, Milene. Requisitos - Aula 07. 1º/2019. 50 slides. Material apresentado para a disciplina de Requisitos de Software no curso de Engenharia de Software da UnB, FGA.

Durante a elaboração desse documento, um documento se mostrou útil e serviu como referência:

- [Priorização dos requisitos funcionais do projeto Stock](https://unbarqdsw.github.io/2020.1_G12_Stock/#/Modeling/MOSCOW)

<div/>