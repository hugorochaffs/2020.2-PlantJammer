# <center> MoSCoW

### Histórico de Versão
|    Data    | Versão | Descrição            | Autor(es)       |
| :--------: | :----: | :------------------: | :-------------: |
| 11/03/2021 |  0.1   | Criação do documento | Leonardo Gomes |
| 11/03/2021 |  0.2   | Adição do resultado | Leonardo Gomes, Hugo Rocha e Victor Jorge |
| 21/03/2021 |  1.0   | Adição de links para os [léxicos](pages/ponto_de_controle_3/lexico) | Leonardo Gomes |

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
| RF001 | O [aplicativo](pages/ponto_de_controle_3/lexico?id=aplicativo) deve deve fornecer no mínimo 100 pratos/[receitas](pages/ponto_de_controle_3/lexico?id=receita) diferentes, sem contar as [receitas](pages/ponto_de_controle_3/lexico?id=receita) que são criadas pelos [usuários](pages/ponto_de_controle_3/lexico?id=usuário) | SHOULD |
| RF002 | O [aplicativo](pages/ponto_de_controle_3/lexico?id=aplicativo) deve disponibilizar [receitas](pages/ponto_de_controle_3/lexico?id=receita) simples e objetivas, que possuem um baixo grau de dificuldade | COULD |
| RF003 | O [aplicativo](pages/ponto_de_controle_3/lexico?id=aplicativo) deve ter uma sessão para listagem das [receitas](pages/ponto_de_controle_3/lexico?id=receita) criadas por determinados chefs de cozinha | SHOULD |
| RF004 | O [aplicativo](pages/ponto_de_controle_3/lexico?id=aplicativo) deve ter uma sessão de edição de pratos favoritos | SHOULD |
| RF005 | Na página de cada [receita](pages/ponto_de_controle_3/lexico?id=receita), deve possuir uma área para o vídeo de alguém [preparando a receitas](pages/ponto_de_controle_3/lexico?id=preparar-receita) | COULD |
| RF006 | Na página de cada [receita](pages/ponto_de_controle_3/lexico?id=receita), deve haver os [passos](pages/ponto_de_controle_3/lexico?id=passo) ensinando a [preparar a receita](pages/ponto_de_controle_3/lexico?id=preparar-receita) | MUST |
| RF007 | Na página de cada [receita](pages/ponto_de_controle_3/lexico?id=receita), deve haver um indicador do custo monetário estimado da [receita](pages/ponto_de_controle_3/lexico?id=receita), com base nos [ingredientes](pages/ponto_de_controle_3/lexico?id=ingrediente) necessários para o preparo | COULD |
| RF008 | Na página de cada [receita](pages/ponto_de_controle_3/lexico?id=receita), deve existir algum indicador de quais [ingredientes](pages/ponto_de_controle_3/lexico?id=ingrediente) podem ser substituídos para melhorar a [receita](pages/ponto_de_controle_3/lexico?id=receita) | SHOULD |
| RF009 | Na página de cada [receita](pages/ponto_de_controle_3/lexico?id=receita), deve haver um seletor da quantidade de porções que se deseja fazer com a [receita](pages/ponto_de_controle_3/lexico?id=receita) escolhida. Uma vez definido a quantidade de porções, a quantidade de [ingredientes](pages/ponto_de_controle_3/lexico?id=ingrediente) devem ser atualizadas automaticamente | MUST |
| RF010 | Na página de cada [receita](pages/ponto_de_controle_3/lexico?id=receita), deve ser exibido as [informações nutricionais](pages/ponto_de_controle_3/lexico?id=quadro-nutricional) da [refeição](pages/ponto_de_controle_3/lexico?id=comida)  | SHOULD |
| RF011 | Na página de cada [receita](pages/ponto_de_controle_3/lexico?id=receita), deve ser exibido o tempo estimado de [preparo da receita](pages/ponto_de_controle_3/lexico?id=preparar-receita) | MUST |
| RF012 | Na página de cada [receita](pages/ponto_de_controle_3/lexico?id=receita), na sessão de [passo a passo](pages/ponto_de_controle_3/lexico?id=passo), pode haver dicas entre os [passos](pages/ponto_de_controle_3/lexico?id=passo), sinalizado a melhor maneira de se realizar o [passo](pages/ponto_de_controle_3/lexico?id=passo) | SHOULD |
| RF013 | Na página de cada [receita](pages/ponto_de_controle_3/lexico?id=receita), deve haver a opção de [compartilhar uma receita](pages/ponto_de_controle_3/lexico?id=compartilhar-receita) | SHOULD |
| RF014 | Na página de cada [receita](pages/ponto_de_controle_3/lexico?id=receita), deve haver uma sessão de sugestões, onde será sugerido as melhores bebidas que combinam com determinada [receita](pages/ponto_de_controle_3/lexico?id=receita) | COULD |
| RF015 | Toda [receita](pages/ponto_de_controle_3/lexico?id=receita) deve possuir uma avaliação associada, e essa avaliação deve ser apresentada sempre que a [receita](pages/ponto_de_controle_3/lexico?id=receita) for exibida | SHOULD |
| RF016 | Na página de cada [receita](pages/ponto_de_controle_3/lexico?id=receita), deve existir a opção de [avaliar a receita](pages/ponto_de_controle_3/lexico?id=avaliar-receita) | MUST |
| RF017 | Na página de cada [receita](pages/ponto_de_controle_3/lexico?id=receita), deve existir a opção de favoritar a [receita](pages/ponto_de_controle_3/lexico?id=receita) | SHOULD |
| RF018 | Na página de cada [receita](pages/ponto_de_controle_3/lexico?id=receita), deve existir a opção de desfavoritar a [receita](pages/ponto_de_controle_3/lexico?id=receita) | SHOULD |
| RF019 | Em algum lugar do APP deve ser possível ver todas as [receitas](pages/ponto_de_controle_3/lexico?id=receita) que já foram favoritadas pelo [usuário](pages/ponto_de_controle_3/lexico?id=usuário) | SHOULD |
| RF020 | Na página de cada [receita](pages/ponto_de_controle_3/lexico?id=receita), deve existir uma sessão de avaliações, onde será exibido todas as avaliações feitas até então | SHOULD |
| RF021 | Na página de [pesquisa de receitas](pages/ponto_de_controle_3/lexico?id=pesquisar-receita), deve existir um filtro para exibir somente as [receitas](pages/ponto_de_controle_3/lexico?id=receita) acima de um certa avaliação | SHOULD |
| RF022 | Na página de [pesquisa de receitas](pages/ponto_de_controle_3/lexico?id=pesquisar-receita), deve existir um filtro para selecionar o fator predominante na [receita](pages/ponto_de_controle_3/lexico?id=receita), sendo que o fator é um [ingrediente](pages/ponto_de_controle_3/lexico?id=ingrediente) irá predominar sobre os demais | SHOULD |
| RF023 | Na página de [pesquisa de receitas](pages/ponto_de_controle_3/lexico?id=pesquisar-receita), deve ser possível [pesquisar receitas](pages/ponto_de_controle_3/lexico?id=pesquisar-receita) pelo nome | MUST |
| RF024 | Caso uma [receita](pages/ponto_de_controle_3/lexico?id=receita) seja de um Chef, deve existir a opção de visualizar o perfil do Chef, e nesse perfil deve exibir informações como: nome, local onde trabalha, experiência, número de seguidores, número de [receitas](pages/ponto_de_controle_3/lexico?id=receita) curtidas, etc | COULD |
| RF025 | Na página de perfil de um Chef deve existir a opção de seguir o Chef | COULD |
| RF026 | Na página de perfil de um Chef deve existir a opção de deixar de seguir o Chef | COULD |
| RF027 | Na página de perfil de um Chef deve existir a opção de avaliar o Chef | COULD |
| RF028 | Na página de perfil de um Chef, deve exibir a média das avaliações e a quantidade de avaliações do chefe | COULD |
| RF029 | O [aplicativo](pages/ponto_de_controle_3/lexico?id=aplicativo) deve ter a opção de [criar uma nova conta](pages/ponto_de_controle_3/lexico?id=fazer-cadastro), utilizando email e senha | MUST |
| RF030 | Após [criar uma nova conta](pages/ponto_de_controle_3/lexico?id=fazer-cadastro) utilizando email e senha, deve ser enviado um email de confirmação, com um link, para o email definido. Enquanto o link não for clicado a [conta](pages/ponto_de_controle_3/lexico?id=conta) deve permanecer como "não verificada" | SHOULD |
| RF031 | O [aplicativo](pages/ponto_de_controle_3/lexico?id=aplicativo) deve ter a opção de [criar uma nova conta](pages/ponto_de_controle_3/lexico?id=fazer-cadastro), utilizando a [conta](pages/ponto_de_controle_3/lexico?id=conta) do Google ou Facebook | SHOULD |
| RF033 | O [aplicativo](pages/ponto_de_controle_3/lexico?id=aplicativo) deve ter a opção de realizar [login](pages/ponto_de_controle_3/lexico?id=fazer-login) com uma [conta](pages/ponto_de_controle_3/lexico?id=conta) existente, utilizando email e senha | MUST |
| RF034 | Na tela de login, deve haver a opção de recuperar senha | MUST |
| RF035 | O [aplicativo](pages/ponto_de_controle_3/lexico?id=aplicativo) deve ter a opção de relizar [login](pages/ponto_de_controle_3/lexico?id=fazer-login) utilizando a [conta](pages/ponto_de_controle_3/lexico?id=conta) do Google ou Facebook | SHOULD |
| RF036 | O [aplicativo](pages/ponto_de_controle_3/lexico?id=aplicativo) deve ter a opção de modificar o nome, email e senha da conta existente | MUST |
| RF037 | O [aplicativo](pages/ponto_de_controle_3/lexico?id=aplicativo) deve ter a opção de excluir uma [conta](pages/ponto_de_controle_3/lexico?id=conta) existente | MUST |
| RF038 | O [aplicativo](pages/ponto_de_controle_3/lexico?id=aplicativo) deve ter a opção de modificar a unidade de medida escolhida (medida imperial, medida métrica) | MUST |
| RF039 | O [aplicativo](pages/ponto_de_controle_3/lexico?id=aplicativo) deve ter a opção de registrar as preferências culinárias (pizza, sopas, tortas, etc) | SHOULD |
| RF040 | O [aplicativo](pages/ponto_de_controle_3/lexico?id=aplicativo) deve ter a opção de modificar as preferências culinárias (pizza, sopas, tortas, etc) | SHOULD |
| RF041 | O [aplicativo](pages/ponto_de_controle_3/lexico?id=aplicativo) deve ter a opção de registrar as [restrições alimentáres](pages/ponto_de_controle_3/lexico?id=restrição-alimentar) do [usuário](pages/ponto_de_controle_3/lexico?id=usuário) | MUST |
| RF042 | O [aplicativo](pages/ponto_de_controle_3/lexico?id=aplicativo) deve ter a opção de modificar as [restrições alimentáres](pages/ponto_de_controle_3/lexico?id=restrição-alimentar) do [usuário](pages/ponto_de_controle_3/lexico?id=usuário) | MUST |
| RF043 | Na página de [pesquisa de receitas](pages/ponto_de_controle_3/lexico?id=pesquisar-receita), deve ser possível filtrar as [receitas](pages/ponto_de_controle_3/lexico?id=receita) pelos [ingredientes](pages/ponto_de_controle_3/lexico?id=ingrediente) disponíveis | MUST |
| RF044 | A lista de resultados exibidas para o [usuário](pages/ponto_de_controle_3/lexico?id=usuário) deve levar em consideração as preferências culinárias do [usuário](pages/ponto_de_controle_3/lexico?id=usuário) | MUST |
| RF045 | Na página de [pesquisa de receitas](pages/ponto_de_controle_3/lexico?id=pesquisar-receita), deve ser possível filtrar as [receitas](pages/ponto_de_controle_3/lexico?id=receita) pelo Chef que cadastrou a [receita](pages/ponto_de_controle_3/lexico?id=receita) | COULD |
| RF046 | Na página de [pesquisa de receitas](pages/ponto_de_controle_3/lexico?id=pesquisar-receita), deve ser possível filtrar as [receitas](pages/ponto_de_controle_3/lexico?id=receita) com base na estação do ano | COULD |
| RF047 | O [aplicativo](pages/ponto_de_controle_3/lexico?id=aplicativo) deve ter uma sessão de agendar uma [refeição](pages/ponto_de_controle_3/lexico?id=comida) , desse modo o [usuário](pages/ponto_de_controle_3/lexico?id=usuário) poderá programar qual dia irá fazer qual [receita](pages/ponto_de_controle_3/lexico?id=receita) | COULD |
| RF048 | O [usuário](pages/ponto_de_controle_3/lexico?id=usuário) deve poder modificar a data agendada de uma determinada [refeição](pages/ponto_de_controle_3/lexico?id=comida)  | COULD |
| RF049 | O [usuário](pages/ponto_de_controle_3/lexico?id=usuário) deve poder remover uma [receita](pages/ponto_de_controle_3/lexico?id=receita) que foi agendada para uma determinada data | COULD |
| RF050 | O [usuário](pages/ponto_de_controle_3/lexico?id=usuário) deve poder compartilhar o planejamento de [refeições](pages/ponto_de_controle_3/lexico?id=comida)  agendadas de uma determinada semana ou mês | COULD |
| RF051 | Na página de [refeições](pages/ponto_de_controle_3/lexico?id=comida)  cadastradas deve ser possível cancelar um agendamento de [refeição](pages/ponto_de_controle_3/lexico?id=comida)  | COULD |
| RF052 | O [aplicativo](pages/ponto_de_controle_3/lexico?id=aplicativo) deve ter uma sessão para gerar uma lista de compras com base nas [receitas](pages/ponto_de_controle_3/lexico?id=receita) que foram programadas para a semana ou para o mês | COULD |
| RF053 | Na página da lista de compras, deve ser possível remover produtos da lista de compras | COULD |
| RF054 | Na página da lista de compras, devem haver blocos de notas, para lembrar de algo | WANT |
| RF055 | Em uma determinada lista de compras, deve ser possível marcar os [alimentos](pages/ponto_de_controle_3/lexico?id=comida)  que já foram adquiridos | COULD |
| RF056 | Deve ser possível compartilhar uma lista de compras | COULD |
| RF057 | Na página da lista de compras, deve ser possível adicionar produtos da lista de compras | COULD |
| RF058 | Na página de configurações do [aplicativo](pages/ponto_de_controle_3/lexico?id=aplicativo), deve ser possível de mudar a linguagem do APP (portugues, ingles, espanhol, frances, ...) | MUST |
| RF059 | Ao selecionar uma nova linguagem, a linguagem do [aplicativo](pages/ponto_de_controle_3/lexico?id=aplicativo) deve mudar para a opção selecionada | MUST |
| RF060 | Na página de configurações do [aplicativo](pages/ponto_de_controle_3/lexico?id=aplicativo), deve ser possível escolher o tema do [aplicativo](pages/ponto_de_controle_3/lexico?id=aplicativo) (modo claro e modo escuro) | WANT |
| RF061 | Na página de configurações do [aplicativo](pages/ponto_de_controle_3/lexico?id=aplicativo), deve ser possível apagar a [conta](pages/ponto_de_controle_3/lexico?id=conta) do [usuário](pages/ponto_de_controle_3/lexico?id=usuário) | MUST |
| RF062 | Quando um novo [usuário](pages/ponto_de_controle_3/lexico?id=usuário) acessar o [aplicativo](pages/ponto_de_controle_3/lexico?id=aplicativo) pela primeira vez, o [aplicativo](pages/ponto_de_controle_3/lexico?id=aplicativo) deve iniciar com o modo Tour, onde o [aplicativo](pages/ponto_de_controle_3/lexico?id=aplicativo) irá guiar a navegação, apresentando as principais sessões do APP | MUST |
| RF063 | Na página de perfil do [usuário](pages/ponto_de_controle_3/lexico?id=usuário), deve haver opção de exibir o histórico de [receitas](pages/ponto_de_controle_3/lexico?id=receita) curtidas e [receitas](pages/ponto_de_controle_3/lexico?id=receita) visitadas pelo [usuário](pages/ponto_de_controle_3/lexico?id=usuário) | SHOULD |
| RF064 | De tempos em tempos deve ser exibido um popup solicitando a avaliação do [aplicativo](pages/ponto_de_controle_3/lexico?id=aplicativo) pelo [usuário](pages/ponto_de_controle_3/lexico?id=usuário), caso ainda não tenha sido avaliado | COULD |
| RF065 | Deve ser possível utilizar o [aplicativo](pages/ponto_de_controle_3/lexico?id=aplicativo) mesmo sem [estar logado](pages/ponto_de_controle_3/lexico?id=estar-logado) ou possuir uma [conta](pages/ponto_de_controle_3/lexico?id=conta). Quando o [aplicativo](pages/ponto_de_controle_3/lexico?id=aplicativo) for aberto, se não existir um [usuário](pages/ponto_de_controle_3/lexico?id=usuário) logado deve existir uma opção para acessar sem login | MUST |
| RF066 | [Usuários](pages/ponto_de_controle_3/lexico?id=usuário) que nunca tiveram uma assitura [Premium](pages/ponto_de_controle_3/lexico?id=premium) devem poder experimentar a assinatura [Premium](pages/ponto_de_controle_3/lexico?id=premium) durante 7 dias | COULD |
| RF067 | Os [usuáros](pages/ponto_de_controle_3/lexico?id=usuário) devem poder obter a assinatura [Premium](pages/ponto_de_controle_3/lexico?id=premium) após a confirmação do pagamento | MUST |
| RF068 | Deve ser mostrado [anúncios](pages/ponto_de_controle_3/lexico?id=anúncio) para [usuários](pages/ponto_de_controle_3/lexico?id=usuário) Freemium, e não deve ser mostrado [anúncios](pages/ponto_de_controle_3/lexico?id=anúncio) para [usuários](pages/ponto_de_controle_3/lexico?id=usuário) que tiverem assinatura [Premium](pages/ponto_de_controle_3/lexico?id=premium) | MUST |
| RF069 | [Usuários](pages/ponto_de_controle_3/lexico?id=usuário) Freemium devem ter um limite de [receitas](pages/ponto_de_controle_3/lexico?id=receita) que podem ser consultadas no dia. [Usuários](pages/ponto_de_controle_3/lexico?id=usuário) [Premium](pages/ponto_de_controle_3/lexico?id=premium) não possuem essas limitações | SHOULD |
| RF070 | Durante períodos excepcionais (promoções, datas comemorativas, pandemias, etc) deve ser liberado assinaturas [Premium](pages/ponto_de_controle_3/lexico?id=premium) para todos os [usuários](pages/ponto_de_controle_3/lexico?id=usuário) | COULD|
| RF071 | Para [usuários](pages/ponto_de_controle_3/lexico?id=usuário) que acabaram de criar a [conta](pages/ponto_de_controle_3/lexico?id=conta), deve ser perguntado qual o objetivo do [usuário](pages/ponto_de_controle_3/lexico?id=usuário) (Comer mais vegetais, Esvaziar a geladeira, Descobrir novas [receitas](pages/ponto_de_controle_3/lexico?id=receita), Comer [comidas saudáveis](pages/ponto_de_controle_3/lexico?id=saudável) ) | SHOULD |
| RF072 | Para [usuários](pages/ponto_de_controle_3/lexico?id=usuário) que acabaram de criar a [conta](pages/ponto_de_controle_3/lexico?id=conta), deve ser perguntado se o[usuário](pages/ponto_de_controle_3/lexico?id=usuário) possui alguma [restrição alimentar](pages/ponto_de_controle_3/lexico?id=restrição-alimentar) (Alergias, Intolerâncias, não consumo de produtos de animais, etc) | MUST |
| RF073 | Para [usuários](pages/ponto_de_controle_3/lexico?id=usuário) que acabaram de criar a [conta](pages/ponto_de_controle_3/lexico?id=conta), deve ser perguntado quais são os pratos favoritos do [usuário](pages/ponto_de_controle_3/lexico?id=usuário) (Macarrão, Lasanhas, Saladas, etc) | MUST |
| RF074 | Para [usuários](pages/ponto_de_controle_3/lexico?id=usuário) que acabaram de criar a [conta](pages/ponto_de_controle_3/lexico?id=conta), deve ser perguntado qual a lingua que o APP deve ser configurado | WON'T |
| RF075 | Para [usuários](pages/ponto_de_controle_3/lexico?id=usuário) que acabaram de criar a [conta](pages/ponto_de_controle_3/lexico?id=conta), deve ser perguntado qual a unidade de medida (imperial, métrica) o APP deve ser configurado | WON'T |
| RF076 | Em algum lugar do APP deve ser possível ver todas as [receitas](pages/ponto_de_controle_3/lexico?id=receita) que já foram favoritadas pelo [usuário](pages/ponto_de_controle_3/lexico?id=usuário) | SHOULD |
| RF077 | Antes de apresentar qualquer [receita](pages/ponto_de_controle_3/lexico?id=receita), deve ser perguntado ao [usuário](pages/ponto_de_controle_3/lexico?id=usuário) se ele tem alguma [restrição alimentar](pages/ponto_de_controle_3/lexico?id=restrição-alimentar) | WON'T |
| RF078 | Deve existir a opção de selecionar [receitas](pages/ponto_de_controle_3/lexico?id=receita) genéricas (Pizzas, omeletes, sopas, etc), onde o [usuário](pages/ponto_de_controle_3/lexico?id=usuário) irá receber uma [receita](pages/ponto_de_controle_3/lexico?id=receita) adaptada com base nos [ingredientes](pages/ponto_de_controle_3/lexico?id=ingrediente) selecionados | COULD |
| RF079 | Na página de busca de [receitas](pages/ponto_de_controle_3/lexico?id=receita), deve ser possível definir qual será o [aroma](pages/ponto_de_controle_3/lexico?id=aroma)  da [receita](pages/ponto_de_controle_3/lexico?id=receita) desejada | COULD |
| RF080 | Antes de gerar uma [receita](pages/ponto_de_controle_3/lexico?id=receita) para o [usuário](pages/ponto_de_controle_3/lexico?id=usuário), deve ser exibido a lista de [ingredientes](pages/ponto_de_controle_3/lexico?id=ingrediente) selecionados e solicitado a confirmação | MUST |
| RF081 | Antes de gerar uma [receita](pages/ponto_de_controle_3/lexico?id=receita) para o [usuário](pages/ponto_de_controle_3/lexico?id=usuário), deve ser apresentado a [roda dos sabores](pages/ponto_de_controle_3/lexico?id=roda-de-sabores) básicos do paladar humano (Doce, Salgado, Azedo, Amargo, Umami), onde cada [ingrediente](pages/ponto_de_controle_3/lexico?id=ingrediente) será categorizado em uma parte da roda, e será solicitado a confirmação do [usuário](pages/ponto_de_controle_3/lexico?id=usuário). Nessa etapa, o [usuário](pages/ponto_de_controle_3/lexico?id=usuário) pode adicionar novos [ingredientes](pages/ponto_de_controle_3/lexico?id=ingrediente) de acordo com os [sabores](pages/ponto_de_controle_3/lexico?id=sabores) que estão faltando | COULD |
| RF082 | Antes de gerar uma [receita](pages/ponto_de_controle_3/lexico?id=receita) para o [usuário](pages/ponto_de_controle_3/lexico?id=usuário), deve ser apresentado um [score](pages/ponto_de_controle_3/lexico?id=score) da [receita](pages/ponto_de_controle_3/lexico?id=receita) que será gerada, de acordo com os [ingredientes](pages/ponto_de_controle_3/lexico?id=ingrediente) que foram selecionados | SHOULD |
| RF083 | Antes de gerar uma [receita](pages/ponto_de_controle_3/lexico?id=receita) para o [usuário](pages/ponto_de_controle_3/lexico?id=usuário), caso o [score](pages/ponto_de_controle_3/lexico?id=score) seja muito baixo o APP deve intervir e perguntar se o [usuário](pages/ponto_de_controle_3/lexico?id=usuário) não deseja realizar determinada alteração na [receita](pages/ponto_de_controle_3/lexico?id=receita) | SHOULD |
| RF084 | Após a seleção e confirmação de todas as etapas de geração de [receita](pages/ponto_de_controle_3/lexico?id=receita), deve ser apresentado a [receita](pages/ponto_de_controle_3/lexico?id=receita) de acordo com os [ingredientes](pages/ponto_de_controle_3/lexico?id=ingrediente) definidos | MUST |
| RF085 | O [usuário](pages/ponto_de_controle_3/lexico?id=usuário) deve poder selecionar e visualizar uma [receita](pages/ponto_de_controle_3/lexico?id=receita) já existente | MUST |
| RF086 | O [usuário](pages/ponto_de_controle_3/lexico?id=usuário) deve poder criar/cadastrar uma [receita](pages/ponto_de_controle_3/lexico?id=receita) no APP | SHOULD |
| RF087 | Na [receita](pages/ponto_de_controle_3/lexico?id=receita) que o [usuário](pages/ponto_de_controle_3/lexico?id=usuário) está executando deve haver a opção de selecionar os [passos](pages/ponto_de_controle_3/lexico?id=passo) que já foram executados | SHOULD |
| RF088 | O [usuário](pages/ponto_de_controle_3/lexico?id=usuário) deve poder agrupar as [receitas](pages/ponto_de_controle_3/lexico?id=receita) em pastas (por exemplo: pasta doces, pasta salgados, pasta "gluten free") | COULD |
| RF089 | Na página de pesquisa deve ser possível encontrar pastas criadas por outros [usuários](pages/ponto_de_controle_3/lexico?id=usuário) | COULD |
| RF090 | Na parte de configurações deve existir a opção de convidar/[compartilhar o aplicativo](pages/ponto_de_controle_3/lexico?id=compartilhar-aplicativo) com outros [usuários](pages/ponto_de_controle_3/lexico?id=usuário) | SHOULD |
| RF091 | O [aplicativo](pages/ponto_de_controle_3/lexico?id=aplicativo) deve possuir uma sessão de anotações, onde os [usuários](pages/ponto_de_controle_3/lexico?id=usuário) poderão deixar seus lembretes | WANT |
| RF092 | Na página de perfil do [usuário](pages/ponto_de_controle_3/lexico?id=usuário), deve ter a opção de visualizar o [quadro nutricional](pages/ponto_de_controle_3/lexico?id=quadro-nutricional) do [usuário](pages/ponto_de_controle_3/lexico?id=usuário), com base nas [receitas](pages/ponto_de_controle_3/lexico?id=receita) que o [usuário](pages/ponto_de_controle_3/lexico?id=usuário) preparou durante a semana e durante o mês | COULD |


## 4. Conclusão

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
